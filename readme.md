# 🚨 Email Job Spam Detection using Machine Learning

An end-to-end machine learning system to detect **fake job and recruitment scam emails** using domain intelligence, behavioral patterns, and explainable features inspired by real-world anti-phishing systems.

---

## 🔍 Problem Statement

Job and recruitment scams are increasingly common and sophisticated. These emails often:
- Impersonate real companies
- Use free or spoofed email domains
- Create false urgency
- Offer jobs without interviews
- Request sensitive personal information

Traditional keyword-based filters or naive text classifiers often fail to capture these patterns reliably.

---

## 💡 Solution Overview

This project builds a **supervised machine learning classifier** that detects scam job emails by converting real-world scam indicators into structured, machine-learnable features.

Rather than relying only on black-box NLP models, the system focuses on **interpretable and explainable signals**, similar to how enterprise email security and fraud detection platforms are designed.

---

## 🧠 Key Features Engineered

- **Sender domain vs claimed company mismatch** (spoofing detection)
- **Free / third-party email domain identification**
- **Urgency and pressure-based language indicators**
- **Job offers without interviews**
- **Presence of suspicious links or attachments**
- **Requests for personal or sensitive information**

---

## ⚙️ Machine Learning Pipeline

1. Data ingestion and inspection  
2. Feature engineering and preprocessing  
3. Train-test split  
4. Model training (classification)  
5. Prediction and evaluation  

The pipeline is implemented end-to-end in a Jupyter Notebook.

---

## 📊 Dataset

The dataset simulates real-world recruitment email scenarios with structured features representing both legitimate and scam emails.

**Target variable:**
- `label` → Scam (1) or Legitimate (0)

---

## 🛠️ Tech Stack

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Jupyter Notebook  

---

## 🎯 Use Cases

- Email security and anti-phishing systems  
- Recruitment platform safety  
- Fraud and risk detection pipelines  
- Trust & Safety machine learning applications  

---

## 🚀 Future Enhancements

- NLP-based feature extraction (TF-IDF / BERT embeddings)
- Model explainability using SHAP
- Hybrid rule + ML scoring system
- Real-time classification API using FastAPI
- Deployment as a production-ready service

---

## 📁 Project Structure

