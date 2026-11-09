<!-- dubline-subs {"title": "A Short Introduction to WebRTC With Godot 4! Advanced Godot!", "author": "FinePointCGI", "files": 3, "updated": "2026-11-08"} -->
# A Short Introduction to WebRTC With Godot 4! Advanced Godot!

<img src="1e89fe/7d8a5847/A%20Short%20Introduction%20to%20WebRTC%20With%20Godot%204%21%20Advanced%20Godot%21.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=ulfGNtiItnc](https://www.youtube.com/watch?v=ulfGNtiItnc) |
| 发布 | 2023-09-06 |
| 时长 | 1 小时 58 分 2 秒 |
| 语言 | 英语 |
| 原作者 | [FinePointCGI](https://www.youtube.com/@FinePointCGI)（@FinePointCGI，约 3 万订阅） |

## 中文信息

**标题**：【中配】1小时实战：在 Godot 4 中手搓 WebRTC 多人游戏网络

**原标题译文**：Godot 4 WebRTC 简短介绍！进阶 Godot！

这期视频将带你深入了解如何在 Godot 4 引擎中从零开始构建基于 WebRTC 协议的多人游戏网络架构。我们将从基础概念出发，全程带你走过从插件集成、信号交换到最终在专用服务器上部署的完整流程。无论你是想实现点对点连接，还是希望构建复杂的网状网络，本视频都提供了实战级别的指导。

通过本视频，你将掌握以下核心知识点：
首先是 WebRTC 的核心机制，包括点对点连接原理、STUN 服务器处理 NAT 映射以及 TURN 服务器的中继功能。
其次是信号服务器的逻辑实现，学习如何通过交换 GUID、Offer、Answer 和 Candidate 等关键信息来建立连接。
在数据传输方面，你将学会如何将游戏数据序列化为 JSON 字符串，并编码为 PackedByteArray 进行高效传输。
此外，视频还会详细讲解大厅管理系统，包括玩家列表管理、32位随机 ID 生成以及基于 ID 的定向通信逻辑。
针对多人互联，我们将演示如何通过 create_mesh_id 函数挂接 Godot 内部的 RPC 调用，构建网状网络。
最后，视频还会涵盖服务器运维实战，包括在 Digital Ocean 上部署 Linux 服务器，并使用 headless 模式在后台运行程序。

本视频非常适合那些具备基础 GDScript 编程能力，且目标是开发多人在线游戏，但目前缺乏网络架构经验的开发者。看完本视频后，你将能够独立完成 WebRTC 连接的初始化与握手流程，掌握数据序列化的关键技术，并具备在 Linux 环境下部署游戏后端服务器的实操能力，从而为你的 Godot 4 多人游戏项目打下坚实的网络基础。

章节
00:00:00 开始
00:00:46 什么是 WebRTC？
00:05:02 讨论预建场景
00:06:45 添加 WEBRTC 库
00:09:11 设置我们的客户端连接
00:12:30 设置我们的信号服务器连接
00:15:30 向我们的服务器发送数据
00:17:53 解析并从服务器缓冲区获取数据
00:22:26 从服务器向客户端发送数据
00:30:44 如何构建大厅系统
00:49:27 设置我们的大厅让其他人加入
00:58:00 开始我们的 WebRTC 数据传输
00:59:13 创建我们的 WebRTC 对等节点
01:06:48 创建我们的 Offer
01:08:15 讨论本地描述与远程描述的区别
01:09:36 创建发送 Offer 和发送 Answer 函数
01:14:29 通过我们的服务器转发对等节点信息
01:17:03 转发 Offer、Answer 和候选者数据
01:22:53 设置我们的网状网络连接
01:24:26 连接几个多人游戏信号
01:32:06 设置 RPC 调用
01:33:48 设置专用服务器
01:35:04 使用 Digital Ocean 托管我们的服务器
01:37:35 将文件传输到 Digital Ocean
01:40:24 将项目导出到 Linux 用于我们的服务器
01:42:46 运行我们的服务器
01:45:24 它运行成功了！
01:45:51 如何脱离服务器进程使其保持运行
01:48:35 挂接我们之前的多人游戏教程
01:53:56 在游戏开始时移除大厅（避免服务器过载）

原视频：A Short Introduction to WebRTC With Godot 4! Advanced Godot!
原作者：FinePointCGI
发布日期：2023-09-06
视频链接：https://www.youtube.com/watch?v=ulfGNtiItnc

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| A Short Introduction to WebRTC With Godot 4! Advanced Godot! - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](1e89fe/0b1730a1/A%20Short%20Introduction%20to%20WebRTC%20With%20Godot%204%21%20Advanced%20Godot%21%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/WXN6B/1e89fe/0b1730a1/A%20Short%20Introduction%20to%20WebRTC%20With%20Godot%204%21%20Advanced%20Godot%21%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](1e89fe/1d7fcff4/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/WXN6B/1e89fe/1d7fcff4/dubbed.srt) |
| A Short Introduction to WebRTC With Godot 4! Advanced Godot! - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](1e89fe/c5b96311/A%20Short%20Introduction%20to%20WebRTC%20With%20Godot%204%21%20Advanced%20Godot%21%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/WXN6B/1e89fe/c5b96311/A%20Short%20Introduction%20to%20WebRTC%20With%20Godot%204%21%20Advanced%20Godot%21%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频章节

| 时间 | 章节 |
|---|---|
| 00:00:00 | Start |
| 00:00:46 | What Is WebRTC? |
| 00:05:02 | Discussing the Prebuilt Scene |
| 00:06:45 | Adding the WEBRTC Library |
| 00:09:11 | Settign up Our Client Connection |
| 00:12:30 | Setting Up Our Signaling Server Connection |
| 00:15:30 | Sending Data to Our Server |
| 00:17:53 | Parsing and Getting Data From the Server Buffer |
| 00:22:26 | Sending Data From Server to Clients |
| 00:30:44 | How To Build a Lobby System |
| 00:49:27 | Setting Up Our Lobby So Others Can Join |
| 00:58:00 | Getting Started With Our WEBRTC Data Transfer |
| 00:59:13 | Creating Our WEBRTC Peers |
| 01:06:48 | Creating Our Offer |
| 01:08:15 | Discussing What a Local Description vs Remote Description Is |
| 01:09:36 | Creating Send Offer and Send Answer Functins |
| 01:14:29 | Relaying Peer Information Though Our Server |
| 01:17:03 | Relaying the Offer Answer and Candidate Data |
| 01:22:53 | Setting Up Our Mesh Connection |
| 01:24:26 | Connecting a Couple Mutiplayer Signals |
| 01:32:06 | Setting Up RPC Calls |
| 01:33:48 | Setting Up a Dedicated Server |
| 01:35:04 | Using Digital Ocean To Host Our Server |
| 01:37:35 | Tldr File Transfer to Digital Ocean |
| 01:40:24 | Exporting Our to Linux for Our Server |
| 01:42:46 | Running Our Server |
| 01:45:24 | IT WORKS! |
| 01:45:51 | How To Disown the Server Process Allowing It To Stay Open |
| 01:48:35 | Hooking Up Our Old Multiplayer Tutorial |
| 01:53:56 | Removing Lobby on Game Start (To Not Overload the Server Over Time) |

## 原视频简介

Subscribe and learn more from me about Game Development and Programming!

---

视频内容版权归原作者所有，字幕仅供学习交流。
