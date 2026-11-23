<!-- dubline-subs {"title": "How Does WebRTC Work? | Crash Course", "author": "Dennis Ivy", "files": 3, "updated": "2026-11-23"} -->
# How Does WebRTC Work? | Crash Course

<img src="1a9370/bc6e8b56/How%20Does%20WebRTC%20Work%20Crash%20Course.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=8I2axE6j204](https://www.youtube.com/watch?v=8I2axE6j204) |
| 发布 | 2022-04-01 |
| 时长 | 1 小时 10 分 42 秒 |
| 语言 | 英语 |
| 原作者 | [Dennis Ivy](https://www.youtube.com/@DennisIvy)（@DennisIvy，约 22 万订阅） |

## 中文信息

**标题**：【中配】1小时实战：从零手搓一个带信令机制的P2P视频聊天

**原标题译文**：WebRTC 是如何工作的？| Crash Course

这期视频将带你深入探索 WebRTC 的核心原理，并手把手教你从零开始构建一个具备自动化信令机制的 P2P 视频聊天应用。很多开发者在接触 WebRTC 时，往往只是调用现成的 SDK，而忽略了底层复杂的握手逻辑和网络穿透原理。本视频旨在打破这种黑盒状态，通过理论讲解与实战项目的结合，让你彻底搞懂 WebRTC 是如何实现低延迟音频、视频和数据传输的。

在视频中，你将学到以下核心知识点：
首先是 WebRTC 的基础定义及其与 WebSockets 的本质区别。我们将探讨为什么实时流媒体更倾向于使用 UDP 协议来实现点对点连接，而 WebSockets 更多用于对延迟不敏感的文本消息传输。
其次是核心的信令机制。由于 WebRTC 本身并不包含内置的信令通道，我们需要配合第三方服务或 WebSocket 来交换连接信息。视频将详细拆解 SDP（会话描述协议）的 Offer 与 Answer 交换逻辑。
接着是网络穿透的关键技术。我们将学习如何利用 STUN 服务器获取公网 IP 和端口，生成 ICE 候选者以穿透防火墙和 NAT 环境，并深入讲解 Trickle ICE 技术如何通过逐个发送候选者来显著减少连接建立的延迟。
此外，视频还会涵盖具体的工程实现细节，包括如何使用 navigator.mediaDevices.getUserMedia 获取本地媒体流，如何通过 addTrack 将轨道添加到 RTCPeerConnection 对象中，以及如何集成 Agora RTM SDK 来实现自动化的信令传输，替代繁琐的手动交换过程。
最后，我们将总结完整的 P2P 连接握手流程，涵盖从发送 Offer、创建并发送 Answer，到交换双方 ICE 候选者并最终建立连接的全过程。

本视频非常适合前端开发人员、对实时通信技术感兴趣的开发者，以及想要深入理解 WebRTC 原理的工程师观看。如果你具备基础的 HTML、CSS 和 JavaScript 知识，并且了解基本的异步编程概念（如 async/await），那么这个视频将为你提供极高的价值。

看完这期视频后，你将能够独立完成以下任务：
你可以清晰地解释 WebRTC 的工作原理，并能够准确描述 SDP、ICE 候选者以及 STUN 服务器在整个连接链路中的作用。
你将具备从零开始构建 P2P 通信应用的能力，能够编写出包含 createOffer、createResponse、setRemoteDescription 和 addIceCandidate 等核心逻辑的代码。
你能够熟练操作浏览器 API 来获取媒体流，并能够通过集成第三方 SDK 来构建出具备自动化信令传输功能的完整视频聊天系统。
最重要的是，你将掌握完整的 P2P 连接调试思路，能够通过分析握手流程中的每一个环节，快速定位并解决连接建立过程中的网络或逻辑问题。

章节
00:00 介绍
00:35 WebRTC基础理论幻灯片
12:05 项目文件初始化
19:40 在页面上显示摄像头
23:28 对等连接（SDP提议与响应）
46:00 使用Agora实现信令传输

原视频：How Does WebRTC Work? | Crash Course
原作者：Dennis Ivy
发布日期：2022-04-01
视频链接：https://www.youtube.com/watch?v=8I2axE6j204

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| How Does WebRTC Work Crash Course - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](853fba/02087f1d/How%20Does%20WebRTC%20Work%20Crash%20Course%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/H6N4T/853fba/02087f1d/How%20Does%20WebRTC%20Work%20Crash%20Course%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| How Does WebRTC Work Crash Course - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](853fba/327388c0/How%20Does%20WebRTC%20Work%20Crash%20Course%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/H6N4T/853fba/327388c0/How%20Does%20WebRTC%20Work%20Crash%20Course%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](853fba/c7bc2e75/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/H6N4T/853fba/c7bc2e75/dubbed.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频章节

| 时间 | 章节 |
|---|---|
| 00:00 | Intro |
| 00:35 | WebRTC Intro Slides |
| 12:05 | Project Files Setup |
| 19:40 | Display Camera to Page |
| 23:28 | Peer Connection (SDP Offer & Answer) |
| 46:00 | Signaling with Agora |

## 原视频简介

WebRTC introduction and complete project based tutorial. Build a small peer to peer video chat application with signaling.

---

视频内容版权归原作者所有，字幕仅供学习交流。
