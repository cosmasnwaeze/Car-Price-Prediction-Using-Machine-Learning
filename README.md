# Car-Price-Prediction-Using-Machine-Learning
Car Price Prediction Using Machine Learning: Linear Regression,  Decision Tree, Random Forest, and Gradient Boosting

![Car Price ](https://i.postimg.cc/ZqdrHTtQ/Black-and-Blue-Modern-Simple-Car-Dealer-Presentation.png)

## **Introduction**
The **Car Price Prediction** project aims to build a machine learning model that accurately estimates the selling price of used cars based on various features such as brand (make), year of manufacture, mileage, fuel type, transmission type, ownership history, drivetrain, seating capacity, and fuel tank capacity. The project leverages multiple machine learning algorithms to analyze the relationship between these factors and the car’s market value.

The primary goal of this project is to help **buyers and sellers** make informed decisions by providing a reliable price estimate. This can benefit car dealerships, online marketplaces, and individuals looking to sell or purchase used vehicles.

## **Vehicle Dataset**
The dataset consists of key vehicle attributes:
- **Year:** Year of manufacture
- **Kilometer:** Distance the car has traveled
- **Seating Capacity:** Number of seats
- **Fuel Tank Capacity:** Fuel storage in liters
- **Make:** Categorical feature representing car brands (Audi, BMW, Toyota, etc.)
- **Fuel Type:** Type of fuel used (Petrol, Diesel, CNG, etc.)
- **Transmission:** Gear system (Manual or Automatic)
- **Owner:** Ownership history (First, Second, Third, Unregistered)
- **Drivetrain:** Power distribution system (FWD, RWD, AWD)

The dataset has been preprocessed with **one-hot encoding** for categorical features.

## **Machine Learning Models Used**
The following models are trained and evaluated:

1. **Linear Regression:**
   - A basic regression model that assumes a linear relationship between input features and price.
2. **Decision Tree:**
   - A tree-based model that splits data based on feature importance but can overfit easily.
3. **Random Forest:**
   - An ensemble of multiple decision trees to improve accuracy and reduce overfitting.
4. **Gradient Boosting:**
   - A powerful boosting algorithm that corrects previous errors to achieve higher predictive accuracy.




# Model Performance Comparison for Car Price Prediction

## **Key Metrics:**
- **Mean Absolute Error (MAE):** Lower is better.
- **Mean Squared Error (MSE):** Lower is better.
- **R² Score:** Higher is better (closer to 1).

## **Comparison of Models:**

| Model               | MAE (Lower is better) | MSE (Lower is better) | R² Score (Higher is better) |
|---------------------|----------------------|----------------------|------------------|
| **Linear Regression** | 541,179.71           | 630,022,453,937.82   | 0.7994           |
| **Random Forest**    | 329,446.13           | 472,747,493,743.24   | 0.8495           |
| **Gradient Boosting** | 361,704.12           | 421,842,775,840.65   | 0.8657           |
| **Decision Tree**    | 413,004.08           | 707,015,956,832.51   | 0.7749           |

## **Best Performing Model:**
- **Gradient Boosting has the highest R² Score (0.8657), lowest MSE, and relatively low MAE.**  
- **Random Forest is also strong, with a slightly lower R² Score (0.8495) and better MAE than Gradient Boosting.**  
- **Linear Regression and Decision Tree perform worse overall.**


