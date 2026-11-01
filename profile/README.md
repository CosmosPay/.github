<div align="center">

# 🪐 Cosmos Pay

**Stablecoin payments for developers and businesses.**

Accept stablecoins with payment links, a hosted checkout or one REST API, on Stellar, Solana and Monad.
Non-custodial: payments settle to the merchant's own address.

[Website](https://cosmospay.lat) · [Payments](https://payments.cosmospay.lat) · [Docs](https://dev.cosmospay.lat/docs/) · [JS/TS SDK on npm](https://www.npmjs.com/package/@cosmosapp/pay_sdk) · [organization@cosmospay.lat](mailto:organization@cosmospay.lat)

<sub>Cosmos Pay (cosmospay.lat) is a different project from the Cosmos Network (ATOM).</sub>

</div>

---

## What it does

- **Payment links and QR codes** from the dashboard, with no code.
- **Hosted and embedded checkout** in seven languages; a pay button or an embedded checkout takes one script tag.
- **Payments REST API** described by an [OpenAPI document](https://dev.cosmospay.lat/docs/openapi.json), a typed JavaScript/TypeScript SDK and webhooks signed with HMAC-SHA256.
- **Three networks**: SEP-7 links on Stellar, Solana Pay links on Solana and EIP-681 links on Monad.
- **Test first**: `dv_` API keys run on test networks, `prod_` keys on mainnet. The key picks the network.
- **Pricing** per payment from 1.5% + 18¢ on Starter, with no monthly fee. See the [plans](https://cosmospay.lat/pricing).

## Projects

| Repository | What it is |
|---|---|
| [**CosmosPay-Developer-Platform**](https://github.com/CosmosPay/CosmosPay-Developer-Platform) | The dashboard, API keys, docs, hosted checkout and payment links (cosmospay.lat, payments.cosmospay.lat and dev.cosmospay.lat). |
| [**CosmosPay-Community-Server**](https://github.com/CosmosPay/CosmosPay-Community-Server) | The Payments API (NestJS + Prisma): payment intents, payment links, swaps and webhooks on Stellar, Solana and Monad. |
| [**CosmosJS_SDK**](https://github.com/CosmosPay/CosmosJS_SDK) | `@cosmosapp/pay_sdk`, the JavaScript / TypeScript SDK for the Payments API. |
| [**CosmosPay-Wallet**](https://github.com/CosmosPay/CosmosPay-Wallet) | Cosmos Wallet, non-custodial: web app, browser extension, desktop and Android builds. Keys are generated and encrypted on the device. |
| [**CosmosPay-Skill**](https://github.com/CosmosPay/CosmosPay-Skill) | Agent skill (`SKILL.md`) that teaches AI coding agents to integrate Cosmos Pay on Stellar, Solana and Monad. |
| [**Stellar-Snap**](https://github.com/CosmosPay/Stellar-Snap) | MetaMask Snap for Stellar and Soroban accounts, payments, swaps and signatures, with a SEP-43 adapter for dApps. |
| [**cosmos-pay-arc**](https://github.com/CosmosPay/cosmos-pay-arc) | A Cosmos Pay payment intent on Arc, Circle's USDC-gas L1: charge in USDC and settle to the merchant in one transaction. |
| [**cosmos-app-runtime**](https://github.com/CosmosPay/cosmos-app-runtime) | Declarative runtime for third-party Cosmos Apps: the app runs in a Web Worker and describes its UI. |
| [**cosmos-app-bridge**](https://github.com/CosmosPay/cosmos-app-bridge) | postMessage bridge between a Cosmos App and the platform that embeds it, with origin checks in both directions. |

## For AI assistants and agents

- [Docs index for LLMs](https://dev.cosmospay.lat/docs/llms.txt) and the [site summary](https://cosmospay.lat/llms.txt); every indexable page is also Markdown at its address with `.md`.
- [How an agent authenticates](https://cosmospay.lat/auth.md): an API key a person creates in the dashboard.
- The [agent skill](https://github.com/CosmosPay/CosmosPay-Skill), listed in the [agent skills index](https://cosmospay.lat/.well-known/agent-skills/index.json).
- [Using the docs with AI](https://dev.cosmospay.lat/docs/ai/).

## Get started

```bash
npm install @cosmosapp/pay_sdk
```

Create an account and your API keys in the [Developer Platform](https://dev.cosmospay.lat), then follow the [server SDK quickstart](https://dev.cosmospay.lat/docs/sdk/server/quickstart/).

---

<div align="center">
<sub>Built in Argentina 🇦🇷. Payments on <a href="https://stellar.org">Stellar</a>, <a href="https://solana.com">Solana</a> and <a href="https://www.monad.xyz">Monad</a>.</sub>
</div>
