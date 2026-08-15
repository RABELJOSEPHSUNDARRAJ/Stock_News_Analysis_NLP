# Stock News Sentiment Analysis

## Project Overview

This project analyzes stock-related news articles to predict whether the sentiment is **Positive**, **Neutral**, or **Negative** using Machine Learning and Deep Learning models.

---

## Project Goal

- Analyze stock news sentiment.
- Classify news into positive, neutral, or negative.
- Compare different text embedding techniques and models.
- Find the best model for sentiment prediction.

---

## Dataset

The dataset contains:

- **Date** – News publication date
- **News** – News article
- **Open, High, Low, Close** – Stock prices
- **Volume** – Trading volume
- **Label** – Sentiment (-1, 0, 1)

---

## Methodology

1. Load and clean the dataset.
2. Perform Exploratory Data Analysis (EDA).
3. Convert news into numerical vectors using:
   - Word2Vec
   - Sentence Transformers
4. Train models:
   - Random Forest
   - Neural Network
5. Evaluate model performance using:
   - Accuracy
   - Precision
   - Recall
   - F1-Score

---

## Results

- Dataset had no missing or duplicate values.
- Random Forest performed well on training data but overfitted.
- Neural Network gave better test performance.
- **Sentence Transformer (all-MiniLM-L6-v2) + Neural Network** achieved the best accuracy and F1-score.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras
- Sentence Transformers
- Gensim

---

## Future Improvements

- Reduce overfitting.
- Tune model parameters.
- Try advanced models like BERT or RoBERTa.

---

## Conclusion

This project demonstrates how NLP and Machine Learning can be used to analyze stock news sentiment. Among the models tested, the **Sentence Transformer (all-MiniLM-L6-v2) with Neural Network** provided the best overall performance.
