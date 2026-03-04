# Awesome OpenClaw 🦞

[English](./README.md) | [简体中文](./README.zh.md)

> A curated list of awesome OpenClaw skills, tools, and resources.  

---

## 📖 Why This List Exists?

OpenClaw (previously known as Moltbot/Clawdbot) is a powerful locally-running AI assistant orchestration layer. As the ecosystem grows, discovering high-quality, safe, and useful extensions becomes critical. This list aims to provide a neutral, community-driven index for all developers and users.

## 🚀 Installation

### 📥 Core Setup

```bash
npm install openclaw
```

### 🛡️ Security Notice

Items in this list are curated but **not audited**. Use them at your own risk. Always review the source code of any skill or plugin before installation.

Please **NEVER** share your `OPENAI_API_KEY` or any other sensitive credentials.

```bash
# Good practice: use environment variables
export OPENAI_API_KEY='your-key-here'
```

---

## 🤖 LLMs & Providers

- **[OpenAI Integration](https://getclawai.com/docs/integrations/openai)** - Standard adapter for GPT-4o and other OpenAI models.
- **[Claude Integration](https://getclawai.com/docs/integrations/claude)** - Deep integration for Anthropic's Claude 3.5 Sonnet.
- **[Gemini Integration](https://getclawai.com/docs/integrations/gemini)** - Support for Google's powerful multimodal models.
- **[Ollama Integration](https://getclawai.com/docs/integrations/ollama)** - Run open-source models locally via Ollama.

## 💬 Messaging Channels

- **[WhatsApp Channel](https://getclawai.com/docs/platforms/whatsapp)** - Connect your AI to WhatsApp Global network.
- **[Telegram Channel](https://getclawai.com/docs/platforms/telegram)** - Deep integration for Telegram bots.
- **[OpenClaw-Wechat](https://github.com/freestylefly/openclaw-wechat)** - A WeChat channel plugin, supporting direct messages, group chats, and QR code login.
- **[DingTalk Connector](https://github.com/DingTalk-Real-AI/dingtalk-openclaw-connector)** - Official DingTalk connector, supporting AI Card streaming and seamless enterprise integration.

## ⚙️ Orchestration & Frameworks

- **[Antfarm (Snarktank)](https://github.com/snarktank/antfarm)** - A multi-agent orchestration framework for OpenClaw, enabling YAML-defined workflows for dev teams and auditing.

## 🛠️ Developer Utilities

- **[Claw CLI](https://www.npmjs.com/package/openclaw)** - The core command line orchestration tool.
- **[Clawdbot](https://getclawai.com/docs/tools/clawdbot)** - The primary AI assistant agent in the ecosystem.
- **[Moltworker (Cloudflare)](https://github.com/cloudflare/moltworker)** - Official middleware to run OpenClaw agents on Cloudflare's edge network.
- **[memU (NevaMind-AI)](https://github.com/NevaMind-AI/memU)** - Advanced agentic memory framework and OpenClaw plugin for persistent 24/7 long-term memory.
- **[MimiClaw (memovai)](https://github.com/memovai/mimiclaw)** - A highly optimized OpenClaw variant for ESP32-S3 microcontrollers, running on a $5 chip.
- **[OpenClawInstaller (miaoxworld)](https://github.com/miaoxworld/OpenClawInstaller)** - A one-click automated deployment and configuration tool for OpenClaw.
- **[Tokscale (junhoyeo)](https://github.com/junhoyeo/tokscale)** - Token usage tracking CLI with explicit support for OpenClaw.ai.
- **[Manifest (mnfst)](https://github.com/mnfst/manifest)** - Smart LLM routing for OpenClaw agents, optimizing costs by up to 70% with real-time analytics.

## 🎨 Showcases & UI

- **[Star-Office-UI](https://github.com/ringhyacinth/Star-Office-UI)** - A beautiful desktop office UI built on OpenClaw.
- **[OpenClaw Studio](https://github.com/grp06/openclaw-studio)** - A web-based dashboard for managing OpenClaw Gateway, AI agents, and workflows.
- **[Crabwalk (luccast)](https://github.com/luccast/crabwalk)** - Real-time companion monitor for OpenClaw agents with live node graph visualization.

## 🧩 Community Skills

- **[XiaohongshuSkills](https://github.com/white0dew/XiaohongshuSkills)** - A powerful skill for Xiaohongshu auto-publishing, commenting, and searching. Supports OpenClaw.
- **[X Research Skill (rohunvora)](https://github.com/rohunvora/x-research-skill)** - A specialized research tool for X (Twitter), enabling agentic search and automated briefings.

## 💡 Use Cases

- **[YouTube Content Pipeline](https://github.com/hesamsheikh/awesome-openclaw-usecases/blob/main/usecases/youtube-content-pipeline.md)** - A comprehensive automation pipeline for YouTube creators to find video ideas, track pitches, and manage content using OpenClaw.
- **[Polymarket Autopilot](https://github.com/hesamsheikh/awesome-openclaw-usecases/blob/main/usecases/polymarket-autopilot.md)** - An automated paper trading system for Polymarket prediction markets using OpenClaw to execute trading strategies.
- **[Personal CRM](https://github.com/hesamsheikh/awesome-openclaw-usecases/blob/main/usecases/personal-crm.md)** - An automated Personal CRM with contact discovery from Gmail/Calendar and daily briefings via Telegram.
- **[Multi-Agent Content Factory](https://github.com/hesamsheikh/awesome-openclaw-usecases/blob/main/usecases/content-factory.md)** - A sophisticated multi-agent system on Discord for automated content production, including research and script writing.
- **[ClawWork (HKUDS)](https://github.com/HKUDS/ClawWork)** - An AI coworker framework based on nanobot (Ultra-Light OpenClaw), introducing economic accountability and task evaluation.

---

## 🤝 Contributing

Please read [CONTRIBUTING.md](./CONTRIBUTING.md) for details on how to submit a resource.

## 📄 License

Licensed under [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/).
