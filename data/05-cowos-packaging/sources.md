# Sources — 第 05 章 CoWoS：被低估的物理瓶颈

> 数据 cutoff：2026-05。所有 CoWoS 月产能数据为月度等效；TSMC 自身披露与第三方测算口径有 ±10% 差异；CoWoS 单 package 与单 wafer 经济数据为业内估算（公司不分品类披露），区间 ±15-25%。

## 一手来源（已 WebFetch 验证）

| 编号 | 来源 | URL / 文档 | 用于章节段落 | 验证结果 |
|------|------|-----------|------------|---------|
| S1 | TSMC 季度法说会（FY2025 Q1-Q4 6-K）| sec.gov/Archives/edgar/data/0001046179 | §5.3 月产能 / §5.6 先进封装营收占比 8-10% | 部分（Q4 6-K 抓取 403，Alpha-sense 综合替代） |
| S2 | Amkor 10-K FY2025 + Q1-Q3 10-Q | sec.gov/Archives/edgar/data/0001047127/000104712726000014/amkr-20251231.htm | §5.5 Amkor 高级封装位置 | 间接（搜索结果确认含 2.5D + TSV + 硅中介层描述） |
| S3 | NVIDIA FY26 Q4 财报（DC 营收 $62.3B、FY26 全年 $215.9B、DC 全年 $193.7B+ networking $11B） | nvidianews.nvidia.com 2026-02-25 | §5.0 概览 / §5.7 章末判断 | 已验证（FY26Q4 DC $62.3B） |
| S4 | IEEE Xplore "Wafer Level System Integration of the Fifth Generation CoWoS-S with High Performance Si Interposer at 2500 mm²"（2021）| ieeexplore.ieee.org/document/9501649 | §5.1 工艺细节 / §5.4 良率近 100% | 已验证（标题与摘要） |
| S5 | NVIDIA 10-Q long-term supply obligations $6.9B + 预付款 | SemiAnalysis 2022 转引 | §5.6 资产专用性 | 间接（SemiAnalysis 转引一手数据） |

## 二手 / 行业研究来源（已 WebFetch 验证）

