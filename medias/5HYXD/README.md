<!-- dubline-subs {"title": "6-Building Advanced RAG Q&A Project With Multiple Data Sources With Langchain", "author": "Krish Naik", "files": 3, "updated": "2026-11-13"} -->
# 6-Building Advanced RAG Q&A Project With Multiple Data Sources With Langchain

<img src="dcf3e7/84f28680/6-Building%20Advanced%20RAG%20Q%26A%20Project%20With%20Multiple%20Data%20Sources%20With%20Langchain.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=2_gSXyt2108](https://www.youtube.com/watch?v=2_gSXyt2108) |
| 发布 | 2024-04-15 |
| 时长 | 24 分 36 秒 |
| 语言 | 英语 |
| 原作者 | [Krish Naik](https://www.youtube.com/@krishnaik06)（@krishnaik06，约 153 万订阅） |

## 中文信息

**标题**：【中配】24 分钟，用 Langchain 整合三个数据源搞定 RAG

**原标题译文**：6-使用 Langchain 构建具有多个数据源的高级 RAG Q&A 项目

在这期视频中，我将带大家深入了解如何利用 Langchain 框架构建一个能够整合多个不同数据源的高级检索增强生成（RAG）问答系统。传统的 RAG 系统往往局限于单一的数据集，但在复杂的实际应用场景中，我们经常需要从不同的平台获取信息。本视频的核心目标就是演示如何通过封装外部工具，并利用智能体（Agent）来实现动态的工具调用，从而构建出一个能够根据用户问题自动判断并从 Wikipedia、RSIV 以及 Langsmith 等多个数据源中提取信息的智能系统。

通过本视频的学习，你将掌握一系列构建多源 RAG 应用的关键技术点。首先，我们将学习如何处理和预处理多样化的数据。视频中展示了如何使用 web-based loader 来加载自定义网站的内容，并结合 OpenAI 的嵌入模型（Embeddings）以及递归字符文本分割器（RecursiveCharacterTextSplitter）对原始数据进行有效的切片与向量化处理。接着，我们将学习如何通过 from_documents 方法将处理后的文档转换为向量数据库，并利用 as_retriever 方法生成标准化的检索器接口。

更核心的内容在于工具的封装与智能体的构建。我将演示如何使用 create_retriever_tool 函数将不同的检索器封装成独立的工具。这一步至关重要，因为只有将检索逻辑转化为工具，智能体才能识别并调用它们。在这一过程中，我们会学习如何编写精准的提示词来定义每个工具的具体任务。随后，我们将进入智能体构建阶段，学习如何使用 create_openai_tools_agent 函数创建智能体。与传统的硬编码逻辑不同，智能体利用大语言模型作为推理引擎，能够根据用户的提问动态决定行动顺序，自主选择调用哪一个工具。此外，视频还会介绍如何从 Langchain Hub 中调用通用的提示词模板，例如 openai function agent，来简化系统消息和人类消息的编写过程。最后，为了方便调试，我还会演示如何设置 agent_executor 的 verbose 参数为 True，这样你就可以清晰地看到智能体在后台是如何思考、选择工具以及执行具体步骤的。

这期视频非常适合那些已经具备 Python 编程基础，并且对大语言模型（LLM）有一定基础概念的开发者或技术人员。无论你是正在研究 RAG 技术，还是希望在自己的项目中实现多数据源整合，本视频提供的实战流程都能为你提供极大的帮助。你不需要具备极其复杂的算法背景，只要熟悉 Langchain 的基本操作，就可以跟随视频中的步骤进行动手实践。

看完这期视频后，你将能够独立完成从数据加载、向量化存储到工具封装的全套流程。你将学会如何构建一个能够处理复杂查询的智能体系统，例如当用户查询 Langsmith 的信息时，系统能自动调用 Langsmith 搜索工具；当用户询问机器学习概念时，系统能转向维基百科；而当用户查询特定论文名称时，系统则能精准调用 RSIV 数据库。通过掌握这些核心知识点，你将具备构建工业级多源 RAG 应用的能力，让你的 AI 应用能够更智能地从互联网和私有数据库中获取知识，提供更准确、更丰富的回答。

原视频：6-Building Advanced RAG Q&A Project With Multiple Data Sources With Langchain
原作者：Krish Naik
发布日期：2024-04-15
视频链接：https://www.youtube.com/watch?v=2_gSXyt2108

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](dcf3e7/7c18f7a4/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/5HYXD/dcf3e7/7c18f7a4/dubbed.srt) |
| 6-Building Advanced RAG Q&A Project With Multiple Data Sources With Langchain - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](dcf3e7/91b4ca58/6-Building%20Advanced%20RAG%20Q%26A%20Project%20With%20Multiple%20Data%20Sources%20With%20Langchain%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/5HYXD/dcf3e7/91b4ca58/6-Building%20Advanced%20RAG%20Q%26A%20Project%20With%20Multiple%20Data%20Sources%20With%20Langchain%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |
| 6-Building Advanced RAG Q&A Project With Multiple Data Sources With Langchain - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](dcf3e7/def7613a/6-Building%20Advanced%20RAG%20Q%26A%20Project%20With%20Multiple%20Data%20Sources%20With%20Langchain%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/5HYXD/dcf3e7/def7613a/6-Building%20Advanced%20RAG%20Q%26A%20Project%20With%20Multiple%20Data%20Sources%20With%20Langchain%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频简介

Hello All we are going to build Advanced RAG Projects With Multiple Data Sources as arxiv,wikipedia and others .Here we will be learnign about agents,tools,toolkits and agent executor 
Code Github: https://github.com/krishnaik06/Updated-Langchain/tree/main/agents
---------------------------------------------------------------------------------------------
Support me by joining membership so that I can upload these kind of videos
https://www.youtube.com/channel/UCNU_lfiiWBdtULKOw6X0Dig/join
-----------------------------------------------------------------------------------
Fresh Langchain Playlist: https://www.youtube.com/watch?v=KmQOlg5YfU0&list=PLZoTAELRMXVOQPRG7VAuHL--y97opD5GQ
►LLM Fine Tuning Playlist: https://www.youtube.com/watch?v=Vg3dS-NLUT4&list=PLZoTAELRMXVN9VbAx5I2VvloTtYmlApe3…

---

视频内容版权归原作者所有，字幕仅供学习交流。
