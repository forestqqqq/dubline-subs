<!-- dubline-subs {"title": "EECS4302 ANTLR4 Parser Generator Tutorial: Part 7", "author": "Jackie Wang", "files": 3, "updated": "2026-11-13"} -->
# EECS4302 ANTLR4 Parser Generator Tutorial: Part 7

<img src="752a50/650e53bf/EECS4302%20ANTLR4%20Parser%20Generator%20Tutorial%20Part%207.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=7L0R1-5nbNg](https://www.youtube.com/watch?v=7L0R1-5nbNg) |
| 发布 | 2020-02-23 |
| 时长 | 1 小时 0 分 11 秒 |
| 语言 | 英语 |
| 原作者 | [Jackie Wang](https://www.youtube.com/@jackiechenweiwang)（@jackiechenweiwang，2570 订阅） |

## 中文信息

**标题**：【中配】1 小时实测 ANTLR4:用 Action 模式直接构建程序对象

**原标题译文**：EECS4302 ANTLR4 解析器生成器教程：第 7 部分

这期视频将带你深入实测 ANTLR4 解析器中的核心技术选型：Action 模式与传统的 Visitor 访问者模式。我们将通过实际的代码演示，对比在移除 Visitor 监听器后，如何利用 Action 模式直接在语法文件中定义语义动作，从而同步构建程序对象。视频将从基础的配置差异出发，逐步深入到复杂的递归处理与属性管理，帮助你理清两种模式在代码生成、执行效率以及设计复杂度上的本质区别，并为你提供在不同项目规模下的架构决策建议。

通过本期视频的学习，你将掌握以下具体的知识点：

首先是 Action 模式的基础配置与核心操作。你将学习如何通过使用 -no-listener 选项来禁用 ANTLR4 默认生成的监听器，从而强制解析器使用内联的 Java 代码来处理语义逻辑。你会看到如何在语法文件的规则块中直接编写 Java 代码，实现诸如构建数字节点、变量声明等具体的程序对象构建逻辑。

其次是关于词法单元与非终结符的引用规范。在 Action 模式下，正确的引用格式至关重要。视频将详细讲解必须使用 $id 格式（例如 $E、$text、$left 或 $right）来引用词法单元和非终结符的规则，避免因引用错误导致的语法错误或属性访问失败。同时，你还将学习如何在递归规则中遵循特定的命名约定，确保子节点对象能够正确传递。

第三是关于解析流程与对象构建的并发优化。我们将对比两种模式的执行流：Visitor 模式通常需要先构建完整的抽象语法树（AST）然后再进行遍历，而 Action 模式可以在解析过程中同步构建对象。你将学会如何通过 parser.program 直接获取完整的程序对象，从而跳过中间的 AST 遍历步骤，提升执行效率。此外，视频还会演示如何在 Action 中处理一个或多个规则时，如何先初始化程序对象，再通过条件判断将子节点累加到程序中。

最后是关于工程实践的设计建议。我们将深入分析两种模式在错误报告、对象构建顺序以及全局属性管理上的优劣。你会了解到，虽然 Action 模式将所有逻辑集中在语法文件中便于统一管理，但在面对复杂项目时，为了符合访问者设计模式并保持代码的可维护性，何时应该回归到 Visitor 模式，以及如何避免通过不断增加父类来支持新操作等实战经验，本视频都会为你提供清晰的指导。

本视频非常适合以下人群观看：
如果你是正在学习 ANTLR4 或需要编写自定义解析器的开发者，这期视频将为你提供极具价值的实战参考。如果你是技术人员，希望深入了解语义动作如何在语法文件中直接实现，或者希望通过对比 Visitor 与 Action 模式来优化你现有项目的代码生成效率，那么本期内容将直接切中你的需求。此外，如果你具备基础的 Java 编程知识，并且熟悉面向对象设计模式（如访问者模式、组合模式），本视频将帮助你更高效地完成解析器的架构设计。

看完本期视频后，你将能够熟练掌握如何在 ANTLR4 中配置并使用 Action 模式，能够准确编写符合规范的语义动作代码，并能够根据项目的实际规模和复杂度，在 Action 模式与 Visitor 模式之间做出科学的架构选择，从而构建出更高效、更易维护的解析器系统。

原视频：EECS4302 ANTLR4 Parser Generator Tutorial: Part 7
原作者：Jackie Wang
发布日期：2020-02-23
视频链接：https://www.youtube.com/watch?v=7L0R1-5nbNg

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| EECS4302 ANTLR4 Parser Generator Tutorial Part 7 - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](752a50/8340d766/EECS4302%20ANTLR4%20Parser%20Generator%20Tutorial%20Part%207%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/D04FD/752a50/8340d766/EECS4302%20ANTLR4%20Parser%20Generator%20Tutorial%20Part%207%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| EECS4302 ANTLR4 Parser Generator Tutorial Part 7 - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](752a50/8bc2b1eb/EECS4302%20ANTLR4%20Parser%20Generator%20Tutorial%20Part%207%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/D04FD/752a50/8bc2b1eb/EECS4302%20ANTLR4%20Parser%20Generator%20Tutorial%20Part%207%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](752a50/e907cbab/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/D04FD/752a50/e907cbab/dubbed.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频简介

iPad Notes: https://www.eecs.yorku.ca/~jackie/teaching/tutorials/notes/EECS4302%20Tutorial%20on%20ANTLR4%20Parser%20Generator.pdf
- AntlrExampleVisitor Project
- Adding semantic actions (effectively a visit method) to each production alternative 
- Re-generate the Java files  
- Reuse most of the model classes in `expression` package
- Retrieving model Expression object directly from the parser (no visit)
- Set up Run Configuration in Eclipse (file prompt) and run test cases on the console
- Export project as an executable JAR and run test cases on the command line prompt
- Comparison: Visitor vs. Action

---

视频内容版权归原作者所有，字幕仅供学习交流。
