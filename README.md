# 🤖 Meeting Transcript Summarizer (Final Version)

> 🎓 **Course:** AIGC5005 – Advanced Deep Learning  
> 📘 **Project Type:** Midterm + Final Project  
> 👥 **Team Members:** Group 7 – Devi, Chandana, Jaspreet  
> 🌐 **Domain:** Natural Language Processing (NLP)  
> 🧠 **Task:** Abstractive Summarization of Meeting Transcripts

---

## 📝 Project Description

This AI-powered tool automatically generates clean and structured meeting summaries from long, unstructured transcripts. Built using a fine-tuned **T5 Transformer**, the system helps reduce time spent reviewing meeting notes while improving team productivity and knowledge sharing.

The final version improves upon the earlier prototype by integrating better text preprocessing, model optimization using **Optuna**, and evaluation using **ROUGE** and **METEOR** metrics. The tool is trained on real-world meeting transcripts from Kaggle, and offers a user-friendly interface built with **Gradio** for easy summary generation.

---

## 🎯 Objectives

- Clean and preprocess messy meeting transcripts.
- Train a fine-tuned **T5 model** for text-to-text summarization.
- Use **Optuna** for hyperparameter tuning (e.g., input length, learning rate).
- Evaluate using ROUGE and METEOR metrics.
- Build a live demo interface using **Gradio** on Google Colab.

---

## 📊 Dataset & Preprocessing

- **Source:** Kaggle – Meeting Transcript Dataset  
- **Steps:**
  - Byte Pair Encoding tokenization
  - Lowercasing, URL and special character removal
  - Padding/truncating input to 512 tokens, summaries to 128 tokens

---

## 🏗️ Architecture & Tools

- **Model:** T5 (Text-to-Text Transfer Transformer)
- **Hyperparameter Tuning:** Optuna with importance-based pruning
- **Evaluation Metrics:** ROUGE-1, ROUGE-2, ROUGE-L, METEOR
- **Interface:** Gradio on Google Colab

---

## 🚀 Demo Access

A Colab-based demo is included to upload transcripts and receive summarized outputs in real-time using the trained model.

➡️ *[Click here to open the Colab Demo](#)* *(Insert your Colab link here)*

---

## 📂 Repository Structure

Meeting_Summarization/ ├── 📓 Meeting_Summarization_Group7.ipynb # Complete project notebook with data processing, model training, and evaluation ├── 📄 Meeting_Summarization_Group7.pdf # Final presentation slides (project summary) ├── 📄 README.md # Project overview and instructions (this file)
