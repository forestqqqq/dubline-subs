<!-- dubline-subs {"title": "IntelliJ Idea Plugin Development EP01", "author": "aptkode", "files": 3, "updated": "2026-11-06"} -->
# IntelliJ Idea Plugin Development EP01

<img src="25c209/6090c24e/IntelliJ%20Idea%20Plugin%20Development%20EP01.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=fVos38m3CU4](https://www.youtube.com/watch?v=fVos38m3CU4) |
| 发布 | 2019-07-18 |
| 时长 | 20 分 1 秒 |
| 语言 | 英语 |
| 原作者 | [aptkode](https://www.youtube.com/@aptkode)（@aptkode，805 订阅） |

## 中文信息

**标题**：【中配】20分钟带你从零搭建 IntelliJ IDEA 插件项目

**原标题译文**：IntelliJ IDEA 插件开发 EP01

欢迎来到 IntelliJ IDEA 插件开发系列教程的第一集。如果你对开发自己的 IDE 插件感兴趣，或者想要深入了解 JetBrains 系列工具背后的扩展机制，那么这期视频将是你迈出第一步的最佳起点。本期视频的核心目标是带领每一位初学者，从零开始搭建起一个完整的 IntelliJ IDEA 插件项目，并带你实操完成最基础但也最核心的交互功能：在 IDE 菜单中注入自定义按钮、弹出消息对话框以及调用系统级的文件选择器。

在这一期视频中，我们将全方位覆盖插件开发的初始化流程。首先，我们将使用 Gradle 构建工具来创建项目。Gradle 是目前插件开发中主流的构建和依赖管理工具，通过它，我们可以高效地管理插件所需的各种依赖库、编译环境以及最终的发布配置。我们将重点讲解如何配置 build.gradle 文件，包括如何正确设置 Group ID、Artifact ID、项目版本号以及确保项目能够兼容 JDK 8 等关键参数。随后，我们将深入解析插件的核心配置文件 plugin.xml。这个文件就像是插件的身份证，包含了插件的 ID、描述、版本信息，以及最重要的 Action 声明。

接下来，我们将进入核心的 Action 机制教学。这是插件开发的灵魂所在。我们将学习如何在 plugin.xml 中定义自定义的菜单分组，并利用菜单锚点（Anchor）的概念，精准地将我们自定义的 Action 按钮插入到 IDE 现有的菜单结构中。通过这一步骤，你可以让你的插件功能完美融入到 IntelliJ IDEA 原生的操作流中。在代码实现层面，本教程采用 Kotlin 作为首选开发语言，我们将演示如何编写 Kotlin 类并继承 Action 基类，重点讲解 actionPerformed 方法。这是插件逻辑的核心入口，所有的点击交互、业务逻辑处理都将在这个方法中完成。

除了基础的菜单注入，本期视频还将带你掌握两个非常实用的 UI 组件。首先是 Message Dialog，我们将演示如何使用 Messages.showMessageDialog 组件向用户展示简单的信息提示、警告或确认对话框。这是插件与用户沟通最直接的方式。其次，我们将学习如何调用 File Chooser。通过使用 FileChooserDescriptor 构造并调用文件/目录选择器，你可以让用户在 IDE 环境中方便地选择文件或路径，这是开发任何涉及文件操作的插件必不可少的交互组件。

本视频非常适合那些已经具备基础的 Kotlin 或 Java 编程基础，并且想要系统性学习 IntelliJ 插件开发流程的开发者。无论你是想为自己的工作流定制专属工具，还是希望通过开发插件来提升自己的技术深度，这期视频都能为你提供扎实的工程实践基础。

看完这期视频后，你将能够独立完成以下操作：首先，你可以从零开始通过 Gradle 搭建出一个标准的 IntelliJ 插件项目框架，并掌握项目同步和环境配置的技巧。其次，你将学会如何通过修改 plugin.xml 文件来定义插件元数据，并成功在 IDE 的主菜单中添加属于自己的自定义按钮。最重要的是，你将掌握如何编写具体的 Kotlin 逻辑代码，通过实现 actionPerformed 方法来驱动插件功能，并能够熟练调用消息对话框和文件选择器等标准 UI 组件。这不仅是插件开发的入门，更是你构建复杂插件功能的基石。让我们从这 20 分钟的实操开始，开启你的插件开发之旅。

原视频：IntelliJ Idea Plugin Development EP01
原作者：aptkode
发布日期：2019-07-18
视频链接：https://www.youtube.com/watch?v=fVos38m3CU4

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| IntelliJ Idea Plugin Development EP01 - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](3b9c30/ad099f2a/IntelliJ%20Idea%20Plugin%20Development%20EP01%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/CMV4Y/3b9c30/ad099f2a/IntelliJ%20Idea%20Plugin%20Development%20EP01%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |
| IntelliJ Idea Plugin Development EP01 - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](3b9c30/daa70bcc/IntelliJ%20Idea%20Plugin%20Development%20EP01%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/CMV4Y/3b9c30/daa70bcc/IntelliJ%20Idea%20Plugin%20Development%20EP01%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](3b9c30/e13d0c45/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/CMV4Y/3b9c30/e13d0c45/dubbed.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频简介

Introduction to IntelliJ Idea plugin development - EP01

---

视频内容版权归原作者所有，字幕仅供学习交流。
