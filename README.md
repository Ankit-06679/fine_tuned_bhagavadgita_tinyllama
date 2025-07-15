# fine_tuned_bhagavadgita_tinyllama

# 🕉️ Gita LLM Assistant

A Streamlit app powered by a TinyLlama model fine-tuned on the Bhagavad Gita using LoRA and PEFT. It answers spiritual and philosophical questions based on the Gita's teachings.

## 🔧 Tech Stack
- TinyLlama-1.1B-Chat
- HuggingFace Transformers + PEFT + LoRA
- Streamlit App
- Dataset: Bhagavad Gita shlokas, meanings, transliterations

## 🚀 Features
- Answer questions like:
  - *What is karma according to Gita?*
  - *Explain detachment from Bhagavad Gita’s point of view*
- Deployed on: (https://huggingface.co/spaces/Ank-067/Gita-assistant)

## 🧠 Training
Fine-tuned using LoRA on a dataset of 700+ shlokas and meanings.

## 🏁 How to Run
```bash
pip install -r requirements.txt
streamlit run app.py
