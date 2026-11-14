<!-- dubline-subs {"title": "EECS4302 ANTLR4 Parser Generator Tutorial: Part 1", "author": "Jackie Wang", "files": 3, "updated": "2026-11-14"} -->
# EECS4302 ANTLR4 Parser Generator Tutorial: Part 1

<img src="6bac34/804569e8/EECS4302%20ANTLR4%20Parser%20Generator%20Tutorial%20Part%201.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=-FdD_xzNFL4](https://www.youtube.com/watch?v=-FdD_xzNFL4) |
| 发布 | 2020-02-23 |
| 时长 | 9 分 55 秒 |
| 语言 | 英语 |
| 原作者 | [Jackie Wang](https://www.youtube.com/@jackiechenweiwang)（@jackiechenweiwang，2570 订阅） |

## 中文信息

**标题**：【中配】9分钟搞定ANTLR4环境配置，从下载到Eclipse调通

**原标题译文**：EECS4302 ANTLR4 解析器生成器教程：第一部分

欢迎来到我的频道，这是关于 ANTLR4 解析器生成工具系列教程的第一期内容。很多同学在开始学习编译器原理或者语法解析时，往往会被复杂的环境配置卡住，甚至在第一步就因为找不到路径或者库冲突而放弃。本期视频的核心目的就是带大家彻底打通 ANTLR4 的开发环境，从零开始讲解如何在不同操作系统上安装工具，并演示如何在 Eclipse IDE 中正确配置 Java 项目的库路径和原生库位置，确保你的开发环境能够顺利跑通。

通过这期视频，你将学到以下具体的知识点：
首先，我将带你访问 ANTLR4 官方资源，了解快速入门指南、不同平台的安装说明以及权威的指南书籍。我们将以 ANTLR4 4.8 版本为例，演示在 Windows、Mac 和 Linux 系统下的下载与安装流程。
其次，视频将详细讲解项目结构的规范化搭建。为了保证后续开发的顺利，我们需要在项目根目录下创建 lib、bin 和 source 文件夹，并确保这些文件夹与项目其他核心文件处于同级位置。
接着，我会重点演示在 Eclipse IDE 中的关键配置步骤。这包括如何在项目的库路径中引入必要的 Java jar 文件，以及如何在源路径下正确配置原生库位置。这是很多新手容易忽略但至关重要的步骤，配置不当会导致解析器无法正常运行。
最后，我将教大家如何进行工具验证。通过在命令行输入 antlr4 和 grun 命令，我们可以直观地确认工具是否已经成功安装到系统的环境变量路径中。此外，我还会简单预告后续课程将涉及的核心概念，包括如何利用访问者模式来处理语法树，以及 Action 语法的基本应用。

这期视频非常适合想要学习使用 ANTLR4 构建解析器的开发者，或者是正在修读软件工程课程、需要掌握语法分析技术的学生。如果你已经具备基础的 Java 编程知识，并且熟悉 Eclipse IDE 的基本操作，那么这期视频将是你进入 ANTLR4 世界的最佳起点。

看完这期视频后，你将能够独立完成 ANTLR4 开发环境的搭建。你不仅能掌握从官方渠道获取正确工具包的方法，还能学会如何规范化管理项目文件结构，并能在 Eclipse 中准确配置复杂的库路径和原生库路径。最重要的是，通过最后的命令行验证步骤，你可以确保自己的开发环境已经完全准备就绪，能够顺利进入到后续的解析器编写和语法树处理阶段。无论你是为了完成学术作业，还是为了开发自己的编译器或 DSL 工具，这期视频都将为你扫清第一道技术障碍。

原视频：EECS4302 ANTLR4 Parser Generator Tutorial: Part 1
原作者：Jackie Wang
发布日期：2020-02-23
视频链接：https://www.youtube.com/watch?v=-FdD_xzNFL4

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](6bac34/02594465/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/9EKJ8/6bac34/02594465/dubbed.srt) |
| EECS4302 ANTLR4 Parser Generator Tutorial Part 1 - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](6bac34/6bb823a8/EECS4302%20ANTLR4%20Parser%20Generator%20Tutorial%20Part%201%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/9EKJ8/6bac34/6bb823a8/EECS4302%20ANTLR4%20Parser%20Generator%20Tutorial%20Part%201%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |
| EECS4302 ANTLR4 Parser Generator Tutorial Part 1 - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](6bac34/923c5b07/EECS4302%20ANTLR4%20Parser%20Generator%20Tutorial%20Part%201%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/9EKJ8/6bac34/923c5b07/EECS4302%20ANTLR4%20Parser%20Generator%20Tutorial%20Part%201%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频简介

iPad Notes: https://www.eecs.yorku.ca/~jackie/teaching/tutorials/notes/EECS4302%20Tutorial%20on%20ANTLR4%20Parser%20Generator.pdf
- Installation of antlr4 and grun,
- Setting Up Two Java Projects in Eclipse,
- References: ANTLR website and Book

---

视频内容版权归原作者所有，字幕仅供学习交流。