| 编号 | 来源 | 用于段落 | 验证日期 |
|------|------|---------|---------|
| T1 | TrendForce 2024-12-13 "TSMC Ramps up CoWoS Capacity across Taiwan, Projected to Nearly Triple by 2026"（2024 35K / 2025 70K / 2026 90K——2026 数字为 2024-12 时点预测；TrendForce 2025-12-08 上修为 120-130K）| §5.3 产能曲线 2024 年底 35K 数字 | 已验证 |
| T2 | TrendForce 2025-12-08 "TSMC's CoWoS-L/S Reportedly Fully Booked"（2025 末 75-80K / 2026 末 120-130K / ASE CoWoP 20-25K）| §5.3 产能 / §5.4 CoWoS-L S 分线 / §5.5 ASE | 已验证 |
| T3 | TrendForce 2025-01-02 "TSMC Set to Expand CoWoS Capacity to Record 75,000 Wafers in 2025"（2025 75K 翻倍 2024 35K）| §5.3 产能曲线 | 已验证 |
| T4 | TrendForce 2025-12-15 "MediaTek Secures Google v7e v8e TPU Orders, Requests 7-Fold CoWoS Increase"（MediaTek 2027 申请 150K wafer/年）| §5.3 客户配额 | 已验证 |
| T5 | TrendForce 2025-08-29 "Broadcom Reportedly Boosts 2026 CoWoS Orders"（Broadcom 2026 加单含 Google TPU v7 / Meta MTIA） | §5.3 客户配额 | 已验证 |
| T6 | TrendForce 2024-09-05 "TSMC Plans Rapid CoWoS Expansion Through 2026"（CAGR >50% 2022-2026、TSMC VP Jun He 演讲、建厂周期 1.5-2 年）| §5.2 扩产物理时间 | 已验证 |
| T7 | TrendForce 2024-05-22 "TSMC More Ambitious on CoWoS Capacity Expansion, Targeting 60% CAGR by 2026" | §5.3 CAGR 60% | 已验证 |
| T8 | TrendForce 2024-11-22 "TSMC Reportedly Slows Down CoWoS Capacity Expansion for 2026"（2024-11 短暂放缓背景）| 章节背景，未直接引用 | 已验证 |
| T9 | TrendForce 2026-05-14 "TSMC Sees AI Wafer Demand Rising 11x From 2022–2026, Targets CoWoS With 24 HBM Stacks in 2029"（11× AI wafer 需求、14× reticle、20-24 HBM stack 长期路线）| §5.1 CoWoS-L 未来路线 | 已验证 |
| T10 | TrendForce 2024-04-16 "TSMC Aggressively Expands CoWoS Capacity, 2024 Target Doubled" | §5.3 产能曲线 | 失败 404，由 T1 / T3 替代 |
| T11 | Tom's Hardware 2026-01-02 "A deeper look at the tightened chipmaking supply chain"（2025 末 75K / 2026 末 120-130K / Bernstein Stacy Rasgon 引语 "HBM 需 DDR5 3-4 倍 wafer"）| §5.0 概览 / §5.3 产能 | 已验证 |
| T12 | FinancialContent 2026-02-05 "TSMC to Quadruple Advanced Packaging Capacity: Reaching 130,000 CoWoS Wafers Monthly by Late 2026" | §5.3 产能曲线 | 标题已验证（详情 socket 抓取失败，Tom's Hardware T11 同步确认） |
| T13 | SemiAnalysis "Advanced Packaging Part 2 Review"（2022-01）"CoWoS-S 用于 NVIDIA P100/V100/A100 / Broadcom / Google TPU / Amazon Trainium / AMD Vega / Xilinx FPGAs / Intel Spring Crest；reticle limit 858 mm²；3× reticle stitching；NVIDIA Q3 long-term supply obligations $6.9B 主要绑 CoWoS"| §5.1 CoWoS 变种 / §5.6 资产专用性 | 已验证 |
| T14 | SemiAnalysis "Nvidia's Blackwell Reworked - Shipment Delays & GB200A Reworked Platforms"（2024-10）| §5.1 CoWoS-L CTE 问题 / §5.4 良率爬坡 | 间接（3DInCites 与 Tom's Hardware 综合转引） |
| T15 | 3DInCites 2024-10-18 IFTLE 607 "Why Nvidia's Blackwell is Having Issues with TSMC CoWoS-L Technology"（CTE 失配、Google 400K+ GB200 / Meta $10B / Microsoft OpenAI 推迟 Q1 2025 后、TSMC 新建 AP6 厂） | §5.1 CoWoS-L CTE 问题 / §5.4 良率 | 已验证 |
| T16 | Epoch AI "AI Chip Supply Chain Constraints"（2026-Q1）"NVIDIA/Google/AMD/Amazon 4 家消耗 90% CoWoS 与 HBM、占先进逻辑 die 仅 12%" | §5.0 概览数据 | 已验证 |
| T17 | Silicon Analysts "NVIDIA B200 Cost Breakdown"（2026-03-02）（B200 BOM $6,400 / GPU die $850 / HBM3e 8 stack $2,900 / CoWoS-L $1,100 / 装配测试 $1,550；H100 CoWoS $750） | §5.4 CoWoS-S vs L 单价 / §5.6 价值分配 | 已验证 |
| T18 | Introl Blog 2025 "CoWoS and Advanced Packaging Chip Architecture in Data Centers"（NVIDIA 2025 CoWoS-L 占 70%+ 配额、CoWoS-S vs L vs R 描述、TSMC 扩 8 个 CoWoS 厂）| §5.1 CoWoS 变种 / §5.3 客户配额 / §5.4 CoWoS-L NVIDIA 70% 配额 | 已验证 |
| T19 | WikiChip TSMC CoWoS 词条（CoWoS-S 2012 推出、CoWoS-R / CoWoS-L 发展史、65nm 硅中介层工艺）| §5.1 工艺细节 / 时间线 | 抓取失败 socket 关闭；维基百科页面历史信息相对稳定，作为辅助参考 |
| T20 | TSMC 3DFabric 技术文档（CoWoS 品牌结构、CoWoS-S / CoWoS-R / CoWoS-L、3DFabric 2022 统一品牌）| §5.1 工艺品牌 | 抓取失败 403；信息散见多家行业报道交叉确认 |
| T21 | 7evenguy "What Are CoWoS-S, CoWoS-R, and CoWoS-L"（CoWoS-S 全硅中介层、CoWoS-R 有机替代、CoWoS-L LSI 桥接、HBM3 stack 数量、Q4 2024 TSMC 28K wafer/月） | §5.1 三变种比较 | 已验证 |
| T22 | Tickeron "TSMC CoWoS Expansion"（TSMC FY25 advanced packaging 营收 8%、FY26 预计 10%+、CoWoS 2026 末 127K wafer/月 NVIDIA 占一半以上）| §5.3 产能 / §5.6 先进封装营收占比 | 已验证（搜索结果综合显示） |
| T23 | Alpha-Sense TSMC Earnings 综合（Q4 2025 营收 $33.73B / 全年 NTD 3,809.05B / 中值 USD $120.9B 按 31.5 NTD/USD 换算，与 ch04 统一口径；FY25 全年毛利率 59.9%、FY25 Q4 单季毛利率 62.3% 创单季历史新高）| §5.6 TSMC 公司层面财务 | 已验证（部分内容综合自 Q1 2026 数据，明确标记） |
| T24 | Lam Research FY24 季报 "HBM packaging-related equipment revenue grew triple-digit percentages YoY" | §5.2 TSV 设备 | 业内研报转引（未直接 WebFetch 公司原始文档） |
| T25 | Camtek FY24-25 季报 "advanced packaging 是营收最主要驱动" | §5.2 量测设备 | 业内研报转引（未直接 WebFetch 公司原始文档） |
| T26 | NVIDIA investor relations 2025-09-18 联合公告 "NVIDIA and Intel to Develop AI Infrastructure and Personal Computing Products"（$5B 投资 + x86 + RTX SoC 联合开发，封装基础为 EMIB / Foveros）+ TechPortal 2025-12-26 "Nvidia completes $5Bn investment in Intel" | §5.6 NVIDIA hold-up 应对 | 已验证（投资公告 2025-09-18，完成交割 2025-12-26；fact-check 修正原稿 2024 年表述错误） |
| T27 | Arizona Commerce Authority 公告 + Amkor 投资者新闻稿（2023-11 首次公告 Peoria advanced packaging facility / 2024-07 与 DOC 签署 CHIPS Act PMT / 2025-10 破土动工 / 2028 年初预期投产；总投资 $5B 扩至 $7B / CHIPS Act 直接拨款 $407M） | §5.8.1 Amkor 国别分布 | 已验证（fact-check 修正原稿 "2024 年宣布" 表述歧义） |

