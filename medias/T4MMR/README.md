<!-- dubline-subs {"title": "System Design Behind Multi-Conference Video Calls - WebRTC vs SFU vs MCU", "author": "Piyush Garg", "files": 3, "updated": "2026-11-27"} -->
# System Design Behind Multi-Conference Video Calls - WebRTC vs SFU vs MCU

<img src="d28a56/0ae607ba/System%20Design%20Behind%20Multi-Conference%20Video%20Calls%20-%20WebRTC%20vs%20SFU%20vs%20MCU.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=Zaz6hYVm-WE](https://www.youtube.com/watch?v=Zaz6hYVm-WE) |
| 发布 | 2026-01-04 |
| 时长 | 24 分 24 秒 |
| 语言 | hi |
| 原作者 | [Piyush Garg](https://www.youtube.com/@piyushgargdev)（@piyushgargdev，约 43 万订阅） |

## 中文信息

**标题**：【中配】24分钟拆解 Google Meet 和 Zoom 背后复杂的视频会议架构

**原标题译文**：多会议视频通话背后的系统设计 - WebRTC vs SFU vs MCU

这期视频将带你深入拆解 Google Meet 和 Zoom 等主流视频会议产品背后的核心系统架构。无论你是对互联网基础设施感兴趣的爱好者，还是正在寻找技术突破的开发者，这期内容都将为你揭开多人视频会议系统是如何在复杂的网络环境下实现低延迟、高并发传输的。我们将从最基础的连接原理出发，一步步对比不同的技术路径，最终揭示为什么选择性转发单元也就是 SFU 成为了目前全球工业界的标准解决方案。

通过本期视频的学习，你可以掌握以下具体的知识点：

首先是关于 P2P 连接的基础知识。我们将探讨在仅有两个节点参与的情况下，如何通过 UDP 协议直接传输数据流。这种方式虽然成本极低，但在面对多人场景时会遇到哪些致命的局限性。

其次是网状对等网络也就是 Mesh Topology 的局限性。我们将分析当用户数量增加时，这种让每个用户与所有其他用户建立点对点连接的模式，是如何导致连接数爆炸以及客户端负载过高的。

接着是多点控制单元也就是 MCU 架构的深度剖析。我们将讨论服务器接收所有流并将其合并成单一流进行广播的逻辑。虽然这种方式在某些场景下可行，但它带来的极高 CPU 消耗以及由此产生的延迟和高昂成本，是如何影响用户体验的。

核心内容是选择性转发单元也就是 SFU 架构的原理与优势。我们将详细解释 SFU 如何作为管道接收并转发原始流，而不进行复杂的合并处理。这种架构之所以成为主流，是因为它提供了极高的灵活性，让客户端能够自主决定如何渲染、静音或缩放特定的流。

最后，我们将介绍 SFU 的实际工作逻辑以及在生产环境中的应用。视频会涵盖服务器如何根据会议 ID 等逻辑判断并决定流的转发路径，并重点介绍 MediaSoup 库。作为一个低级别的 SFU 库，MediaSoup 如何提供工作线程、传输层和路由器等核心技术支持，以及它如何在 Node.js 环境中帮助开发者构建生产级的视频会议架构。

这期视频非常适合以下人群观看：

如果你是一名对视频会议系统架构感兴趣的开发者，想要了解大型互联网产品背后的技术选型，这期视频将为你提供清晰的架构视角。

如果你是一名需要了解 WebRTC 底层原理的工程师，视频中关于 UDP 协议、流转发逻辑以及不同拓扑结构对比的内容，将帮助你更深刻地理解实时通信的底层机制。

如果你正计划使用 Node.js 构建自己的多人视频会议应用，本视频提供的 SFU 架构原理以及对 MediaSoup 库的介绍，将为你提供实操层面的技术参考和架构指导。

看完这期视频后，你将能够清晰地分辨出 P2P、MCU 和 SFU 三种架构的核心差异，理解不同技术方案在成本、延迟和扩展性上的权衡。你将掌握多人视频会议系统设计的核心逻辑，明白为什么 SFU 是目前工业级的首选，并能够基于这些原理去思考和设计自己的实时通信产品架构。无论你是想提升自己的技术深度，还是在为自己的项目寻找技术方案，这期视频都将为你提供极具价值的架构知识储备。

原视频：System Design Behind Multi-Conference Video Calls - WebRTC vs SFU vs MCU
原作者：Piyush Garg
发布日期：2026-01-04
视频链接：https://www.youtube.com/watch?v=Zaz6hYVm-WE

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| System Design Behind Multi-Conference Video Calls - WebRTC vs SFU vs MCU - 印地语字幕（转写）.hi.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](31969d/99ab02dd/System%20Design%20Behind%20Multi-Conference%20Video%20Calls%20-%20WebRTC%20vs%20SFU%20vs%20MCU%20-%20%E5%8D%B0%E5%9C%B0%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.hi.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/T4MMR/31969d/99ab02dd/System%20Design%20Behind%20Multi-Conference%20Video%20Calls%20-%20WebRTC%20vs%20SFU%20vs%20MCU%20-%20%E5%8D%B0%E5%9C%B0%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.hi.srt) |
| System Design Behind Multi-Conference Video Calls - WebRTC vs SFU vs MCU - 简体中文+印地语双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](31969d/da71239b/System%20Design%20Behind%20Multi-Conference%20Video%20Calls%20-%20WebRTC%20vs%20SFU%20vs%20MCU%20-%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%2B%E5%8D%B0%E5%9C%B0%E8%AF%AD%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/T4MMR/31969d/da71239b/System%20Design%20Behind%20Multi-Conference%20Video%20Calls%20-%20WebRTC%20vs%20SFU%20vs%20MCU%20-%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%2B%E5%8D%B0%E5%9C%B0%E8%AF%AD%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](31969d/e011ce05/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/T4MMR/31969d/e011ce05/dubbed.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频简介

Hey everyone, In this video, we are going to discuss the system design of Multi Conference video calling application like Google Meet or Zoom. We will discuss what is WebRTC and how does Peer to Peer P2P works and limitations. We will then discuss MCU which stands for multipoint control unit and finally discuss Selective Forwarding Unit in WebRTC. Furthermore, we will also touch Media soup SFU Library, which enables you to build SFU in Node.js.

---

视频内容版权归原作者所有，字幕仅供学习交流。
