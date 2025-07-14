# 📬 Spam Email Detection using Machine Learning

This project detects whether an SMS/email message is **Spam** or **Not Spam (Ham)** using classical machine learning models and NLP techniques.

---

## 📌 Problem Statement

Unsolicited spam messages are a major problem in digital communication. This project uses machine learning to build a text classification model that can automatically classify messages as spam or not spam.

---

## 📂 Dataset

- **Source**: [UCI SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
- **Size**: 5,574 SMS messages
- **Labels**: `ham` (0) = not spam, `spam` (1) = spam

---

## 📊 Project Pipeline

| Step | Description |
|------|-------------|
| ✅ Step 1 | Load & Explore Dataset |
| ✅ Step 2 | Clean & Preprocess Text (NLP) |
| ✅ Step 3 | Visualize Class Balance |
| ✅ Step 4 | Split into Train/Test |
| ✅ Step 5 | TF-IDF Vectorization |
| ✅ Step 6 | Train Models (Logistic Regression, SVM, Random Forest) |
| ✅ Step 7 | Evaluate Accuracy, Precision, Recall, F1-Score |
| ✅ Step 8 | Predict on Custom Test Messages |
| ✅ Step 9 | Plot Confusion Matrix & Share |

---

## ⚙️ Models Used

- 📌 Logistic Regression (Best Accuracy)
- 📌 Support Vector Machine (SVM)
- 📌 Random Forest

---

## 📈 Accuracy Summary

| Model | Accuracy |
|-------|----------|
| Logistic Regression | ~98.5% |
| SVM                  | ~98.3% |
| Random Forest        | ~96.5% |

> Logistic Regression performed best overall.

---

## 🧪 Sample Predictions

```bash
📨 Message: "Congratulations! You've won a free iPhone!"
🧠 Prediction: 📬 Spam

📨 Message: "Don’t forget to bring your ID for the meeting."
🧠 Prediction: 📩 Not Spam
