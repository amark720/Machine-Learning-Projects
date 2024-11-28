# House Price Prediction Analysis

This project is based on the **Kaggle House Price Prediction Competition**. The goal is to predict the sale price of houses using advanced regression techniques while gaining insights into the data through visualization and preprocessing. The project demonstrates how to clean and preprocess the dataset, build multiple regression models, and evaluate their performance.

## Features
- Comprehensive data cleaning and preprocessing:
  - Handling missing values with imputation.
  - Separating categorical and numerical features for specialized processing.
  - Feature scaling using MinMaxScaler.
  - One-hot encoding for categorical variables.
- Implementation of various regression models:
  - Linear Regression
  - Lasso Regression
  - ElasticNet Regression
  - XGBoost
  - LightGBM
- Evaluation using cross-validation to ensure robust model performance.
- Creation of a submission-ready file for Kaggle.

### Training and Validation Results
- Performance of models using cross-validation.
- Comparison of different regression techniques.

## Technologies Used
- **Programming Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning Libraries:** Scikit-learn, XGBoost, LightGBM
- **Environment:** Kaggle Notebook

## How to Use
### Step 1: Clone the Repository
```bash
git clone https://github.com/amark720/Machine-Learning-Projects.git
cd "House Price Predection"
```

### Step 2: Dataset Preparation
1. Download the dataset from Kaggle: [House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques).
2. Place the dataset files (`train.csv`, `test.csv`) in the project directory.

### Step 3: Run the Python IPYNB file
Execute the code cells to preprocess data, train models, and generate predictions:

The script will generate a submission file named `submit.csv` in the project directory.

### My Kaggle Notebook Link -> https://www.kaggle.com/datawarriors/house-price-predection-using-regression

## Areas of Further Improvement
- **Feature Engineering:** Create new features from existing ones (e.g., interaction terms, polynomial features) to improve model performance.
- **Model Optimization:** Perform hyperparameter tuning for XGBoost and LightGBM using GridSearchCV or RandomizedSearchCV.
- **Visualization:** Add more exploratory data analysis (EDA) to better understand correlations and trends.
- **Pipeline Development:** Automate preprocessing, training, and validation steps into a single pipeline for efficiency.
- **Deep Learning Models:** Experiment with neural networks for regression tasks.

## Conclusion
This project showcases how to preprocess data effectively, build multiple machine learning models, and evaluate their performance in predicting house prices. The results highlight the strengths of ensemble models like LightGBM and XGBoost, which achieved high accuracy on this dataset. The generated insights and predictions can be a valuable tool for real estate analysis.

## Acknowledgments
- Thanks to Kaggle for providing the dataset used in this competition.
- Gratitude to the developers of Scikit-learn, LightGBM, and XGBoost for enabling advanced regression techniques.
- Appreciation to the open-source Python community for their invaluable tools and libraries.

#### 📧 Feel Free to contact me at➛ **amark720@gmail.com** for any assistance or questions related to this project!
