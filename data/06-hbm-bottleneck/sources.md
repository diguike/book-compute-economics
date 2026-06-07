# Sources — 第 06 章 HBM：单卡最贵部件，反共识主战场

最后更新：2026-05-29（fact-check 修复二轮）；数据采集 cutoff：2026-05。

## 一手来源

| 编号 | 来源 | URL | 用于章节段落 |
|------|------|-----|------------|
| S1 | SK Hynix FY2025 Financial Results 新闻稿（2026-01-28 发布） | https://news.skhynix.com/sk-hynix-announces-fy25-financial-results/ | 5.x SK Hynix 财务画像；FY25 营收 97.15 万亿 KRW、营业利润 47.21 万亿 KRW、营业利润率 49%；HBM 营收 YoY 翻倍；HBM4 量产准备 |
| S2 | SK Hynix HBM4 / TSMC 合作公告（2025-04-23，TSMC NA Tech Symposium） | https://news.skhynix.com/tsmc-2025-technology-symposium-sk-hynix-showcases-hbm4/ | 6.x HBM4 base die TSMC 合作；12-Hi HBM4 > 2 TB/s |
| S3 | Micron Q1 FY2026 业绩（2025-09 财季）— Futurum 转 Micron 新闻稿 | https://futurumgroup.com/insights/micron-technology-q1-fy-2026-sets-records-strong-q2-outlook/ | 5.x Micron 财务画像：Q1 FY26 营收 $13.6B、Cloud Memory BU $5.3B、HBM 全年售罄、HBM4 2026 Q2 量产 |
| S4 | BIS Federal Register 2024-12-05 "Foreign-Produced Direct Product Rule…" 终稿 | https://www.federalregister.gov/documents/2024/12/05/2024-28270/foreign-produced-direct-product-rule-additions-and-refinements-to-controls-for-advanced-computing | 8.x HBM 对华出口管制；2 GB/s/mm² 带宽密度阈值；ECCN 3A090.c；2024-12-02 生效，2024-12-31 HBM 合规截止 |
| S5 | WilmerHale BIS 出口管制解读（2024-12-06） | https://www.wilmerhale.com/en/insights/client-alerts/20241206-bis-issues-sweeping-additional-restrictions-on-semiconductors-and-advanced-computing-entity-list-designations | 8.x License Exception HBM；FDP 规则覆盖 |
| S6 | NVIDIA FY26 财报新闻稿（2026-02-25） | https://nvidianews.nvidia.com | 1.x H100 整卡售价、单价相关基准 |

## 二手来源（已交叉验证 / 已标机构 + 时点）

