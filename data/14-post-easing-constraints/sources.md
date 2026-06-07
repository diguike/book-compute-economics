# Sources — 第 14 章 缓解之后：电力与客户集中度成为新硬约束

## 一手来源

| 编号 | 来源 | URL / 文档 | 用于章节段落 |
|------|------|-----------|------------|
| S1 | NVIDIA FY26 10-K 客户集中度披露 + 历史 10-K（FY22 起） | https://investor.nvidia.com/ | 14.4、14.7 |
| S2 | CoreWeave S-1 + 2025-Q1/Q2/Q3 10-Q + 8-K（RPO 集中度） | CoreWeave IR | 14.4、14.6 |
| S3 | PJM IMM 容量市场拍卖结果（与 ch10 共享） | https://www.pjm.com/markets-and-operations/rpm | 14.2 |
| S4 | ERCOT 大负荷请求积压（与 ch10 共享） | http://www.ercot.com/ | 14.2 |
| S5 | EIA / DOE 美国变压器供应链评估 | https://www.eia.gov/ / https://www.energy.gov/ | 14.2 |
| S6 | GE Vernova / Hitachi Energy / Siemens Energy 变压器交货 IR | 各公司 IR | 14.2 |
| S7 | NRC SMR 公开审批记录（NuScale / TerraPower / X-energy / Holtec） | https://www.nrc.gov/ | 14.3 |
| S8 | Vistra / Constellation / TerraPower / X-energy / Holtec SMR 公开公告 | 各公司 IR | 14.3 |
| S9 | Microsoft-Constellation Three Mile Island 重启公告（与 ch10 共享） | Microsoft / Constellation 2024-09 | 14.2 |
| S10 | NVIDIA FY26 10-K 关联交易 / 战略投资披露 | NVIDIA IR | 14.4（伏笔，主战场留 ch18） |
| S11 | Anthropic-Google / Anthropic-AWS 战略投资公告 | Anthropic / Google / AWS 联合公告 | 14.4 |
| S12 | xAI Colossus 公开通讯 + Memphis Chamber | xAI 官方 + Memphis Chamber + Introl Blog | 14.4 |
| S13 | PJM 2027/28 BRA 触顶 $333.44/MW-day（FERC 临时上限上调后） | PJM Inside Lines 2025-12-17 + Power Engineering 2025-12 + EnergyChoiceMatters 2025-12-17 | 14.1、14.2、14.8 |
| S14 | CoreWeave-OpenAI 三笔合约一手披露（2025-03-10 $11.9B / 2025-05 $4B / 2025-09-25 $6.5B = $22.4B） | CoreWeave 新闻稿 2025-03-10 + CoreWeave 8-K 2025-09-25 + CNBC 2025-03-10 + Bloomberg 2025-09-25 | 14.0、14.4 |
| S15 | NVIDIA FY22 Q4 earnings release（Data Center FY22 $10.61B 一手） | https://nvidianews.nvidia.com/news/nvidia-announces-financial-results-for-fourth-quarter-and-fiscal-2022 | 14.5 |
| S16 | Anthropic 2026-02 ARR $14B 公开披露（$1B → $14B 14 个月跃升） | SaaStr 2026-02 + CNBC 2026-02-12 "Anthropic closes $30 billion funding round at $380 billion valuation" | 14.0、14.4 |
| S17 | xAI Colossus 100K H100 首阶段 2024-07-22 上线（122 天建成） | xAI 官网 "Colossus" + Introl Blog | 14.4 |
| S18 | NVIDIA-OpenAI 战略合作公告（"up to $100 billion" + "至少 10GW"） | OpenAI / NVIDIA 联合公告 2025-09-22 | 14.5 |
| S19 | 2026 自然年 hyperscaler CapEx 实际上修轨迹（Meta $125-145B / Amazon ~$200B / Google $175-190B） | Fortune 2026-04-29 + ConstellationR + CNBC 2026-04-29 + Futurum "AI Capex 2026: The $690B Infrastructure Sprint" + Tom's Hardware | 14.1 |

## 二手来源

