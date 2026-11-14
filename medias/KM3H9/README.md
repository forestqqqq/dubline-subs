<!-- dubline-subs {"title": "Getting Started with On-Device AI: RAG using ObjectBox Vector Database and LangChain", "author": "Krish Naik", "files": 3, "updated": "2026-11-13"} -->
# Getting Started with On-Device AI: RAG using ObjectBox Vector Database and LangChain

<img src="fa358e/4858d652/Getting%20Started%20with%20On-Device%20AI%20RAG%20using%20ObjectBox%20Vector%20Database%20and%20LangChain.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=9LewL1bUS6g](https://www.youtube.com/watch?v=9LewL1bUS6g) |
| 发布 | 2024-05-16 |
| 时长 | 29 分 35 秒 |
| 语言 | 英语 |
| 原作者 | [Krish Naik](https://www.youtube.com/@krishnaik06)（@krishnaik06，约 153 万订阅） |

## 中文信息

**标题**：【中配】29 分钟实测：用开源库在本地跑离线 RAG

**原标题译文**：入门端侧 AI：使用 ObjectBox Vector Database 和 LangChain 进行 RAG

在这期视频中，我将带大家深入实测如何利用开源技术栈在本地设备上构建一套完全离线的检索增强生成（RAG）应用。随着大模型技术的普及，很多开发者和企业在实际落地过程中都会面临数据隐私泄露和网络延迟的难题。本视频的核心目标就是展示如何通过 ObjectBox 向量数据库与 LangChain 框架的结合，在无需互联网连接的情况下，让大模型能够精准访问并推理你的私有数据。我们将从基础的环境配置开始，一步步完整走通从文档加载、分块切片、向量嵌入存储到最终生成问答的全流程，并实测其在本地边缘设备上的运行效果。

通过本视频的学习，你可以掌握以下核心知识点：

首先是关于 RAG 技术的深度理解。你会了解到检索增强生成是如何通过主动扩充语言模型的知识库，来提升 AI 对私有数据以及最新信息的访问与推理能力的。相比于单纯依赖模型自身的权重，RAG 能够显著增强模型在特定垂直领域的表现。

其次是核心组件的实操应用。视频中详细介绍了 ObjectBox 向量数据库。作为一款支持多语言的完全开源向量数据库，它具备离线优先架构和高性能的本地持久化能力。相比于许多依赖云端的方案，本地向量数据库不仅能有效保护数据隐私，还能减少 40% 以上的移动和云端成本。

在技术实现层面，我们将深入探讨 LangChain 框架提供的标准化组件。包括如何使用 PyPDFDirectoryLoader 加载 PDF 文档，以及如何利用递归字符分割器（RecursiveCharacterTextSplitter）将长文档智能切分为适合向量索引的文本块。此外，视频还会讲解如何设置 768 维度的向量嵌入来存储文本语义信息，并演示如何使用 StuffDocumentsChain 这种简单的文档处理策略，将上下文直接注入到提示词中。

在交互与推理环节，我将演示如何结合 Ollama 在本地运行 Llama 3 等大语言模型，实现完全离线的推理与问答。同时，利用 Streamlit 框架，你可以快速搭建出一个具备交互功能的本地演示应用，并学习如何通过 session_state 来管理数据库状态，确保用户交互的连贯性。

本视频非常适合以下人群观看：

如果你是一名希望将 AI 能力部署到手机、物联网（IoT）或嵌入式设备等边缘端开发的开发者，本视频提供的本地化方案将为你提供极具价值的参考。如果你是关注数据隐私、要求在无需联网的情况下也能使用大模型能力的企业技术人员，这里展示的离线架构正是你需要的技术路径。此外，如果你具备基础的 Python 编程知识，并且对 LangChain 和 Streamlit 框架感兴趣，那么本视频将带你从零开始构建出一个完整的本地 RAG 项目。

看完这期视频后，你将能够独立完成以下操作：

首先，你可以熟练配置本地开发环境，通过简单的命令安装必要的库文件。其次，你能够掌握完整的 RAG 逻辑架构，包括如何处理 PDF 文档、如何进行文本切片以及如何调用嵌入模型。最重要的是，你将学会如何将 ObjectBox 与 LangChain 串联，在本地建立起一套高效的向量索引系统。最后，你将能够亲手搭建出一个拥有图形化界面的本地问答应用，并在保证数据不出本地的前提下，实现对私有文档的精准检索与智能问答。无论你是想优化现有的 AI 工作流，还是想探索边缘计算中的 AI 应用，这期实测视频都将为你提供实操性的技术支持。

原视频：Getting Started with On-Device AI: RAG using ObjectBox Vector Database and LangChain
原作者：Krish Naik
发布日期：2024-05-16
视频链接：https://www.youtube.com/watch?v=9LewL1bUS6g

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| Getting Started with On-Device AI RAG using ObjectBox Vector Database and LangChain - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](fa358e/b8adb3cf/Getting%20Started%20with%20On-Device%20AI%20RAG%20using%20ObjectBox%20Vector%20Database%20and%20LangChain%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/KM3H9/fa358e/b8adb3cf/Getting%20Started%20with%20On-Device%20AI%20RAG%20using%20ObjectBox%20Vector%20Database%20and%20LangChain%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |
| Getting Started with On-Device AI RAG using ObjectBox Vector Database and LangChain - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](fa358e/e91a220f/Getting%20Started%20with%20On-Device%20AI%20RAG%20using%20ObjectBox%20Vector%20Database%20and%20LangChain%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/KM3H9/fa358e/e91a220f/Getting%20Started%20with%20On-Device%20AI%20RAG%20using%20ObjectBox%20Vector%20Database%20and%20LangChain%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](fa358e/f3595578/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/KM3H9/fa358e/f3595578/dubbed.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频简介

Today, we're exploring on-device AI / Edge AI, where the hardware isn’t a limit and the cloud optional.

---

视频内容版权归原作者所有，字幕仅供学习交流。
