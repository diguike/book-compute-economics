# Sources — 第 30 章 五种估值模板：详略主次明确（NVDA + CoreWeave 详）

> R2 修订（2026-05-29）：在原骨架基础上补全 8 条核心一手 / 关键二手来源，对齐 fact-check 结论。详细规范参见 `.claude/skills/book-writer/references/data-citation.md`。
> R3 修订（2026-05-29 fact-check 修复轮）：
> - S2 NVDA FY26 CapEx 由 $3.4B 修正为一手 $6.04B（FY26 Q4 新闻稿现金流量表 "Purchases related to property and equipment and intangible assets: $6,042 million"），CapEx/Revenue 由 1.6% 修正为 2.80%；
> - S7 Nebius Q1 2026 EBITDA margin 由 +28.5% 修正为集团 +32% / AI 业务 +45%（来源切换为 Q1 2026 6-K + earnings call transcript 一手），FY25 -27% 切换为 Nebius AI 业务全年 +$59M 转正 + 集团前 9 个月 -26.4% 时点细化；
> - S15 被投对象由 Nebius 修正为 CoreWeave（$87.20/share × 22.94M 股 = $2B，2026-01-26 披露，CNBC 一手）；
> - 新增 S18（NVIDIA $2B 投资 Nebius，2026-03-11）、S19（CoreWeave 流动负债拆分 current debt $3.7B / 总流动负债 $9.7B）、S20（Cisco / Lucent 历史 P/E 量级核算）。

## 一手来源

