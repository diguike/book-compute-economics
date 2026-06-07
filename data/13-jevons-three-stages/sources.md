# Sources — 第 13 章 训-后训-推三段与杰文斯弹性：需求侧的 2027 之后

## 一手来源

| 编号 | 来源 | URL / 文档 | 用于章节段落 |
|------|------|-----------|------------|
| S1 | OpenAI o1 / o3 系统报告（system card）+ 技术博客 | https://openai.com/research/ | 13.3 |
| S2 | Anthropic Constitutional AI / Claude 3.5/3.7 公开论文 + 博客 | https://www.anthropic.com/research | 13.3 |
| S3 | DeepSeek R1 / R1-Zero / V3 论文 | arXiv 2025-01 | 13.3、13.5 |
| S4 | Google Gemini 2.5 技术报告 | https://deepmind.google/ | 13.3 |
| S5 | OpenAI / Anthropic / Google / DeepSeek API 公开价目（历史快照，含 DeepSeek API Docs news250120 = R1 首发价 cache miss $0.55 / cache hit $0.14 / output $2.19） | 各厂 pricing 页 + Web Archive + api-docs.deepseek.com | 13.1、13.6 |
| S6 | Brynjolfsson 学术系列（J-curve、生产力悖论、AI 影响测算）：Brynjolfsson & Hitt 2000 "Beyond Computation" *JEP* 14(4) + Brynjolfsson, Rock, Syverson 2018 NBER WP 25148 / 2021 *AEJ:Macro* 13(1) + Brynjolfsson, Li, Raymond 2023 NBER WP 31161 | NBER / JEP / AEJ:Macro | 13.7 |
| S7 | Jevons《The Coal Question》1865 + 现代弹性研究 | 原典 + Sorrell 等综述 | 13.5 |
| S8 | Acemoglu-Restrepo task-based 框架（与 ch02、ch26 共享） | NBER / Acemoglu 个人页 | 13.5（伏笔指向 ch26） |

## 二手来源

| 编号 | 来源 | 用于段落 | 是否已回溯一手 | 备注 |
|------|------|---------|--------------|------|
| T1 | Epoch AI 训练 + 推理算力测算与数据库 | 13.3、13.4、13.6、13.8 | 部分（学术性） | 与一手论文交叉 |
| T2 | Stanford AI Index 2025-2026 | 13.6、13.8 | 部分 | — |
| T3 | Menlo Ventures 企业 AI 报告（State of AI in the Enterprise） | 13.5、13.8 | 部分（调研） | 标口径 |
| T4 | Gartner / Forrester 企业 AI 预算渗透 | 13.5、13.8 | 部分 | — |
| T5 | McKinsey AI Compute Outlook（2024-2025 系列） | 13.4 | 部分（建模） | 与 Epoch AI 对照 |
| T6 | The Information / Reuters 关于 Cursor / Replit / Anthropic / OpenAI 补贴的报道 | 13.6（伏笔指向 ch18） | 部分 | 不作为唯一来源 |
| T7 | Morgan Stanley / Goldman Sachs / Bernstein 训推比例预测 | 13.4 | 部分 | 与一手交叉 |
| T8 | Cursor / Replit / Lovable 公开博客 + Founder 访谈 | 13.6 | 部分 | — |

## 已知数据缺口（按"业内估算 / 无法验证"标）

1. **后训练算力占比量化**：OpenAI / Anthropic 仅给定性描述，**按 Epoch AI + 论文反推 + 标"业内估算"**。
2. **企业 AI 预算渗透率**：调研性数据（Menlo / Gartner），**按调研口径标**。
3. **Cursor / Replit / Lovable 等工具补贴金额**：私有公司，**仅有 The Information 等媒体披露**，主战场留 ch18。
4. **McKinsey vs Epoch 训推比例的口径差异**：必须严格还原两方对"后训练"如何归类。
5. **per-token 价格 99% 跌幅**：基于公开 pricing 历史快照，**口径要明确**（同模型 vs 跨模型、同时点 vs 跨时点）。
6. **模型公司真实 ARR（剔除补贴和循环）**：主战场在 ch18，本章只给伏笔。
7. **DeepSeek R1 RL 阶段 GPU-hour**：DeepSeek R1 论文未直接披露 RL 阶段算力；业内反推区间 5-40%（V3 前训练比），差异来自 MFU 假设。Epoch AI "What went into training DeepSeek-R1" 2025 在 MFU 同档假设下估计约 $1M / ~200K-400K GPU-hour，本章已按此区间标注。
8. **AI 推理总支出 $2B/月 的加权口径**：表格 per-token 价格列取的是同档低价锚点（$0.14），不能直接乘总 token 量。本章 §13.6 已补加权说明（混合定价加权平均约 $0.40-0.60/1M，与 5000T tokens/月相乘得 $2-3B/月）。

## 数据采集时点

- 最后一次更新：2026-05
- 论文 / 公开博客截止：2026-04
- API pricing 历史快照：Web Archive 多时点
- 全章 data_cutoff：2026-05

## 与其他章联动

- ch02 算力作为生产要素 → 本章经济学锚点（Jevons / Brynjolfsson）的章末理论锚点速查表索引位
- ch12 2027 拐点 → 本章是 ch12 的需求侧对偶
- ch14 缓解之后 → 本章三段需求场景是 ch14 客户集中度反身性的输入
- ch18 模型层与循环交易 → 本章模型公司 ARR 增长是 ch18 剔除循环 ARR 的输入
- ch24 算力作为 GPT → 本章 Brynjolfsson J-curve 是 ch24 GPT 三判据的伏笔
- ch25 算力与 TFP → 本章 J-curve 在 ch25 微观渠道测算共享
- ch29 周期定位 → 本章 18-36 月杰文斯窗口是 ch29 周期阶段判断的需求侧输入
- ch31 12 议题答辩 → 议题 5、6 主答辩位
- ch32 五年之后 → 本章三套需求场景与 ch32 情景模型衔接
