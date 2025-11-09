# UnSloth.ai Fine-Tuning — Colabs + Videos

This repo contains five Colab notebooks that satisfy the assignment tasks (a)–(e) using Unsloth. Each entry links to the notebook (openable in Colab) and the corresponding short walkthrough video.

## Quick Index

- Colab1 — Full finetune small model (SmolLM2 135M) satisfies (a). Shows raw full parameter update, synthetic chat dataset, chat template creation, inference, optional Hub push.
  - Notebook: `colab1_full_finetune_smollm2.ipynb`  
    Open in Colab: https://colab.research.google.com/github/ArshanBhanage/UnSloth.ai-FineTuning/blob/main/colab1_full_finetune_smollm2.ipynb  
    Video: https://youtu.be/KydipkXbQWg

- Colab2 — LoRA fine-tune (parameter efficient) on Mistral 7B addresses (b). Mirrors the full finetune flow with adapters; optionally swap in SmolLM2 with LoRA.
  - Notebook: `Mistral_Lora_Finetuning_colab_2_.ipynb`  
    Open in Colab: https://colab.research.google.com/github/ArshanBhanage/UnSloth.ai-FineTuning/blob/main/Mistral_Lora_Finetuning_colab_2_.ipynb  
    Video: https://youtu.be/X3py44Eh4Go

- Colab3 — Preference RL via DPO using chosen/rejected pairs satisfies (c). Demonstrates Unsloth’s DPO speed-ups, dataset formatting, and quick qualitative check.
  - Notebook: `Mistral_Lora_Finetuning_Reinforcement_Sentiment_colab_3_.ipynb`  
    Open in Colab: https://colab.research.google.com/github/ArshanBhanage/UnSloth.ai-FineTuning/blob/main/Mistral_Lora_Finetuning_Reinforcement_Sentiment_colab_3_.ipynb  
    Video: https://youtu.be/XR-TC-grdTE

- Colab4 — GRPO multimodal reasoning (vision + math) satisfies (d). Uses MathVista subset, dual rewards (format + correctness), and Gemma‑3 Vision 4B with LoRA.
  - Notebook: `Colab_4_Gemma3_(4B)_Vision_GRPO.ipynb`  
    Open in Colab: https://colab.research.google.com/github/ArshanBhanage/UnSloth.ai-FineTuning/blob/main/Colab_4_Gemma3_(4B)_Vision_GRPO.ipynb  
    Video: https://youtu.be/7i19A6GDdPU

- Colab5 — Continued Pretraining in Hindi satisfies (e). Extends a base LLM’s language capability with QLoRA; saves LoRA + merged weights, shows perplexity.
  - Notebook: `unsloth_cpt_colab5_hindi.ipynb`  
    Open in Colab: https://colab.research.google.com/github/ArshanBhanage/UnSloth.ai-FineTuning/blob/main/unsloth_cpt_colab5_hindi.ipynb  
    Video: https://youtu.be/vKrDBvEAEvo

---

## Extra Notebook (reference)

- `Mistral_Full_Finetuning_colab_1_.ipynb`: Full finetuning Mistral‑7B variant with SFT; heavier than LoRA—use if you have more VRAM.

## Assignment (for reference)

Modern AI with unsloth.ai — Tasks (a)–(e): Full finite‑tuning small model, LoRA PEFT, RL with preferred/rejected pairs (DPO), GRPO reasoning, and Continued Pretraining (CPT).

## Usage

- Click any "Open in Colab" link, run cells top‑to‑bottom, and compare outputs with the video walkthrough.
- For Hub pushes or gated datasets, ensure you’ve accepted terms and configured an HF token.
