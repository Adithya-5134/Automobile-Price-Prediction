# 🚗 Automobile Price Prediction 🚀

## 📌 Project Overview
Welcome to the **Automobile Price Prediction** project! This machine learning model predicts the price of automobiles based on various features such as make, fuel type, engine specifications, and other key attributes.

## 📂 Dataset Information

- **📄 File:** automobile.csv  
  
- **📊 Features:**  
  
  - 🔹 **symboling**: Risk factor rating assigned by insurance companies
    
  - 🔹 **normalized-losses**: Relative loss percentage of the car
    
  - 🔹 **make**: Brand of the automobile
    
  - 🔹 **fuel-type**: Type of fuel used (gas/diesel)
    
  - 🔹 **aspiration**: Type of aspiration (std/turbo)
    
  - 🔹 **num-of-doors**: Number of doors in the vehicle
    
  - 🔹 **body-style**: Car body style (sedan, hatchback, etc.)
    
  - 🔹 **drive-wheels**: Type of drive system (FWD, RWD, 4WD)
    
  - 🔹 **engine-location**: Engine placement (front/rear)
    
  - 🔹 **wheel-base**: Distance between front and rear wheels
    
  - 🔹 **length**: Length of the automobile
    
  - 🔹 **width**: Width of the automobile
    
  - 🔹 **height**: Height of the automobile
    
  - 🔹 **curb-weight**: Weight of the automobile without passengers or cargo
    
  - 🔹 **engine-type**: Type of engine (ohc, ohcf, etc.)
    
  - 🔹 **num-of-cylinders**: Number of cylinders in the engine
    
  - 🔹 **engine-size**: Size of the engine in cubic centimeters
    
  - 🔹 **fuel-system**: Type of fuel system (mpfi, carb, etc.)
    
  - 🔹 **bore**: Diameter of the engine cylinder
    
  - 🔹 **stroke**: Length of the piston stroke
    
  - 🔹 **compression-ratio**: Engine compression ratio
    
  - 🔹 **horsepower**: Power output of the engine
    
  - 🔹 **peak-rpm**: Maximum revolutions per minute of the engine
    
  - 🔹 **city-mpg**: Fuel efficiency in city driving (miles per gallon)
    
  - 🔹 **highway-mpg**: Fuel efficiency on highways (miles per gallon)
    
  - 🔹 **price**: Price of the automobile (Target Variable)  

## 🔍 Model Implementation

- **📜 File:** automobile_price_prediction.ipynb  
  
- **🛠️ Steps Followed:**  
  
  1. 🏗️ **Data Preprocessing** - Handling missing values, encoding categorical variables, and feature scaling  

  2. 📊 **Exploratory Data Analysis (EDA)** - Visualizing correlations and data distribution  

  3. 🤖 **Model Selection** - Training multiple regression models  

  4. 📈 **Model Evaluation** - Comparing model performance using various metrics  

## 🤖 Models Used

- 🔹 **Linear Regression**
  
- 🔹 **Decision Tree Regressor**
  
- 🔹 **Random Forest Regressor**
  
- 🔹 **Gradient Boosting Regressor**
  
- 🔹 **XGBoost Regressor**
  
- 🔹 **K-Nearest Neighbors (KNN) Regressor**
  
- 🔹 **MLP Regressor**  

## 📉 Metrics Used

- 📌 **R² Score**
  
- 📌 **Mean Absolute Error (MAE)**
  
- 📌 **Mean Squared Error (MSE)**
  
- 📌 **Root Mean Squared Error (RMSE)**  

## 🔍 Hyperparameter Tuning & Optimization

- Used **GridSearchCV** and **RandomizedSearchCV** to optimize model performance.
  
- Applied **cross-validation** to enhance model generalization.  

## 🔑 Key Insights

- 🚘 **Engine size, horsepower, and curb weight** are the most significant factors influencing automobile prices.
  
- ⛽ **Fuel type and fuel efficiency** also impact pricing but to a lesser extent.
  
- 🔧 **Aspiration (turbocharged vs. standard)** can have an effect on the price due to performance differences.  

## 🎯 Conclusion

This project successfully predicts automobile prices using various machine learning models. The **Decision Tree Regressor** provided the most accurate predictions. The findings highlight that engine specifications, fuel efficiency, and body style are crucial factors in determining the price of an automobile.
