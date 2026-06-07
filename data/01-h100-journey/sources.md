# Sources — 第 01 章 一张 H100 的旅程：从沙子到 token 的 BOM

## 一手来源

| 编号 | 来源 | URL / 文档 | 用于章节段落 | 验证状态 |
|------|------|-----------|------------|---------|
| S1 | NVIDIA Q4 FY26 财报新闻稿 | https://nvidianews.nvidia.com/news/nvidia-announces-financial-results-for-fourth-quarter-and-fiscal-2026 | §2 NVIDIA 毛利率 75.0% / FY26 数据中心营收 $193.7B / 全年 GAAP 71.1% | 已 WebFetch 验证 |
| S1b | NVIDIA Form 10-K FY2026 | https://www.sec.gov/Archives/edgar/data/0001045810/000104581026000021/nvda-20260125.htm | §2 NVIDIA FY26 R&D expense $18.497B（已公开披露，非业内估算） | 已 WebFetch 验证（fact-check L88-A-14） |
| S2 | TSMC FY25 4Q 6-K SEC filing | https://www.sec.gov/Archives/edgar/data/0001046179/000104617926000008/a4q25e_withguidancexfinal.htm | §2 §4 §7 TSMC FY25 整体毛利率 59.9% / Q4 62.3% | 已 WebSearch 间接验证（来自 Finovian / SEC） |
| S3 | TSMC Capital Markets Day 2025 + 月度营收 | https://investor.tsmc.com/ | §5 CoWoS 容量计划 / HPC 比重 | 待 fact-check 阶段直接 fetch |
| S4 | SK Hynix FY25 Financial Results 新闻稿 | https://news.skhynix.com/sk-hynix-announces-fy25-financial-results/ | §4 §5 SK Hynix FY25 营业利润率 49% / Q4 营业利润率 58% / HBM 营收同比翻倍 | 已 WebSearch 间接验证（来自 blocksandfiles / Yahoo Finance / 官网） |
| S5 | 工业富联 2025 年报（601138，鸿海 A 股子公司） | 工业富联 IR / 腾讯财经转载 2026-03（https://news.qq.com/rain/a/20260312A01S6C00） | §2 §4 §5 工业富联 601138 FY25 整体毛利率 6.98% / AI 服务器分品类 12-15% / 营收 9028.87 亿 RMB | 已 WebFetch 验证（fact-check L73-A-11） |
| S5b | Hon Hai (鸿海母公司) FY2025 press release | https://www.honhai.com/en-us/press-center/press-releases/latest-news/1978 | §4 主体口径说明：母公司 FY25 毛利率 6.15%（与子公司 601138 不同口径，本书不混用） | 已 WebFetch 验证 |
| S6 | CoreWeave S-1 + 2024 10-K + 2025-Q1 8-K | SEC EDGAR | §1 CoreWeave 数据中心位置；6 年折旧 | 已 WebSearch 间接验证（来自 wccftech / Bizety / SeekingAlpha 多家） |
| S7 | NVIDIA H100 产品规格页 + Hopper Architecture Whitepaper | https://www.nvidia.com/en-us/data-center/h100/ + https://developer.nvidia.com/blog/nvidia-hopper-architecture-in-depth/ | §1 H100 SXM5 物理规格：5 stack HBM3 / 80GB / 3.35 TB/s / 814 mm² die / 800 亿晶体管 / TSMC 4N | 已 WebFetch 验证 |
| S8 | ASML FY2025 press release + 6-K | https://www.asml.com/en/news/press-releases/2026/q4-2025-financial-results；GlobeNewsWire 转载 2026-01-28（https://www.globenewswire.com/news-release/2026/01/28/3227191/0/en/ASML-reports-32-7-billion-total-net-sales-and-9-6-billion-net-income-in-2025.html） | §1 §3 ASML 2025 全年 EUV 交付 48 套（含 2 台高 NA）/ FY2025 毛利率 52.8% | 已 WebFetch 验证 |
| S8b | ASML EUV 定价：FourWeekMBA 2026（低 NA） + TechPowerUp 2024（高 NA） | https://fourweekmba.com/asml-machine-pricing-from-5m-duv-to-724m-hyper-na-euv/；https://www.techpowerup.com/319071/asml-high-na-euv-twinscan-exe-machines-cost-usd-380-million-10-20-units-already-booked | §1 低 NA EUV 单价 $183-220M、高 NA EUV 单价 $380M | 已 WebFetch 验证（fact-check L38-A-2） |
| S9 | Hon Hai (Foxconn) FY2025 & 4Q25 财报 | https://www.foxconn.com/en-us/press-center/press-releases/latest-news/1978 | §5 整机组装产业链 | 直接 fetch 403，间接通过 Futubull / 中华网验证 |

