# **Global Tech Job Salary Analysis & Prediction**

## **Project Overview**

This project explores the salary trends in the global tech industry using a dataset containing information on job roles, locations, salaries, and remote work ratios. Machine learning models, including **Random Forest Regressor**, were used to predict salaries based on these factors. The project aims to identify key salary trends and improve predictive accuracy for better salary estimations.

## **Dataset Description**

- The dataset consists of **5,000 records** with no missing values.
- It includes features like job title, experience level, company size, remote work ratio, and salary.
- The dataset spans multiple years, with an **observed exponential increase** in the number of tech jobs and a general salary increase, except for a slight decrease in 2024.

## **Exploratory Data Analysis (EDA) Insights**

- **Top 5 Countries by Tech Jobs:** The majority of tech jobs are concentrated in a few countries. Visualizing the distribution of jobs helps understand geographical salary trends.
- **Remote Work Trends:** The dataset includes **Onsite, Hybrid, and Remote** job roles. The proportion of remote jobs has increased over time.
- **Salary Distribution:** Salaries vary significantly based on experience level and company size.

## **Model Implementation: Random Forest Regressor**

### **Model Performance Metrics**

- **Mean Absolute Error (MAE):** 0.635
- **Mean Squared Error (MSE):** 0.689
- **Root Mean Squared Error (RMSE):** 57,731.35
- **R² Score:** 0.256

### **Interpretation**

- The **low R² score (25.6%)** indicates that the model is not capturing salary trends effectively.
- The **high RMSE** suggests significant deviation between predicted and actual salaries.
- The model currently lacks predictive strength and requires improvements.

## **Recommendations & Next Steps**

### **1. Feature Engineering & Data Processing**

- Convert categorical variables (e.g., job titles, company size) into **better-encoded formats** (e.g., ordinal encoding, one-hot encoding).
- Transform date fields into meaningful **numerical features** (e.g., extracting year, quarter).
- Identify and remove **outliers** that distort salary distributions.

### **2. Model Tuning & Alternative Approaches**

- Perform **hyperparameter tuning** (e.g., adjusting `n_estimators`, `max_depth` in Random Forest).
- Try **Gradient Boosting models** (XGBoost, LightGBM) for better performance.
- Explore **Neural Networks (MLPRegressor)** to capture complex patterns.

### **3. Data Augmentation & More Training Data**

- Increase dataset size to improve generalization.
- Add **external data sources** (e.g., cost of living indexes) to enhance predictions.

## **Conclusion**

This project provides insights into global tech salary trends and highlights areas for improving salary prediction models. Future work will focus on refining feature selection, optimizing model parameters, and incorporating advanced machine learning techniques to enhance prediction accuracy.

---

### **Project Files & Code**

All code and data analysis can be found in this repository. Contributions and suggestions for improvements are welcome!

