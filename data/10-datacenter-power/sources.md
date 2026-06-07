# Sources — 第 10 章 数据中心与电力：钢筋水泥不是瓶颈，电是

## 一手来源

| 编号 | 来源 | URL / 文档 | 用于章节段落 |
|------|------|-----------|------------|
| S1 | PJM Independent Market Monitor 容量市场拍卖结果（2025/26、2026/27） | https://www.pjm.com/markets-and-operations/rpm | 10.2 |
| S2 | EIA 美国零售电价 / 大客户工业电价 | https://www.eia.gov/electricity/ | 10.3、10.7 |
| S3 | EIA 月度电力 / 大负荷接入 | https://www.eia.gov/electricity/data.php | 10.4 |
| S4 | FERC 大负荷请求 / 输电瓶颈报告 | https://www.ferc.gov/ | 10.4 |
| S5 | IEA《Electricity 2024》《Energy and AI 2025》 | https://www.iea.org/topics/electricity | 10.1、10.7 |
| S6 | LBNL 数据中心电力研究（2024 更新） | https://eta.lbl.gov/ | 10.1 |
| S7 | Digital Realty FY25 10-K + 季度 supplemental | https://investor.digitalrealty.com/ | 10.5 |
| S8 | Equinix FY25 10-K + 季度 supplemental | https://investors.equinix.com/ | 10.5 |
| S9 | QTS / Iron Mountain（含 IRM data center）/ CoreSite（American Tower 合并后口径）公开数据 | 各公司 IR | 10.5 |
| S10 | Crusoe Abilene 900MW 项目公告 + Bloomberg / Reuters 项目融资披露 | Crusoe 官方 + Bloomberg | 10.6 |
| S11 | Microsoft-Constellation Three Mile Island 重启公告 | Microsoft / Constellation 联合公告 2024-09 | 10.7 |
| S12 | AWS-Talen Susquehanna 核电 PPA 公告 | Talen 公告 | 10.7、10.8 |
| S13 | Loudoun County / Dominion Energy 公开排队数据 | Dominion Energy IR + Loudoun County Economic Development | 10.3、10.4 |
| S14 | ERCOT 大负荷请求积压公告 | http://www.ercot.com/ | 10.4、10.8 |
| S15 | GE Vernova FY25 10-K + Capital Markets Day（变压器 / 燃机 backlog） | https://www.gevernova.com/ | 10.4（伏笔指向 ch27） |
| S16 | Hitachi Energy / Siemens Energy 变压器交货周期 IR | 各公司 IR | 10.4 |

## 二手来源

| 编号 | 来源 | 用于段落 | 是否已回溯一手 | 备注 |
|------|------|---------|--------------|------|
| T1 | Data Center Frontier（行业垂直媒体） | 10.3、10.6 | 部分（行业整理） | — |
| T2 | Research and Markets / S&P Global IDC 报告 | 10.5 | 部分 | — |
| T3 | Goldman Sachs / Morgan Stanley / Bernstein 数据中心电力深度 | 10.1、10.7 | 部分（基于 IEA / EIA） | 与一手交叉 |
| T4 | Trendforce / Synergy Research 全球 hyperscale DC 容量 | 10.8 | 部分 | — |
| T5 | The Information / Reuters / Bloomberg 关于 Crusoe / xAI Memphis / Loudoun 排队的具体报道 | 10.3、10.6 | 部分 | 与公司公告交叉 |
| T6 | CBRE / JLL / Cushman & Wakefield 数据中心市场报告 | 10.5 | 部分（行业整理） | — |
| T7 | SemiAnalysis Data Center 深度 | 10.6 | 部分 | — |

## 已知数据缺口（按"业内估算 / 无法验证"标）

