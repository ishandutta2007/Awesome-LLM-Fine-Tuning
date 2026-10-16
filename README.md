# Awesome-LLM-Fine-Tuning

## Top LLM Fine-Tuning Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Parameter-Efficient Adaptation, Instruction Tuning & Model Customization*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **LLM Fine-Tuning**. These tools enable supervised fine-tuning (SFT), LoRA/QLoRA adaptation, reinforcement learning from human feedback (RLHF), direct preference optimization (DPO), and full-parameter training of open-source and proprietary language models.



**Examples** include Predibase, Lamini, Scale AI, Together AI, Fireworks AI, OctoAI, MonsterAPI, RunPod, Baseten, and Modal (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, consumer-hardware training, and transparent model customization — ideal for ML engineers, researchers, and developers building vendor-neutral fine-tuning pipelines.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Predibase](https://predibase.com/)**  

  LoRA-centric fine-tuning platform with LoRAX multi-adapter serving; enables thousands of fine-tuned adapters on a single base model deployment .



- **[Lamini](https://www.lamini.ai/)**  

  Enterprise platform for fine-tuning and serving open-source LLMs with focus on data privacy and compliance.



- **[Scale AI](https://scale.com/)**  

  Data labeling and model evaluation platform with fine-tuning services for enterprise AI teams.



- **[Together AI](https://www.together.ai/)**  

  Open-model fine-tuning and inference platform with pay-per-token training; supports LoRA and full fine-tuning of Llama, Qwen, and Mixtral models .



- **[Fireworks AI](https://fireworks.ai/)**  

  Fast fine-tuning and serving of open models with multi-LoRA support and sub-second time-to-first-token (TTFT) for optimized inference .



- **[OctoAI](https://octoai.cloud/)**  

  Cloud platform for deploying and fine-tuning generative AI models with optimized inference infrastructure.



- **[MonsterAPI](https://monsterapi.ai/)**  

  GPU cloud platform offering fine-tuning services and serverless inference for open-source LLMs.



- **[RunPod](https://www.runpod.io/)**  

  GPU cloud with fine-tuning templates and serverless endpoints; popular for cost-effective training of custom models .



- **[Baseten](https://www.baseten.co/)**  

  Model serving and fine-tuning platform focused on production deployment of custom models.



- **[Modal](https://modal.com/)**  

  Serverless GPU platform with Python decorator-based infrastructure; cold starts around 1 second and second-level billing for fine-tuning workflows .



## Open-Source GitHub Projects



- **[Alpaca-LoRA](https://github.com/tloen/alpaca-lora)**  

  **The foundational LoRA fine-tuning implementation** for LLaMA — instruct-tune on consumer hardware in under 5 hours on a single RTX 4090. Uses Hugging Face PEFT and bitsandbytes for cheap, efficient adaptation; 18.5k+ stars .



- **[Unsloth](https://github.com/unslothai/unsloth)**  

  **Fastest open-source library for local LLM fine-tuning** — optimized for low VRAM (even laptops), plug-and-play with Hugging Face models. Enables 2-5x faster training with reduced memory usage .



- **[Axolotl](https://github.com/OpenAccess-AI-Collective/axolotl)**  

  Flexible LLM fine-tuning configuration framework supporting LoRA, QLoRA, multi-GPU, and custom training pipelines. YAML-driven configs for reproducible experiments .



- **[LLaMA-Factory](https://github.com/hiyouga/LLaMA-Factory)**  

  **All-in-one fine-tuning UI and CLI** — supports 100+ models (LLaMA, Qwen, DeepSeek, Gemma, GLM, Mistral) with continuous pre-training, SFT, reward modeling, PPO, DPO, KTO, ORPO. Day-0 support for cutting-edge releases .



- **[TRL (Transformer Reinforcement Learning)](https://github.com/huggingface/trl)**  

  Hugging Face's library for RLHF, DPO, PPO, and reward modeling. Essential for post-training alignment of LLMs .



- **[PEFT](https://github.com/huggingface/peft)**  

  **Parameter-Efficient Fine-Tuning library** — implements LoRA, adapters, prefix tuning, and other efficient methods. The foundation for most modern fine-tuning workflows .



- **[DeepSpeed](https://github.com/microsoft/DeepSpeed)**  

  Microsoft's deep learning optimization library for training massive models efficiently with memory and speed optimizations. Industry standard for scaling LLM training .



- **[H2O LLM Studio](https://github.com/h2oai/h2o-llmstudio)**  

  No-code GUI framework for fine-tuning LLMs with enterprise features. 4,366+ stars, designed for teams without deep ML expertise .



- **[Oumi](https://github.com/oumi-ai/oumi)**  

  **Comprehensive open platform for training, evaluating, and deploying foundation models** — 8,400+ stars. Zero boilerplate recipes for DeepSeek R1, Llama 3.1, Qwen, and vision models with remote cloud launch support .



- **[Kiln](https://github.com/Kiln-AI/Kiln)**  

  Easy tool for fine-tuning, synthetic data generation, and dataset collaboration. 4,051+ stars .



- **[xTuring](https://github.com/stochasticai/xTuring)**  

  Build, customize, and control your own LLMs from data preprocessing to fine-tuning. 2,663+ stars .



### Additional Strong Open-Source Options



- **[LLM-Finetuning (ashishpatel26)](https://github.com/ashishpatel26/LLM-Finetuning)** — Comprehensive examples of fine-tuning with PEFT across multiple model families .

- **[ZO2](https://github.com/liangyuwang/zo2)** — Zeroth-order offloading enabling **full-parameter fine-tuning of 175B LLMs with only 18GB GPU memory** .

- **[DB-GPT-Hub](https://github.com/eosphoros-ai/DB-GPT-Hub)** — Text-to-SQL fine-tuning with models, datasets, and techniques .

- **[Maestro (Roboflow)](https://github.com/roboflow/maestro)** — Streamlined fine-tuning for multimodal models (PaliGemma 2, Florence-2, Qwen2.5-VL) .

- **[DeepSpeed-Chat-Extension](https://github.com/wangclnlp/DeepSpeed-Chat-Extension)** — Extensions for SFT and RLHF fine-tuning .

- **[SimpleTuner](https://github.com/bghira/SimpleTuner)** — General fine-tuning kit for diffusion models .

- **[OneTrainer](https://github.com/Nerogar/OneTrainer)** — One-stop solution for Stable Diffusion training needs .



**Frameworks for building custom systems**: Combine **Unsloth** or **Axolotl** for training, **PEFT** for parameter-efficient methods, **TRL** for alignment, **LLaMA-Factory** for UI-driven experimentation, and **vLLM** or **SGLang** for high-throughput serving. For distributed training, layer in **DeepSpeed** or **FSDP**. For LoRA serving at scale, **LoRAX** (Predibase) enables thousands of adapters on a single base model .



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Fine-tuning requires careful data preparation, evaluation harnesses, and validation splits to avoid overfitting and catastrophic forgetting.

- Self-hosted training requires GPU infrastructure, proper experiment tracking (W&B, TensorBoard, MLflow), and checkpoint management.

- Always evaluate whether prompting or RAG can solve your problem before committing to fine-tuning — 80% of perceived fine-tuning needs are better addressed upstream .



---



**Made for ML engineers, AI researchers, data scientists, and open-source enthusiasts.**  

Let's make LLM fine-tuning more accessible, efficient, and vendor-neutral.
