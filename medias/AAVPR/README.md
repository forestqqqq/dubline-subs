<!-- dubline-subs {"title": "IntelliJ Idea Plugin Development EP03", "author": "aptkode", "files": 3, "updated": "2026-11-06"} -->
# IntelliJ Idea Plugin Development EP03

<img src="8b52bd/eb51f14d/IntelliJ%20Idea%20Plugin%20Development%20EP03.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=q052NlaweJ0](https://www.youtube.com/watch?v=q052NlaweJ0) |
| 发布 | 2019-09-08 |
| 时长 | 18 分 43 秒 |
| 语言 | 英语 |
| 原作者 | [aptkode](https://www.youtube.com/@aptkode)（@aptkode，805 订阅） |

## 中文信息

**标题**：【中配】18分钟手把手带你从零开发一个IntelliJ IDEA插件

**原标题译文**：IntelliJ Idea 插件开发 EP03

在这期视频中，我将带大家从零开始，手把手完成一个 IntelliJ IDEA 插件的开发全过程。我们将共同打造一个名为 Maven Dependency Updater 的实用插件，该插件的核心功能是实现 Maven 依赖项的版本更新检查。这不仅是一个简单的功能演示，更是一次完整的插件开发实战教学，涵盖了从项目初始化、环境配置到核心逻辑实现的每一个关键步骤。

通过本期视频的学习，你将掌握以下核心知识点：

首先是关于插件的基础配置与依赖管理。你将学会如何在 plugin.xml 文件中通过添加 depends 标签来引入 org.jetbrains.ide.main 模块，这是调用 IntelliJSDK 中 Maven 相关核心内容的关键步骤。

其次是插件的本地化机制处理。视频将详细讲解如何创建 .properties 文件作为资源包，并在 plugin.xml 的 references 部分进行正确注册。通过这种方式，你可以确保插件能够支持多语言显示，这是开发高质量、符合规范的插件的基础。

在代码实现层面，你将学习如何创建 Bundle 类。通过继承 SDK 已有的 Bundle 类并修改指向对应的 .properties 文件，你可以学会如何利用 message 方法来获取本地化的字符串，从而让插件界面更加专业。

更深入的内容包括代码检查（Inspection）的注册与实现。你将学习如何通过继承 DomElementInspection 类，并配合使用 @RegisterInspection 注解，将自定义检查项注册到插件设置中。同时，你还会了解到如何在 plugin.xml 中配置检查项的显示名称、所属组名、警告级别以及默认的启用状态。

最后，视频将带你进入核心逻辑的编写。你将学习如何重写 checkFileElement 方法，并掌握如何利用 generateManageDependencyAction 等现有的 SDK 类来获取 Maven 项目模型以及具体的依赖信息。通过这些操作，你将能够让插件真正具备识别和处理 Maven 依赖的能力。

本视频非常适合具备 Java 或 Kotlin 开发基础，并且想要通过实战项目深入了解 IntelliJ IDEA 插件开发流程的开发者。无论你是想为自己的工作流定制专属工具，还是希望进入插件开发领域，这期视频提供的实操路径都能为你提供清晰的指引。

看完这期视频后，你将能够独立完成一个基础插件的构建。你不仅能掌握从 settings.gradle、build.gradle 到 plugin.xml 的项目配置，还能熟练操作本地化资源包的配置，并能够通过继承 SDK 类来快速实现复杂的代码检查逻辑。通过本视频的实操练习，你将具备从零开始构建插件、注册自定义检查项并获取 Maven 项目模型数据的核心能力，为后续开发更复杂的 IDE 扩展功能打下坚实的基础。

原视频：IntelliJ Idea Plugin Development EP03
原作者：aptkode
发布日期：2019-09-08
视频链接：https://www.youtube.com/watch?v=q052NlaweJ0

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| IntelliJ Idea Plugin Development EP03 - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](8b52bd/4fb1f60f/IntelliJ%20Idea%20Plugin%20Development%20EP03%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/AAVPR/8b52bd/4fb1f60f/IntelliJ%20Idea%20Plugin%20Development%20EP03%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](8b52bd/b2b7c594/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/AAVPR/8b52bd/b2b7c594/dubbed.srt) |
| IntelliJ Idea Plugin Development EP03 - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](8b52bd/f3350f0f/IntelliJ%20Idea%20Plugin%20Development%20EP03%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/AAVPR/8b52bd/f3350f0f/IntelliJ%20Idea%20Plugin%20Development%20EP03%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频简介

Introduction to IntelliJ Idea plugin development - EP03

---

视频内容版权归原作者所有，字幕仅供学习交流。
