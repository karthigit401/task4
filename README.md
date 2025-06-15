Task-04: Sentiment Analysis on Social Media Data
This project analyzes and visualizes sentiment patterns in social media data to understand public opinion and attitudes toward specific topics or brands. The dataset used is a Twitter entity sentiment analysis dataset from Kaggle.

📊 Objective
To explore and interpret sentiment-labeled tweets to uncover patterns, trends, and the overall public mood related to various entities on Twitter.

🔍 Dataset
Source: Kaggle – Twitter Entity Sentiment Analysis

Files: Entity_Sentiment.csv

Description: Contains tweets with associated sentiment labels (Positive, Neutral, Negative), as well as named entities.

🛠️ Tools Used
Python

Pandas

Matplotlib / Seaborn

NLTK / TextBlob or Scikit-learn

Jupyter Notebook

📁 Folder Structure

Task-04/
│
├── data/
│   └── Entity_Sentiment.csv         # Raw dataset
│
├── sentiment_analysis_twitter.ipynb  # Main Jupyter Notebook
│
├── output/
│   ├── sentiment_charts/           # Sentiment distribution, word clouds
│   └── cleaned_data.csv            # Preprocessed dataset
│
└── README.md                        # This file
🔧 Steps Performed
Cleaned tweet text (removed URLs, mentions, hashtags, special characters)

Tokenized and normalized text

Visualized sentiment distribution (bar charts, pie charts)

Generated word clouds for each sentiment category

Performed basic NLP techniques: stopword removal, stemming/lemmatization

(Optional) Trained a simple classifier to predict sentiment from tweet text


✅ Status
Project Completed ✅

🙋‍♂️ Author
Karthikeyan Anoop
