<!-- dubline-subs {"title": "MCP Servers Explained & Built", "author": "Tech With Tim", "files": 3, "updated": "2026-11-22"} -->
# MCP Servers Explained & Built

<img src="63de23/650abb71/MCP%20Servers%20Explained%20%26%20Built.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=He8tUwLzLnU](https://www.youtube.com/watch?v=He8tUwLzLnU) |
| 发布 | 2026-09-24 |
| 时长 | 30 分 14 秒 |
| 语言 | 英语 |
| 原作者 | [Tech With Tim](https://www.youtube.com/@TechWithTim)（@TechWithTim，约 212 万订阅） |

## 中文信息

**标题**：【中配】30 分钟，从零搭建带 OAuth 认证的 MCP 服务器

**原标题译文**：MCP Servers 原理解析与构建

这期视频将带你深入系统地解析 MCP（Model Context Protocol）服务器的架构原理与安全机制。随着 AI 代理技术的快速发展，如何让 AI 模型安全、高效地连接到真实世界的工具成为了核心课题。本视频不仅会从理论层面剖析 MCP 的定义与通信机制，更会通过从零开始的代码实战演示，手把手教你如何构建一个支持身份验证与细粒度权限控制的 AI 工具连接层。

在视频的前半部分，我们将深入探讨 MCP 服务器的本质。你会了解到 MCP 服务器实际上是向 AI 模型提供一组可调用函数列表的程序，它旨在解决重复开发工具管道的痛点。我们将详细拆解 MCP 的通信机制：模型本身并不直接操作工具，而是输出调用指令文本，由后台代码执行工具操作并将结果通过 JSON 格式回传。同时，视频还会对比本地运行模式与远程运行模式的差异。本地模式虽然适合个人测试，但由于无法跨设备共享，在生产环境中，基于 HTTP URL 的远程运行模式才是首选方案。

针对当前公共 MCP 服务器普遍缺乏安全认证或仅使用易被攻破的静态 API 密钥等安全隐患，本视频提供了完整的工业级解决方案。我们将演示如何采用 OAuth 2.1 配合 PKCE 流程来实现安全的身份验证。通过这种方式，系统可以通过令牌签名验证用户身份，并严格检查权限范围。此外，视频还会展示动态客户端注册机制，这一机制可以实现自动化流程，让开发者无需手动管理每一个用户的凭证。

在实战演示环节，我们将使用 Python 语言和 FastMCP 框架，从零构建本地及远程 MCP 服务器。你将看到完整的代码实践，包括如何使用 uv 或 node 命令执行脚本，以及如何在 Cursor 终端中管理工具通信。对于远程模式，我们将演示如何修改传输参数以支持 HTTP 和流式传输，使服务器可以通过特定 URL 被外部客户端直接访问。在身份验证流程中，你会看到用户如何在浏览器中完成 OAuth 授权链接的点击，并勾选特定的权限范围。最后，我们将验证多用户身份切换与权限控制的实际效果，例如系统如何准确识别用户身份，并仅允许其执行拥有对应权限范围的操作，如仅允许特定用户执行笔记的读写操作。

本视频非常适合开发者或工程师观看，特别是那些正在构建 AI 代理（AI agents）或者需要深入理解 AI 如何连接真实世界工具的技术人员。如果你对 MCP 协议的原理、安全架构以及具体的代码实现感兴趣，并且具备基础的编程知识（如 Python 基础）以及对 OAuth 2.1 基本概念的了解，那么这期视频将为你提供极具价值的实战参考。

看完这期视频后，你将能够从底层逻辑上理解 MCP 协议的运作方式，掌握从本地测试到生产环境远程部署的完整路径。你将学会如何摒弃不安全的静态密钥，转而构建基于 OAuth 2.1 和 PKCE 的高安全性认证架构。通过学习视频中的 FastMCP 框架实践，你将具备从零搭建带认证 MCP 服务器的能力，能够实现在复杂的生产环境中构建具备多用户身份识别和细粒度权限控制的 AI 工具连接层，确保你的 AI 应用在连接外部数据源（如 Notion、Slack、Airtable 等）时既高效又安全。

章节
00:00 概述
00:15 什么是 MCP 服务器
03:08 本地与远程运行模式
04:13 访问控制机制
09:18 MCP 协议详解
11:52 从零构建服务器
20:20 添加身份验证

原视频：MCP Servers Explained & Built
原作者：Tech With Tim
发布日期：2026-09-24
视频链接：https://www.youtube.com/watch?v=He8tUwLzLnU

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](4ce641/61aedcf0/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/9H9YD/4ce641/61aedcf0/dubbed.srt) |
| MCP Servers Explained & Built - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](4ce641/a9250de4/MCP%20Servers%20Explained%20%26%20Built%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/9H9YD/4ce641/a9250de4/MCP%20Servers%20Explained%20%26%20Built%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| MCP Servers Explained & Built - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](4ce641/f61c0afd/MCP%20Servers%20Explained%20%26%20Built%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/9H9YD/4ce641/f61c0afd/MCP%20Servers%20Explained%20%26%20Built%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频章节

| 时间 | 章节 |
|---|---|
| 00:00 | Overview |
| 00:15 | What is an MCP Server |
| 03:08 | Local vs Remote |
| 04:13 | Access Control |
| 09:18 | MCP Protocol |
| 11:52 | Building the Server |
| 20:20 | Adding Authentication |

## 原视频简介

Secure your MCP server using Descope for free: https://descope.plug.dev/W4lLipY

---

视频内容版权归原作者所有，字幕仅供学习交流。
