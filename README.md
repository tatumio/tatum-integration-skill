# Tatum Integration Skill

A skill for AI coding agents that automatically integrates Tatum blockchain API into any project. Detects your framework, writes code, installs dependencies, and configures everything.

## Installation

```bash
npx skills add https://github.com/tatumio/tatum-integration-skill --skill tatum
```

## Usage

```bash
/tatum add balance checking for Ethereum
/tatum add webhook for Bitcoin transactions
/tatum add NFT balance checking
/tatum add crypto price tracking
```

## What It Does

- Detects your framework (Express, FastAPI, Spring Boot, Django, Laravel, etc.)
- Creates service files, controllers, and routes following your project conventions
- Installs dependencies (`npm install`, `pip install`, etc.)
- Configures `.env` with API key
- Uses v4 endpoints (latest, non-deprecated)

## Supported Stacks

| Language | Frameworks |
|----------|-----------|
| JavaScript/TypeScript | Express, NestJS, Fastify, Koa |
| Python | FastAPI, Django, Flask |
| Java | Spring Boot, Quarkus, Micronaut |
| PHP | Laravel, Symfony, Slim |
| Go | Gin, Echo, Chi |
| Ruby | Rails, Sinatra |

## API Coverage (126 Endpoints)

| Category | Endpoints | Examples |
|----------|-----------|----------|
| V4 Data API | 75 | Wallets, transactions, tokens, NFTs, DeFi, staking, exchange rates |
| V4 Notifications | 16 | Webhook subscriptions, templates, filtering, HMAC verification |
| V3 Chain-Specific | 35 | TRON (10), XLM (7), XRP (8), ADA (6), Algorand (4) |

60+ blockchain networks supported including Ethereum, Bitcoin, Polygon, Solana, Arbitrum, Base, and more.

## Documentation

| File | Description |
|------|-------------|
| [Skill.md](Skill.md) | Complete integration workflow |
| [API Parameters](reference/api-parameters.md) | Request parameters for all endpoints |
| [API Responses](reference/api-responses.md) | Response schemas for all endpoints |
| [Data API Reference](reference/data-api-complete.md) | Full API reference (126 operations) |
| [Framework Examples](reference/frameworks/) | Express, FastAPI, Spring Boot, Django, Laravel |

## Support

- [GitHub Issues](https://github.com/tatumio/tatum-integration-skill/issues)
- [Tatum Docs](https://docs.tatum.io)

## License

MIT
