# JestBet — Online Casino & Sports Betting Platform

<p align="center">
  <img src="https://img.shields.io/badge/JestBet-Casino%20%2B%20Sportsbook-C9A227?style=for-the-badge" alt="JestBet casino and sportsbook" />
  <img src="https://img.shields.io/badge/MERN-MongoDB%20%7C%20Express%20%7C%20React%20%7C%20Node-47A248?style=for-the-badge" alt="MERN stack" />
  <img src="https://img.shields.io/badge/Casino-Timeless%20Tech%20API-1B4F72?style=for-the-badge" alt="Timeless Tech casino API" />
  <img src="https://img.shields.io/badge/Sports-Betradar%20API-0b3d5c?style=for-the-badge" alt="Betradar sports API" />
  <img src="https://img.shields.io/badge/Status-Available%20for%20customers-2ea44f?style=for-the-badge" alt="Available for customers" />
</p>

<p align="center">
  <strong>JestBet</strong> (also searched as <strong>JestBet</strong>) is a production-style <strong>online casino and sportsbook</strong> I built end-to-end.<br/>
  Casino games run on the <a href="https://www.timelesstech.io/en">Timeless Tech</a> Game Aggregator API.<br/>
  Live sports, fixtures, and odds run on <a href="https://www.betradar.com">Betradar</a> (Betrader sports API).<br/>
  The product is a single <strong>MERN stack</strong> application - MongoDB, Express, React, and Node.js.
</p>

<p align="center">
  <a href="./video.mp4" >
  <strong>▶ Watch the JestBet intro video</strong>
  </a>&nbsp; | &nbsp;
  <a href="https://t.me/casinodev1"><strong>Hire me / start a project</strong></a>
</p>

---


## What is JestBet?

**JestBet** is a combined **iGaming** product: one brand, one wallet, two revenue verticals.

| Product | What players get | Integration |
| --- | --- | --- |
| **JestBet Sportsbook** | Pre-match and in-play betting, live scores, markets, bet slip | **Betradar** sports API / Unified Odds-style feed |
| **JestBet Casino** | Slots, live casino, crash and aggregator titles in one lobby | **Timeless Tech** Game Aggregator API (seamless / transfer wallet) |
| **Account & cashier** | Register, login, deposit, withdraw, bet and game history | JWT auth, MongoDB wallet ledger |
| **Realtime** | Odds ticks, ticket status, balance updates | Node.js + Socket.IO |
| **Admin** | Players, risk, content, and reports | Role-based React admin |

Customers use JestBet when they want a **launch-ready sports + casino site**, not a collection of disconnected demos.

---

## Why operators look for JestBet

People searching for a **MERN casino**, a **Betradar sportsbook**, or a **Timeless Tech** integrator usually need the same thing: someone who has already joined those APIs to a real player product.

JestBet shows that work in one place:

- **Casino API — Timeless Tech** — lobby catalog, game launch, seamless and transfer wallet, provider callbacks
- **Sports API — Betradar (Betrader)** — fixtures, live scores, markets, and odds for football and other sports
- **MERN stack** — MongoDB for users, wallets, bets, and rounds · Express APIs · React sportsbook and lobby · Node.js workers and webhooks
- **One wallet** across sports tickets and casino rounds
- **Desktop and mobile** player UI

If that is the stack you are hiring for, you can skip a long discovery call and start from the video.

---

## Architecture

```
JestBet React client         Express / Node API              Providers
┌─────────────────┐         ┌──────────────────┐           ┌─────────────────┐
│ Sportsbook      │ REST +  │ Auth & wallets   │  odds     │ Betradar        │
│ Casino lobby    │ Socket  │ Bets & tickets   │ ────────► │ sports API      │
│ Cashier         │ ──────► │ Casino sessions  │  games    │ Timeless Tech   │
│ Admin           │         │ Webhooks         │ ────────► │ casino API      │
└─────────────────┘         └────────┬─────────┘           └─────────────────┘
                                     │
                                     ▼
                                MongoDB
```

---

## Skills this product demonstrates

I am a full-stack **iGaming** engineer. JestBet is the public proof of the work I do for customers.

**Core stack:** `MongoDB` `Express.js` `React` `Node.js` `Socket.IO` `JWT`

**Casino:** Timeless Tech aggregator · slots · live casino · crash · wallet callbacks

**Sports:** Betradar / Betrader sports API · pre-match · in-play · bet slip · cash-out style flows

**Product:** white-label sportsbook, online casino lobby, cashier, admin, responsible-gaming messaging

---

## Looking for JestBet, a sportsbook, or a casino build?

I take on work for operators, studios, and founders:

- New **JestBet-style** sports + casino launches
- **Timeless Tech** casino API integration
- **Betradar** / Betrader sports API integration
- Full **MERN** betting platforms
- Fixes, audits, and upgrades on an existing book

