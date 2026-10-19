<!-- dubline-subs {"title": "I Built a Personal AI Agent on a Raspberry Pi — Jeremy Adams, Neo4j", "author": "AI Engineer", "files": 3, "updated": "2026-10-19"} -->
# I Built a Personal AI Agent on a Raspberry Pi — Jeremy Adams, Neo4j

<img src="c4b447/08e2b06e/I%20Built%20a%20Personal%20AI%20Agent%20on%20a%20Raspberry%20Pi%20%E2%80%94%20Jeremy%20Adams%2C%20Neo4j.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=oUZEt4EiPbk](https://www.youtube.com/watch?v=oUZEt4EiPbk) |
| 发布 | 2026-10-03 |
| 时长 | 20 分 10 秒 |
| 语言 | 英语 |
| 原作者 | [AI Engineer](https://www.youtube.com/@aiDotEngineer)（@aiDotEngineer，约 76 万订阅） |

## 中文信息

**标题**：用 Raspberry Pi 和 Neo4j 构建带长久记忆的 AI Agent

**原标题译文**：我在 Raspberry Pi 上构建了一个个人 AI Agent —— Jeremy Adams, Neo4j

在这期视频中，我们将深入探讨如何结合 Raspberry Pi 微型计算机、Neo4j 图数据库以及最新的 MCP 协议，共同构建一个具备结构化长久记忆能力的个人 AI Agent 系统。很多时候，AI 的局限性在于无法真正理解并关联碎片化的信息，而本视频的核心目的就是通过图谱技术，将零散的日常记录转化为具有深度逻辑联系的知识网络。我们将从硬件选型到软件架构的全流程进行拆解，带你领略如何让 AI 真正“记住”用户的经历。

通过本期视频的学习，你将掌握以下核心知识点：
首先是关于硬件与系统架构的设计。你会了解到为什么在构建移动端交互终端时，选择 Raspberry Pi 这类可定制的设备比高性能笔记本更具优势。同时，我们将剖析完整的通信链路：用户通过 WhatsApp 发送消息，经过 Cloud Agent SDK 处理，再通过 MCP 服务器与 Neo4j 数据库进行交互。
其次是核心的记忆模型构建。视频详细讲解了如何采用 POLE 模型（涵盖人物 Person、物体 Object、地点 Location、事件 Event）来建立结构化的记忆体系，将个人经历转化为具体的节点和关系。
再者是关键的技术协议应用。我们将演示如何利用 Model Context Protocol (MCP) 让 AI Agent 能够高效地查询并访问 Neo4j 中的知识图谱，从而在对话中调用相关的背景信息。
此外，你还将学习到离线优先的策略：在网络环境不稳定的情况下，系统如何在本地记录原始数据，并在后续同步至云端进行自动化清洗与关联分析。
最后是自动化的记忆提取。我们将演示如何利用 Neo4j Agent Memory 服务，从长期的对话历史中自动识别并过滤出关键的记忆点，如特定的人物、地点或核心概念。

本视频非常适合以下人群观看：如果你是一名正在研究 AI Agent 开发、对图数据库应用感兴趣的开发者；或者你是一位正在寻找如何为 AI 构建长期记忆（Long-term Memory）技术方案的技术人员；亦或是关注边缘计算与硬件结合、想要尝试将 Raspberry Pi 与各类传感器或物理按钮结合的硬核爱好者。

看完本期视频后，你将能够掌握一套完整的实战方案：不仅能理解如何利用图数据库构建结构化的记忆模型，还能学会如何通过 MCP 协议整合复杂的后端数据，并最终实现一个能够在弱网环境下稳定运行、具备自动信息提炼能力的 AI Agent 系统。无论你是想优化自己的知识管理工具，还是在探索更高级的 AI 应用形态，这个实战案例都将为你提供极具参考价值的技术路径。

章节
0:00 开场介绍
0:12 来自 Neo4j 的问候
1:32 我们要构建的内容
1:57 现场硬件搭建
4:51 Raspberry Pi 爪子启动
6:06 为什么选择小型爪子
8:05 为什么选择 NanoClaw
8:55 架构：WhatsApp $\rightarrow$ NanoClaw $\rightarrow$ Claude
9:40 图谱基础知识
10:10 通过 MCP 查询 Neo4j
10:50 在飞机上构建记忆：POLE 模型
12:15 演示：记忆图谱
13:29 添加语音转文字功能
14:49 记录展会信息
15:34 带本地 Neo4j 的离线模式
17:03 在云端丰富主题内容
18:23 升级到 Neo4j Agent Memory
19:33 开始前往 GraphAcademy

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| I Built a Personal AI Agent on a Raspberry Pi — Jeremy Adams, Neo4j - 中英双语字幕.srt | 双语字幕 | [查看 / 下载](c4b447/1bb2c30f/I%20Built%20a%20Personal%20AI%20Agent%20on%20a%20Raspberry%20Pi%20%E2%80%94%20Jeremy%20Adams%2C%20Neo4j%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/D01GK/c4b447/1bb2c30f/I%20Built%20a%20Personal%20AI%20Agent%20on%20a%20Raspberry%20Pi%20%E2%80%94%20Jeremy%20Adams%2C%20Neo4j%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| I Built a Personal AI Agent on a Raspberry Pi — Jeremy Adams, Neo4j - 英语字幕（转写）.en.srt | 原文字幕（转写） | [查看 / 下载](c4b447/5d484d71/I%20Built%20a%20Personal%20AI%20Agent%20on%20a%20Raspberry%20Pi%20%E2%80%94%20Jeremy%20Adams%2C%20Neo4j%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/D01GK/c4b447/5d484d71/I%20Built%20a%20Personal%20AI%20Agent%20on%20a%20Raspberry%20Pi%20%E2%80%94%20Jeremy%20Adams%2C%20Neo4j%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |
| I Built a Personal AI Agent on a Raspberry Pi — Jeremy Adams, Neo4j - 简体中文字幕（翻译）.zh.srt | 译文字幕 | [查看 / 下载](c4b447/cf3f0db7/I%20Built%20a%20Personal%20AI%20Agent%20on%20a%20Raspberry%20Pi%20%E2%80%94%20Jeremy%20Adams%2C%20Neo4j%20-%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%E5%AD%97%E5%B9%95%EF%BC%88%E7%BF%BB%E8%AF%91%EF%BC%89.zh.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/D01GK/c4b447/cf3f0db7/I%20Built%20a%20Personal%20AI%20Agent%20on%20a%20Raspberry%20Pi%20%E2%80%94%20Jeremy%20Adams%2C%20Neo4j%20-%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%E5%AD%97%E5%B9%95%EF%BC%88%E7%BF%BB%E8%AF%91%EF%BC%89.zh.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，时间轴与原视频一致，可直接拖进播放器（PotPlayer、VLC、IINA 等）加载。

## 原视频章节

| 时间 | 章节 |
|---|---|
| 0:00 | Intro |
| 0:12 | Hi from Neo4j |
| 1:32 | What we're building |
| 1:57 | Live hardware setup |
| 4:51 | The Raspberry Pi claw boots up |
| 6:06 | Why small claws |
| 8:05 | Why NanoClaw |
| 8:55 | Architecture: WhatsApp → NanoClaw → Claude |
| 9:40 | Graphs 101 |
| 10:10 | Querying Neo4j over MCP |
| 10:50 | Building memory on a plane: the POLE schema |
| 12:15 | Demo: the memory graph |
| 13:29 | Adding voice-to-text |
| 14:49 | Recording the expo booths |
| 15:34 | Offline mode with a local Neo4j |
| 17:03 | Enriching themes in the cloud |
| 18:23 | Upgrading to Neo4j Agent Memory |
| 19:33 | Get started with GraphAcademy |

## 原视频简介

No Mac Mini, no laptop agent. Jeremy Adams runs his personal AI agent on an old Raspberry Pi he wears around his neck.

---

视频内容版权归原作者所有，字幕仅供学习交流。
