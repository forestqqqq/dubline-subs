<!-- dubline-subs {"title": "EECS4302 ANTLR4 Parser Generator Tutorial: Part 3", "author": "Jackie Wang", "files": 3, "updated": "2026-11-13"} -->
# EECS4302 ANTLR4 Parser Generator Tutorial: Part 3

<img src="9ef2e8/d8b1e5f9/EECS4302%20ANTLR4%20Parser%20Generator%20Tutorial%20Part%203.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=2o9ImGNI1uw](https://www.youtube.com/watch?v=2o9ImGNI1uw) |
| 发布 | 2020-02-23 |
| 时长 | 42 分 27 秒 |
| 语言 | 英语 |
| 原作者 | [Jackie Wang](https://www.youtube.com/@jackiechenweiwang)（@jackiechenweiwang，2570 订阅） |

## 中文信息

**标题**：【中配】42 分钟 EECS4302 项目：用 ANTLR4 把解析树变代码

**原标题译文**：EECS4302 ANTLR4 解析器生成器教程：第 3 部分

这期视频将带大家深入了解 EECS4302 课程中的一个核心项目，重点演示如何利用 ANTLR4 解析器将解析树高效地转换为自定义的模型对象。在编译器开发或语言处理过程中，直接操作复杂的解析树往往会导致代码逻辑混乱且难以调试。本视频的核心思路是引入一套自定义的模型类体系，通过解耦解析树结构与业务逻辑模型，来简化调试过程并更精准地控制对象结构。我们将全方位拆解从语法定义到对象构建的完整链路，帮助大家掌握从抽象语法树到具体程序模型的转化技术。

通过观看本视频，你可以掌握以下具体的知识点：

首先是关于模型类设计与对象构建的核心逻辑。视频详细讲解了如何使用 Expression、Number、Variable 等自定义模型类来替代直接操作解析树。通过这种方式，我们可以建立起清晰的层次结构，让程序的逻辑更加直观。核心逻辑遵循自底向上的原则：在转换过程中，程序会先处理叶子节点以创建基础对象，随后上层节点通过对应的 visit 方法将这些子对象链接起来。这种递归设计模式能够完美处理运算符优先级，确保生成的对象结构符合预期的逻辑嵌套。

其次是关于 ANTLR4 访问者模式（Visitor Pattern）的深度进阶技巧。视频会展示 ANTLR4 默认生成的 visitor 类虽然包含泛型接口和基于产生式规则自动生成的方法，但其默认实现的粒度往往较为粗糙，类型定义不够直观。为了解决这个问题，我们将学习如何在语法文件的产生式规则旁添加特定的标签，通过这种方式重新生成包含细粒度方法的自定义访问者类。这不仅能优化代码结构，还能让转换逻辑更加模块化。

此外，视频还会深入剖析泛型机制在转换过程中的应用。你会了解到 visit 方法的返回类型是如何与模板参数 t 一致的，从而实现内部节点到具体表达式的平滑转换。同时，我们还会分析 expression base visitor 的设计，它作为非抽象类继承自接口并实现了所有方法，这是手动实现具体 Visitor 类的关键基础。最后，视频还会展示组合模式（Combination Pattern）的宏观全貌，例如 Program 如何持有 Expression 列表来构建复杂的递归对象。

本视频非常适合正在学习编译原理或形式语言自动机的学生，同时也适合那些在实际开发中需要处理表达式解析、语法树转换等任务的开发者。如果你已经对 ANTLR4 生成器以及访问者模式有了基础的认知，那么这期视频将为你提供从理论到实践的深度进阶指导。

看完这期视频后，你将能够独立完成从 ANTLR4 解析树到自定义模型对象的转换流程。你不仅能学会如何设计合理的模型类层次结构，还能掌握通过修改语法标签来定制化生成访问者类的实战技巧。通过掌握自底向上的递归构建逻辑和泛型 visit 方法的配合，你将能够构建出结构清晰、易于调试的程序模型，从而在处理复杂的语言解析任务时游刃有余。

原视频：EECS4302 ANTLR4 Parser Generator Tutorial: Part 3
原作者：Jackie Wang
发布日期：2020-02-23
视频链接：https://www.youtube.com/watch?v=2o9ImGNI1uw

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| EECS4302 ANTLR4 Parser Generator Tutorial Part 3 - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](9ef2e8/7aa6b61c/EECS4302%20ANTLR4%20Parser%20Generator%20Tutorial%20Part%203%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/CPW0N/9ef2e8/7aa6b61c/EECS4302%20ANTLR4%20Parser%20Generator%20Tutorial%20Part%203%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](9ef2e8/9fac74ca/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/CPW0N/9ef2e8/9fac74ca/dubbed.srt) |
| EECS4302 ANTLR4 Parser Generator Tutorial Part 3 - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](9ef2e8/b9271e2b/EECS4302%20ANTLR4%20Parser%20Generator%20Tutorial%20Part%203%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/CPW0N/9ef2e8/b9271e2b/EECS4302%20ANTLR4%20Parser%20Generator%20Tutorial%20Part%203%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频简介

iPad Notes: https://www.eecs.yorku.ca/~jackie/teaching/tutorials/notes/EECS4302%20Tutorial%20on%20ANTLR4%20Parser%20Generator.pdf
- AntlrExampleVisitor Project
- Design and Implementation of model classes in `expression`: Expression, Number, Variable Declaration, Variable, Multiplication, Addition, Program
- Idea about building model objects while visiting the parse tree
- Examine: Default generated Visitor Classes (interface and implementing class)
- Add labels to alternatives in grammar file, re-generate all files
- Examine: Re-generated Visitor Classes (names matching labels)

---

视频内容版权归原作者所有，字幕仅供学习交流。
