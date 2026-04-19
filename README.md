# Assignment Title

Sentiment Analysis of Tweets on Taylor Swift

## (1) Problem Statement

Describe the problem.
The problem is to perform sentiment analysis on tweets related to Taylor Swift by classifying them into positive, neutral, or negative sentiments using machine learning techniques.

## (2) Objective

* Define the goal.
  The goal is to analyze tweets and build classification models to accurately predict the sentiment of each tweet.

## (3) Dataset

* Source:
  Manually created dataset of 100 tweets related to Taylor Swift.
* Features:
  Tweet text and sentiment label (Positive, Neutral, Negative).
* Size:
  100 tweets

## (4) Methodology

1. Data Preprocessing
   Text was converted to lowercase, stopwords were removed, and data was cleaned.
2. EDA
   Basic exploration of dataset including distribution of sentiments.
3. Model Building
   Naive Bayes, SVM, and Logistic Regression classifiers were used with TF-IDF vectorization.
4. Evaluation
   Models were evaluated using Accuracy, Precision, and Recall metrics.

## (5) Results

* Metrics and insights
  Logistic Regression performed the best with higher accuracy, precision, and recall compared to Naive Bayes and SVM.

## (6) How to Run

```bash
pip install -r requirements.txt
python main.py
```

## (7) Conclusion

Summarize findings.
Sentiment analysis was successfully performed on the dataset, and Logistic Regression was found to be the most effective model for this task.

## (8) Student's details

* Name: Ansari Mohammed Huzaifa
* Roll No: 02
* UIN: 231A007
* YEAR: TE-AIDS
