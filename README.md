# Hermes Agent Desktop

[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://github.com/Demon904050/hermes-desktop/releases)
[![Platform](https://img.shields.io/badge/platform-macOS%20%7C%20Windows-orange.svg)](https://github.com/Demon904050/hermes-desktop/releases)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/NousResearch/hermes-agent/blob/main/LICENSE)

> **一个与你共同成长的 AI 助手** — 安装简单，配置一次，随时通过飞书、Telegram、Discord 等平台与它对话。

## 什么是 Hermes Agent 桌面端？

Hermes Agent 是一个开源的自主 AI 助手，核心特性：

- **持久记忆**：长期运行，持续学习项目背景和你的偏好，不会每次重启都"失忆"
- **多平台接入**：通过飞书、Telegram、Discord、Email 等多个平台与它对话
- **定时自动化**：用自然语言设置定时任务，如"每天早上9点给我发一份昨日工作简报"
- **技能系统**：遇到新任务，AI 会自动编写技能（SKILL）存档，下次复用
- **代码执行**：自带代码解释器/终端，支持 Python、Shell 等

## 下载版本

| 平台 | 系统要求 | 下载地址 |
|------|----------|----------|
| 🪟 Windows | Windows 10/11 | [Hermes Agent-1.0.0-Setup.exe](https://github.com/Demon904050/hermes-desktop/releases/tag/v1.0.0) |
| 🍎 macOS (Apple Silicon) | macOS 12.0+，M1/M2/M3/M4 | [hermes-desktop-0.5.1-arm64.dmg](https://github.com/Demon904050/hermes-desktop/releases/tag/v0.5.1) |

## 安装步骤

### 🪟 Windows 版
1. 下载 `Hermes Agent-1.0.0-Setup.exe`
2. 双击运行，一路点击"下一步"即可
3. 首次运行在「系统设置 → 隐私与安全性」中允许运行
4. 启动后按终端提示完成 API Key 配置

### 🍎 macOS 版
1. 下载 `hermes-desktop-0.5.1-arm64.dmg`
2. 双击挂载，将 **Hermes Agent** 拖入应用程序文件夹
3. 首次运行在「系统设置 → 隐私与安全性」中点击"仍要打开"
4. 启动后按终端提示完成配置

## 快速配置

```bash
hermes setup
```

配置内容包括：
1. 填入 API Key（支持 MiniMax / OpenAI / Anthropic 等）
2. 选择接入平台（飞书 / Telegram / Discord 等）
3. 完成身份验证，开始使用

## 官方资源

| 资源 | 链接 |
|------|------|
| 官网 | https://hermes-agent.nousresearch.com |
| 核心项目（GitHub） | https://github.com/NousResearch/hermes-agent |
| 官方文档 | https://hermes-agent.nousresearch.com/docs |
| Discord 社区 | https://discord.gg/NousResearch |

## 版本历史

- **v1.0.0**（2026-05）：首个 Windows 正式版
- **v0.5.1**（2026-05）：首个 macOS Apple Silicon 版

## License

桌面客户端基于 [Hermes Agent](https://github.com/NousResearch/hermes-agent)（MIT License）构建。