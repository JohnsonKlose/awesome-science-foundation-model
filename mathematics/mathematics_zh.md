# 数学与科学推理

<p align="right"><strong>Language:</strong> <a href="mathematics_en.md">English</a> | 中文</p>

> 覆盖数学推理、定理证明、符号回归、科学计算等数学与科学推理基础模型。
> [总览](../README.zh.md)
> 说明：本页已剔除纯数据集、基准、挑战赛、库与仅有产品发布页的条目；为避免误译，少量新增条目暂沿用英文版简述。

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
| AlphaGeometry | Solving Olympiad Geometry Without Human Demonstrations | Trieu H. Trinh | 2024 | DOI:10.1038/s41586-023-06747-5 | Nature 2024 | DeepMind开发的神经-符号几何定理证明器，无需人类示范即可解决奥赛级平面几何问题。 |
| AlphaGeometry 2 | Gold-medalist Performance in Solving Olympiad Geometry with AlphaGeometry2 | Yuri Chervonyi | 2025 | arXiv:2502.03544 | arXiv | 升级版AlphaGeometry，在25年IMO几何题上达到84%成功率，超越人类金牌选手平均水平 |
| Lean Copilot | Lean Copilot: Large Language Models as Copilots for Theorem Proving in Lean | Peiyang Song | 2025 | PMLR v288 | International Conference on Neuro-symbolic Systems 2025 | 将LLM集成到Lean定理证明器中的框架，支持策略建议、证明搜索和前提选择。 |
| LLEMMA | Llemma: An Open Language Model for Mathematics | Zhangir Azerbayev | 2024 | ICLR 2024 proceedings | ICLR 2024 | EleutherAI开发的开源数学语言模型，在Proof-Pile-2数据集上继续预训练Code Llama，支持数学推理和工具使用。 |
| DeepSeek-Prover | DeepSeek-Prover: Advancing Theorem Proving in LLMs through Large-Scale Synthetic Data | Huajian Xin | 2024 | arXiv:2405.14333 | arXiv | 通过大规模合成数据生成增强的Lean形式化定理证明LLM |
| DeepSeek-Prover-V1.5 | DeepSeek-Prover-V1.5: Harnessing Proof Assistant Feedback for Reinforcement Learning and Monte-Carlo Tree Search | Huajian Xin | 2024 | arXiv:2408.08152 | arXiv | 通过证明助手反馈、强化学习和蒙特卡洛树搜索优化的Lean 4定理证明模型 |
| DeepSeek-Prover-V2 | DeepSeek-Prover-V2: Advancing Formal Mathematical Reasoning via Reinforcement Learning for Subgoal Decomposition | Z. Z. Ren | 2025 | arXiv:2504.21801 | arXiv | 最新开源形式化定理证明模型，使用递归证明流水线和DeepSeek-V3进行子目标分解 |
| InternLM-Math | InternLM-Math: Open Math Large Language Models Toward Verifiable Reasoning | Huaiyuan Ying | 2024 | arXiv:2402.06332 | arXiv | 上海AI Lab开源双语数学推理模型，整合思维链推理、Lean 4证明和数学问题求解 |
| MathCoder | MathCoder: Seamless Code Integration in LLMs for Enhanced Mathematical Reasoning | Ke Wang | 2024 | ICLR 2024 proceedings | ICLR 2024 | 通过无缝代码集成增强LLM数学推理能力的模型系列，使用MathCodeInstruct数据集微调。 |
| Minerva | Solving Quantitative Reasoning Problems with Language Models | Aitor Lewkowycz | 2022 | NeurIPS 2022 proceedings | NeurIPS 2022 | Google开发的大语言模型，通过在科学和数学论文上训练增强定量推理能力，支持数学、物理和工程问题求解。 |
| Goedel-Prover | Goedel-Prover: A Frontier Model for Open-Source Automated Theorem Proving | Yong Lin | 2025 | arXiv:2502.07640 | arXiv | 开源Lean形式化定理证明模型，在大规模合成数据上训练，推进自动化定理证明前沿 |
| Goedel-Prover-V2 | Goedel-Prover-V2: Scaling Up Automated Theorem Proving with Reinforcement Learning | (Goedel Lab) | 2025 | arXiv:2508.03613 | arXiv Preprint | Goedel-Prover的扩展版本，引入强化学习进一步提升定理证明能力。 |
| Kimina-Prover | Kimina-Prover: 72B Parameter Model Achieving 80.7% on miniF2F | (Moonshot AI) | 2025 | arXiv:2504.11354 | arXiv Preprint | 720亿参数Lean定理证明模型，在miniF2F基准上达到80.7%通过率。 |
| Seed-Prover | Seed-Prover: Advancing Formal Mathematical Reasoning | (ByteDance) | 2025 | arXiv:2507.23726 | arXiv Preprint | 字节跳动开发的形式化数学推理模型，在2025年IMO中解出5/6题。 |
| Seed-Prover 1.5 | Seed-Prover 1.5: Large-Scale Reinforcement Learning for Theorem Proving | (ByteDance) | 2025 | arXiv:2512.17260 | arXiv Preprint | Seed-Prover升级版，采用大规模强化学习训练，进一步提升形式化证明能力。 |
| InternLM2.5-StepProver | InternLM2.5-StepProver: Advancing Automated Theorem Proving via Expert Iteration on Large-Scale LEAN Problems | (Shanghai AI Lab) | 2024 | arXiv:2410.15700 | arXiv Preprint | 上海AI Lab开发的基于专家迭代的Lean定理证明模型，结合批评引导搜索策略。 |
| FunSearch | Mathematical Discoveries from Program Search with Large Language Models | (DeepMind) | 2024 | DOI:10.1038/s41586-023-06924-6 | Nature 2024 | DeepMind开发的进化式程序搜索框架，利用LLM进行数学发现，发现cap set问题新构造。 |
| LLM-SR | LLM-SR: Scientific Equation Discovery via Programming with Large Language Models | Parshin Shojaee | 2024 | arXiv:2404.18400 | arXiv | 使用大语言模型进行符号回归和科学方程发现的框架 |
| TheoremLlama | TheoremLlama: Transforming General-Purpose LLMs into Lean4 Experts | Ruida Wang | 2024 | DOI:10.18653/v1/2024.emnlp-main.667 | EMNLP 2024 | 将通用LLM(LLaMA-3-8B)转化为Lean4定理证明专家的框架 |
| HTPS | HyperTree Proof Search for Neural Theorem Proving | Guillaume Lample | 2022 | NeurIPS 2022 proceedings | NeurIPS 2022 | 蒙特卡洛树搜索方法用于Lean/Metamath自动定理证明，达到SOTA |
| APOLLO | APOLLO: Automated LLM and Lean Collaboration for Proof Generation | — | 2025 | NeurIPS 2025 | NeurIPS 2025 | 模块化框架，结合LLM与Lean4形式验证进行自动化证明生成 |
| LeanNavigator | Generating Millions of Lean Theorems with Proofs by Exploring State Transitions | — | 2025 | arXiv:2503.04772 | arXiv | 通过状态转换探索大规模生成Lean定理和证明的系统 |
| Numina-Lean-Agent | An Open and General Agentic Reasoning System for Formal Mathematics | — | 2026 | arXiv:2601.14027 | arXiv | 开放通用形式数学智能体推理系统 |
| Goedel-Code-Prover | Hierarchical Proof Search for Open Automated Code Verification | — | 2026 | arXiv:2603.19329 | arXiv | 自动化代码形式验证层次证明搜索 |
| AlphaVerus | Bootstrapping Formally Verified Code Generation through Self-Improving Translation | — | 2025 | — | ICLR 2025 | 自提升LLM生成形式化验证代码 |
| SymCode | SymCode: Neurosymbolic Approach to Mathematical Reasoning via Verifiable Code | — | 2025 | arXiv:2510.25975 | EACL 2026 | 神经符号数学推理框架 |
| STP | Self-play Theorem Prover in Lean | Kefan Dong (Stanford) | 2025 | arXiv:2502.00212 | ICML 2025 | 自我对弈LLM在Lean中交替猜想和证明 |
| Hilbert | Recursively building formal proofs via LLM + Lean | — | 2025 | arXiv:2509.22819 | arXiv | 递归结合LLM推理与Lean验证构建形式证明 |

