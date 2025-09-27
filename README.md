Project Description

The Ford Car Price Prediction project is a machine learning application designed to predict the selling prices of used Ford cars based on historical data.

The dataset includes key features such as:

Model – Car model name (e.g., Fiesta, Focus, Mondeo).

Year – Manufacturing year of the car.

Transmission – Type of transmission (Manual, Automatic, Semi-Auto).

Fuel Type – Type of fuel used (Petrol, Diesel, Hybrid, etc.).

Mileage – Distance traveled by the car.

Tax – Road tax applicable to the vehicle.

MPG – Miles per gallon (fuel efficiency).

Engine Size – Size of the engine in liters.

By analyzing these features, the model predicts the price of a Ford car, helping users estimate fair resale values.

The project involves:

Data Cleaning & Preprocessing – Handling missing values, encoding categorical features, and scaling numeric data.

Exploratory Data Analysis (EDA) – Understanding patterns, distributions, and correlations between features.

Model Training – Applying machine learning models such as Linear Regression, Random Forest, and Gradient Boosting.

Evaluation – Comparing models using metrics like MAE, RMSE, and R².
# 🚗 Ford Car Price Prediction

A machine learning project that predicts the price of used Ford cars based on their features such as model, year, transmission, fuel type, mileage, engine size, and fuel efficiency.

---

## 📌 Features in Dataset
- **model**: Car model name (e.g., Fiesta, Focus, Mondeo)  
- **year**: Year of manufacture  
- **transmission**: Type of transmission (Manual, Automatic, Semi-Auto)  
- **fuelType**: Type of fuel (Petrol, Diesel, Hybrid, etc.)  
- **mileage**: Distance traveled by the car (in miles)  
- **tax**: Road tax applicable  
- **mpg**: Miles per gallon (fuel efficiency)  
- **engineSize**: Engine size in liters  
- **price**: Target variable (selling price of the car)  

---

## 🛠️ Steps in the Project
1. **Data Preprocessing**
   - Handled missing values  
   - Encoded categorical variables (Label Encoding / One-Hot Encoding)  
   - Normalized numerical features  

2. **Exploratory Data Analysis (EDA)**
   - Distribution of car prices  
   - Year-wise price trends  
   - Transmission and fuel type impact on price  
   - Boxplots, scatterplots, and correlation heatmaps  

3. **Modeling**
   - Implemented regression models:  
     - Linear Regression  
     - Random Forest Regressor  
     - Gradient Boosting Regressor  
   - Evaluated using MAE, RMSE, and R²  

4. **Results**
   - Random Forest and Gradient Boosting performed best with high R² scores.  
   - Feature importance showed **year, mileage, and model** had the most influence on price.  

---

## 📊 Technologies Used
- **Python**  
- **Pandas, NumPy** – Data manipulation  
- **Matplotlib, Seaborn** – Visualization  
- **Scikit-learn** – Machine Learning models  

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone <repo-link>

2. Run the Jupyter Notebook or Python script

   📈 Example Prediction

Input:

Model: Fiesta  
Year: 2018  
Transmission: Manual  
Fuel Type: Petrol  
Mileage: 25,000 miles  
Engine Size: 1.0L  
MPG: 55  
Tax: 145


Output:

Predicted Price: £9,500 (approx)

Conclusion

This project shows how machine learning can be applied in the automotive industry to estimate fair resale prices of cars. The model provides valuable insights for buyers, sellers, and dealerships by reducing guesswork and making pricing decisions more data-driven.

Visualization – Boxplots, scatter plots, and feature importance graphs to interpret results.

This project demonstrates the application of data science and machine learning techniques in the automotive domain, with practical use in car dealerships, resale platforms, and buyers/sellers.
