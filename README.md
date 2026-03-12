# 📧 SMS Spam Detection using NLP & Machine Learning

Classify SMS messages as **Spam** or **Ham (Not Spam)** using Natural Language Processing and Machine Learning.

## 🎯 Features
- Text preprocessing (lowercase, punctuation removal, number removal)
- TF-IDF Vectorization with bigrams (1,2)
- Multinomial Naive Bayes & Logistic Regression comparison
- Confusion Matrix & Classification Report
- Save/Load trained model using Joblib
- Custom message prediction function

## 📊 Model Performance
| Model | Accuracy |
|-------|----------|
| Naive Bayes | ~97% |
| Logistic Regression | ~98% |

## 🛠️ Tech Stack
- Python, Scikit-learn
- NLP, TF-IDF
- Pandas, NumPy
- Matplotlib, Seaborn

## ⚙️ How to Run
```bash
pip install pandas scikit-learn matplotlib seaborn joblib
