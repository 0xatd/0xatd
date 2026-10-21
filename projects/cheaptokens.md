# CheapTokens

**Live product · private application code · public agent skill pack**

[Use CheapTokens](https://cheaptokens.ai) · [Public skills](https://github.com/0xatd/cheaptokens-skills)

## The product

Discounted Venice AI API credits for people and agents. I built and operate the product, including the purchase flow, credit accounting, key delivery, and agent-facing integration.

## Engineering

- Next.js application with Postgres-backed purchases and credit accounting.
- USDC/x402 payments on Base, settlement verification, and wallet-authenticated account flows.
- Same-day credits and prepaid usage workflows.
- Provider cooldown handling and recovery for eligible paid-but-undelivered purchases.
- An agent router skill for discovering credits, checking expiry, and calling Venice endpoints.

The public skill pack separates my CheapTokens routing work from the official Venice skills it vendors, with source and license attribution. The production application is private; the skill repository is not a mirror of that application.

Venice is the provider integration for this product, not the scope of all my work.

[Back to profile](../README.md)
