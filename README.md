# 📈 Real-time Sentiment Analysis for Consumer Insights (96% Accuracy)

### 🚀 Project Overview
This project is an end-to-end Natural Language Processing (NLP) solution designed to analyze and categorize consumer sentiment in real-time. By processing text data from global feedback datasets, the model classifies feedback into **Positive, Negative, or Neutral** categories with a high degree of precision (**96% accuracy**).

### 🧠 Core Methodology & NLP Logic
The project focuses on capturing the nuances of human language through a sophisticated preprocessing and feature engineering pipeline:

1.  **Advanced Text Cleaning:** * Implemented tokenization, lemmatization (using NLTK), and custom regex filters to handle social media "noise" such as emojis, hashtags, and informal slang.
2.  **Feature Engineering (n-grams):** * Utilized **Bigrams and Trigrams** to capture contextual relationships (e.g., distinguishing between "good" and "not good"), which significantly boosted accuracy over simple unigram word-counting.
3.  **Vectorization Strategy:** * Applied **TF-IDF (Term Frequency-Inverse Document Frequency)** to weigh the importance of specific words across the consumer feedback corpus, ensuring that common "stop words" do not bias the sentiment score.
4.  **Model Architecture:** * Leveraged a **Logistic Regression** base with a tuned **Naive Bayes** classifier for high-speed, real-time inference without sacrificing performance.

### 📊 Technical Impact
- **Accuracy:** 96% on testing datasets.
- **Consumer Insights:** Specifically designed to detect "Brand Sentiment" trends, helping businesses identify service pain points immediately.
- **Real-time Engine:** Optimized the inference pipeline to process and classify incoming text streams in milliseconds.

### 🛠 Tech Stack
- **Languages:** Python (Advanced)
- **NLP Libraries:** NLTK, Scikit-Learn
- **Data Handling:** Pandas, NumPy
- **Environment:** Jupyter Notebook / Anaconda

### 📁 Repository Structure
- `sentiment_analysis.ipynb`: The primary notebook containing data cleaning, model training, and evaluation.
- `consumer_feedback_sample.csv`: Sample data used for real-time inference testing.
- `requirements.txt`: Project dependencies for quick local setup.

### 🚀 How to Run
1. Clone the repository: `git clone https://github.com/Ayushimishra02/Real-time-Sentiment-Analysis.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the notebook to see the real-time classification in action.
