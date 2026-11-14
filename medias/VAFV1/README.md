<!-- dubline-subs {"title": "3-Langchain Series-Production Grade Deployment LLM As API With Langchain And FastAPI", "author": "Krish Naik", "files": 3, "updated": "2026-11-13"} -->
# 3-Langchain Series-Production Grade Deployment LLM As API With Langchain And FastAPI

<img src="3c672f/2f845c5d/3-Langchain%20Series-Production%20Grade%20Deployment%20LLM%20As%20API%20With%20Langchain%20And%20FastAPI.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=XWB5DXP-DO8](https://www.youtube.com/watch?v=XWB5DXP-DO8) |
| 发布 | 2024-04-03 |
| 时长 | 27 分 11 秒 |
| 语言 | 英语 |
| 原作者 | [Krish Naik](https://www.youtube.com/@krishnaik06)（@krishnaik06，约 153 万订阅） |

## 中文信息

**标题**：【中配】27 分钟，用 LangServe 把 OpenAI 和 Llama 封装成 API

**原标题译文**：3-Langchain 系列-使用 Langchain 和 FastAPI 将 LLM 作为 API 进行生产级部署

这期视频将带你深入了解如何利用 LangServe 和 FastAPI 这两个强大的工具，将不同的大语言模型高效地封装成生产级的 REST API。无论你是想调用 OpenAI 的强大能力，还是希望集成 Claude 甚至是在本地运行的 Llama 2 模型，本视频都将为你提供一套完整的实操方案。我们将从基础的工具介绍开始，逐步过渡到多模型路由的定义逻辑，最后通过构建一个包含前端交互层的完整 Python Web 应用，展示如何实现端到端的 RAG 应用调用。

在视频中，你将学到一系列非常实用的核心知识点。首先，我们将探讨 LangServe 是如何将 LangChain 的 Runnable 和 Chain 无缝集成到 FastAPI 应用中的。你会看到如何使用 add_route 函数，将不同的模型以及预设的提示词模板绑定到独立的路由路径上。例如，通过定义不同的路由路径如 /essay 和 /poem，你可以实现在单一 API 入口下处理多种不同的大模型交互逻辑。此外，视频还会详细讲解如何在代码中利用 os.getenv 安全地加载环境变量，确保你的 OpenAI Key 或 Ollama URL 等敏感信息不会泄露。

除了后端逻辑，我们还会重点演示 FastAPI 的一些便捷功能，比如它如何自动生成 Swagger UI 文档，这对于开发者快速查看 API 的输入输出架构非常有帮助。在实际开发过程中，我们还会遇到各种棘手的环境问题，比如由于缺少 sse-starlette 依赖导致的导入错误，视频中会演示如何通过更新 requirement.txt 文件并使用 pip install 命令来准确解决这些 Python 依赖问题。

为了让你的应用更具实用性，我们还将引入 Streamlit 框架。你将学习如何利用 Streamlit 快速构建交互式的前端界面，包括如何添加文本输入框以及如何展示模型返回的结果。在调用大模型 API 时，我们会演示如何构造标准的 JSON 数据（例如包含 topic 参数），并学习如何解析返回结果中的 output 字段。最后，我们将使用 requests 库发送 HTTP POST 请求，这是调用后端 API 的标准方式，也是将模型能力转化为实际产品服务的关键步骤。

本视频非常适合以下几类观众：首先是希望将自己开发的 LangChain 应用部署为 REST API 的开发者，如果你已经写好了逻辑但不知道如何对外提供接口，这期内容就是为你准备的。其次是需要集成 OpenAI、Claude 或本地大模型（如 Llama 2）的技术人员，视频提供的多模型路由方案能帮助你快速构建统一的后端服务。最后，如果你是熟悉 Python 基础但想要进阶学习 FastAPI 和 Streamlit 框架的初学者，本视频提供的从环境配置到前端展示的全流程教学，将帮助你快速上手并构建出可运行的 Demo。

看完这期视频后，你将能够独立完成从模型接入到接口封装的全过程。你不仅能掌握如何将不同模型的能力封装成可复用的接口，从而支持跨设备的统一交互，还能学会如何构建一个包含前端 UI 的完整 Web 应用。通过实践视频中的步骤，你可以亲手搭建出一个能够处理作文生成、诗歌创作等多种任务的 API 服务，并能在本地通过 Streamlit 界面进行实测验证。无论你是为了完成项目需求，还是为了提升自己的全栈开发能力，这期视频提供的实操经验都将为你提供巨大的帮助。

原视频：3-Langchain Series-Production Grade Deployment LLM As API With Langchain And FastAPI
原作者：Krish Naik
发布日期：2024-04-03
视频链接：https://www.youtube.com/watch?v=XWB5DXP-DO8

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](3c672f/0e24e8b2/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/VAFV1/3c672f/0e24e8b2/dubbed.srt) |
| 3-Langchain Series-Production Grade Deployment LLM As API With Langchain And FastAPI - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](3c672f/475636e4/3-Langchain%20Series-Production%20Grade%20Deployment%20LLM%20As%20API%20With%20Langchain%20And%20FastAPI%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/VAFV1/3c672f/475636e4/3-Langchain%20Series-Production%20Grade%20Deployment%20LLM%20As%20API%20With%20Langchain%20And%20FastAPI%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |
| 3-Langchain Series-Production Grade Deployment LLM As API With Langchain And FastAPI - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](3c672f/705ceae8/3-Langchain%20Series-Production%20Grade%20Deployment%20LLM%20As%20API%20With%20Langchain%20And%20FastAPI%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/VAFV1/3c672f/705ceae8/3-Langchain%20Series-Production%20Grade%20Deployment%20LLM%20As%20API%20With%20Langchain%20And%20FastAPI%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频简介

github: https://github.com/krishnaik06/Updated-Langchain
LangServe helps developers deploy LangChain runnables and chains as a REST API.This library is integrated with FastAPI and uses pydantic for data validation.In addition, it provides a client that can be used to call into runnables deployed on a server. A JavaScript client is available in LangChain.js.
#krishnaik
---------------------------------------------------------------------------------------------
Support me by joining membership so that I can upload these kind of videos
https://www.youtube.com/channel/UCNU_lfiiWBdtULKOw6X0Dig/join
-----------------------------------------------------------------------------------
►LLM Fine Tuning Playlist: https://www.youtube.com/watch?v=Vg3dS-NLUT4&list=PLZoTAELRMXVN9VbAx5I2VvloTtYmlApe3
►AW…

---

视频内容版权归原作者所有，字幕仅供学习交流。
