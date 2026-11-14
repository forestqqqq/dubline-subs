<!-- dubline-subs {"title": "7-End To End Advanced RAG Project using Open Source LLM Models And Groq Inferencing engine", "author": "Krish Naik", "files": 3, "updated": "2026-11-13"} -->
# 7-End To End Advanced RAG Project using Open Source LLM Models And Groq Inferencing engine

<img src="1c4086/76468d5a/7-End%20To%20End%20Advanced%20RAG%20Project%20using%20Open%20Source%20LLM%20Models%20And%20Groq%20Inferencing%20engine.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=QQdiHrIc84o](https://www.youtube.com/watch?v=QQdiHrIc84o) |
| 发布 | 2024-04-16 |
| 时长 | 28 分 11 秒 |
| 语言 | 英语 |
| 原作者 | [Krish Naik](https://www.youtube.com/@krishnaik06)（@krishnaik06，约 153 万订阅） |

## 中文信息

**标题**：【中配】Groq 推理引擎实测：开源大模型 RAG 应用开发全过程

**原标题译文**：7-使用开源 LLM 模型和 Groq 推理引擎的端到端高级 RAG 项目

在这期视频中，我将带大家深入实测 Groq 推理引擎的强大性能，并手把手演示如何利用开源大语言模型（如 Llama 系列和 Mistral 系列）结合 LangChain 和 FAISS 框架，从零开始构建一个完整的端到端检索增强生成（RAG）应用。随着生成式 AI 的普及，许多开发者在实际部署中遇到了传统 GPU 推理速度缓慢、响应延迟高的痛点。本视频的核心目标就是通过 Groq 引擎的高性能推理能力，配合高效的 RAG 架构，打造一个既能保证回答准确性，又能实现极速响应的 AI 应用原型。

通过本视频的学习，你将掌握一系列构建工业级 RAG 应用的核心知识点。首先，我们将深入了解 Groq LPU（语言处理单元）的技术优势，看它如何通过高计算密度和超高内存带宽来突破当前生成式 AI 推理的瓶颈。在技术实现层面，我将详细拆解以下关键步骤：

第一，数据获取与预处理：演示如何使用 WebBaseLoader 从指定的网页中抓取原始数据，并利用 RecursiveCharacterTextSplitter 工具，按照字符大小对长文档进行递归分块处理。我会讲解 chunk_size 等关键参数对检索效果的影响。

第二，向量数据库构建：讲解如何利用 FAISS 向量数据库配合嵌入模型，将处理后的文本转化为向量并进行存储。我们将重点讨论向量属性初始化这一关键配置步骤，这是很多初学者容易忽略但会导致运行时错误的核心细节。

第三，模型集成与提示词工程：演示如何使用 LangChain 的 ChatGroq 类来实例化模型，并配合 chat_template 定义复杂的提示词模板，从而规范模型的回答逻辑。同时，我会对比不同模型，例如 Mistral 7B 模型如何支持高达 32k 的长上下文长度，以应对更复杂的文档检索场景。

第四，Web 界面开发与性能优化：利用 Streamlit 框架快速构建 Web 端交互界面，并演示如何使用 st.session_state 在 Web 应用中持久化存储模型实例与会话状态。此外，我还将展示如何使用 time.process_time 函数精确计算代码执行耗时，帮助大家量化评估推理性能的提升。

本视频非常适合具备 Python 编程基础，并且对 LangChain、Streamlit 以及向量数据库基本概念有所了解的技术人员或开发者。如果你正在寻找比传统 GPU 推理更快的 AI 推理方案，或者希望学习如何将开源模型转化为可落地的生产力工具，这期视频将为你提供完整的实操路径。

看完这期视频后，你将能够独立完成从数据抓取、文本分块、向量索引到模型推理的全流程开发。你不仅能学会如何调用 Groq API 密钥并配置相应的 Python 依赖库（如 LangChain、Streamlit、BS4、FAISS），还能学会如何通过优化索引数量、调整模型选择以及处理上下文长度等手段，来不断迭代和优化你的 RAG 应用。无论你是想提升自己的技术栈，还是在寻找高效的 AI 开发方案，这期实测教程都将为你提供极具价值的参考。

原视频：7-End To End Advanced RAG Project using Open Source LLM Models And Groq Inferencing engine
原作者：Krish Naik
发布日期：2024-04-16
视频链接：https://www.youtube.com/watch?v=QQdiHrIc84o

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| 7-End To End Advanced RAG Project using Open Source LLM Models And Groq Inferencing engine - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](1c4086/1e2264cb/7-End%20To%20End%20Advanced%20RAG%20Project%20using%20Open%20Source%20LLM%20Models%20And%20Groq%20Inferencing%20engine%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/FTYMH/1c4086/1e2264cb/7-End%20To%20End%20Advanced%20RAG%20Project%20using%20Open%20Source%20LLM%20Models%20And%20Groq%20Inferencing%20engine%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](1c4086/7fbe0da8/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/FTYMH/1c4086/7fbe0da8/dubbed.srt) |
| 7-End To End Advanced RAG Project using Open Source LLM Models And Groq Inferencing engine - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](1c4086/adb56613/7-End%20To%20End%20Advanced%20RAG%20Project%20using%20Open%20Source%20LLM%20Models%20And%20Groq%20Inferencing%20engine%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/FTYMH/1c4086/adb56613/7-End%20To%20End%20Advanced%20RAG%20Project%20using%20Open%20Source%20LLM%20Models%20And%20Groq%20Inferencing%20engine%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频简介

In this video we will develop an end to end advanced Rag project using open source llm models such as Llama2, Mistral using groq inferencing engine
code github: https://github.com/krishnaik06/Updated-Langchain/tree/main/groq
---------------------------------------------------------------------------------------------
Support me by joining membership so that I can upload these kind of videos
https://www.youtube.com/channel/UCNU_lfiiWBdtULKOw6X0Dig/join
-----------------------------------------------------------------------------------
Fresh Langchain Playlist: https://www.youtube.com/watch?v=KmQOlg5YfU0&list=PLZoTAELRMXVOQPRG7VAuHL--y97opD5GQ
►LLM Fine Tuning Playlist: https://www.youtube.com/watch?v=Vg3dS-NLUT4&list=PLZoTAELRMXVN9VbAx5I2VvloTtYmlApe3
►AWS Bedrock Playlist: https://www.yout…

---

视频内容版权归原作者所有，字幕仅供学习交流。
