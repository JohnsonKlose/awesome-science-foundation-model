# Mathematics & Scientific Reasoning

<p align="right"><strong>Language:</strong> English | <a href="mathematics_zh.md">中文</a></p>

> Mathematical reasoning, theorem proving, symbolic regression, scientific computing, and related mathematical foundation models.
> [Index](../README.md)

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
| LLEMMA | Llemma: An Open Language Model for Mathematics | An open-source math language model by EleutherAI trained on Proof-Pile-2 via continued pre-training of Code Llama, supporting mathematical reasoning and tool use. | [ICLR](https://openreview.net/forum?id=4WnqRR915j) |
| DeepSeek-Prover | DeepSeek-Prover: Advancing Theorem Proving in LLMs through Large-Scale Synthetic Data | An LLM enhanced for Lean formal theorem proving using large-scale synthetic data generation. | [arXiv](https://arxiv.org/abs/2405.14333) |
| DeepSeek-Prover-V1.5 | DeepSeek-Prover-V1.5: Harnessing Proof Assistant Feedback for Reinforcement Learning and Monte-Carlo Tree Search | A Lean 4 theorem proving model optimized with proof assistant feedback, reinforcement learning, and Monte-Carlo tree search. | [arXiv](https://arxiv.org/abs/2408.08152) |
| DeepSeek-Prover-V2 | DeepSeek-Prover-V2: Advancing Formal Mathematical Reasoning via Reinforcement Learning for Subgoal Decomposition | The latest open-source formal theorem proving model using recursive proof pipelines and DeepSeek-V3 for subgoal decomposition. | [arXiv](https://arxiv.org/abs/2504.21801) |
| InternLM-Math | InternLM-Math: Open Math Large Language Models Toward Verifiable Reasoning | An open-source bilingual math reasoning model by Shanghai AI Lab integrating chain-of-thought reasoning, Lean 4 proofs, and MATH problem solving. | [arXiv](https://arxiv.org/abs/2402.06332) |
| MathCoder | MathCoder: Seamless Code Integration in LLMs for Enhanced Mathematical Reasoning | A model series enhancing LLM mathematical reasoning through seamless code integration, fine-tuned on the MathCodeInstruct dataset. | [ICLR](https://openreview.net/forum?id=z8TW0ttBPp) |
| Minerva | Solving Quantitative Reasoning Problems with Language Models | A Google LLM trained on scientific and mathematical papers to enhance quantitative reasoning for math, physics, and engineering problems. | [NeurIPS 2022](https://papers.nips.cc/paper_files/paper/2022/hash/18abbeef8cfe9203fdf9053c9c4fe191-Abstract-Conference.html) |
| Goedel-Prover | Goedel-Prover: A Frontier Model for Open-Source Automated Theorem Proving | An open-source Lean formal theorem proving model trained on large-scale synthetic data, advancing the automated theorem proving frontier. | [arXiv](https://arxiv.org/abs/2502.07640) |
| Goedel-Prover-V2 | Goedel-Prover-V2: Scaling Up Automated Theorem Proving with Reinforcement Learning | An extended Goedel-Prover incorporating reinforcement learning to further improve theorem proving capability. | [arXiv](https://arxiv.org/abs/2508.03613) |
| Kimina-Prover | Kimina-Prover: 72B Parameter Model Achieving 80.7% on miniF2F | A 72-billion-parameter Lean theorem proving model by Moonshot AI achieving 80.7% pass rate on the miniF2F benchmark. | [arXiv](https://arxiv.org/abs/2504.11354) |
| Seed-Prover | Seed-Prover: Advancing Formal Mathematical Reasoning | A formal mathematical reasoning model by ByteDance that solved 5/6 problems at the 2025 IMO. | [arXiv](https://arxiv.org/abs/2507.23726) |
| Seed-Prover 1.5 | Seed-Prover 1.5: Large-Scale Reinforcement Learning for Theorem Proving | An upgraded Seed-Prover using large-scale reinforcement learning training to further improve formal proof capability. | [arXiv](https://arxiv.org/abs/2512.17260) |
| InternLM2.5-StepProver | InternLM2.5-StepProver: Advancing Automated Theorem Proving via Expert Iteration on Large-Scale LEAN Problems | An expert iteration-based Lean theorem proving model by Shanghai AI Lab with critique-guided search strategies. | [arXiv](https://arxiv.org/abs/2410.15700) |
| AlphaVerus | Bootstrapping Formally Verified Code Generation through Self-Improving Translation | A self-improving LLM system that generates formally verified code by bootstrapping translation quality. | [ICLR](https://proceedings.mlr.press/v267/aggarwal25a.html) |
| Leanstral | Leanstral: First Open-Source AI Agent for Formal Verification in Lean 4 | Mistral AI's first open-source AI agent for formal verification in Lean 4. | [Mistral AI](https://huggingface.co/mistralai/Leanstral-7B) |
| STP | Self-play Theorem Prover in Lean | A self-play LLM that alternates between conjecturing and proving theorems in Lean. | [ICML](https://arxiv.org/abs/2502.00212) |

---

<a id="mathematics-section-02"></a>
## Scientific Multimodal Reasoning
*Large-scale models for cross-disciplinary scientific knowledge understanding and reasoning, supporting text, images, molecules, and other scientific data modalities.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| Intern-S1 | Intern-S1: A Scientific Multimodal Foundation Model | A 241B-parameter MoE scientific multimodal foundation model by Shanghai AI Lab trained on trillion-scale scientific data, supporting text/image/video scientific reasoning. | [arXiv](https://arxiv.org/abs/2508.15763) |
| Galactica | Galactica: A Large Language Model for Science | A scientific language model (125M–120B parameters) by Meta AI trained on 106 billion tokens of scientific literature, supporting paper summarization, math reasoning, and molecular understanding. | [arXiv](https://arxiv.org/abs/2211.09085) |
| SciGLM | SciGLM: Training Scientific Language Models with Self-Reflective Instruction Annotation and Tuning | A scientific language model enhanced via self-reflective instruction tuning for reasoning in physics, chemistry, math, and formal proofs. | [ACL](https://doi.org/10.52202/079017-0046) |
| SciDFM | SciDFM: A Large Language Model with Mixture-of-Experts for Science | An 18.2B-parameter (5.6B active) MoE science foundation model trained from scratch, supporting domain-specific knowledge including molecules and amino acid sequences. | [NeurIPS](https://arxiv.org/abs/2409.18412) |
| Intern-S1-Pro | Intern-S1-Pro: Scientific Multimodal Foundation Model at Trillion Scale | A trillion-parameter MoE scientific multimodal foundation model covering chemistry, physics, life sciences, and earth sciences. | [arXiv](https://arxiv.org/abs/2603.25040) |
| FuXi-Uni | FuXi-Uni: A Unified Multimodal Foundation Model for Cross-Disciplinary Scientific Research | A unified multimodal foundation model for cross-disciplinary scientific research integrating diverse scientific data types. | [arXiv](https://arxiv.org/abs/2601.01363) |

---

<a id="mathematics-section-03"></a>
## Mathematical Reasoning LLMs
*Large language models specialized for mathematical problem solving through pre-training and fine-tuning on large-scale math corpora and synthetic data.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| Qwen2.5-Math | Qwen2.5-Math Technical Report: Toward Mathematical Expert Model via Self-Improvement | A bilingual (Chinese-English) math LLM series by Alibaba (1.5B–72B parameters) achieving leading performance on math reasoning benchmarks. | [arXiv](https://arxiv.org/abs/2409.12122) |
| DeepSeekMath | DeepSeek-Math: Pushing the Limits of Mathematical Reasoning in Open Language Models | A 7B-parameter math reasoning model trained on 120 billion math tokens via continued pre-training, pushing open-source math reasoning limits. | [arXiv](https://arxiv.org/abs/2402.03300) |
| Mathstral | MathΣtral: Mathematics-Specialized 7B Model | A 7B-parameter math-specialized model by Mistral AI optimized for mathematical reasoning and STEM problem solving. | [Mistral AI](https://mistral.ai/news/mathstral) |
| WizardMath | WizardMath: Empowering Mathematical Reasoning for Large Language Models via Reinforced Evol-Instruct | A model that enhances LLM mathematical reasoning through a reinforced evolutionary instruction method. | [arXiv](https://arxiv.org/abs/2308.09583) |
| MAmmoTH | MAmmoTH: Building Math Generalist Models through Hybrid Instruction Tuning | A math generalist model built through hybrid instruction tuning (CoT + PoT) using the MathInstruct dataset. | [ICLR](https://openreview.net/forum?id=yLClGs770I) |
| MAmmoTH2 | MAmmoTH2: Scaling Instructions from the Web | An upgraded MAmmoTH leveraging web-scale data to expand mathematical instruction training. | [NeurIPS 2024](https://papers.nips.cc/paper_files/paper/2024/hash/a4ca07aa108036f80cbb5b82285fd4b1-Abstract-Conference.html) |
