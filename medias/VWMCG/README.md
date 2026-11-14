<!-- dubline-subs {"title": "8-Building Gen AI Powered App Using Langchain And Huggingface And Mistral", "author": "Krish Naik", "files": 3, "updated": "2026-11-13"} -->
# 8-Building Gen AI Powered App Using Langchain And Huggingface And Mistral

<img src="89da77/e0e8ee8f/8-Building%20Gen%20AI%20Powered%20App%20Using%20Langchain%20And%20Huggingface%20And%20Mistral.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=RZ2Vu8z-P1Q](https://www.youtube.com/watch?v=RZ2Vu8z-P1Q) |
| 发布 | 2024-04-20 |
| 时长 | 29 分 47 秒 |
| 语言 | 英语 |
| 原作者 | [Krish Naik](https://www.youtube.com/@krishnaik06)（@krishnaik06，约 153 万订阅） |

## 中文信息

**标题**：【中配】29 分钟，用 Langchain 手搓私有 PDF 问答机器人

**原标题译文**：8-使用 Langchain、Huggingface 和 Mistral 构建生成式 AI 应用

在这期视频中，我将带大家从零开始，手把手教大家如何构建一个完整的端到端生成式 AI 问答应用。我们将利用目前主流的 Langchain 框架，结合 Hugging Face 上的开源大语言模型 Mistral 以及 FAISS 向量数据库，实现基于私有 PDF 文档的检索增强生成（RAG）技术。这不仅是一个简单的代码演示，更是一个完整的技术链路拆解，旨在帮助大家理解如何让 AI 模型能够基于你提供的特定私有数据，给出准确且符合事实的回答，从而有效解决大模型在处理特定领域知识时容易出现的幻觉问题。

通过本期视频的学习，你将掌握以下核心知识点：

首先是 RAG 技术的整体架构。你将了解到 RAG 是如何通过结合外部知识库与大模型能力来增强回答准确性的。我们将学习如何利用 PyPDFDirectoryLoader 数据加载器高效读取 PDF 文件，并使用 RecursiveCharacterTextSplitter 文本分割器对内容进行处理。在这一过程中，我会详细讲解文本分割的策略，例如如何设置块大小为 1000 字符，并配合 200 字符的重叠量，以在保证上下文完整性的同时兼顾检索效率，防止关键信息在切分过程中丢失。

其次是向量数据库与嵌入模型的应用。视频中将演示如何使用 Sentence Transformers 库提供的 all-MiniLM-L6-v2 开源嵌入模型，将处理后的文本转换为数值向量。随后，我们将这些向量存储到 FAISS 向量数据库中。FAISS 作为一种常用的本地向量数据库，能够支持高效的相似度搜索操作，这是构建本地 AI 应用的关键环节。

接着是模型配置与提示词工程。我们将学习如何通过 Hugging Face Hub API 在无需本地 GPU 的情况下调用 Mistral 7B 开源大语言模型。我会演示如何配置关键的超参数，例如将温度值（Temperature）设置为 0.1 以降低输出的随机性，确保模型在处理事实性问答时更加稳定，并设置最大长度为 500。同时，我还会讲解如何编写有效的提示词模板，明确约束模型仅依据提供的上下文内容来回答问题。

最后是自动化流程的串联。我们将学习如何构建 RetrievalQA Chain 检索问答链，将检索器、大语言模型和提示词模板串联成一个自动化的处理流程。我会演示如何设置检索参数 k 值（通常设为 3），以确保系统能获取到足够的多源信息。通过这些步骤，我们将完成从原始 PDF 数据到最终问答输出的全流程闭环。

本视频非常适合以下人群观看：首先是希望快速掌握 Langchain 和 RAG 技术栈的开发者，视频涵盖了从数据加载到链式调用的完整链路；其次是需要处理私有文档（如 PDF）并构建本地 AI 应用的工程师，你可以直接参考视频中的工程实践；最后，如果你是对开源大模型部署、向量数据库应用以及提示词工程感兴趣的初学者，这期视频也能为你提供清晰的入门路径。

看完这期视频后，你将能够独立完成从零到一的私有 PDF 问答机器人构建。你将学会如何处理复杂的 PDF 数据流，掌握向量检索的核心逻辑，并能够熟练运用 Langchain 框架组装出功能完善的 RAG 应用。通过实操练习，你将能够验证系统是否能基于特定的 PDF 数据集（如视频中使用的 US Census 数据）准确回答关于保险覆盖范围或州间差异等具体问题，真正实现让 AI 成为你的私人知识库助手。

原视频：8-Building Gen AI Powered App Using Langchain And Huggingface And Mistral
原作者：Krish Naik
发布日期：2024-04-20
视频链接：https://www.youtube.com/watch?v=RZ2Vu8z-P1Q

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| 8-Building Gen AI Powered App Using Langchain And Huggingface And Mistral - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](89da77/16ed5052/8-Building%20Gen%20AI%20Powered%20App%20Using%20Langchain%20And%20Huggingface%20And%20Mistral%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/VWMCG/89da77/16ed5052/8-Building%20Gen%20AI%20Powered%20App%20Using%20Langchain%20And%20Huggingface%20And%20Mistral%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| 8-Building Gen AI Powered App Using Langchain And Huggingface And Mistral - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](89da77/45bd585f/8-Building%20Gen%20AI%20Powered%20App%20Using%20Langchain%20And%20Huggingface%20And%20Mistral%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/VWMCG/89da77/45bd585f/8-Building%20Gen%20AI%20Powered%20App%20Using%20Langchain%20And%20Huggingface%20And%20Mistral%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](89da77/8ced4e94/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/VWMCG/89da77/8ced4e94/dubbed.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频简介

In this video we will be building an end to end langchain project using hugging open source llm models such as Mistral and also open source embedding models. 
code github: https://github.com/krishnaik06/Updated-Langchain
-------------------------------------------------------------------------------------------------
Support me by joining membership so that I can upload these kind of videos
https://www.youtube.com/channel/UCNU_lfiiWBdtULKOw6X0Dig/join
-----------------------------------------------------------------------------------
Fresh Langchain Playlist: https://www.youtube.com/watch?v=KmQOlg5YfU0&list=PLZoTAELRMXVOQPRG7VAuHL--y97opD5GQ
►LLM Fine Tuning Playlist: https://www.youtube.com/watch?v=Vg3dS-NLUT4&list=PLZoTAELRMXVN9VbAx5I2VvloTtYmlApe3
►AWS Bedrock Playlist: https://www.yout…

---

视频内容版权归原作者所有，字幕仅供学习交流。
