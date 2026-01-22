# 🏠 AirBnB Rental Prices Prediction

An end-to-end data science project to predict Airbnb rental prices based on listing features.

## 📌 Project Overview
This project aims to predict Airbnb rental prices using a comprehensive machine learning pipeline. It includes data preprocessing, visualization, feature engineering, model building, and evaluation.
The goal is to identify key factors that influence the price of Airbnb listings and create a model that can estimate rental prices accurately.

## 💡 Key Objectives
* Perform detailed exploratory data analysis (EDA) to understand patterns and relationships.<br>
* Build multiple machine learning models to predict prices.<br>
* Identify important features affecting price.<br>
* Present actionable insights for hosts and travelers.<br>
## 🧠 Skills & Tools Used
* **Languages:** Python<br>
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn<br>
* **Techniques:** Data cleaning, encoding, feature engineering, model comparison, visualization<br>
* **IDE:** Jupyter Notebook
## 📂 Dataset
* **Dataset:** dataSP23.csv
* **Key Columns:**
  * neighbourhood<br>
  * room_type<br>
  * accommodates<br>
  * minimum_nights<br>
  * number_of_reviews<br>
  * availability_365<br>
  * price (Target Variable)
## 🔧 Project Workflow
### 1️⃣ Data Preprocessing
* Handled missing values<br>
* Encoded categorical variables<br>
* Scaled numerical features<br>
* Created new features (like total amenities count)
### 2️⃣ Exploratory Data Analysis (EDA)
* Visualized price distributions<br>
* Compared average price across room types and neighborhoods<br>
* Correlation heatmap to find key influencers<br>
* Outlier detection and removal
### 3️⃣ Feature Engineering
* Created amenities_count and other derived variables<br>
* Transformed skewed columns<br>
* Removed redundant or highly correlated columns
### 4️⃣ Model Building
Trained and compared:<br>

* Linear Regression<br>
* Random Forest Regressor<br>
* Gradient Boosting Regressor<br>
* XGBoost (if applicable)
### 5️⃣ Model Evaluation
* Metrics used: R², RMSE, MAE<br>
* Visualized predicted vs. actual prices<br>
* Identified top features using model feature importances
## 📊 Key Insights
* Room type and location are the most significant factors affecting price.<br>
* Superhost status and number of reviews have a positive impact on price.<br>
* Listings with shorter minimum stay tend to attract higher average prices.<br>
* Best performing model achieved R² ≈ 0.85 and RMSE ≈ 12.4 (update with your actual results).
