# 📰 Fake News Classifier using LSTM

A deep learning project that classifies news articles as **Real** or **Fake** using **Long Short-Term Memory (LSTM) networks**.  
The model is trained on labeled datasets of news articles and predicts the authenticity of unseen articles.

---

## 👨‍💻 Author
**Abhishek TM**  

---

## 📌 Features
- Text preprocessing (tokenization, stopword removal, padding)  
- Word embeddings for feature representation  
- LSTM-based neural network for classification  
- Training and evaluation on benchmark fake news datasets  
- Provides accuracy, loss plots, and evaluation metrics  

---

## 📂 Project Structure
fake-news-classifier-using-LSTM/
│── data/ # Dataset (or link in README)
│── notebooks/ # Jupyter Notebooks (if any)
│── src/ # Source code
│ ├── preprocess.py # Text preprocessing functions
│ ├── train.py # Model training
│ ├── evaluate.py # Model evaluation
│ └── predict.py # Prediction on new articles
│── models/ # Saved LSTM models
│── requirements.txt # Python dependencies
│── README.md # Project documentation


---

## ⚙️ Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/AbhishekTM/fake-news-classifier-using-LSTM-main.git
   cd fake-news-classifier-using-LSTM-main

Tech Stack

Python
TensorFlow / Keras
NumPy, Pandas
NLTK / spaCy (for text preprocessing)
Matplotlib / Seaborn

Results

1.Achieved high accuracy on benchmark datasets.

2.Metrics: Precision, Recall, F1-Score
