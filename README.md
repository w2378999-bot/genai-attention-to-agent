# 写给非工程师的生成式AI技术史

> 从 Word2Vec 到 Agent，沿着每一代技术回答前一代痛点的逻辑，走完生成式 AI 的完整演进路径。


---

## 这是什么

一份交互式的生成式 AI 技术史学习材料，基于真实的学习过程整理而来。

它不是学术综述，也不是新闻式科普，而是一条**有顺序的理解路径**——每个阶段都在回答前一个阶段留下的核心痛点，每个技术选择都有对应的"为什么"。

**适合谁看**：了解 ChatGPT 等产品，想深入理解背后技术逻辑，但不追求写代码的人。不需要深入的数学背景。

---

## 内容结构

| 阶段 | 时期 | 核心问题 |
|------|------|----------|
| 第一阶段：地基 | 2013–2017 | 语言模型在 Transformer 之前是怎么工作的？它的根本缺陷是什么？ |
| 第二阶段：革命 | 2017–2019 | Transformer 如何解决旧问题？Self-Attention 究竟在"算什么"？ |
| 第三阶段：军备竞赛 | 2020–2022 | 规模化为什么有效？如何让模型"听话"而不只是预测下一个词？ |
| 第四阶段：分化与深化 | 2023–2024 | 不同公司的技术路线有什么本质差异？DeepSeek 为什么能用更少资源做出更好效果？ |
| 第五阶段：现在与未来 | 2025– | 推理模型和 Agent 是什么？这个领域目前真正还没解决的核心难题是什么？ |

每个阶段包含：
- **主线步骤**：核心概念按演进顺序排列
- **展开深入**：可点击的追问节点，覆盖 LSTM 门控机制、Attention 权重计算、RLHF 奖励模型原理、DeepSeek MoE 改进、长上下文优化（FlashAttention / GQA / RoPE）、OpenClaw 本地 Agent 等约 20 个深度话题
- **延伸阅读**：每阶段推荐 4 篇最值得读的论文或博文，附说明读它的理由

---

## 使用方式

### 直接访问
点击上方在线链接即可，无需安装任何东西。

### 本地运行
下载 `genai-attention-to-agent.html`，用浏览器直接打开即可。单文件，无外部依赖。

### 部署到 GitHub Pages
1. Fork 或克隆本仓库
2. 进入仓库 **Settings → Pages**
3. Source 选择 `main` 分支，目录选 `/ (root)`
4. 保存后等约 1 分钟，访问 `https://你的用户名.github.io/仓库名`

---

## 技术特点

- **单文件 HTML**：约 100KB，无框架依赖，无需构建，浏览器直接打开
- **交互式步进器**：每个阶段独立导航，支持随时跳转
- **术语 tooltip**：金色下划线词汇悬停显示简介，不需要离开页面查资料
- **可展开节点**：深度内容默认收起，不干扰主线阅读
- **内嵌可视化**：RNN 串行 vs Transformer 并行、MoE 稀疏激活、RLHF 三步流程等关键概念附有图示

---

## 覆盖的主要概念

`Word2Vec` `RNN` `LSTM` `门控机制` `Seq2Seq` `Attention` `Self-Attention` `Transformer` `位置编码 / RoPE` `BERT` `GPT` `预训练 / 微调` `Scaling Law` `涌现能力` `RLHF` `奖励模型` `DPO` `宪法 AI` `ChatGPT` `扩散模型` `MoE` `FlashAttention` `GQA` `RAG` `长上下文` `DeepSeek` `Chain of Thought` `推理模型 / o1 / R1` `Agent` `Tool Use` `MCP` `Skill` `OpenClaw` `幻觉` `可解释性` `GEO`

---

## 材料来源

内容基于对以下论文和资料的整理与消化，每个阶段结尾有对应的延伸阅读列表：

- Vaswani et al., *Attention Is All You Need* (2017)
- Devlin et al., *BERT* (2018)
- Brown et al., *GPT-3* (2020)
- Ouyang et al., *InstructGPT / RLHF* (2022)
- Bai et al., *Constitutional AI* (2022)
- DeepSeek AI, *DeepSeek-V2 / V3 / R1* (2024)
- Jay Alammar, *The Illustrated Transformer / BERT*
- Christopher Olah, *Understanding LSTM Networks*
- 以及更多，详见各阶段延伸阅读

---

## 说明

- 内容截止时间：2026 年 5 月
- 非数学专业人士友好，保留英文技术术语
- 基于真实学习过程整理，不代表任何机构立场

如果发现内容错误或有补充建议，欢迎提 Issue 或 PR。
