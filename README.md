# -*- coding: utf-8 -*-
# Sentiment Classification README - Humorous Edition

print("""
# Sentiment Classification with Machine Learning Approaches 🤖💬

Welcome to **Sentimentville**, where words meet emotions, and Yelp reviews meet their destiny! 
This is not just your average machine learning project—it’s an emotional rollercoaster where algorithms judge your text better than your best friend. 🌟

---

## 🚀 Features

- **VaderSentiment**: A quick, gut-level lexicon-based sentiment analyzer. 💬 ➡️ 😄/😡
- **Bag of Words Vectorization**: Text broken down into meaningful chunks—because context matters! 📚
- **TF-IDF Magic**: Highlighting the words that truly matter (like "delicious" over "the"). ✨
- **Model Showdown**:
  - **Naive Bayes**: The simple but effective workhorse. 🐴
  - **SVM**: Sharp and precise—like a samurai sword. 🎯
  - **Logistic Regression**: The classic overachiever. 🧮
- **Sentiment Predictions**: Forget neutrality; it’s all about positive or negative vibes. ⚖️🚫

---

## 🛠️ Installation

Ready to dive in? First, get your toolbox ready by running:

pip install pandas scikit-learn vaderSentiment

## 📖 How It Works
- Import the Dataset: Load Yelp reviews from restaurant_reviews_az.csv.
- VaderSentiment Magic: Classify text as "positive" or "negative" (no gray areas here).
- Train Machine Learning Models: Fit Naive Bayes, SVM, and Logistic Regression models to predict sentiment.
- Performance Metrics: Precision, recall, F1 score—we’ve got them all.
- Predict Fresh Reviews: Watch your model shine on unseen text.

## 📊 Model Comparisons

- VaderSentiment: Quick but basic. Great for small datasets, less so for nuance.
- Naive Bayes: Simple and speedy. Sometimes too simple.
- SVM: Sharp and effective but computationally heavy.
- Logistic Regression: Reliable and robust, especially with TF-IDF.

## 🥳 Example Predictions
- Here’s how the Logistic Regression model performed on fresh reviews:
- Review:
"The service is good, but location is hard to find. Sanitation is not very good with old facilities. Food served tasted extremely fishy."

Prediction: Negative 🙅
- Reasoning: Let’s be honest—fishy food and poor sanitation never end well.
- Review:
"The restaurant is definitely one of my favorites. The food is absolutely delicious!"

Prediction: Positive 🌟
- Reasoning: Favorites and delicious food? A recipe for positivity.
- Review:
"Friendly staff. Good food. Acceptable service."

Prediction: Positive 😊
- Reasoning: The staff carried the day, even if the service didn’t.
  
## 🤝 Acknowledgment
- GenAI Tools: For debugging and making everything feel smarter. 🤖
- Instructional Team: For keeping the project ship sailing straight. 🚢
- Classmates: For their brilliant questions and discussions. 💡
