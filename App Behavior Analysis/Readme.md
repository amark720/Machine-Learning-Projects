# APP BEHAVIOR ANALYSIS
![Python](https://img.shields.io/badge/Python-3.8-blue) ![Scikit-learn](https://img.shields.io/badge/Library-ScikitLearn-orange) ![Pandas](https://img.shields.io/badge/Library-Pandas-yellowgreen) ![Numpy](https://img.shields.io/badge/Library-Numpy-lightgrey)


## **Introduction**
This project aims to predict whether a user will continue using an app after it becomes paid. Using a Logistic Regression model, the analysis helps identify users likely to convert into paid customers based on their previous subscription behavior and app usage features. This insight enables businesses to focus their marketing efforts on retaining users with higher conversion potential.


## **Features**
- Predicts app subscription continuation likelihood using Logistic Regression.
- Handles data preprocessing, including scaling, feature selection, and model tuning.
- Evaluates model performance using metrics like accuracy, precision, recall, and F1-score.
- Incorporates advanced techniques like Grid Search for hyperparameter optimization.
- Provides detailed insights into feature importance using model coefficients.


## **Installation Instructions**
### Step 1: Clone the Repository
```bash
git clone https://github.com/amark720/Machine-Learning-Projects.git
cd "App Behavior Analysis"
```

### Step 2: Install Required Libraries
Install the necessary libraries using the following command:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Step 3: Dataset Preparation
Ensure the dataset file (`new_appdata10.csv`) is placed in the project directory. This file contains the user behavior data required for analysis.


## **Technologies Used**
- **Programming Language:** Python 3.8
- **Data Manipulation:** Pandas, Numpy
- **Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn


## **How to Use**
1. **Run the Python Script:**
   Execute the `Project1 - EDA.py` file to perform data preprocessing, model training, and evaluation.
   ```bash
   python "Project1 - EDA.py"
   ```

2. **Preprocessing:**
   - Splits the data into training and test sets.
   - Removes identifiers and scales features for uniformity.

3. **Model Training and Evaluation:**
   - Trains a Logistic Regression model.
   - Evaluates it using k-Fold Cross Validation and Grid Search.

4. **Output Results:**
   - Displays metrics like accuracy, precision, recall, and F1-score.
   - Saves the confusion matrix and final results to the project directory.


## **Areas of Further Improvement**
- **Feature Engineering:** Add more user behavior metrics to improve model performance.
- **Support for Additional Algorithms:** Test advanced models like Random Forest, Gradient Boosting, or Neural Networks.
- **Real-Time Data Integration:** Incorporate live app usage data for continuous prediction updates.
- **Visualization Enhancements:** Develop dashboards for visualizing user retention patterns and predictions.


## **Conclusion**
This project provides a practical solution for predicting app subscription behavior. By identifying potential paid users, businesses can optimize marketing strategies and improve user retention rates. The use of Logistic Regression ensures simplicity, interpretability, and scalability.


## **Acknowledgments**
- Thanks to the **Scikit-learn** team for their comprehensive machine learning tools.
- Appreciation to **Pandas**, **Numpy**, **Matplotlib**, and **Seaborn** for data handling and visualization capabilities.

#### 📧 Feel Free to contact me at➛ **amark720@gmail.com** for any assistance or questions related to this project!
