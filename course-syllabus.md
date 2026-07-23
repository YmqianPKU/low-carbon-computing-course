# 低碳算力服务系统智能优化 — 暑期在线自学课程大纲（增补版）

> **课程主题**：低碳算力服务系统智能优化  
> **总学时**：40 小时  
> **学习周期**：建议 5 周（每周 8 学时）  
> **课程形式**：在线自学（视频课程 + 阅读材料 + 实践项目）  
> **编制日期**：2026-07-22  
> **增补日期**：2026-07-22（补充视频课程、前沿学者/论文/期刊/机构、跨学科研究方向）  

---

## 课程简介

在国家人工智能发展战略与"双碳"目标深度交汇的时代背景下，构建高效、绿色、可控的算力基础设施已成为关乎国家数字主权与AI产业国际竞争力的核心议题。本课程设置五个模块，从理论、方法、机制到安全实现全链条覆盖，旨在培养学习者对低碳算力服务系统的综合理解和工程实践能力。

---

## 模块一：分布式智能优化理论（8 学时）

### 学习目标
掌握异构计算环境下算力资源的协同配置与优化调度的核心理论与算法。

### 学习内容

| 章节 | 内容要点 | 学时 |
|------|---------|------|
| 1.1 分布式系统基础 | 分布式计算概念、CAP定理、一致性与容错、分片与复制 | 1.5 |
| 1.2 异构计算架构 | CPU/GPU/FPGA/NPU 混合架构、算力特征建模、性能评估指标 | 1.5 |
| 1.3 资源调度算法 | 启发式算法（贪心、遗传、模拟退火）、多目标优化（NSGA-II、MOPSO）、强化学习调度 | 2 |
| 1.4 分布式协同优化 | 并行进化算法框架、分布式差分进化、协同调度机制 | 1.5 |
| 1.5 实践项目 | 基于 Kubernetes 的 GPU 资源调度实验 | 1.5 |

### 推荐学习资源

**视频课程**
- MIT 6.5840（原 6.824）: Distributed Systems（Spring 2026）
  - 课程主页：https://pdos.csail.mit.edu/6.824/
  - B站（2020春中文字幕）：https://www.bilibili.com/video/BV1iD4y1U7gu/
  - B站（经典版）：https://www.bilibili.com/video/BV1kt411v7Rp/
  - 备注：MIT 经典分布式系统课程，涵盖 MapReduce、Raft、GFS、Spanner 等，含 5 个 Go 语言 Lab
- **Coursera — Foundations of Distributed Database Systems**
  - 链接：https://www.coursera.org/learn/foundations-of-distributed-database-systems
  - 备注：涵盖分布式数据库架构、水平/垂直分区、查询优化与一致性协议，中级课程，持续开课
- **Coursera — Cloud Computing Specialization (University of Illinois)**
  - 链接：https://www.coursera.org/specializations/cloud-computing
  - 备注：伊利诺伊大学云计算专项课程，含分布式系统、MapReduce、一致性协议等模块
- **edX — MIT 6.5840 (原 6.824) Lab 资源仓库**
  - GitHub：https://github.com/chaozh/MIT-6.824
  - 备注：MIT 分布式系统课程 Lab 完整实现参考（Go 语言），含 Raft、分片 KV 等
- **B站 — 分布式系统架构实战教程（26讲）**
  - 链接：https://www.bilibili.com/video/BV165411P7ba/
  - 备注：涵盖 Redis+Dubbo+ZooKeeper 分布式架构实战，适合工程实践补充

**阅读材料**
- 《Designing Data-Intensive Applications》by Martin Kleppmann（免费英文版：https://dataintensive.net/）
- 异构计算资源调度优化综述：https://www.docin.com/p-4762613510.html
- 分布式计算与资源调度教学课件：https://max.book118.com/html/2025/0322/5203043011012122.shtm
- IDEC: 智能分布式边缘计算系统架构（知乎）：https://zhuanlan.zhihu.com/p/431786289

**GitHub 实践资源**
- MIT 6.5840 Lab 代码参考（2023版）：https://github.com/ToniXWD/MIT6.5840
- MIT 6.5840 Lab 实现（含笔记）：https://github.com/casey-li/MIT6.5840
- MIT 6.824/6.5840 完整实验仓库：https://github.com/PeterHUistyping/MIT6.824-6.5840-Distributed-Systems

