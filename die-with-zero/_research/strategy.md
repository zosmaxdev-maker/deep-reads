# Die With Zero — Deep-Read Strategy

Generated: 2026-05-11

## Chapter plan (6 chapters, compressed from book's 9)

原书 9 章 + Conclusion + Appendix。Deep-read 压缩成 6 章（每章涵盖原书 1-2 个章节的概念簇），更适合"读了 → 学到"的节奏。

| Deep-read ch | Maps to original | Core concept | Whitelist citations |
|---|---|---|---|
| **Ch1: 生命能量 — 从赚钱到活出经历** | Ch1 + Ch2 | Life energy, experiences over things, memory dividend, compounding memories | 1 Finkelstein 2013, 3 Gold 1998, 5 Becker (Human Capital), 6 Carter-Gilovich 2012, 7 Bach (latte factor), 56 Robins-Dominguez |
| **Ch2: Die With Zero — 数学论点 + 工具集** | Ch3 + Ch4 | Life-Cycle Hypothesis (Modigliani), wasted life energy, longevity/mortality risk, annuities (Thaler annuity puzzle), life expectancy calculators, "Final Countdown" | 8 Hurd 1992, 9 Shefrin-Thaler 1991, 10 Bricker 2017, 11 Banerjee 2018, 12 Stein 1998, 13 Foster 2015, 14 Chou 2003, 15 Palumbo 1999, 16 AARP 2018, 17 Statista 2019, 18 Lieber 2018, 19 Thaler 2011, 20 Becker-Murphy-Philipson 2007, 21 Final Countdown app, 54 Modigliani LCH |
| **Ch3: 给孩子和慈善 — 时机决定一切** | Ch5 | Inheritance peak age 60 problem, three Rs (random), peak utility of money, giving while living (Chuck Feeney), charity timing | 22 Feiveson-Sabelhaus 2018, 23 Wolff-Gittleman 2014, 24 Krakovsky 2019, 25 Chopik-Edelstein 2019, 26 Heinrich 2014, 27 Behrman-Stacey 1997, 28 Psacharopoulos-Patrinos 2018, 29 Jansen-Katz 2002, 30 Grant-Buxton 2018, 2 Callahan 2018 |
| **Ch4: 健康 · 金钱 · 时间 — 平衡三角** | Ch6 | 50-30-20 critique, shifting balance with age, declining utility curve, health as multiplier, buying time, personal interest rate, marshmallow test | 31 Dubner-Levitt 2013, 32 Warren-Tyagi 2006, 33 Nyaupane 2008, 34 Sapolsky 1998, 35 Honeyman 2016 (Stern), 36 Cross 2018 (Staples bet), 37 Whillans 2017, 38 Maverick 2019, 55 Mischel marshmallow |
| **Ch5: Time Buckets + 你的 Net Worth Peak** | Ch7 + Ch8 | Many deaths (life stages), regret-free living, savoring, time buckets vs bucket list, biological age, net worth peak as date, decumulation | 39 Ware 2012, 40 Layous 2018, 41 Moore 2018 Census, 42 PropertyMetrics 2018, 43 O'Hara AARP, 44 Sell 2018, 45 Pew 2018, 46 Gosselin 2019, 47 DQYDJ, 48 Fed 2018, 49 Smith Kiplinger 2018, 50 GAO 2017, 51 Miller 2017 |
| **Ch6: Be Bold + 整合** | Ch9 + Conclusion | Asymmetric risk, age & risk tolerance, Mark Cuban / Cohen Goonies stories, quantify the fear, risk averse vs fearful, integration capstone | 52 Vohs 2019, 53 Cohen interview, plus web critiques (White Coat Investor, Bogleheads) |

## Per-chapter component counts (AI adaptive)

| Ch | Reflection exercises | Quiz items |
|---|---|---|
| Ch1 (foundation) | 4 | 5 |
| Ch2 (heavy math + tools) | 4 | 5 |
| Ch3 (kids/charity, fewer 实证) | 3 | 4 |
| Ch4 (rich tradeoffs) | 4 | 5 |
| Ch5 (most actionable) | 5 | 5 |
| Ch6 (capstone) | 4 | 5 |

## Voice rules

- Direct, challenging, second person 你
- Match Psychology-of-Money ch1 baseline tone
- Include 1-2 `pullbox.warn` "挑战" boxes per chapter pushing back on reader complacency
- Cite web critiques where appropriate (especially Ch2 / Ch6) to show this isn't blind cheerleading

## Critical theme: 这本书的内在张力

- Bill 假设读者 over-saving，但 White Coat Investor 反驳：大多数美国人 under-saving。教材要承认这个张力。
- "Die with literal zero" 不可能精确实现——教材要重新定义为 "die close to zero, not literal zero"
- 给孩子/慈善 = 内嵌挑战：如何避免给孩子太多让他们 spoiled

## Parallelization plan (P3)

- Main thread 写 ch1 (建立 baseline)
- 5 agents 并行 ch2-ch6（每个一章）
- 等所有 agents 完成
- Main thread P4 capstone

## File outputs

```
~/deep-reads/die-with-zero/
├── _research/
│   ├── sources.md           ✅ written
│   └── strategy.md          ✅ written (this file)
├── ch1-life-energy.html             ← main thread
├── ch2-die-with-zero-math.html      ← agent
├── ch3-kids-and-charity.html        ← agent
├── ch4-health-money-time.html       ← agent
├── ch5-time-buckets-and-peak.html   ← agent
├── ch6-be-bold.html                 ← agent
├── outline.html             ← main thread P4
├── index.html               ← main thread P4 (capability map)
├── README.md                ← main thread P4
└── deploy.sh                ← main thread P6
```
