---
title: "介绍"
description: "Guides lead a user through a specific task they want to accomplish, often with a sequence of steps."
summary: ""
date: 2023-09-07T16:04:48+02:00
lastmod: 2023-09-07T16:04:48+02:00
draft: false
menu:
  docs:
    parent: ""
    identifier: "example-6a1a6be473e933280d78ea53de6158d"
weight: 101
toc: true
seo:
  title: "" # custom title (optional)
  description: "" # custom description (recommended)
  canonical: "" # custom canonical URL (optional)
  noindex: false # false (default) or true
---

{{< figure src="images/dm-gtm0375hi1t02-0.jpg" alt="" >}}

**Pico_DM_GTM0375HI1T02** 是基于树莓派 Pico 设计的一款低成本显示拓展板，用来学习、评估、开发LVGL或其他GUI应用。 

<mark>**我们使用了PIO模拟8080接口，来达到LCD的极限时序参数。**</mark>

演示视频链接:
[https://www.bilibili.com/video/BV1aD42177CE/](https://www.bilibili.com/video/BV1aD42177CE/)

树莓派 RP2040 是树莓派的首款微控制器。它为微控制器领域带来了高性能，低成本和易于使用的标志性价值。

{{< details "以下内容引用自树莓派官方介绍">}}
With a large on-chip memory, symmetric dual-core processor complex, deterministic bus fabric, and rich peripheral set augmented with our unique Programmable I/O (PIO) subsystem, it provides professional users with unrivalled power and flexibility. 

凭借巨大的片上内存、对称双核处理器、确定性总线结构和丰富的外设，以及我们独特的可编程I/O (PIO)子系统，它为专业用户提供了无与伦比的功能和灵活性。

With detailed documentation, a polished MicroPython port, and a UF2 bootloader in ROM, it has the lowest possible barrier to entry for beginner and hobbyist users.

有了详细的文档，一个精美的MicroPython端口，以及ROM中的UF2引导加载程序，它对初学者和爱好者用户来说具有最低的入门门槛。

{{< /details >}}

{{< figure src="images/rp2040.jpg" alt="" >}}


## 产品参数

| | Pico_DM_GTM0375HI1T02 |
| --- | --- | --- |
| 芯片 | 树莓派 RP2040 | 树莓派 RP2350 |
| 处理器 | 双核 ARM Cortex-M0 + @ 133MHz | 双核 Arm Cortex-M33 或 双核 Hazard3 RISC-V processors @ 150MHz |
| 内存 | 264 KB SRAM | 520 KB on-chip SRAM |
| 闪存 | 最大 16MB |
| 显示屏 | 3.5寸 TFT 480x320 8位8080 ILI9488 |
| 触摸屏 | 3.5寸 RTP NS2009 |

<!-- {{< card-grid >}}
  {{< link-card title="官方购买链接" href="https://item.taobao.com/item.htm?ft=t&id=776451474190&spm=a21dvs.23580594.0.0.52de3d0dccvs2X&skuId=5311045681719" >}}
{{< /card-grid >}} -->

{{< callout context="note" title="说明" icon="info-circle" >}} 默认配置不包括核心板，需自行准备，或选配 {{< /callout >}}
