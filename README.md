# Credit Card Approval Prediction

## Project Overview
This project develops a machine learning model to predict credit card approvals. It includes data preprocessing, model development, and SQL analysis to extract business insights.

## Dataset
The dataset contains 1,548 credit card applications with various features including:
- Demographic information (gender, age, marital status)
- Financial information (income, employment)
- Property ownership details

## Methodology
1. Data Preprocessing
   - Handled missing values
   - Encoded categorical variables
   - Addressed class imbalance using SMOTE

2. Feature Engineering
   - Created new features
   - Scaled numerical features

3. Model Development
   - Implemented 5 machine learning models:
     - Support Vector Machine (SVM)
     - Random Forest
     - K-Nearest Neighbors (KNN)
     - XGBoost
     - Logistic Regression
   - Used GridSearchCV for hyperparameter tuning

4. SQL Analysis
   - Performed various queries to extract business insights

## Results
- SVM achieved the highest accuracy of 87%
- Identified key factors influencing credit card approvals
- Extracted demographic trends in credit risk

## Technologies Used
- Python
- Scikit-learn
- Pandas
- Matplotlib
- Seaborn
- DuckDB for SQL analysis

## How to Run
1. Clone this repository
2. Install required packages: `pip install -r requirements.txt`
3. Run the Jupyter notebook: `jupyter notebook credit_card_approval.ipynb`

## Future Work
- Explore more advanced feature engineering techniques
- Implement deep learning models
- Develop a web application for real-time predictions

## Author
Ashish Patel

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
