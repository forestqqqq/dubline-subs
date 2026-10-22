<!-- dubline-subs {"title": "Continuing to build a web app with TanStack Start, Drizzle, Better Auth & Tailwind", "author": "Maximilian Schwarzmüller Extended", "files": 3, "updated": "2026-10-21"} -->
# Continuing to build a web app with TanStack Start, Drizzle, Better Auth & Tailwind

<img src="34a79e/0b7a67fe/Continuing%20to%20build%20a%20web%20app%20with%20TanStack%20Start%2C%20Drizzle%2C%20Better%20Auth%20%26%20Tailwind.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=f13cO4CxlUQ](https://www.youtube.com/watch?v=f13cO4CxlUQ) |
| 发布 | 2025-04-10 |
| 时长 | 1 小时 57 分 24 秒 |
| 语言 | 英语 |
| 原作者 | [Maximilian Schwarzmüller Extended](https://www.youtube.com/@maximilian-extended)（@maximilian-extended，4420 订阅） |

## 中文信息

**标题**：实战 2 小时，用 TanStack Start + Drizzle 构建全栈投票应用

**原标题译文**：继续使用 TanStack Start, Drizzle, Better Auth 和 Tailwind 构建 Web 应用

在这期实战教学视频中，我们将带你深入参与一个从零开始构建的全栈 Web 应用开发过程。我们选择了一个具有实际业务逻辑的“投票系统”作为实战案例，该应用支持用户注册登录、提议新话题以及对不同话题进行投票。通过这个具体的项目，我们将深度剖析如何将 TanStack Start 框架、Drizzle ORM 数据库持久层以及 Better Auth 身份验证系统这三者完美融合，构建出一个功能完备且架构合理的全栈应用。

在长达两小时的实战过程中，你将获得非常具体的知识点提升：
首先是关于认证逻辑的高效重构。我们将探讨如何摒弃过去繁琐的、在服务端手动处理 Cookie 的复杂逻辑，转而采用 Better Auth 提供的客户端库（auth client）。这种做法能极大地简化登录和注册流程，让系统自动管理 Cookie，从而让开发者更专注于业务逻辑而非底层认证细节。
其次是全栈表单交互的实战技巧。我们将演示如何利用 TanStack Start 的 server 函数配合前端的 useServerfn 钩子，在前后端之间建立平滑的连接。通过这种方式，你可以轻松实现从前端表单提交到后端处理，再到页面自动重定向的完整闭环，显著提升用户体验。
在数据持久层方面，我们将深入讲解 Drizzle ORM 的实战用法。你将学习如何定义 SQLite 数据库模型（如话题表和投票表），并利用迁移工具同步本地数据库结构。更重要的是，我们将重点攻克复杂的“一对多”关联查询问题。通过正确配置 Relations 以及使用 with 子句，我们可以有效解决由于配置不当导致的 Drizzle 死循环问题，确保数据查询的高效与准确。
此外，你还将学习到如何在服务端函数中利用 getHeaders 获取当前会话信息，并针对未登录用户进行强制的权限拦截。同时，为了保证 TypeScript 类型的严谨性，我们将演示如何利用 Drizzle 的 extras 功能来处理 SQL 别名（例如在查询时统计投票总数），确保前端接收到的数据类型始终一致。
最后，我们还会专门讨论在现代开发流程中如何正确使用 AI 工具。我们会明确 AI 在解决陌生技术问题、快速查阅复杂文档等场景中的辅助地位，同时强调开发者在处理核心业务逻辑和架构决策时不可替代的作用。

本期视频非常适合以下几类朋友观看：如果你正在使用 TanStack Start 或 Drizzle ORM 构建全栈应用，这期视频将为你提供实战层面的避坑指南；如果你在项目中遇到身份验证集成困难，或者在处理数据库关联查询、TypeScript 类型对齐等技术难题时感到困扰，本视频提供的解决方案将非常有帮助。此外，如果你也关注如何利用 GitHub Copilot 或 Cursor 等 AI 工具来辅助提升软件工程的开发效率，这期内容也将为你提供有价值的思考维度。

看完这期视频后，你将能够熟练掌握 TanStack Start 与 Drizzle 的整合模式，能够独立构建具备完整认证逻辑和复杂数据库关联查询功能的全栈功能模块。你将学会如何建立稳健的数据模型并处理复杂的 SQL 别名，能够在实际项目中快速部署出高性能的 Web 应用，并且能够更理智、高效地利用 AI 工具来辅助你的日常开发工作。

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| Continuing to build a web app with TanStack Start, Drizzle, Better Auth & Tailwind - 英语字幕（转写）.en.srt | 原文字幕（转写） | [查看 / 下载](34a79e/0cab60d5/Continuing%20to%20build%20a%20web%20app%20with%20TanStack%20Start%2C%20Drizzle%2C%20Better%20Auth%20%26%20Tailwind%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/9MJBQ/34a79e/0cab60d5/Continuing%20to%20build%20a%20web%20app%20with%20TanStack%20Start%2C%20Drizzle%2C%20Better%20Auth%20%26%20Tailwind%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |
| Continuing to build a web app with TanStack Start, Drizzle, Better Auth & Tailwind - 中英双语字幕.srt | 双语字幕 | [查看 / 下载](34a79e/6ed8d640/Continuing%20to%20build%20a%20web%20app%20with%20TanStack%20Start%2C%20Drizzle%2C%20Better%20Auth%20%26%20Tailwind%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/9MJBQ/34a79e/6ed8d640/Continuing%20to%20build%20a%20web%20app%20with%20TanStack%20Start%2C%20Drizzle%2C%20Better%20Auth%20%26%20Tailwind%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| Continuing to build a web app with TanStack Start, Drizzle, Better Auth & Tailwind - 简体中文字幕（翻译）.zh.srt | 译文字幕 | [查看 / 下载](34a79e/8f81d7f3/Continuing%20to%20build%20a%20web%20app%20with%20TanStack%20Start%2C%20Drizzle%2C%20Better%20Auth%20%26%20Tailwind%20-%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%E5%AD%97%E5%B9%95%EF%BC%88%E7%BF%BB%E8%AF%91%EF%BC%89.zh.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/9MJBQ/34a79e/8f81d7f3/Continuing%20to%20build%20a%20web%20app%20with%20TanStack%20Start%2C%20Drizzle%2C%20Better%20Auth%20%26%20Tailwind%20-%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%E5%AD%97%E5%B9%95%EF%BC%88%E7%BF%BB%E8%AF%91%EF%BC%89.zh.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，时间轴与原视频一致，可直接拖进播放器（PotPlayer、VLC、IINA 等）加载。

## 原视频简介

Let's continue exploring TanStack Start, Drizzle and Better Auth by building a web app - one step at a time.

---

视频内容版权归原作者所有，字幕仅供学习交流。
