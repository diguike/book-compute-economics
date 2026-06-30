# Sources — 第 7 章 加速芯片：NVIDIA 75% 毛利率的护城河拆解

## 一手来源

| 编号 | 来源 | URL / 文档 | 用于章节段落 |
|------|------|-----------|------------|
| S1 | NVIDIA FY26 10-K | https://investor.nvidia.com/ | 7.1（营收 / 毛利率）、7.6（客户集中度）、7.9（地域收入） |
| S2 | NVIDIA FY26Q1-Q4 10-Q | https://investor.nvidia.com/ | 7.1（季度拆分）、7.6（关联交易披露） |
| S3 | NVIDIA GTC 2025 / 2026 主题演讲（CUDA 开发者数量 / Blackwell roadmap） | https://www.nvidia.com/gtc/ | 7.3、7.4、7.5 |
| S4 | NVIDIA Blackwell architecture whitepaper | https://www.nvidia.com/en-us/data-center/ | 7.4（NVLink / NVSwitch 拓扑）、7.5（NVL72 reference design） |
| S5 | AMD Q4 2025 earnings press release（FY25 全年 Data Center segment $16.6B）| https://ir.amd.com/ 2026-02-03 | 7.3.3、7.8（AMD FY25 数据中心营收一手 + MI350 vs H200 对照） |
| S6 | Broadcom FY25 8-K（含 Google TPU ASIC 业务表外贡献） | https://investors.broadcom.com/ | 7.8（TPU 出货规模反推） |
| S7 | AWS re:Invent 2025 主题演讲（Trainium2 / Trainium3） | https://aws.amazon.com/events/reinvent/ | 7.8 |
| S8 | 华为开发者大会公告（Ascend 910C / CANN） | https://developer.huawei.com/ | 7.9（Ascend 出货定性） |
| S9 | Anthropic-Google TPU 大单：Google Cloud 官方新闻稿"Anthropic to Expand Use of Google Cloud TPUs and Services"（up to one million TPU chips）| googlecloudpresscorner.com 2025-10-23 | 7.8（ASIC 大订单证据，一手官方披露口径） |
| S10 | OpenAI-AMD 战略合作公告 + warrant 结构 8-K | AMD 8-K 2025-10 | 7.6、7.8（客户绑定） |
| S11 | NVIDIA FY26 10-K 关联交易 / 战略投资披露（与 CoreWeave / OpenAI / xAI） | https://investor.nvidia.com/ | 7.6（循环交易机制位，详细机制留给 ch18） |
| S12 | Meta FY25 10-K（MTIA 自研路线 / Capex / Data Center 进展披露） | https://investor.atmeta.com/ | 7.3.2（hyperscaler 自研对 CUDA 软件税的对冲位） |
| S13 | CoreWeave 2026-01-23 8-K（NVDA 以 $87.20/share 认购 2,293.6 万股 ≈ $2.0B） | SEC EDGAR 文档 ID 000176962826000044 | 7.6.3（关联投资定量一手） |
| S14 | NVIDIA-OpenAI $100B / 10 GW 战略合作公告 | https://blogs.nvidia.com/blog/openai-nvidia/ 2025-09-22 | 7.6.3（OpenAI 战略投资） |
| S15 | UALink Consortium 1.0 公开规范 / 路线图 | https://ualinkconsortium.org/ | 7.4.3（UALink 替代品时间窗口） |
| S16 | xAI Colossus 集群公告 + Memphis Chamber 2024-2025 公开披露 | xAI 官方 + Memphis Chamber 公示 | 7.6.3（xAI 关联交易） |
| S17 | AMD FY25 全年 Data Center 分部 $16.635B（"a record $16.6 billion, up 32% YoY"）| AMD Q4 2025 earnings press release，ir.amd.com 2026-02-03 | 7.3.3（AMD MI300X / MI350 路径） |
| S18 | NVIDIA GTC 2025 keynote 官方转录稿（CUDA 开发者 ~600 万、覆盖 200+ 国家）| Rev.com transcript 2025 | 7.3.1（CUDA 开发者数量一手） |
| S19 | NVIDIA NVLink 产品页（NVLink 5 每 GPU 1.8 TB/s bidirectional）| nvidia.com/en-us/data-center/nvlink/ | 7.4.2（NVLink 5 带宽方向口径） |
| S20 | NVIDIA FY26 Q3 10-Q（四个直接客户 22% + 15% + 14% + 10%）| SEC EDGAR 2025-11 | 7.6.1（季度客户集中度峰值） |

## 二手来源

