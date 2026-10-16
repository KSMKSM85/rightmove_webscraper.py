# hyperliquid-trading-bot

Testnet-first trading bot for Hyperliquid.

Status: empty. Nothing in this repository trades real money.

Design principles:
- Testnet only until explicitly changed.
- Trades through an API (agent) wallet, which can trade but cannot withdraw.
- Hard position-size and daily-loss limits enforced in code, plus a kill switch.
- Private keys live in a local `.env` file, which is git-ignored and never committed.
