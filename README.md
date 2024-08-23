Sentiment Analysis and Domain Classification of Tweets using PySpark, BERT, and Azure

## Description:
This project focuses on sentiment analysis and domain classification of tweets. The goal is to categorize tweets into positive or negative sentiments and classify them into various domains like politics, education, etc. The project leverages PySpark for processing large datasets, BERT for transfer learning, and Azure Databricks for scalable data processing.

## Technologies Used: 
- Python
- PySpark
- BERT
- Streamlit
- Azure Databricks
- Selenium for web scraping

## Project Structure:
├── data
│   ├── final_dataset_twitter.csv
│   └── new_data_by_american_news.csv
├── notebooks
│   ├── twitter-16gb.ipynb
│   └── selenium-extracted-tweets.ipynb
|   └── concat-dataframe.ipynb
|   └── BERTFinal.ipynb
├── Azure
│   ├── pyspark.ipynb
├── Streamlit
│   ├── app.py
│   └── requirements.txt
└── README.md

## Features
- Sentiment analysis using pre-trained BERT models.
- Domain classification of tweets into categories like politics, education, etc.
- Scalable data processing with PySpark.
- User-friendly interface built with Streamlit.