## 二手来源（已交叉核对）

| 编号 | 来源 | 用于段落 | 是否已回溯一手 |
|------|------|---------|--------------|
| T1 | Silicon Analysts AI Chip Costs Database 2026-04 snapshot | §2 §3 §5 §7 BOM 拆解主框架 + GB200 BOM + 数据缺口 | URL: https://siliconanalysts.com/data/ai-chip-costs；已 WebFetch 验证 H100 $3,320 / GB200 $13,500 / B200 $6,400 |
| T2 | SemiAnalysis "AI Server Cost Analysis — Memory Is The Biggest Loser" 2023 | §1 §2 §7 HBM 占 BOM 35-47% 经典论断 / 第二口径对照 | URL: https://newsletter.semianalysis.com/p/ai-server-cost-analysis-memory-is；已 WebSearch 间接验证 |
| T3 | SemiAnalysis "B100, B200, GB200 - COGS, Pricing, Margins" 2024-03 | §2 §3 Blackwell 一代 BOM 对照 + GB200 单模组售价 ~$65,000 业内估算 | URL: https://newsletter.semianalysis.com/p/nvidia-b100-b200-gb200-cogs-pricing；已 WebSearch 间接验证 |
| T4 | TrendForce "TSMC CoWoS Capacity Triple by 2026" 2024-12-13 | §5 §6 CoWoS 月产能 2024 35K → 2025 70-75K → 2026 90-130K | URL: https://www.trendforce.com/news/2024/12/13/news-tsmc-ramps-up-cowos-capacity-across-taiwan-projected-to-nearly-triple-by-2026/；已 WebFetch 验证 |
| T5 | TrendForce "TSMC CoWoS to 75K Wafers in 2025" 2025-01-02 | §5 CoWoS 2025 月产能 75K | URL: https://www.trendforce.com/news/2025/01/02/news-tsmc-set-to-expand-cowos-capacity-to-record-75000-wafers-in-2025-doubling-2024-output/；已 WebSearch 间接验证 |
| T6 | FinancialContent / Token Ring "TSMC 130K CoWoS by Late 2026" 2026-02-05 | §5 CoWoS 2026 末月产能 130K | URL: https://markets.financialcontent.com/...；fetch 失败但已 WebSearch 间接验证 |
| T7 | IntuitionLabs "NVIDIA AI GPU Prices: H100 ($27K-$40K)" 2024 | §1 §2 H100 渠道售价 $25,000-30,000 | URL: https://intuitionlabs.ai/articles/nvidia-ai-gpu-pricing-guide；已 WebSearch 验证 |
| T8 | Tom's Hardware "Blackwell Superchips $70K, NVL72 $3M" 2024 | §3 GB200 NVL72 整柜售价 $2.8-3.4M | URL: https://www.tomshardware.com/pc-components/gpus/nvidias-next-gen-blackwell-ai-gpus-to-cost-up-to-dollar70000-fully-equipped-servers-range-up-to-dollar3000000-report；已 WebSearch 验证 |
| T9 | WikiChip TSMC CoWoS 条目 | §1 CoWoS interposer 尺寸 ~2,500 mm² / 3× reticle | URL: https://en.wikichip.org/wiki/tsmc/cowos；待 fact-check 直接 fetch |
| T10 | Spheron / Awesome Agents NVL72 Guide 2024 | §3 NVL72 72 GPU + 36 CPU + 13.5 TB HBM3E + 120kW + 1.36 t | URL: https://www.spheron.network/blog/nvidia-gb200-nvl72-guide/；已 WebSearch 验证 |
| T11 | TrendForce / Counterpoint Foundry 市占率 2025-Q1 | §6 TSMC 先进节点 90% 市占率 | 已在 supply-chain-overview.md 调研中验证 |
| T12 | SUMCO 2024 IR Day | §1 信越 + SUMCO 12 寸硅片合计 50% 市占率 | 已在调研中验证 |
| T13 | wccftech / Bizety / SeekingAlpha CoreWeave 6 年折旧分析 | §1 CoreWeave 6 年折旧（参考性） | 已 WebSearch 间接验证（一手是 CoreWeave S-1） |

