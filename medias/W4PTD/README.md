<!-- dubline-subs {"title": "Building Vagrant plugins", "author": "HashiCorp, an IBM Company", "files": 3, "updated": "2026-11-13"} -->
# Building Vagrant plugins

<img src="abaee9/b5fd2b0c/Building%20Vagrant%20plugins.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=yUuPBlobyRQ](https://www.youtube.com/watch?v=yUuPBlobyRQ) |
| 发布 | 2022-10-26 |
| 时长 | 13 分 28 秒 |
| 语言 | 英语 |
| 原作者 | [HashiCorp, an IBM Company](https://www.youtube.com/@HashiCorp)（@HashiCorp，约 7 万订阅） |

## 中文信息

**标题**：【中配】13 分钟实测，用 Go 在 Vagrant 里写一个 Guest 插件

**原标题译文**：构建 Vagrant 插件

这期视频将带大家深入了解 Vagrant 的架构演变，并手把手演示如何利用 Go 语言从零开始编写一个 Guest 插件。随着 Vagrant 版本的更新，其核心架构正经历从 Ruby 向 Go 的转型，引入了基于 Go 的新插件接口。本视频的核心目标是演示如何通过 Go 编写插件，利用 gRPC API 与 Vagrant 的 Ruby 核心进行高效交互，并最终实现对 Parrot OS 操作系统的自动检测功能。

通过本视频的学习，你可以掌握以下核心知识点：

首先，你将深入理解 Vagrant 2.3 版本引入的新插件接口架构。你会了解到 Vagrant 核心现在主要由 Go 编写，并通过 gRPC API 与外部插件进行通信。其中，视频还会详细讲解名为 Vagrant Shim 的翻译层原理，它是如何负责在 Go 插件所需的 gRPC API 与实际 Ruby API 之间进行转换的，这是理解跨语言互操作性的关键。

其次，视频将演示完整的插件构建流程。我们将从零开始构建一个名为 Parrot OS 的 Guest 插件，涵盖从克隆模板仓库、执行 go mod init 初始化到更新核心代码的每一个具体步骤。你将学习到 Guest 插件必须实现的特定组件接口，包括 detect 和 parent 等关键函数签名。

在核心逻辑层面，你将掌握 detect 函数的具体实现细节。这包括如何从 target 或 machine 对象中提取 communicator，并执行特定的系统命令（例如 cat /etc/os-release）来获取机器信息。此外，你还会学到 Go 插件如何直接调用现有的 Ruby 插件（如 Debian 插件），以及反向调用的机制，这充分展示了 Vagrant 在不同语言环境下的协同能力。

最后，视频还会涵盖插件的部署与运行机制。你会了解到 Vagrant 插件的安装路径位于 .vagrant/plugins 目录，并支持全局或项目级别的安装。同时，视频会解释 Vagrant serve 是如何作为一个长驻进程运行，充当 gRPC 服务器并加载所有已安装插件的。你还将看到 Guest 检测通常在 SSH 连接建立后触发的完整流程，以及如何通过 UI.output 将检测结果实时输出给用户。

本视频非常适合以下人群观看：
如果你是一名具备 Go 语言基础语法知识的开发者，并且希望利用 Go 语言来扩展 Vagrant 的功能，那么这期视频将为你提供实操指南。
如果你是运维人员，需要编写 Guest 插件来支持特定的操作系统环境，本视频提供的从零构建到安装验证的流程将非常有帮助。
如果你是对 HashiCorp 多云基础设施自动化架构感兴趣的技术人员，通过学习本视频中关于 gRPC 通信、Shim 翻译层以及跨语言插件交互的内容，可以帮助你更深刻地理解现代基础设施工具的底层设计思路。

看完这期视频后，你将能够独立完成从插件代码编写到二进制文件编译、安装以及最终在 Vagrant 环境中验证插件功能的全过程。你将不仅掌握如何为 Parrot OS 编写检测插件，更将掌握一套通用的、基于 Go 和 gRPC 的 Vagrant 插件开发方法论，能够应对更多复杂的自定义扩展需求。

原视频：Building Vagrant plugins
原作者：HashiCorp, an IBM Company
发布日期：2022-10-26
视频链接：https://www.youtube.com/watch?v=yUuPBlobyRQ

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| Building Vagrant plugins - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](abaee9/12c42d9d/Building%20Vagrant%20plugins%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/W4PTD/abaee9/12c42d9d/Building%20Vagrant%20plugins%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| Building Vagrant plugins - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](abaee9/4d1ec4ef/Building%20Vagrant%20plugins%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/W4PTD/abaee9/4d1ec4ef/Building%20Vagrant%20plugins%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](abaee9/b42a65ee/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/W4PTD/abaee9/b42a65ee/dubbed.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频简介

With Vagrant 2.3 released, there is a whole new Go based interface for building with Vagrant. The goal of this talk is to briefly introduce the viewer to the new Go based Vagrant plugin interface. Learn more → https://developer.hashicorp.com/vagrant/tutorials

---

视频内容版权归原作者所有，字幕仅供学习交流。
