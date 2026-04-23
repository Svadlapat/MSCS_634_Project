#  Customer Churn Analysis

##  Dataset
This project uses the Telco Customer Churn dataset, which contains around 7,000 customer records and 20+ features. The dataset includes customer demographics, services, billing information, and contract details. The target variable is Churn.

##  Project Steps
1. Data Cleaning & Preprocessing
   - Removed missing values and duplicates
   - Converted data types (TotalCharges to numeric)
   - Encoded categorical variables

2. Exploratory Data Analysis (EDA)
   - Visualized churn distribution
   - Analyzed tenure and monthly charges
   - Created correlation heatmap

3. Feature Engineering
   - Converted categorical data into numeric format
   - Standardized features

4. Regression Modeling
   - Applied Linear, Ridge, and Lasso Regression
   - Ridge Regression performed best

5. Classification
   - Used Decision Tree and KNN
   - Decision Tree achieved good accuracy

6. Clustering
   - Applied K-Means clustering
   - Identified 3 customer segments

7. Association Rule Mining
   - Explored Apriori algorithm
   - Not fully applied due to non-transactional dataset

##  Major Findings
- Customers with low tenure are more likely to churn
- High monthly charges increase churn probability
- Customer segmentation helps identify high-value customers
- Predictive models effectively estimate churn behavior

## 📌 Conclusion
This project demonstrates how data mining techniques can be used to analyze customer behavior and support better business decisions.