## 已知数据缺口（本章承担 6 项，已在正文 §7 明示）

| 缺口 # | 数据项 | 业内估算区间 | 主要估算来源 |
|---|---|---|---|
| 1 | NVIDIA 实际 BOM | $3,000-3,500 | Silicon Analysts / SemiAnalysis / Bernstein 三方拆解，±15-20% |
| 2 | TSMC CoWoS-S 单独毛利率 | 50-55% | 卖方研报反推（公司不分品类披露），±10pp |
| 3 | HBM3 单 stack 出厂价 | $200-300/stack | Silicon Analysts HBM Pricing + TrendForce 月度跟踪 + SemiAnalysis 分析，±15% |
| 4 | GB200 NVL72 整柜实际成交价 | $2.8-3.4M | HSBC 2024 + Tom's Hardware + 多家媒体共识，±15% |
| 5 | TSMC 4N 单 H100 die 制造成本 | $280-340 | Silicon Analysts wafer cost USD 17K-20K + 良率 60-70% 反推，±15% |
| 6 | NVIDIA 数据中心业务单卡净利 | $15,000-18,000 | 由 GAAP 毛利率 + 运营费用率反推，±20% |

## 数据采集时点

- 骨架创建时点：2026-05-27
- 正文初稿写作时点：2026-05-28
- 全书 data_cutoff：2026-05
- 章节特定 data_cutoff：与全书一致；NVDA / TSMC / SK Hynix / Foxconn 财报数据取至 2026-Q1 财报披露完毕后的最新版

## 关键事实交叉验证记录

写作期间通过 WebFetch / WebSearch 直接核对的关键数据点：

