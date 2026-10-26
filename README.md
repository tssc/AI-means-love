# AI-means-love ❤️

![AI-means-love](assets/banner.svg)

**EN** · [ZH-CN](i18n/zh-CN/README.md) · [ZH-TW](i18n/zh-TW/README.md) · [JA](i18n/ja/README.md) · [KO](i18n/ko/README.md) · [ES](i18n/es/README.md) · [FR](i18n/fr/README.md) · [DE](i18n/de/README.md) · [PT](i18n/pt-BR/README.md) · [RU](i18n/ru/README.md)

> **Our foundation: Stay hungry. Stay foolish.** · *Simplicity is the ultimate sophistication.* — Steve Jobs


> **AI means love.**
> In Chinese, "AI" is pronounced exactly like 愛 — the word for *love*. We record every step of artificial intelligence because we believe its progress should be measured by how it helps, heals and connects people.

A living, verifiable **chronicle of AI history**: first backfilled from the 1950 Turing Test to today, then updated with **one carefully checked entry every day**. No hype, no invented stories — just the record of a world progressing, one day at a time.

## What this project does

1. **A verifiable chronicle** — `TIMELINE.md`
   Every entry has a date, what happened, **why it matters — the good it brings**, and sources. Dates are exact to the day when verifiable; otherwise only the month is given. Nothing is made up.
2. **Structured data** — `data/events.json`
   The same history in machine-readable form, ready to power a visual timeline website, charts, videos and daily digests.
3. **One entry a day** — `daily/YYYY-MM-DD.md`
   Each day we select the single event most worth remembering. If nothing qualifies, we honestly write "no entry today" and say why.

## What earns a place in history

✅ Major model or product launches, milestone papers, major open-source releases, scientific breakthroughs (medicine, proteins, accessibility…), and policy or governance events with wide impact
❌ Rumors, pure marketing, one-day stock moves, unsourced claims

Every entry requires an **official source first, plus at least one independent source** for cross-checking. See `docs/DAILY_UPDATE.md` and the multilingual rules in `docs/I18N.md`.

## Repository structure

```
AI-means-love/
├── README.md / TIMELINE.md     # English (canonical source)
├── i18n/<locale>/              # README + TIMELINE per language
├── data/events.json            # Structured events (canonical)
├── daily/                      # One entry per day
├── assets/                     # Banner and images
└── docs/                       # DAILY_UPDATE.md · I18N.md
```

## Translation status

**Full (README + 48-entry TIMELINE):** EN · ZH-CN · ZH-TW · JA · KO
**README full, TIMELINE in progress:** ES · FR · DE · PT · RU

English is the canonical source; other languages sync from it under the rules in `docs/I18N.md`. Translation PRs are very welcome.

## The name

- **AI** sounds like **愛 (love)**: technology for good is not a slogan here — it is the last column of every entry: *how does this make people's lives better?*
- That is what sets this chronicle apart from a plain timeline: it records not only what happened, but what it means for ordinary people.

## Contributing

Spotted a wrong date, a missing milestone, or a better source? Open an Issue or PR with the date, a source link and one sentence of explanation.

## Status

- [x] Backfill v1: 1950–2026, 48 entries (2026-10-26)
- [x] Published on GitHub (2026-10-26, https://github.com/tssc/AI-means-love)
- [x] Multilingual: 10 languages, English canonical (2026-10-26)
- [ ] Daily updates running (every day at 21:00 CST a draft is prepared and reviewed before publishing)
- [ ] Next: a visual timeline website

---
*Maintained daily. Because the world is progressing.*
