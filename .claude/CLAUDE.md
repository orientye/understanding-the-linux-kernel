# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 代码参考来源

- **优先使用本地代码：** 本仓库笔记以 `..\linux` 下的内核源码为参考基准。如果该目录存在且包含对应源码，以此为准。
- **远程回退：** 当本地源码目录不包含相关代码或不存在时，参考以下在线资源：
  - https://elixir.bootlin.com/linux/latest
  - https://github.com/torvalds/linux/

## 写作规范

- 文档使用 AsciiDoc 格式（`.asc` 文件）
- 中文为主，术语可保留英文原文
- 引用内核源码时标注函数名和文件路径
