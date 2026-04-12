# Mathematics & Scientific Reasoning

<p align="right"><strong>Language:</strong> English | <a href="mathematics_zh.md">中文</a></p>

> Mathematical reasoning, theorem proving, symbolic regression, scientific computing, and related mathematical foundation models.
> [Index](../README.md)
> Curation note: pure datasets, benchmarks, challenges, libraries, and product-only release pages are excluded; a few adjacent precursor models remain where scientific FM boundaries are still unsettled.

## Table of Contents
- [Theorem Proving](#mathematics-section-01)
- [Scientific Multimodal Reasoning](#mathematics-section-02)
- [Mathematical Reasoning LLMs](#mathematics-section-03)

<a id="mathematics-section-01"></a>
## Theorem Proving
*Foundation models for formal mathematical reasoning, combining LLMs with proof assistants such as Lean for automated theorem proving and mathematical competition problem solving.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| AlphaProof | Olympiad-Level Formal Mathematical Reasoning with AlphaProof | A formal mathematical reasoning system by DeepMind combining reinforcement learning with Lean proof assistant, solving 4/6 problems at the 2024 IMO to reach silver-medal level. | [Nature](https://doi.org/10.1038/s41586-025-09833-y) |
| AlphaGeometry | Solving olympiad geometry without human demonstrations | A neuro-symbolic geometry theorem prover by DeepMind that solves Olympiad-level plane geometry problems without human demonstrations. | [Nature](https://doi.org/10.1038/s41586-023-06747-5) |
| AlphaGeometry 2 | Gold-medalist Performance in Solving Olympiad Geometry with AlphaGeometry2 | An upgraded AlphaGeometry achieving 84% success rate on 25 years of IMO geometry problems, exceeding human gold-medalist average. | [arXiv](https://arxiv.org/abs/2502.03544) |
| Lean Copilot | Lean Copilot: Large Language Models as Copilots for Theorem Proving in Lean | A framework integrating LLMs into the Lean theorem prover for tactic suggestion, proof search, and premise selection. | [PMLR 2025](https://proceedings.mlr.press/v288/song25a.html) |
| LLEMMA | Llemma: An Open Language Model for Mathematics | An open-source math language model by EleutherAI trained on Proof-Pile-2 via continued pre-training of Code Llama, supporting mathematical reasoning and tool use. | [ICLR 2024](https://proceedings.iclr.cc/paper_files/paper/2024/hash/b225f5c7cd13615e9558c3931fa4e66f-Abstract-Conference.html) |
| DeepSeek-Prover | DeepSeek-Prover: Advancing Theorem Proving in LLMs through Large-Scale Synthetic Data | An LLM enhanced for Lean formal theorem proving using large-scale synthetic data generation. | [arXiv](https://arxiv.org/abs/2405.14333) |
| DeepSeek-Prover-V1.5 | DeepSeek-Prover-V1.5: Harnessing Proof Assistant Feedback for Reinforcement Learning and Monte-Carlo Tree Search | A Lean 4 theorem proving model optimized with proof assistant feedback, reinforcement learning, and Monte-Carlo tree search. | [arXiv](https://arxiv.org/abs/2408.08152) |
| DeepSeek-Prover-V2 | DeepSeek-Prover-V2: Advancing Formal Mathematical Reasoning via Reinforcement Learning for Subgoal Decomposition | The latest open-source formal theorem proving model using recursive proof pipelines and DeepSeek-V3 for subgoal decomposition. | [arXiv](https://arxiv.org/abs/2504.21801) |
| InternLM-Math | InternLM-Math: Open Math Large Language Models Toward Verifiable Reasoning | An open-source bilingual math reasoning model by Shanghai AI Lab integrating chain-of-thought reasoning, Lean 4 proofs, and MATH problem solving. | [arXiv](https://arxiv.org/abs/2402.06332) |
| MathCoder | MathCoder: Seamless Code Integration in LLMs for Enhanced Mathematical Reasoning | A model series enhancing LLM mathematical reasoning through seamless code integration, fine-tuned on the MathCodeInstruct dataset. | [ICLR 2024](https://proceedings.iclr.cc/paper_files/paper/2024/hash/15425f2df99aa1ba52712c9a4afc8536-Abstract-Conference.html) |
| Minerva | Solving Quantitative Reasoning Problems with Language Models | A Google LLM trained on scientific and mathematical papers to enhance quantitative reasoning for math, physics, and engineering problems. | [NeurIPS 2022](https://proceedings.neurips.cc/paper_files/paper/2022/hash/18abbeef8cfe9203fdf9053c9c4fe191-Abstract-Conference.html) |
| Goedel-Prover | Goedel-Prover: A Frontier Model for Open-Source Automated Theorem Proving | An open-source Lean formal theorem proving model trained on large-scale synthetic data, advancing the automated theorem proving frontier. | [arXiv](https://arxiv.org/abs/2502.07640) |
| Goedel-Prover-V2 | Goedel-Prover-V2: Scaling Up Automated Theorem Proving with Reinforcement Learning | An extended Goedel-Prover incorporating reinforcement learning to further improve theorem proving capability. | [arXiv](https://arxiv.org/abs/2508.03613) |
| Kimina-Prover | Kimina-Prover: 72B Parameter Model Achieving 80.7% on miniF2F | A 72-billion-parameter Lean theorem proving model by Moonshot AI achieving 80.7% pass rate on the miniF2F benchmark. | [arXiv](https://arxiv.org/abs/2504.11354) |
| Seed-Prover | Seed-Prover: Advancing Formal Mathematical Reasoning | A formal mathematical reasoning model by ByteDance that solved 5/6 problems at the 2025 IMO. | [arXiv](https://arxiv.org/abs/2507.23726) |
| Seed-Prover 1.5 | Seed-Prover 1.5: Large-Scale Reinforcement Learning for Theorem Proving | An upgraded Seed-Prover using large-scale reinforcement learning training to further improve formal proof capability. | [arXiv](https://arxiv.org/abs/2512.17260) |
| InternLM2.5-StepProver | InternLM2.5-StepProver: Advancing Automated Theorem Proving via Expert Iteration on Large-Scale LEAN Problems | An expert iteration-based Lean theorem proving model by Shanghai AI Lab with critique-guided search strategies. | [arXiv](https://arxiv.org/abs/2410.15700) |
| FunSearch | Mathematical discoveries from program search with large language models | An evolutionary program search framework by DeepMind leveraging LLMs for mathematical discovery, finding new constructions for the cap set problem. | [Nature](https://doi.org/10.1038/s41586-023-06924-6) |
| LLM-SR | LLM-SR: Scientific Equation Discovery via Programming with Large Language Models | A framework for symbolic regression and scientific equation discovery using large language models. | [arXiv](https://arxiv.org/abs/2404.18400) |
| TheoremLlama | TheoremLlama: Transforming General-Purpose LLMs into Lean4 Experts | A framework that transforms a general-purpose LLM (LLaMA-3-8B) into a Lean 4 theorem proving expert. | [ACL Anthology](https://aclanthology.org/2024.emnlp-main.667/) |
| HTPS | HyperTree Proof Search for Neural Theorem Proving | A Monte-Carlo tree search method for automatic theorem proving in Lean/Metamath achieving state-of-the-art results. | [NeurIPS 2022](https://proceedings.neurips.cc/paper_files/paper/2022/hash/a8901c5e85fb8e1823bbf0f755053672-Abstract-Conference.html) |
| APOLLO | APOLLO: Automated LLM and Lean Collaboration for Proof Generation | A modular framework combining LLMs with Lean 4 formal verification for automated proof generation. | [NeurIPS](https://arxiv.org/abs/2505.05758) |
| LeanNavigator | Generating Millions of Lean Theorems with Proofs by Exploring State Transitions | A system for large-scale generation of Lean theorems and proofs through systematic state transition exploration. | [arXiv](https://arxiv.org/abs/2503.04772) |
| Numina-Lean-Agent | An Open and General Agentic Reasoning System for Formal Mathematics | An open and general agentic reasoning system for formal mathematical reasoning in Lean. | [arXiv](https://arxiv.org/abs/2601.14027) |
| Goedel-Code-Prover | Hierarchical Proof Search for Open Automated Code Verification | A hierarchical proof search system for automated code formal verification. | [arXiv](https://arxiv.org/abs/2603.19329) |
| AlphaVerus | Bootstrapping Formally Verified Code Generation through Self-Improving Translation | A self-improving LLM system that generates formally verified code by bootstrapping translation quality. | [ICLR](https://arxiv.org/abs/2412.06176) |
| SymCode | SymCode: Neurosymbolic Approach to Mathematical Reasoning via Verifiable Code | A neurosymbolic mathematical reasoning framework combining neural generation with formal code verification. | [EACL](https://arxiv.org/abs/2510.25975) |
| STP | Self-play Theorem Prover in Lean | A self-play LLM that alternates between conjecturing and proving theorems in Lean. | [ICML](https://arxiv.org/abs/2502.00212) |
| Hilbert | Hilbert: Recursively Building Formal Proofs via LLM and Lean | A system that recursively combines LLM reasoning with Lean verification to construct formal proofs. | [arXiv](https://arxiv.org/abs/2509.22819) |

---

<a id="mathematics-section-02"></a>
## Scientific Multimodal Reasoning
*Large-scale models for cross-disciplinary scientific knowledge understanding and reasoning, supporting text, images, molecules, and other scientific data modalities.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| Intern-S1 | Intern-S1: A Scientific Multimodal Foundation Model | A 241B-parameter MoE scientific multimodal foundation model by Shanghai AI Lab trained on trillion-scale scientific data, supporting text/image/video scientific reasoning. | [arXiv](https://arxiv.org/abs/2508.15763) |
| Galactica | Galactica: A Large Language Model for Science | A scientific language model (125M–120B parameters) by Meta AI trained on 106 billion tokens of scientific literature, supporting paper summarization, math reasoning, and molecular understanding. | [arXiv](https://arxiv.org/abs/2211.09085) |
| SciGLM | SciGLM: Training Scientific Language Models with Self-Reflective Instruction Annotation and Tuning | A scientific language model enhanced via self-reflective instruction tuning for reasoning in physics, chemistry, math, and formal proofs. | [ACL](https://arxiv.org/abs/2401.07950) |
| SciDFM | SciDFM: A Large Language Model with Mixture-of-Experts for Science | An 18.2B-parameter (5.6B active) MoE science foundation model trained from scratch, supporting domain-specific knowledge including molecules and amino acid sequences. | [NeurIPS](https://arxiv.org/abs/2409.18412) |
| MathCoder2 | MathCoder2: Better Math Reasoning from Continued Pretraining on Model-translated Mathematical Code | A method for enhancing LLM mathematical reasoning through continued pre-training on model-translated mathematical code. | [arXiv](https://arxiv.org/abs/2410.08196) |
| Intern-S1-Pro | Intern-S1-Pro: Scientific Multimodal Foundation Model at Trillion Scale | A trillion-parameter MoE scientific multimodal foundation model covering chemistry, physics, life sciences, and earth sciences. | [arXiv](https://arxiv.org/abs/2603.25040) |
| FuXi-Uni | FuXi-Uni: A Unified Multimodal Foundation Model for Cross-Disciplinary Scientific Research | A unified multimodal foundation model for cross-disciplinary scientific research integrating diverse scientific data types. | [arXiv](https://arxiv.org/abs/2601.01363) |
| Aletheia | Aletheia: Autonomous Math Research Agent for Professional Discoveries | An autonomous mathematical research agent by DeepMind capable of making professional-level mathematical discoveries. | [arXiv](https://arxiv.org/abs/2602.10177) |
| TongGeometry | TongGeometry: Proposing and Solving Olympiad Geometry with Guided Tree Search | A neuro-symbolic AI system for Olympiad geometry that can both solve and generate geometry problems. | [Nature MI](https://doi.org/10.1038/s42256-025-01164-x) |
| SR-Scientist | LLMs as AI Scientists for Scientific Equation Discovery | A framework that transforms LLMs into AI scientists for discovering scientific equations from data. | [ICLR](https://arxiv.org/abs/2510.11661) |

---

<a id="mathematics-section-03"></a>
## Mathematical Reasoning LLMs
*Large language models specialized for mathematical problem solving through pre-training and fine-tuning on large-scale math corpora and synthetic data.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| DeepSeekMath | DeepSeekMath: Pushing the Limits of Mathematical Reasoning in Open Language Models | A 7B-parameter math reasoning model trained on 120 billion math tokens via continued pre-training, pushing open-source math reasoning limits. | [arXiv](https://arxiv.org/abs/2402.03300) |
| WizardMath | WizardMath: Empowering Mathematical Reasoning for Large Language Models via Reinforced Evol-Instruct | A model that enhances LLM mathematical reasoning through a reinforced evolutionary instruction method. | [arXiv](https://arxiv.org/abs/2308.09583) |
| MetaMath | MetaMath: Bootstrap Your Own Mathematical Questions for Large Language Models | A method that enhances LLM math training data by bootstrapping diverse mathematical question variants. | [ICLR 2024](https://proceedings.iclr.cc/paper_files/paper/2024/hash/c400474e8a36d0812fdee52739288b12-Abstract-Conference.html) |
| ToRA | ToRA: A Tool-Integrated Reasoning Agent for Mathematical Problem Solving | A tool-integrated reasoning agent that interleaves natural language reasoning with Python code execution for mathematical problem solving. | [ICLR 2024](https://proceedings.iclr.cc/paper_files/paper/2024/hash/d3cf1559a8795eb1ed2b3ad52409ac7d-Abstract-Conference.html) |
| MAmmoTH | MAmmoTH: Building Math Generalist Models through Hybrid Instruction Tuning | A math generalist model built through hybrid instruction tuning (CoT + PoT) using the MathInstruct dataset. | [ICLR 2024](https://proceedings.iclr.cc/paper_files/paper/2024/hash/b063829b922fdeb4fa3472dd3471ff43-Abstract-Conference.html) |
| MAmmoTH2 | MAmmoTH2: Scaling Instructions from the Web | An upgraded MAmmoTH leveraging web-scale data to expand mathematical instruction training. | [Advances in Neural Information Processing Systems 37](https://arxiv.org/abs/2405.03548) |
| DART-Math | DART-Math: Difficulty-Aware Rejection Tuning for Mathematical Problem-Solving | A difficulty-aware rejection sampling tuning method with biased training on high-difficulty math problems. | [NeurIPS 2024](https://proceedings.neurips.cc/paper_files/paper/2024/hash/0ef1afa0daa888d695dcd5e9513bafa3-Abstract-Conference.html) |
| JiuZhang3.0 | JiuZhang3.0: Efficiently Improving Mathematical Reasoning by Training Small Data Synthesis Models | A method that efficiently improves math reasoning by training small data synthesis models, reducing data dependency. | [NeurIPS 2024](https://proceedings.neurips.cc/paper_files/paper/2024/hash/0356216f73660e15670510f5e42b5fa6-Abstract-Conference.html) |
| rStar-Math | rStar-Math: Small LLMs Can Master Math Reasoning with Self-Evolved Deep Thinking | A framework enabling small LLMs to master math reasoning via Monte-Carlo tree search and self-evolved deep thinking. | [ICML](https://arxiv.org/abs/2501.04519) |
| Skywork-Math | Skywork-Math: Data Scaling Laws for Mathematical Reasoning in Large Language Models | A study exploring data scaling laws for mathematical reasoning in LLMs, providing guidance for math LLM training. | [技术报告](https://arxiv.org/abs/2407.08348) |
