# IRZIAN STUDIO

**Software, Automation & Digital Products**  
**Built with Trust. Made to Last.**  
**ساخته‌شده با اعتماد، ماندگار برای آینده**

IRZIAN STUDIO is the umbrella brand for a long-term digital business. Its foundation is designed to support software, automation, digital products, services, and—when the legal, technical, and operational requirements are ready—NFTs and other digital collectibles.

## Current stage

This repository contains the first public-facing website scaffold and the initial brand/operating documents. It is intentionally lightweight: no paid services, database, wallet, payment processor, or customer-data collection is enabled.

## Project structure

- `public/` — static website served by Cloudflare Workers static assets
- `docs/` — brand charter, roadmap, governance, and architecture notes
- `wrangler.toml` — Cloudflare Workers configuration

## Run locally

Requirements: Node.js and npm.

```bash
npm install
npm run dev
```

Open the local URL printed by Wrangler.

## Deploy to Cloudflare

```bash
npm run deploy
```

Connect this repository to Cloudflare Workers Builds. Use `npm run deploy` as the deploy command if the dashboard asks for one. No build step is currently required.

## Principles

1. Trust and clarity before growth.
2. Keep the core brand independent of any single product or platform.
3. Add new business lines without breaking existing ones.
4. Protect customer privacy and collect only necessary data.
5. Document important decisions so future maintainers can understand them.
6. Do not launch payments, wallets, or NFT features until security, legal, and operational reviews are complete.

## Brand families

- **IRZIAN Software** — software products and utilities
- **IRZIAN Labs** — research, prototypes, and experiments
- **IRZIAN Digital** — digital assets and collectibles
- **IRZIAN Services** — automation and digital services

These are planned brand families, not separate legal entities.

## Status

Foundation / Version 0.1.0 — October 2026.
