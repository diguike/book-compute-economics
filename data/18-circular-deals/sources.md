# Sources — 第 18 章 模型层与循环交易

> 本章是全书法律敏感度最高的章节之一，fact-check 强度最高，每一笔关联交易披露必须原文核对，"嫌疑"措辞严格中性。
> 编号体系：S1-S10 为一手来源（含 SEC EDGAR / 公司 IR / 白宫新闻发布会），T1-T21 为二手来源（含财经媒体、卖方研究、学术研究、行业数据库、Wikipedia）。

## 一手来源

| 编号 | 来源 | URL / 文档 | 用于章节段落 |
|------|------|-----------|------------|
| S1 | NVDA FY2026 10-K（财年截至 2026-01-25 / 2026-02 披露：全年口径前 2 客户 22% + 14% = 36%、4 家客户合计 ~61%）+ FY2026 各期 10-Q（Q1 FY26 10-Q 期末 2025-04-27 口径 16% + 14% = 30%、Q2 FY26 10-Q 期末 2025-07 口径 23% + 16% = 39%）"Concentration of Customer and Credit Risk" 段 + 关联交易披露 + 战略投资公允价值披露 | SEC EDGAR：NVDA CIK 0001045810；Q1 FY26 10-Q 已 WebFetch 锁定 nvda-20250427.htm | NVDA 战略投资矩阵节 / §1.5 / §3.4 / §6.2 / 5 维度对照表维度 4 |
| S2 | NVDA 2024-2026 战略投资 8-K（OpenAI / xAI / CoreWeave / Mistral 关键交易） | SEC EDGAR：NVDA 8-K 各期，含 2025-09-22 OpenAI 框架投资公告（NVIDIA Newsroom 同步发布于 blogs.nvidia.com/blog/openai-nvidia） | NVDA 战略投资矩阵节 / §1.2 / §1.3 |
| S3 | CoreWeave 2025-03 / 2025-05 / 2025-09 各期 8-K（OpenAI 合同三批次扩约：$11.9B 2025-03 + $4B 2025-05 + $6.5B 2025-09 = 累计 $22.4B / 5 年） | SEC EDGAR：CoreWeave CIK（IPO 2025-03 后开始报送）+ CoreWeave IR press release "CoreWeave Expands Agreement with OpenAI by up to $6.5B"（2025-09） | OpenAI 三角合同节 / §1.3 |
| S4 | Oracle FY26 Q1 / Q2 10-Q + 2025-09-09 Press Release + 电话会 transcript（RPO 从 Q4 FY25 末 $138B 跳到 Q1 FY26 末 $455B / Stargate 披露）+ Oracle Q4 FY25 Press Release 2025-06（RPO $138B / 同比 +41% 基线） | SEC EDGAR：Oracle CIK 0001341439 | OpenAI 三角合同节 / §1.3 / 本章 §1 与 ch17 联动数据 |
| S5 | AMD 2025-10-06 8-K（OpenAI 6 GW MI450 + 1.6 亿股 warrant 结构 / $0.01 行权价 / 分批 vesting / 最末批 AMD 股价 ≥ $600 触发） | SEC EDGAR：AMD CIK 0000002488 | AMD warrant 节 / §1.3 |
| S6 | MSFT FY25 10-K（OpenAI 投资披露累计 ~$13B + 关联交易 + 算力 credit 对价说明）+ FY26 续约谈判公开信息 | SEC EDGAR：MSFT CIK 0000789019 | OpenAI 三角合同节 / §1.3 |
| S7 | CoreWeave 2026-01-23 8-K（NVDA 公开市场战略持股 22,935,780 ≈ 22.94M shares × $87.20 ≈ $2.000B；transaction date 2026-01-23 / filing date 2026-01-26）+ CoreWeave 2026-03-31 8-K（$8.5B DDTL facility closed，Meta 5 年合同 + 11 万张 H100/B100 抵押，首次投资级 GPU-backed financing；CoreWeave 2026-02 公开寻求阶段，2026-03-31 完成签约） | SEC EDGAR：CoreWeave 8-K + CoreWeave IR press release | §1.2 NVDA 关联投资清单 / §3.5 GPU 抵押融资证据 / 维度 5 |
| S8 | Lucent Technologies FY1999 10-K（财年截至 1999-09-30，营收 $38B / 毛利 40% / 员工 12 万 / vendor financing 余额披露）+ Lucent 1999-2002 各期 10-Q | SEC EDGAR：Lucent Technologies Inc. CIK 0001006240（1996 年 AT&T 分拆 IPO，2006 年与 Alcatel 合并后注销） | §2.1 Lucent 历史复盘 / §2.3 vendor financing 工具拆解 / 维度 4 Lucent 前 5 客户口径 |
| S9 | Nortel Networks Corporation 1999-2009 10-K（FY1999-FY2008，最末一期 2008-12 财年）+ SEDAR 历史档案（加拿大主报送渠道） | SEC EDGAR：Nortel Networks Corporation CIK 0000072911（按 F-30 表格在 SEC 双重披露）+ SEDAR Plus 历史档案（Nortel Networks Limited） | §2.2 Nortel 历史复盘 / Nortel 崩盘时间线表 |
| S10 | SEC AAER（Accounting and Auditing Enforcement Releases）相关 Lucent / Nortel / Global Crossing / WorldCom 调查 + 法庭文件 | SEC EDGAR Litigation Releases + AAER 序列（Lucent 2004 SEC 和解 AAER 编号 + Nortel 2007 SEC 起诉 CFO / CEO 文件 + Global Crossing 2002 破产法庭文件，具体编号待 fact-check 阶段 WebFetch 锁定） | §2.1-§2.4 vendor financing 信贷质量历史复盘 / §3.4 1999 披露不充分参照 |

