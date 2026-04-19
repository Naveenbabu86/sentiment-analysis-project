📊 Sentiment Analysis using NLP
🔹 Project Overview

This project performs Sentiment Analysis on user-generated review data using Natural Language Processing (NLP) techniques.
It includes data collection (web scraping), preprocessing, feature engineering (BoW, TF-IDF), and sentiment classification.

🔹 Problem Statement

To build a text processing pipeline that converts raw review text into numerical features and classifies them into positive or negative sentiment.

🔹 Features
✅ Web scraping of review data
✅ Text preprocessing:
Lowercasing
Tokenization
Stopword removal
Punctuation removal
✅ Feature Engineering:
One Hot Encoding (OHE)
Bag of Words (BoW)
TF-IDF
✅ Sentiment classification using Machine Learning
✅ Clean and structured dataset
🔹 Tech Stack
Python
Pandas
NLTK
Scikit-learn
BeautifulSoup
🔹 Project Structure
MiniProj/
│── webscraping.ipynb
│── requirements.txt
│── README.md
│── clean_reviews.csv (optional)
🔹 Installation
Clone the repository:
git clone https://github.com/Naveenbabu86/sentiment-analysis-project.git
Navigate to the project folder:
cd sentiment-analysis-project
Install dependencies:
pip install -r requirements.txt
🔹 Usage
Open and run the Jupyter Notebook:
webscraping.ipynb
Steps performed:
Data scraping
Text preprocessing
Feature extraction (BoW, TF-IDF)
Sentiment classification
🔹 Output
Cleaned review dataset
Feature matrices (BoW, TF-IDF)
Sentiment predictions (Positive/Negative)
🔹 Key Observations
TF-IDF provides better performance than Bag of Words
High sparsity observed in feature matrices
Traditional methods do not capture semantic meaning effectively
🔹 Limitations
Cannot understand context or sarcasm
Ignores word order
Limited performance on complex sentences
🔹 Future Improvements
Use advanced models like BERT
Build interactive dashboard using Streamlit
Use real-time data via APIs (Twitter/Reddit)
