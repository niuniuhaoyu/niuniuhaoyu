# 你好，我是牛浩宇（Haoyu Niu）👋

[English](README.md) | [简体中文](README_zh.md)

澳门城市大学 [应用经济学](https://www.cityu.edu.mo/) 大四学生。

我对**计量经济学**与**因果推断**感兴趣，为实证研究开发开源工具——目前聚焦于现代双重差分
方法、异质性处理效应及其诊断。

## 研究兴趣

- 因果推断与项目评估
- 双重差分与前趋势诊断
- 异质性处理效应（因果森林 / GRF）
- 应用微观计量经济学

## 项目

面向实证分析的开源工具。我用 Stata（ado + Mata）与 Python 编写，与独立实现逐一核对，并
附带测试。每个 Stata 包都提供中英文文档。

**Stata 程序包**

- **[contdid](https://github.com/niuniuhaoyu/contdid)** —— 连续处理双重差分（Callaway、
  Goodman-Bacon & Sant'Anna 2024）：B 样条剂量-反应 `ATT(d)` 与平均因果响应 `ACRT(d)`、
  统一置信带、交错采纳、以及条件平行趋势（`covariates()`）。已与作者的 R 实现对拍。

- **[qdid](https://github.com/niuniuhaoyu/qdid)** —— 分位数双重差分（Callaway & Li 2019）：
  以 copula stability 估计处理组分位数处理效应 `QTT(τ)`，含聚类自助区间、统一置信带、
  条件 QTT 与交错采纳。已对拍 R `qte`。

- **[didc](https://github.com/niuniuhaoyu/niuniuhaoyu-didc)** —— 差中差断点（Picchetti、
  Pinto & Shinoki 2026）：当混淆政策由同一阈值赋值时的局部多项式估计，含论文的两项效度
  检验与部分识别界。估计内核与独立编写的加权最小二乘拟合核对。

- **[cforest](https://github.com/niuniuhaoyu/cforest)** —— Stata 版因果森林 / 广义随机
  森林（Wager & Athey 2018；Athey、Tibshirani & Wager 2019）：条件平均处理效应 + 样本外
  预测、最优线性投影、变量重要性；已与 R `grf` 对拍。

**其他**

- **[detective_engine](https://github.com/niuniuhaoyu/detective_engine)** —— 约束驱动的
  推理小说生成引擎（Python）：在公平性 / 可解性约束下倒推生成，配"精妙度"评分
  （必然 × 唯一 × 惊异）。

- **[sop-pensieve](https://github.com/niuniuhaoyu/sop-pensieve)** —— 活的科研与工具 SOP
  知识库（"冥想盆"）：案例复现、DiD / 实证分析规范、参考文献核验、投稿前自查、AI 辅助编程
  核验。每完成一项任务，都沉淀出一条可复用的流程。

## 链接

- 🏫 澳门城市大学
- 📫 3522359513@qq.com

---

[English](README.md) | [简体中文](README_zh.md)
