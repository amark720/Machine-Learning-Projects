# Car Price Prediction

Car Price Prediction is a machine learning-based application designed to predict the price of a used car based on user-provided attributes. It uses the **Random Forest Regression Algorithm** for accurate predictions, providing valuable insights for sellers and buyers of used cars.

<img src="https://github.com/amark720/Amar-kumar/blob/master/ScreenShots/Used%20Car%20Price%20Prediction.png" width=70% height=40%>


## Introduction
This project predicts the price of a used car by considering various attributes such as the car model, mileage, fuel type, and other details provided by the user. The backend is powered by a pre-trained machine learning model using Random Forest Regression, while the frontend is built with Flask for a seamless user experience.

## Features
- Predicts car prices with high accuracy using Random Forest Regression.
- Takes user inputs for attributes like:
  - Year of manufacture
  - Present price
  - Mileage
  - Ownership details
  - Fuel type
  - Seller type
  - Transmission type
- Provides user-friendly input and output interface via a Flask-based web app.
- Outputs the predicted price in an easy-to-understand format.

## Installation Instructions
### Step 1: Clone the Repository
```bash
git clone https://github.com/amark720/Machine-Learning-Projects.git
cd "Car Price Predection & Deployment"
```

### Step 2: Install Dependencies
Install the required Python libraries:
```bash
pip install -r requirements.txt
```

### Step 3: Run the Application
```bash
python app.py
```
- The application will start running at `http://127.0.0.1:5000/`.

### Step 4: Access the Application
Open a browser and navigate to `http://127.0.0.1:5000/` to access the web interface.

## Technologies Used
- **Programming Language:** Python
- **Machine Learning:** Scikit-learn (Random Forest Regression)
- **Web Framework:** Flask
- **Frontend:** HTML, CSS, Jinja2 Templates
- **Libraries:** Pandas, Numpy, Scikit-learn

## How to Use
1. Visit the web application interface.
2. Enter the following details:
   - Year of manufacture
   - Present price of the car
   - Mileage covered (in kilometers)
   - Ownership details (e.g., number of previous owners)
   - Fuel type (Petrol/Diesel)
   - Seller type (Individual/Dealer)
   - Transmission type (Manual/Automatic)
3. Click the **Predict** button.
4. The app will display the predicted price of the car in lakhs.

## Areas of Further Improvement
- **Enhance Model Performance:** Explore advanced models like Gradient Boosting or XGBoost for better accuracy.
- **Data Integration:** Allow users to upload CSV files for batch predictions.
- **User Interface:** Improve UI design for a more intuitive user experience.
- **Cloud Integration:** Deploy the app using services like AWS or Google Cloud for better scalability.
- **Mobile Optimization:** Develop a mobile-friendly version of the app.

## Conclusion
This project demonstrates the practical application of machine learning in predicting used car prices. It provides an accessible tool for users to make informed decisions when buying or selling cars. The integration of Flask ensures a smooth and interactive user experience.

## Acknowledgments
- Thanks to the developers of **Scikit-learn** for providing powerful machine learning tools.
- Appreciation to **Flask** for a simple yet robust web framework.
- Gratitude to the open-source community for the supporting libraries.

#### 📧 Feel Free to contact me at➛ **amark720@gmail.com** for any assistance or questions related to this project!
