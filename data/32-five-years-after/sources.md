# Sources — 第 32 章 五年之后：电力、HBM、客户集中度三不变量

> 占位文件。全书收尾章，段落级 disclaimer，作者主观概率分布 + 修正机制是本章方法论核心。写正文时按 data-citation.md 规范补全。

## 一手来源（待补全）

| 编号 | 来源 | URL / 文档 | 用于章节段落 |
|------|------|-----------|------------|
| S1 | Pierre Wack "Scenarios: Uncharted Waters Ahead" / "Scenarios: Shooting the Rapids" | Harvard Business Review 1985 | 32.1 方法论 |
| S2 | LBNL "United States Data Center Energy Usage Report" 2024 + 2030 展望 | https://www.energy.gov/eere/buildings/articles/lbnl-data-center-report-2024 | 32.8 / 32.9 不变量 1 |
| S3 | IEA "Energy and AI" 2025 + IEA Electricity Outlook | https://www.iea.org/ | 32.8 / 32.9 |
| S4 | TSMC Capital Markets Day 2025 + CoWoS 长期规划 | TSMC IR | 32.8 不变量 2 |
| S5 | SK Hynix + Samsung HBM 长期规划 | 各 IR | 32.8 不变量 2 |
| S6 | NVDA 10-K + CoreWeave 10-K（客户集中度 5 年敏感性） | SEC EDGAR | 32.8 不变量 3 |
| S7 | Lloyd's Market Reports（台海航运保险） | https://www.lloyds.com/ | 32.5 台海指标 1 |
| S8 | TSMC ADR / TPE 双重上市数据 | Bloomberg / Refinitiv | 32.5 台海指标 2 |
| S9 | TSM 期权偏度数据 | Bloomberg / Cboe / 期权数据 | 32.5 台海指标 3 |
| S10 | 4 大 hyperscaler FY26 CapEx 指引 + 长期 CapEx 框架 | 各 10-K + 业绩会 | 32.2 / 32.3 |
| S11 | DeepSeek-V3 训练论文 + 业内拆解 | DeepSeek arXiv + 多源 | 32.7 |
| S12 | Epoch AI 长期趋势分析 | https://epoch.ai/ | 32.2 / 32.7 |

## 二手来源（待补全）

| 编号 | 来源 | 用于段落 | 是否已回溯一手 |
|------|------|---------|--------------|
| T1 | Peter Schwartz "The Art of the Long View" | 32.1 情景规划方法论 | 否（专著） |
| T2 | Knight "Risk, Uncertainty and Profit" 1921 | 32.1 风险 vs 不确定性 | 否（理论） |
| T3 | Taleb "Antifragile" / "The Black Swan" | 32.1 凸性脆弱性 | 否（理论） |
| T4 | Crafts 蒸汽机经济史长序列（电气化情景对照） | 32.6 情景 C | 否（学术） |
| T5 | Richmond Fed / Brookings telecom 系列 | 32.4 情景 B | 部分 |
| T6 | EIA 页岩油历史回顾 | 32.4 情景 B 次要参照 | 否 |
| T7 | Goldman Sachs / Morgan Stanley AI 长期展望 | 32.3 / 32.7 | 部分（卖方） |

## 已知数据缺口（本章相关）

- **五年延伸数据**——CapEx / 电力 / 算力价格 / 终端收入 4 维度的 2026-2031 延伸均为外推，须明示假设
- **HBM + CoWoS 2027-2030 产能预测**——业内估算 + 产能扩张计划，须明示口径
- **台海航运保险费率（war risk premium）**——劳合社披露按年 + 按航线，可能有口径调整
- **TSMC ADR vs TPE 价差**——汇率与流动性影响大，须按 5 日 / 20 日 MA 平滑后比较
- **TSM 期权偏度 skew**——美股期权数据可获取，但偏度定义口径多（put/call IV 比 / 25-delta 偏度），须明示
- **作者主观概率分布的"理由"**——无法被 fact-check，只能通过修正机制让读者后续验证
- **DeepSeek 训练成本下降幅度**——业内拆解差异大（10x / 20x / 95% 等），须明示口径
- **NVDA / CoreWeave 客户集中度 5 年敏感性**——基于自建模型 + 历史敏感性，须明示假设

## 数据采集时点

- 骨架创建时点：2026-05-27
- 全书 data_cutoff：2026-05
- 章节特定 data_cutoff：与全书一致；台海风险指标取截至 2026-05 月度数据；hyperscaler / NVDA / CoreWeave 数据复用 ch29 / ch30；情景规划方法论文献无时点要求