### 进度要求
- **第 1 周**：完成全部 1.1–1.5 内容学习
- 交付物：提交一份异构资源调度方案设计文档（含算法选择理由和预期性能分析）

---

## 模块二：低碳算力服务系统演化规划（8 学时）

### 学习目标
学会利用多源异构数据支撑算力系统的布局规划、容量配置与动态演进决策。

### 学习内容

| 章节 | 内容要点 | 学时 |
|------|---------|------|
| 2.1 算力网络体系架构 | 算力网络三层架构（算力层·网络层·服务层）、云-边-端协同、算网大脑 | 1.5 |
| 2.2 绿色算力发展态势 | 绿色算力 ELII 框架（高效·低碳·智能·集约）、PUE 指标体系、全生命周期评价 | 1.5 |
| 2.3 系统布局优化 | "东数西算"枢纽节点布局、多源异构数据融合、空间-时间耦合规划 | 2 |
| 2.4 容量配置与动态演进 | 需求预测模型、弹性容量规划、算力设施分阶段建设、演进路径设计 | 2 |
| 2.5 实践项目 | 基于公开数据的城市级算力中心选址与容量规划案例分析 | 1 |

### 推荐学习资源

**报告与白皮书**
- 中国信通院《绿色算力技术创新研究报告(2024年)》
  - 链接：https://www.docin.com/p-4635038308.html
  - 备注：设施层·设备层·平台层技术创新全景
- 中国信通院《算力电力协同发展研究报告(2025年)》
  - 链接：https://www.sohu.com/a/893800836_121649899
  - 备注：算力电力协同发展阶段、要素与路径系统梳理
- 《2024国家"东数西算"枢纽节点绿色算力指数研究报告》
  - 链接：https://www.sohu.com/a/795065369_121852023
  - 备注：各枢纽节点绿色算力发展水平量化评估
- 《数据中心全生命周期绿色算力指数白皮书 2024》
  - 链接：https://www.sohu.com/a/797328388_121656383
  - 备注：全生命周期绿色算力指数体系与测算方法
- 《算网能一体化白皮书(2024版)》— 中国电力工程顾问集团 & 紫金山实验室
  - 链接：https://max.book118.com/html/2024/1226/7042015134010013.shtm
  - 备注：算网与能源协同创新参考架构
- 《绿色计算产业发展白皮书(2024版)》
  - 链接：https://www.sohu.com/a/849260667_121734021
  - 备注：绿色计算产业空间与技术趋势
- 清华大学&火山引擎《算力电力协同：思路与探索白皮书(2025年)》
  - 链接：https://max.book118.com/html/2025/0221/5112004001012103.shtm
  - 备注：郭庆来团队撰写，算电协同微观-中观-宏观三层框架

**延伸阅读**
- 算力网络演进与生态应用创新：https://blog.csdn.net/tiangang2024/article/details/146348322
- 算力网络架构演进的思考（新华三）：https://blog.csdn.net/weixin_45882672/article/details/149910951
- 北京大学宋洁教授：AI大模型如何实现算力低耗能：https://bda.pku.edu.cn/info/1024/3192.htm

### 进度要求
- **第 2 周**：完成全部 2.1–2.5 内容学习
- 交付物：提交一份区域算力设施布局与演进规划报告

---

## 模块三：算力-电力协同优化调度（8 学时）

### 学习目标
理解多主体参与下算力、能源与碳排放的协同优化机制，掌握算电协同调度模型。

### 学习内容

| 章节 | 内容要点 | 学时 |
|------|---------|------|
| 3.1 算电协同基础 | 算力能耗现状（数据中心用电占比）、"比特到瓦特"能量转换、PUE 与碳排因子 | 1.5 |
| 3.2 源网荷储一体化 | 绿电直供模式、配电网绿电消纳、园区级源网荷储一体化项目案例 | 1.5 |
| 3.3 多主体协同优化 | 算力节点与电力节点融合模型、多时空尺度调度、双向协同优化策略 | 2 |
| 3.4 碳排放协同管理 | 碳足迹追踪、碳电一体化机制、绿电证书与碳交易市场 | 1.5 |
| 3.5 实践项目 | 算力-电力协同调度仿真实验（基于公开数据集） | 1.5 |

