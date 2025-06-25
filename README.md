# Fake_news_detection
# Fake News Detection using Machine Learning

This project uses Natural Language Processing (NLP) and various machine learning models to classify news articles as **real** or **fake** based on their text content.

## 💡 Objective

To build a reliable machine learning model that detects misinformation in news articles using textual analysis. This can help fight the spread of fake news online.

---

## 🗃️ Dataset Overview

- **File**: `fake_news_dataset[1].csv`
- **Size**: 20,000 news articles
- **Columns used**: `text`, `label`
- **Target Classes**:  
  - `real` → 0  
  - `fake` → 1

---

## 🧠 Models Used

The following machine learning models were trained and evaluated:

- PassiveAggressiveClassifier
- Logistic Regression
- Random Forest
- Decision Tree
- Support Vector Machine (SVM)
- Multinomial Naive Bayes

All models were trained using TF-IDF vectorized news text.

---

## 🧪 Model Performance

Here are the **accuracy scores** of each model on the test dataset (4,000 samples):

| Model                      | Accuracy |
|---------------------------|----------|
| PassiveAggressiveClassifier | 50.35%   |
| Logistic Regression       | 51.12%   |
| Random Forest             | 50.00%   |
| Decision Tree             | 49.80%   |
| Support Vector Machine    | 49.98%   |
| Multinomial Naive Bayes   | 50.85%   |

### 🧾 Example: Confusion Matrix & Classification Report (MultinomialNB)

