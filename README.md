# GPT Shakespeare 🧠📜

This project is a personal implementation inspired by transformer-based architectures, primarily grounded in the ideas introduced in the paper **["Attention Is All You Need"](https://arxiv.org/abs/1706.03762)** by Vaswani et al.

The goal of this project is to understand how models like GPT generate coherent text — in this case, mimicking the poetic style of **Shakespeare**.

---

## 📖 What I Learned

While building this project, I studied and explored:

- The **transformer architecture** in detail, including:
  - Multi-head self-attention
  - Positional encoding
  - Layer normalization and residual connections
- How **sequence modeling** works without recurrence
- How transformers are scaled up to build large models like **GPT**
- Tokenization, embedding, and autoregressive text generation

This practical journey has helped me deeply internalize the workings of transformers, far beyond just theory.

---

## 🏗️ Project Overview

- Notebook: [`gpt_project.ipynb`](gpt_project.ipynb)
- Model: Transformer-based text generator
- Dataset: Sampled from Shakespeare’s works (or placeholder text)
- Output: Coherent, Shakespeare-style text samples

---

## 📦 Files

| File                  | Description                          |
|-----------------------|--------------------------------------|
| `gpt_project.ipynb`   | Main notebook containing model code  |
| `README.md`           | This documentation file              |
| `LICENSE`             | MIT License                          |

---

## 🚀 How to Use

1. Open `gpt_project.ipynb` in [Google Colab](https://colab.research.google.com/)
2. Run all cells to train or sample from the model
3. Modify text/data and explore further

---

## 🧠 Next Steps

- Improve sampling quality
- Try training on real Shakespeare datasets
- Experiment with temperature and top-k sampling
- Fine-tune using HuggingFace models

---

## 🪪 License

This project is open-sourced under the [MIT License](LICENSE).

---

*Built with curiosity and caffeination ☕ by Lakshin Khurana.*
