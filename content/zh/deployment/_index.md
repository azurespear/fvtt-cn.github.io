---
title: "部署/安装"
linkTitle: "💻 部署/安装"
weight: 11
type: docs
menu:
  main:
    weight: 11
---

{{% pageinfo %}}
部署、安装快速入门教程
{{% /pageinfo %}}

[官方教程（英文）](https://foundryvtt.com/article/tutorial/)

[官方更新日志（英文）](https://foundryvtt.com/releases/)

部署完毕后，参见[使用教程](../tutorial)，了解如何设置并使用 Foundry VTT

## 部署方式很多，该如何选择?
> 世界上并不存在完美的解决方案，只存在适合自己的。

FoundryVTT 一般存在两种部署方式，一是 [P2P](#p2p)，一是[服务器](#服务器)。
P2P 方式非常直觉地在 GM 自己的电脑上部署，而服务器方式则需要一台能够公网连接的服务器。

### P2P
首先值得一提的是，在国内网络环境下，P2P 绝不会是一个对大多数人都完美的解决方案，但它确实方便、便宜：*使用自己的电脑安装、启动 FVTT，并不需要任何服务器成本*

它的问题是，当玩家们位于各种不同网络环境下（比如 GM 是联通，而 PL 是移动，则互相之间的连接稳定性就会差一些。*更恐怖的是一些杂鱼宽带*）

并且，P2P 方式需要所有玩家之间的 NAT 方式足够开放，才能够互相连接上。如果你常玩 P2P 连接的主机游戏，或许你已经知道：这是一个很多人踩过的坑了。

如果对网络连通性有一定的自信，并且拥有足够的上传带宽（> 10Mbps），P2P 是不错的方案。*其实只要拥有足够的上传带宽，也可以尝试花钱购买一些内网中转服务：这些中转服务用自己的服务器转发 FVTT 的流量，即使 NAT 方式非常严格，玩家们就可以访问*

### 服务器
服务器相对 P2P，有两个独特的问题是：
- 有一定门槛，毕竟不是每一个玩家都接触过 Windows/Linux 服务器的连接与操作
- 有一定成本，往往按月计费。虽然能跑的动 FVTT 的配置的服务器价格不高，但也是一笔固定开支

如果从来没使用过 Linux，并且对输入命令完全不感兴趣，推荐使用 Windows 服务器部署。这和日常使用电脑的差别不会太大，*但缺点是 Windows 服务器往往会因为安装了 Windows 而价格更贵，且性能**通常**比同配置的 Linux 服务器要稍微差一些*。

如果你不介意通过输入命令（别担心，目前社区拥有若干部署脚本，足以让输入的命令简化到 2-3 行）来部署 FVTT，那么使用 Linux 足以满足你的需求，*不过管理文件并不会比 Windows 服务器方便*。

## 前置要求

（✅：必需 | ⭕：可选）

| 需求 | P2P | 服务器 | 备注 |
| ---- | ---- | ---- | ---- |
| 购买 FoundryVTT | ✅ | ✅ | 50 美元（现价） |
| 优质的本地网络质量 | ✅ | ⭕ | 对所有玩家 |
| 购买、续费服务器 | ⭕ | ✅ | 计费方式多样 |
| 购买、绑定域名 | ⭕ | ⭕ | 域名访问方便 |
| 掌握基础服务器操作 | ⭕ | ✅ | Win、Linux 基础的操作 |
