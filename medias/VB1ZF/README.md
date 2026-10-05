<!-- dubline-subs {"title": "Intro to Shaders – JavaScript & p5.js Course for Beginners", "author": "freeCodeCamp.org", "files": 3, "updated": "2026-10-05"} -->
# Intro to Shaders – JavaScript & p5.js Course for Beginners

<img src="a34ad8/754382ff/Intro%20to%20Shaders%20%E2%80%93%20JavaScript%20%26%20p5.js%20Course%20for%20Beginners.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=YdhXnB5E-4s](https://www.youtube.com/watch?v=YdhXnB5E-4s) |
| 发布 | 2026-07-15 |
| 时长 | 1 小时 14 分 41 秒 |
| 语言 | 英语 |
| 原作者 | [freeCodeCamp.org](https://www.youtube.com/@freecodecamp)（@freecodecamp，约 1190 万订阅） |

## 中文信息

**标题**：1小时内从零上手 Shader，用 p5.js 做出动态分形心形

**原标题译文**：Shader 入门 - 适合初学者的 JavaScript 与 p5.js 课程

如果你一直对那些在网页上流动的炫酷视觉特效感到好奇，或者想知道如何在 Web 端利用 GPU 的强大算力去创作复杂的动态图形，那么这期视频就是为你量身定制的入门指南。本课程将带你跨越从零到一的门槛，在短短的一小时内，通过 p5.js 与 GLSL 编程的实战结合，带你深入底层原理，最终亲手构建出一个极具视觉冲击力的动态分形心形特效。

这不仅仅是一个简单的特效教程，而是一次系统的图形编程入门之旅。为了让你能够真正理解 Shader 的逻辑，视频内容从最基础的硬件逻辑开始铺陈。首先，我们将深入探讨 GPU 与 CPU 处理逻辑的核心差异：你会了解到 GPU 是如何作为并行处理大量像素的蓝图，在处理大规模网格数据时展现出远超 CPU 的优势。随后，课程将明确顶点着色器与片元着色器的职能分工，让你明白几何定位与最终颜色计算是如何协同工作的。

在进入实战环节前，你将掌握至关重要的坐标系转换知识。我们将学习如何将 p5.js 提供的 0 到 1 的归一化坐标转换为 WebGL 所需的 -1 到 1 的裁剪空间（Clip Space），并学会利用 u_resolution 变量来处理分辨率比例问题，确保你的作品在不同尺寸的画布上都不会出现拉伸变形。

随后，我们将进入核心数学概念的实战应用。你将学习如何利用 fract 函数配合坐标偏移，在不使用循环的情况下创造出复杂的平铺网格效果；掌握 step、smoothstep 以及 abs 和 sin 等基础数学函数作为塑形函数，去构建心形等各种几何轮廓；通过反距离方程逻辑来模拟真实光线的发光感；并学会利用 mix 函数配合塑形函数的输出值来精准控制颜色的亮度与过渡。此外，我们还会探讨如何利用基于余弦的方程生成丰富的动态色调，从而替代简单的线性混合，让色彩更具层次感。最后，由于 GPU 不支持递归，我们将学习通过 for 循环对 UV 坐标进行重映射，从而实现多层分形叠加的高级视觉效果。

这门课程非常适合以下几类人群：首先是想要探索 WebGL 和 Shader 开发领域的创意开发者，如果你希望在网页端实现高性能的交互式艺术，这是极佳的切入点；其次是对于图形编程充满兴趣但没有任何相关经验的初学者，本视频提供的从底层原理出发的教学路径能帮你建立正确的知识体系；最后，也是最重要的一类人，就是那些渴望掌握用数学公式驱动视觉效果、追求通过算法生成动态动画和复杂形状的开发者。

看完这期课程后，你将不再只是一个只会调用现成库的初学者，而是能够理解底层渲染逻辑的创作者。你将具备在 p5.js 环境下编写 GLSL 代码的能力，掌握从坐标映射到复杂数学公式转换的核心技术，并能够独立运用这些工具去构建出具有发光效果、动态渐变以及分形结构的视觉作品。通过本视频的学习，你将拥有从零开始构建高度自定义图形特效的技术底座，让你的创意不再受限于简单的素材堆砌，而是可以通过代码逻辑精准地表达出来。

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| Intro to Shaders – JavaScript & p5.js Course for Beginners - 中英双语字幕.srt | 双语字幕 | [查看 / 下载](a34ad8/5a9e7938/Intro%20to%20Shaders%20%E2%80%93%20JavaScript%20%26%20p5.js%20Course%20for%20Beginners%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/VB1ZF/a34ad8/5a9e7938/Intro%20to%20Shaders%20%E2%80%93%20JavaScript%20%26%20p5.js%20Course%20for%20Beginners%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| Intro to Shaders – JavaScript & p5.js Course for Beginners - 英语字幕（转写）.en.srt | 原文字幕（转写） | [查看 / 下载](a34ad8/727dd4c3/Intro%20to%20Shaders%20%E2%80%93%20JavaScript%20%26%20p5.js%20Course%20for%20Beginners%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/VB1ZF/a34ad8/727dd4c3/Intro%20to%20Shaders%20%E2%80%93%20JavaScript%20%26%20p5.js%20Course%20for%20Beginners%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |
| Intro to Shaders – JavaScript & p5.js Course for Beginners - 简体中文字幕（翻译）.zh.srt | 译文字幕 | [查看 / 下载](a34ad8/c7ff3e83/Intro%20to%20Shaders%20%E2%80%93%20JavaScript%20%26%20p5.js%20Course%20for%20Beginners%20-%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%E5%AD%97%E5%B9%95%EF%BC%88%E7%BF%BB%E8%AF%91%EF%BC%89.zh.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/VB1ZF/a34ad8/c7ff3e83/Intro%20to%20Shaders%20%E2%80%93%20JavaScript%20%26%20p5.js%20Course%20for%20Beginners%20-%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%E5%AD%97%E5%B9%95%EF%BC%88%E7%BF%BB%E8%AF%91%EF%BC%89.zh.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，时间轴与原视频一致，可直接拖进播放器（PotPlayer、VLC、IINA 等）加载。

## 原视频章节

| 时间 | 章节 |
|---|---|
| 0:00:00 | Intro |
| 0:00:51 | Part 1 - Basic Introduction to Shaders |
| 0:01:17 | What is a shader? |
| 0:03:24 | Bridge between CPU and GPU |
| 0:04:20 | Vertex and fragment shaders |
| 0:06:09 | Start coding in p5.js |
| 0:09:44 | GLSL Rulebook |
| 0:12:50 | Set up canvas space in a vertex shader |
| 0:16:16 | Color pixels in a fragment shader |
| 0:17:44 | Map clip space to screen coordinates |
| 0:20:03 | Create a static gradient |
| 0:22:04 | Create a dynamic gradient |
| 0:27:03 | Part 2 - Domain Repetition |
| 0:28:33 | Draw a circle |
| 0:32:05 | Use gl_FragCoord to get pixel coordinates |
| 0:38:45 | Create tiling with fract() |
| 0:42:00 | Fix aspect ratio |
| 0:43:56 | Introduce the standard resolution fix |
| 0:45:01 | Part 3 - Shaping Functions |
| 0:45:38 | What is a shaping function? |
| 0:46:20 | Explore sin() function |
| 0:47:41 | Explore step() function |
| 0:48:25 | Explore smoothstep() function |
| 0:49:40 | Explore abs() function |
| 0:51:33 | Create a glowing effect with inverse distance equation |
| 0:55:02 | Animate glowing rings |
| 0:54:21 | Experiment with other shapes |
| 0:57:43 | Part 4: Colors |
| 0:57:43 | Introduce mix() function |
| 1:01:01 | Change the blend ratio using uTime |
| 1:02:12 | Change the blend ratio using position |
| 1:04:18 | Change the blend ratio using shaping functions (step & smoothstep) |
| 1:05:22 | Change the blend ratio using shaping functions (distance functions) |
| 1:08:22 | Introduce cosine-based color palette |
| 1:10:54 | Bonus! Fractals! |

## 原视频简介

Learn the fundamentals of shaders, with zero prior experience required. Starting from the basics of how the GPU renders pixels, you'll progress to building an animated, fractal heart effect written entirely from scratch. Designed specifically for creative developers who want to break into WebGL and master the math of motion.

---

视频内容版权归原作者所有，字幕仅供学习交流。
