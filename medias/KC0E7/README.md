<!-- dubline-subs {"title": "IntelliJ Idea Plugin Development EP02", "author": "aptkode", "files": 3, "updated": "2026-11-06"} -->
# IntelliJ Idea Plugin Development EP02

<img src="4a60c2/85e79c51/IntelliJ%20Idea%20Plugin%20Development%20EP02.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=IeqRswA9VP8](https://www.youtube.com/watch?v=IeqRswA9VP8) |
| 发布 | 2019-08-17 |
| 时长 | 52 分 18 秒 |
| 语言 | 英语 |
| 原作者 | [aptkode](https://www.youtube.com/@aptkode)（@aptkode，805 订阅） |

## 中文信息

**标题**：【中配】52 分钟学会 IntelliJ IDEA 插件的 UI 交互与数据持久化

**原标题译文**：IntelliJ Idea 插件开发 EP02

欢迎来到本期视频。如果你正在探索 IntelliJ IDEA 插件开发的领域，那么掌握如何与用户进行有效的交互，以及如何安全地管理插件数据，是构建高质量插件的必经之路。本期视频将带你深入了解 IntelliJ IDEA 插件开发中的核心交互逻辑与数据持久化方案。我们将从最基础的消息对话框开始，逐步过渡到复杂的自定义表单界面，并深入探讨如何正确处理不同类型的数据存储，确保插件在用户多次使用过程中能够稳定地保留状态，同时严格保护用户的敏感信息。

在本期视频中，你将学到以下具体的知识点：

首先是基础的 UI 交互实现。我们将学习如何利用 Messages 工具类中的 showInputDialog 方法，快速创建一个简单的消息输入对话框，这是获取用户简单输入最快捷的方式。接着，我们将进阶到更复杂的界面构建。通过继承 DialogWrapper 类，你可以定制包含多个输入字段的复杂对话框。为了让这些界面整齐美观，我们将重点讲解如何利用 UIUtil 和 GridBag 工具类来简化 GridBagLayout 布局的构建。通过这些工具，你可以轻松创建样式化的 JLabel、JTextField 以及用于输入密码的 JPasswordField 组件。此外，我们还会演示如何重写 doOkAction 方法，这是捕获并处理用户在对话框中提交的数据关键步骤。

在数据持久化方面，本视频提供了完整的实战方案。我们将学习如何使用 PersistentStateComponent 将插件配置自动转换为 XML 等格式进行持久化存储。通过定义 pluginState 对象和 Settings 类，你可以让插件在重启或关闭后依然保留用户的个性化设置。与此同时，视频特别强调了数据安全的处理原则：我们将详细讲解如何区分非敏感数据与敏感数据。对于非敏感数据，我们使用插件状态对象进行处理；而对于用户名和密码等高度敏感的信息，我们必须使用 CredentialsManager 来确保安全。我们将演示如何通过 ServiceManager 获取持久化组件实例，并利用 companion object 提供全局访问，同时展示如何通过 getPassword 方法安全地获取敏感信息。

最后，我们将涵盖更高级的交互组件。我们将学习如何继承 BasePopupListPopupStep 类，并通过重写 quickSearch 和 onChosen 方法来创建自定义的弹出列表。结合 JBPopupFactory 的应用，你可以为用户提供更加流畅的搜索与选择体验。

本视频非常适合正在学习 IntelliJ IDEA 插件开发的开发者观看。无论你是刚开始接触 JetBrains 插件 SDK，还是已经具备基础 Java 知识但苦于不知道如何构建复杂的 UI 界面，或者在处理用户数据存储时感到困惑，这期视频都能为你提供实用的技术指导。

看完本视频后，你将能够独立完成以下任务：
你可以熟练地根据需求选择合适的交互组件，无论是简单的输入框还是复杂的网格布局表单。你将能够掌握在插件中构建规范 UI 界面的标准流程，包括布局管理和组件样式处理。在数据管理方面，你将能够正确配置插件的持久化方案，让插件具备记忆功能。最重要的是，你将学会遵循 JetBrains 的安全规范，能够正确区分并处理不同级别的数据，确保用户的敏感信息在插件运行过程中得到妥善保护。通过本视频的学习，你将具备构建具备专业交互体验和安全数据管理能力的 IntelliJ IDEA 插件的核心技术储备。

原视频：IntelliJ Idea Plugin Development EP02
原作者：aptkode
发布日期：2019-08-17
视频链接：https://www.youtube.com/watch?v=IeqRswA9VP8

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](4a60c2/0f11bb45/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/KC0E7/4a60c2/0f11bb45/dubbed.srt) |
| IntelliJ Idea Plugin Development EP02 - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](4a60c2/7202429c/IntelliJ%20Idea%20Plugin%20Development%20EP02%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/KC0E7/4a60c2/7202429c/IntelliJ%20Idea%20Plugin%20Development%20EP02%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |
| IntelliJ Idea Plugin Development EP02 - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](4a60c2/c41b0065/IntelliJ%20Idea%20Plugin%20Development%20EP02%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/KC0E7/4a60c2/c41b0065/IntelliJ%20Idea%20Plugin%20Development%20EP02%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频简介

Introduction to IntelliJ Idea plugin development - EP02

---

视频内容版权归原作者所有，字幕仅供学习交流。
