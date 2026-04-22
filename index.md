# 知识库索引

## 概念

### AI 基础
- [[LLM（大语言模型）]] — 文字接龙机器，本质是概率计算
- [[Token（词元）]] — 计费单位，中文约1.5-2个Token
- [[Context-Window（上下文窗口）]] — 窗口越大不代表效果越好
- [[Embedding（嵌入向量）]] — 把文字变成数字向量，表示语义
- [[Attention（注意力机制）]] — Transformer 的核心机制
- [[Self-Attention（自注意力机制）]] — 每个词查看所有其他词

### Agent 与 Skills
- [[Agent（智能体）]] — 能拆解任务、调用工具、观察调整
- [[Agentic Skills（技能设计）]] — 描述流程的方法调用，非一次性提示词
- [[Harness（脚手架）]] — Prompt 的进化版，AI 的完整工作手册
- [[PACT框架]] — Agent 产品设计的责任分配框架
- [[Multi-Agent（多智能体）]] — 多个 Agent 协作的系统
- [[Tool-Use（工具调用）]] — Agent 感知外部世界的函数
- [[Resolver（解析器）]] — 上下文的路由表
- [[Diarization（归因化）]] — 从非结构化来源抽取结构化档案
- [[Human-in-the-Loop（人在回路）]] — 关键节点人工干预
- [[Context-Manager（上下文管理器）]] — 管理 Agent 的思考空间
- [[Context-Rot（上下文腐化）]] — 长对话中的上下文失效现象

### Multi-Agent 协作模式
- [[Generator-Verifier（生成-验证者）]] — 一个生成，一个验证质量
- [[Orchestrator-Subagent（调度-子智能体）]] — 调度者拆解任务分发
- [[Agent-Teams（智能体团队）]] — 多智能体并行，各自有长时间记忆
- [[Message-Bus（消息总线）]] — 事件驱动，订阅-发布模式
- [[Shared-State（共享状态）]] — 去中心化，频繁共享中间发现

### RAG 与知识管理
- [[RAG（检索增强生成）]] — 开卷考试，检索质量是RAG的生死线
- [[Agentic-RAG]] — 带多跳检索能力的 RAG 架构
- [[AI知识层]] — 位于你和 Agent 之间的基础设施
- [[Knowledge Graph（知识图谱）]] — 实体-关系-实体的三元组结构
- [[Memory（记忆系统）]] — Agent 的记忆能力
- [[Cognee]] — Agent 记忆架构的综合方案

### 训练与优化
- [[Fine-tuning（微调）]] — 让模型真正学会
- [[Pre-training（预训练）]] — 基座模型的训练阶段
- [[SFT（监督微调）]] — 用标准答案训练模型
- [[RLHF（人类反馈强化学习）]] — 用人类反馈优化模型
- [[LoRA（低秩适配）]] — 只改0.1%-1%参数
- [[Distillation（知识蒸馏）]] — 用大模型教小模型

### 可靠性
- [[幻觉]] — 主流模型幻觉率10%-30%
- [[Chain-of-Thought（思维链）]] — 拆解多步问题
- [[Grounding（知识锚定）]] — 让AI回答有据可查

### 评估与指标
- [[Precision（精确率）]] — 别乱报
- [[Recall（召回率）]] — 别漏掉
- [[Latency（延迟优化）]] — AI产品的体验关键

### 架构
- [[Transformer（变换器）]] — 现代 LLM 的基础架构
- [[Encoder-Decoder（编码器-解码器）]] — Transformer 的两种结构
- [[MoE （混合专家）]] — 总参数大、但每个 token 只用一小部分
- [[Agentic软件]] — AI Agent 驱动的软件系统

### 安全与工程
- [[Security Engineering（安全工程）]] — 系统强制权限，非 prompt 强制
- [[System Engineering（系统工程）]] — 组件间交互的学科
- [[MCP（模型上下文协议）]] — 统一的工具接入标准
- [[CI/CD]] — 持续集成/部署
- [[AI-First（AI优先战略）]] — 软件工程 First，而非 AI First

### 视频与媒体
- [[AI视频运镜]] — AI 视频生成中的运镜技巧

### 经济与就业
- [[Jevons Paradox（杰文斯悖论）]] — 技术进步反而增加资源消耗