## 二手来源

| 编号 | 来源 | 用于段落 | 是否已回溯一手 |
|------|------|---------|--------------|
| T1 | Bloomberg 2026《AI Circular Deals》系列报道 + AMD-OpenAI 2025-10 报道 | §1 循环交易关系网 / §1.3 AMD warrant 行 / 章末综合 | 部分对照 8-K |
| T2 | Wikipedia: Advanced Micro Devices / NVIDIA / OpenAI / CoreWeave / Stargate LLC 等条目 | §1.2 / §1.3 / §1.4 二级公司基本面定位 | 二手汇编，主要数字与一手 8-K 交叉 |
| T3 | The Information 2025-2026 OpenAI / Anthropic / xAI ARR + Anthropic 投资轮报道 | §5.1 公开 ARR 表 / §5.2 修正 ARR / Anthropic 双重依赖表 | 二手交叉，原文是匿名信源 + 不点估值 |
| T4 | Reuters 2025-09 OpenAI-Oracle 报道 + 2025-11 OpenAI ARR 报道 | OpenAI 三角合同 / §5.1 | 已对照 Oracle 电话会 |
| T5 | SemiAnalysis 2025-2026 循环交易跟踪系列 + GPU 单位经济跟踪 | §5.2 修正 ARR 口径 B / C / §6 监测指标 | 部分对照公告 |
| T6 | Sequoia Capital 2024-06 David Cahn《AI's $600B Question》+ 2024-09 续作《$600B Question, Part 2》 | §5.2 四种剔除口径 / 修正 ARR 量级判断 | 公开评论 + 不构成研报 |
| T7 | 2002-2003《Nortel 财务造假》专题报道汇编（含 Fortune 2004-01 / WSJ 2003-2004 系列） | §2.2 Nortel 崩盘 / §2.4 1999 信贷质量历史复盘 | 历史档案 |
| T8 | Google→Anthropic 股权与算力的多源时间线：CNBC 2026-04-24《Google to invest up to $40 billion in Anthropic》（新承诺 up to $40B 股权框架，含业绩里程碑）+ Reuters / Bloomberg 2026-04 跟进 + Google Cloud Press Corner 2025-10-23《Anthropic to Expand Use of Google Cloud TPUs and Services》（up to 1M TPU 多年算力合同，**非股权注入**）+ Google IR 历史披露 2023-2025 股权累计 ~$6.5B（2023 起 ~$5.5B + 2025-01 加 $1B） | §1.1 mermaid 图 / §1.1 第二条线索 Anthropic 段落 / §1.4 Anthropic 双重依赖表 Google 股权 + 算力两行 | 一手公告 + 二手交叉（CNBC / Reuters / Bloomberg 2026-04-24 与 Google Cloud Press Corner 2025-10-23 已锁定） |
| T9 | AWS-Anthropic 投资公告（2023-09 首轮 $4B / 2024-11 加投 $4B）+ Project Rainier 2024-11 Trainium2 集群公告 | §1.4 Anthropic 双重依赖表 AWS 行 | 已对照 AWS 公开公告 |
| T10 | The Register 2025-11《AI 公司互购》系列报道（含 "an industry sector getting fatter by eating itself" 比喻） | §3.3 维度 2 资金流闭环引用 / §1.3 业内估算 Oracle GPU 采购 $40B+ | 部分对照公告 |
| T11 | Fortune 2026-02-02《Pledge to invest $100 billion in OpenAI was 'never a commitment,' says Nvidia's Huang》+ 后续多家媒体跟进（截至 data_cutoff 2026-05，业内估算 NVDA 实际向 OpenAI 相关轮次注入 ~$30B 量级） | §3.4 会计透明度 / 市场反应段（Huang 对 $100B 框架的回调） | 一手报道（Fortune 直接采访） |
| T12 | Silicon Data H100 / H200 Rental Index 月度披露（2023-2026） | §3.5 维度 5 GPU 二手流动性 / §6.4 监测指标 / CoreWeave Meta 合同抵押 | 公开行业数据库 |
| T13 | Wikipedia: Stargate LLC（OpenAI / SoftBank / Oracle / MGX 联合体）+ 白宫 2025-01-21 新闻发布会同步报道 | §1.3 Stargate 行 / §1.5 联动 ch17 数据 | 已对照白宫 Press Release |
| T14 | NVDA Ventures 公开 portfolio 页面（NVDA 一级市场投资清单：Mistral / Cohere / Hugging Face / Perplexity / Runway / Wayve / Figure 等 50+ 标的） | §1.2 NVDA 关联投资清单 6-9 行 | 公司官网公开披露 |
| T15 | xAI Colossus 公告（2024-09 Memphis 200K H100 集群上线 / 2025 扩展到 1M H100/H200 量级）+ xAI 2024-12 Series C 综合报道 | §1.4 xAI 孤峰结构 | 部分对照 xAI 公开声明 |
| T16 | Brookings Institution 2005 Robert Crandall《The Telecommunications Bust: A Reconsideration》+ Wolman 2003《The CLEC Experience》学术研究 | §2.1 Lucent / Nortel vendor financing 历史复盘 / §2.4 信贷质量纠偏 | 公开学术研究 |
| T17 | Fortune 2004-01《What's wrong with Lucent》专题 + WSJ 2002-2003《Nortel / Lucent vendor financing》系列调查 | §2.1 vendor financing 余额时间线表 / §2.4 历史误读纠偏 | 已对照 SEC 调查文件 |
| T18 | Wikipedia: Lucent Technologies / Nortel Networks / Cisco Systems 条目（含 Lucent 1999-12 市值 $258B / 股价 $84.25 → $0.55、Nortel 2000-09 市值 C$398B、Cisco 2000-03-27 市值 $555B / 股价 $80.06 等历史数字） | §2.1 / §2.2 / Lucent / Nortel / Cisco 历史数字 / 维度 4 客户集中度对照 | 二手汇编，与 S8 / S9 交叉 |
| T19 | the-ai-corner 2026-04 Anthropic 2026-Q1 ARR 综合报道 | §5.1 Anthropic 2026-Q1 ARR | 二手综合，与 The Information / Bloomberg 交叉 |
| T20 | Burry 2025-11 Twitter / X 公开攻击点（GPU 折旧业内争议 2-3 年 vs 财务 5-6 年） | §3.5 反面 GPU 折旧争议 / §6.4 触发机制 | 社交媒体公开发言 + 与 Silicon Data 交叉 |
| T21 | Menlo Ventures 2025《State of Generative AI in the Enterprise》年度报告（含 Anthropic 企业 LLM + coding 市场份额突破数据） | §5.1 第二件事 Anthropic 增速观察 | 公开行业研究 |

