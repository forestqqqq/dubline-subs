<!-- dubline-subs {"title": "AI Engineering Full Course - Build and Deploy a Real AI App", "author": "Dave Ebbelaar", "files": 3, "updated": "2026-11-27"} -->
# AI Engineering Full Course - Build and Deploy a Real AI App

<img src="ae98da/da19b8c2/AI%20Engineering%20Full%20Course%20-%20Build%20and%20Deploy%20a%20Real%20AI%20App.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=XzjSx7u9mGw](https://www.youtube.com/watch?v=XzjSx7u9mGw) |
| 发布 | 2026-10-30 |
| 时长 | 3 小时 10 分 6 秒 |
| 语言 | 英语 |
| 原作者 | [Dave Ebbelaar](https://www.youtube.com/@daveebbelaar)（@daveebbelaar，约 31 万订阅） |

## 中文信息

**标题**：【中配】3 小时实战：手搓一个生产级的 AI 客服代理系统

**原标题译文**：AI 工程全课程 - 构建并部署真实的 AI 应用

这期视频是一门完整的 AI 工程实战课程，旨在带领大家从零开始构建一个真正具备生产能力的 AI 客服代理系统。我们不仅是简单地调用一个 API，而是要完整走通从邮件接入、后端逻辑处理、AI 代理流水线构建、数据库持久化到前端管理后台开发，最后到 Docker 容器化部署的全栈开发流程。通过这期视频，你将亲手打造出一个能够处理真实业务逻辑的 AI 应用，涵盖了从数据抓取到用户交互的每一个核心环节。

在实战过程中，你将掌握以下核心知识点：

首先是基础架构与数据交互。我们将学习如何对接 Gmail API 并建立轮询机制，在不需要公共域名的情况下，通过每 30 到 60 秒一次的轮询实现自动化邮件获取。同时，我们将深入学习如何利用 Pydantic 构建严格的数据模型，将 AI 输出从模糊的字符串转化为可程序化控制的结构化数据，这是构建稳健系统的关键。

其次是 AI 代理的设计与优化。我们将使用 PydanticAI 框架来定义分类器和代理，并遵循逻辑分支优先的原则，通过代码逻辑来处理复杂业务，而不是试图把所有逻辑都塞进提示词里。为了防止 AI 产生幻觉，我们将引入护栏机制和自我反思环节，增加承诺行动布尔字段来确保输出的可靠性。此外，你还将学习如何建立自动化评估脚本，通过自我修正循环来诊断模型错误并微调提示词，从而避免针对特定案例的过拟合问题。

最后是工程化部署与全栈整合。视频涵盖了如何利用种子脚本动态导入品牌基调和退货规则等知识库内容，以及如何实施生产环境的安全防护，包括 IP 地址限制数据库连接池。最后，我们将使用 React 开发管理后台，实现与数据库的实时联动，提供可视化的工单监控界面，并最终通过 Docker 容器确保服务在后台持续稳定运行。

本视频非常适合希望从零构建生产级 AI 应用的开发者、AI 工程初学者，或者是想要通过实战项目提升简历竞争力的求职者。如果你具备基础的 Python 编程能力、Node.js 基础，并且对 Git 操作以及 Docker 容器的基本概念有所了解，那么这期视频将是你的最佳实战指南。

看完这期视频后，你将能够独立完成一个完整的 AI 客服代理系统。你不仅能掌握 FastAPI、PydanticAI、Claude、Supabase、Docker 和 React 等主流技术栈的综合运用，还能学会如何设计复杂的 AI 流水线，并具备从零搭建、部署到维护生产级 AI 应用的全套实战能力。

章节
0:00:00 介绍
0:06:57 项目准备
0:20:37 Gmail API 访问
0:36:23 Gmail 客户端
0:45:27 轮询机制
0:53:48 数据库
1:10:36 首次回复
1:18:14 知识库
1:23:21 AI 流水线
1:55:31 评估
2:08:41 服务器设置
2:23:41 使用 Docker 部署
2:44:54 管理后台
3:05:19 总结

原视频：AI Engineering Full Course - Build and Deploy a Real AI App
原作者：Dave Ebbelaar
发布日期：2026-10-30
视频链接：https://www.youtube.com/watch?v=XzjSx7u9mGw

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](33bb93/14ec6ca8/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/YG3XA/33bb93/14ec6ca8/dubbed.srt) |
| AI Engineering Full Course - Build and Deploy a Real AI App - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](33bb93/a927fc94/AI%20Engineering%20Full%20Course%20-%20Build%20and%20Deploy%20a%20Real%20AI%20App%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/YG3XA/33bb93/a927fc94/AI%20Engineering%20Full%20Course%20-%20Build%20and%20Deploy%20a%20Real%20AI%20App%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |
| AI Engineering Full Course - Build and Deploy a Real AI App - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](33bb93/c6c5099f/AI%20Engineering%20Full%20Course%20-%20Build%20and%20Deploy%20a%20Real%20AI%20App%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/YG3XA/33bb93/c6c5099f/AI%20Engineering%20Full%20Course%20-%20Build%20and%20Deploy%20a%20Real%20AI%20App%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频章节

| 时间 | 章节 |
|---|---|
| 0:00:00 | Introduction |
| 0:06:57 | Project setup |
| 0:20:37 | Gmail API access |
| 0:36:23 | Gmail client |
| 0:45:27 | The poller |
| 0:53:48 | Database |
| 1:10:36 | First reply |
| 1:18:14 | Knowledge base |
| 1:23:21 | AI pipeline |
| 1:55:31 | Evals |
| 2:08:41 | Server setup |
| 2:23:41 | Deploy with Docker |
| 2:44:54 | Admin dashboard |
| 3:05:19 | Wrap up |

## 原视频简介

In this full AI Engineering course, I show you how to build an AI customer support agent from start to finish.

---

视频内容版权归原作者所有，字幕仅供学习交流。
