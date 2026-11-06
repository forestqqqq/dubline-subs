<!-- dubline-subs {"title": "IntelliJ Idea Plugin Development EP04", "author": "aptkode", "files": 3, "updated": "2026-11-06"} -->
# IntelliJ Idea Plugin Development EP04

<img src="3049de/56c8648b/IntelliJ%20Idea%20Plugin%20Development%20EP04.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=9o2kPEcIzio](https://www.youtube.com/watch?v=9o2kPEcIzio) |
| 发布 | 2019-09-16 |
| 时长 | 31 分 26 秒 |
| 语言 | 英语 |
| 原作者 | [aptkode](https://www.youtube.com/@aptkode)（@aptkode，805 订阅） |

## 中文信息

**标题**：【中配】31分钟带你搞定IntelliJ插件核心PSI与快速修复

**原标题译文**：IntelliJ Idea 插件开发 EP04

欢迎来到本期视频。如果你正在探索 IntelliJ IDEA 插件开发的深水区，那么理解 PSI 概念以及如何实现快速修复功能是必经之路。本期视频的核心目标是带你深入了解 IntelliJ IDEA 插件开发中的核心基石——PSI（Program Structure Interface）。我们将通过一个完整的实战项目，从基础的 PSI 概念解析开始，逐步过渡到复杂的依赖检索、多模块项目处理，最终落地到最实用的快速修复功能实现。通过这 31 分钟的教学，你将掌握如何构建一个能够自动检索依赖并提供自动化修复建议的插件，全方位提升你的插件开发能力。

在本次课程中，我们将涵盖以下核心知识点：

首先是 PSI 的深度解析。PSI 是 IntelliJ IDEA 中文件和元素（例如 Java 文件、XML 标签等）的虚拟结构表示。它是插件开发中处理代码逻辑的核心工具，通过 PSI，开发者可以轻松地遍历、定位和操作代码中的各种元素。我们将详细讲解 PSI 在插件开发中的核心作用，帮助你建立起对 IDE 内部数据结构的正确认知。

其次是依赖检索的实战技巧。我们将演示如何利用 NewMainArtifactSearch 工具从 IntelliJ 的索引中检索特定 groupId 和 artifactId 的最新版本号。这是实现自动化工具的关键步骤，通过这一技术，你的插件可以智能地获取外部库的最新信息。

接着是多模块项目的复杂处理。在实际开发中，项目往往包含复杂的父子模块结构。我们将学习如何利用 mainAndPomProjectProcessorUtils 类递归处理多模块项目中的父子项目 POM 文件。这一知识点能确保你的插件在处理大型工程时，能够准确识别并处理所有 POM 文件中的依赖项，避免因项目结构复杂而导致的逻辑失效。

最后是快速修复功能的完整闭环。我们将学习如何创建并配置 LocalQuickFix，并通过重写 applyFix 方法来实现具体的自动化逻辑。我们将演示如何利用 PSI 元素精确定位到 POM 文件中的 version 标签，并将其自动更新为从索引中获取到的最新版本号。此外，视频还会展示如何在沙盒环境中运行插件，通过快捷键触发检查流程，并获取包含项目信息和版本号的提示消息，完成从逻辑编写到实际运行的全流程闭环。

本视频非常适合具有 Java 或 Kotlin 基础，并且想要深入学习 IntelliJ IDEA 插件开发核心技术的开发者观看。无论你是刚开始接触插件开发，还是在开发过程中遇到了处理复杂项目结构或实现自动化修复功能的瓶颈，这期视频提供的实战思路和核心 API 讲解都能为你提供巨大的帮助。

看完本期视频后，你将能够独立掌握 PSI 的基本操作，学会利用 IDE 内置索引检索依赖信息，并具备处理多模块项目 POM 文件逻辑的能力。更重要的是，你将掌握创建 LocalQuickFix 的标准流程，能够编写出能够自动定位元素并执行修复动作的插件功能。通过本课程的实战演练，你将能够从零开始构建起一个具备工业级能力的插件功能模块，并在沙盒环境中顺利通过测试，真正掌握 IntelliJ IDEA 插件开发的核心技术栈。

原视频：IntelliJ Idea Plugin Development EP04
原作者：aptkode
发布日期：2019-09-16
视频链接：https://www.youtube.com/watch?v=9o2kPEcIzio

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| IntelliJ Idea Plugin Development EP04 - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](3049de/5e4318b2/IntelliJ%20Idea%20Plugin%20Development%20EP04%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/TZ8ER/3049de/5e4318b2/IntelliJ%20Idea%20Plugin%20Development%20EP04%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](3049de/9e424f41/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/TZ8ER/3049de/9e424f41/dubbed.srt) |
| IntelliJ Idea Plugin Development EP04 - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](3049de/bd809ff2/IntelliJ%20Idea%20Plugin%20Development%20EP04%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/TZ8ER/3049de/bd809ff2/IntelliJ%20Idea%20Plugin%20Development%20EP04%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频简介

Introduction to IntelliJ Idea plugin development - EP04

---

视频内容版权归原作者所有，字幕仅供学习交流。