## 已知数据缺口（本章相关）

- **数据缺口 #6** OpenAI / Anthropic / xAI 详细财务——本章核心数据。全程"业内估算 + 区间"，**单一来源信息不引用**
- **数据缺口 #7** CoreWeave 与 OpenAI 协议的现金流分布——业内估算
- **NVDA 对 OpenAI 投资的最终承诺金额**——已公告分阶段框架，每阶段触发条件未完全披露，按"已公告 + 待触发"分列
- **AMD-OpenAI warrant 行权价 + 触发条件**——部分细节未公开披露，按"已公告 + 估算"标注
- **SEC AAER 具体编号**（S10）——Lucent 2004 SEC 和解 / Nortel 2007 SEC 起诉 / Global Crossing 2002 破产法庭文件的具体编号待 fact-check 阶段 WebFetch 锁定
- **Google→Anthropic 时间线已锁定**（T8）——fact-check 阶段已确认：2026-04-24 CNBC 报道 up to $40B 股权新承诺；2025-10-23 Google Cloud Press Corner 是 1M TPU 算力合同（非股权）。两者性质不同，原"业内综合"标注已细化
- **Jensen Huang 公开表态时点修正**（T11）——fact-check 阶段确认：截至 data_cutoff 2026-05，可锁定的 Huang 关于 $100B 框架的公开发言为 2026-02-02 Fortune 采访"never a commitment"；2026-03 GTC 主题演讲中"circular is not on the table"精确措辞经全网检索无法独立确认，已在正文以 Fortune 2026-02-02 表态替换
- **Lucent FY1999 员工口径差异**——BHC paper《The Rise and Demise of Lucent Technologies》给出 153,000，部分历史汇编引用 120,000；按 12-15 万区间标注

