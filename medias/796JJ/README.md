<!-- dubline-subs {"title": "EECS4302 ANTLR4 Parser Generator Tutorial: Part 2", "author": "Jackie Wang", "files": 3, "updated": "2026-11-13"} -->
# EECS4302 ANTLR4 Parser Generator Tutorial: Part 2

<img src="cba032/625b6f6d/EECS4302%20ANTLR4%20Parser%20Generator%20Tutorial%20Part%202.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=cWUbZ0fCZB4](https://www.youtube.com/watch?v=cWUbZ0fCZB4) |
| 发布 | 2020-02-23 |
| 时长 | 45 分 41 秒 |
| 语言 | 英语 |
| 原作者 | [Jackie Wang](https://www.youtube.com/@jackiechenweiwang)（@jackiechenweiwang，2570 订阅） |

## 中文信息

**标题**：【中配】45 分钟演示用 ANTLR4 手写一个表达式解析器

**原标题译文**：EECS4302 ANTLR4 解析器生成器教程：第 2 部分

这期视频将带你深入了解如何利用 ANTLR4 工具链从零开始构建一个功能完整的表达式解析器。我们将通过一个完整的实战案例，演示从最初的语法规范编写到最终生成可运行代码的全流程。无论你是想深入研究编译器原理，还是在实际项目中需要处理复杂的解析逻辑，这期视频提供的实操演示都能为你提供清晰的路径参考。

在视频中，我们将涵盖从基础到进阶的多个核心知识点。首先，我们将学习如何使用 ANTLR4 命令行工具将 .g4 语法规范文件转换为 Java 词法分析器和解析器类。你会看到具体的 exprParser.java 和 exprLexer.java 是如何生成的，以及这些生成文件在项目中的基本角色。接着，我们将深入探讨语法规则的设计技巧，特别是如何在产生式规则中通过调整分支的先后顺序来模拟运算符的优先级，例如确保乘法在加法中具有更高的优先级。

此外，视频还会详细讲解一些容易被忽略但至关重要的细节。例如，为了启用 ANTLR4 的错误处理机制，必须在语法顶层添加 EOF 文件结束符，并学习如何利用 grun 工具运行测试用例，从而准确定位到诸如冒号后缺少类型等具体的语法错误，并获取精确的行号和列号信息。我们还会讨论 ANTLR4 的默认配置，包括它如何自动处理注释和空白符，从而简化你的语法定义。

在代码生成阶段，我们将对比两种主流的模式：默认的监听器模式和通过 -visitor 参数生成的访问者模式。我们将演示如何配置访问者接口及其实现类，以实现更灵活的逻辑转换。同时，视频也会提醒大家在实际开发中的注意事项，比如生成的 Java 文件必须放置在正确的包结构中以避免命名冲突，以及在修改 .g4 文件后必须重新运行生成命令以确保所有依赖类同步更新。最后，我们将展示如何将解析树转换为自定义对象的实例化过程，这是在编译器中实现灵活逻辑转换的关键步骤。

本视频非常适合正在学习编译器原理、需要构建解析器的开发者，以及具备 Java 编程基础并希望掌握抽象语法树概念的技术人员观看。通过这期视频的学习，你将能够掌握 ANTLR4 的工具链基础用法和高级配置技巧。看完视频后，你将具备从零开始编写 .g4 语法文件、配置优先级规则、利用 grun 工具进行语法测试、生成并调用访问者模式代码的能力。你将能够独立完成从原始语法定义到解析树构建，再到自定义对象转换的完整解析流程，为构建复杂的编译器或解析工具打下坚实的基础。

原视频：EECS4302 ANTLR4 Parser Generator Tutorial: Part 2
原作者：Jackie Wang
发布日期：2020-02-23
视频链接：https://www.youtube.com/watch?v=cWUbZ0fCZB4

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](cba032/153b59c2/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/796JJ/cba032/153b59c2/dubbed.srt) |
| EECS4302 ANTLR4 Parser Generator Tutorial Part 2 - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](cba032/602a2132/EECS4302%20ANTLR4%20Parser%20Generator%20Tutorial%20Part%202%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/796JJ/cba032/602a2132/EECS4302%20ANTLR4%20Parser%20Generator%20Tutorial%20Part%202%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| EECS4302 ANTLR4 Parser Generator Tutorial Part 2 - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](cba032/d0b46f83/EECS4302%20ANTLR4%20Parser%20Generator%20Tutorial%20Part%202%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/796JJ/cba032/d0b46f83/EECS4302%20ANTLR4%20Parser%20Generator%20Tutorial%20Part%202%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频简介

iPad Notes: https://www.eecs.yorku.ca/~jackie/teaching/tutorials/notes/EECS4302%20Tutorial%20on%20ANTLR4%20Parser%20Generator.pdf
- What is ANTLR?
- Specifying Tokens, Production Rules, and Precedence
- Use of grun to Test Grammar

---

视频内容版权归原作者所有，字幕仅供学习交流。