### 推荐学习资源

**报告与文章**
- "算电协同"助力算力中心绿色低碳发展的实践与思考
  - 链接：http://k.sina.com.cn/article_5953466437_162dab0450670ao1xi.html
  - 备注：国内典型算电协同实践案例
- 算力电力节点可调节资源的双向协同优化调度（学术论文）
  - 链接：https://max.book118.com/html/2025/0224/7150130135010040.shtm
  - 备注：系统架构设计、资源模型、调度模型详解
- 南方电网电碳算协同运营系统发布报道
  - 链接：https://new.qq.com/rain/a/20250829A05N2500
  - 备注：电碳算协同运营的最新产业实践
- 算力与电力如何协同优化（北极星电力网）
  - 链接：https://news.bjx.com.cn/html/20250319/1432801.shtml
  - 备注：算电协同的基本关系与挑战
- AI算力网络中的绿色节能调度算法（CSDN专栏）
  - 链接：https://download.csdn.net/blog/column/12557265/149415847
  - 备注：智能感知·多目标优化·分布式协同技术栈
- 绿色算力网络构建与智能调度实践
  - 链接：https://blog.csdn.net/tiangang2024/article/details/146188148
  - 备注：异构计算集群、跨区域网络互联、能耗监测平台
- 国网冀北电力《2024年人工智能快速发展背景下算力电力协同发展的思考报告》
  - 链接：https://www.sohu.com/a/845803026_121735625
  - 备注：岳昊专家团队，含京津冀算力负荷精准识别与调度协同案例
- 2025算电协同发展论坛纪实
  - 链接：https://new.qq.com/rain/a/20251216A02S3F00
  - 备注：能源调度与算力调度双向协同最新产业实践

**延伸阅读**
- 算电协同核心技术逻辑拆解：https://blog.csdn.net/EAlReport/article/details/161227373
- 绿色革命：算力与电力如何共舞实现双碳梦想：https://www.xianjichina.com/special/detail_555140.html

### 进度要求
- **第 3 周**：完成全部 3.1–3.5 内容学习
- 交付物：提交一份算电协同调度方案设计书（含数学模型描述）

---

## 模块四：算力服务市场机制设计（8 学时）

### 学习目标
掌握构建高效、公平、低碳导向的跨域算力交易与激励机制的理论与方法。

### 学习内容

| 章节 | 内容要点 | 学时 |
|------|---------|------|
| 4.1 博弈论基础 | 纳什均衡、Stackelberg博弈、拍卖理论、机制设计原理 | 2 |
| 4.2 算力定价机制 | 成本维度（固定/可变/机会成本）、需求维度（QoS·优先级）、动态定价策略 | 1.5 |
| 4.3 算力交易架构 | 算力网络交易平台设计、多资源双向拍卖、可信交易保障、声誉评估模型 | 2 |
| 4.4 激励机制设计 | 代币激励、信誉机制、贡献度评估、公平性与可扩展性原则 | 1.5 |
| 4.5 实践项目 | 基于博弈论的算力交易机制仿真设计 | 1 |

### 推荐学习资源

**视频课程**
- **Coursera — Game Theory (Stanford & UBC)**
  - 链接：https://www.coursera.org/learn/game-theory-1
  - 讲师：Matthew O. Jackson (Stanford)、Kevin Leyton-Brown、Yoav Shoham (UBC)
  - 讲师主页：https://www.coursera.org/instructor/jacksonm
  - 备注：Coursera 持续开课的博弈论经典课程，涵盖纳什均衡、扩展式博弈、贝叶斯博弈、重复博弈等，已注册学习者超 10 万
- **Coursera — Game Theory II: Advanced Applications (Stanford & UBC)**
  - 链接：https://www.coursera.org/learn/game-theory-2
  - 备注：博弈论进阶课程，重点讲解社会选择、**机制设计**、拍卖理论，与模块四核心高度匹配
- **B站 — 斯坦福博弈论 II: 高级应用（中英字幕）**
  - 链接：https://www.bilibili.com/video/BV1W34y1F7tt/
  - 备注：Coursera Game Theory II 的 B站搬运版，含机制设计与拍卖理论章节
