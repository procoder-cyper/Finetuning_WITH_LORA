
# 🧠✨ Implementing the LoRA Paper with TinyLlama 🦙💡

Welcome to my implementation of the 🔬 **LoRA (Low-Rank Adaptation)** paper, applied to a real-world fine-tuning task using 🦙 `TinyLlama-1.1B-Chat`! This project showcases **parameter-efficient fine-tuning** on the 📐 **GSM8K** dataset (grade-school math questions) using 4-bit quantization, Hugging Face 🤗 tools, and LoRA magic 🧪.

> ✅ This repo contains a clean and practical implementation of the **LoRA paper** (paper included in repo 📄) for small-scale large language model fine-tuning!

---

## 🚀 Project Highlights

✨ **Model:** `TinyLlama/TinyLlama-1.1B-Chat`  
📚 **Dataset:** `openai/gsm8k` (subsampled)  
🔧 **Techniques Used:**
- 🧠 **LoRA (Low-Rank Adaptation)** — lightweight, modular fine-tuning!
- 🧮 **BitsAndBytes 4-bit quantization** — memory-efficient training
- 🧰 **Hugging Face Transformers, PEFT, Datasets** — the modern NLP toolkit
- 🧪 **Causal Language Modeling** — solving math problems via generation!

---

## 📓 Notebook: What’s Inside

- 📥 Model loading & quantization
- 🔗 Injecting LoRA adapters into attention layers
- 📊 Dataset loading + tokenization
- 🏋️‍♂️ Fine-tuning on GSM8K
- 🧪 Evaluation using exact-match accuracy
- 📉 Logging and results output

---

## 🗃️ Repo Structure

```
📁 project-root/
├── Finetuning_LORA.ipynb       # Main training notebook 📓
├── README.md                   # You're reading it! 😎
├── LoRA-Paper.pdf              # The original LoRA paper 📄

