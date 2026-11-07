<!-- dubline-subs {"title": "IntelliJ Idea Plugin Development EP05 - Publish Plugin", "author": "aptkode", "files": 3, "updated": "2026-11-06"} -->
# IntelliJ Idea Plugin Development EP05 - Publish Plugin

<img src="91b7c3/47449697/IntelliJ%20Idea%20Plugin%20Development%20EP05%20-%20Publish%20Plugin.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=7P7m_sRsrrY](https://www.youtube.com/watch?v=7P7m_sRsrrY) |
| 发布 | 2019-09-22 |
| 时长 | 9 分 33 秒 |
| 语言 | 英语 |
| 原作者 | [aptkode](https://www.youtube.com/@aptkode)（@aptkode，805 订阅） |

## 中文信息

**标题**：【中配】看完就能把你的 IntelliJ 插件发布到官方市场

**原标题译文**：IntelliJ Idea 插件开发 EP05 - 发布插件

如果你已经完成了一款 IntelliJ IDEA 插件的基础功能开发，那么接下来最关键的一步就是如何让更多用户发现并使用你的作品。很多开发者在完成代码编写后，往往会卡在最后一步：如何顺利地将插件提交到 JetBrains 官方插件市场。本期视频将手把手带你走通整个发布流程，重点演示如何利用 Gradle 自动化工具，将你的插件从本地环境顺利推送到官方平台，涵盖从版本管理、依赖配置到身份验证的所有核心环节。

通过这期视频的学习，你将掌握以下具体的知识点：

首先是关于版本管理的规范。为了确保插件在市场中能够按照正确的逻辑进行排序，视频中详细介绍了如何利用 op.apache 的 Maven 库中的 comparable version 机制。这是保证你的插件版本号能够被系统正确识别的关键技术点。

其次是关于配置的一致性要求。在发布插件之前，必须确保 build.gradle 文件和 plugin.xml 文件中的版本号完全保持一致。任何细微的偏差都可能导致发布过程失败，视频中会明确演示如何同步这些核心参数。

第三是关于依赖关系的修正。在发布过程中，经常会遇到由于模块依赖标签不正确导致的报错。本视频将根据官方文档的要求，教你如何正确配置 plugin.xml 中的模块依赖，确保插件能够顺利通过平台的校验。

第四是关于身份验证的安全配置。为了保护你的账号安全，我们不再使用直接输入用户名和密码的原始方式，而是采用 Token 机制。我会演示如何在用户主目录的 gradle.properties 文件中正确配置从 JetBrains Hub 生成的发布令牌，这是实现自动化推送的基础。

第五是关于首次发布的特殊处理。由于 JetBrains 平台的限制，首次部署插件时通常需要通过 Web 界面手动上传一次插件，以建立基础的仓库信息。视频中包含了这一关键的初始化步骤，避免你因为跳过此步骤而导致后续自动化任务失败。

最后是自动化发布的实操演练。在完成上述所有准备工作后，我将演示如何通过修改版本号并运行 publishPlugin 任务，实现插件的自动化推送。同时也会涉及 verifyPlugin 任务的检查，确保每次推送的插件都是符合要求的。

这期视频特别适合以下人群观看：
如果你是一名正在学习 IntelliJ IDEA 插件开发的初学者，并且已经完成了插件的基础功能开发，正准备将其推向市场，那么这期视频就是为你量身定制的。
如果你在尝试手动发布插件时遇到了各种莫名其妙的报错，或者不知道如何配置 Gradle 自动化发布流程，本视频提供的实操演示将帮助你快速避坑。
如果你希望建立一套标准化的插件发布工作流，通过 Gradle 脚本来管理版本更新和自动化推送，从而提高开发效率，本视频提供的技术细节将非常有帮助。

看完这期视频后，你将能够独立完成从本地开发到官方市场发布的完整闭环。你将学会如何正确配置 Gradle 项目以支持插件发布，掌握版本号同步和依赖修正的技巧，学会安全地配置发布令牌，并能够熟练操作 publishPlugin 任务。最重要的是，你将能够跳过繁琐的手动操作，建立起一套高效的自动化发布流程，让你的插件能够顺利出现在 JetBrains 官方插件市场中，走向更多用户。

原视频：IntelliJ Idea Plugin Development EP05 - Publish Plugin
原作者：aptkode
发布日期：2019-09-22
视频链接：https://www.youtube.com/watch?v=7P7m_sRsrrY

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](91b7c3/05bca4fb/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/100T9/91b7c3/05bca4fb/dubbed.srt) |
| IntelliJ Idea Plugin Development EP05 - Publish Plugin - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](91b7c3/6da2996f/IntelliJ%20Idea%20Plugin%20Development%20EP05%20-%20Publish%20Plugin%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/100T9/91b7c3/6da2996f/IntelliJ%20Idea%20Plugin%20Development%20EP05%20-%20Publish%20Plugin%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| IntelliJ Idea Plugin Development EP05 - Publish Plugin - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](91b7c3/7c2bb7e6/IntelliJ%20Idea%20Plugin%20Development%20EP05%20-%20Publish%20Plugin%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/100T9/91b7c3/7c2bb7e6/IntelliJ%20Idea%20Plugin%20Development%20EP05%20-%20Publish%20Plugin%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频简介

Introduction to IntelliJ Idea plugin development - EP05 - Publish Plugin

---

视频内容版权归原作者所有，字幕仅供学习交流。