- **Coursera — Business Economics and Game Theory for Decision Making (Illinois Tech)**
  - 链接：https://www.coursera.org/learn/illinois-tech-business-economics-and-game-theory-for-decision-making
  - 备注：伊利诺伊理工商业博弈论课程，侧重决策应用，含市场弹性与定价策略
- **Coursera — Tim Roughgarden 算法博弈论**
  - 讲师学术主页：http://theory.stanford.edu/~tim/
  - Coursera 讲师页：https://www.coursera.org/instructor/~768
  - 备注：斯坦福教授，《Twenty Lectures on Algorithmic Game Theory》作者，机制设计领域权威
- **算法博弈论二十讲（中文版笔记）**
  - 知乎专栏：https://zhuanlan.zhihu.com/p/187527902
  - CSDN笔记：https://blog.csdn.net/weixin_44251455/article/details/141329069
  - 备注：Tim Roughgarden 著作中文学习笔记，涵盖迈尔森引理、机制设计、多参数机制设计

**阅读材料**
- 算力100问第86问：算力定价机制应该如何设计？
  - 链接：https://blog.csdn.net/bjdx_001/article/details/146205190
  - 备注：定价目标·因素·策略·模型全梳理
- 算力网络多方资源共享机制：算力交易
  - 链接：https://blog.csdn.net/qq_38998213/article/details/143649205
  - 备注：交易平台设计、声誉评估、Stackelberg博弈、拍卖理论
- 基于区块链的算力网络交易机制研究
  - 链接：https://www.docin.com/p-4790721955.html
  - 备注：多资源双向拍卖算法、MCMF组合调度
- AI算力网络激励机制设计原理解析
  - 链接：https://download.csdn.net/blog/column/12557265/149239183
  - 备注：博弈论视角的激励设计核心逻辑
- 算力100问第51问：算力电力协同市场机制怎么运作？
  - 链接：https://blog.csdn.net/bjdx_001/article/details/145572716
  - 备注：算力市场与电力市场融合运作机制

### 进度要求
- **第 4 周**：完成全部 4.1–4.5 内容学习
- 交付物：设计一个低碳导向的算力交易机制方案（含激励模型和公平性分析）

---

## 模块五：低碳算力服务系统动态安全管理（8 学时）

### 学习目标
掌握数据隐私保护、算法鲁棒性、系统安全与基础设施韧性的核心技术与评估方法。

### 学习内容

| 章节 | 内容要点 | 学时 |
|------|---------|------|
| 5.1 数据隐私保护 | 同态加密、差分隐私、安全多方计算（MPC）、联邦学习隐私机制 | 2 |
| 5.2 算法鲁棒性 | 对抗样本攻击与防御、模型剪枝/蒸馏的安全性、动态参数激活鲁棒性分析 | 1.5 |
| 5.3 系统安全机制 | 加密协议（SSL/TLS、IPSec）、智能合约安全、区块链可信交易、零信任架构 | 2 |
| 5.4 基础设施韧性 | AI 韧性评估模型、容错机制、灾备恢复、供应链安全 | 1.5 |
| 5.5 实践项目 | 算力服务系统安全评估与韧性提升方案设计 | 1 |

### 推荐学习资源

**视频课程**
- **蚂蚁隐语隐私计算实训营（B站系列课程，2024-2025年持续更新）**
  - 第3讲：详解隐私计算框架及技术要点：https://www.bilibili.com/video/BV1dJ4m1b7AX/
  - 第4讲：隐语 SecretFlow/SecretNote 安装与使用：https://www.bilibili.com/video/BV1Hw4m1e7CA
  - 联邦学习第5课：基于隐私保护的机器学习算法：https://blog.csdn.net/weixin_43427267/article/details/140560752
  - 实训营社区：隐语 · 实训社区
  - GitHub：https://github.com/secretflow/secretflow
  - 备注：蚂蚁集团开源隐私计算框架 SecretFlow 系列实训课程，涵盖 MPC、联邦学习、同态加密、差分隐私、PSI/PIR 等，2024年起持续开课
- **联邦学习框架 FederatedScope 实战（B站）**
  - 链接：https://www.bilibili.com/video/BV1NB4y1v7ek/
  - 备注：事件驱动联邦学习框架，含隐私保护技术讲解

**阅读材料**
- 算力网络：安全与隐私保护技术专题报告
  - 链接：https://doc.mbalib.com/view/15ea62572bb2da4bce6c8b1743bd0269.html
  - 备注：加密算法·协议·算力网络安全全面综述
