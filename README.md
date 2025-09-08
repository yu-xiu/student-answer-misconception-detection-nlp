# Misconception Detection in Student Short Answers

This project explores **automatic misconception detection** in student open-ended responses using the **SciEntsBank dataset**.  
By combining **state-of-the-art NLP models** (BERT-base, DeBERTa, LLaMA) with **explainable AI techniques** (SHAP).
This project aims to:

- 📖 Classify student answers into *Correct, Partially Correct, Incorrect, Irrelevant*.  
- 🔎 Identify common **misconception patterns** across student populations.  
- 🧩 Provide **interpretable explanations** for model predictions to support teachers and researchers.  

### 🎯 Motivation
Most EdTech systems provide only "right/wrong" judgments, but teachers and students need deeper insights into **why mistakes happen**.  
This project bridges **educational science** and **data science** by uncovering student misconceptions and making model decisions transparent.  

### ✨ Key Features
- Fine-tuned transformer-based models, such as BERT-base (Bidirectional Encoder Representations from Transformer), DeBERTa, and LLaMA for short answer classification.  
- Misconception clustering and visualization to highlight common learning difficulties.  
- Explainability via SHAP for transparent feedback.  
- Jupyter notebooks for reproducibility and easy experimentation.  


### Models
#### Model: BERT-base

[BERT](https://arxiv.org/abs/1810.04805) (*Bidirectional Encoder Representations from Transformers*) is a transformer-based language model introduced by Google in 2018. It was pretrained on large English corpora (BookCorpus and Wikipedia) using two self-supervised tasks:

- **Masked Language Modeling (MLM):** predicting randomly masked words in a sentence.  
- **Next Sentence Prediction (NSP):** predicting whether one sentence logically follows another.  

The **BERT-base** configuration is the standard version of the model with:
- 12 transformer encoder layers  
- Hidden size of 768  
- 12 self-attention heads  
- ~110M parameters  

BERT-base provides a strong balance between efficiency and accuracy and is widely used as a baseline for fine-tuning in downstream NLP tasks such as classification, question answering, and semantic similarity.


### 🚀 Future Work
- Integrating Reinforcement Learning for adaptive feedback.  
- Building a dashboard for teachers to visualize misconceptions.  




## 📜 License
This repository is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)**.  
You may use this work for **research and educational purposes only**.  
👉 [View full license here](https://creativecommons.org/licenses/by-nc/4.0/)