| 数据点 | 一手 / 二手值 | 验证状态 |
|---|---|---|
| NVIDIA Q4 FY26 数据中心营收 | $62.3B | 已直接 WebFetch nvidianews.nvidia.com 验证 |
| NVIDIA FY26 全年数据中心营收 | $193.7B | 同上 |
| NVIDIA Q4 FY26 整体毛利率 GAAP / Non-GAAP | 75.0% / 75.2% | 同上 |
| NVIDIA FY26 全年毛利率 GAAP | 71.1% | 同上 |
| TSMC FY25 整体毛利率 | 59.9% | 已 WebSearch 间接验证（一手是 TSMC SEC 6-K filing） |
| TSMC Q4 2025 毛利率 | 62.3% | 同上 |
| TSMC CoWoS 月产能 2024 → 2025 → 2026 | 35K → 75K → 90-130K | 已直接 WebFetch TrendForce 验证 |
| SK Hynix FY25 营业利润率 | 49% | 已 WebSearch 间接验证 |
| SK Hynix Q4 2025 营业利润率 | 58% | 同上 |
| H100 SXM5 物理规格 | 5 stack HBM3 / 80GB / 3.35 TB/s / GH100 die 814 mm² / 800 亿晶体管 / TSMC 4N | 已直接 WebFetch developer.nvidia.com 验证 |
| H100 渠道售价 | $25,000-30,000（mid 价位）/ Dell HGX 8-GPU 板 $216K | 已 WebSearch IntuitionLabs 等多源验证 |
| H100 BOM 总额 | $3,320 | 已直接 WebFetch Silicon Analysts 验证（其下分项 die $300 + HBM $1,350 + CoWoS $750 + test/assembly $920） |
| B200 BOM 总额 | $6,400（die $1,400 + HBM $2,900 + CoWoS $1,100 + ...） | 已 WebSearch SemiAnalysis 间接验证 |
| GB200 BOM 总额 | $13,500（die $1,700 + HBM $5,800 + CoWoS $2,200） | 已直接 WebFetch Silicon Analysts 验证 |
| GB200 单模组售价（业内估算） | ~$65,000 | 已 WebSearch 间接验证（SemiAnalysis "B100, B200, GB200 COGS, Pricing, Margins" 2024-03 + Silicon Analysts 2026-04 交叉） |
| GB200 NVL72 整柜售价 | $3M（HSBC 2024 估算 / 多家媒体确认） | 已 WebSearch 多源验证 |
| GB200 NVL72 整柜 HBM3E 总容量 | 13.4 TB | 已直接 WebFetch NVIDIA GB200 NVL72 产品页验证（72 × B200 × 192 GB ≈ 13.4 TB；早期 Spheron Guide 给 13.5 TB，按 NVIDIA 一手页修正为 13.4 TB） |
| 工业富联 601138 FY25 整体毛利率 | 6.98%（AI 服务器分品类 12-15%）；鸿海母公司合并报表 6.15%（不同口径） | 已 WebFetch 多源验证（fact-check L73-A-11） |
| NVIDIA FY26 R&D 支出 | $18.497B（10-K 一手披露） | 已 WebFetch 验证（fact-check L88-A-14；旧稿 $26-30B 估算已废弃） |
| ASML FY2025 EUV 交付 | 48 套（含 46 台低 NA、2 台高 NA EUV） | 已 WebFetch 验证（一手 ASML press release） |
| ASML EUV 单台售价 | 低 NA $183-220M / 高 NA $380M | 已 WebFetch FourWeekMBA + TechPowerUp 验证（fact-check L38-A-2；旧稿 $150-180M 区间已修正） |
| CoWoS-S interposer 尺寸 | ~2,500 mm²（约 3× reticle 858 mm²） | 已 WebSearch WikiChip 间接验证 |
| CoreWeave 6 年折旧政策 | 6 年直线 | 已 WebSearch 间接验证（一手 CoreWeave S-1） |

发布前 P1（留 verify-data / fact-check 阶段处理）：
- TSMC CoWoS 月产能 90K vs 130K 两个数字的口径差异（TrendForce 2024-12-13 给的是 90K、FinancialContent 2026-02 给的是 130K）—— 正文已并列引用两数 + 标"目标"
- Dell HGX H100 8-GPU 板报价 $216K 一手 URL 待补
- IntuitionLabs 网页可信度低于卖方研报，发布前再补一手或转 SemiAnalysis 系列

## 写作期间未独立 fact-check（留 fact-check 阶段验证）

- NVIDIA Mellanox 收购 InfiniBand 业务历史细节
- Ibiden ABF 基板 80%+ 集中度（Counterpoint / SUMCO IR Day）
- AVC / Auras vapor chamber 散热在 H100 SXM5 中的市占
- 各 hyperscaler 数据中心物理位置（AWS Loudoun / MS VA-TX-AZ / Google OR-IA-SC / CoreWeave VA-TX-NV）
- SemiAnalysis 早期 H100 BOM $3,200 与 Bernstein $3,500 vs Silicon Analysts $3,320 的三方差异
- Epoch AI GPT-4 训练 ~10^25 FP16 FLOPs 估算（Epoch AI 公开数据）