1. **核心 IDC 集群（北弗 / 凤凰城等）100MW+ 项目排队周期"4 年"**：不同来源（Dominion 公开 vs 行业媒体追踪）口径不同，**按"截至 2025-XX 业内估算"标**。
2. **大型变压器 24-48 个月交货周期**：GE Vernova / Hitachi 披露范围 + 行业整理综合，**按区间表达**。
3. **Crusoe Abilene 实际通电进度**：截至 2026-05 仅有部分阶段公告，最新进度需 fact-check 时确认。
4. **企业级 PPA 价格细节**：MSFT-Constellation / AWS-Talen 等大单具体 $/MWh 价格大多不披露，**业内估算 $80-110/MWh，标无法验证**。
5. **IEA / Goldman Sachs / S&P 数据中心电力 2030 预测口径差异**：本章必须并列三套口径，不取单点。

## 写作期新增 WebFetch 验证信源（2026-05 写作时点）

| 信源 | URL / 报告 | 验证用途 | 验证状态 |
|------|-----------|---------|---------|
| W1 | PJM 2026/2027 BRA Report 2025-07-22 | $329.17/MW-day 上限触顶 | verified（pjm.com 一手 PDF） |
| W1b | PJM 2027/2028 BRA Press Release 2025-12-17 | $333.44/MW-day 新 FERC 上限（+1.3%）+ 134,479 MW | verified（pjm.com 一手 PDF + cpvretail 2025-12-22 交叉） |
| W2 | PJM 2025/2026 BRA Report 2024-07-30 | $269.92/MW-day 同比 +833% | verified |
| W3 | PJM Inside Lines 新闻稿 2025-07-22 "Auction Procures 134,311 MW" | 拍卖中标容量 134,311 MW + supply responds to price signal | verified |
| W4 | NJBPU 2025-07-23 新闻稿 | 新泽西每户电费 +$20-30 政治压力 | verified |
| W5 | EVA Report PJM 2025/26 BRA Final 2024-08 | BGE $466.36 / DOM $444.26 局部价 | verified |
| W6 | Bloomberg 2024-08-29 "Virginia Data Centers Face Seven-Year Wait" | Loudoun 7 年最长 + 1-3 年延长 | verified |
| W7 | Data Center Frontier "Dominion Resumes New Connections" | Loudoun 50GW 排队 + 1GW/年接入 | verified |
| W8 | IEA Energy and AI 2025 Report | 全球 DC 2030 ~945 TWh + 美国 +240 TWh | verified |
| W9 | LBNL 2024 US Data Center Energy Usage Report 2024-12 | 美国 DC 2023 占 4.4%、2028 高端 12% / 580 TWh | verified |
| W10 | Goldman Sachs Research "AI to drive 165% increase" 2024 | 美国 DC 2030 ~750 TWh + 122GW capacity + $720B 升级 | verified |
| W11 | GlobeNewswire 2025-08-25 "US Transformers Industry Report 2025-2030" | LPT 2-4 年交期 + GE Vernova / Eaton / Siemens 主导 | verified |
| W12 | GE Vernova Q3 2025 SEC 8-K（gevpressrelease3q25.htm） | Electrification backlog $26B、YTD +$6.5B | verified |
| W13 | Utility Dive 2024-09-20 Constellation TMI restart | 20 年 PPA + 2028 重启 + Microsoft 客户 | verified |
| W14 | Yahoo Finance 2024-09-23 Jefferies TMI 价格估算 | TMI $110-115/MWh | verified |
| W15 | DOE / CNBC 2025-11-18 Constellation $1B 联邦贷款 | TMI 重启资金 | verified |
| W16 | Talen 8-K 2024-08 + DCD 2024 AWS Susquehanna 公告 | AWS 接收 Cumulus 数据中心园区、$650M | verified |
| W17 | World Nuclear News + AWS-Talen 17 年 PPA 公告 | 1,920MW × 17 年至 2042 + 7 年 ramp | verified |
| W18 | Constellation Calpine 收购 2026-01-07 完成（constellationenergy.com 2026-01 新闻稿） | $26.6B 交易 + 60GW 零 / 低碳容量 + 完成日 2026-01-07 | verified |
| W19 | Constellation 2025-Q4 全年业绩 stocktitan | 2025 调整后 EPS $9.39 + 2025 核电 182,690 GWh | verified |
| W20 | Vistra Comanche Peak 8-K 2025 | 1,200MW × 20 年 PPA、2027-Q4 起送电 | verified |
| W21 | Crusoe Abilene 1.2GW 公告 + Tom's Hardware 2026-03 | 8 栋楼 / 2026-mid 完工 + 10 台 LM2500 燃机 360MW | verified |
| W22 | Data Center Frontier "Crusoe 4.5GW Natural Gas" 2025 | Crusoe 燃机配套 + Abilene 扩张 | verified |
| W23 | Digital Realty Q4 2025 业绩 2026-02-05 | FY2025 core FFO/share $7.39 + Q4 bookings $400M + backlog $817M | verified |
| W24 | Digital Realty Q3 2025 财报会 transcript 2025-10-23 | Q3 FFO/share $1.89、+13% YoY、AFFO +16% YoY、commencement schedule | verified |
| W25 | Equinix 2025 Annual Report (SEC ARS) | 12% AFFO 增长、$3.731-3.811B 区间、280 DC / 77 markets | verified |
| W26 | Equinix Q3 2025 业绩 2025-10-29 | 56 major projects / 12 xScale / 900MW 储备容量 / interconnection +10% | verified |
| W27 | ERCOT 大负荷接入 2025-12 公告 | 2025-11 226GW 排队（同比 +260%）、77% 来自数据中心 | verified |
| W28 | LBNL Queued Up 2025 Edition | 2024 年底全美 2300GW 排队、中位 5 年 | verified |
| W29 | Oklo + Kairos + X-Energy SMR 进度 2025-2026 | Oklo 2028 demo / Kairos Hermes Two 建设许可 / X-Energy IPO 2026-04 | verified |
| W30 | Utility Dive PJM Capacity Auction +22% 2025 | 验证 2026/27 拍卖 22% 同比增 + 触顶 | verified |
| W31 | NVIDIA Blackwell water efficiency + 液冷 | GB200 NVL72 120-140 kW/rack + DLC-2 98% 热抓 | verified |
| W32 | RTO Insider PJM $329 cap + 模拟无上限 $141,828/MW-year | 拍卖触顶 + 模拟突破上限 | verified |
| W33 | Talen Energy IR 2024-11-03 "Statement on FERC Order Rejecting Susquehanna ISA" + Power Engineering 报道 | FERC 否决 AWS Susquehanna 480MW ISA 时点 = 2024-11-01 投票（不是 12 月） | verified |
| W34 | Crusoe 2024-10-15 "Crusoe, Blue Owl Capital and Primary Digital Joint Venture" + DCD 2025 "Crusoe secures $750m credit facility from Brookfield" | $3.4B JV 主导方为 Blue Owl + Primary Digital；Brookfield 单独提供 $750M 信贷 | verified |
| W35 | Latitude Media 2025 "ERCOT's large load queue has nearly quadrupled in a single year" + Utility Dive 2025 | ERCOT 2024 年底排队 63 GW（非 80 GW）；226 GW / 63 GW ≈ 3.6× | verified |

## 数据采集时点

- 最后一次更新：2026-05
- PJM 拍卖数据截止：2025-07（2026/27 容量年度），2025-12（2027/28 容量年度）
- 财报数据截止：2025-Q4 / 2026-Q1
- 行业报告截止：2026-Q1
- 全章 data_cutoff：2026-05

## 与其他章联动

- ch11 双瓶颈物理 → 本章末尾"芯片侧瓶颈缓解后电力成为下一瓶颈"是 ch14 入口
- ch14 缓解之后 → 本章 10.4 物理 Gantt 表是 ch14 的输入
- ch23 主权 AI 新中心 → 本章 10.8 中东 / 东南亚 sovereign DC 伏笔的展开
- ch27 算力与电力市场 → 本章是"电力主线"的起点，ch27 是"宏观外溢"位
- ch30 IDC REIT 估值模板 → 本章 10.5 FFO / AFFO / lease-up rate 数据
- ch32 五年之后 → 本章电力作为不变量的早期证据