---

<a id="mathematics-section-02"></a>
## 科学多模态推理

### 综述 Overview

科学多模态推理基础模型涵盖跨学科科学知识理解与推理的大规模模型，支持文本、图像、分子等多模态科学数据的处理和推理。

---

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| Intern-S1 | Intern-S1: A Scientific Multimodal Foundation Model | Lei Bai | 2025 | arXiv:2508.15763 | arXiv | 上海AI Lab 2410亿参数MoE科学多模态基础模型，在万亿级科学数据上训练，支持文本/图像/视频科学推理 |
| Galactica | Galactica: A Large Language Model for Science | Ross Taylor | 2022 | arXiv:2211.09085 | arXiv | Meta AI科学语言模型（1.25亿-1200亿参数），在1060亿token科学文献上训练，支持论文摘要、数学推理和分子理解 |
| SciGLM | SciGLM: Training Scientific Language Models with Self-Reflective Instruction Annotation and Tuning | Dan Zhang | 2024 | arXiv:2401.07950 | ACL 2024 | 基于自反射指令标注和调优的科学语言模型，增强LLM在物理、化学、数学和形式证明等领域的推理能力。 |
| SciDFM | SciDFM: A Large Language Model with Mixture-of-Experts for Science | Liangtai Sun | 2024 | arXiv:2409.18412 | NeurIPS 2024 | 从零训练的182亿参数（56亿活跃）MoE科学基础模型，支持分子、氨基酸序列等领域特异性知识理解。 |
| MathCoder2 | MathCoder2: Better Math Reasoning from Continued Pretraining on Model-translated Mathematical Code | Zimu Lu | 2024 | arXiv:2410.08196 | arXiv | 通过在模型翻译的数学代码上继续预训练来增强LLM数学推理的方法 |
| Intern-S1-Pro | Scientific Multimodal Foundation Model at Trillion Scale | Shanghai AI Lab | 2026 | arXiv:2603.25040 | arXiv | 万亿参数MoE科学多模态FM，覆盖化学、物理、生命科学、地球科学 |
| FuXi-Uni | FuXi-Uni: A Unified Multimodal FM for Cross-Disciplinary Scientific Research | — | 2025 | arXiv:2601.01363 | arXiv | 统一多模态FM用于跨学科科学研究 |
| Aletheia | Autonomous math research agent for professional discoveries | DeepMind | 2026 | arXiv:2602.10177 | arXiv | DeepMind自主数学研究智能体 |
| TongGeometry | Neuro-symbolic AI for olympiad geometry | BIGAI | 2026 | Nature Machine Intelligence | Nature MI | 神经符号AI奥赛几何，可解题也可出题 |
| SR-Scientist | LLMs as AI scientists for scientific equation discovery | — | 2025 | arXiv:2510.11661 | ICLR 2026 | 将LLM转化为科学方程发现的AI科学家 |

