# Sources — 第 12 章 2027 拐点：双瓶颈缓解的节奏与三个预警信号

## 一手来源

| 编号 | 来源 | URL / 文档 | 用于章节段落 |
|------|------|-----------|------------|
| S1 | TSMC 法说会 CoWoS 产能指引（2024-Q4 起每季更新） | https://investor.tsmc.com/ | 12.4 |
| S2 | SK Hynix FY25 IR Day + 季报（HBM4 时间表） | https://www.skhynix.com/eng/ir/ | 12.3 |
| S3 | Micron FY25-FY26 10-K / 10-Q（HBM4 时间表） | https://investors.micron.com/ | 12.3 |
| S4 | Samsung 半导体季报 + IR Day | https://www.samsung.com/global/ir/ | 12.3、12.7 |
| S5 | NVIDIA FY26 10-K + 季度指引（Blackwell 出货 + Hopper 残余） | https://investor.nvidia.com/ | 12.5 |
| S5a | NVIDIA FY26Q1 财报新闻稿（数据中心营收 $39.1B，FY26Q1 总营收 $44.1B） | https://nvidianews.nvidia.com/news/nvidia-announces-financial-results-for-first-quarter-fiscal-2026 (2025-05-28) | 12.1、12.4 |
| S5b | NVIDIA FY26Q4 + 全年财报新闻稿（FY26Q4 数据中心 $62.3B，FY26 全年数据中心 $193.7B，全年总营收 $215.938B） | https://nvidianews.nvidia.com/news/nvidia-announces-financial-results-for-fourth-quarter-and-fiscal-2026 (2026-02-25) | 12.1、12.4 |
| S5c | AWS / Azure / Google / Meta 2026 FY CapEx 指引（合计 $240-260B，YoY +40%） | 各家 2025-Q4 / 2026-Q1 财报法说会 | 12.1 |
| S6 | Anthropic-Google TPU 联合公告 / 博客 | Anthropic / Google 官方 2025 | 12.6 |
| S7 | AWS re:Invent 2025 主题演讲（Trainium2 / Project Rainier） | https://aws.amazon.com/events/reinvent/ | 12.6 |
| S8 | Meta MTIA 公开发布博客 + Hardware Days | https://ai.meta.com/blog/ | 12.6 |
| S9 | DeepSeek / Qwen / Mistral 关于推理优化的开源论文 | arXiv / GitHub | 12.6 |
| S10 | Epoch AI 训练 / 推理算力测算与公开数据库 | https://epoch.ai/ | 12.6 |

## 二手来源

| 编号 | 来源 | 用于段落 | 是否已回溯一手 | 备注 |
|------|------|---------|--------------|------|
| T1 | Silicon Data H100 Rental Index（每周更新） | 12.5、12.7 | 部分（指数口径） | 关键预警指标；2026-05 数据 spot $1.70-2.63/hr |
| T2 | Trendforce HBM / CoWoS 月度跟踪 | 12.3、12.4 | 部分 | — |
| T3 | SemiAnalysis 2027 拐点 / HBM4 / CoWoS 深度 + H100 1-year contract index | 全章 | 部分 | 与 TSMC / SK Hynix 一手交叉；2026-03 H100 1-year contract $2.35/hr |
| T4 | Dylan Patel 公开访谈与报告（Hopper 二手价 / Anthropic TPU 部署） | 12.5、12.6 | 部分 | 不作为唯一来源 |
| T5 | Morgan Stanley / Bernstein / Goldman Sachs 2027 紧缺缓解判断对照 | 12.2、12.7 | 部分 | 与本章反共识立场对照 |
| T6 | The Information / Tom's Hardware / CNBC 关于 Anthropic-Google / Anthropic-Broadcom 大单 | 12.6 | 部分 | Tom's Hardware 2026-04 引用 Mizuho 估算；CNBC 2026-04-06 |
| T7 | Reuters / KED Global / 韩国媒体关于 Samsung NVDA 认证状态 | 12.3、12.7 | 部分 | 与 Samsung 法说会交叉 |
| T8 | Compute Exchange / Hashrate Index / IntuitionLabs 关于 H100 used / refurbished 价格 | 12.5、12.7 | 部分（业内估算，无公开统一交易所） | 信号 2 基线监测来源 |
| T9 | Google Cloud Press Corner + Anthropic news 2025-10-23 / 2026-04-06 关于 TPU 大单 | 12.6 | 是（公司方公告）| Anthropic-Google 1M TPU + 1 GW（2026）+ 3.5 GW（2027 起）|
| T10 | StorageNewsletter / Tom's Hardware / TechPowerUp / Micron IR 关于 HBM4 量产 | 12.3 | 部分（公司方公告 + 媒体综合） | Micron HBM4 high-volume production 2026-03-17 NVIDIA GTC 2026 公告 |
| T11 | TrendForce 2026-01-26 / Digitimes 2025-12-26 关于 Samsung / SK Hynix HBM4 量产 | 12.3 | 部分 | TrendForce 原文："passed validation without any redesign"；11.7 Gb/s 超 10 Gb/s 规格；2026-02 启动 NVIDIA / AMD 出货 |
| T17 | CNBC 2026-04-20 关于 Amazon 对 Anthropic 追加 $25B 投资（叠加此前 $8B，累计承诺约 $33B） | 12.6 | 是（公司方公告 + 媒体） | https://www.cnbc.com/2026/04/20/amazon-invest-up-to-25-billion-in-anthropic-part-of-ai-infrastructure.html |
| T18 | TechCrunch / Bloomberg 2026-04-24 关于 Google 对 Anthropic 投资 $40B | 12.6 | 是（媒体报道 + 官方） | https://techcrunch.com/2026/04/24/google-to-invest-up-to-40b-in-anthropic-in-cash-and-compute/ |
| T19 | NVIDIA FY26Q4 earnings call transcript（Motley Fool 2026-02-25） + NVIDIA Developer Blog 关于 GB300 NVL72 vs Hopper 50x throughput/MW + 35x lower token cost | 12.5 | 是（公司方公告 + 一手） | https://www.fool.com/earnings/call-transcripts/2026/02/25/nvidia-nvda-q4-2026-earnings-call-transcript/; https://developer.nvidia.com/blog/scaling-token-factory-revenue-and-ai-efficiency-by-maximizing-performance-per-watt/ |
| T20 | Meta Q4 2025 earnings call transcript（Motley Fool 2026-01-28）— CFO Susan Li 引语 | 12.1 | 是（公司方公告） | https://www.fool.com/earnings/call-transcripts/2026/01/28/meta-meta-q4-2025-earnings-call-transcript/ |
| T21 | Counterpoint Research 全球 DRAM / HBM 市占（Samsung 2024 全年 HBM ~39-40%） | 12.3 | 部分 | https://counterpointresearch.com/en/insights/global-dram-and-hbm-market-share |
| T12 | Meta AI Blog 2026-03-11 + DCD 2026-03 关于 MTIA 4 代路线图 | 12.6 | 是（公司方公告） | MTIA 300 已量产；400/450/500 在 2026-2027 上市 |
| T13 | AWS re:Invent 2025 keynote + DCD 2025-11 关于 Project Rainier 500K Trainium2 集群 | 12.6 | 是（公司方公告） | Anthropic 训推两用 |
| T14 | FinancialContent / Tiger Brokers 关于 CoWoS 130K 月产能（2026 末）| 12.4 | 部分 | TSMC 法说会指引转引；Tiger Brokers 引用 127K，FinancialContent 引用 130K |
| T15 | TPU v6e / Trainium2 / MTIA perf/W 公开数据（业内 PFLOPS/MW 反推） | 12.6 | 部分 | Google Cloud 官方 + AWS re:Invent 2025 + Meta AI Blog 2026-03 公开性能指标交叉 |
| T16 | TrendForce × SemiAnalysis 综合 HBM4 量产月度估算 | 12.3 | 否（业内估算） | SK Hynix / Micron / Samsung 均未单独披露 HBM4 出货 |

