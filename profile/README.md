# Belonix

**Open developer ambassador platform.**

Belonix bridges dev tool companies and the builders who use them — making developer advocacy structured, transparent, and paid.

---

## What is Belonix?

Dev tools live or die by word-of-mouth from real developers. Belonix makes that word-of-mouth scalable and merit-based.

Any user can create campaigns and apply to other campaigns — there is no separate "company" or "ambassador" account type. Independent developers earn USDC for the work they already do: writing tutorials, shipping integrations, posting threads. DevRel teams run structured programs without hiring. Everyone operates on the same transparent platform.

**Built for:** independent developers looking to earn from their existing work, and DevRel teams at dev tool companies who want to run ambassador programs at scale.

---

## Core Loop

1. **Create a campaign** — set dates, cohort size, and fund a USDC reward pool directly from your wallet
2. **Define tasks** — write briefs with required tags, link patterns, and payout tiers
3. **Apply** — developers browse active campaigns and submit applications
4. **Submit proof** — approved cohort members complete tasks and submit proof links
5. **Get paid** — approved submissions trigger automatic USDC transfers on-chain

---

## Features

### For Developers

- Wallet-first sign-in — no email or password required
- Browse active campaigns without an account
- Connect X, GitHub, and Telegram to unlock platform actions
- Apply to campaigns and track application status
- Access a per-campaign cohort dashboard once approved
- Submit work with proof links and notes
- Automatic USDC payouts to your connected wallet on approval
- Tier system with payout multipliers (trial → starter → plus → pro → elite)
- Full payout history with on-chain transaction links
- Per-campaign leaderboard with self-highlight
- Notifications via email or Telegram

### For Campaign Creators

- Any authenticated user can create campaigns
- Fund the USDC reward pool at campaign creation directly from your wallet (on-chain)
- Define tasks with rich markdown briefs, required tags, difficulty tiers, and deadlines
- View the cohort — who applied, who was approved
- Review submissions from participants

### For Admins

- Cohort approval queue — approve or reject applicants with notes
- Submission review with per-submission payout amount control
- Automated on-chain USDC transfers triggered by submission approval
- User tier assignment (5 tiers with multipliers from 1.0× to 3.0×)
- Funnel metrics dashboard with stage-by-stage drop-off

---

## Tech Stack

| Layer         | Technology                                           |
| ------------- | ---------------------------------------------------- |
| Frontend      | Next.js 15 (App Router), TypeScript, Tailwind CSS v4 |
| Backend       | Node.js, Express, TypeScript, Prisma                 |
| Database      | PostgreSQL 16                                        |
| Auth          | Sign In with Ethereum (SIWE), JWT                    |
| Blockchain    | Base (automated USDC payouts)                        |
| Notifications | Email + Telegram                                     |