## 关键引用文本（一手定性）

- **Bernstein Stacy Rasgon（Tom's Hardware 2026-01-02 转引）**："producing HBM requires approximately three to four times more wafer resources than DDR5 manufacturing"——用于 §5.0 概览说明 CoWoS / HBM 是真正约束。
- **TrendForce 2025-12-08 标题原文**："TSMC's CoWoS-L/S Reportedly Fully Booked"——用于 §5.3 / §5.4 满产佐证。
- **NVIDIA 10-Q（SemiAnalysis 2022 转引）**：long-term supply obligations $6.9B with $1.64B prepayments already made, additional $1.79B planned——用于 §5.6 资产专用性。
- **Tom's Hardware 2026-01-02**："NVIDIA expected to account for more than half of [2026 CoWoS] output"——用于 §5.3 NVIDIA 配额。

## 已知数据缺口（本章相关）

- **缺口 #2 TSMC CoWoS 单独毛利率**——公司从未单独披露 CoWoS 毛利率；业内估算 50-55% 中位区间（与 ch01 H100 BOM 拆解口径一致；CoWoS-S 偏上沿、CoWoS-L 偏下沿乃至略低于 50%，全口径加权回归 50-55%）。
- **CoWoS-L 良率**——TSMC 不公开 stack 良率；业内估算 2024 初期 60-70%、2025 末稳态 75-80%。
- **Amkor / ASE 在 NVIDIA 合格供应商列表的真实进度**——半公开；公司从不披露认证状态。
- **CoWoS 各客户实际月度配额**——半公开；本章数据综合 TrendForce / SemiAnalysis 报道与卖方研报推算。
- **TSMC CoWoS 单 wafer 加工费**——公司不披露；业内估算 $40-50K（CoWoS-S vs CoWoS-L 不同）。
- **Amkor 2.5D advanced packaging 业务独立营收**——10-K 未单独披露，归在 "computing end market" 大类下。
- **ASE CoWoP 客户认证进度**——公司未披露 NVIDIA / AMD 是否在认证名单。

## 一手数据可获取性的局限说明

CoWoS 这条链上一手数据可获取性比 HBM 章更弱：
1. TSMC 把 CoWoS 与 SoIC、CoWoP 合并为"先进封装"披露，无法精确分离 CoWoS 自身的营收/毛利率/产能贡献；
2. Amkor 与 ASE 不分品类披露 CoWoS-class 业务，10-K / 10-Q 只能间接推算；
3. NVIDIA 与 CoWoS 供应链上的合约细节几乎全部为商业机密；
4. CoWoS 月产能的三方口径（TrendForce / DigiTimes / SemiAnalysis）存在 ±10% 差异，本章选取中位值并标注区间。

本章所有产能数据均为综合多源估算，并在每个数字旁明示来源与时点。涉及单 package 经济数据均明确标注"业内估算"，并给出推算逻辑。

## 数据采集时点

- 骨架创建时点：2026-05-27
- 正文写作时点：2026-05-28
- 全书 data_cutoff：2026-05
- 章节特定 data_cutoff：与全书一致；CoWoS 月产能取至 2025-Q4 TrendForce 与 Tom's Hardware 2026-01 综合更新；TSMC 财务取至 FY2025 Q4 财报（2026-01 发布）；NVIDIA 财务取至 FY26 Q4（2026-02-25 发布）。

## 待补全（fact-check 阶段处理）

- TSMC 2025-Q4 法说会 transcript 原文中"先进封装 2025 占总营收 8%、2026 预计 10%+"的 CC Wei / Wendell Huang 原话（Alpha-Sense 综合二次转引，需要回溯一手 transcript）
- Bernstein Stacy Rasgon 关于 HBM 与 CoWoS 是真正约束的原始研报（Tom's Hardware 转引，需 fact-check 回溯）
- SemiAnalysis 2022 "Advanced Packaging Part 2 Review" 关于 NVIDIA $6.9B long-term supply obligations 的具体 10-Q 期号（季度需精确到 Q3 FY23 vs 其他季度，本章引用为 "Q3"，需回溯一手 10-Q）
- TSMC VP Jun He 在 SEMICON Taiwan 2024 演讲的视频或 transcript 原文（"建厂周期从 3-5 年压缩到 1.5-2 年"原话）
- ASE CoWoP 月度 20-25K wafer 目标的公司一手指引（TrendForce 2025-12-08 转引，需找 ASE 财报或新闻稿对照）