| 编号 | 来源 | 用于段落 | 是否已回溯一手 | 备注 |
|------|------|---------|--------------|------|
| T1 | Dylan Patel / SemiAnalysis 二手 GPU 价格跟踪 | 14.6 | 部分（业内） | 业内估算严格标注 |
| T2 | Silicon Data H100 Rental Index | 14.6 | 部分（指数） | — |
| T3 | Bernstein / Morgan Stanley / Mizuho neo-cloud 深度 | 14.6 | 部分 | 与 ch16 联动 |
| T4 | Bloomberg 关联交易 / 循环交易跟踪 | 14.4 | 部分 | 主战场留 ch18 |
| T5 | Pritchett "Lessons from History of Investment Booms"（telecom 1999 fiber 价格） | 14.6 | 部分（学术整理） | 数据缺口 11 |
| T6 | Brookings telecom buildout 系列 | 14.6 | 部分 | — |
| T7 | Richmond Fed "Boom and Bust in Telecommunications" | 14.6 | 部分 | — |
| T8 | Goldman Sachs / Bernstein SMR 商业化时间表对照 | 14.3 | 部分 | 与 NRC 一手交叉 |
| T9 | The Information / Reuters 关于 Anthropic / xAI 主要客户结构的报道 | 14.4 | 部分 | 不作为唯一来源 |

## 已知数据缺口（按"业内估算 / 无法验证"标）

1. **NVDA 客户名（10-K 不点名）**：本章严格按 FY26 10-K 全年直接披露口径——两个直接客户 ≥10%（Customer A 22% + Customer B 14% = 36%），Top 4 全年业内估算 ~61%（综合 FY26 Q1-Q4 10-Q 单季披露 + 全年 10-K 推演，与 ch07 §7.6 已立锚一致）；FY26Q2 10-Q 单季 Top 2 = 39%（Customer A 23% + Customer B 16%）、Top 6 entities = 85% 为单季高位口径；本章不点客户名，市场推测的"5 家 hyperscaler 终端 50-55%"业内估算仅作交叉佐证。
2. **Anthropic / xAI 真实客户结构**：未上市，**业内估算 + 标无法验证**。
3. **二手 H100 / H200 跌幅**：无公开市场，**Dylan Patel + 渠道 + Silicon Data 多源**。
4. **SMR 实际并网时间**：不同公司公告与 NRC 审批口径差异大，**按"截至 2026-05 业内估算"标**。
5. **大型变压器交货周期 24-48 个月**：GE Vernova / Hitachi 披露范围 + 行业整理综合，**按区间表达**。
6. **1996-2000 长途光纤 per-Mbps 曲线**：调研 SUMMARY 已列为数据缺口 11，**多源拼接 + 标"无单一权威曲线"**。
7. **CoreWeave 折旧应力测试**：本章 14.6 给框架，详细模型留 ch16。
8. **NVDA 客户集中度反身性量化模型**：本章 14.7 给框架性敏感度，完整模型留 ch30。

## 数据采集时点

- 最后一次更新：2026-05
- NVDA 10-K FY26 截止：2026-01-26（FY26 财年终）
- CoreWeave 季报截止：2026-Q1（如已发布）/ 2025-Q4
- PJM 拍卖：2025-07（2026/27 容量年度）
- 全章 data_cutoff：2026-05

## 与其他章联动

- ch10 数据中心与电力 → 本章 14.2 是 ch10 物理位的次生硬约束位
- ch11 双瓶颈物理 → 本章承接 ch11 章末 NVDA 毛利率敏感度
- ch12 2027 拐点 → 本章承接 ch12 供给侧缓解判断
- ch13 杰文斯 + 训推三段 → 本章 14.4 客户集中度与 ch13 需求侧弹性互动
- ch16 CoreWeave 解剖 → 本章 14.6 折旧应力测试输入 ch16 完整模型
- ch18 模型层与循环交易 → 本章 14.4 关联交易 / 战略投资为 ch18 机制描述位输入
- ch27 算力与电力市场 → 本章 14.2 + 14.3 是 ch27 宏观外溢的中介位
- ch29 周期定位 → 本章 14.6 二手 H100 跌幅是 ch29 三个泡沫顶部预警的伏笔；14.7 NVDA 客户集中度反身性是 ch29 NVDA P/E 历史分位对照的输入
- ch30 五估值模板 → 本章 14.7 是 NVDA 反身性量化模型的伏笔
- ch31 12 议题答辩 → 议题 7（电力）+ 议题 8（客户集中度）主答辩位
- ch32 五年之后 → 本章是"电力 + 客户集中度"三不变量章中两个不变量的章末伏笔位
- 附录 D-2 可证伪条件操作手册 → 议题 7、8 的可证伪条件清单
