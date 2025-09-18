# Customer Spending Prediction

## Project Overview

This project focuses on identifying potential high-spending customers using supervised machine learning techniques. The objective is to support marketing strategy by predicting which customers are most likely to respond positively to credit card marketing campaigns.

## Dataset Description

The dataset includes demographic and behavioral attributes such as:

- Gender  
- Age  
- Annual Income  
- Spending Score  
- Tenure  
- Credit Card Ownership  
- Number of Bank Products Used  
- Estimated Salary  

**Target Variable**: Indicates whether the customer is a potential high spender (`Yes` or `No`).

## Objectives

- Perform exploratory data analysis (EDA)  
- Clean and preprocess the data  
- Train classification models  
- Evaluate model performance  
- Predict high-value customers  

## Technologies Used

- Python 3  
- Pandas, NumPy  
- Seaborn, Matplotlib  
- Scikit-learn  
- Jupyter Notebook  

## Approach

1. **Data Exploration & Cleaning**  
   - Identified missing values  
   - Handled data type inconsistencies  
   - Performed visual analysis for distribution and outliers

2. **Preprocessing**  
   - Label encoding for categorical variables  
   - Normalization for numeric features  
   - Train-test split (70-30)

3. **Modeling**  
   - Trained Logistic Regression, Decision Tree, and Random Forest  
   - Evaluated using accuracy, precision, recall, and F1-score

4. **Prediction**  
   - Final model selected based on best performance  
   - Used for identifying potential customers for targeted marketing

## Results

The Random Forest model yielded the best performance metrics and was selected as the final predictive model.

## Repository Contents
Customer-Spending-Prediction/
│
├── FDS_Project_LearnerNotebook_FullCode.html # Main code notebook
├── README.md # Project documentation
├── LICENSE # MIT License
└── .gitignore # File exclusions


## How to Use

1. Clone this repository  
2. Open the `.html` file or run the original notebook  
3. Install required Python libraries if needed  
4. Follow the notebook to view EDA, modeling, and predictions

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.


