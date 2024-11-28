# Stock Sentiment Analysis

This project analyzes the sentiment of stock-related news headlines to predict whether the sentiment is positive or negative. By leveraging the **Scikit-learn** and a **Random Forest Classifier**, the program calculates the sentiment score of stock headlines for a specific date or across multiple dates. The insights gained can be used to make informed decisions about stock trends.

## Features
- **News Headline Sentiment Analysis:**
  - Calculates sentiment scores for stock headlines.
  - Provides a compound sentiment value for each headline.

- **Date-Specific Analysis:**
  - Analyze news headlines for a specific date, all available dates, or today's news.

- **Multiple Stock Analysis:**
  - Input multiple stock ticker symbols (e.g., `AAPL, MSFT, TSLA`) to analyze headlines simultaneously.

- **Predictive Modeling:**
  - Implements a **Random Forest Classifier** to predict the sentiment label (positive or negative) for stock headlines.

- **Bag of Words (BoW):**
  - Uses BoW for feature extraction from headline text, enabling effective training of the Random Forest model.

## Screenshots

### Confusion Matrix
<img src="https://github.com/amark720/Machine-Learning-Projects/blob/main/Stock%20Sentiment%20Analysis%20using%20News%20Headlines/ConfusionMatrix%26Accuracy.jpg" width=50% height=50% >

## Technologies Used
- **Programming Language:** Python
- **Machine Learning:**
  - Random Forest Classifier
  - Scikit-learn
- **Natural Language Processing:**
  - Bag of Words (BoW)
  - CountVectorizer
- **Libraries:** Pandas, NumPy

## How to Use
### Step 1: Clone the Repository
```bash
git clone https://github.com/amark720/Machine-Learning-Projects.git
cd "Stock Sentiment Analysis using News Headlines"
```

### Step 2: Prepare the Dataset
1. Place the dataset file (`Data.csv`) in the project directory.
2. The dataset should include columns for:
   - `Date`: The date of the news headline.
   - `Headline`: The text of the news headline.
   - `Label`: Sentiment labels (positive or negative) for supervised learning.

### Step 3: Run the Python Script
Execute the IPYNB script to preprocess data, train the model, and analyze sentiment:

The program will output:
- Sentiment scores for the headlines.
- Accuracy, confusion matrix, and classification report of the Random Forest model.

## Areas of Further Improvement
- **Dataset Expansion:** Include more comprehensive datasets for better generalization.
- **Advanced Models:** Experiment with deep learning models like LSTMs or transformers (e.g., BERT).
- **Interactive Dashboard:** Develop a web-based dashboard for real-time sentiment analysis.
- **Multilingual Support:** Extend sentiment analysis to non-English headlines.
- **Contextual Analysis:** Incorporate headline context and tone for improved predictions.

## Conclusion
This project demonstrates the use of sentiment analysis and machine learning in financial markets. By analyzing news headlines, the model provides actionable insights into stock trends. The combination of SciKit Learn and Random Forest ensures robust sentiment predictions, making this tool a valuable asset for investors and analysts.

## Acknowledgments
- Gratitude to the developers of Scikit-learn for their machine learning utilities.
- Appreciation to the open-source community for their contributions to Python libraries like Pandas and NumPy.

#### 📧 Feel Free to contact me at➛ **amark720@gmail.com** for any assistance or questions related to this project!
