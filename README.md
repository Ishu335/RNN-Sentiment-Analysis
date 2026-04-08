# 🧠 RNN-Based Sentiment Analysis

## 📌 Project Overview
This project implements a **Sentiment Analysis system using Recurrent Neural Networks (RNN)** to classify text into **positive or negative sentiment**.

The model learns contextual relationships in text using sequence modeling techniques, making it effective for Natural Language Processing (NLP) tasks.

---

## 🎥 Demo

![Demo](https://raw.githubusercontent.com/Ishu335/RNN-Sentiment-Analysis/4268d87768b00559202aad072f4ca8583fc04a71/img/rnn_sentiment.gif)

---

## 🧠 Model Architecture

![Architecture](https://raw.githubusercontent.com/Ishu335/RNN-Sentiment-Analysis/4268d87768b00559202aad072f4ca8583fc04a71/img/ChatGPT%20Image%20Apr%208%2C%202026%2C%2010_26_58%20PM.png)

---

## 📊 Dataset
- Text dataset (IMDb / custom dataset)
- Binary classification:
  - Positive sentiment  
  - Negative sentiment  

---

## 🧠 Model Details

The model uses **RNN (LSTM/GRU)** architecture:

- Embedding Layer → Converts words into dense vectors  
- RNN Layer → Captures sequential dependencies  
- Fully Connected Layer → Produces output  
- Sigmoid Activation → Binary classification  

👉 RNN models are effective because they can capture dependencies between words in a sequence, making them suitable for text analysis :contentReference[oaicite:0]{index=0}  

---

## ⚙️ Tech Stack
- Python  
- PyTorch  
- NumPy  
- Matplotlib  
- NLP Techniques  

---

## 🔄 Workflow

1. Data Cleaning (remove special characters, lowercase)
2. Tokenization  
3. Sequence Padding  
4. Model Building (Embedding + RNN)  
5. Model Training  
6. Evaluation & Prediction  

---

## 📈 Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- Loss  

---

## 📊 Results

| Metric   | Value |
|----------|------|
| Accuracy | ~85–90% |
| Loss     | Reduced over epochs |

---

## 📷 Sample Predictions

- **Input:** "This movie was amazing!" → ✅ Positive  
- **Input:** "Worst experience ever." → ❌ Negative  

---

## 🚀 Key Features
- End-to-end NLP pipeline  
- RNN-based sequence modeling  
- Embedding-based text representation  
- Real-time sentiment prediction  

---

## 📁 Project Structure
```
📦 RNN-Sentiment-Analysis
┣ 📂 data
┣ 📂 img
┣ 📂 model
┣ 📜 main.ipynb
┗ 📜 README.md
```
## 💡 Key Learnings
- RNN & LSTM architecture understanding
- Text preprocessing and tokenization
- Sequence modeling for NLP
-  Model evaluation and tuning

 ## 🔮 Future Improvements
- Bidirectional LSTM
- Attention mechanism
- FastAPI deployment
- Streamlit UI