## 数据采集时点

- 骨架创建时点：2026-05-28
- 编号体系修订时点：2026-05-29（verify-data 二轮）
- fact-check 修复时点：2026-05-29（一轮 5 mismatch + 2 timestamp + 1 IC + 3 unverifiable 应用完）
- 全书 data_cutoff：2026-05
- 章节特定 data_cutoff：与全书一致（NVDA / Oracle / CoreWeave FY26 最新一期）

## 法律 / 合规预警

- 本章是法律敏感度最高章。"循环交易嫌疑"必须用"机制层面观察到 X 现象"而非"X 公司虚增 / 操纵 / 欺诈"
- 涉及每一家公司的引述，必须配该公司的官方声明 / 财报披露作为对照
- 1999 vendor financing 历史案例可用作"机制对照"，不可用作"对当前 AI 公司的定性"
- 章末免责段必须明确"评论而非建议、本章不构成对任何公司的指控"

## 跨章共享

- `circular-deals-network.md` 与 ch29（周期定位顶部信号位）共享底表，本章是机制位 / ch29 是信号位
- `mag7-capex-tracking.csv` 与 ch17 共享
- 修正 ARR 模型与 ch31（12 议题答辩）共享，本章只立证据 / ch31 收束定性
- Lucent / Nortel / Cisco 1999-2001 历史口径（S8 / S9 / T18）与 ch29 / ch31 共享，跨章数字按裁定表统一（Lucent 顶峰市值 $258B / Cisco 顶峰市值 $555B / Cisco forward P/E 130x）

## 时效更新补充来源（2026-06-26）

- Oracle RPO：FY26 Q3（2026-03-10）\$553B、FY26 Q4（2026-06-10）\$638B；FY2026 capex \$55.7B、OCI IaaS +93%。来源：Oracle IR FY26 Q3/Q4、ERP Today。
- 模型公司 ARR：Anthropic 2026-05-28 Series G（\$380B 估值）~\$30B run-rate、后续上修；OpenAI 2026-03 ~\$25B+、2026-06-08 递交保密版 S-1。来源：Anthropic IR、VentureBeat、Reuters、PYMNTS。
