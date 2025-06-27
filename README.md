# llm-ch1-textgen-playground
Based on Chapter 1 of Hands-On LLMs: Interactive Microsoft/phi-3-mini-4k-instruct text generation playground using Colab
# 🤖 Phi-3 Mini Instruction-Tuned LLM Demo

A lightweight text generation project using **Microsoft’s `phi-3-mini-4k-instruct`** — a compact, open-weight language model fine-tuned for instruction-following tasks.

This project lets users interact with the model through custom prompts and explores how well it handles real-world queries using Hugging Face's Transformers library.

---

## 🚀 Quick Demo

> **Prompt**: “Explain transformers to a 10-year-old.”  
> **Output**: “Imagine your brain is trying to read a book really fast, but it needs to remember every important word. Transformers help by keeping track of what’s important and what comes next—like a super memory!”

---

## 📚 About the Model

- **Model**: [`microsoft/phi-3-mini-4k-instruct`](https://huggingface.co/microsoft/phi-3-mini-4k-instruct)
- **Size**: ~1.8B parameters
- **Context Length**: 4,000 tokens
- **Purpose**: Instruction-following, helpful assistant tasks
- **License**: MIT

---

## 🧪 Features

- 🧠 Prompt-based generation with `phi-3-mini-4k-instruct`
- 🛠 Adjustable parameters: temperature, max tokens, top-k, top-p
- 🔍 Clean and simple interface (optional: via Streamlit)
- 📦 Deployable on CPU or GPU (works well even in limited environments)

---

## 🛠 Setup Instructions

### 🔗 1. Clone the Repo

```bash
git clone https://github.com/eddymontana/phi3-mini-instruct-demo.git
cd phi3-mini-instruct-demo
