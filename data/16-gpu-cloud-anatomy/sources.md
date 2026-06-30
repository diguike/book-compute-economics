# Sources — 第 16 章 GPU 云解剖

> 已对正文使用到的数据点逐条核对。本章 fact-check 重点：CoreWeave 8-K / 10-Q 数字、客户集中度披露、Burry 公开论点原文。

## 一手来源

| 编号 | 来源 | URL / 文档 | 用于章节段落 |
|------|------|-----------|------------|
| S1 | CoreWeave S-1 (2025-03-03 提交) | SEC EDGAR 1769628 (https://www.sec.gov/Archives/edgar/data/1769628/000119312525044231/d899798ds1.htm) | §1.3 客户集中度、§2.1、§2.2 折旧政策、§4.1 客户集中度数据 |
| S2 | CoreWeave Q1 2025 8-K | https://www.sec.gov/Archives/edgar/data/0001769628/000176962825000010/coreweave1q25earningspress.htm | §1 营收时序对照 |
| S3 | CoreWeave Q2 2025 8-K | https://www.sec.gov/Archives/edgar/data/0001769628/000176962825000039/coreweave2q25earningspress.htm | §1 营收时序对照 |
| S4 | CoreWeave Q3 2025 8-K（2025-11-10）| https://www.sec.gov/Archives/edgar/data/0001769628/000176962825000059/coreweave3q25earningspress.htm | §1 全节核心数据 |
| S5 | CoreWeave Q3 2025 10-Q | https://www.sec.gov/Archives/edgar/data/0001769628/000176962825000062/crwv-20250930.htm | §1 利息支出、净亏损 |
| S6 | CoreWeave Q3'25 Earnings Presentation | https://s205.q4cdn.com/133937190/files/doc_financials/2025/q3/Earnings-Deck-2025-Q3.pdf | §1 Revenue Backlog 拆分 |
| S7 | CoreWeave 2025-09-25 8-K — OpenAI $6.5B 扩约 | https://investors.coreweave.com/news/news-details/2025/CoreWeave-Expands-Agreement-with-OpenAI-by-up-to-6-5B/default.aspx | §1.3、§4 OpenAI 合同 |
| S7.5 | CoreWeave-OpenAI 2025-05 扩约 $4B（公司未单独发 8-K）| 二手已确认：Bloomberg 2025-05-15 "OpenAI Expands CoreWeave Tie-Up With New $4 Billion Cloud Deal"（bloomberg.com/news/articles/2025-05-15/openai-expands-coreweave-tie-up-with-new-4-billion-cloud-deal，付费墙）+ The Information / 多家媒体 2025-05 综合 + CoreWeave 投资者关系页；fact-check 阶段确认日期 / 金额，原文 quote 受付费墙限制 | §1.3 OpenAI 合同三批 |
| S8 | CoreWeave 2026-01-23 8-K — NVIDIA $2B 认购 | SEC 文档 ID 000176962826000044 | §1.3 NVIDIA 三角关系 |
| S9 | CoreWeave Q1 2026 8-K | SEC 文档 ID 000176962826000220 | §4.1 RPO $99.4B 数据 |
| S10 | CoreWeave 2026-04 senior notes 公告（$1.75B + $1B 9.75% 2031 + $3.5B conv 1.75% 2032，合计 $6.25B）| https://www.lw.com/en/news/latham-advises-on-coreweave-debt-offerings —— 律师事务所（Latham & Watkins）授权公告，公司方一手；对应一手 8-K / 144A 备案文件待 fact-check 阶段 WebFetch 补 | §3.4 利率压力分析 |
| S11 | Nebius Q1 2026 业绩公告（businesswire）| https://www.businesswire.com/news/home/20260513568820/en/Nebius-reports-first-quarter-2026-financial-results | §6.2 Nebius 数据 |
| S12 | Nebius Q1 2026 Shareholder Letter | https://assets.nebius.com/assets/aa1bc2e6-df83-40cd-a6a2-95e7cda3d16c/Nebius%20SHL_Q1%202026.pdf | §6.2 一次性收益拆分 |
| S13 | Nebius Q1 2026 6-K | https://www.sec.gov/Archives/edgar/data/0001513845/000110465926059872/tm2614392d1_ex99-2.htm | §6.1 一手对照 |
| S14 | Crusoe Stargate Abilene $11.6B 融资公告 | Yahoo Finance 综合（CoreWeave / Crusoe / Blue Owl + Primary Digital Infrastructure，2025）| §6.2 Crusoe 模型 |
| S15 | Crusoe D 轮 $600M 融资（2024-12）| 媒体披露综合 | §6.1 Crusoe 估值 |
| S16 | Lambda D 轮 $480M（2025-02）| Lambda 官方博客 lambda.ai/blog（$480M D 轮公告，未披露估值）+ 媒体披露综合（估值分歧：PitchBook 报 ~$2.5B、techfundingnews 等媒体报 ~$4B）| §6.1 Lambda 估值 |
| S17 | Burry / Cassandra Unchained X post（2025-11-11）| https://x.com/michaeljburry/status/1987918650104283372 | §5.1 Burry 原文 |
| S18 | CoreWeave SEC DRSLTR（letter to SEC，公开回复）| https://www.sec.gov/Archives/edgar/data/0001769628/000095012325000509/filename1.htm | §4.1 Microsoft RPO < 50% 披露 |
| S19 | Meta 2025 Q1 财报折旧期延长披露 + 2024 10-K | SEC EDGAR Meta CIK 1326801 | §3.1 折旧期对照 |
| S20 | Amazon FY24 10-K（AWS 5 年服务器折旧）| SEC EDGAR Amazon | §3.1 折旧期对照 |
| S21 | Microsoft FY24 10-K（Azure 6 年折旧）| SEC EDGAR Microsoft | §3.1 折旧期对照 |
| S22 | Alphabet 2024 10-K | SEC EDGAR Alphabet | §3.1 折旧期对照 |
| S23 | Oracle FY24 10-K | SEC EDGAR Oracle | §3.1 折旧期对照 |
| S24 | NVIDIA Blackwell whitepaper（2024-03）| NVIDIA 官网 | §3.2、§3.4 B200 / B300 量产节奏 |
| S25 | CNBC 2026-01-19 报道 "OpenAI to focus on 'practical adoption' in 2026, says finance chief Sarah Friar" | https://www.cnbc.com/2026/01/19/openai-to-focus-on-practical-adoption-in-2026-says-finance-chief-sarah-friar.html | §4.2 OpenAI 2025 ARR ~$20B（CFO Sarah Friar 2026-01 官方口径） |
| S26 | OpenAI 官方 blog 2026-01 "A business that scales with the value of intelligence" | https://openai.com/index/a-business-that-scales-with-the-value-of-intelligence/ | §4.2 OpenAI 2025 ARR ~$20B 一手披露 |
| S27 | Nebius Q1 2026 Shareholder Letter（2026-05-13）—— **2026 CapEx 指引 $20-25B** | https://assets.nebius.com/assets/aa1bc2e6-df83-40cd-a6a2-95e7cda3d16c/Nebius%20SHL_Q1%202026.pdf | §7.3 Nebius 稳态测算 CapEx 指引（上调自 $16-20B，主要用于 2027 产能投建 + 宾州 1.2 GW 新建数据中心） |
| S28 | Nebius Q1 2026 6-K（FY2026）| https://www.sec.gov/Archives/edgar/data/0001513845/000110465926059872/tm2614392d1_ex99-1.htm | §7.3 一手对照 CapEx 指引 / Q1 财务 |

## 二手来源

| 编号 | 来源 | 用于段落 | 是否已回溯一手 |
|------|------|---------|--------------|
| T1 | Silicon Data H100 Rental Price Over Time（2025-12）| §3.2 H100 二手价、§3.4 长期合约价 | Silicon Data 自有数据库，部分回溯一手 |
| T2 | Silicon Data H100 Price Spike（2026-01）| §3.4 长期合约价反弹 | Silicon Data 自有数据库 |
| T3 | DatacenterDynamics 2025-11-10 CoreWeave Q3 综合 | §1.2 债务结构、CapEx 指引 | 综合 8-K，一手已对照 |
| T4 | Fortune 2025-11-10 CoreWeave Q3 综合 | §1.4 综合判断 | 综合 8-K |
| T5 | CNBC 2025-11-11 Burry 攻击报道 | §5.1 Burry put 仓位 | 综合 SEC 13F |
| T6 | CNBC 2025-11-14 GPU 折旧争议综合 | §3.2、§5.3 公司方反驳 | 综合公司方表态 |
| T7 | parameter.io 2025-11 Burry $176B 数据 | §5.1 量化数字 | 来自 Burry Substack 综合 |
| T8 | Chip Stock Investor 2025-11 Meta 折旧综合 | §3.1 Meta 折旧变化 | 综合 META 10-K |
| T9 | theCUBE Research 298 集 GPU Depreciation（2025）| §3.2 GPU Value Cascade、§3.1 折旧期对照 | 综合 hyperscaler 10-K |
| T10 | Bizety 2025-09-23 CoreWeave vs Nebius 折旧 | §3.1 折旧期对照 | 综合 S-1 + Nebius IR |
| T11 | Mizuho 2025 neocloud 覆盖 | §6.3 估值倍数 | 卖方研报 |
| T12 | Morgan Stanley 2025 GPU 云覆盖 | §6.3 估值倍数 | 卖方研报 |
| T13 | MLQ.ai 2025-11 CoreWeave 综合 | §1.3 2026 营收指引 | 综合 8-K |
| T14 | tech-insider.org 2026-01 H100 二手价 | §3.2 H100 二手价时序 | 综合 Silicon Data + Compute Exchange |
| T15 | Compute Exchange 2026 H100 价格指南 | §3.2 H100 二手价时序 | 二手平台数据 |
| T16 | introl.com 2025-12 GPU 价格 collapse | §3.2 H100 二手价时序 | 综合多源 |
| T17 | BigGo Finance Nebius Q1 2026 | §7.3 Nebius CapEx 数字（已弃用，回溯到一手 S27/S28）| 综合 Nebius Q1 业绩 |
| T18 | aicerts.ai 2025-11 Cassandra Unchained | §5.1 Burry Substack 主张 | 综合 Burry Substack |

## 已知数据缺口（本章相关）

- **缺口 #7** CoreWeave 与 OpenAI 协议的年度现金流分布——CoreWeave 与 OpenAI 都未公开年度现金流分布；业内估算 5 年合同年度现金流分布在 $2-7B 不等（取决于 OpenAI 算力消费曲线），明确标注"业内估算"
- **CoreWeave / Nebius 真实利用率**——招股书 / 8-K 不披露真实利用率，业内估算 80-92% 区间，正文 §3.3 三维矩阵中以 75% / 85% / 95% 三档处理
- **H100 二手价**——交易高度分散，正文 §3.2 用"业内估算 + 区间"处理（区间 ±20%）
- **CoreWeave SG&A 行级别拆分**——8-K 不单独披露，§1.1 表中"业内估算自一手数据"两行按 Revenue + 直接成本占比反推，估算区间 ±5%
- **Burry 持仓规模**——13F 披露 NVDA put 名义 $187M、Palantir put 名义 $912M（2025-09-30），但 13F 不强制披露行权价 / 到期日 / 实际权利金敞口；正文 §5.2 已明确"名义价值有误导"
- **CoreWeave DDTL（delayed-draw term loan）加权利率**——公司不单独披露；正文 §1.2 采用综合利率 8.9%（季度利息 $310M / 期末债务 $14B 年化反推）
- **Crusoe / Lambda 财务**——未上市，所有数据为间接综合，正文 §6.1 已标"业内估算"
- **Nebius Q1 2026 净利润 $621M 拆分**——公司披露 majority 来自所持 ClickHouse / Avride / Toloka 重估，但具体每项金额未公开；正文 §6.2 已标"主要来自 ... 非现金重估"

## 数据采集时点

- 骨架创建时点：2026-05-28
- 全书 data_cutoff：2026-05
- 章节特定 data_cutoff：与全书一致（CoreWeave Q3 2025 8-K + Q1 2026 8-K + Nebius Q1 2026 业绩为最新一期）
- 本次正文写作时点：2026-05-28
- 主要 WebFetch 验证轮次：2026-05-28（共 18 个公开网址 + 7 次 WebSearch 关键词检索）

## 模型版本控制

- `coreweave-dcf.xlsx`（pending）与 ch30 `gpu-cloud-template.xlsx` 共用 DCF 引擎但输出不同——本章输出"稳态盈利可能区间"（§7），ch30 输出"完整 DCF 估值"
- §3.3 三维敏感矩阵的 12 个单元格已经在本章正文给出，对应 `depreciation-sensitivity.csv` 数据文件，由 fact-check 子命令在事实关验证

## fact-check 优先级

写作完成后转 fact-check 阶段时，按以下优先级核验：

1. **P0（必须 100% 核验）**：CoreWeave Q3 2025 8-K / 10-Q 所有数字（§1.1、§1.2 表格）、Microsoft 62% 营收占比（§2.1、§4.1）、Burry X post 原文 + Substack $176B 数据（§5.1）
2. **P1（高优先级）**：Nebius Q1 2026 数字（§6）、OpenAI 合同三批累计 $22.4B（§1.3）、Meta / Amazon / Microsoft / Google / Oracle 折旧期（§3.1）
3. **P2（中优先级）**：H100 二手价时序、Silicon Data 数据、§3.3 敏感矩阵的单卡 economics 假设
4. **P3（低优先级，已明确"业内估算"）**：Crusoe / Lambda 数据、客户集中度逐年变化、DDTL 利率反推

## 时效更新补充来源（2026-06-26）

- CoreWeave Q1 2026（2026-05-07 披露）：营收 \$2.078B（+112% YoY）、revenue backlog \$99.4B、净亏损 \$740M、债务 \$24.9B、capex \$7.695B、2026 全年指引 \$12-13B。来源：CoreWeave IR / SEC 8-K、AlphaStreet。截至 2026-06-25 市值约 \$53.9B（股价 \$98.76）。来源：Yahoo Finance、Capital.com。