- AI算力网络与通信隐私计算安全机制解析
  - 链接：https://download.csdn.net/blog/column/12557265/149209192
  - 备注：联邦学习·同态加密·安全多方计算·通信隐私保护
- 隐私计算与联邦学习安全：从同态加密到差分隐私的实战指南
  - 链接：https://cloud.tencent.com/developer/article/2590468
  - 备注：端到端安全防线技术栈与代码实战
- AI韧性：AI安全的革命性基准模型（MBA智库）
  - 链接：https://doc.mbalib.com/view/9532e6327a26108098caf0f91732c96a.html
  - 备注：基于进化论的AI韧性评分标准与基准测试模型
- 面向联邦学习的隐私保护算法全面剖析
  - 链接：https://www.docin.com/p-4844106367.html
  - 备注：安全多方计算·同态加密·差分隐私·零知识证明系统梳理

**GitHub 实践资源**
- PySyft — 隐私保护机器学习库（联邦学习 + 差分隐私 + MPC）
  - 链接：https://github.com/OpenMined/PySyft
  - 备注：支持 PyTorch/TensorFlow，含完整教程文档
- Federated-Learning-with-Differential-Privacy
  - 链接：https://github.com/Yangfan-Jiang/Federated-Learning-with-Differential-Privacy
  - 备注：基于 PyTorch 的差分隐私联邦学习框架实现
- 差分隐私联邦学习实战 Jupyter Notebook
  - 链接：https://github.com/gitgik/differential-privacy-federated-learning
  - 备注：含完整代码示例，适合动手学习

### 进度要求
- **第 5 周**：完成全部 5.1–5.5 内容学习
- 交付物：提交一份算力服务系统安全评估报告（含威胁模型和韧性提升建议）

---

## 学习进度总览

| 周次 | 模块 | 学时 | 核心交付物 |
|------|------|------|-----------|
| 第 1 周 | 模块一：分布式智能优化理论 | 8 | 异构资源调度方案设计文档 |
| 第 2 周 | 模块二：低碳算力服务系统演化规划 | 8 | 区域算力设施布局与演进规划报告 |
| 第 3 周 | 模块三：算力-电力协同优化调度 | 8 | 算电协同调度方案设计书 |
| 第 4 周 | 模块四：算力服务市场机制设计 | 8 | 低碳算力交易机制方案 |
| 第 5 周 | 模块五：低碳算力服务系统动态安全管理 | 8 | 系统安全评估报告 |
| **合计** | | **40** | **5 份模块交付物** |

---

## 学习建议

1. **先理论后实践**：每个模块先完成视频课程和阅读材料的理论学习，再开展实践项目
2. **跨模块联动**：模块三（算电协同）与模块四（市场机制）有强关联，建议交叉学习
3. **关注政策动态**：算力领域政策更新快，建议定期关注中国信通院、国家发改委等机构最新发布
4. **动手验证**：模块一的 Kubernetes 调度实验和模块三的仿真实验是核心实操环节，务必动手完成
5. **学术延伸**：如有研究需求，可进一步检索 IEEE TPS、IEEE TPDS、《计算机学报》等期刊相关论文

---

## ★ 增补：前沿学者与研究方向

### 模块一：分布式系统与智能优化

| 学者 | 机构 | 方向 | 主页/链接 |
|------|------|------|----------|
| Robert Morris | MIT | 分布式系统（6.5840课程负责人） | https://pdos.csail.mit.edu/6.824/ |
| Martin Kleppmann | Cambridge | 分布式系统、数据密集型应用 | https://martin.kleppmann.com/ |
| 施巍松 (Weisong Shi) | 韦恩州立大学 | 边缘计算、可持续计算（IEEE Fellow） | https://www.cs.wayne.edu/~weisong/ |
| Adam Wierman | Caltech | 可持续网络系统、数据中心资源管理 | https://www.adamwierman.com/ |

**经典论文**
- Shi, W., et al. "Edge Computing: Vision and Challenges" (2016) — 被引 4000+，边缘计算奠基论文
- Kleppmann, M. "Designing Data-Intensive Applications" (2017) — 分布式系统工程圣经

### 模块二：绿色算力与算力网络

