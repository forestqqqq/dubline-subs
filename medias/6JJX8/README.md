<!-- dubline-subs {"title": "Harness Engineering: Building the Production Cage for Powerful Domain Agents — Mike Chambers, AWS", "author": "AI Engineer", "files": 3, "updated": "2026-10-17"} -->
# Harness Engineering: Building the Production Cage for Powerful Domain Agents — Mike Chambers, AWS

<img src="44314a/3ad957bd/Harness%20Engineering%20Building%20the%20Production%20Cage%20for%20Powerful%20Domain%20Agents%20%E2%80%94%20Mike%20Chambers%2C%20AWS.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=gxVZ_1tuuq4](https://www.youtube.com/watch?v=gxVZ_1tuuq4) |
| 发布 | 2026-09-14 |
| 时长 | 20 分 46 秒 |
| 语言 | 英语 |
| 原作者 | [AI Engineer](https://www.youtube.com/@aiDotEngineer)（@aiDotEngineer，约 76 万订阅） |

## 中文信息

**标题**：Mike Chambers：用一套 JSON 搞定 80% 智能体开发

**原标题译文**：Harness Engineering：为强大的领域智能体构建生产级框架 —— Mike Chambers, AWS

在这期视频中，我们将带你深入探讨由 Mike Chambers 分享的核心技术理念：如何通过“套索工程”的思想，从零开始构建具备记忆管理、多租户隔离以及高度可观测性的生产级智能体。Mike Chambers 作为 AWS 的资深 AI 专家，在演示中清晰地划分了“使用型”与“构建型”智能体的区别。很多开发者往往容易陷入所谓的“垃圾操作”（Slop Ops）陷阱，即仅仅通过点击云端控制台界面来手动配置资源，而缺乏系统的工程化思维。本视频将带你跳出这种低效模式，转而采用基础设施即代码（IaC）的理念，通过自动化手段来确保智能体在生产环境中的可扩展性与安全性。

通过这期课程，你将掌握以下核心知识点：
首先是“套索工程”（Harness Engineering）的核心定义。它指的是在剥离掉大模型本身后，用于控制、管理和支撑智能体运行的所有组件集合。一个成熟的构建型智能体必须涵盖记忆系统、技能集、工具链、MCP 服务器以及统一的团队标准。
其次是生产级部署的关键要素。你会了解到为了让智能体真正投入商用，必须考虑组件的独立扩展性、支付逻辑、身份验证、运行时管理以及关键的可观测性指标。
重点内容在于 AgentCore CLI 的实战应用。通过学习如何利用该工具配合简单的 JSON 配置文件来定义模型和提示词，你可以大幅简化开发流程，从而自动化完成约 80% 的智能体基础建设工作。
此外，视频还会展示如何实现跨平台的交互逻辑。你将了解到如何利用 HTTP 协议连接本地运行的 Strands Agent 与云端部署的 Bedrock 实例，从而实现异步运行和统一的交互接口。

本期内容非常适合以下人群观看：如果你是一名希望构建真正能够投入生产环境、而非仅仅停留在原型阶段的开发者，这期视频将为你提供极其重要的工程化视角；如果你是关注 AWS Bedrock Agent Core 技术栈或 Strands 开源框架的技术人员，其中的架构设计思路将对你非常有帮助；此外，如果你的团队目前正面临多租户隔离难题、长期记忆管理挑战或智能体可观测性不足等实际工程问题，本视频提供的解决方案将极具参考价值。

看完这期视频后，你将能够改变以往依赖手动配置的粗放开发习惯，掌握基于基础设施即代码的自动化部署流程。你将学会如何通过一套 JSON 配置文件快速构建出具备专业级架构的智能体系统，并能够熟练运用 AgentCore CLI 和相关工具链来处理复杂的后端逻辑，最终实现一个既能支持大规模用户扩展，又具备完善监控与调试能力的工业级 AI 智能体应用。

章节
0:00 Mike Chambers 介绍背景及两类智能体区别
2:45 用减法定义套索工程概念
4:24 围绕编程助手的套索工程实践
5:16 停止垃圾操作：拒绝手动点云控制台
6:07 构建型智能体必备的核心组件清单
6:57 现场演示：基于 SDK 的工具装饰器 Agent
8:38 集成会话管理器与短期记忆机制
10:16 使用 AgentCore CLI 进行一键部署
12:50 无需多租户代码即可实现横向扩展
15:18 本地与云端智能体的统一交互接口
16:59 揭秘被跳过的关键 JSON 配置选项
18:40 推荐 Strands 作为快速构建替代方案

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| Harness Engineering Building the Production Cage for Powerful Domain Agents — Mike Chambers, AWS - 简体中文字幕（翻译）.zh.srt | 译文字幕 | [查看 / 下载](44314a/8807c4d3/Harness%20Engineering%20Building%20the%20Production%20Cage%20for%20Powerful%20Domain%20Agents%20%E2%80%94%20Mike%20Chambers%2C%20AWS%20-%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%E5%AD%97%E5%B9%95%EF%BC%88%E7%BF%BB%E8%AF%91%EF%BC%89.zh.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/6JJX8/44314a/8807c4d3/Harness%20Engineering%20Building%20the%20Production%20Cage%20for%20Powerful%20Domain%20Agents%20%E2%80%94%20Mike%20Chambers%2C%20AWS%20-%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%E5%AD%97%E5%B9%95%EF%BC%88%E7%BF%BB%E8%AF%91%EF%BC%89.zh.srt) |
| Harness Engineering Building the Production Cage for Powerful Domain Agents — Mike Chambers, AWS - 英语字幕（转写）.en.srt | 原文字幕（转写） | [查看 / 下载](44314a/b3e1c676/Harness%20Engineering%20Building%20the%20Production%20Cage%20for%20Powerful%20Domain%20Agents%20%E2%80%94%20Mike%20Chambers%2C%20AWS%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/6JJX8/44314a/b3e1c676/Harness%20Engineering%20Building%20the%20Production%20Cage%20for%20Powerful%20Domain%20Agents%20%E2%80%94%20Mike%20Chambers%2C%20AWS%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |
| Harness Engineering Building the Production Cage for Powerful Domain Agents — Mike Chambers, AWS - 中英双语字幕.srt | 双语字幕 | [查看 / 下载](44314a/c266f8b1/Harness%20Engineering%20Building%20the%20Production%20Cage%20for%20Powerful%20Domain%20Agents%20%E2%80%94%20Mike%20Chambers%2C%20AWS%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/6JJX8/44314a/c266f8b1/Harness%20Engineering%20Building%20the%20Production%20Cage%20for%20Powerful%20Domain%20Agents%20%E2%80%94%20Mike%20Chambers%2C%20AWS%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，时间轴与原视频一致，可直接拖进播放器（PotPlayer、VLC、IINA 等）加载。

## 原视频章节

| 时间 | 章节 |
|---|---|
| 0:00 | Who he is and how he got here |
| 2:45 | Two kinds of agents: the ones we use, the ones we build |
| 4:24 | Defining a harness by subtraction |
| 5:16 | The harness around a coding assistant |
| 6:07 | No more slop ops |
| 6:57 | What an agent you build needs instead |
| 8:38 | Live coding: a bare agent with tools |
| 10:16 | Adding a session manager and memory |
| 12:50 | Deploying with the AgentCore CLI |
| 15:18 | Scaling out without writing multi tenant code |
| 16:59 | Talking to the running agent, local and deployed |
| 18:40 | The harness option he skipped |

## 原视频简介

Mike Chambers puts a dictionary entry on screen: a harness is a set of straps and fastenings used to control an animal. Swap animal for model and the definition holds. His working version is subtraction. Take an agent, remove the model, and everything left over is the harness. Chambers is a senior AI specialist developer advocate at AWS, and he splits the field in two. There are agents we use, coding assistants and productivity tools, where the harness is memory, skills, tools, MCP servers, and the standards your team deploys to everyone. Then there are agents we build, and those need far more: loop management, scaling, payments, identity, runtime, context management, and the item he lists last while insisting it should come first, observability and evaluation. Writing all of that into one…

---

视频内容版权归原作者所有，字幕仅供学习交流。