---

---

<a id="mathematics-section-03"></a>
## 数学推理LLM

### 综述 Overview

数学推理LLM专注于通过预训练和微调提升大语言模型在数学问题求解（算术、代数、竞赛数学等）中的推理能力，通常在大规模数学语料或合成数据上训练。

---

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| DeepSeekMath | DeepSeekMath: Pushing the Limits of Mathematical Reasoning in Open Language Models | Zhihong Shao | 2024 | arXiv:2402.03300 | arXiv | 70亿参数数学推理模型，通过继续预训练在1200亿数学token上训练，突破开源数学推理极限 |
| WizardMath | WizardMath: Empowering Mathematical Reasoning for Large Language Models via Reinforced Evol-Instruct | Haipeng Luo | 2023 | arXiv:2308.09583 | arXiv | 通过强化进化指令方法增强LLM数学推理的模型 |
| MetaMath | MetaMath: Bootstrap Your Own Mathematical Questions for Large Language Models | Longhui Yu | 2024 | ICLR 2024 proceedings | ICLR 2024 | 通过引导生成多样化数学问题变体增强LLM数学训练数据。 |
| ToRA | ToRA: A Tool-Integrated Reasoning Agent for Mathematical Problem Solving | Zhibin Gou | 2024 | ICLR 2024 proceedings | ICLR 2024 | 工具集成推理智能体，交错使用自然语言推理和Python代码执行解决数学问题。 |
| MAmmoTH | MAmmoTH: Building Math Generalist Models through Hybrid Instruction Tuning | Xiang Yue | 2024 | ICLR 2024 proceedings | ICLR 2024 | 通过混合指令微调（CoT + PoT）构建的数学通用模型，使用MathInstruct数据集。 |
| MAmmoTH2 | MAmmoTH2: Scaling Instructions from the Web | Xiang Yue | 2024 | arXiv:2405.03548 | arXiv | MAmmoTH升级版，利用网络规模数据扩展数学指令训练 |
| DART-Math | DART-Math: Difficulty-Aware Rejection Tuning for Mathematical Problem-Solving | Yuxuan Tong | 2024 | DOI:10.52202/079017-0251 | NeurIPS 2024 | 难度感知拒绝采样调优方法，针对高难度数学题进行偏向性训练。 |
| JiuZhang3.0 | JiuZhang3.0: Efficiently Improving Mathematical Reasoning by Training Small Data Synthesis Models | Kun Zhou | 2024 | DOI:10.52202/079017-0059 | NeurIPS 2024 | 通过训练小型数据合成模型高效提升数学推理能力，减少数据依赖。 |
| rStar-Math | rStar-Math: Small LLMs Can Master Math Reasoning with Self-Evolved Deep Thinking | (Microsoft Research) | 2025 | arXiv:2501.04519 | ICML 2025 | 小型LLM通过蒙特卡洛树搜索和自进化深度思考掌握数学推理。 |
| Skywork-Math | Skywork-Math: Data Scaling Laws for Mathematical Reasoning in Large Language Models | (Skywork Team) | 2024 | — | 技术报告 | 探索数学推理中数据缩放规律的研究，为数学LLM训练提供指导。 |

---
