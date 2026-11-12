# AI Phishing Detector

## 📌 Project Description

An AI-powered project designed to detect potentially malicious URLs and identify phishing indicators using Machine Learning and URL feature analysis.

---

## 💡 How It Works

The user enters a URL, which is sent to the Flask backend. A Machine Learning model then analyzes the URL and provides a risk assessment based on its characteristics.

---

## 🛠️ Technologies Used

- **Frontend:** HTML + CSS + JavaScript
- **Backend:** Python + Flask
- **Machine Learning:** Scikit-learn
- **Dataset:** Legitimate and phishing URLs
- **Model:** Logistic Regression-based text classification using URL features

---

## 📊 Model Performance

### Training Results

- **Training Samples:** 272,000
- **Testing Samples:** 68,000

### Model Evaluation Results

| Metric | Score |
|--------|-------|
| Accuracy | 95.03% |
| Precision | 94.34% |
| Recall | 95.81% |
| F1-Score | 95.07% |

---

## 📁 Project Structure

```text
AI-Phishing-Detector/
│
├── backend/
│   └── app.py
│
├── frontend/
│   └── index.html
│
├── model/
│   ├── dataset_real.csv
│   ├── dataset.csv
│   ├── phishing_model.pkl
│   ├── train_model.py
│   └── vectorizer.pkl
│
├── requirements.txt
└── README.md
