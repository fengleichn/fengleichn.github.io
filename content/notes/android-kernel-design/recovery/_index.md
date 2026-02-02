---
title: "02. Recovery：为什么它要独立？启动链路与职责边界"
description: "Recovery 的职责边界、启动链路、分区与 OTA 关系"
weight: 20
---

这一章分三块：

- 启动链路：Bootloader → Kernel → init → recovery
- 职责边界：为什么要独立于 Android userspace
- OTA/分区：A/B、签名校验、回滚与一致性

## 目录
- [01. 启动链路总览](./01-bootflow/)
- [02. 分区与镜像组织](./02-partitions/)
- [03. 为什么必须独立](./03-why-separate/)

