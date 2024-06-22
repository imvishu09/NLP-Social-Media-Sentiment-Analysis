# Twitter Sentiment Analysis

## Overview

This repository contains code for a Twitter sentiment analysis project. The project utilizes machine learning models to classify tweets as either positive or negative. The primary goal is to provide a tool for understanding public sentiment on Twitter, which can be valuable for various applications, such as brand monitoring, social media analytics, and market research.

## Key Features

- **Data Preprocessing:** Thorough cleaning of tweet data to remove noise, usernames, special characters, and apply stemming for better feature extraction.
- **Exploratory Data Analysis (EDA):** Visualization of word clouds and hashtag analysis to uncover patterns in positive and negative tweets.
- **Machine Learning Models:** Implementation and evaluation of multiple machine learning models, including Logistic Regression, XGBoost, and Decision Tree, using both Bag-of-Words and TF-IDF features.
- **Streamlit App:** An interactive web application built with Streamlit allows users to input tweets and receive real-time sentiment predictions.

## Project Structure

- **`train.csv`:** The training dataset containing tweets labeled as positive (0) or negative (1).
- **`test.csv`:** The test dataset used for evaluating model performance.
- **`twitter_sentiment.pkl`:** The trained machine learning model saved in pickle format.
- **`app.py`:** The Streamlit application code.
- **`model_code.ipynb`:** Jupyter Notebook containing the code for data preprocessing, EDA, model training, and evaluation. (**Note:** This might be a `.py` file depending on how you structured your code.)

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/twitter-sentiment-analysis.git
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
   
3. **Run the Streamlit app:**
   ```bash
   streamlit run app.py
   ```

## Usage

1. Open the Streamlit app in your web browser.
2. Enter a tweet in the text input box.
3. Click the "Predict" button to get the sentiment prediction (positive or negative).

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to improve this project.

## Acknowledgments

The dataset used in this project was sourced from the following GitHub repository:
[https://github.com/dD2405/Twitter_Sentiment_Analysis](https://github.com/dD2405/Twitter_Sentiment_Analysis)
Please see the above source for the dataset's license and terms of use.

## Contact

For any questions or feedback, feel free to contact me at imvishu09@gmail.com.
