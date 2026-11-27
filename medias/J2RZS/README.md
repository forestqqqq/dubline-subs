<!-- dubline-subs {"title": "Next.js Explained in 10 Minutes(How It Really Works)", "author": "Frontend School", "files": 3, "updated": "2026-11-26"} -->
# Next.js Explained in 10 Minutes(How It Really Works)

<img src="72527c/1b5a3fb8/Next.js%20Explained%20in%2010%20Minutes%28How%20It%20Really%20Works%29.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=-1Kf9ogqcy0](https://www.youtube.com/watch?v=-1Kf9ogqcy0) |
| 发布 | 2026-11-17 |
| 时长 | 11 分 38 秒 |
| 语言 | 英语 |
| 原作者 | [Frontend School](https://www.youtube.com/@FrontendSchoolOfficials)（@FrontendSchoolOfficials，19 订阅） |

## 中文信息

**标题**：【中配】看完这个视频就能讲清 Next.js 到底怎么工作的

**原标题译文**：10分钟带你了解 Next.js（它是如何真正工作的）

很多开发者在实际项目中使用 Next.js 时，往往只是在模仿 API 或者按照文档复制粘贴代码，却并不真正理解框架底层的运作逻辑。这会导致在面对复杂的性能优化问题、组件渲染异常或者架构设计抉择时感到无从下手。本期视频正是为了打破这种黑盒状态，带你深入 Next.js 的核心架构原理，从基础的路由机制到高级的流式渲染，全方位拆解 Next.js 是如何在 React 之上构建高性能应用的。

通过本视频的学习，你可以掌握以下核心知识点：

首先是 Next.js 与 React 的本质区别。你会了解到 Next.js 不仅仅是 React 的一个库，它提供了一整套完整的框架能力，包括基于文件夹结构的路由系统、高性能的 Turbopack 打包工具以及专门的编译器。

其次是 App Router 的路由机制。我们将详细讲解文件夹结构如何直接对应 URL 结构，并明确 page.tsx 作为公开页面、layout.tsx 用于包裹页面并保持状态、以及 loading.tsx、error.tsx、not-found.tsx 和 route.ts 等特殊文件的具体职责。

核心重头戏是服务端组件（Server Components）与客户端组件（Client Components）的区别。你会搞清楚为什么服务端组件仅在服务器运行且不向浏览器传输 JS，支持直接操作数据库但不支持交互；而客户端组件如何通过 use client 标记，在服务器预渲染 HTML 后，在浏览器中通过注水（Hydration）实现交互。

此外，视频还会带你追踪完整的请求流转全流程：从 Middleware 代理到路由器匹配，再到服务器生成 HTML 和 RSC 负载，最后到浏览器显示 HTML 并下载 JS 进行注水的每一个步骤。

在性能优化方面，我们将深入探讨流式渲染（Streaming）。你会学习如何利用 Suspense 将慢速组件的 HTML 异步流式传输到浏览器，从而避免整个页面等待渲染完成。同时，视频还会涵盖静态渲染、动态渲染、增量静态再生成（ISR）以及 use cache 指令等多种缓存策略，帮助你根据页面需求选择最合适的渲染模式。

最后，视频还会涵盖无刷新导航与预取机制，解释点击链接时如何仅获取新路由的 RSC 负载并更新变化部分；以及 Server Actions 如何通过 use server 标记，让你直接从组件调用服务器端逻辑处理数据写入，无需手动编写 API 路由。此外，视频还会涉及 Turbopack 如何按路由拆分 JS 包，以及在 Vercel、Docker 容器或 Node 服务器上的部署逻辑。

本视频非常适合前端工程师、正在准备前端面试的开发者，以及希望深入理解 Next.js 底层原理的 React 开发者。如果你已经具备基础的 React 知识和基本的 Web 开发概念（如 HTTP 请求、HTML 渲染等），那么这个视频将是你的进阶之路上的重要参考。

章节
0:00 介绍
0:32 你将学到什么
1:18 什么是 Next.js (React vs Next.js)
2:15 路由：你的文件夹就是你的路由
3:22 服务端组件 vs 客户端组件
4:26 一个请求的完整步骤
5:48 使用 Suspense 实现流式渲染
6:30 静态、动态与缓存
7:38 无刷新导航
8:22 Server Actions
9:12 构建与部署
9:58 3 个面试题
10:51 总结

原视频：Next.js Explained in 10 Minutes(How It Really Works)
原作者：Frontend School
发布日期：2026-11-17
视频链接：https://www.youtube.com/watch?v=-1Kf9ogqcy0

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| Next.js Explained in 10 Minutes(How It Really Works) - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](72527c/7db2eb5c/Next.js%20Explained%20in%2010%20Minutes%28How%20It%20Really%20Works%29%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/J2RZS/72527c/7db2eb5c/Next.js%20Explained%20in%2010%20Minutes%28How%20It%20Really%20Works%29%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |
| Next.js Explained in 10 Minutes(How It Really Works) - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](72527c/ad5f6118/Next.js%20Explained%20in%2010%20Minutes%28How%20It%20Really%20Works%29%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/J2RZS/72527c/ad5f6118/Next.js%20Explained%20in%2010%20Minutes%28How%20It%20Really%20Works%29%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](72527c/b6d5fb5e/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/J2RZS/72527c/b6d5fb5e/dubbed.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频章节

| 时间 | 章节 |
|---|---|
| 0:00 | Intro |
| 0:32 | What you'll learn |
| 1:18 | What Next.js is (React vs Next.js) |
| 2:15 | Routing: your folders are your routes |
| 3:22 | Server vs Client Components |
| 4:26 | One request, step by step |
| 5:48 | Streaming with Suspense |
| 6:30 | Static, dynamic & caching |
| 7:38 | Navigation without reloads |
| 8:22 | Server Actions |
| 9:12 | Build & deploy |
| 9:58 | 3 interview questions |
| 10:51 | Recap |

## 原视频简介

Next.js explained properly, in one video. 🚀

---

视频内容版权归原作者所有，字幕仅供学习交流。
