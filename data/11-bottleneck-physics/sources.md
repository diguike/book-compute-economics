# Sources — 第 11 章 双瓶颈的物理学：CoWoS 与 HBM 为什么是真紧缺

## 一手来源

| 编号 | 来源 | URL / 文档 | 用于章节段落 |
|------|------|-----------|------------|
| S1 | TSMC 4 季度法说会逐字稿（CoWoS 产能指引） | https://investor.tsmc.com/ | 11.2、11.4 |
| S2 | TSMC 月度营收公告 | https://investor.tsmc.com/ | 11.2 |
| S3 | SK Hynix FY25 IR Day + 季报 | https://www.skhynix.com/eng/ir/ | 11.2、11.5 |
| S4 | Micron FY25-FY26 10-K / 10-Q（HBM3e 12h 量产时间表） | https://investors.micron.com/ | 11.2、11.5 |
| S5 | Samsung 半导体季报 + IR Day | https://www.samsung.com/global/ir/ | 11.2、11.5 |
| S6 | ASML 季报 + 在手订单披露 | https://www.asml.com/en/investors | 11.4 |
| S7 | NVIDIA FY26 10-K 供应链披露 + Blackwell whitepaper | https://investor.nvidia.com/ | 11.5、11.6、11.7 |
| S8 | TSMC IEDM / VLSI Symposium / Symposium on Advanced Packaging 论文 | IEEE Xplore | 11.3（CoWoS-L 良率） |
| S9 | SK Hynix / Micron / Samsung IEDM / ISSCC HBM 工艺论文 | IEEE Xplore | 11.3（TSV 工艺） |
| S10 | NVIDIA 财报 / 公告中关于 HBM 供应链多元化的披露 | NVIDIA IR | 11.5 |
| S11 | Silicon Analysts AI Chip Costs 数据库 2026-04 snapshot（GB200 BOM 拆解 + HBM Pricing） | 商业数据库订阅 | 11.6、11.7、§11.7 表 11-31 BOM、表 11-26 HBM 单 stack 价格曲线 |
| S12 | Lam Research / Camtek / Onto / AMAT / ASML FY24-FY25 季报 | 各公司 IR | 11.4（设备厂业绩对照表 11-17）|
| S13 | NVIDIA FY26 全年 earnings release（2026-02-25 新闻稿 / 8-K）— 区别于 FY26 10-K | nvidianews.nvidia.com / SEC EDGAR | 11.2、11.6、11.7 |

## 二手来源

| 编号 | 来源 | 用于段落 | 是否已回溯一手 | 备注 |
|------|------|---------|--------------|------|
| T1 | Trendforce HBM 月度 + CoWoS 季度报告 | 11.2、11.3、11.6 | 部分（行业整理） | 业内估算严格标注 |
| T2 | SemiAnalysis CoWoS / HBM / NVDA 深度系列 | 全章 | 部分 | 与 TSMC / SK Hynix 一手交叉 |
| T3 | Bernstein HBM 价值链深度（2024-2026） | 11.6、11.7 | 部分 | — |
| T4 | Morgan Stanley / Mizuho NVDA / TSMC / HBM 三家深度 | 11.5、11.7 | 部分 | — |
| T5 | Dylan Patel 公开访谈与报告 | 11.5、11.6 | 部分 | 与一手交叉 |
| T6 | Reuters / 韩国朝鲜日报 / 中央日报 / 日经关于 Samsung HBM3e 认证延迟、CoWoS 客户分配的报道 | 11.5 | 部分（多源） | 不作为唯一来源 |
| T7 | DigiTimes 关于 TSMC CoWoS 嘉义 / 高雄新厂的报道 | 11.4 | 部分 | — |
| T8 | NVDA 卖方共识（Bloomberg / Visible Alpha）毛利率 | 11.7 | 部分（基于 NVDA 季报 + 卖方建模） | 与自建模型对照 |
| T9 | SemiAnalysis 2024-09 "The Memory Wall"（具体报告，T2 系列下子项） | 11.1（HBM 制造成本 $100-130 估算）| 部分 | 时点 2024-09；2026-05 估算可能更低 |
| T10 | Tiger Brokers 2026 CoWoS 月产能 127K 引用 | 11.2（CoWoS 月产能爬坡表 11-2 行注）| 否（二手转引）| 与 TSMC 2025-Q4 法说会 + FinancialContent 130K 交叉 ±3K |
| T11 | FinancialContent 2026-02-05 "TSMC to Quadruple Advanced Packaging Capacity" | 11.2 | 否（二手）| 引用 TSMC 一手；130K 与 Tiger Brokers 127K 双源 |
| T12 | Tom's Hardware 2026-01-02 CoWoS 产能综述 + 2025-09-23 Samsung HBM3e 12-Hi 通过 NVDA QS | 11.2、11.5 | 否（二手）| 与 T1 TrendForce / T6 韩国报道交叉 |
| T13 | Digitimes 2025-12-26 HBM4 加速量产报道 | 11.2、11.5 | 否 | T7 主题之外的扩展 |
| T14 | Futurum 综合 Micron Q1 FY2026 earnings call 2025-12 | 11.5、表 11-4 | 是（基于 Micron 一手 earnings call） | Cloud Memory BU $5.3B 数字交叉 |
| T15 | 3DInCites 2024-10-18 NVDA Blackwell CoWoS-L 翘曲 / CTE 失配报道 | 11.3 表 11-7 / §11.3 翘曲段 | 否（二手）| 与 SemiAnalysis "Nvidia's Blackwell Reworked" 2024-10 交叉 |
| T16 | TrendForce 2026-05-14 CoWoS-L 路线 14 倍 reticle / 20 stack 报道 | 11.3 | 部分 | 2026-05 data_cutoff 时点之内最新行业报告 |
| T17 | KED Global 2025-09-19 / 韩国朝鲜日报 / 中央日报 Samsung HBM3e 12-Hi 通过 NVDA QS 时点报道 | 11.5 | 否（T6 系列下具体文章登记）| 与 T6 笼统覆盖打通 |

