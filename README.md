# EDA_of_Data 📊
Overview
This project focuses on Exploratory Data Analysis (EDA) of the Churn Modelling Dataset to uncover insights and patterns about customer behavior. The dataset includes customer demographics, credit scores, geography, and other key attributes, which help to identify factors influencing customer churn.

The analysis provides a foundation for predictive modeling and better understanding of customer retention strategies.

Features of the Project
Data Cleaning: Handled missing, incorrect, or inconsistent data to ensure high-quality analysis.
Feature Exploration: Studied relationships between variables to gain insights into the dataset.
Visualization: Used visual tools to represent data insights for better understanding.
Churn Patterns: Identified key factors contributing to customer churn.
Correlation Analysis: Examined interrelationships among variables to prioritize important factors.
Tools and Technologies Used
Programming Language: Python 🐍
Libraries:
Pandas
NumPy
Matplotlib
Seaborn
Plotly
Environment: Jupyter Notebook
Dataset Details
The Churn Modelling Dataset includes the following columns:

RowNumber: Unique identifier for rows.
CustomerId: Unique identifier for customers.
Surname: Customer surname.
CreditScore: Customer's credit score.
Geography: Country (e.g., France, Spain, Germany).
Gender: Customer gender.
Age: Customer age.
Tenure: Number of years with the bank.
Balance: Customer account balance.
NumOfProducts: Number of products held by the customer.
HasCrCard: Does the customer have a credit card (binary).
IsActiveMember: Is the customer an active member (binary).
EstimatedSalary: Estimated salary of the customer.
Exited: Target variable (1 for churned, 0 for retained).
Analysis Highlights
Demographics Analysis: Distribution of customers by geography, age, and gender.
Churn Rate Analysis: Examined how churn rates vary across different groups.
Credit Score Impact: Visualized the impact of credit scores on churn.
Active Membership Trends: Correlation between activity levels and retention.
Salary vs. Churn: Relationship between salary range and customer churn.
Visualizations
Some key visualizations include:

Churn by Geography and Gender.
Credit Score Distribution among Churned and Retained Customers.
Correlation Heatmap of Features.
Distribution of Account Balance and Salary.
Project Goals
Gain insights into factors that influence customer churn.
Highlight actionable business strategies to improve retention.
Create a foundation for predictive modeling.
How to Use
Clone this repository:
bash
Copy code
git clone https://github.com/idarshanpatil/EDA-Of-Churn-Modelling-Dataset.git
Navigate to the project folder and open the Jupyter Notebook.
Run the cells to explore and visualize the dataset.
Adjust and modify code to experiment with additional insights.
Project Structure
plaintext
Copy code
EDA-Of-Churn-Modelling-Dataset/
├── dataset/
│   └── churn_modelling.csv
├── eda_churn_modelling.ipynb
├── requirements.txt
└── README.md
Author
👨‍💻 Darshan Patil

LinkedIn: Darshan Patil
GitHub: idarshanpatil
Portfolio: darshanpatil
Email: patildarshan272@gmail.com
Acknowledgments
Dataset sourced from Kaggle/Churn Modelling.
Special thanks to open-source contributors and Python community for powerful libraries.
