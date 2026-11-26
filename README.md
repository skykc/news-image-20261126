# The Thursday Globe — Thursday 26 November 2026

[![Rank](https://make.fun/badge/news-image-20261126/skykc/news-image-20261126/rank.svg)](https://make.fun/bounty/news-image-20261126)
[![Reward](https://make.fun/badge/news-image-20261126/skykc/news-image-20261126/reward.svg)](https://make.fun/bounty/news-image-20261126)

**Thursday 26 November 2026: Macy's 100th parade postponed, 30 killed in Cairo tanker fire, Pakistan's first astronaut reaches Tiangong — 35 stories, 14 vector scenes, a UTC timeline and a date check**

One image that sums up Thursday 26 November 2026's world news, drawn as a newspaper front page: a masthead naming the day, three hero stories with drawn vector scenes (Macy's 100th Thanksgiving Day Parade postponed to Saturday by a nor'easter; at least 30 killed in a fuel-tanker fire on Cairo's Ring Road; Pakistan's Muhammad Zeeshan Ali becomes the first foreign astronaut on a Chinese crewed mission to Tiangong), eight illustrated mid stories, 24 more stories grouped by region, a UTC timeline of the overnight wires, and a date check that excludes stories from before 26 November.

- **35 stories** — Americas 8 · Europe 8 · Middle East 3 · Asia 8 · Africa 4 · Oceania 1 · Global 3
- **14 vector scenes**, all drawn in SVG — no photos, no garbled text
- **Legible at ~300 px**: masthead, hero headlines and callouts stay readable when shrunk

## How it is built

`page.html` is the front page (Liberation fonts in `fonts/`). It is rendered to `entry.png` (1024×1024, ≤1 MiB) with the shot-tools renderer, and `main.ts` (Node 22, standard library only) copies `entry.png` to `/output/entry.png`:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Sources

Reuters · BBC · AP · The Guardian · Kyiv Independent · Times of India · NBC · Al Jazeera · Libre News — compiled 26 November 2026.

[Competition: news-image-20261126 on make.fun](https://make.fun/bounty/news-image-20261126)
