<!-- dubline-subs {"title": "EECS4302 ANTLR4 Parser Generator Tutorial: Part 4", "author": "Jackie Wang", "files": 3, "updated": "2026-11-13"} -->
# EECS4302 ANTLR4 Parser Generator Tutorial: Part 4

<img src="da49da/75be7e73/EECS4302%20ANTLR4%20Parser%20Generator%20Tutorial%20Part%204.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=zo_oiHzKLqw](https://www.youtube.com/watch?v=zo_oiHzKLqw) |
| 发布 | 2020-02-23 |
| 时长 | 1 小时 3 分 8 秒 |
| 语言 | 英语 |
| 原作者 | [Jackie Wang](https://www.youtube.com/@jackiechenweiwang)（@jackiechenweiwang，2570 订阅） |

## 中文信息

**标题**：【中配】1 小时演示：用 ANTLR 自顶向下查错

**原标题译文**：EECS4302 ANTLR4 解析器生成器教程：第 4 部分

这期视频将带大家深入了解如何利用 ANTLR 生成的访问者模式（Visitor Pattern）来构建编译器或解释器的核心逻辑。我们将通过一个完整的实战演示，展示如何通过继承泛型基类，将复杂的语法解析树递归转换为语义对象，并在转换过程中高效地实现变量重复声明和未定义引用的语义错误检测。这不仅是一个关于工具使用的教程，更是一次关于编译器前端语义分析逻辑的深度实践。

在视频中，我们将涵盖以下核心知识点：

首先是关于访问者类（Visitor Class）的设计与实现。我们将学习如何继承 ExpressionBaseVisitor 泛型基类，并利用 Eclipse 等工具自动生成代码骨架，从而快速搭建起解析树遍历的框架。通过这种方式，我们可以将复杂的树结构遍历逻辑抽象出来，专注于具体的语义转换逻辑。

其次是关于自顶向下（Top-Down）遍历的核心逻辑及其在语义错误检测中的应用。在处理变量声明时，遍历顺序至关重要。通过自顶向下的遍历，我们可以按照代码的行号顺序维护已声明变量的列表。我们将演示如何利用 vars 私有列表来追踪变量的状态，通过检查子节点的 ID 和类型来精准判断是否存在重复声明或非法引用。

接着是关于如何构建二元运算对象。我们将讲解如何通过 ctx.getChild(index) 获取子树结构，在 visit 方法中递归调用 visit 方法，从而自动委托给子类执行。这种递归机制实现了树结构的深度优先遍历，让我们无需显式检查运算符即可构建出完整的表达式对象。

此外，视频还会重点讲解程序根节点的转换处理。程序根节点需要遍历所有非 EOF 子节点，并将转换后的对象收集到对应的列表中。同时，我们还会讨论如何确保语义错误信息包含精确的行号（Line）和列号（Column），这些信息可以通过词法单元的位置信息进行精确定位。

最后，我们还会深入探讨类型安全与架构设计。为了匹配目标模型类的继承层级，我们需要设计两个独立的访问者类。我们将讨论如何在构造函数中初始化语义错误列表，并在主程序中累加各子树的检测结果，确保整个转换过程的严谨性。

本视频非常适合以下人群观看：
如果你正在学习编译器原理，或者正在着手构建自己的解释器或编译器，这期视频提供的实战思路将对你非常有帮助。
如果你是一名熟悉 Java 泛型编程和面向对象设计模式（尤其是访问者模式）的程序员，通过本视频你可以快速掌握如何将这些模式应用于复杂的语法树处理任务中。
如果你是技术人员，正面临如何高效处理语法树到语义对象转换逻辑的难题，本视频提供的自顶向下查错思路将为你提供直接可用的解决方案。

看完本视频后，你将能够掌握如何使用 ANTLR 生成的访问者类来处理复杂的语法树。你不仅能学会如何利用泛型继承来简化代码编写，还能掌握如何通过自顶向下的遍历顺序来维护变量状态，从而在转换过程中自动检测出重复声明和未定义引用等语义错误。通过学习视频中的递归构建逻辑和根节点处理技巧，你将能够独立完成从语法解析树到语义对象的完整转换流程，并能够输出包含精确位置信息的错误报告，为构建稳健的编译器前端打下坚实的基础。

原视频：EECS4302 ANTLR4 Parser Generator Tutorial: Part 4
原作者：Jackie Wang
发布日期：2020-02-23
视频链接：https://www.youtube.com/watch?v=zo_oiHzKLqw

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](da49da/380cfaee/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/N9VVN/da49da/380cfaee/dubbed.srt) |
| EECS4302 ANTLR4 Parser Generator Tutorial Part 4 - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](da49da/8f241581/EECS4302%20ANTLR4%20Parser%20Generator%20Tutorial%20Part%204%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/N9VVN/da49da/8f241581/EECS4302%20ANTLR4%20Parser%20Generator%20Tutorial%20Part%204%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| EECS4302 ANTLR4 Parser Generator Tutorial Part 4 - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](da49da/9f7ccc0d/EECS4302%20ANTLR4%20Parser%20Generator%20Tutorial%20Part%204%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/N9VVN/da49da/9f7ccc0d/EECS4302%20ANTLR4%20Parser%20Generator%20Tutorial%20Part%204%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频简介

iPad Notes: https://www.eecs.yorku.ca/~jackie/teaching/tutorials/notes/EECS4302%20Tutorial%20on%20ANTLR4%20Parser%20Generator.pdf
- AntlrExampleVisitor Project
- Implementing Two Visitor Classes for Transforming Parse Trees to Expression Objects
- AntlrToProg extends ExprBaseVisitor[Prog]
- AntlrToExpr extends ExprBaseVisitor[Expr]

---

视频内容版权归原作者所有，字幕仅供学习交流。
