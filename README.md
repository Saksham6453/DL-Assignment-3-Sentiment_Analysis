# DL-Assignment-3-Sentiment_Analysis
#Name: Saksham Sharma
Course: MCA (AI & ML)
Subject: Deep Learning
Assignment: 3
Title: Text Sentiment Classification using RNN & LSTM

## 📌 Project Overview

This project focuses on sentiment analysis of movie reviews using deep learning models.
The goal is to classify text into **positive** or **negative** sentiment using sequential models.

---

## 🧠 Models Implemented

* 🔹 Simple RNN (Recurrent Neural Network)
* 🔹 LSTM (Long Short-Term Memory)

---

## 📂 Dataset

* **IMDB Movie Reviews Dataset**
* 50,000 movie reviews
* Binary classification:

  * Positive (1)
  * Negative (0)

---

## ⚙️ Technologies Used

* Python
* TensorFlow / Keras
* NumPy, Pandas
* Matplotlib
* Scikit-learn

---

## 🔄 Workflow

1. Load dataset (pre-tokenized IMDB data)
2. Pad sequences to fixed length
3. Build RNN model
4. Build LSTM model
5. Train models
6. Evaluate performance
7. Plot accuracy & loss graphs

---

## 📊 Results

| Model | Accuracy |
| ----- | -------- |
| RNN   | ~85%     |
| LSTM  | ~88–90%  |

👉 LSTM performs better due to its ability to capture long-term dependencies.

---

## 📈 Visualizations

* Training vs Validation Accuracy
* Training vs Validation Loss

---

## 🧪 Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-score

---

## 🧠 Key Concept

LSTM overcomes the **vanishing gradient problem** of RNN using:

* Forget Gate
* Input Gate
* Output Gate

---

## 📁 Project Structure

```
Sentiment-Analysis-RNN-LSTM/
│
├── Sentiment_Analysis_DL-3.ipynb
├── DL_Assignment_3_Report.pdf
├── README.md
```

---

## 🚀 How to Run

1. Open notebook in Google Colab
2. Run all cells
3. View results and graphs

---

## 👨‍💻 Author

**Saksham Sharma**
MCA (AI & ML)
2501940007

---

## ⭐ Future Improvements

* Add GRU model
* Use custom dataset with Tokenizer
* Hyperparameter tuning
* Deploy using Streamlit

---
