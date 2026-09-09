# solana-token-scanner
Free real-time Solana token discovery with trust scores, risk analysis and smart money detection

# Solana Token Scanner

**Free real-time Solana token discovery and risk analysis.**

🔍 **Live at:** [solanatokenscanner.com](https://www.solanatokenscanner.com)

## What It Does

Monitors new Solana token launches every 5 minutes and analyzes each one for:

- **Trust Score** (0–100) based on 6 on-chain factors
- **Risk Flags** — LP lock, mint authority, freeze authority
- **Momentum Score** — volume acceleration, buy pressure, holder growth
- **Smart Money Detection** — known wallet activity
- **Holder Concentration** — top-10 wallet distribution

## Features

- ⚡ Real-time scanner — new tokens every 5 minutes
- 🛡️ Automated risk analysis
- 📊 Trust Score with full breakdown
- 🧠 Smart Money signals
- 🔥 Trending tokens
- 💧 High liquidity rankings
- 📈 Volume rankings
- 🆓 Free — no login required

## Data Sources

| Source | Data |
|--------|------|
| [DexScreener](https://dexscreener.com) | Price, liquidity, volume, pairs |
| [Helius](https://helius.dev) | Holder data, token authority |
| [RugCheck](https://rugcheck.xyz) | Risk score, LP lock status |

## Tech Stack

- **Frontend:** Next.js 15, TypeScript, Tailwind CSS
- **Database:** PostgreSQL (Supabase) + Prisma ORM
- **Deployment:** Vercel
- **APIs:** DexScreener, Helius RPC, RugCheck

## Live Demo

Visit **[solanatokenscanner.com](https://www.solanatokenscanner.com)** to:

- Browse newly discovered Solana tokens
- Analyze any token by address
- Track trending tokens with momentum data
- Identify smart money activity

## Disclaimer

This tool provides blockchain data analysis for informational purposes only.
Not financial advice. Always conduct your own research (DYOR).

---

⭐ Star this repo if you find it useful!
