# Amazon Review Sentiment Analysis

This project performs sentiment classification on Amazon product reviews using TF-IDF vectorization, logistic regression, and visualization techniques.

## 📁 Dataset

- Columns: `Review`, `Sentiment` (1–5)
- Converted to: `full_text`, `clean_text`, and mapped sentiment labels (positive, neutral, negative)

## 🔧 Tools & Libraries

- Python, Pandas, Scikit-learn
- NLTK, WordCloud, Matplotlib, Seaborn

## 🧠 Key Steps

- Combined and cleaned review text
- Preprocessed text: tokenization, lemmatization, stopword removal
- Converted ratings to sentiment categories
- TF-IDF vectorized up to 5000 features
- Trained Logistic Regression model
- Evaluated with classification report and confusion matrix

## 📊 Visualizations

- WordCloud for positive and negative sentiment
- Confusion matrix heatmap
- Top 10 TF-IDF terms for both positive and negative classes

## ✅ Results

- Sentiment classification on real-world Amazon reviews
- Accuracy score and detailed evaluation
- Clear visualization of key terms influencing sentiment
