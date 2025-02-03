# Advanced-Sentiment-Analysis
PYTHON( Visual Studio Code ), SQL( SSMS ), EXCEL( CSV )
## Purpose
  This project demonstrates how to perform advanced sentiment analysis using Python, SQL, and various libraries like nltk, pyodbc, and vaderSentiment. It connects to a SQL database to fetch text data, performs sentiment analysis on the data, and categorizes the sentiment score into predefined buckets.

## Requirements
  -Python libraries installed:
    -pandas
    -nltk
    -pyodbc
    -sqlalchemy
    -vaderSentiment

## Steps 
1. **Import pandas, nltk, pyodbc, SentimentIntensityAnalyzer**
   
- `pandas`
- `nltk`
- `pyodbc`
- `sqlalchemy`

2. **Dowload vader_lexicon (Valence Aware Dictionary and sEntiment Reasoner) required for sentiment analysis.**
   
    - `vaderSentiment`
      
3. **Fetch Data from SQL Database**
   
   -Create a function to fetch data from your SQL database using `pyodbc` and `pandas.read_sql()`
   
4. **Perform Sentiment Analysis**

   -Use the `SentimentIntensityAnalyzer` from `nltk` to calculate sentiment scores.
   
5. **Categorize Sentiment Based on Score**

   -Define categories based on sentiment scores (positive, neutral, negative).
   
6. **Bucket Sentiment Scores**

   -Create a function that buckets sentiment scores into predefined text categories.
   
7. **Apply Sentiment Analysis**
   
   -Apply the sentiment analysis function on the dataset to get sentiment scores.
   
8. **Apply Sentiment Categorization**

   -Apply the categorization function to the sentiment scores.
   
9. **Apply Bucketing**

   -Apply the bucketing function on the sentiment scores.
   
10. **Save to CSV File**
  
   -Save the results into a CSV file.
  


