# Machine Learning from Disaster - Titanic Predictions

This project analyzes the famous Titanic dataset from Kaggle's **"Titanic - Machine Learning from Disaster"** competition. The goal is to predict the survival of passengers based on various features such as age, sex, fare, embarked location, and more. The project demonstrates data preprocessing, feature engineering, and machine learning modeling to achieve accurate predictions.

## Features
- **Data Preprocessing:**
  - Handles missing values in features like `Age`, `Fare`, and `Embarked`.
  - Encodes categorical variables using techniques like one-hot encoding.
  - Normalizes and scales numerical features for better model performance.

- **Feature Engineering:**
  - Creates a new feature `Title` extracted from passenger names.
  - Constructs `Family_Size` and `IsAlone` features from family-related columns (`SibSp` and `Parch`).
  - Extracts cabin types by isolating the first letter from the `Cabin` feature.

- **Modeling:**
  - Implements **Logistic Regression** as the primary classification algorithm.
  - Utilizes performance metrics like accuracy, precision, recall, and F1-score for evaluation.

## Screenshots

### Confusion Matrix & Accuracy
<img src="https://github.com/amark720/Machine-Learning-Projects/blob/main/Titanic%20Survival%20Predection/ConfusionMatrix%26Accuracy.jpg" width=50% height=50% >


## Technologies Used
- **Programming Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Environment:** Jupyter Notebook

## How to Use
### Step 1: Clone the Repository
```bash
git clone https://github.com/amark720/Machine-Learning-Projects.git
cd "Titanic Survival Predection"
```

### Step 2: Dataset Preparation
1. Download the Titanic dataset from [Kaggle](https://www.kaggle.com/c/titanic).
2. Place the dataset files (`train.csv`, `test.csv`) in the `input/` directory.

### Step 3: Run the Python Script
Execute the IPYNB script to preprocess data, train models, and generate predictions:

#### My Kaggle Notebook Link -> https://www.kaggle.com/datawarriors/easy-beginner-titanic-solution

### Output
- A submission file named `1_Logistics_Regression_Submission.csv` will be generated, containing predictions for the test dataset.

## Areas of Further Improvement
- **Advanced Models:** Experiment with ensemble methods like Random Forest, Gradient Boosting, or XGBoost for better accuracy.
- **Hyperparameter Tuning:** Optimize model parameters using techniques like GridSearchCV or RandomizedSearchCV.
- **Deep Learning:** Explore the use of neural networks to improve predictions further.
- **Feature Importance Analysis:** Identify and interpret the most critical features influencing survival.

## Conclusion
This project demonstrates how to preprocess real-world data, engineer meaningful features, and build a machine learning model to solve a classification problem. The insights gained from analyzing Titanic data not only enhance predictive accuracy but also provide a deeper understanding of survival trends.

## Acknowledgments
- Thanks to Kaggle for providing the Titanic dataset for this competition.
- Gratitude to the developers of Scikit-learn, Pandas, and Seaborn for their incredible tools.
- Appreciation to the open-source community for their support and contributions to data science.

#### 📧 Feel Free to contact me at➛ **amark720@gmail.com** for any assistance or questions related to this project!
