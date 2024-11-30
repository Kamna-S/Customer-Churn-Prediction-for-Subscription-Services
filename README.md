# Customer Churn Prediction for Subscription Services

## Project Overview
This project aims to predict customer churn for subscription-based services. By analyzing historical customer data, we identify patterns and factors that contribute to customer cancellation. The model provides actionable insights to help businesses retain customers and reduce churn.

## Dataset
The dataset used in this project is the Telco Customer Churn dataset, which contains information about customers' demographics, subscription details, and service usage.

### Key Columns:
- **tenure**: Number of months the customer has been with the service
- **MonthlyCharges**: Monthly subscription charges
- **Churn**: Whether the customer has churned (1) or not (0)

## Approach
1. **Data Cleaning**: Handle missing values and drop irrelevant features.
2. **Feature Engineering**: Create new features, such as `AvgChargesPerMonth`, to improve model performance.
3. **Data Preprocessing**: Encode categorical variables and scale numerical features.
4. **Modeling**: Use a **Gradient Boosting Classifier** to predict churn based on customer data.
5. **Evaluation**: Evaluate the model using **Accuracy**, **ROC AUC Score**, and **Classification Report**.

## Results
- **Accuracy**: The model achieved an accuracy score of **0.79**.
- **ROC AUC Score**: The ROC AUC score was **0.85**.
- **Top Features**: Key features contributing to churn prediction were identified, with the top 10 features visualized.

## ROC Curve
The ROC (Receiver Operating Characteristic) curve illustrates the performance of the model in distinguishing between churned and non-churned customers.

![ROC Curve](roc_curve.png)

## Tools & Libraries Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Installation
1. Clone the repository:
2. Install required libraries:

## Conclusion
By understanding customer churn, businesses can take proactive steps to improve customer retention, ultimately increasing profitability and customer satisfaction.
