# Sources — 第 9 章 服务器与整柜：8-12% 毛利的脏活与 NVIDIA 的垂直 onshore

## 一手来源

| 编号 | 来源 | URL / 文档 | 用于章节段落 |
|------|------|-----------|------------|
| S1 | Supermicro FY25 10-K | https://ir.supermicro.com/ | 9.1、9.5（AI 整机毛利） |
| S2 | Supermicro FY24-FY25 8-K（审计 / 申报延期事件） | 同上 | 9.5（背景） |
| S3 | Dell Technologies FY26 8-K / 10-K + Q4 FY26 earnings call（ISG 拆分：ISG 全年 $60.8B、AI server $24.7B、AI backlog $43B 截至 2026-01、ISG OP $7.1B / OP margin 11.7%） | https://investors.delltechnologies.com/ | 9.1、9.5、章末小结 |
| S4 | HPE FY25 10-K（含 Cray AI 业务） | https://investors.hpe.com/ | 9.5 |
| S5 | 工业富联（601138.SS）2025 年报（实际营收 CNY 902.9B / +38%）+ 2026-Q1 季报 | http://www.fii-foxconn.com/ | 9.1、9.5、9.8 |
| S6 | 鸿海精密（2317.TW）月度营收 | https://www.honhai.com/ | 9.1、9.8 |
| S7 | Quanta Computer（2382.TW）月度营收 | https://www.quantatw.com/ | 9.1 |
| S8 | Wiwynn（6669.TW）月度营收 | https://www.wiwynn.com/ | 9.1 |
| S9 | IEIT Systems（伊云数）季报 | 公司 IR | 9.5（对照） |
| S10 | NVIDIA GTC 2025 / 2026 NVL72 reference design 公告 | https://www.nvidia.com/gtc/ | 9.4 |
| S11 | NVIDIA Blackwell + GB200 NVL72 whitepaper | https://www.nvidia.com/en-us/data-center/ | 9.3、9.4 |
| S12 | Tom's Hardware / ServeTheHome NVL72 拆机 + reference rack 详解 | https://www.tomshardware.com/ / https://www.servethehome.com/ | 9.3、9.6 |

## 二手来源

| 编号 | 来源 | 用于段落 | 是否已回溯一手 | 备注 |
|------|------|---------|--------------|------|
| T1 | SemiAnalysis GB200 NVL72 系统经济性 | 9.3、9.4 | 部分（拆机 + 产业链） | 业内估算严格标注 |
| T2 | Morgan Stanley / Mizuho 服务器供应链深度 | 9.1、9.5 | 部分 | — |
| T3 | Counterpoint Research 服务器市占 | 9.1 | 部分 | — |
| T4 | Trendforce 服务器与 AI 服务器月度跟踪 | 9.1 | 部分 | — |
| T5 | The Information / DigiTimes 关于 NVL72 整柜成交价 / 液冷供应商的报道 | 9.3、9.6 | 部分（"据知情人士"） | 不作为唯一来源 |
| T6 | Bloomberg / Reuters 关于 ODM 越南 / 墨西哥扩产报道 | 9.8 | 部分 | 与公司公告交叉 |

## 已知数据缺口（按"业内估算 / 无法验证"标）

1. **GB200 NVL72 整柜实际成交价**：NVDA 不披露，超大客户合同细节不公开。**业内估算 $2.8-3.4M，区间表达**。
2. **整柜 BOM NVDA 模组占比**：基于 ch01 BOM 第三方拆解推导，**业内估算 70%+**。
3. **ODM 公司"AI 营收"定义**：各家口径不同（富士康"云计算" vs Quanta"AI server" vs Wiwynn"hyperscale ODM"），本章需明确口径并列。
4. **液冷 manifold / cold plate 关键供应商集中度**：业内仅有少数报道，**业内估算**。
5. **Supermicro AI GPU 整机内部毛利拆分**：SMCI 给整体业务毛利但 AI 与非 AI 分线毛利不披露。

## 数据采集时点

- 最后一次更新：2026-05
- 财报数据截止：SMCI FY25（截至 2025-06）/ Dell FY26（截至 2026-01，8-K 与 Q4 earnings 已披露 ISG $60.8B / AI server $24.7B / backlog $43B / ISG OP margin 11.7%）/ 工业富联 2025 年报已披露（营收 CNY 902.9B）/ 其他 2026-Q1
- 月度营收数据截止：2026-04
- 全章 data_cutoff：2026-05

## 与其他章联动

- ch01 BOM 表 → 本章 9.3 整柜 BOM 推导的输入
- ch07 加速芯片 → 本章 9.4 系统设计税的横向佐证
- ch08 网络与互连 → 本章 9.3 整柜里 NVSwitch tray / Spine 的占比
- ch16 CoreWeave / Nebius 是 ODM 整柜的最大下游 → 本章为 ch16 整机折旧基数提供输入
- ch20 沿价值链守住中心节点 → 本章 9.8 ODM 产能地理与美国 onshore 政策
- ch29 周期定位 → 本章是"上游 NVDA 寡头垄断 vs telecom 三家分蛋糕"5 差异的工程证据
