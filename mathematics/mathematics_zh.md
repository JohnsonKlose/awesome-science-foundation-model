# 数学与科学推理

<p align="right"><strong>Language:</strong> <a href="mathematics_en.md">English</a> | 中文</p>

> 覆盖数学推理、定理证明、符号回归、科学计算等数学与科学推理基础模型。
> [总览](../README.zh.md)

## 目录
- [定理证明](#mathematics-section-01)
- [科学多模态推理](#mathematics-section-02)
- [数学推理LLM](#mathematics-section-03)

<a id="mathematics-section-01"></a>
## 定理证明

### 综述 Overview

定理证明基础模型专注于形式化数学推理，结合大语言模型与证明辅助系统（如Lean），用于自动化定理证明、数学竞赛问题求解等。

---

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| AlphaProof | Olympiad-Level Formal Mathematical Reasoning with AlphaProof | (DeepMind团队) | 2024 | DOI:10.1038/s41586-025-09833-y | Nature 2025 | DeepMind开发的形式化数学推理系统，结合强化学习和Lean证明助手，在2024年IMO中解出4/6题达到银牌水平。 |
| LLEMMA | Llemma: An Open Language Model for Mathematics | Zhangir Azerbayev | 2023 | arXiv:2310.10631 | ICLR 2024 | EleutherAI开发的开源数学语言模型，在Proof-Pile-2数据集上继续预训练Code Llama，支持数学推理和工具使用。 |
| DeepSeek-Prover | DeepSeek-Prover: Advancing Theorem Proving in LLMs through Large-Scale Synthetic Data | (DeepSeek-AI) | 2024 | arXiv:2405.14333 | arXiv Preprint | 通过大规模合成数据增强Lean形式化定理证明能力的LLM。 |
| DeepSeek-Prover-V1.5 | DeepSeek-Prover-V1.5: Harnessing Proof Assistant Feedback for Reinforcement Learning and Monte-Carlo Tree Search | (DeepSeek-AI) | 2024 | arXiv:2408.08152 | arXiv Preprint | 利用证明助手反馈进行强化学习和蒙特卡洛树搜索优化的Lean 4定理证明模型。 |
| DeepSeek-Prover-V2 | DeepSeek-Prover-V2: Advancing Formal Mathematical Reasoning via Reinforcement Learning for Subgoal Decomposition | (DeepSeek-AI) | 2025 | arXiv:2504.21801 | arXiv Preprint | 最新的开源形式化定理证明模型，利用递归定理证明管线和DeepSeek-V3进行子目标分解。 |
| InternLM-Math | InternLM-Math: Open Math Large Language Models Toward Verifiable Reasoning | Huaiyuan Ying | 2024 | arXiv:2402.06332 | arXiv Preprint | 上海AI Lab开发的开源双语数学推理模型，集成链式思考推理、Lean 4证明和MATH求解。 |
| MathCoder | MathCoder: Seamless Code Integration in LLMs for Enhanced Mathematical Reasoning | Ke Wang | 2023 | arXiv:2310.03731 | ICLR 2024 | 通过无缝代码集成增强LLM数学推理能力的模型系列，使用MathCodeInstruct数据集微调。 |
| Minerva | Solving Quantitative Reasoning Problems with Language Models | Aitor Lewkowycz | 2022 | arXiv:2206.14858 | NeurIPS 2022 | Google开发的大语言模型，通过在科学和数学论文上训练增强定量推理能力，支持数学、物理和工程问题求解。 |
| Goedel-Prover | Goedel-Prover: A Frontier Model for Open-Source Automated Theorem Proving | (Goedel Lab) | 2025 | arXiv:2502.07640 | arXiv Preprint | 开源Lean形式化定理证明模型，基于大规模合成数据训练，推进自动定理证明前沿。 |
| Goedel-Prover-V2 | Goedel-Prover-V2: Scaling Up Automated Theorem Proving with Reinforcement Learning | (Goedel Lab) | 2025 | arXiv:2508.03613 | arXiv Preprint | Goedel-Prover的扩展版本，引入强化学习进一步提升定理证明能力。 |
| Kimina-Prover | Kimina-Prover: 72B Parameter Model Achieving 80.7% on miniF2F | (Moonshot AI) | 2025 | arXiv:2504.11354 | arXiv Preprint | 720亿参数Lean定理证明模型，在miniF2F基准上达到80.7%通过率。 |
| Seed-Prover | Seed-Prover: Advancing Formal Mathematical Reasoning | (ByteDance) | 2025 | arXiv:2507.23726 | arXiv Preprint | 字节跳动开发的形式化数学推理模型，在2025年IMO中解出5/6题。 |
| Seed-Prover 1.5 | Seed-Prover 1.5: Large-Scale Reinforcement Learning for Theorem Proving | (ByteDance) | 2025 | arXiv:2512.17260 | arXiv Preprint | Seed-Prover升级版，采用大规模强化学习训练，进一步提升形式化证明能力。 |
| InternLM2.5-StepProver | InternLM2.5-StepProver: Advancing Automated Theorem Proving via Expert Iteration on Large-Scale LEAN Problems | (Shanghai AI Lab) | 2024 | arXiv:2410.15700 | arXiv Preprint | 上海AI Lab开发的基于专家迭代的Lean定理证明模型，结合批评引导搜索策略。 |
| AlphaVerus | Bootstrapping Formally Verified Code Generation through Self-Improving Translation | — | 2025 | — | ICLR 2025 | 自提升LLM生成形式化验证代码 |
| Leanstral | First open-source AI agent for formal verification in Lean 4 | Mistral AI | 2026 | HuggingFace | Mistral AI | Mistral AI首个开源Lean 4形式验证AI |
| STP | Self-play Theorem Prover in Lean | Kefan Dong (Stanford) | 2025 | arXiv:2502.00212 | ICML 2025 | 自我对弈LLM在Lean中交替猜想和证明 |

---

<a id="mathematics-section-02"></a>
## 科学多模态推理

### 综述 Overview

科学多模态推理基础模型涵盖跨学科科学知识理解与推理的大规模模型，支持文本、图像、分子等多模态科学数据的处理和推理。

---

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| Intern-S1 | Intern-S1: A Scientific Multimodal Foundation Model | Lei Bai | 2025 | arXiv:2508.15763 | arXiv Preprint | 上海AI Lab开发的科学多模态基础模型，241B参数（28B活跃）MoE架构，在万亿级科学数据上训练，支持文本/图像/视频的科学推理。 |
| Galactica | Galactica: A Large Language Model for Science | Ross Taylor | 2022 | arXiv:2211.09085 | arXiv Preprint | Meta AI开发的科学语言模型（125M-120B参数），在1060亿token的科学文献上训练，支持论文总结、数学推理、分子理解等。 |
| SciGLM | SciGLM: Training Scientific Language Models with Self-Reflective Instruction Annotation and Tuning | Dan Zhang | 2024 | arXiv:2401.07950 | ACL 2024 | 基于自反射指令标注和调优的科学语言模型，增强LLM在物理、化学、数学和形式证明等领域的推理能力。 |
| SciDFM | SciDFM: A Large Language Model with Mixture-of-Experts for Science | Liangtai Sun | 2024 | arXiv:2409.18412 | NeurIPS 2024 | 从零训练的182亿参数（56亿活跃）MoE科学基础模型，支持分子、氨基酸序列等领域特异性知识理解。 |
| Intern-S1-Pro | Scientific Multimodal Foundation Model at Trillion Scale | Shanghai AI Lab | 2026 | arXiv:2603.25040 | arXiv | 万亿参数MoE科学多模态FM，覆盖化学、物理、生命科学、地球科学 |
| FuXi-Uni | FuXi-Uni: A Unified Multimodal FM for Cross-Disciplinary Scientific Research | — | 2025 | arXiv:2601.01363 | arXiv | 统一多模态FM用于跨学科科学研究 |

---

---

<a id="mathematics-section-03"></a>
## 数学推理LLM

### 综述 Overview

数学推理LLM专注于通过预训练和微调提升大语言模型在数学问题求解（算术、代数、竞赛数学等）中的推理能力，通常在大规模数学语料或合成数据上训练。

---

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| Qwen2.5-Math | Qwen2.5-Math Technical Report: Toward Mathematical Expert Model via Self-Improvement | (Alibaba Qwen Team) | 2024 | — | 技术报告 | 阿里巴巴开发的双语（中英）数学LLM系列，1.5B-72B参数，在数学推理基准上达到领先水平。 |
| DeepSeekMath | DeepSeek-Math: Pushing the Limits of Mathematical Reasoning in Open Language Models | (DeepSeek-AI) | 2024 | arXiv:2402.03300 | arXiv Preprint | 7B参数数学推理模型，在1200亿数学token上继续预训练，推进开源数学推理极限。 |
| Mathstral | Mathstral: Mathematics-Specialized 7B Model | (Mistral AI) | 2024 | — | Mistral AI发布 | Mistral AI开发的7B参数数学专用模型，针对数学推理和问题求解优化。 |
| WizardMath | WizardMath: Empowering Mathematical Reasoning for Large Language Models via Reinforced Evol-Instruct | Haipeng Luo | 2023 | arXiv:2308.09583 | arXiv Preprint | 通过强化进化指令方法增强LLM数学推理能力。 |
| MAmmoTH | MAmmoTH: Building Math Generalist Models through Hybrid Instruction Tuning | Xiang Yue | 2023 | arXiv:2309.05653 | ICLR 2024 | 通过混合指令微调（CoT + PoT）构建的数学通用模型，使用MathInstruct数据集。 |
| MAmmoTH2 | MAmmoTH2: Scaling Instructions from the Web | Xiang Yue | 2024 | arXiv:2405.03548 | arXiv Preprint | MAmmoTH升级版，利用网络规模数据扩展数学指令训练。 |

---

> **总计 / Total: 29 models** — 定理证明 TheoremProving: 17 | 科学多模态推理 ScientificReasoning: 6 | 数学推理LLM MathReasoning: 6