| 学者 | 机构 | 方向 | 主页/链接 |
|------|------|------|----------|
| 高文 | 鹏城实验室/北大 | "东数西算"、中国算力网（中国工程院院士） | 鹏城实验室 |
| 宋洁 | 北京大学 | AI大模型算力低耗能、绿色计算 | https://bda.pku.edu.cn/info/1024/3192.htm |
| 郭庆来 | 清华大学电机系 | 算力电力协同（IEEE/IET Fellow，长江学者） | https://www.eea.tsinghua.edu.cn/faculties/guoqinglai.htm |

**核心报告**
- 郭庆来团队《算力电力协同：思路与探索白皮书(2025)》— 清华大学 & 火山引擎
- 中国信通院《算力电力协同发展研究报告(2025年)》
- 中国信通院《绿色算力技术创新研究报告(2024年)》

### 模块三：算电协同与碳感知计算

| 学者 | 机构 | 方向 | 主页/链接 |
|------|------|------|----------|
| Adam Wierman | Caltech | 碳感知调度、数据中心可持续性 | https://www.adamwierman.com/ |
| 郭庆来 | 清华大学 | 算电协同调度、电网能量管理 | https://www.eea.tsinghua.edu.cn/faculties/guoqinglai.htm |
| 岳昊 | 国网冀北电力 | 算力电力协同规划与调度实践 | 冀北电力专家报告 |

**前沿论文**
- Breukelman, E. et al. "Carbon-Aware Computing in a Network of Data Centers: A Hierarchical Game-Theoretic Approach" (arXiv 2024)
  - 链接：https://arxiv.org/abs/2405.18070
  - 备注：碳感知计算 + 博弈论的跨模块交叉论文
- Microsoft Research "Carbon-aware computing" 白皮书 (2023)
  - 链接：https://news.microsoft.com/wp-content/uploads/prod/sites/418/2023/01/carbon_aware_computing_whitepaper.pdf

**开源工具**
- Green Algorithms Calculator — 剑桥可持续计算实验室
  - GitHub: https://github.com/GreenAlgorithms/green-algorithms-tool
  - 备注：算法碳排放计算器，已发布 v3.0
- Carbon Aware SDK — Microsoft / Green Software Foundation
  - GitHub: https://github.com/Green-Software-Foundation/carbon-aware-sdk
  - 备注：碳感知计算开发工具包，含 API 和 SDK
- Carbon-Aware Computing 平台
  - 链接：https://www.carbon-aware-computing.com/
  - 备注：提供碳感知计算开箱即用工具

### 模块四：机制设计与算法博弈论

| 学者 | 机构 | 方向 | 主页/链接 |
|------|------|------|----------|
| Tim Roughgarden | Columbia (原Stanford) | 算法博弈论、机制设计、Web3 | http://theory.stanford.edu/~tim/ |
| Noam Nisan | Hebrew University | 算法机制设计 | 《Algorithmic Game Theory》合编者 |
| Eva Tardos | Cornell | 算法博弈论、网络博弈 | Cornell CS |

**经典教材与课程**
- Tim Roughgarden《Twenty Lectures on Algorithmic Game Theory》(2016)
  - 中文版笔记：https://zhuanlan.zhihu.com/p/187527902
  - CSDN笔记（含机制设计章节）：https://blog.csdn.net/weixin_44251455/article/details/141329069
- Nisan, Roughgarden, Tardos, Vazirani 编《Algorithmic Game Theory》(2007)
  - DOI: https://doi.org/10.1017/CBO9780511800481

### 模块五：联邦学习与隐私安全

| 学者 | 机构 | 方向 | 主页/链接 |
|------|------|------|----------|
| Virginia Smith | CMU | 联邦学习、差分隐私 | CMU ML Department |
| Robin C. Geyer | — | 差分隐私联邦学习（client-level perspective） | NIPS 2017 论文 |

**经典论文**
- Geyer, R.C., Klein, T., Nabi, M. "Differentially Private Federated Learning: A Client Level Perspective" (NIPS 2017)
  - CSDN解读：https://blog.csdn.net/qq_39715243/article/details/113138060
- Springer "A Differential Privacy Federated Learning Scheme with Improved Noise Perturbation" (2024)
  - 链接：https://link.springer.com/chapter/10.1007/978-981-97-5606-3_6

