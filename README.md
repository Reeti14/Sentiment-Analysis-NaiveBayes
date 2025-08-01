# Sentiment Analysis of Product Reviews using Naive Bayes

This project performs **sentiment analysis** on product reviews to determine whether a review is **positive or negative**. It uses **Natural Language Processing (NLP)** techniques and the **Naive Bayes** classification algorithm.

---

## Project Description

The main goal of this project is to analyze product reviews from a dataset and classify them based on sentiment. The classifier is trained to understand the difference between positive and negative reviews using real-world review data.

---

## 🛠️ Implementation Details

- **Programming Language**: Python
- **Libraries Used**:
  - `pandas` for data manipulation
  - `nltk` for text preprocessing (tokenization, stopword removal, stemming)
  - `scikit-learn` for model training and evaluation

- **Steps Followed**:
  1. **Loading the dataset** of product reviews.
  2. **Preprocessing the text**: removing stopwords, stemming, tokenizing.
  3. **Feature Extraction** using TF-IDF (Term Frequency-Inverse Document Frequency).
  4. **Model Training** using the Naive Bayes algorithm.
  5. **Evaluation**: Using accuracy, precision, recall, and a confusion matrix.

---

## ⚙️ How to Run

1. Clone the repo or open the [Colab Notebook](https://colab.research.google.com/drive/1Xe0fKV0T9ECjFuMOmNPP5qMj9y5EG7fw?usp=sharing)
2. Install the requirements:

   ```bash
   pip install -r requirements.txt
3.Run the notebook or script.

🚧 Challenges & Solutions
Challenge	Solution
Handling large datasets	Filtered for a smaller, manageable dataset for model testing
Text preprocessing issues	Used NLTK for efficient cleaning, stemming, and stopword removal
Overfitting & Bias	Tuned TF-IDF parameters and used a simple, interpretable model (Naive Bayes)

📁 Files
sentiment_analysis.ipynb – Main notebook containing the implementation

IMDB Dataset.csv – Review dataset (trimmed for GitHub)

requirements.txt – List of required libraries

📎 Live Demo
Access the Colab version: Click Here

🙋‍♀️ Author
Reeti Singh
BTech CSE | United Institute of Technology
IBM Summer Internship Project – 2025



