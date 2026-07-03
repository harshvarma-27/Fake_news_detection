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
---

## ⚙️ Machine Learning Pipeline

```text
News Dataset
     │
     ▼
Text Cleaning
     │
     ▼
Tokenization
     │
     ▼
TF-IDF Vectorization
     │
     ▼
Model Training
     │
     ▼
Prediction
     │
     ▼
Fake / Real Classification
```

---

## 🛠️ Tech Stack

### Programming Language
- Python

### Libraries
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn

---

## 📂 Project Structure

```text
Fake_news_detection/
│
├── fake_news_dataset.csv
├── fake_news_detection.ipynb
├── model.pkl
├── requirements.txt
└── README.md
```

---

## 🎯 Learning Outcomes

This project helped in understanding:

- Natural Language Processing (NLP)
- Text Classification
- TF-IDF Vectorization
- Machine Learning Model Comparison
- Feature Engineering
- Classification Metrics
- Confusion Matrix Analysis

---

## 🔮 Future Enhancements

- BERT-based fake news detection
- Transformer models
- Real-time news verification
- Browser extension integration
- Multi-language support
- Explainable AI predictions

---

## 👨‍💻 Author

Harsha Vardhan Varma

GitHub: https://github.com/harshvarma-27
### 🧾 Example: Confusion Matrix & Classification Report (MultinomialNB)