| 编号 | 来源 | URL / 文档 | 发布时点 | 用于章节段落 |
|------|------|-----------|---------|------------|
| S1 | NVIDIA FY26 Q4 财报新闻稿 "NVIDIA Announces Financial Results for Fourth Quarter and Fiscal 2026" | https://nvidianews.nvidia.com/news/nvidia-announces-financial-results-for-fourth-quarter-and-fiscal-2026 | 2026-02-25 | §30.2（NVDA 营收 $215.9B / 数据中心 $193.7B / GAAP 毛利率 71.1% / 净利 $120.1B / 稀释 EPS $4.90 / Q4 $68.1B / Q4 GAAP 毛利率 75.0% / FY27Q1 指引 $78.0B±2% / FY26 股东返还 $41.1B / 剩余回购授权 $58.5B） |
| S2 | NVIDIA FY26 10-K | SEC EDGAR（accession number 待 fact-check 阶段 2026-03 末提交后回填） | 2026-03（预计） | §30.2 / §30.3 设备商主模板（CapEx 一手 $6.04B / Revenue 2.80%—— 来自 FY26 Q4 新闻稿现金流量表 "Purchases related to property and equipment and intangible assets: $6,042 million"、客户集中度 Risk Factors 年报口径 Customer A 22% + Customer B 14% = 36%、股东返还明细） |
| S3 | NVIDIA 历史 10-K（FY24 / FY25） Risk Factors 客户集中度披露 | SEC EDGAR | 2024 / 2025 | §30.3.2 客户集中度 CR5 历史路径 |
| S4 | CoreWeave Q3 2025 8-K + 10-Q | SEC EDGAR（CIK 0001769628）https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0001769628&type=10-Q | 2025-11 | §30.4 / §30.10 GPU 云主模板（营收、Adj EBITDA $838M、maintenance CapEx、RPO $55.6B、总债 $14B、利息覆盖率） |
| S5 | CoreWeave S-1 + FY24 10-K | SEC EDGAR | 2025-03（S-1） / 2025（10-K） | §30.4 GPU 云模板（折旧政策 6 年、客户集中度 CR1 60% MSFT 2024、CapEx 强度） |
| S6 | CoreWeave 2026-02 公告（Meta 合约 ABS $8.5B） | CoreWeave Press Release（URL 待 fact-check 阶段补） | 2026-02 | §30.4.8 ABS / vendor financing |
| S7 | Nebius Group Q4 + FY2025 业绩公告 + Q1 2026 业绩公告（含 6-K） | businesswire 2026-02-12 + Nebius IR Q1 2026 6-K + Q1 2026 earnings call transcript | 2026-02 (FY25) / 2026-05 (Q1 2026) | §30.4.7 横截面（Nebius AI 业务 FY2025 全年 adjusted EBITDA +$59M 转正 / 集团前 9 个月 -26.4%；Q1 2026 集团 +32% / AI 业务 +45%）；URL https://www.businesswire.com/news/home/20260212534404/en/Nebius-Reports-Fourth-Quarter-and-Full-Year-2025-Financial-Results、Q1 2026 6-K SEC EDGAR https://www.sec.gov/Archives/edgar/data/0001513845/000110465926059872/tm2614392d1_ex99-2.htm |
| S8 | Cisco FY2000 10-K | SEC EDGAR https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0000858877&type=10-K | 2000-10 | §30.8 / §30.10 历史对照（Cisco FY2000 营收 $18.9B、市值 $555B 顶峰、远期 P/E ~130x） |
| S9 | Lucent Technologies 1999-2000 10-K | SEC EDGAR | 1999-2000 | §30.8 历史对照（Lucent CLEC 客户、vendor financing 规模） |
| S10 | TSMC FY25 6-K + 2026 Capital Markets Day | https://investor.tsmc.com/ | 2026-04 | §30.5（TSMC NT$2,894B / 毛利率 59.9% / HPC 51% / 先进制程 73%） |
| S11 | SK Hynix FY25 公告 | SK Hynix IR | 2026-01 | §30.5（KRW 66.2T / 营业利润率 49% / 净现金转正） |
| S12 | Microsoft FY25 10-K + GOOGL FY24 10-K | SEC EDGAR | 2025-07 / 2025-02 | §30.6 折旧政策附注（4→6 年变更对 EPS 影响） |
| S13 | Digital Realty / Equinix FY25 10-K | SEC EDGAR | 2026-02 | §30.7 FFO / AFFO / Power booked / 利用率 |
| S14 | Michael Burry — Scion Asset Management Q3 2025 13F | SEC EDGAR https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0001649339&type=13F | 2025-11-14 | §30.4.6（NVDA / PLTR 看跌头寸披露） |
| S15 | NVIDIA 战略投资 CoreWeave $2B（2026-01-26 披露，$87.20/share × 22.94M 股 ≈ $2,000M） | CNBC 2026-01-26 https://www.cnbc.com/2026/01/26/3coreweave-nvidia-stock-ai-data-centers.html + Bloomberg 综合 + CoreWeave 8-K 2026-01 | 2026-01-26 | §30.4 / §30.10.1（CoreWeave 多头论点：NVIDIA 既是供应商又是战略股东） |
| S16 | SemiAnalysis HBM 跟踪报告（HBM3e / HBM4 stack 价格、CoWoS 产能） | semianalysis.com（付费内容，URL 待 fact-check 阶段补） | 2026-Q1 | §30.2.3 bull case HBM4 stack 价格 $400-500 + ch04 / ch06 交叉 |
| S17 | NVIDIA FY26 Q2 10-Q + 8-K 客户集中度披露 | SEC EDGAR https://www.sec.gov/Archives/edgar/data/0001045810/000104581025000209/nvda-20250727.htm | 2025-08 | §30.3.2 季报口径 Customer A 23% + Customer B 16% = 39%（单季）/ H1 35% / Top 6 entities 85%；年报口径见 S2（22% + 14% = 36%） |
| S18 | NVIDIA 战略投资 Nebius $2B（2026-03-11 披露） | Nebius IR + 媒体综合（URL 待 fact-check 阶段补） | 2026-03-11 | §30.4.7 横截面对照（Nebius 资本结构：NVIDIA $2B 投资 + 净现金） |
| S19 | CoreWeave Q3 2025 10-Q 流动负债拆分 | SEC EDGAR + levelheadedinvesting.com Q3 2025 10-Q 分析 https://www.levelheadedinvesting.com/p/coreweave-crwv-q3-2025-when-the-interest-bill-becomes-the-story | 2025-11 | §30.10.2 短期债务 current debt ~$3.7B 内含于流动负债合计 $9.7B |
| S20 | Cisco 1999-2000 trailing / forward P/E 量级 + Lucent 1999-12 P/E 独立核算 | ycharts 付费数据（量级参考）+ Cisco FY99/FY00 10-K split-adj EPS（$0.29 / $0.36）+ RBC PA Lucent In Depth Report https://www.rbcpa.com/commentary-archive/lucent-in-depth-report/（"F1999: 1.12 [EPS]; Lucent was priced at 84 1/4 during December of 1999"）+ CNBC 2025-12-10 Cisco $80.06 split-adjusted record + companiesmarketcap.com Lucent peak $258B | 1999-12 / 2000-03 / 2025-12 | §30.8.1 + §30.8.2 历史对照 |