## 已知数据缺口（按"业内估算 / 无法验证"标）

1. **CoWoS-L 月产能 2026 末 130K+ 目标**：TSMC 自己披露与 Trendforce / SemiAnalysis 估算口径不同，**多源并列 + 标"业内估算"**。
2. **HBM 单 stack 价格 $80 → $300+ 历史曲线**：三家厂商均不披露 stack 价格，**业内估算 $200-300 区间表达**。
3. **CoWoS-L 大面积 interposer 良率**：TSMC 学术论文给定性数据，量化数字仅有 SemiAnalysis 等估算，**按"业内估算"标**。
4. **Samsung HBM3e 8h NVDA 认证延迟具体时点**：Samsung 自己披露与第三方报道差 1-2 季，**两套时间线并列**。
5. **NVDA 毛利率敏感度矩阵**：本章 11.7 是**作者自建模型**，5 个关键假设需在 sources.md 与正文同步明示，每项标敏感性边界：
   - 假设 1：HBM 占 BOM 43%（$5,800 / $13,500）；敏感性边界 35%-50%（Rubin 平台升级到 HBM4 后上升）。
   - 假设 2：GPU die 占 BOM 13%（双 B200 + Grace die 摊销）；敏感性边界 11-15%（受 TSMC 节点迁移影响 < 1pp）。
   - 假设 3：整卡 ASP $75K 中值；敏感性边界 $65K-$90K 业内估算区间。
   - 假设 4：反身性传导系数 70%（BOM 节省被 NVDA 吸收为毛利的比例）；敏感性边界 50-85%。50% 时矩阵正向 pp 缩水约 29%；85% 时放大约 21%。
   - 假设 5：CoWoS 利用率 100% → 80% 对应单 wafer 边际成本下降 5-10%（业内估算）；敏感性边界 3-12%，取 7.5% 为中值。
   配套数据文件：`data/11-bottleneck-physics/nvda-margin-sensitivity.csv`（9 交叉点完整算式 + 反身性系数边界 + 公司层翻译）。

## 数据采集时点

- 最后一次更新：2026-05
- 财报数据截止：TSMC / SK Hynix / Micron / Samsung 2026-Q1
- 行业报告截止：2026-Q1
- 全章 data_cutoff：2026-05

## 与其他章联动

- ch01 BOM → 本章产能与价格曲线推回 BOM
- ch05 CoWoS 横截面 → 本章是 ch05 的机制 / 时序深化（边界严格切分）
- ch06 HBM 横截面 → 本章是 ch06 的机制 / 时序深化
- ch07 NVDA 五税 → 本章 11.7 是"供给紧缺税"机制位的量化伏笔
- ch12 2027 拐点 → 本章四因素分解是 ch12 拐点判断的供给侧基线
- ch14 缓解之后 → 本章 11.7 NVDA 毛利率敏感度是 ch14 客户集中度反身性的伏笔
- ch29 周期定位 → 本章 11.7 是 NVDA P/E vs Lucent/Nortel 历史分位比对的输入
- ch30 设备商型估值模板 → 本章 11.7 输入 NVDA 估值模板

## 关联任务（待回收）

- **NVDA FY26 supply commitments $90B+ vs GAAP RPO $2.3B 口径**：ch11 fact-check 已明确两套数字口径不同——NVDA FY26 10-K 披露 GAAP RPO（合同 >1 年）为 $2.3B；$90B+ 是 off-balance-sheet 的 supply / purchase commitments，业内卖方研报整理口径。本章 §11.1 / §11.2 / §11.4 / §11.6 / 小结统一改成 "supply commitments $90B+"，并明示 GAAP RPO 是 $2.3B。S7 / S13 一手数字待 ch07 fact-check 完成后做最终对账（ch07 §7.6.2 supply commitments 披露口径同步追溯任务）。
- **Samsung DS FY25 营业利润率 19.1%（非 22%）**：ch11 fact-check 修正。来源：Samsung Electronics 2025 全年业绩 DS 营业利润 KRW 24.9T / DS 营收 KRW 130.1T。本章 §11.5 与 SK Hynix 49% 的差距相应改为 30pp（非 27pp）。
- **ASML 2025 末 backlog €38.8B（非估算 ">€35B"）**：ch11 fact-check 修正，来源 ASML Q4 2025 财报 2026-01-28，与 ch03 fact-check 一致口径。
- **Micron HBM4 GTC 2026 量产宣布日期 2026-03-16（非 03-17）**：ch11 fact-check 修正，一手来源 GlobeNewswire / Micron IR 2026-03-16。StorageNewsletter 2026-03-17 是次日转引。
- **NVDA 前 5 客户营收占比 ~40%**：本章 §11.7 假设表与 ch07 §7.6 + ch29 §29.3 维度 10 共用同一口径；待 ch07 verify-data 关解决"4 客户 vs 4-5 客户"口径分歧后回收。
