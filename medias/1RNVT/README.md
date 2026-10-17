<!-- dubline-subs {"title": "Claude Agent SDK Tutorial – Build AI Agents with Claude Code", "author": "ExamPro", "files": 3, "updated": "2026-10-17"} -->
# Claude Agent SDK Tutorial – Build AI Agents with Claude Code

<img src="92d7ea/43e7e971/Claude%20Agent%20SDK%20Tutorial%20%E2%80%93%20Build%20AI%20Agents%20with%20Claude%20Code.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=SM-Fy8e3nFk](https://www.youtube.com/watch?v=SM-Fy8e3nFk) |
| 发布 | 2026-09-14 |
| 时长 | 37 分 10 秒 |
| 语言 | 英语 |
| 原作者 | [ExamPro](https://www.youtube.com/@ExamProChannel)（@ExamProChannel，约 8 万订阅） |

## 中文信息

**标题**：用 Claude Code 自动修复 Python 代码错误

**原标题译文**：Claude Agent SDK 教程 – 使用 Claude Code 构建 AI Agent

在这一期的视频中，我们将深入探讨如何利用 Claude Agent SDK 在 Python 环境中构建具备自我修复能力的 AI 代理。这不仅仅是一个简单的工具演示，而是一个完整的实战流程：从基础的本地环境搭建、依赖管理配置，到核心的通过日志上下文让 AI 自动识别并修正代码错误的闭环逻辑。随着 AI 技术的快速发展，如何让 Agent 真正理解报错信息并自主完成修复，成为了开发者提升生产力的关键点。本视频将带你完整走过这一技术路径，让你掌握构建具备自我纠错能力的智能代理的核心逻辑。

通过这期视频的学习，你可以掌握以下非常具体的知识点：首先是关于环境与工具的选型，包括在 WSL2 环境下安装原生编译版本的 Claude Code 以获取最佳性能，以及在开发和生产环境中分别选择订阅密钥或 API Key 的不同策略；其次是核心的依赖管理与配置简化，例如如何通过 pip install agent-sdks 快速部署所需的 SDK 包，并移除不必要的隔离环境配置来提升执行效率。在代码实现层面，你将学到如何编写包含故意错误的初始脚本来测试 Agent 的异常处理能力，以及如何为 AI 代理授予读取、编辑和执行 Bash 的权限，这是让它能够自主操作文件并进行修复的前提条件。此外，视频还会详细讲解日志系统的构建：包括使用 ISO 8601 时间戳格式来提升日志的可读性与机器解析效率，以及通过自定义解析器将复杂的 Python 对象字符串转换为人类可读的终端输出格式。最核心的内容在于利用这些结构化的日志文件作为上下文输入给 Claude，让它能够精准定位如 Ruby 中 puts 方法误用等语法错误或逻辑问题，并自动生成修正后的代码。

本期内容非常适合以下几类人群观看：如果你是一名希望学习如何构建和使用 AI Agent 的开发者，这期视频提供的完整工作流将为你提供实战参考；如果你是经常处理 Python 项目、需要掌握更高效的 Python 环境配置与依赖管理技巧的程序员，这里的工程实践会非常有帮助；如果你是对 Claude Code SDK 及其背后的日志调试机制感兴趣的技术人员，本视频深入剖析的上下文注入机制将是你的核心干货；当然，只要你具备基础的编程知识，能够理解基本的 Python 语法并识别常见的代码错误类型，都能从这期内容中获得实用的技术启发。

看完这个视频后，你将能够掌握一套完整的自动化调试方案。在实际开发中，当你面对复杂的报错信息时，不再需要手动反复查阅文档或在终端里反复尝试修改参数，而是可以通过构建的 AI 代理自动完成问题的定位与修复。通过学习本视频中的技术点，你可以学会如何构建结构化的日志系统来辅助 AI 理解上下文，从而建立起一套从发现错误到自动修复的闭环流程。无论你是想优化自己的开发工作流，还是希望深入研究 AI Agent 的交互逻辑，这期内容都能为你提供扎实的实战基础，帮助你真正掌握利用 Claude 系列工具提升编程效率的核心技巧。

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| Claude Agent SDK Tutorial – Build AI Agents with Claude Code - 英语字幕（转写）.en.srt | 原文字幕（转写） | [查看 / 下载](1ac4aa/58a8caee/Claude%20Agent%20SDK%20Tutorial%20%E2%80%93%20Build%20AI%20Agents%20with%20Claude%20Code%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/1RNVT/1ac4aa/58a8caee/Claude%20Agent%20SDK%20Tutorial%20%E2%80%93%20Build%20AI%20Agents%20with%20Claude%20Code%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |
| Claude Agent SDK Tutorial – Build AI Agents with Claude Code - 简体中文字幕（翻译）.zh.srt | 译文字幕 | [查看 / 下载](1ac4aa/a2b052df/Claude%20Agent%20SDK%20Tutorial%20%E2%80%93%20Build%20AI%20Agents%20with%20Claude%20Code%20-%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%E5%AD%97%E5%B9%95%EF%BC%88%E7%BF%BB%E8%AF%91%EF%BC%89.zh.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/1RNVT/1ac4aa/a2b052df/Claude%20Agent%20SDK%20Tutorial%20%E2%80%93%20Build%20AI%20Agents%20with%20Claude%20Code%20-%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%E5%AD%97%E5%B9%95%EF%BC%88%E7%BF%BB%E8%AF%91%EF%BC%89.zh.srt) |
| Claude Agent SDK Tutorial – Build AI Agents with Claude Code - 中英双语字幕.srt | 双语字幕 | [查看 / 下载](1ac4aa/b0955a89/Claude%20Agent%20SDK%20Tutorial%20%E2%80%93%20Build%20AI%20Agents%20with%20Claude%20Code%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/1RNVT/1ac4aa/b0955a89/Claude%20Agent%20SDK%20Tutorial%20%E2%80%93%20Build%20AI%20Agents%20with%20Claude%20Code%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，时间轴与原视频一致，可直接拖进播放器（PotPlayer、VLC、IINA 等）加载。

## 原视频简介

Build your first AI agent with the Claude Agent SDK.

---

视频内容版权归原作者所有，字幕仅供学习交流。