**开源项目**
- PySyft — 隐私保护ML库（联邦学习 + DP + MPC + 同态加密）
  - GitHub: https://github.com/OpenMined/PySyft
- Federated-Learning-with-Differential-Privacy
  - GitHub: https://github.com/Yangfan-Jiang/Federated-Learning-with-Differential-Privacy
- TensorFlow Privacy — Google 差分隐私库
  - GitHub: https://github.com/tensorflow/privacy

---

## ★ 增补：有影响力的学术期刊与会议

### 核心期刊

| 期刊 | 出版社 | 方向 | 链接 |
|------|--------|------|------|
| IEEE Transactions on Sustainable Computing (T-SUSC) | IEEE | 可持续计算 | ISSN: 2377-3782 |
| IEEE Transactions on Power Systems (TPS) | IEEE | 电力系统调度 | IEEE Xplore |
| IEEE Transactions on Parallel and Distributed Systems (TPDS) | IEEE | 分布式系统 | IEEE Xplore |
| IEEE Transactions on Emerging Topics in Computing | IEEE | 新兴计算技术 | IEEE Xplore |
| IEEE Transactions on Smart Grid | IEEE | 智能电网 | IEEE Xplore |
| Sustainable Computing: Informatics and Systems (SUSCOM) | Elsevier | 可持续计算 | ScienceDirect |
| Journal of Smart Environments and Green Computing (SEG) | IOS Press | 绿色计算 | https://segcjournal.com/ |
| Energy Research & Social Science | Elsevier | 能源跨学科研究 | ScienceDirect |

### 核心会议

| 会议 | 方向 |
|------|------|
| ACM/IEEE Symposium on Edge Computing (SEC) | 边缘计算（施巍松创立） |
| ACM SIGMETRICS | 系统性能评测与建模 |
| NeurIPS | AI/机器学习（含联邦学习方向） |
| ICML | 机器学习（含差分隐私方向） |
| IEEE INFOCOM | 网络与通信 |
| ACM EC (Electronic Commerce) | 机制设计与博弈论 |
| USENIX OSDI / ACM SOSP | 操作系统与分布式系统 |
| ACM FC (Financial Cryptography) | 区块链与加密机制 |

---

## ★ 增补：研究机构与实验室

| 机构 | 方向 | 链接 |
|------|------|------|
| MIT PDOS Lab | 分布式系统 | https://pdos.csail.mit.edu/ |
| Cambridge Sustainable Computing Lab | 绿色算法、可持续计算 | https://github.com/Cambridge-Sustainable-Computing-Lab |
| Caltech Rigorous Systems Lab | 可持续网络系统 | https://www.adamwierman.com/ |
| 清华大学电机系（郭庆来团队） | 算电协同 | https://www.eea.tsinghua.edu.cn/faculties/guoqinglai.htm |
| 中国信息通信研究院（信通院） | 算力政策与技术研究 | http://www.caict.ac.cn/ |
| 鹏城实验室 | 中国算力网、智算基础设施 | https://www.pcl.ac.cn/ |
| 紫金山实验室 | 算网能一体化 | https://www.zjsl.org.cn/ |
| 北京大学大数据科学研究中心 | AI绿色算力 | https://bda.pku.edu.cn/ |
| Green Software Foundation | 碳感知软件开发 | https://greensoftware.foundation/ |
| OpenMined | 隐私保护机器学习开源社区 | https://www.openmined.org/ |
| Microsoft Research — Carbon Aware | 碳感知计算 | https://github.com/microsoft/carbon-aware-sdk |

---

## ★ 增补：跨学科研究方向建议

本课程五大模块本身就处于计算机科学、能源工程、经济学、安全学的交叉地带。以下列出六个值得深入探索的跨学科研究方向：

### 方向一：碳感知算力调度 × 能源经济学
- **核心问题**：如何设计碳电联合市场下的算力调度策略，使碳排放和成本同时最优化？
- **交叉学科**：分布式系统 + 电力市场 + 碳交易机制
- **切入点**：参考 arXiv:2405.18070（Hierarchical Game-Theoretic Approach）的方法论
- **实践路径**：基于 Carbon Aware SDK + 电力市场实时电价数据构建仿真

