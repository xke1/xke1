## Ke (Shawn) Xu — WhiteSwanQuant

**EN** | [中文在下方](#中文)

**AI-driven independent quant researcher.** I run many parallel dry-run strategies on crypto derivatives 24/7, iterate by finding flaws in *reality* rather than in backtests, and publish occasional research notes on LinkedIn. BSc Mathematics @ King's College London → MSc Strategic Marketing @ Imperial College Business School.

Obsessed with derivatives. I scrape everything exchanges expose — open interest, long/short ratios, top-trader positioning, taker flow, funding, premium index — because price-only alpha is a crowded room. Currently learning to build **options strategies** (Deribit) as the next leg.

### 🧬 How my flagship was born — a flaw found in reality, not in a backtest

Good signals come from good statistics. But statistics are regime-conditional: in the **early-June 2026 BTC crash**, my then-live quality-first book fired **zero short entries** while its longs bled — the exact moment you most need the system to act is the moment statistically-mined signals go silent. Black swans don't appear in your threshold tables.

That failure became the design: split the book into an **alpha layer** (quality signals, no gates) and a **regime-coverage layer** (signals mined *per market regime*, scored by their thinnest regime-cell, so every regime × side combination always has ammunition). Smoothness moved from a hope into the mining objective function itself.

### 🔴 Currently live (dry-run, 24/7)
**[regime-smooth-45sig-2026-06](https://github.com/xke1/regime-smooth-45sig-2026-06)** — the result: 45 signals (24 alpha + 21 regime-fillers) on 90 Binance USDT-perps, thinnest cell = a long candidate every ~13 min *during downtrends*. Four exit philosophies run as a controlled live experiment — same signals, same entries, only exits differ. Ships with a **dead-ends museum** and unedited launch-night postmortems.

**[iter7y-pipeline-2026-05](https://github.com/xke1/iter7y-pipeline-2026-05)** — the quality-first sibling (and the book that went silent in the crash): 16 hand-curated low-frequency signals, walk-forward Sortino mining, deploy step embeds the research engine *verbatim* with bit-level `--verify`. Two books, two philosophies: smooth-everywhere vs. picky-and-precise.

> Alpha decays. Process compounds. I publish both — including everything that failed.

### 🧰 Older work
- [Quant-Atoms-and-Mining-Procedures](https://github.com/xke1/Quant-Atoms-and-Mining-Procedures) — 755-atom time-series library + non-overfitting mining discipline
- [StrategiesRepo](https://github.com/xke1/StrategiesRepo) — backtested → dry-run → lived strategies
- [ccxt-trade-checker](https://github.com/xke1/ccxt-trade-checker) — fees/funding/spread/impact cost checker

### 🤝
Community: [@whiteswanquant](https://x.com/whiteswanquant) · 中英双语 · Open to quant / AI×crypto roles in HK

---

<a name="中文"></a>
## 中文

**AI 驱动的独立量化研究者。** 多个加密衍生品策略并行 dry-run 7×24 跑着,迭代方式是从**现实**里找缺陷而不是从回测里,研究心得不定期发在 LinkedIn。本科数学 @ 伦敦国王学院(KCL)→ 硕士战略营销 @ 帝国理工商学院。

对衍生品痴迷。交易所暴露什么我就爬什么 — 持仓量、多空比、大户持仓、taker 流量、资金费率、溢价指数 — 因为纯价格 alpha 是个拥挤的房间。正在学习搭建 **期权交易策略**(Deribit)作为下一条腿。

### 🧬 旗舰策略的诞生 — 缺陷在现实里被发现,不在回测里

好信号基本都来自好的统计。但统计是体制条件化的:**2026 年 6 月初 BTC 大跌**,当时在跑的质量优先 book 空头**开仓 0 次**,多头持续失血 — 最需要系统出手的时刻,恰恰是统计挖出来的信号集体失声的时刻。黑天鹅不会出现在你的阈值表里。

这次失败变成了设计本身:把 book 拆成 **alpha 层**(质量信号,无门槛)+ **体制覆盖层**(按市场体制分格挖矿、按最薄格打分,保证任何体制×方向组合永远有弹药)。"开仓丝滑"从愿望变成了挖矿目标函数。

### 🔴 正在跑(dry-run, 7×24)
**[regime-smooth-45sig-2026-06](https://github.com/xke1/regime-smooth-45sig-2026-06)** — 上面那个设计的成品:45 信号(24 alpha + 21 体制填充)跑 90 个 Binance U 本位永续,最薄格 = 阴跌体制下每 ~13 分钟仍有多头候选。四种出场哲学做受控实盘实验 — 同信号、同入场,只有出场不同。附带**死路博物馆**和未删改的上线夜复盘。

**[iter7y-pipeline-2026-05](https://github.com/xke1/iter7y-pipeline-2026-05)** — 质量优先的兄弟篇(也就是大跌中失声的那个 book):16 个人工精选低频信号、walk-forward Sortino 挖矿、部署环节把研究引擎**逐字内嵌**进实盘文件并附 bit 级 `--verify`。两个 book,两种哲学:处处丝滑 vs 挑剔精准。

> Alpha 会衰减,过程会复利。两个都公开 — 包括所有失败的。

### 🧰 早期工作
- [Quant-Atoms-and-Mining-Procedures](https://github.com/xke1/Quant-Atoms-and-Mining-Procedures) — 755 个时序 atom 库 + 反过拟合挖矿纪律
- [StrategiesRepo](https://github.com/xke1/StrategiesRepo) — 回测 → dry-run → 实盘的策略集
- [ccxt-trade-checker](https://github.com/xke1/ccxt-trade-checker) — 手续费/资金费/点差/冲击成本检查器

### 🤝
社区: [@whiteswanquant](https://x.com/whiteswanquant) · 中英双语 · 求职方向: 香港 quant / AI×crypto
