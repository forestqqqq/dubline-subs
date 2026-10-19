<!-- dubline-subs {"title": "I moved off of Next.js", "author": "Theo - t3․gg", "files": 3, "updated": "2026-10-19"} -->
# I moved off of Next.js

<img src="cab798/e4aae349/I%20moved%20off%20of%20Next.js.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=Sc5ca-VJdxY](https://www.youtube.com/watch?v=Sc5ca-VJdxY) |
| 发布 | 2026-01-07 |
| 时长 | 52 分 29 秒 |
| 语言 | 英语 |
| 原作者 | [Theo - t3․gg](https://www.youtube.com/@t3dotgg)（@t3dotgg，约 57 万订阅） |

## 中文信息

**标题**：重写1.4万行代码：为什么 T3 Chat 最终抛弃了 Next.js

**原标题译文**：我不再使用 Next.js 了

这期视频带你深度复盘 T3 Chat 项目从 Next.js 迁移到 TanStack Start 的全过程。这不仅仅是一次简单的框架更换，更是一场关于产品需求与技术选型之间权衡的深刻实践。通过对近 14,000 行新增代码和 10,000 行删除代码的深度剖析，我们将深入探讨在追求极致客户端优先体验、处理复杂后端逻辑（如 AI 流式计算）以及应对特定基础设施限制时，不同技术栈所带来的架构差异与工程挑战。

在视频中，你将了解到以下核心知识点：

首先是关于核心矛盾的深度剖析。Next.js 虽然功能强大，但其设计哲学更偏向服务端渲染（SSR）。然而，为了实现极致流畅、瞬间跳转的单页应用（SPA）体验，团队在 Next.js 中被迫引入了 React Router 并编写大量复杂的重写规则作为补丁。这些非标准的操作不仅增加了维护成本，也成为了技术债。视频将详细讲解为什么最终决定抛弃这些补丁，转而选择更符合客户端优先逻辑的架构。

其次是关于路由机制与类型安全的实战对比。我们将深入探讨 TanStack Start 如何通过结合文件系统路由与 TypeScript 推断（生成 .gen.ts 文件），在提供极强类型安全的同时实现自动化的路径更新。相比于在 Next.js 中手动维护复杂的路由逻辑，这种自动化带来的工程便利性是核心考量点之一。

再者是针对特定场景的架构优化方案。视频涵盖了如何在 Cloudflare 环境下应对严格的打包体积限制（如 3MB/10800KB 的限制），以及如何通过微调路由的最大持续时间设置，将耗时较长的 AI 聊天请求与短小的 TRPC 调用在物理上隔离。特别是针对特定 AI 生成任务设置 799 秒超时的实操经验，对于正在构建 AI 应用的开发者来说具有极高的参考价值。

最后，我们将总结出一套深刻的技术选型哲学：没有完美的工具，只有最适合被魔改以满足特定工程需求的方案。通过分析 T3 Chat 在数据层（TRPC, Redis, Convex, Effect）、基础设施（Cloudflare, Vercel）以及开发工具（Graphite 处理超大型 PR）上的全方位抉择，你会学到如何在复杂的业务逻辑与技术限制之间找到最佳平衡点。

本期视频特别推荐给以下人群：

如果你正在使用 Next.js 并在处理复杂的客户端路由逻辑时感到困扰，或者在为如何实现流畅的 SPA 体验而苦恼，这期内容将为你提供全新的视角。
如果你对 TanStack 生态（包括 TanStack Start 和 TanStack Router）感兴趣，想要了解它们在实际大规模项目中的表现，本视频提供了非常硬核的实战案例。
如果你是一名关注 AI 应用开发、尤其是涉及流式传输（Streaming）和后端架构优化的工程师，视频中关于 Nitro 处理 API 路由以及隔离长耗时任务的细节将非常有帮助。
如果你是团队负责人，正在面临大规模代码重构或技术栈迁移的决策压力，通过 T3 Chat 的实战案例，你可以更清晰地看到技术选型背后的逻辑链条：即产品需求与团队愿景应当始终高于框架本身的偏好。

通过观看本期视频，你将能够从复杂的工程实践中抽离出核心的方法论。你不仅能掌握 TanStack Start 在类型安全和路由处理上的优势，还能学到如何在受限的云端基础设施（如 Cloudflare Worker）上优化资源利用率。最重要的是，你将学会如何评估工具的边界，在面对复杂需求时，能够做出基于工程实效而非仅仅基于技术热度的决策。

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| I moved off of Next.js - 简体中文字幕（翻译）.zh.srt | 译文字幕 | [查看 / 下载](cab798/6273a803/I%20moved%20off%20of%20Next.js%20-%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%E5%AD%97%E5%B9%95%EF%BC%88%E7%BF%BB%E8%AF%91%EF%BC%89.zh.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/1ZV7G/cab798/6273a803/I%20moved%20off%20of%20Next.js%20-%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%E5%AD%97%E5%B9%95%EF%BC%88%E7%BF%BB%E8%AF%91%EF%BC%89.zh.srt) |
| I moved off of Next.js - 中英双语字幕.srt | 双语字幕 | [查看 / 下载](cab798/d6b1b2e1/I%20moved%20off%20of%20Next.js%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/1ZV7G/cab798/d6b1b2e1/I%20moved%20off%20of%20Next.js%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| I moved off of Next.js - 英语字幕（转写）.en.srt | 原文字幕（转写） | [查看 / 下载](cab798/e2483517/I%20moved%20off%20of%20Next.js%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/1ZV7G/cab798/e2483517/I%20moved%20off%20of%20Next.js%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，时间轴与原视频一致，可直接拖进播放器（PotPlayer、VLC、IINA 等）加载。

## 原视频简介

I've officially moved T3 Chat off of NextJS and onto TanStack Start.

---

视频内容版权归原作者所有，字幕仅供学习交流。
