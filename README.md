# ETAS-GMprob 地震動機率評估 / Ground-Shaking Probability Assessment

**🌐 Live dashboard:** [中文版](https://mchsieh.github.io/etas-gmprob-dashboard/)｜[English](https://mchsieh.github.io/etas-gmprob-dashboard/en.html)

台灣地區地震動機率之每小時自動化評估，由國立中央大學 **E-DREaM 地震災害風險評估與管理研究中心** 產製。

Hourly automated probabilistic ground-shaking assessment for Taiwan, produced by the **Earthquake-Disaster & Risk Evaluation and Management (E-DREaM) Center, National Central University**.

## 方法 / Method

ETAS 模型（中央氣象署 M ≥ 3 地震目錄，每小時更新）→ 條件強度 → 地震活動模擬（1,000 組虛擬地震目錄）→ 地震動模型（GMM）→ 各站點震度超越機率。

ETAS model (CWA catalog, M ≥ 3, hourly updates) → conditional intensity → seismicity simulation (1,000 synthetic catalogs) → ground-motion model (GMM) → site-specific intensity exceedance probabilities.

## 引用 / Reference

Hsieh, M.-C., et al. (2024). Toward Real-Time Ground-Shaking-Intensity Forecasting Using ETAS and GMM: Insights from the Analysis of the 2022 Taitung Earthquake Sequence. *Seismological Research Letters*, 95(6). [Link](https://pubs.geoscienceworld.org/ssa/srl/article-abstract/95/6/3264/645862/)

## 聲明 / Disclaimer

本頁內容為研究性質之機率評估產品，並非對特定地震的預測，亦非官方警報；正式地震資訊請以中央氣象署（CWA）發布為準。

This is a research-grade probabilistic assessment — not a prediction of specific earthquakes and not an official warning. For authoritative earthquake information, refer to the Central Weather Administration (CWA), Taiwan.

---

*This repository hosts the static dashboard only; it is updated automatically every hour.*
