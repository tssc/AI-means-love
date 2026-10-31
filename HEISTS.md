# 🔐 The Great Crypto Heists — a side chronicle

> This project's main timeline records **AI history only**. This page is a deliberate side room: the security history behind the timeline's AI-for-cybersecurity entries (Gemini 4 Carbon, Mistral Large 4). It is **not** part of the main timeline, and its events are not counted in `data/events.json`.

Why keep it at all? Because the largest theft in crypto history happened the same week frontier models started advertising cyber benchmarks — the offence and the defence now scale together.

---

## The main event · 2026-10-30 — Binance loses $6.3 billion

- **Date**: 2026-10-30 (Beijing time, from ~04:05 CST; 20:00 UTC on Oct 29)
- **Category**: Cybersecurity incident
- **Protagonist**: Binance

### What happened

Attackers drained about **$6.3 billion** of crypto from the hot wallets of Binance, the world's largest crypto exchange — the biggest crypto theft on record, roughly four times the $1.5 billion Bybit hack of February 2025. Blockchain records show the bulk moved in about **20 minutes**, across Ethereum, Bitcoin, Tron, Solana, the XRP Ledger and other networks.

Binance's preliminary investigation points to a compromised **DevOps engineer's laptop**, which gave the attacker access to a service container used to submit unauthorized withdrawal transactions; the exchange later said it had found additional points of breach, and reported no evidence of a wallet private-key leak. Blockchain analytics firm TRM Labs says the attackers compromised Binance's **signing infrastructure** — the system that authorizes transactions.

### Response and recovery

- Binance suspended withdrawals, began a full security review, and pledged to cover all losses from company funds: about **$6.34 billion** set aside internally, roughly $5 billion of it already held in the same assets that were taken, the remaining ~$1.3 billion being bought through market and OTC channels. The exchange also operates the SAFU fund, a $1 billion bitcoin reserve for user protection.
- Stablecoin issuers and partners froze about **$3 billion** of the stolen assets: Tether froze over $1.567 billion in USDT, Circle over $800 million in USDC, Ripple about $200 million, and World Liberty Financial roughly $27–29 million.
- TRM estimates about **$2.4 billion** — mostly bitcoin and ether, which no issuer can freeze remotely — remains beyond easy reach.
- Attribution is unsettled: TRM Labs and Elliptic see strong similarities to North Korea's TraderTraitor (Lazarus-linked) operations, with TRM highly confident it is the same group as the Bybit hack; Binance itself has not identified the attackers, and North Korea routinely denies such claims. Investigation ongoing.

### Why it matters

The biggest crypto heist ever was not a stolen vault key — it was a hijacked authorization system: one compromised laptop reaching the machinery that tells the vault to release money. And the recovery shows the industry's unique other side: centrally issued stablecoins can be frozen on-chain, pinning about half the loot in place within hours.

### The good it brings

If Binance makes users whole as pledged, ordinary customers bear none of the cost of the largest theft in the industry's history; and the promised full technical post-mortem would become a security textbook for every major platform.

### Sources

- Official: Binance, Security Incident Update #2 (2026-10-30) — https://www.binance.com/zh-CN/square/post/382974122328634
- Independent: Reuters, *Gone in 20 minutes* (2026-10-30) — https://www.reuters.com/legal/government/gone-20-minutes-how-biggest-heist-crypto-history-unfolded-2026-10-30/
- Independent: The Block (2026-10-30) — https://www.theblock.co/news/ecosystems/2026-10-30-binance-says-it-has-6-34-billion-ready-to-cover-hack-losses-432208

---

## Before it · the major crypto thefts

Amounts are values at the time of each event, per the sources listed below. The Reuters ranking (2026-10-30) is the main basis; Binance's own two earlier incidents are cross-checked against CoinDesk.

| Date | Event | Amount | What happened, in one line |
|---|---|---|---|
| 2025-02-21 | Bybit | ~$1.5B | Ether taken from a cold wallet; the FBI attributed the theft to North Korea's TraderTraitor actors |
| 2021-08 | Poly Network | ~$610M | DeFi cross-chain exploit; the hacker later returned nearly all of it |
| 2022-10-06 | BNB Chain bridge (Binance ecosystem) | ~$570M minted, ~$100–110M actually moved off | A forged proof minted 2M BNB through the BSC Token Hub; validators halted the chain and froze most of it; no user funds taken |
| 2022-03 | Ronin Network | ~$540M | 173,600 ETH and 25.5M USDC stolen from the Axie Infinity sidechain |
| 2018-01 | Coincheck | ~$530M | Hot-wallet breach that tightened exchange-security rules in Japan |
| 2011–2014 | Mt. Gox | ~$500M | The exchange that once handled ~80% of global bitcoin trade was drained over years; bankruptcy in 2014, ~24,000 customers affected |
| 2022-02 | Wormhole | ~$320M | Bridge exploit took 120,000 wrapped ETH; Jump Trading later replaced the funds |
| 2019-05-07 | Binance hot wallet | 7,000 BTC (~$40M) | Phishing and malware harvested API keys and 2FA codes, then one transaction out; Binance covered it fully from the SAFU fund |

Sources: Reuters ranking — https://www.reuters.com/legal/government/where-binances-63-billion-breach-ranks-cryptos-biggest-hacks-heists-2026-10-30/ ; FBI public service announcement on Bybit (2025-02-26, I-022625-PSA); CoinDesk on Binance 2019 — https://www.coindesk.com/markets/2019/05/07/hackers-steal-407-million-in-bitcoin-from-crypto-exchange-binance/ and on the BNB Chain incident — https://www.coindesk.com/business/2022/10/06/binance-linked-bnb-price-falls-close-to-4-on-hack-rumors/

---

*Side chronicle added 2026-10-31. Kept separate from the AI timeline on purpose — Stay hungry. Stay foolish.*
