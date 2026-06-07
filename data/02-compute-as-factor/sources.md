# Sources — 第 02 章 算力作为生产要素：定义、计量与三重身份

## 数据采集时点

- 章节首次定稿：2026-05-27
- 本次 sources.md 全量重整：2026-05-29
- 全书 data_cutoff：2026-05
- 章节特定 data_cutoff：与全书一致（涉及 BLS / NVDA / 各家 hyperscaler FY25 季度数据均按 2026-05 前可得最新一期）

## 一手来源

| 编号 | 来源 | URL / 文档 | 时点 | 用于章节段落（L 行号近似） |
|------|------|-----------|------|------|
| S1 | NVIDIA H100 产品规格页（FP32 / TF32 / BF16 / FP16 / FP8 / INT8 Tensor Core dense + sparsity）| https://www.nvidia.com/en-us/data-center/h100/ | 2026-05 访问 | L42（§1.1 FLOPS 单位）/ L84-88（§1.3 陷阱一 dense vs sparsity）|
| S2 | NVIDIA Blackwell B200 / GB200 NVL72 白皮书（Hopper vs Blackwell FP8 / FP4 算力对比） | nvidia.com/en-us/data-center/blackwell-architecture/ | 2026-05 访问 | L88（B200 vs H100 跨代算力比）/ L143（跨代差 1.2-2.5×）|
| S3 | NVIDIA TensorRT-LLM Release Notes（推理 throughput 优化） | github.com/NVIDIA/TensorRT-LLM/releases | 2024-2025 各版 | L361（软件依赖让 H100 inference throughput 涨 2-3 倍）|
| S4 | Solow, R. (1957)《Technical Change and the Aggregate Production Function》| Review of Economics and Statistics, 39(3): 312-320；JSTOR | 1957 原文 | L139（87.5% / 12.5% 增长会计原结论）|
| S5 | Jevons, W. S. (1865)《The Coal Question》| Project Gutenberg 公版 | 1865 原文 | L506-543（§5 Jevons 反弹效应原始论述）|
| S6 | Acemoglu, D. & Restrepo, P. (2018-2020) Robots and Jobs / Tasks 系列 | NBER WP 22252 / 23077 / 25684 / 26331 | 2018-2020 | L548-562（§6 task-based 框架 displacement / productivity / reinstatement 三效应）|
| S7 | Acemoglu, D. (2024)《The Simple Macroeconomics of AI》| NBER WP 32487（2024-05）| 2024-05 | L214 / L232 / L560（Acemoglu 对 AI 对 TFP 真实贡献的谨慎批评）|
| S8 | Bresnahan, T. & Trajtenberg, M. (1995)《General Purpose Technologies: Engines of Growth?》| Journal of Econometrics, 65(1): 83-108 | 1995 原文 | L668-684（§7.3 GPT 三判据：pervasiveness / continuous improvement / innovation complementarities）|
| S9 | Brynjolfsson, E., Li, D. & Raymond, L. R. (2023)《Generative AI at Work》| NBER Working Paper 31161 | 2023-04 首发，2025 修订 | L169（5-15% 生产率提升）/ L556（客服 14% / 新员工 34% / Copilot 55% task completion 速度）|
| S10 | Brynjolfsson, E., Rock, D. & Syverson, C. (2018)《The Productivity J-Curve》| NBER WP 25148 + Brookings | 2018 / 2021 | L179（IT 资本对 TFP 1990-2007 年化 0.8-1.2 ppt）/ L212（J-curve 10-15 年延迟实现期）|
| S11 | Jorgenson, D., Ho, M. & Stiroh, K. (2008)《A Retrospective Look at the U.S. Productivity Growth Resurgence》| Journal of Economic Perspectives, 22(1): 3-24 | 2008 原文 | L179（IT 资本 1995-2007 贡献）/ L199-208（TFP 历史子区间）/ L244（按 ⊂ K 单独测算份额方法论）|
| S12 | Romer, P. M. (1986/1990) Endogenous Growth 系列 | JPE 1986 / JPE 1990 | 1986 / 1990 | L195（Romer 把研发从 A 拆出来作为知识资本）|
| S13 | Stiroh, K. (2002)《Information Technology and the U.S. Productivity Revival》| AER 92(5)：1559-1576 | 2002 原文 | L195（Stiroh 把 IT 资本从 K 拆成独立子要素）|
| S14 | U.S. BLS Productivity News Releases（季度 + 年度 TFP / 多要素生产率） | bls.gov/news.release/prod3.htm + bls.gov/mfp/ | 2024-03 / 2025-03 / 2026-03 各期 | L199-208（TFP 历史区间表）/ L206（2025 年度 0.8%，2026-03 发布）/ L208 注 |
| S15 | U.S. BLS Business Trends and Outlook Survey / Business and Technology Survey | bls.gov/bdm/business-employment-dynamics.htm + Census BTOS | 2024-2025 多期 | L169（美国企业 AI 采纳率 8-12%）|
| S16 | U.S. Census Bureau Business Trends and Outlook Survey | census.gov/programs-surveys/btos.html | 2025 各期 | L169（AI 采纳率交叉源）|
| S17 | CBO（Congressional Budget Office）《TFP Growth in Historical Perspective》| cbo.gov | 2013 | L208（TFP 子区间数据辅助）|
| S18 | IEA《Electricity 2025》+《Energy and AI》| iea.org | 2025 各期 | §1.1 MW 单位辅助 / §4 电力市场对照（间接引用）|
| S19 | Microsoft FY22Q4 法说会（Amy Hood CFO，4 → 6 年折旧公告） | microsoft.com/en-us/Investor + EDGAR 0000789019 | 2022-07-26 法说会 | L267（MSFT 2022-08 折旧政策变化）|
| S20 | Microsoft FY25 10-K + FY25 Q4 balance sheet | EDGAR / microsoft.com/en-us/Investor + microsoft.com/en-us/investor/earnings/fy-2025-q4/balance-sheets | FY25（截至 2025-06-30）2025-07 报送 | L50（MSFT FY25 CapEx $64.6B）/ L257（MSFT FY25 年末 PP&E 净值 $205.0B，accumulated depreciation $93.7B）/ L322（finance lease 余额）/ L324（$115B 量级测算输入）|
| S21 | Alphabet 2023-04-25 Q1 2023 财报新闻稿（4 → 6 年服务器 / 5 → 6 年网络设备） | EDGAR 0001652044-23-000041 + abc.xyz/investor | 2023-04-25 | L268（GOOG Q1 2023 D&A 减 $988M / FY23 减 $3.4B）|
| S22 | Alphabet Q1 2025 8-K + 后续季度披露（Q1 PP&E 净值 $185.1B；Q2 $203.2B；Q3 $223.8B） | EDGAR / abc.xyz/investor | Q1 2025 截至 2025-03-31；Q3 2025 截至 2025-09-30 | L257（GOOG Q1 2025 PP&E 净值 $185.1B，时点为 Mar 31, 2025；FY25 年末数字 data_cutoff 2026-05 时仍按季度滚动披露）|
| S23 | Meta Q2 2022 10-Q（服务器 4 → 4.5 年） | EDGAR 0001326801-22-000023 | 2022-07-27 报送 | L269（Meta Q2 2022 折旧变化）|
| S24 | Meta Q4 2022 10-K（服务器 4.5 → 5 年） | EDGAR 0001326801-23-000013 | 2023-02 报送 | L270（Meta Q4 2022 折旧变化）|
| S25 | Meta Q4 2024 财报新闻稿（服务器 + 部分网络资产 5 → 5.5 年） | investor.atmeta.com | 2025-01-29 | L271（Meta 2025-01-29 折旧变化 + FY25 D&A 减 $2.9B）|
| S26 | Meta FY25 10-K（PP&E 净值 $176.4B + FY25 CapEx ~$72B） | EDGAR / investor.atmeta.com | FY25（截至 2025-12-31）2026-Q1 报送 | L50（META FY25 CapEx ~$72B）/ L257（META FY25 年末 PP&E 净值 $176.4B）|
| S27 | Amazon FY23 10-K（服务器 5 → 6 年；2024-02 披露） | EDGAR / amazon.com/ir | 2024-02 报送 | L272（AMZN Q4 2023 / FY24 起 5→6 年）|
| S28 | Amazon FY24 10-K（服务器 6 → 5 年部分资产；2025-02 披露） | EDGAR / amazon.com/ir | 2025-02 报送 | L273（AMZN Q4 2024 / FY25 起 6→5 年部分；FY25 营业利润减 ~$0.7B）|
| S29 | Amazon Q4 2024 earnings call transcript（Brian Olsavsky CFO 表态） | seekingalpha.com 2025-02-06 + amazon.com/ir | 2025-02-06 | L284（Olsavsky 反向折旧公开理由）|
| S30 | Amazon FY25 10-K（PP&E 净值 $357.0B + FY25 CapEx $131.8B） | EDGAR / amazon.com/ir | FY25（截至 2025-12-31）2026-Q1 报送 | L50（AMZN FY25 CapEx $131.8B）/ L257（AMZN FY25 年末 PP&E 净值 $357.0B）|
| S31 | CoreWeave S-1 / IPO 招股书 | EDGAR / coreweave.com/investors | 2025-03 | L275（CoreWeave technology equipment 6 年折旧）/ L98-99（NVL36/72 + managed cluster 口径）|
| S32 | CoreWeave Q3 2025 8-K（FY25 Q3 营收 $1,364.7M + Backlog $55.6B + 220K 卡业内估算口径） | EDGAR / coreweave.com/investors | 2025-11-10 报送 | L118（Q3 营收 $1,364.7M）/ L120（220K 卡业内估算反推）/ L498（Backlog $55.6B + OpenAI $22.4B / 5 年）|
| S33 | CoreWeave 2026-02 Meta 合同抵押融资公告（$8.5B）| coreweave.com/news + 综合报道 | 2026-02 | L498（用 Meta 合同抵押拿 $8.5B 融资）|
| S34 | Nebius IR 折旧政策（4 年） | nebius.com/investors + Bizety 2025-09 综合 | 2024-10 重新上市后 | L276（Nebius 4 年）/ L286（Adjusted EBITDA margin 对比）|
| S35 | Oracle (OCI) 折旧政策变化（5 → 6 年 CY23Q1） | Bizety 2025-09 综合（Oracle 一手未单独披露） | CY23Q1 | L274（Oracle 折旧政策时点）|
| S36 | NVIDIA FY25Q4 财报新闻稿（数据中心营收 +93% YoY） | nvidianews.nvidia.com + EDGAR | 2025-02-26 | L524（NVDA FY25Q4 数据中心营收同比 +93%）|
| S37 | NVIDIA FY25Q4 财报电话会 transcript（FY25Q4 数据中心 $35.6B 等绝对数）| seekingalpha.com 2025-02-26 + nvidianews | 2025-02-26 | L524 辅助交叉口径 |
| S38 | DeepSeek API Docs（R1 首发价 $0.07 / $2.19；后续调价 cache miss $0.55 / cache hit $0.14）| api-docs.deepseek.com/news/news250120 | 2025-01-20 首发 + 2026-05 当前价 | L46 / L439 / L510（DeepSeek-R1 首发价 + 2026-05 当前价口径）|
| S39 | DeepSeek-R1 论文（arXiv:2501.12948） | arxiv.org/abs/2501.12948 | 2025-01-22 | L508-512（R1 推理性能与 OpenAI o1 接近的实证支撑）|
| S40 | DeepSeek-V3 论文（arXiv:2412.19437） | arxiv.org/abs/2412.19437 | 2024-12-26 | L438（DeepSeek-V3 模型背景）|
| S41 | OpenAI API Pricing 历史页面 | openai.com/api/pricing/ + web.archive.org/web/* | 2023-03 至 2026-05 各档历史定价快照 | L46 / L428-441（GPT-4 / GPT-4 Turbo / GPT-4o / GPT-4o mini / GPT-4.1 nano）/ L510（OpenAI o1 $15/$60）|
| S42 | Anthropic API Pricing 历史页面 | anthropic.com/pricing + web.archive.org/web/* | 2024-03 至 2026-05 各档 | L435-437（Claude 3 Opus / Claude 3.5 Sonnet / Claude Sonnet 4.5）|
| S43 | PJM Base Residual Auction 结果（2025/2026 + 2026/2027 BRA 容量价格）| pjm.com/markets-and-operations/rpm | 2024-07 + 2025-07 | L532（PJM 容量市场两年跳涨 11 倍）|
| S44 | Crusoe Energy 2025-03-18 新闻稿 / GlobeNewswire（Abilene 园区规划总容量 1.2GW，扩容公告） | globenewswire.com/news-release/2025/03/18/3044956 + crusoe.ai/news + Data Center Frontier 2025 综合 | 2025-03-18 | L48（Crusoe Abilene 1.2GW 园区总规划；首批两栋建筑约 200MW）|

## 二手来源 / 行业报告

| 编号 | 来源 | 用于段落（L 行号近似）| 是否已回溯一手 |
|------|------|---------|--------------|
| T1 | Stanford AI Index 2025（HAI） | hai.stanford.edu/ai-index/2025-ai-index-report | 训练成本 + per-token 价格曲线辅助 | 部分（指向 Epoch AI / OpenAI 等一手） |
| T2 | Epoch AI《Can AI scaling continue through 2030》| epochai.org/blog/can-ai-scaling-continue-through-2030 | 2024-08 | L42 / L70（GPT-4 2e25 FLOP 与 2030 年 2e29 FLOP 上限估算）| 部分（指向各家训练披露 + 公开论文综合） |
| T3 | Epoch AI《Training Compute of Frontier AI Models Grows by 4-5x per Year》| epochai.org/blog/training-compute-of-frontier-ai-models-grows-by-4-5x-per-year | 2024-05 | L679（前沿训练算力 2010-2024 年化 4-5×）| 一手指数（Epoch AI 自建数据库） |
| T4 | Epoch AI Compute Trends 系列 + Inference Price Trends | epochai.org/data | 2024-2026 各期 | L426-441（per-token 价格曲线综合）/ L522（2025 推理 token 调用总量涨 50× 量级）| 一手指数（Epoch AI 自建） |
| T5 | Silicon Data H100 Long-term Contract Index 2024-2026 | silicondata.com（Compute Exchange 母公司）| 2024-2026 月度 | L44（H100 长合约价 $2.35/h）/ L99 / L304 / L401-410（H100 GPU-hour 价格表）/ L348（H100 二手价 70%+ 跌幅）| 一手指数（Silicon Data 自有交易数据）|
| T6 | Silicon Data H100 Spot / Rental Index | silicondata.com / Compute Exchange | 2024-2026 月度 | L92-99（compute-only / bare-metal / NVL36 / managed cluster 四档口径）/ L401-410 现货价行 | 一手指数 |
| T7 | Compute Exchange 二手 GPU 拍卖价 / 二级市场参考 | computeexchange.com | 2026 各期 | L348（H100 二手价综合）| 一手交易数据 |
| T8 | SemiAnalysis AI Server Cost / H100 Teardown | semianalysis.com（部分付费）| 2024-2025 | L302（H100 SXM5 整机 $32K 摊销口径）| 一手 teardown |
| T9 | Silicon Analysts AI Server Cost Database 2025 | siliconanalysts.com | 2025 | L61 / L302（单整机 $32K per GPU 综合）| 一手 BOM 数据库 |
| T10 | CBRE《North America Data Center Trends》2024-2025 | cbre.com/insights/reports | 2024-2025 | L61（数据中心建设成本 $10-13M/MW 基准）| 一手行业调研 |
| T11 | JLL《Global Data Center Outlook》2024-2025 | jll.com/en/trends-and-insights | 2024-2025 | L61（数据中心建设成本基准交叉源）| 一手行业调研 |
| T12 | theCUBE Research《GPU Value Cascade》框架 | siliconangle.com / thecuberesearch.com | 2025 | L343（Year 1-2 训练 / Year 3-4 高端推理 / Year 5-6 batch 推理 阶梯框架）| 二手分析 |
| T13 | Bizety《Data Center Depreciation Schedules》综合 | bizety.com | 2025-09 | L274 / L276（Oracle / Nebius 折旧期综合）| 二手汇编 |
| T14 | The Register《Microsoft / Meta / Amazon 折旧期变化》系列 | theregister.com | 2022-08-02 / 2024-02-02 / 2025-02-07 各期 | L267 / L272 / L273（折旧政策时点交叉源）| 二手报道 |
| T15 | Seeking Alpha Amazon Q4 2024 Earnings Call Transcript | seekingalpha.com/article/* | 2025-02-06 | L273 / L284（Olsavsky 表态交叉源）| 二手 transcript 整理（基于 Amazon 一手）|
| T16 | CNBC《Microsoft's mammoth AI bet will lead to over $100 billion in data center leases》| cnbc.com | 2024-10-01 | L322（MSFT FY24 finance lease 超 $100B 披露）| 二手报道（基于 MSFT 一手披露）|
| T17 | CNBC Burry hyperscaler GPU 折旧争议报道 | cnbc.com | 2025-11-11 | L74 / L288 / L347-353（Burry 2-3 年折旧反情景）| 二手报道（基于 Burry X 公开主张）|
| T18 | Fortune Burry 反情景报道（综合 Scion Asset Management 公开主张） | fortune.com | 2025-11-13 | L288 交叉源 | 二手报道 |
| T19 | Lex Fridman Podcast #452 Dario Amodei | youtube.com/@lexfridman | 2024-11 | §5 Jevons 与算力需求弹性背景（间接引用） | 一手访谈 |
| T20 | Menlo Ventures《State of Generative AI》2025 | menlovc.com/perspective/2025-the-state-of-ai-in-business | 2025 | L163（hyperscaler CapEx + 模型层市场规模综合）| 二手调研 |
| T21 | Synergy Research Group Hyperscaler CapEx | srgresearch.com | 2025 | L163（$400-500B AI 算力支出综合）| 二手调研 |
| T22 | IDC AI Spending Guide | idc.com | 2025 | L163（AI 算力支出交叉源）| 二手调研 |
| T23 | The Information AI 产业报道（OpenAI ARR / hyperscaler 合同综合） | theinformation.com | 2025-06 等 | L34（OpenAI ARR $22-25B 口径）/ L510（DeepSeek 影响 OpenAI 付费 token 总量分析背景）| 二手报道 |
| T24 | 综合 2025-01-27 美股盘后报道（NVDA 单日 -$589B 市值）| Bloomberg / Reuters / Yahoo Finance 综合 | 2025-01-27 | L516 / L536（NVDA 单日 -$589B）| 二手综合 |
| T25 | Mag7 hyperscaler 各家季度 / 年度 ARR & CapEx 披露综合（用于 §2.2 估算 + §5 OpenAI 付费 token 反向上涨）| 各家 IR + EDGAR | 2024-2026 滚动 | L163 / L520（付费 token 总量反向上涨综合）| 一手财报混合二手分析 |

## 学术框架与理论锚点（§6-7 主要回引）

| 编号 | 来源 | 用于段落（L 行号近似）|
|------|------|---------|
| A1 | Cobb, C. W. & Douglas, P. H. (1928)《A Theory of Production》AER 18(1)：139-165 | L135-153（Cobb-Douglas 生产函数原形式 + α / β 推论）|
| A2 | Minsky, H. P. (1986)《Stabilizing an Unstable Economy》| L614 / §7（Minsky 三段债务 / 金融不稳定假说 + 主答辩 ch29）|
| A3 | Soros, G. (1987 / 2008) Reflexivity 系列 | L615 / §7（反身性，主答辩 ch30）/ L494-502（反身性裂缝）|
| A4 | Carlota Perez (2002)《Technological Revolutions and Financial Capital》| L644（不进表的理论：Perez 技术经济范式，本章 ch24 / ch32 局部使用）|
| A5 | Coase, R. (1937)《The Nature of the Firm》| L641（不进表的理论：交易成本，ch07 / ch15 局部使用）|
| A6 | Williamson, O. (1985) Hold-up 与不完全合约理论 | L642（不进表的理论：ch05 CoWoS 瓶颈局部使用）|
| A7 | Pisano & Shih (2009)《Restoring American Competitiveness》HBR + 后续书 | L643（不进表的理论：ch01 + ch06 价值切片局部使用）|

## 已知数据缺口（本章相关，无法在 fact-check 阶段补齐的）

- 算力作为生产要素 γ 的精确估算——学术界无定论，本章给三套区间估算并明示"作者推演 + 业内估算"标签；不强行收敛到点估计
- finance lease 与 capital lease 在不同会计准则（US GAAP vs IFRS）下的可比性——给口径注释，不做跨准则换算
- per-token 价格的"含 prompt cache vs 不含"的精确换算——业内估算 30-50% 折扣，不给点估计
- NVIDIA FY26 前 5 大客户占 ~40% 的精确客户名单——NVDA 10-K 仅披露百分比口径，不披露客户名（ch07 主答辩位详谈）
- CoreWeave Q3 2025 平均部署活跃 GPU 量 220K 卡——CoreWeave 不单独披露 GPU 部署数量，本数据由营收 ÷ 加权小时价反推（业内估算）
- $22.4B / 5 年 OpenAI-CoreWeave 合同条款细节——OpenAI 非上市，合同条款仅披露金额 + 期限，不披露年度 take-or-pay 分布

## 引用规范说明

- 每条数据点在正文中按"数据 + 单位 + （来源：S/T 编号或来源全名 + 时点）"格式标注
- 一手数据：S 系列编号，优先引用
- 二手数据：T 系列编号，引用时同步标"待 fact-check 阶段 WebFetch"
- 学术理论：A 系列编号，正文引用作者 + 年份即可
- 业内估算 / 作者推演：明示"业内估算"或"作者推演"，不强行附 URL
- fact-check 阶段：S1-S44 / T1-T25 每条单独 WebFetch 至少一次，比对正文数值与一手原文，结论入 fact-check.yaml
