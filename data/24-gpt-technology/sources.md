# Sources — 第 24 章 算力作为通用目的技术：与蒸汽、电力、IT 的可比

> 占位文件。写正文时按 data-citation.md 规范补全。

## 一手来源（待补全）

| 编号 | 来源 | URL / 文档 | 用于章节段落 |
|------|------|-----------|------------|
| S1 | Bresnahan & Trajtenberg "General Purpose Technologies" | Journal of Econometrics 65 (1995) 83-108 | 24.1 三判据定义 |
| S2 | David "The Dynamo and the Computer" | American Economic Review 80 (1990) | 24.5 生产力悖论 |
| S3 | Crafts "Steam as a General Purpose Technology" | Economic Journal 114 (2004) | 24.2 蒸汽机扩散 |
| S4 | Devine "From Shafts to Wires: Historical Perspective on Electrification" | Journal of Economic History 1983 | 24.2 电力扩散 |
| S5 | BEA NIPA 历史 GDP / 投资序列 | https://www.bea.gov/itable | 24.2 / 24.4 |
| S6 | Hyperscaler 财报 CapEx（MSFT / GOOG / META / AMZN） | SEC EDGAR | 24.4 算力 CapEx 占 GDP |
| S7 | Stanford AI Index Report 2026 | https://aiindex.stanford.edu/ | 24.3 AI 渗透率 |
| S8 | NBER 美国生产率长序列 | https://www.nber.org/ | 24.5 TFP 数据 |
| S9 | BLS Multifactor Productivity（私营非农部门 TFP 长序列） | https://www.bls.gov/productivity/tables/ | 24.5 / 24.5 TFP 1995-2007 ≈ 1.4%；1973-1995 ≈ 0.3-0.5% |
| S10 | Smithsonian National Museum of American History "Generating Change" | https://americanhistory.si.edu/explore/exhibitions/american-enterprise/online/corporate-era/generating-change | 24.2 / 24.4 / 24.5 电气化 1899 < 5%、1919 ~50%、1929 ~75% 多源共识 |
| S11 | Cui, Demirer, Jaffe et al. "The Effects of Generative AI on High-Skilled Work" | SSRN 4945566（2024-09）；后续发表于 Management Science | 24.3 Microsoft 内部 4867 工程师 Copilot 实测：PR +26.1%、代码评审 +10.6% |
| S12 | US Census Bureau CPS Computer and Internet Use Supplement | https://www2.census.gov/programs-surveys/demo/tables/computer-internet/ | 24.4 美国家庭 PC 拥有率历史序列（1989 ≈ 15% / 1993 = 22.8% / 1997 = 35%；CPS 未每年做补充调查） |

## 二手来源（待补全）

| 编号 | 来源 | 用于段落 | 是否已回溯一手 |
|------|------|---------|--------------|
| T1 | Goldfarb & Tucker "Digital Economics" | 24.2 / 24.5 | 部分 |
| T2 | Brynjolfsson "The Productivity Paradox of Information Technology" (1993) | 24.5 | 否（经典文献） |
| T3 | McKinsey State of AI 2025 / 2026 | 24.3 渗透率 | 部分 |
| T4 | Epoch AI 单位算力价格序列 | 24.3 improvement potential | 部分（与 Silicon Data 交叉） |
| T5 | Carlota Perez "Technological Revolutions and Financial Capital" | 24.4 / 24.6 | 否（理论框架） |
| T6 | Allen "The British Industrial Revolution in Global Perspective" | 24.2 蒸汽时代 | 否 |

## 已知数据缺口（本章相关）

本章是宏观经济入口章，数据缺口主要在历史长序列的口径统一：

- **三轮历史 GPT 的 TFP 长序列**——不同国家、不同学者口径差异大，本章须明示选用 BEA / NIPA 美国口径
- **AI 跨行业渗透率**——主要来自企业自报问卷（McKinsey / Stanford AI Index），存在 self-report bias，必须标"自报口径"
- **「算力 OPEC」卡特尔行为评估**——卡特尔行为本身不可直接验证，只能通过价格 / 产能 / 客户绑定的代理指标推断
- **历史 GPT 的扩散速度口径**——蒸汽与电力的"普及"定义不一（动力源占比 / 行业渗透率 / 家庭普及），须明示选择
- **类比定位（2025 ≈ 蒸汽 1820 / 电力 1905 / IT 1985）**是作者类比性观察，非历史一一对应，须明示

## 数据采集时点

- 骨架创建时点：2026-05-27
- 全书 data_cutoff：2026-05
- 章节特定 data_cutoff：与全书一致；历史数据取学界标准版本，AI 渗透率数据取 2026 年最新报告