| 编号 | 来源 | 用于段落 | 是否已回溯一手 | 备注 |
|------|------|---------|--------------|------|
| T1 | SemiAnalysis H100 / B200 BOM teardown | 7.2 | 部分（基于产业链拆解，非 NVDA 披露） | 业内估算严格标注 |
| T2 | Silicon Analysts / Dylan Patel H100 经济性深度 | 7.2 | 部分 | 与 SemiAnalysis 交叉 |
| T3 | Bernstein NVDA 季度更新 + 中国营收追踪 | 7.1、7.9 | 部分（基于 10-K） | — |
| T4 | Mizuho AMD / 中国 ASIC 深度（2025-2026） | 7.8、7.9 | 部分 | — |
| T5 | Morgan Stanley NVDA 数据中心估值模型 | 7.1（与 ch30 对照） | 部分 | ch30 估值模板时再交叉 |
| T6 | IDC 中国 AI 芯片市场份额 | 7.9 | 部分（口径需说明） | 非财务数据 |
| T7 | Counterpoint Research / TrendForce 中国 AI 芯片出货 | 7.9 | 部分 | 与 IDC 交叉 |
| T8 | The Information 关于 Anthropic-Google TPU、xAI-NVDA、OpenAI-AMD 合同的报道 | 7.6、7.8 | 部分（"据知情人士"，需另找一手佐证） | 不作为唯一来源 |
| T9 | Tom's Hardware / ServeTheHome reference rack 拆解 + Tom's Hardware 2025-Q3 UALink 进展 | 7.4.3、7.5 | 部分（基于实物） | 与 ch09 共享 |
| T10 | PyTorch 2.0-2.5 release notes + HuggingFace Transformers + Accelerate 后端支持矩阵 | 7.3.1 | 上游官方 release notes（一手） | CUDA / ROCm 后端默认对照 |
| T11 | Lamini AI / Together AI 2025 ROCm 部署 retrospective（技术博客 / 公开 talk） | 7.3.2 | 部分（公司公开自述） | 与 SemiAnalysis MI300X 评测交叉 |
| T12 | Supermicro / 工业富联（鸿海精密 2317.TW）/ Dell FY25-FY26 财报与法说会（OEM 整机毛利率） | 7.5.1 | 一手（各公司财报） | 与 ch09 共享 |
| T13 | SemiAnalysis 2025-Q3 *Huawei Ascend Production Ramp* + IDC 2026-04 中国 AI 加速卡市场报告 | 7.9.2（Ascend 910C 出货双锚） | SemiAnalysis 部分 / IDC 一手（付费报告） | 取双锚区间表达 |
| T14 | CXMT HBM 产能 2025 全年 ~2M stacks（SemiAnalysis 综合） | 7.9.2（HBM 约束悲观情景） | 部分 | 与 ch06 国产 HBM 章节共享 |

## 已知数据缺口（按"业内估算 / 无法验证"标）

1. **H100 / B200 / GB200 完整出厂 BOM**：所有数字来自第三方拆解，NVDA 不披露。**业内估算 + 区间表达**。
2. **华为 Ascend 910C 真实出货量、良率、单价**：非上市 + 国安考量披露最低。本章 7.9.2 取 SemiAnalysis 2025-Q3 *Huawei Ascend Production Ramp* 预测（全 Ascend 805K / 910C 占 653K / HBM 约束悲观 250-300K）+ IDC 2026-04 *中国 AI 加速卡市场报告* 实际 812K 全 Ascend 出货双锚，**910C 单型号 250-650K 区间表达**；良率与单价仍无一手。
3. **TPU / Trainium 单位推理毛利率**：Google / AWS 不拆分。Broadcom TPU ASIC 业务表外贡献只能推断 NRE + 出货规模。**框架式拆解**。
4. **NVDA 客户集中度具体客户名**：FY26 10-K 全年披露 Top 2 ~36%（22% + 14%）/ FY26 Q2 10-Q 披露 Top 2 39%、Top 6 ~85% / FY26 Q3 10-Q 披露 Top 4 ~61%（22% + 15% + 14% + 10%），但 NVDA 不点名。市场推测（Microsoft / Meta / Google / Amazon / Oracle）但本书严格只用披露口径。全年 10-K 口径与单季 10-Q 口径差异源自 10% 披露阈值——全年中只有持续大客户保持在阈值之上，季度颗粒度更敏感。
5. **NVDA 关联交易 / 战略投资金额**：10-K 披露但口径碎片化。机制位用之，金额留给 ch18 集中处理。
6. **国产 ASIC（寒武纪 / 燧原 / 海光）真实订单与良率**：仅有招股书 / 部分公告，**业内估算占主**。

## 数据采集时点

- 最后一次更新：2026-05
- 财报数据截止：NVDA FY26（截至 2026-01-26）/ 其他公司 2026-Q1
- 行业报告截止：2026-Q1
- 全章 data_cutoff：2026-05（与全书一致）

## 与其他章联动

- ch01 BOM 表（一手 BOM 拆解）→ 本章 7.2 加价基准
- ch05 CoWoS / ch06 HBM → 本章 7.7 供给紧缺税的物理基础
- ch08 网络与互连 → 本章 7.4 NVLink 系统税的横向佐证
- ch09 服务器与整柜 → 本章 7.5 系统设计税的下游证据
- ch11 双瓶颈物理 → 本章 7.7 的机制深化（瓶颈缓解对毛利率传导）
- ch14 缓解之后 → 本章 7.6 客户集中度反身性的章末伏笔承接
- ch18 模型层与循环交易 → 本章 7.6 关联交易的完整描述位
- ch21 / ch28 → 本章 7.9 中国市场镜像的全景展开
- ch30 五估值模板 → 本章五税分解作为 NVDA 估值模板的护城河输入

## 时效更新补充来源（2026-06-26）

- NVDA FY27 Q1（2026-05-20）：营收 \$81.6B、数据中心 \$75.2B（计算 \$60.4B + 网络 \$14.8B）、GAAP 毛利率 74.9%、GAAP 营业利润 \$53.5B、FY27 Q2 指引 \$91B。来源：NVIDIA IR / Stocktitan。
- AMD Q1 2026（2026-05-05）：营收 \$10.3B、数据中心 \$5.8B（+57%）、GAAP 毛利率 53%；定制版 MI450 进入 Meta 6GW 部署协议。来源：AMD IR、DCD。
- NVDA AI 加速器市占：~80-85%（趋势向下）。来源：Silicon Analysts、TrendForce。
