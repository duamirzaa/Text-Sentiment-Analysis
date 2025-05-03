# Text-Sentiment-Analysis
A sentiment analysis model trained on movie reviews to classify them as positive or negative, including the ability to analyze reviews written in Gen Z slang or informal language.
# 🎬 Text Sentiment Analysis on Movie Reviews (Including Gen Z Language)

This project applies **Natural Language Processing (NLP)** to perform **sentiment analysis** on a movie reviews dataset. The model classifies reviews as **positive** or **negative**, and is designed to handle a wide range of review styles — including modern, informal, or **Gen Z-style comments**.

---

## 🧠 Project Objective

- Analyze the sentiment of user-generated movie reviews.
- Build a model that can handle informal language and slang.
- Classify each review as either positive or negative.

---

## 🗂️ Dataset

- Source: it's included
- Format: CSV file
- Features:
  - `review`: The text of the movie review
  - `sentiment`: Target label (`positive` or `negative`)

---

## 🔧 Tools & Libraries

- Python
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn
- NLTK or spaCy
- Matplotlib, Seaborn

---

## 📊 Key Steps Performed

- Text preprocessing:
  - Lowercasing, punctuation removal, tokenization
  - Stopword removal and optional stemming/lemmatization
- Feature extraction using **TF-IDF**
- Model training with **Logistic Regression / Naive Bayes**
- Model evaluation with **accuracy**, **confusion matrix**, etc.
- Tested with casual and Gen Z-style comments to ensure generalization

---

## ✅ Sample Results

- `"this movie was so mid but kinda funny ngl"` ➝ **Negative**
- `"absolute banger. 10/10 would watch again!"` ➝ **Positive**
- `"the plot was fire but the acting was cringe"` ➝ **Mixed / depends on polarity** ➝ **Mostly Positive/Negative** *(based on dominant words)*

---



## 💡 Highlights

- Handles informal and Gen Z-style comments (e.g., "mid", "fire", "cringe")
- Robust preprocessing pipeline
- Well-suited for real-world online review platforms

---

## 🚀 Future Improvements

- Add sarcasm detection
- Extend model to classify **neutral** or **mixed** sentiment
- Train on multilingual or code-mixed datasets

---

## 📬 Contact

Open an issue or reach out for collaboration or suggestions!

