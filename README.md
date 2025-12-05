📘 Amazon Electronics Review – Sentiment & Emotion Analysis

A complete NLP project that performs sentiment classification, emotion detection, and business insights extraction using the Amazon Electronics 5-core dataset.

This project applies text preprocessing, TF-IDF vectorization, Logistic Regression, VADER sentiment, and NRC emotion lexicon to understand customer opinions and uncover patterns that can help businesses improve product strategy and customer satisfaction.

⭐ Project Highlights

✔ Sentiment Classification: Positive, Neutral, Negative

✔ Rule-based Analysis using VADER

✔ Emotion Detection using NRC Emotion Lexicon

✔ Machine Learning Model (TF-IDF + Logistic Regression)

✔ Visualizations: Wordclouds, Confusion Matrix, Emotion Bar Chart

✔ Practical Business Insights from review patterns

✔ Optimized for performance with fast preprocessing

📂 Dataset

Dataset: Amazon Electronics Reviews (5-core)
Source: UCSD / McAuley Amazon Review Data Repository
Format: JSON (one review per line)

Columns used:

text → Review text

rating → Star rating (1–5)

sentiment_label → Derived sentiment

clean_text → Preprocessed text

⚠️ Full dataset not included due to size limits.
A 20,000-row sample is provided instead for easy testing.

🧹 Preprocessing Steps

Each review is cleaned using the following steps:

Convert text to lowercase

Remove URLs, HTML tags, numbers, punctuation

Tokenize efficiently using .split() (faster than NLTK tokenizer)

Remove stopwords

Lemmatize words using WordNet

Remove empty rows

Sample dataset to 20,000 reviews for performance

🤖 Machine Learning Pipeline
1️⃣ Train/Test Split

80% training

20% testing

Stratified sampling to preserve class balance

2️⃣ TF-IDF Vectorizer

max_features = 30,000

ngram_range = (1, 2)

min_df = 5

3️⃣ Model

Logistic Regression (max_iter=1000)
Runs fast and performs strongly on text classification.

4️⃣ Metrics

Accuracy

Precision, Recall, F1-score

Confusion Matrix

📊 Visualizations

The notebook includes:

Sentiment Distribution Plot

Positive WordCloud

Negative WordCloud

Confusion Matrix (Heatmap)

Emotion Bar Chart

These enhance your portfolio and make the analysis visually understandable.

🧠 Sentiment Analysis Methods
✔ Rule-Based (VADER)

Works well for social media & short text

Outputs: positive, negative, neutral

✔ Machine Learning

TF-IDF text representation

Logistic Regression classifier

Much better at handling long-form reviews

💬 Emotion Detection (NRC Lexicon)

Each review is analyzed to detect dominant emotions:

joy

trust

anger

fear

sadness

disgust

anticipation

surprise

Useful for understanding why customers feel the way they do.

💡 Key Business Insights
1. What Customers Love

Long battery life

Good performance

Build quality

Value for money

2. Common Pain Points

Product defects

Short lifespan

Poor-quality accessories

Items arriving damaged

3. Emotion Trends

Anger & Disgust → missing parts, broken items

Sadness → expensive products failing

Joy & Trust → strong build and reliable performance

4. Recommendations

Improve quality assurance

Fix commonly failing components

Improve packaging and customer support

Highlight strong features in marketing campaigns

🧑‍💻 Author

Jenil – Data Science Enthusiast
