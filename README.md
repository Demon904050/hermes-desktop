# Hermes Agent Desktop (macOS Apple Silicon)

[![Version](https://img.shields.io/badge/version-0.5.1-blue.svg)](https://github.com/Demon904050/hermes-desktop/releases)
[![Platform](https://img.shields.io/badge/platform-macOS%20Apple%20Silicon-orange.svg)](https://github.com/Demon904050/hermes-desktop/releases)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/NousResearch/hermes-agent/blob/main/LICENSE)

> **一个与你共同成长的 AI 助手** — 安装简单，配置一次，随时通过飞书、Telegram、Discord 等平台与它对话。

## 什么是 Hermes Agent 桌面端？

Hermes Agent 是一个开源的自主 AI 助手，核心特性：

- **持久记忆**：长期运行，持续学习项目背景和你的偏好，不会每次重启都"失忆"
- **多平台接入**：通过飞书、Telegram、Discord、Email 等多个平台与它对话
- **定时自动化**：用自然语言设置定时任务，如"每天早上9点给我发一份昨日工作简报"
- **技能系统**：遇到新任务，AI 会自动编写技能（SKILL）存档，下次复用
- **代码执行**：自带代码解释器/终端，支持 Python、Shell 等

桌面端将 Hermes Agent 包装成 macOS 原生应用，安装后双击即可运行，无需敲命令行。

## 系统要求

- macOS 12.0 及以上
- **Apple Silicon（M1 / M2 / M3 / M4）**
- 支持 Intel Mac 的版本正在规划

> ⚠️ 本安装包为 `arm64` 架构，仅适用于 Apple Silicon Mac。Intel Mac 用户请等待后续版本。

## 下载安装

**最新版本**：https://github.com/Demon904050/hermes-desktop/releases

点击 `hermes-desktop-0.5.1-arm64.dmg` 下载，完成后：

1. 双击 `.dmg` 文件
2. 将 **Hermes Agent** 拖入应用程序文件夹
3. 首次运行可能需要在「系统设置 → 隐私与安全性」中点击"仍要打开"
4. 启动后按照终端提示完成首次配置（填入 API Key、选择接入平台）

## 快速配置

```bash
# 如果终端里直接运行 CLI 版本，可以用：
hermes setup
```

桌面端启动后会引导你完成：
1. 配置 API Key（支持 MiniMax / OpenAI / Anthropic 等）
2. 选择接入的即时通讯平台（飞书 / Telegram / Discord 等）
3. 完成身份验证，开始使用

## 官方资源

| 资源 | 链接 |
|------|------|
| 官网 | https://hermes-agent.nousresearch.com |
| GitHub（核心项目） | https://github.com/NousResearch/hermes-agent |
| 官方文档 | https://hermes-agent.nousresearch.com/docs |
| Discord 社区 | https://discord.gg/NousResearch |

## 版本说明

- **v0.5.1**：首个公开 macOS Apple Silicon 版本，基于官方 Hermes Agent 打包

## License

本桌面客户端基于 [Hermes Agent](https://github.com/NousResearch/hermes-agent)（MIT License）构建。