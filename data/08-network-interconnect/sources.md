# Sources — 第 8 章 网络与互连：Broadcom 的隐形 AI 红利

## 一手来源

| 编号 | 来源 | URL / 文档 | 用于章节段落 |
|------|------|-----------|------------|
| S1 | Broadcom FY25 10-K + 8-K | https://investors.broadcom.com/ | 8.1、8.4（AI 半导体营收、毛利） |
| S2 | NVIDIA Blackwell / NVL72 / NVLink 5 architecture whitepaper | https://www.nvidia.com/en-us/data-center/ | 8.2（NVLink 5 带宽、NVSwitch） |
| S3 | NVIDIA FY26 10-K（Networking 业务线拆分） | https://investor.nvidia.com/ | 8.3、8.5（IB / Spectrum-X 收入） |
| S4 | Astera Labs FY25 10-K + S-1 | https://ir.asteralabs.com/ | 8.6（PCIe retimer 营收与毛利） |
| S5 | Marvell FY26 10-K + 10-Q（定制硅业务披露） | https://investor.marvell.com/ | 8.4（Marvell ASIC 与 AVGO 对比） |
| S6 | Coherent FY25 10-K（含 II-VI 合并后口径） | https://ir.coherent.com/ | 8.7（光模块） |
| S7 | Lumentum FY25 10-K | https://www.lumentum.com/en/investors | 8.7 |
| S8 | 中际旭创（300308.SZ）2025 年报 + 2026-Q1 季报 | http://www.innolight.com/ | 8.7、8.9 |
| S9 | 新易盛（300502.SZ）2025 年报 | 新易盛 IR | 8.7、8.9 |
| S10 | 天孚通信（300394.SZ）2025 年报 | 天孚通信 IR | 8.7、8.9 |
| S11 | Arista Networks FY25 10-K（以太网 AI 数据中心交换机） | https://investors.arista.com/ | 8.5 |
| S12 | Cisco FY25 10-K（AI 网络营收） | https://investor.cisco.com/ | 8.5（对照） |
| S13 | NVIDIA Q4 FY26 earnings call 2026-02-25（Networking 全年 $31.4B / +142% 一手披露） | https://investor.nvidia.com/ + 多源转引（TheEnergyMag、ServeTheHome） | 8.3、8.8（NVDA Networking FY26 营收 + 网络层双抽税表） |
| S14 | AVGO Q4 FY25 earnings call 2025-12-12（AI 半导体 FY25 $20B / +65% YoY 一手） | https://investors.broadcom.com/ + The Motley Fool transcript + swift.vc 综合 | 8.4、8.8（AVGO AI 半导体全年口径） |
| S15 | UALink Consortium 公告 2024-10-29（Consortium 注册成立） | https://www.businesswire.com/news/home/20241029998800/en/Ultra-Accelerator-Link-Consortium-Incorporates-Announces-Membership-Opportunity | 8.2（UALink 时间线） |
| S16 | UALink Consortium 1.0 规范公告 2026-04-07（四份规格正式发布） | https://www.businesswire.com/news/home/20260407620696/en/Ultra-Accelerator-Link-UALink-Consortium-Publishes-Four-Specifications-Defining-In-Network-Compute-Chiplets-Manageability-and-200G-Performance | 8.2（UALink 1.0 正式发布时点） |
| S17 | NVIDIA developer blog GB200 NVL72 文章 | https://developer.nvidia.com/blog/nvidia-gb200-nvl72-delivers-trillion-parameter-llm-training-and-real-time-inference/ | 8.2（NVLink 5 1.8 TB/s bidirectional 口径 + 130 TB/s aggregated bidirectional） |
| S18 | NVIDIA Newsroom Mellanox 收购公告 + SEC 8-K NVDA-20200427 | https://nvidianews.nvidia.com/ + SEC EDGAR | 8.3（Mellanox $6.9B 收购对价 + 2020-04-27 完成时点） |

## 二手来源

| 编号 | 来源 | 用于段落 | 是否已回溯一手 | 备注 |
|------|------|---------|--------------|------|
| T1 | LightCounting 800G / 1.6T 光模块年度报告 | 8.7 | 部分（行业出货数据，无更上游一手） | 标口径 + 时点 |
| T2 | Dell'Oro Group AI Networking 季度报告 | 8.3、8.5 | 部分 | 与 LightCounting 交叉 |
| T3 | 650 Group AI infrastructure 报告 | 8.1、8.5 | 部分 | — |
| T4 | Morgan Stanley AVGO / NVDA / AVGO 网络深度（2025-2026） | 8.3、8.4 | 部分（基于财报） | — |
| T5 | Bernstein AI 网络专题 | 8.3、8.7 | 部分 | — |
| T6 | The Information / The Register 关于 Meta 以太网 / Anthropic Spectrum-X 试点的报道 | 8.5 | 部分（"据知情人士"） | 不作为唯一来源 |
| T7 | ServeTheHome / Tom's Hardware NVL72 / B200 集群拆机 | 8.2 | 部分（基于实物） | — |
| T8 | SemiAnalysis AI Networking 深度 | 8.1、8.4 | 部分 | — |

## 已知数据缺口（按"业内估算 / 无法验证"标）

1. **Broadcom 定制 XPU 客户名（Google / Meta / ByteDance 等）**：AVGO 披露"超大客户"但不点名，本书严格用 AVGO 披露口径，业内归属仅作交叉佐证。
2. **NVIDIA Networking 业务（InfiniBand + Spectrum-X + NVLink Switch System）独立毛利率**：NVDA 在 FY26 Q4 earnings call 2026-02-25 给出 FY26 全年 Networking 营收 $31.4B / +142% 一手口径（业务边界含 NVLink Switch System + InfiniBand + Spectrum-X 三类），但不分子产品披露毛利率。**业内估算 70%+，按估算标注**。注意：本章 §8.3 中 InfiniBand 与 Spectrum-X 单独的营收拆分仍属业内估算，因 NVDA 不细分披露。
3. **AVGO AI 半导体 XPU vs 网络拆分**：AVGO 自己披露与卖方拆分口径不同，需明确两套口径并列。
4. **1.6T 光模块 2026 末出货**：仍以厂家指引 + 卖方预测为主，**预测属性按时点 + 区间标注**。
5. **Spectrum-X / IB 在大客户的实际渗透率**：META / Anthropic / xAI 试点规模仅有媒体披露，**不作为唯一来源**。

## 数据采集时点

- 最后一次更新：2026-05
- 财报数据截止：AVGO FY25（截至 2025-11）/ 其他 2026-Q1
- 行业报告截止：2026-Q1
- 全章 data_cutoff：2026-05

## 与其他章联动

- ch01 BOM 表 → 本章网络成本进 BOM 整柜行
- ch07 NVLink 系统税 → 本章 8.2-8.5 是横向佐证
- ch09 服务器与整柜 → 本章 8.2 NVL72 物理形态承接 ch09 整柜叙事
- ch20 沿价值链守住中心节点 → 本章 8.9 中国光模块产业链对美出口的政策传导
- ch30 设备商型估值模板 → AVGO 与 NVDA 并列作为五税商业模式模板
