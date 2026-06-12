## Ke (Shawn) Xu — WhiteSwanQuant

**AI-driven independent quant researcher.** I run many parallel dry-run strategies on crypto derivatives 24/7, iterate by finding flaws in *reality* rather than in backtests, and publish occasional research notes on [LinkedIn](https://www.linkedin.com/in/ke-xu-quant). KCL Mathematics & Finance → Imperial College London.

Obsessed with derivatives microstructure. I scrape everything exchanges expose — open interest, long/short ratios, top-trader positioning, taker flow, funding, premium index — because price-only alpha is a crowded room. Currently learning to build **options strategies** (Deribit) as the next leg.

### 🧬 How my flagship was born — a flaw found in reality, not in a backtest

Good signals come from good statistics. But statistics are regime-conditional: in the **early-June 2026 BTC crash**, my then-live quality-first book fired **zero short entries** while its longs bled — the exact moment you most need the system to act is the moment statistically-mined signals go silent. Black swans don't appear in your threshold tables.

That failure became the design: split the book into an **alpha layer** (quality signals, no gates) and a **regime-coverage layer** (signals mined *per market regime*, scored by their thinnest regime-cell, so every regime × side combination always has ammunition). Smoothness moved from a hope into the mining objective function itself.

### 🔴 Currently live (dry-run, 24/7)
**[regime-smooth-45sig-2026-06](https://github.com/xke1/regime-smooth-45sig-2026-06)** — the result: 45 signals (24 alpha + 21 regime-fillers) on 90 Binance USDT-perps, thinnest cell = a long candidate every ~13 min *during downtrends*. Four exit philosophies (pure time-stop / hold-to-profit / take-profit / hybrid) run as a controlled live experiment — same signals, same entries, only exits differ. Ships with a **dead-ends museum** and unedited launch-night postmortems.

**[iter7y-pipeline-2026-05](https://github.com/xke1/iter7y-pipeline-2026-05)** — the quality-first sibling (and the book that went silent in the crash): 16 hand-curated low-frequency signals, walk-forward Sortino mining, deploy step embeds the research engine *verbatim* with bit-level `--verify`. Two books, two philosophies: smooth-everywhere vs. picky-and-precise.

> Alpha decays. Process compounds. I publish both — including everything that failed.

### 🧰 Older work
- [Quant-Atoms-and-Mining-Procedures](https://github.com/xke1/Quant-Atoms-and-Mining-Procedures) — 755-atom time-series library + non-overfitting mining discipline
- [StrategiesRepo](https://github.com/xke1/StrategiesRepo) — backtested → dry-run → lived strategies
- [ccxt-trade-checker](https://github.com/xke1/ccxt-trade-checker) — fees/funding/spread/impact cost checker

### 🤝
Community: [@whiteswanquant](https://x.com/whiteswanquant) · 中英双语 · Open to quant / AI×crypto roles in HK
