# Crypto records and reconciliation

**Private development · earlier open-source version available**

[Browse the public version](https://github.com/0xatd/onchain-wallets-dashboard)

## The problem

A wallet history is not a complete financial history. Transfers, exchange records, protocol custody, and original acquisition costs need to be connected without inventing missing information.

## What I built

- A public, self-hosted wallet/transaction organizer with agent-facing API and MCP surfaces.
- A more recent private implementation with receipt-backed tracing, a deterministic evidence collector, a shared investigation queue, and reviewable accounting proposals.
- Tests for incomplete evidence, duplicate processing, custody continuity, and preservation of original source records.

The private build is not published in the public repository. Personal transaction records, wallet ownership decisions, and audit evidence stay private. This is ongoing reconciliation software, not a claim that a complete tax audit has been finished or that generated figures are filing-ready.

[Back to profile](../README.md)
