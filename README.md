# nanoGPT 🧠✨

This project is a personal implementation inspired by transformer-based architectures, primarily grounded in the ideas introduced in the paper **["Attention Is All You Need"](https://arxiv.org/abs/1706.03762)** by Vaswani et al.

The goal of this project is to understand how models like GPT generate coherent text — in this case, mimicking the poetic style of **Shakespeare** using a character-level language model.

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
- Handling external text inputs and modular Python script execution

This practical journey has helped me deeply internalize the workings of transformers, far beyond just theory.

---

## 🏗️ Project Overview

- Notebook: [`gpt_project.ipynb`](gpt_project.ipynb)
- Script: [`gpt.py`](gpt.py)
- Dataset: [`input.txt`](input.txt) — sample training text
- Model: Transformer-based character-level text generator
- Output: Coherent, Shakespeare-style text samples

---

## 📦 Files

| File                  | Description                                  |
|-----------------------|----------------------------------------------|
| `gpt_project.ipynb`   | Main notebook containing model code          |
| `gpt.py`              | Standalone Python script version of notebook |
| `bigram.py`           | Previous version of gpt.py                   |
| `input.txt`           | Sample text input used to train the model    |
| `README.md`           | This documentation file                      |
| `LICENSE`             | MIT License                                  |

---

## 🚀 How to Use

1. Open `gpt_project.ipynb` in [Google Colab](https://colab.research.google.com/)  
   **or** run `gpt.py` locally in your Python environment
2. Ensure `input.txt` is present in the same directory
3. Run the model to train or generate text
4. Modify `input.txt` to train on different data

---

## 🧠 Next Steps

- Improve sampling quality
- Train on the full Shakespeare corpus
- Experiment with temperature and top-k sampling
- Add CLI support to the script
- Fine-tune using HuggingFace models

---

## 🪪 License

This project is open-sourced under the [MIT License](LICENSE).

---

*Built with curiosity and caffeination ☕ by Lakshin Khurana.*
