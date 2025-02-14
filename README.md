# House-Price-Prediction
Project Overview
This project focuses on:

 Predicting house prices using machine learning techniques.
 Supporting better decision-making in real estate investments and property valuation.
---

Dataset

  King County House Sales Data:

   Contains 21,613 records with features such as square footage, number of bedrooms, bathrooms, and location.
   Covers various property attributes critical for price determination.

---

**Objective**
The project goals include:

   Performing exploratory data analysis to uncover insights.
   Cleaning and preprocessing the dataset to ensure data quality.
   Building and evaluating a machine learning model to predict house prices.
   Identifying key factors influencing housing costs.

---

**Project Workflow**

  1. Data Collection and Loading:  
   - Utilized the King County dataset containing property features and prices.  

2. Data Preprocessing:  
   - Dropped irrelevant columns and handled missing values in critical features like bedrooms and bathrooms.  
   - Converted the `date` column to datetime format for enhanced analysis.  

3. Feature Engineering:  
   - Retained impactful features like square footage, bedrooms, and bathrooms.  
   - Extracted temporal information from the `date` column.  

4. Exploratory Data Analysis (EDA):  
   - Visualized relationships between house prices and key features using scatter plots.  
   - Created a correlation heatmap to identify significant predictors of price.  

5. Modeling:  
   - Implemented a Random Forest Regressor to predict house prices.  
   - Split data into training and testing sets (80-20 split).  

6. Evaluation:  
   - Assessed model performance using metrics:  
     - Mean Squared Error (MSE): 21,351,347,796  
     - R² Score: 0.86  

---

**Results**

- Achieved an R² score of 0.86, demonstrating strong predictive power.  
- Identified key features such as square footage and number of bedrooms as the most influential factors in determining house prices. 

---

**Tools and Technologies**

- Programming Language: Python  
- Libraries:  
  - Data Analysis: Pandas, NumPy  
  - Visualization: Matplotlib, Seaborn  
  - Machine Learning: scikit-learn
 
Colab Notebook

   Explore the full implementation of this project in the [Colab Notebook](https://colab.research.google.com/drive/18DbCWPpkjYvJ7xinQU74vJtjFwE-eNjV?usp=sharing).
