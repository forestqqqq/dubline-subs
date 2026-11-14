<!-- dubline-subs {"title": "4-Langchain Series-Getting Started With RAG Pipeline Using Langchain Chromadb And FAISS", "author": "Krish Naik", "files": 3, "updated": "2026-11-13"} -->
# 4-Langchain Series-Getting Started With RAG Pipeline Using Langchain Chromadb And FAISS

<img src="07aa44/41ad6b52/4-Langchain%20Series-Getting%20Started%20With%20RAG%20Pipeline%20Using%20Langchain%20Chromadb%20And%20FAISS.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=9Thc6hRw2Gs](https://www.youtube.com/watch?v=9Thc6hRw2Gs) |
| 发布 | 2024-04-07 |
| 时长 | 30 分 21 秒 |
| 语言 | 英语 |
| 原作者 | [Krish Naik](https://www.youtube.com/@krishnaik06)（@krishnaik06，约 153 万订阅） |

## 中文信息

**标题**：【中配】30 分钟，用 Langchain 手搓一个能跑 RAG 流水线

**原标题译文**：4-Langchain 系列-使用 Langchain、ChromaDB 和 FAISS 构建 RAG 流水线入门

在当前的大模型应用开发中，如何让 AI 处理企业内部的私有数据或者刚刚发布的实时资讯，是每一个开发者都会遇到的核心痛点。由于大模型的训练数据存在截止日期，且无法直接访问你的本地文件或私有数据库，单纯依靠提示词工程往往难以获得精准的回答。为了解决这一问题，检索增强生成（RAG）技术成为了目前工业界最主流的解决方案。本期视频将带大家深入浅出地实操一遍，仅用 30 分钟时间，带你利用 Langchain 框架从零开始手搓一套完整的 RAG 流水线，带你走通从原始数据到最终检索结果的全流程。

通过本期视频的学习，你将掌握 RAG 架构的核心组件及其在企业级开发中的必要性。我们将从最基础的数据获取开始，演示如何使用 Langchain 提供的多种数据加载工具，包括用于处理纯文本的 TextLoader、用于抓取网页内容的 WebBaseLoader，以及专门解析本地 PDF 文件的 PyPDFLoader。在实际操作中，你会看到如何配合 BeautifulSoup 库和 CSS 选择器来精准提取网页中的特定信息块，并学习如何解析像 Attention Is All You Need 这样的专业 PDF 文档。

除了数据加载，视频还会重点讲解非结构化文本的处理策略。你会学到为什么长文档必须切分为小片段，这是为了适应大模型的上下文长度限制并提升检索效率。我们将深入探讨 RecursiveCharacterTextSplitter 的具体用法，学习如何通过调整 chunk_size 和 chunk_overlap 参数来平衡片段大小与语义连贯性，确保在切分过程中不会丢失关键的上下文信息。

在向量化环节，视频将演示如何使用 OpenAIEmbeddings 类将文本转换为高维向量表示，并对比不同嵌入模型在性能上的差异。随后，我们将进入向量数据库的部署环节，实操演示两种主流的本地向量数据库方案：ChromaDB 和 FAISS。你会看到如何通过 chroma.from_documents() 和 FAISS.from_documents() 方法将处理好的文档片段与向量信息存储到数据库中。最后，我们将执行相似度检索测试，通过 db.similarity_search(query) 方法验证 RAG 流水线的完整闭环，实测模型是否能准确回答关于论文作者、模型维度以及注意力机制等关键细节问题。

这期视频非常适合那些希望构建能够处理私有数据或新发布内容的 AI 应用开发者。如果你是一名熟悉 Python 编程基础，并且已经初步了解 Langchain 基础概念，但目前在向量数据库实战经验上感到迷茫的技术人员，那么这期视频将为你提供极具价值的实操指南。

看完这期视频后，你将能够独立完成从数据加载、文本分块、向量化到数据库存储的完整 RAG 开发流程。你将掌握如何根据不同的数据源选择合适的加载器，学会科学地对长文档进行分块处理，能够熟练操作 ChromaDB 和 FAISS 两种主流向量数据库，并最终能够构建出一个能够准确检索并回答特定问题的 RAG 流水线原型。无论你是想为公司内部文档做一个知识库，还是想开发一个基于特定领域的 AI 助手，这期视频提供的实战经验都将为你打下坚实的技术基础。

原视频：4-Langchain Series-Getting Started With RAG Pipeline Using Langchain Chromadb And FAISS
原作者：Krish Naik
发布日期：2024-04-07
视频链接：https://www.youtube.com/watch?v=9Thc6hRw2Gs

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| 4-Langchain Series-Getting Started With RAG Pipeline Using Langchain Chromadb And FAISS - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](07aa44/18efa20a/4-Langchain%20Series-Getting%20Started%20With%20RAG%20Pipeline%20Using%20Langchain%20Chromadb%20And%20FAISS%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/NSY2A/07aa44/18efa20a/4-Langchain%20Series-Getting%20Started%20With%20RAG%20Pipeline%20Using%20Langchain%20Chromadb%20And%20FAISS%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](07aa44/36d8e278/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/NSY2A/07aa44/36d8e278/dubbed.srt) |
| 4-Langchain Series-Getting Started With RAG Pipeline Using Langchain Chromadb And FAISS - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](07aa44/98cb5da5/4-Langchain%20Series-Getting%20Started%20With%20RAG%20Pipeline%20Using%20Langchain%20Chromadb%20And%20FAISS%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/NSY2A/07aa44/98cb5da5/4-Langchain%20Series-Getting%20Started%20With%20RAG%20Pipeline%20Using%20Langchain%20Chromadb%20And%20FAISS%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频简介

RAG is a technique for augmenting LLM knowledge with additional data.
LLMs can reason about wide-ranging topics, but their knowledge is limited to the public data up to a specific point in time that they were trained on. If you want to build AI applications that can reason about private data or data introduced after a model’s cutoff date, you need to augment the knowledge of the model with the specific information it needs. The process of bringing the appropriate information and inserting it into the model prompt is known as Retrieval Augmented Generation (RAG).
github: https://github.com/krishnaik06/Updated-Langchain
---------------------------------------------------------------------------------------------
Support me by joining membership so that I can upload these kind of videos
https…

---

视频内容版权归原作者所有，字幕仅供学习交流。
