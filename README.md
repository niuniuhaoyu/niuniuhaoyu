# Hi, I'm Haoyu Niu 👋

[English](README.md) | [简体中文](README_zh.md)

Senior undergraduate in **Applied Economics** at the
[City University of Macau](https://www.cityu.edu.mo/).

I'm interested in **econometrics** and **causal inference**, and I build
open-source tools for empirical research — currently focused on modern
difference-in-differences methods, heterogeneous treatment effects, and
their diagnostics.

## Research interests

- Causal inference & program evaluation
- Difference-in-differences and pre-trends diagnostics
- Heterogeneous treatment effects (causal forests / GRF)
- Applied microeconometrics

## Projects

Open-source tools for empirical analysis. I write them in Stata (ado + Mata)
and Python, verify them against independent implementations, and ship the tests.
Each Stata package ships English and Chinese documentation.

**Stata packages**

- **[contdid](https://github.com/niuniuhaoyu/contdid)** — difference-in-differences
  with a continuous treatment (Callaway, Goodman-Bacon & Sant'Anna 2024):
  B-spline dose-response `ATT(d)` and the average causal response `ACRT(d)`,
  uniform confidence bands, staggered adoption, and conditional parallel trends
  (`covariates()`). Cross-validated against the authors' R implementation.

- **[qdid](https://github.com/niuniuhaoyu/qdid)** — quantile difference-in-differences
  (Callaway & Li 2019): the quantile treatment effect on the treated `QTT(τ)` via
  copula stability, cluster-bootstrap intervals, a uniform confidence band,
  conditional QTT, and staggered adoption. Matched to R `qte`.

- **[didc](https://github.com/niuniuhaoyu/niuniuhaoyu-didc)** — difference-in-discontinuities
  (Picchetti, Pinto & Shinoki 2026): local polynomial estimation when a
  confounding policy is assigned at the same cutoff, with the paper's two
  validity tests and partial-identification bounds. The estimation kernel is
  checked against an independently coded weighted-least-squares fit.

- **[cforest](https://github.com/niuniuhaoyu/cforest)** — causal forests /
  generalized random forests for Stata (Wager & Athey 2018; Athey, Tibshirani &
  Wager 2019): the conditional average treatment effect with out-of-sample
  prediction, best linear projection, and variable importance; cross-checked
  against R `grf`.

**Other**

- **[detective_engine](https://github.com/niuniuhaoyu/detective_engine)** — a
  constraint-driven detective-fiction generation engine (Python): backwards
  generation under fairness/solvability constraints, with an ingenuity scorer
  (inevitability × uniqueness × surprise).

- **[sop-pensieve](https://github.com/niuniuhaoyu/sop-pensieve)** — a living
  library of research & tooling **SOPs** ("pensieve"): case replication,
  DID/empirical-analysis standards, reference verification, pre-submission
  checklists, and AI-assisted coding verification. Every finished task leaves
  a reusable procedure behind.

## Links

- 🏫 City University of Macau
- 📫 3522359513@qq.com

---

[English](README.md) | [简体中文](README_zh.md)