## 二手来源

| 编号 | 来源 | 用于段落 | 是否已回溯一手 |
|------|------|---------|--------------|
| T1 | Damodaran 估值数据库（行业 multiples、历史 P/E、半导体估值分位） pages.stern.nyu.edu/~adamodar/ | §30.2.6 / §30.8.1 NVDA 历史远期 P/E、Cisco 远期 P/E ~130x 峰值、半导体寡头中位 | 部分（学术数据 + 数据库时间序列） |
| T2 | Bloomberg / Refinitiv / Visible Alpha 卖方共识（机构：摩根士丹利 / 高盛 / Mizuho / Bernstein / Citi；2026-05 拉取） | §30.2.6 / §30.8.1 / §30.9 / §30.10 远期 P/E 共识 / EV/EBITDA 共识 / Mag7 PEG | 部分（机构数据，单点价格回溯到当日盘后） |
| T3 | Sequoia "AI's $600B Question" — David Cahn https://www.sequoiacap.com/article/ais-600b-question/ | §30.2 / §30.4 / §30.9 需求侧基线缺口 | 否（行业评论） |
| T4 | StockAnalysis Nebius 综合摘要 https://stockanalysis.com/stocks/nbis/financials/ | §30.4.7 Nebius EBITDA margin 转正口径 | 已二次回溯 Nebius IR |
| T5 | Pitchbook 非上市估值数据 | §30.4.7 Crusoe / Lambda 估值横截面 | 部分 |
| T6 | NAREIT REIT 行业数据 | §30.7 cap rate / FFO 行业基线 | 部分 |
| T7 | Soros 《The Alchemy of Finance》 | §30.3.1 反身性框架 | 否（理论） |
| T8 | Popper 《The Logic of Scientific Discovery》 | §30.11 可证伪 | 否（理论） |
| T9 | SemiAnalysis TCO 模型 | §30.5 模板 3 | 部分（付费 + 时效） |
| T10 | Yahoo Finance NVDA 日线 / 市值 | §30.2 当前股价 + 市值 $3.5-4T 区间 | 一手（盘面数据） |
| T11 | Cassandra Unchained（Michael Burry 公开评论账号） | §30.4.6 Burry 折旧期论点 | 与 13F（S14）交叉 |
| T12 | 二手 GPU 市场报价综合（H100 2025 年市价 ~$15K） | §30.4.5 清算价值估算 | 否（行业经验） |
| T13 | NVIDIA FY26 Q4 财报会逐字稿（sovereign AI 评论 + Rubin 产品路线图） | NVIDIA IR 综合 + 卖方综合（URL 待 fact-check 阶段补） | 2026-02 | §30.2.3 bull case sovereign AI 增量叙事 + 中东 / 印度 / 欧洲 AI 主权计划 |

## 已知数据缺口（本章相关）

- **TSMC CoWoS 单独毛利率**——公司不披露，业内估算 50-65%，本章作为敏感性参数处理
- **HBM 出厂价**——业内估算 $200-300/stack，作为模板 3 敏感性参数
- **NVDA 实际 BOM**——业内估算 $3,000-3,500，作为模板 1 敏感性参数
- **非上市 GPU 云财务**（Lambda / Crusoe）披露有限，模板移植到这些公司须明示假设
- **OpenAI / Anthropic 与 CoreWeave 协议现金流分布**——总额 $11.9B + 期限披露，按月 / 按季现金流不披露
- **AI ABS / vendor financing 总规模**——缺集中统计
- **历史 Cisco / Lucent 估值分位的会计调整**——GAAP 1999 vs 现在差异大，须重新调整
- **AI infra 折旧期变更影响**——hyperscaler 各家口径不同（MSFT / GOOG / META），须明示原文披露
- **Nebius Q1 2026 营收 / EBITDA 拆分**——二手 StockAnalysis 综合，待 Nebius 季报原文进一步交叉

## 数据采集时点

- 骨架创建时点：2026-05-27
- R2 修订时点：2026-05-29
- R3 fact-check 修复时点：2026-05-29（CapEx / Nebius margin / S15 被投对象修正 + DCF 重算）
- 全书 data_cutoff：2026-05
- 章节特定 data_cutoff：与全书一致；NVDA / CoreWeave 取截至 2026-Q1 财报披露完毕后的最新版；hyperscaler 折旧政策取 2026 年版 10-K 附注