### 编程工具
- [[Codex（OpenAI编程工具）]] — OpenAI 的 AI 编程工具

## 主题

### AI 战略
- [[AI战略2026-2027]] — AI时代如何定位个人和组织
- [[Stanford AI Index Report 2026]] — 斯坦福年度AI指数报告
- [[超级智能治理]] — 超级智能过渡期的政策框架

### Agent 系统
- [[Agentic系统工程]] — 构建 Agentic 软件的系统工程方法论
- [[Agentic 软件五层架构]] — Agent/Data/Security/Interface/Infrastructure
- [[Agent产品设计]] — Agent 产品的设计原则和 PACT 框架
- [[Agent工具设计]] — Anthropic 官方工具设计指南
- [[AI论文周报]] — AI 学术论文精选

### 知识管理
- [[Transformer架构]] — Transformer 的深度解析
- [[AI幕僚长]] — 用 AI 工具搭建个人参谋长系统
- [[AI知识管理]] — 个人知识管理的最佳实践

### AI 就业
- [[AI就业策略]] — AI 时代的就业策略
- [[AI创业范式]] — AI 时代的创业范式
- [[AI时代技能发展]] — AI 时代的技能发展
- [[AI就业与经济影响]] — Jevons Paradox、就业极化分析

### AI 技术对比
- [[Coding-Agent工具对比]] — Claude Code vs Codex 深度对比
- [[AI视频生成]] — 运镜技巧大全

### 开源与闭源
- [[开源模型vs闭源模型]] — 开源与闭源模型的优劣对比

### 开源与闭源
- [[开源模型vs闭源模型]] — 开源与闭源模型的优劣对比

## 实体

### 人物
- [[Garry Tan]] — YC CEO，提出 Agentic Skills 概念
- [[Lilian Weng]] — OpenAI 研究员，提出 Agent 记忆三层框架
- [[MoGawdat]] — Google 前高管，AI 战略专家
- [[Cara Phillips]] — Multi-Agent 协作模式提出者
- [[Allen]] — 产品炼丹指北作者，Agent 产品设计专家
- [[Michael Livi]] — Adobe 总监，AI 幕僚长案例
- [[宝玉AI]] — 技术博主，AI 文章翻译者

### 组织
- [[OpenAI]] — AI 研究公司
- [[Anthropic]] — AI 安全公司，Claude 的开发方
- [[Stanford HAI]] — 斯坦福以人为本人工智能研究院
- [[Y Combinator]] — 顶级创业孵化器
- [[Microsoft]] — 科技巨头，Memento/Universal Verifier
- [[Meta AI]] — 科技巨头，Llama/神经计算机

### 工具
- [[Claude Code]] — Anthropic 的 AI 编程工具
- [[Codex]] — OpenAI 的 AI 编程工具

## 源文档摘要

### AI 产品经理核心概念
- [[001 通往AGI之路/AI产品经理60核心概念_Part1]]
- [[001 通往AGI之路/AI产品经理60核心概念_Part2]]

### Agent 与 Skills
- [[源文档摘要/AI-Agentic-Skills设计关键概念]]
- [[源文档摘要/Anthropic官方指南_怎么给Agent设计工具]]
- [[源文档摘要/多智能体协作指南_五种主流模式]]

### 记忆与知识管理
- [[源文档摘要/LLM长期记忆为何仍是未解难题]]
- [[源文档摘要/Agent记忆架构从Python列表到Cognee完整方案]]
- [[源文档摘要/AI知识层_让每个Agent都变聪明的双层系统]]

### 产品与设计
- [[源文档摘要/做Agent产品你是在重新分配责任]]
- [[源文档摘要/AI圈最烧脑的8个概念一文彻底讲透]]

### 战略与就业
- [[源文档摘要/AI会带来大规模失业吗]]
- [[源文档摘要/OpenAI超级智能治理与产业政策]]
- [[源文档摘要/Stanford AI Index Report 2026 完整解读]]

### 工程实践
- [[源文档摘要/为什么你的AI优先战略可能大错特错]]
- [[源文档摘要/大量开发者转投Codex_120小时实测]]

### 个人效率
- [[源文档摘要/时间管理的新解法_AI幕僚长]]
- [[源文档摘要/本周顶级AI论文精选_4_6-4_12]]
- [[源文档摘要/AI视频运镜提示词大全]]
