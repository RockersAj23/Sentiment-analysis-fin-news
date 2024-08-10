# Stock Sentiment Analysis

This repository contains a Jupyter notebook that performs sentiment analysis on stock-related news headlines. The goal is to predict whether the sentiment expressed in the headlines is positive, negative, or neutral, which can be used to inform stock trading decisions.

## Project Overview
- **Data**: The dataset includes news headlines, dates, and corresponding stock prices.
- **Objective**: Analyze the sentiment of news headlines to predict their impact on stock prices.
- **Techniques**: The project employs Natural Language Processing (NLP) techniques, including text preprocessing, vectorization, and machine learning models, to classify sentiment.

## Key Features
- **Data Preprocessing**: Handling missing values, text cleaning, and feature engineering.
- **Exploratory Data Analysis (EDA)**: Visualization of sentiment distribution and data patterns.
- **Sentiment Model**: A machine learning model trained to classify the sentiment of headlines.
- **Model Evaluation**: Metrics such as accuracy, precision, recall, and F1-score to assess model performance.

## Getting Started
1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/stock-sentiment-analysis.git
    ```
2. **Install the necessary dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
3. **Run the notebook**:
    Open the `Stock Sentiment Analysis.ipynb` notebook and run the cells in sequence.

## Dependencies
- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib

## Results
The final model achieves 0.85449 on the test data, making it a valuable tool for predicting the sentiment of stock-related news.

## Conclusion
This project demonstrates the application of NLP in finance, providing insights that can potentially guide trading strategies.