## 已知数据缺口（按"业内估算 / 无法验证"标）

1. **HBM4 三家量产时间口径差异**：SK 法说会 vs Micron vs Samsung 之间 1-2 季差，**多源并列**。
2. **TSMC CoWoS 2026 末 130K+ 月产能**：TSMC 自己披露与 Trendforce / SemiAnalysis 估算口径不同，**多源并列**。
3. **Hopper 二手报价**：无公开市场，**Dylan Patel + 渠道 + Bernstein 多源估算**。
4. **Anthropic-Google TPU 合同细节（数量 / 期限 / 单价）**：仅公告总量，**业内估算 + 标无法验证**。
5. **Samsung HBM3e NVDA 认证最新状态**：时点敏感，**fact-check 时拉最新**。
6. **DeepSeek / Qwen 推理优化对算力需求弹性的具体影响**：学术 + 工程估算，**按区间表达**，主答辩留 ch13。

## 数据采集时点

- 最后一次更新：2026-05
- 财报数据截止：TSMC / SK Hynix / Micron / Samsung / NVDA 2026-Q1
- Silicon Data H100 Rental Index 截止：2026-05 最新一周
- Compute Exchange / Hashrate Index H100 used / refurbished 价格截止：2026-04
- Anthropic-Broadcom 公告时点：2026-04-06
- Amazon 追加 Anthropic $25B 投资公告时点：2026-04-20（累计承诺约 $33B）
- Google 追加 Anthropic $40B 投资公告时点：2026-04-24
- Micron / SK Hynix / Samsung HBM4 NVIDIA GTC 2026 公告时点：2026-03-17
- 全章 data_cutoff：2026-05

## 与其他章联动

- ch05 CoWoS / ch06 HBM 横截面 → 本章是横截面的"未来时序"
- ch11 双瓶颈物理 → 本章四股缓解力是 ch11 四因素分解的对偶
- ch13 杰文斯 + 训推三段 → 本章供给侧缓解 + ch13 需求侧弹性共同收束反共识 #4
- ch14 缓解之后 → 本章缓解之后引出 ch14 新硬约束
- ch29 周期定位 → 本章三个预警信号与 ch29 三个泡沫顶部预警指标在结构上同构，但定位不同（ch12 = 紧缺缓解侧 / ch29 = 资本周期顶部侧）
- ch31 12 议题答辩 → 本章三个预警 + 当章立此存照是 ch31 议题 3 五段式的输入
- ch32 五年之后 → 本章可证伪条件是 ch32 情景概率分布的修正机制基线
- 附录 D-2 可证伪条件操作手册 → 本章 falsification-watch.csv 是手册的一部分