| 编号 | 来源 | URL | 用于段落 | 验证状态 |
|------|------|------|---------|--------|
| T1 | Silicon Analysts HBM Pricing Database（2026-04 snapshot） | https://siliconanalysts.com/data/hbm-pricing | 4.x HBM 价格曲线表 HBM2e/HBM3/HBM3E/HBM4 单价 | 业内估算，方法论披露 |
| T2 | Silicon Analysts AI Chip Costs Database（2026-04） | https://siliconanalysts.com/data/ai-chip-costs | 1.x H100/B200/GB200 BOM 拆解 HBM vs GPU die vs CoWoS | 业内估算 |
| T3 | TrendForce 2024-05-06 HBM 价格预测 | https://www.trendforce.com/presscenter/news/20240506-12125.html | 4.x HBM 占 DRAM 总价值比例 / 容量比例 | 一手转载（TrendForce 自有） |
| T4 | TrendForce 2025-12-24 HBM3E 2026 涨价 20% 报道 | https://www.trendforce.com/news/2025/12/24/news-samsung-sk-hynix-reportedly-plan-20-hbm3e-price-hike-for-2026-as-nvidia-h200-asic-demand-rises/ | 4.x 2026 HBM3E 价格、需求结构、HBM4/HBM3E 营收占比预测 | 一手转载 |
| T5 | KED Global Samsung NVIDIA 12-Hi HBM3E 认证通过报道（2025-09-19） | https://www.kedglobal.com/korean-chipmakers/newsView/ked202509190008 | 3.x Samsung HBM3E 认证 18 个月历程 | 一手转载（Jun Young-hyun 受访） |
| T6 | TrendForce 2025-10-21 HBM 三家市占 / Samsung HBM4 SEDEX 首发 | https://www.trendforce.com/news/2025/10/21/news-samsung-reportedly-to-make-korean-hbm4-debut-tomorrow-at-sedex-sk-hynix-also-on-display/ | 3.x、5.x、6.x HBM 市占 / HBM4 进度 | 一手转载 |
| T7 | TrendForce 2026-02-09 Samsung HBM4 出货预测 | https://www.trendforce.com/news/2026/02/09/news-samsung-hbm4-reportedly-to-ship-first-after-lunar-new-year-initial-share-projected-at-mid-20/ | 6.x Samsung HBM4 初期市占 mid-20% | 一手转载 |
| T8 | Tom's Hardware CXMT HBM2 量产报道（2025-Q2） | https://www.tomshardware.com/tech-industry/chinas-cxmt-begins-mass-producing-hbm2-memory-well-ahead-of-schedule-2026-was-the-previously-telegraphed-target | 8.x CXMT HBM2 量产时点、华为 Ascend 客户 | 引 industry sources |
| T9 | Digitimes 2026-04-09 CXMT 12-Hi HBM 2027 目标 | https://www.digitimes.com/news/a20260409PD229/cxmt-hbm-production-2027-market.html | 8.x CXMT 12-Hi HBM 路线图 | 业内估算 |
| T10 | SK Hynix Q4 2025 Earnings Call Highlights — Yahoo Finance | https://finance.yahoo.com/news/sk-hynix-inc-fra-hy9h-010034963.html | 5.x DRAM ASP +25% QoQ、HBM4 量产营收 | 一手 transcript 转载 |
| T11 | SemiAnalysis "AI Server Cost Analysis — Memory Is The Biggest Loser" | https://newsletter.semianalysis.com/p/ai-server-cost-analysis-memory-is | 1.x DGX H100 售价 / 毛利 / HBM 单源 | 付费分析师 |
| T12 | KED Global SK Hynix HBM4 3nm 转换报道（2024-12-03） | https://www.kedglobal.com/korean-chipmakers/newsView/ked202412030008 | 6.x HBM4 base die 从 5nm 升级 3nm 的客户要求 | 业内估算 + 行业消息源 |
| T13 | Bureau of Industry and Security 新闻稿（2024-12-02） | https://www.bis.gov/press-release/commerce-strengthens-export-controls-restrict-chinas-capability-produce-advanced-semiconductors-military | 8.x BIS 管制公告原文 | 政府一手 |
| T14 | Digitimes 2025-12-26 SK Hynix HBM4 量产 / NVIDIA 出样 | https://www.digitimes.com/news/a20251226PD215/sk-hynix-nvidia-hbm4-tsmc-production.html | 6.x HBM4 量产时点 | 付费内容（摘要） |
| T15 | TrendForce 2026-01-09 NVIDIA 推动 HBM4 12-layer ramp + 16-layer push | https://www.trendforce.com/news/2026/01/09/news-nvidia-demand-fuels-hbm4-race-12-layer-ramps-16-layer-push-by-sk-hynix-samsung-and-micron/ | 2.x / 6.x HBM4 首批 12-Hi、16-Hi 仍在开发 | 一手转载 |
| T16 | Tom's Hardware 2026-01 SK Hynix 16-Hi HBM4 48GB CES 2026 展示 | https://www.tomshardware.com/tech-industry/sk-hynix-shows-16-hi-hbm4-memory-for-ai-accelerators-48-gb-at-10-gt-s-over-a-2-048-interface | 2.x / 6.x 16-Hi 48GB 11.7Gbps Vera Rubin 平台样品（仍在开发）| 一手转载 |
| T17 | SK Hynix HBM4 World-First Development 新闻稿 | https://news.skhynix.com/sk-hynix-completes-worlds-first-hbm4-development-and-readies-mass-production/ | 6.x HBM4 量产准备就绪、首批 12-Hi | 一手 |
| T18 | ArentFox Schiff BIS 2024-12-05 出口管制 summary | https://www.afslaw.com/perspectives/alerts/summary-biss-december-5-2024-chip-controls | 8.x 2 GB/s/mm² + License Exception HBM 3.3 GB/s/mm² 门槛 | 一手转载 |
| T19 | Counterpoint Research 2024 全年 HBM 市占数据 | https://www.counterpointresearch.com/insights/global-hbm-market-share-2024/ | 1.x / 3.x / 小结：2024 全年 Samsung HBM 市占约 40%、SK Hynix 约 52%、Micron 约 8%（季度数据来自 TrendForce 付费报告，2024-Q2 41% / 2025-Q2 17% 为付费季度口径） | 二手机构 |
| T20 | Micron HBM4 GTC 2026 量产公告（2026-03-16） | https://investors.micron.com/news-releases/news-release-details/micron-announces-hbm4-high-volume-production | 5.x Micron HBM4 实际进入 high-volume production 时点（自然季度 Q1 末），略早于 TrendForce 2025-12 给的 Q2 预测 | 公司一手 |
| T21 | SemiAnalysis "Huawei Ascend Production Ramp" 报告 | https://newsletter.semianalysis.com/p/huawei-ascend-production-ramp | 8.x Huawei Ascend 全系列与 910C 单型号出货拆分对照（910C ~65 万、910 全系列 ~80 万对照 IDC 2026-04 总数 812K）；CXMT HBM 2026 预测 ~2M stacks | 付费分析师 |

## 已知数据缺口（本章正文必须明示）

- **HBM 出厂价**：三家厂商均不分品类披露。本章使用 Silicon Analysts 4 月 2026 数据库 HBM3 $200/stack、HBM3E $300/stack、HBM4 业内估算 $500/stack。业内估算 ±15%。
- **三家 HBM 单品营业利润率**：均不分品类披露。SK Hynix FY2025 整体营业利润率 49%（一手），DRAM 整体利润率高于平均但 HBM 单品 60%+ 仅是业内估算。
- **HBM4 三家 NVIDIA 认证真实进度**：SK Hynix 已量产 / 占 HBM4 约 2/3、Samsung 1Q26 末完成验证、Micron 已交样但排第三——所有口径都是 TrendForce / Digitimes 业内消息源。
- **CXMT HBM2 良率、出货量、单价**：未上市，仅 Tom's Hardware / Digitimes 行业消息源，业内估算落后 SK Hynix 三代。
- **HBM3E vs HBM4 切换中 2025-Q4 实际 ASP**：合同基本以年度签订，月度 ASP 变化未充分披露。
- **NVIDIA HBM 实际采购单价 / 合同条款**：未披露，按业内估算 NVIDIA 在 HBM3E 上拿到 tier-1 量价。

## 数据采集时点

- 骨架创建时点：2026-05-27
- 全书 data_cutoff：2026-05
- 本章 data_cutoff：与全书一致；三家 HBM 厂取至 2026-Q1 季报、Silicon Analysts HBM 价格库取至 2026-04
- WebFetch 验证时点：2026-05-28
- fact-check 修复时点：2026-05-29（修订 Samsung HBM 2024 市占口径从季度切年度、Micron HBM4 量产时点加注实际 2026-03-16 GTC 公告、Huawei Ascend 81 万从 910C 单型号修正为全系列 aggregate）
