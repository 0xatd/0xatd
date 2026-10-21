# Crypto accounting

**In development · earlier open-source version available**

[Browse the public version](https://github.com/0xatd/onchain-wallets-dashboard)

## Why I’m building it

Every year I spend around $1,000 on crypto tax accounting and still end up fixing errors, tracking down missing transactions, and doing a lot of the work myself. I’m building this to make that process much cheaper and easier for anyone with onchain activity.

## What it does today

The system brings together wallet and exchange records, traces transactions, and investigates missing cost basis. Software handles supported transactions automatically; AI helps investigate the unresolved cases. It also looks for forgotten wallets and acquisition records, with ownership confirmed before another wallet is included.

The current build includes receipt-backed tracing, an investigation queue, and accounting proposals linked to their supporting records. An earlier self-hosted version is public; the latest development is still private.

## Where it’s going

The goal is to start with one address—ideally your main wallet—and reconstruct your financial history across the accounts you own: transactions, transfers, original acquisition costs, and tax accounting.

I plan to open-source the full system so anyone can run it themselves, then offer a hosted version for people who want an easy place to save their records and keep them up to date.

[Back to profile](../README.md)