### 方向二：算力市场机制设计 × 行为经济学
- **核心问题**：算力提供者的策略行为如何影响市场效率和公平性？如何设计激励机制抑制投机？
- **交叉学科**：算法博弈论 + 行为经济学 + 区块链
- **切入点**：Tim Roughgarden 的机制设计理论 + 算力网络多方博弈模型
- **实践路径**：构建 Stackelberg 博弈仿真，验证不同激励策略下的市场均衡

### 方向三：联邦学习 × 电力系统隐私保护
- **核心问题**：算电协同调度中，电力数据和算力负载数据的隐私如何通过联邦学习保护？
- **交叉学科**：隐私计算 + 电力系统 + 分布式优化
- **切入点**：差分隐私联邦学习框架（PySyft）+ 智能电网负荷预测场景
- **实践路径**：用联邦学习训练跨机构电力负荷预测模型，对比集中式训练的隐私风险

### 方向四：边缘计算 × 碳排放生命周期评价（LCA）
- **核心问题**：边缘计算架构相比集中式云，在全生命周期碳排放上是增加还是减少？
- **交叉学科**：计算机系统 + 环境工程 + LCA 方法论
- **切入点**：施巍松边缘计算框架 + Green Algorithms 碳排放计算器
- **实践路径**：对同一AI推理任务，分别测算云端执行和边缘执行的碳足迹

### 方向五：AI韧性工程 × 关键基础设施安全
- **核心问题**：算力基础设施作为国家关键信息基础设施，如何评估和提升其对抗极端事件的韧性？
- **交叉学科**：安全工程 + 系统可靠性 + 供应链管理 + 政策研究
- **切入点**：AI韧性基准模型 + 数据中心灾备恢复案例
- **实践路径**：构建算力基础设施韧性评估框架，涵盖物理层、网络层、服务层

### 方向六：绿色AI算法 × 芯片硬件协同设计
- **核心问题**：如何从算法和硬件协同设计的角度降低AI训练与推理的能耗？
- **交叉学科**：机器学习 + 芯片架构 + 能效优化
- **切入点**：模型压缩（剪枝/蒸馏）+ 异构计算调度 + NPU 能效比优化
- **实践路径**：对比同一模型在不同硬件（GPU vs NPU vs FPGA）上的能效比

---

## 核心参考资源汇总

| 类型 | 资源名称 | 来源 |
|------|---------|------|
| 白皮书 | 绿色算力技术创新研究报告(2024) | 中国信通院 |
| 白皮书 | 算力电力协同发展研究报告(2025) | 中国信通院 |
| 白皮书 | 算力电力协同：思路与探索白皮书(2025) | 清华大学 & 火山引擎 |
| 白皮书 | 东数西算枢纽节点绿色算力指数研究报告 | 中国信通院 |
| 白皮书 | 数据中心全生命周期绿色算力指数白皮书 | 远景科技 |
| 白皮书 | 算网能一体化白皮书(2024) | 中国电力工程顾问集团·紫金山实验室 |
| 白皮书 | 绿色计算产业发展白皮书(2024) | 绿色计算产业联盟 |
| 白皮书 | Carbon-aware Computing Whitepaper | Microsoft Research |
| 视频课 | MIT 6.5840 Distributed Systems (Spring 2026) | MIT OCW / B站 |
| 视频课 | Coursera — Foundations of Distributed Database Systems | Coursera |
| 视频课 | Coursera — Cloud Computing Specialization (UIUC) | Coursera |
| 视频课 | Coursera — Game Theory (Stanford & UBC) | Coursera |
| 视频课 | Coursera — Game Theory II: Advanced Applications (Stanford & UBC) | Coursera |
| 视频课 | 蚂蚁隐语隐私计算实训营 (2024-2025) | B站 / 隐语社区 |
| 视频课 | 联邦学习框架 FederatedScope | B站 |
| 书籍 | Designing Data-Intensive Applications | Martin Kleppmann |
| 书籍 | Twenty Lectures on Algorithmic Game Theory | Tim Roughgarden |
| 书籍 | 边缘计算（第二版） | 施巍松等 |
| 开源 | Green Algorithms Calculator | Cambridge Sustainable Computing Lab |
| 开源 | Carbon Aware SDK | Microsoft / Green Software Foundation |
| 开源 | PySyft | OpenMined |
| 开源 | TensorFlow Privacy | Google |
