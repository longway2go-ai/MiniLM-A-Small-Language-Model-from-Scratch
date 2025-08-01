# 🧠 MiniLM: A Small Language Model from Scratch

MiniLM is a small, efficient, and educational language model built from scratch, inspired by [Karpathy's nanoGPT](https://github.com/karpathy/nanoGPT) and the [TinyStories research paper](https://arxiv.org/abs/2305.07759) by Microsoft. This project is designed to help understand the full lifecycle of training a Transformer-based model, from data preparation to inference, in an accessible and minimalist codebase.

---

## 🚀 Features

- ⚙️ Pure PyTorch implementation — no external training libraries
- 📚 Clean, well-commented code for learning and experimentation
- 🏗️ Modular Transformer architecture
- 🧾 Token-level and character-level tokenization options
- 📉 Training on TinyStories-like synthetic dataset (or your own!)
- 📦 Efficient training with gradient accumulation and mixed precision
- 🧪 Tiny inference script to generate new text from a prompt

---

## 📖 Background

- **nanoGPT**: A compact reimplementation of OpenAI’s GPT-style models by Andrej Karpathy, focusing on readability and simplicity.
- **TinyStories**: A Microsoft Research paper demonstrating that small transformer models (under 10M parameters) can be trained to generate coherent short stories when trained on domain-specific synthetic datasets.

This project blends both ideas: the simplicity and training loop style of nanoGPT with the scale and dataset philosophy of TinyStories.

---

## 🏗️ Architecture

- GPT-style Transformer decoder
- Causal self-attention
- Positional embeddings
- Configurable depth and width (e.g., 2-6 layers, 128-512 hidden units)
- Dropout for regularization

---
