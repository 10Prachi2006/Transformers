# 📚 Transformer & LLM Papers Roadmap

This is a curated collection of the most important papers that shaped the modern Transformer ecosystem.

---

# 🏛 Foundation of Transformers

## 1. Attention Is All You Need (2017)
**Authors:** Vaswani et al.

Paper:
https://arxiv.org/abs/1706.03762

Why it matters:
- Introduced the Transformer architecture
- Removed recurrence entirely
- Introduced Self-Attention, Multi-Head Attention, Positional Encoding
- Started the modern LLM era

Read if:
You want to understand where everything began.

---

# 🧠 Understanding Attention

## 2. Effective Approaches to Attention-Based Neural Machine Translation (2015)

Authors:
Luong et al.

Paper:
https://arxiv.org/abs/1508.04025

Why it matters:
- Popularized attention mechanisms before Transformers
- Shows the transition from RNNs → Attention

---

## 3. Neural Machine Translation by Jointly Learning to Align and Translate (2014)

Authors:
Bahdanau et al.

Paper:
https://arxiv.org/abs/1409.0473

Why it matters:
- First major attention mechanism
- Solved encoder bottleneck problem

---

# 🤖 BERT Family

## 4. BERT: Pre-training of Deep Bidirectional Transformers (2018)

Authors:
Devlin et al.

Paper:
https://arxiv.org/abs/1810.04805

Why it matters:
- Introduced bidirectional Transformer pretraining
- Revolutionized NLP benchmarks

Used by:
- BERT
- RoBERTa
- DistilBERT

---

## 5. RoBERTa (2019)

Paper:
https://arxiv.org/abs/1907.11692

Why it matters:
- Improved BERT training methodology

---

# 🚀 GPT Family

## 6. Improving Language Understanding by Generative Pre-Training (GPT)

Paper:
https://cdn.openai.com/research-covers/language-unsupervised/language_understanding_paper.pdf

Why it matters:
- First GPT model

---

## 7. Language Models are Few-Shot Learners (GPT-3)

Paper:
https://arxiv.org/abs/2005.14165

Why it matters:
- Demonstrated scaling laws
- Emergent capabilities

---

## 8. GPT-4 Technical Report

Paper:
https://arxiv.org/abs/2303.08774

Why it matters:
- Large-scale frontier model insights

---

# 🔄 Encoder-Decoder Models

## 9. Exploring the Limits of Transfer Learning with T5

Paper:
https://arxiv.org/abs/1910.10683

Why it matters:
- Unified all NLP tasks as text-to-text

---

# 📏 Scaling Laws

## 10. Scaling Laws for Neural Language Models

Paper:
https://arxiv.org/abs/2001.08361

Why it matters:
- Explained how performance scales with model size

---

## 11. Chinchilla

Paper:
https://arxiv.org/abs/2203.15556

Why it matters:
- Compute-optimal training
- Changed industry training practices

---

# 🧭 Positional Encoding

## 12. RoFormer: Rotary Position Embedding (RoPE)

Paper:
https://arxiv.org/abs/2104.09864

Why it matters:
- Introduced RoPE
- Dominant positional encoding in modern LLMs

Used by:
- LLaMA
- Claude
- Gemini
- Mistral

---

## 13. ALiBi

Paper:
https://arxiv.org/abs/2108.12409

Why it matters:
- Relative position bias without embeddings

---

# ⚡ Efficient Attention

## 14. FlashAttention

Paper:
https://arxiv.org/abs/2205.14135

Why it matters:
- Faster exact attention
- Massive memory savings

---

## 15. FlashAttention-2

Paper:
https://arxiv.org/abs/2307.08691

Why it matters:
- Better GPU utilization

---

## 16. FlashAttention-3

Paper:
https://arxiv.org/abs/2407.08608

Why it matters:
- Optimized for H100 GPUs

---

# 💾 Inference Optimization

## 17. Fast Transformer Decoding (Multi-Query Attention)

Paper:
https://arxiv.org/abs/1911.02150

Why it matters:
- Introduced MQA

---

## 18. GQA: Generalized Multi-Query Transformer

Paper:
https://arxiv.org/abs/2305.13245

Why it matters:
- Standard KV-cache optimization today

Used by:
- LLaMA 3
- Gemma
- Mistral

---

# 🎯 Fine-Tuning

## 19. LoRA

Paper:
https://arxiv.org/abs/2106.09685

Why it matters:
- Fine-tune billion-parameter models cheaply

---

## 20. QLoRA

Paper:
https://arxiv.org/abs/2305.14314

Why it matters:
- Fine-tuning on consumer GPUs

---

# 🧑‍🏫 Alignment

## 21. InstructGPT

Paper:
https://arxiv.org/abs/2203.02155

Why it matters:
- RLHF enters mainstream

---

## 22. Direct Preference Optimization (DPO)

Paper:
https://arxiv.org/abs/2305.18290

Why it matters:
- Simpler alternative to RLHF

---

# 🤝 Mixture of Experts

## 23. Switch Transformer

Paper:
https://arxiv.org/abs/2101.03961

Why it matters:
- Sparse activation at scale

---

## 24. Mixtral of Experts

Paper:
https://arxiv.org/abs/2401.04088

Why it matters:
- Modern open-source MoE

---

# 🌍 Multimodal Models

## 25. CLIP

Paper:
https://arxiv.org/abs/2103.00020

Why it matters:
- Vision-language alignment

---

## 26. Flamingo

Paper:
https://arxiv.org/abs/2204.14198

Why it matters:
- Few-shot multimodal learning

---

# 📖 Recommended Reading Order

1. Attention Is All You Need
2. Bahdanau Attention
3. BERT
4. GPT-3
5. T5
6. Chinchilla
7. RoPE
8. FlashAttention
9. GQA
10. LoRA
11. InstructGPT
12. DPO
13. Switch Transformer
14. CLIP

---
Built alongside the Transformer Masterclass.