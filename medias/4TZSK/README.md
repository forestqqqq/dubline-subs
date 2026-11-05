<!-- dubline-subs {"title": "[Learn Lab] Create a Terraform provider with the Plugin Framework", "author": "HashiCorp, an IBM Company", "files": 2, "updated": "2026-11-05"} -->
# [Learn Lab] Create a Terraform provider with the Plugin Framework

<img src="547180/6cad7f8d/%5BLearn%20Lab%5D%20Create%20a%20Terraform%20provider%20with%20the%20Plugin%20Framework.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=16qs7LJSyps](https://www.youtube.com/watch?v=16qs7LJSyps) |
| 发布 | 2023-10-25 |
| 时长 | 1 小时 2 分 19 秒 |
| 语言 | 英语 |
| 原作者 | [HashiCorp, an IBM Company](https://www.youtube.com/@HashiCorp)（@HashiCorp，约 7 万订阅） |

## 中文信息

**标题**：【中配】1 小时实操，用 Go 语言手写一个自定义 Terraform Provider

**原标题译文**：[Learn Lab] 使用 Plugin Framework 创建 Terraform provider

在这期视频中，我将带大家深入了解 Terraform Provider 的底层原理，并手把手教大家如何使用 Go 语言从零开始构建一个自定义的 Terraform Provider。我们将全程采用最新的 HashiCorp Plugin Framework（Go SDK）作为开发框架，涵盖从基础环境的初始化、认证逻辑的编写到最终对接真实数据源的全流程。无论你是想修复现有 Provider 中的 Bug，还是需要为公司内部的新产品开发专属的 Provider，亦或是为了管理公司私有云资源而需要定制化工具，这期实操教学都将为你提供完整的技术路径。

通过本视频的学习，你将掌握以下核心知识点：

首先是关于 Terraform Provider 的核心原理。你会了解到 Provider 本质上是使用 Go 语言编写的插件，它通过 RPC 机制与 Terraform Core 进行通信，并利用客户端库通过 HTTPS 协议与目标 API 进行交互。理解这一架构是进行自定义开发的基础。

其次是关于现代化的开发工具链。我们将使用最新的 Plugin Framework，并利用官方提供的脚手架工具，学习如何配置 Makefile 和 GitHub Actions 来自动化和规范化开发流程。

第三是高效的开发调试技巧，即开发者覆盖（Developer Override）。我会演示如何通过修改 Terraformrc 文件，将 Provider 的路径指向本地的 go bin 目录。这一技巧能让你在不需要发布到注册表的情况下，实现极速的本地迭代和调试循环。

第四是核心代码的逻辑实现。我们将深入剖析 configure 函数，学习如何获取用户配置属性、验证必要参数、处理敏感信息（Sensitive）以及初始化客户端。同时，我还会强调职责分离（Separation of Concerns）的原则，讲解如何将客户端库逻辑与 Provider 代码分离，从而实现客户端的独立测试并快速定位 Bug。

最后是数据源逻辑的迁移与模型映射。我们将学习如何将最初的桩代码（Stub）转换为真实的数据源逻辑，并掌握如何定义与 Terraform 匹配的 Go 数据模型，确保底层类型能够准确转换为 Terraform 基础类型并正确写入 State 文件。

本视频非常适合具备基础 Go 语言编程能力、熟悉 Terraform 基本概念（如 Provider、Resource、Data Source、State）的 Go 语言开发者、DevOps 工程师，以及需要为公司内部产品或私有云资源开发自定义 Provider 的技术人员。如果你已经掌握了 Docker 的基本操作，并且希望从理论走向实操，这期视频将是你的最佳入门指南。

看完这期视频后，你将能够独立完成一个自定义 Provider 的基础框架搭建。你将学会如何搭建包含数据库和 API 环境的本地测试环境，能够熟练编写 Provider 的核心结构，并能够通过 terraform plan 命令验证认证逻辑和数据获取是否正常。通过本视频的实操，你将具备从零构建、调试并对接真实 API 的能力，为你的基础设施自动化管理提供更强大的自定义支撑。

原视频：[Learn Lab] Create a Terraform provider with the Plugin Framework
原作者：HashiCorp, an IBM Company
发布日期：2023-10-25
视频链接：https://www.youtube.com/watch?v=16qs7LJSyps

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](547180/7830adec/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/4TZSK/547180/7830adec/dubbed.srt) |
| [Learn Lab] Create a Terraform provider with the Plugin Framework - 英语字幕.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](547180/a4d92ce4/%5BLearn%20Lab%5D%20Create%20a%20Terraform%20provider%20with%20the%20Plugin%20Framework%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/4TZSK/547180/a4d92ce4/%5BLearn%20Lab%5D%20Create%20a%20Terraform%20provider%20with%20the%20Plugin%20Framework%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95.en.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频简介

Create a Terraform provider with HashiCorp’s Plugin Framework. Terraform providers let you manage resources via their underlying product APIs. The Plugin Framework is a Go SDK you will use to develop your own Terraform providers.

---

视频内容版权归原作者所有，字幕仅供学习交流。
