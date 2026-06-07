# Sources — 第 28 章 出口管制与脱钩的经济账：三套口径下的双边成本

> 占位文件。写正文时按 data-citation.md 规范补全。

## 一手来源（待补全）

| 编号 | 来源 | URL / 文档 | 用于章节段落 |
|------|------|-----------|------------|
| S1 | BIS Export Controls Federal Register Notices | https://www.bis.doc.gov/index.php/regulations/federal-register-notices | 28.1 / 28.7 |
| S2 | NVIDIA 10-K / 10-Q 地域营收披露 | SEC EDGAR | 28.3 / 28.10 |
| S3 | Applied Materials / KLA / Lam Research FY25 10-K（一手地域披露：AMAT FY25 总营收 $28.37B / 中国 ~30%；LRCX FY25 总营收 $18.44B / 中国 ~34%；KLA FY25 总营收 $12.16B / 中国 ~30%；fact-check 已直接拉取一手 10-K）| SEC EDGAR | 28.3 |
| S4 | 美国商务部 CHIPS 办公室公告（含 TSMC Arizona $6.6B 2024-04 + 2024-11 最终协议；Samsung Taylor 2024-04 初步条款 $6.4B → 2024-12 最终协议 $4.745B；Intel Ohio 2024-03 初步条款 $8.5B → 2024-11 最终协议 $7.86B + $11B 贷款）| https://www.commerce.gov/chips | 28.3 / 28.8 |
| S4b | AMD Q2 2025 Form 8-K（一手 SEC 申报）：$800M MI308 库存与相关支出，源自美国政府对 AMD Instinct MI308 数据中心 GPU 产品的出口管制 | SEC EDGAR | 28.3 |
| S5 | TSMC 6-K 月度营收 + 地域披露 | TSMC IR | 28.5 |
| S6 | ASML 季报 + 在手订单披露 | https://www.asml.com/en/investors | 28.5 |
| S7 | SK Hynix / Samsung IR HBM 客户结构披露 | 各公司 IR | 28.5 |
| S8 | SMIC 财报 + 公告 | https://www.smics.com/en/site/investor_information | 28.4 |
| S9 | 中国商务部出口管制公告（稀土 / 锗 / 镓） | http://www.mofcom.gov.cn/ | 28.9 |
| S10 | USGS Mineral Commodity Summaries 2025（一手：镓中国占全球 99%；锑 ~47-48%；锗 ~60%；高纯石墨 ~65%；中重稀土 Tb / Dy 等 ~85-90%）| https://pubs.usgs.gov/periodicals/mcs/ | 28.9 |
| S11 | NVDA 财报会议 transcript（H20 / H20E 节奏） | NVDA IR | 28.7 / 28.10 |
| S12 | Tokyo Electron / Screen / Advantest 财报 | 各 IR | 28.5 |

## 二手来源（待补全）

| 编号 | 来源 | 用于段落 | 是否已回溯一手 |
|------|------|---------|--------------|
| T1 | PIIE 出口管制系列评估（Chad Bown 2024 *Export Controls: America's Other National Security Threat*（PIIE Working Paper 24-x）+ Hufbauer / Schott 2024-2025 工作论文综合，无单一对应报告） | 28.6 | 部分（综合多篇工作论文，无单一对应报告） |
| T1b | Bordoff & O'Sullivan, *Foreign Affairs* 2024-09《The Age of Energy Insecurity》+ 2025-05 系列分析（科技脱钩 + 能源 + 产业政策） | 28.2 / 28.6 | 部分 |
| T2 | CSIS Wadhwani Center / Trade Policy Reports | 28.1 / 28.6 / 28.11 | 部分 |
| T3 | Bernstein / Mizuho / Citi 半导体研究（中国敞口） | 28.3 / 28.5 | 部分 |
| T4 | SemiAnalysis（华为 / SMIC / Ascend 出货估算） | 28.4 | 否（业内估算） |
| T5 | The Information / Reuters / Bloomberg 报道 + CRN / Tom's Hardware 2025-08 报道（AMD MI308 $800M 减值的媒体补充：fact-check 阶段已升级为一手 AMD Q2 2025 8-K SEC 申报，时点修正为 Q2 FY2025 / 2025-07，详见 S4b）| 28.4 / 28.7 | 已回溯至一手（S4b）|
| T6 | Capital Economics / Bloomberg Economics 中美脱钩测算 | 28.6 | 部分 |
| T7 | ITIF 关于 CHIPS Act 评估 | 28.8 | 部分 |
| T8 | Brookings / Atlantic Council 报告 | 28.6 / 28.11 | 部分 |

## 已知数据缺口（本章相关）

本章是全书数据缺口最集中的章节之一，主要因为中方信息不透明：

- **华为 Ascend 910C 出货量与单价**——非上市，多数业内估算，差异大（30 万-70 万颗 / 年）
- **SMIC 7nm（N+2）良率**——公司不披露，业内估算 30-50%
- **国产 ASIC 真实订单与良率**（寒武纪 / 海光 / 摩尔线程）——部分上市公司有营收披露但芯片级数据缺失
- **CHIPS Act "已批 vs 实付 vs 实际产出"** 三个口径必须严格区分
- **中方稀土反制的实际经济效应**——出口许可数据有但下游影响（半导体设备 / 防务 / 汽车）需推断
- **NVDA 中国数据中心营收口径**——"按销售目的地"vs"按账单地点"差异大，必须按 10-K 原文口径
- **第三方溢出的精确量化**——韩台日欧的敞口部分披露，部分须从产业链反推

## 数据采集时点

- 骨架创建时点：2026-05-27
- 全书 data_cutoff：2026-05
- 章节特定 data_cutoff：与全书一致；BIS 清单取截至 2026-05 最新公告，NVDA 财报取 FY26 全年
