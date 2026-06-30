# 算力经济学

面向 AI 工程师与 AI 投资者的算力经济学读本。

从一张 H100 出发，把算力产业链（芯片 / 封装 / HBM / 服务器 / 数据中心 / 电力 / 云）与资本周期（一二级市场 / 估值 / CapEx 周期）串成一张全景图。

## 这本书写给谁

- AI 工程师，每天在用 GPU 但想看清自己工作所在的产业位置
- AI 投资者（股票为主，也包括少量一级），需要把技术叙事翻译成可建模的财务 / 产业框架
- 财经记者、产业研究员，想要技术细节足够准确但又不掉书袋的读本
- 行业从业者（云、IDC、芯片）想要看跨环节的全景

## 这本书不写什么

- 不做选股建议、不做操作策略
- 不是 AI / 半导体的入门科普
- 不主打政策解读 / 地缘博弈

## 数据时效基准

数据截止 **2026 年 5 月**。每个数据点会单独标具体时点，发布后会维护更新日志。

## 怎么读

- **快速上手**：读序章 + 第 1 章（H100 旅程） + 第 29 章（周期定位）
- **系统学习**：按目录顺序，8 个部分各成体系
- **只关心估值**：直接看第 7 部（第 29-31 章 估值 / 周期 / 争议论证）+ 各章末「核心结论」

## 目录

**序章**

- [序章　三个不可能的算力故事](book/00-prologue/README.md)

**第一部　总论**

- [第 1 章　一张 H100 的旅程：从沙子到 token 的 BOM](book/01-h100-journey/README.md)
- [第 2 章　算力作为生产要素：定义、计量与三重身份](book/02-compute-as-factor/README.md)

**第二部　产业链全景**

- [第 3 章　上游设备：ASML、应用材料、东京电子的隐形垄断](book/03-upstream-equipment/README.md)
- [第 4 章　晶圆代工：TSMC 的工艺溢价与三家分蛋糕](book/04-wafer-foundry/README.md)
- [第 5 章　CoWoS：被低估的物理瓶颈](book/05-cowos-packaging/README.md)
- [第 6 章　HBM：单卡最贵部件，反共识主战场](book/06-hbm-bottleneck/README.md)
- [第 7 章　加速芯片：NVIDIA 75% 毛利率的护城河拆解](book/07-accelerator-moat/README.md)
- [第 8 章　网络与互连：Broadcom 的隐形 AI 红利](book/08-network-interconnect/README.md)
- [第 9 章　服务器与整柜：8-12% 毛利的脏活与 NVIDIA 的整柜价值收编](book/09-server-rack/README.md)
- [第 10 章　数据中心与电力：钢筋水泥不是瓶颈，电是](book/10-datacenter-power/README.md)

**第三部　因果与机制**

- [第 11 章　双瓶颈：CoWoS 与 HBM 为什么是真紧缺](book/11-bottleneck-physics/README.md)
- [第 12 章　2027 拐点：双瓶颈缓解的节奏与三个预警信号](book/12-2027-inflection/README.md)
- [第 13 章　训-后训-推三段与杰文斯弹性：需求侧的 2027 之后](book/13-jevons-three-stages/README.md)
- [第 14 章　缓解之后：电力与客户集中度成为新硬约束](book/14-post-easing-constraints/README.md)

**第四部　商业模式与盈利结构**

- [第 15 章　三种算力商业模式：自建、长租、转租的会计分野](book/15-three-models/README.md)
- [第 16 章　GPU 云解剖：CoreWeave 60% EBITDA 是怎么算出来的](book/16-gpu-cloud-anatomy/README.md)
- [第 17 章　三大云的算力账本：CapEx、折旧政策、AI 回报路径](book/17-hyperscaler-books/README.md)
- [第 18 章　模型层与循环交易：补贴扩张和 vendor financing 复刻](book/18-circular-deals/README.md)

**第五部　全球格局**

- [第 19 章　美国主导体系：技术、资本、规则的三位一体](book/19-us-trinity/README.md)
- [第 20 章　沿价值链守住中心节点：美国的三类工具与盟友配合](book/20-us-chokepoints/README.md)
- [第 21 章　中国应对：两条线、一个时间差](book/21-china-response/README.md)
- [第 22 章　东亚与欧洲的三难均衡：韩台日欧的对冲策略](book/22-east-asia-europe/README.md)
- [第 23 章　边缘新中心：主权 AI 资本如何重塑算力地图（2025-）](book/23-sovereign-ai/README.md)

**第六部　宏观经济影响**

- [第 24 章　算力作为通用目的技术：与蒸汽、电力、IT 的可比](book/24-gpt-technology/README.md)
- [第 25 章　算力与全要素生产率：宏观证据与微观渠道](book/25-tfp-channels/README.md)
- [第 26 章　算力与人力资本：自动化、增强、位移三种机制](book/26-human-capital/README.md)
- [第 27 章　算力与电力市场：变压器、PJM、长期 PPA 与政治回压](book/27-power-market/README.md)
- [第 28 章　出口管制与脱钩的经济账：三套口径下的双边成本](book/28-export-controls/README.md)

**第七部　周期与资本市场**

- [第 29 章　周期定位：12 维度对照、三个预警、五个差异](book/29-cycle-positioning/README.md)
- [第 30 章　五种估值模板：详略主次明确](book/30-valuation-templates/README.md)
- [第 31 章　12 个争议的论证：可证伪条件五段式](book/31-disputes-defense/README.md)

**第八部　前瞻**

- [第 32 章　五年之后：电力、HBM、客户集中度三不变量](book/32-five-years-after/README.md)

**附录**（待补，正文文件尚未写入仓库）

- 附录 A　数据源黄页
- 附录 B　数据时效维护机制
- 附录 C　术语表（中英对照）
- 附录 D　评论免责说明

## 开源仓库

- GitHub: https://github.com/diguike/book-compute-economics
- 在线阅读：[inferloop.dev](https://inferloop.dev)

## 反馈

发现错误或希望补充哪一块，欢迎在 GitHub 提 issue、飞书评论或邮件联系。
