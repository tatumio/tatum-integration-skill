<div align="center">

# ⛓️ Tatum Integration Skill

**One command. Any framework. Full blockchain API access.**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Endpoints](https://img.shields.io/badge/API_Endpoints-126-blue)](reference/data-api-complete.md)
[![Chains](https://img.shields.io/badge/Blockchains-60+-purple)](#-supported-networks)
[![Frameworks](https://img.shields.io/badge/Frameworks-18+-green)](#-supported-stacks)

A skill for AI coding agents that automatically integrates the **Tatum blockchain API** into any project.
Detects your framework, writes code, installs dependencies, and configures everything.

</div>

---

## 🚀 Quick Start

```bash
npx skills add https://github.com/tatumio/tatum-integration-skill --skill tatum
```

Then just tell it what you need:

```bash
/tatum add balance checking for Ethereum
/tatum add webhook for Bitcoin transactions
/tatum add NFT balance checking
/tatum add crypto price tracking
```

---

## ✨ What It Does

| | Feature | Description |
|---|---------|-------------|
| 🔍 | **Auto-Detection** | Detects your framework: Express, FastAPI, Spring Boot, Django, Laravel, and more |
| 🏗️ | **Code Generation** | Creates service files, controllers, and routes following your project conventions |
| 📦 | **Dependency Management** | Installs packages automatically (`npm install`, `pip install`, etc.) |
| 🔐 | **Environment Config** | Configures `.env` with your Tatum API key |
| 🆕 | **Latest APIs** | Uses v4 endpoints (latest, non-deprecated) |

---

## 🛠️ Supported Stacks

| Language | Frameworks |
|:---------|:-----------|
| **JavaScript / TypeScript** | Express · NestJS · Fastify · Koa |
| **Python** | FastAPI · Django · Flask |
| **Java** | Spring Boot · Quarkus · Micronaut |
| **PHP** | Laravel · Symfony · Slim |
| **Go** | Gin · Echo · Chi |
| **Ruby** | Rails · Sinatra |

---

## 📡 API Coverage: 126 Endpoints

| Category | Endpoints | Examples |
|:---------|:---------:|:---------|
| **V4 Data API** | 75 | Wallets, transactions, tokens, NFTs, DeFi, staking, exchange rates |
| **V4 Notifications** | 16 | Webhook subscriptions, templates, filtering, HMAC verification |
| **V3 Chain-Specific** | 35 | TRON (10) · XLM (7) · XRP (8) · ADA (6) · Algorand (4) |

### 🌐 Supported Networks

> **60+ blockchain networks** including Ethereum, Bitcoin, Polygon, Solana, Arbitrum, Base, and more.

---

## 📚 Documentation

| Resource | Description |
|:---------|:------------|
| [📘 Skill.md](Skill.md) | Complete integration workflow |
| [📋 API Parameters](reference/api-parameters.md) | Request parameters for all endpoints |
| [📤 API Responses](reference/api-responses.md) | Response schemas for all endpoints |
| [📖 Data API Reference](reference/data-api-complete.md) | Full API reference (126 operations) |
| [💡 Framework Examples](reference/frameworks/) | Express, FastAPI, Spring Boot, Django, Laravel |

---

## 🤝 Support

- 🐛 [GitHub Issues](https://github.com/tatumio/tatum-integration-skill/issues) : Report bugs or request features
- 📖 [Tatum Docs](https://docs.tatum.io) : Official API documentation

---

<div align="center">

**MIT License** · Built with ❤️ by [Tatum](https://tatum.io)

</div>
