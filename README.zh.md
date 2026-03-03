# Awesome OpenClaw 🦞

[English](./README.md) | [简体中文](./README.zh.md)

> OpenClaw（原名 Clawdbot/Moltbot）生态系统下的精选技能、工具与资源列表。

---

## 📖 为什么建立这个列表？

OpenClaw 是一个强大的本地运行 AI 助手编排层。随着生态的扩展，发现高质量、安全且实用的扩展变得至关重要。本列表旨在为所有开发者和用户提供一个中立的、社区驱动的资源索引。

## 🛡️ 安全声明

本列表中的项目经过筛选但**未经审计**。请自行承担使用风险。在安装任何技能或插件之前，请务必审查其源代码。

---

### 📥 安装 (Installation)

```bash
npm install openclaw
```

### 🛡️ 安全提示 (Security Notice)
您可以使用请 **切勿** 分享您的 `OPENAI_API_KEY` 或任何其他敏感凭证。

```bash
# 最佳实践：使用环境变量
export OPENAI_API_KEY='your-key-here'
```

---

## 🤖 模型服务商 (LLM Providers)

- **[OpenAI Integration](https://getclawai.com/docs/integrations/openai)** - OpenAI 模型标准适配器（支持 GPT-4o 等）。
- **[Claude Integration](https://getclawai.com/docs/integrations/claude)** - Anthropic Claude 深度集成。
- **[Gemini Integration](https://getclawai.com/docs/integrations/gemini)** - Google Gemini 多模态模型支持。
- **[Ollama Integration](https://getclawai.com/docs/integrations/ollama)** - 通过 Ollama 支持本地开源模型。

## 💬 消息通道 (Messaging Channels)

- **[WhatsApp Channel](https://getclawai.com/docs/platforms/whatsapp)** - 将您的 AI 连接到 WhatsApp 全球网络。
- **[Telegram Channel](https://getclawai.com/docs/platforms/telegram)** - 为 Telegram 机器人提供深度集成。
- **[OpenClaw-Wechat](https://github.com/freestylefly/openclaw-wechat)** - 微信通道插件，支持私聊、群聊及二维码登录。

## 🛠️ 开发者工具 (Developer Utilities)

- **[Claw CLI](https://www.npmjs.com/package/openclaw)** - 核心命令行编排工具。
- **[Clawdbot](https://getclawai.com/docs/tools/clawdbot)** - OpenClaw 生态主推的 AI 助手。
- **[Moltbot](https://getclawai.com/docs/tools/moltbot)** - 多平台消息通知与监控机器人。
- **[Moltworker (Cloudflare)](https://github.com/cloudflare/moltworker)** - Cloudflare 官方提供的中间件，支持在边缘侧运行 OpenClaw 智能体。
- **[memU (NevaMind-AI)](https://github.com/NevaMind-AI/memU)** - 为 OpenClaw 打造的高级智能体记忆框架及插件，实现 24/7 持久化长期记忆。

## 🎨 案例展示 (Showcases & UI)

- **[Star-Office-UI](https://github.com/ringhyacinth/Star-Office-UI)** - 基于 OpenClaw 开发的精美桌面办公 UI。
- **[OpenClaw Studio](https://github.com/grp06/openclaw-studio)** - 用于管理 OpenClaw 网关、智能体及工作流的 Web 仪表盘。

## 🧩 社区技能 (Community Skills)

- **[XiaohongshuSkills](https://github.com/white0dew/XiaohongshuSkills)** - 支持小红书自动发布、自动评论、自动检索的强大技能。支持 OpenClaw。

## 💡 应用案例 (Use Cases)

- **[YouTube Content Pipeline](https://github.com/hesamsheikh/awesome-openclaw-usecases/blob/main/usecases/youtube-content-pipeline.md)** - 为 YouTube 创作者提供的全面自动化流水线，利用 OpenClaw 进行视频创意获取、提案追踪和内容管理。
- **[Polymarket Autopilot](https://github.com/hesamsheikh/awesome-openclaw-usecases/blob/main/usecases/polymarket-autopilot.md)** - 针对 Polymarket 预测市场的自动化模拟交易系统，利用 OpenClaw 执行多种交易策略。
- **[Personal CRM](https://github.com/hesamsheikh/awesome-openclaw-usecases/blob/main/usecases/personal-crm.md)** - 具有自动联系人发现功能的个人 CRM，可扫描 Gmail/日历并在 Telegram 上提供每日简报。
- **[Multi-Agent Content Factory](https://github.com/hesamsheikh/awesome-openclaw-usecases/blob/main/usecases/content-factory.md)** - 在 Discord 上运行的精密多代理系统，用于自动化内容制作，涵盖调研与脚本编写。

---

## 🤝 贡献指南

请阅读 [CONTRIBUTING.zh.md](./CONTRIBUTING.zh.md) 了解如何提交资源。

## 📄 协议

本仓库数据以 [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) (无保留权利) 协议发布。
