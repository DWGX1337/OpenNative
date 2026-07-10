# OpenNative

> 以前写的 Minecraft client 狗屎实验，没什么技术力但很有时代感。
> An old Minecraft client experiment — kept for its period charm.

---

## Overview

OpenNative is an early Minecraft client project, written in Java. It's a personal practice piece from back in the day — not polished, not impressive, but real. The repo preserves it as-is for anyone interested in Minecraft client internals, reverse-engineering patterns, or just seeing how things were done in that era.

## 概述

OpenNative 是一个早期的 Minecraft 客户端项目，Java 写的。当年的练手作品，没什么技术力，但留着当成长记录。对 Minecraft 客户端逆向、调试分析感兴趣的可以翻翻看，感受一下那个时代的做法。

---

## Features / 功能

- Minecraft client 实现（早期练习版本）
- Java 编写，客户端级代码
- 保留了完整的历史快照，适合对比研究

---

## Tech Stack / 技术栈

| Item | Detail |
|------|--------|
| Language | Java |
| Domain | Minecraft client |
| Topics | `java`, `minecraft`, `minecraft-client`, `legacy-project` |

构建系统和依赖信息在 `OpenNative.rar` 内部。

<!-- TODO: confirm 具体构建系统（Gradle / Maven / 手动）与依赖版本 —— 解压 OpenNative.rar 后确认。 -->

---

## Project Structure / 项目结构

```
OpenNative/
├── OpenNative.rar     # 核心归档：Minecraft client 项目源码（~3.8 MB）
└── README.md
```

<!-- TODO: confirm .rar 内部结构 —— 压缩包未解压，内部源码结构未公开。 -->

---

## Getting Started / 快速开始

核心内容打包在 `OpenNative.rar` 中。解压后查看：

```sh
# Linux/macOS
unrar x OpenNative.rar
# 或
7z x OpenNative.rar
```

解压后根据内部工程文件确定构建方式。

<!-- TODO: confirm 是否存在可用的构建/运行命令 —— 需解压后依据内部工程文件确定。 -->

---

## Status / 状态

归档状态。这是一个历史项目快照，不再活跃开发。

Archived. This is a historical snapshot, no longer under active development.

---

## License / 许可证

未指定许可协议。仓库中不包含 LICENSE 文件，默认保留所有权利。

No license specified. All rights reserved by default.
