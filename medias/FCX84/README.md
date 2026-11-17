<!-- dubline-subs {"title": "How Docker Containers Really Work: Namespaces & cgroups Explained", "author": "Bit Byte Talks", "files": 3, "updated": "2026-11-16"} -->
# How Docker Containers Really Work: Namespaces & cgroups Explained

<img src="d8b590/f6ff0d62/How%20Docker%20Containers%20Really%20Work%20Namespaces%20%26%20cgroups%20Explained.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=dFGPOr_gInY](https://www.youtube.com/watch?v=dFGPOr_gInY) |
| 发布 | 2026-11-06 |
| 时长 | 10 分 39 秒 |
| 语言 | 英语 |
| 原作者 | [Bit Byte Talks](https://www.youtube.com/@BitByteTalks)（@BitByteTalks，约 3 万订阅） |

## 中文信息

**标题**：【中配】10分钟带你拆解Docker容器底层：Namespaces与cgroups

**原标题译文**：Docker 容器的真实工作原理：Namespaces 与 cgroups 解析

很多同学在日常使用 Docker 进行开发或部署时，往往只是在命令行里输入几个命令，或者在配置文件里写上一些参数，却很少有人真正深入思考过，这些操作背后的底层原理究竟是怎么实现的。为什么容器能做到进程隔离？为什么一个容器崩溃了不会影响到宿主机或其他容器？为什么我们可以限制某个容器只能使用特定的 CPU 核心或内存？这期视频将带你深入 Linux 内核的底层，用最通俗易懂的方式，在短短 10 分钟内带你彻底拆解 Docker 容器的核心支柱：Namespaces 与 cgroups。

通过这期视频的学习，你将能够掌握容器技术的两大核心支柱。首先是 Namespaces，它决定了进程能“看到”什么，也就是所谓的“隐私视角”。我们将详细拆解六种主要的命名空间：PID 命名空间让容器内的程序认为自己是系统中的唯一进程，也就是 PID 1；挂载命名空间提供了独立的根目录视图，比传统的 Chroot 更强大且安全；网络命名空间为每个容器提供独立的网络接口、IP 地址、路由表和端口；用户命名空间允许容器内拥有 root 权限，但实际上映射到宿主机上的只是普通用户权限；UTS 命名空间允许容器拥有独立的主机名；IPC 命名空间则负责隔离进程间的通信内容，比如共享内存等。

除了“能看到什么”，我们还要讨论“能用多少”。这就是 cgroups（控制组）的作用。如果说 Namespaces 是在给进程划分房间，那么 cgroups 就是在给每个房间分配“预算”。我们将深入探讨 cgroups 如何通过限制 CPU 核心数、内存容量、磁盘写入速度和网络带宽，来防止所谓的“吵闹的邻居”占用过多系统资源。通过这些机制，系统可以确保每个容器都在规定的资源预算内运行，从而保证整体系统的稳定性和公平性。

此外，视频还会带你理清很多常见的技术误区。很多初学者容易把容器和虚拟机混为一谈，实际上容器并不是虚拟机，它本质上就是运行在特定 namespaces 和 cgroups 约束下的普通 Linux 进程。我们还会聊到除了这两个核心机制之外，Linux 还会通过 Capabilities 权限拆分和 Seccomp 系统调用过滤来提供额外的安全防护。通过这些知识点的串联，你将能够理解 Docker 的端口映射、卷挂载以及内存限制等常用操作背后对应的内核技术点。

这期视频非常适合对容器底层原理感兴趣的初学者、后端开发人员以及运维工程师。无论你是想在面试中展现出更深厚的底层技术功底，还是希望在日常工作中更透彻地理解自己所使用的工具，这期视频都能为你提供极大的帮助。只要你具备基础的 Linux 操作系统常识，无需任何复杂的预备知识，就能通过这期视频快速建立起对容器技术的底层认知。

看完这期视频后，你将能够清晰地描述容器是如何通过 Linux 内核机制实现进程隔离与资源限制的。你将不再仅仅是会用 Docker 命令的“使用者”，而是能够从内核视角理解容器本质的“技术人”。通过对 Namespaces 和 cgroups 的深度拆解，你将能够准确分辨容器与虚拟机的本质区别，并能用专业的术语解释容器的安全机制和资源调度原理。无论是在技术交流中还是在实际的架构设计中，这些底层知识都将成为你极具竞争力的核心知识储备。

原视频：How Docker Containers Really Work: Namespaces & cgroups Explained
原作者：Bit Byte Talks
发布日期：2026-11-06
视频链接：https://www.youtube.com/watch?v=dFGPOr_gInY

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](a1f54f/7f551844/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/FCX84/a1f54f/7f551844/dubbed.srt) |
| How Docker Containers Really Work Namespaces & cgroups Explained - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](a1f54f/d60786e5/How%20Docker%20Containers%20Really%20Work%20Namespaces%20%26%20cgroups%20Explained%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/FCX84/a1f54f/d60786e5/How%20Docker%20Containers%20Really%20Work%20Namespaces%20%26%20cgroups%20Explained%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| How Docker Containers Really Work Namespaces & cgroups Explained - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](a1f54f/d7f0610c/How%20Docker%20Containers%20Really%20Work%20Namespaces%20%26%20cgroups%20Explained%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/FCX84/a1f54f/d7f0610c/How%20Docker%20Containers%20Really%20Work%20Namespaces%20%26%20cgroups%20Explained%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

---

视频内容版权归原作者所有，字幕仅供学习交流。
