### README.md  

# **Bank Customer Churn Analysis**  

## **Project Description**  
This project focuses on analyzing customer churn for a bank to identify factors contributing to customer attrition. The insights gained will help develop effective retention strategies and loyalty programs to minimize customer churn and enhance business performance.  


## **Data Dictionary**  
The dataset contains the following fields:  

- **RowNumber**: Record (row) number, not affecting output.  
- **CustomerId**: Random values, no impact on churn.  
- **Surname**: Customer surname, no impact on churn.  
- **CreditScore**: Affects churn; higher scores reduce likelihood of exit.  
  - Excellent: 800–850  
  - Very Good: 740–799  
  - Good: 670–739  
  - Fair: 580–669  
  - Poor: 300–579  
- **Geography**: Customer location, influences churn likelihood.  
- **Gender**: May impact churn; worth exploring.  
- **Age**: Older customers are less likely to churn.  
- **Tenure**: Years as a bank client; longer tenure indicates loyalty.  
- **Balance**: Higher account balances reduce churn likelihood.  
- **NumOfProducts**: Number of products purchased from the bank.  
- **HasCrCard**: Whether the customer has a credit card.  
  - 1: Credit card holder  
  - 0: Non-credit card holder  
- **IsActiveMember**: Active customers are less likely to churn.  
  - 1: Active Member  
  - 0: Inactive Member  
- **Estimated Salary**: Higher salaries reduce churn likelihood.  
- **Exited**: Indicates whether the customer has left the bank.  
  - 0: Retained  
  - 1: Exited  
- **Bank DOJ**: The date when the customer joined the bank.  

---

## **Data Sources**  
The following data assets were used to gather information about bank customers:  
- **ActiveCustomer**  
- **Bank_Churn**  
- **CreditCard**  
- **CustomerInfo**  
- **ExitCustomer**  
- **Gender**  
- **Geography**  


## **Key Objectives**  
1. Perform an exploratory data analysis (EDA) to identify trends and patterns.  
2. Build a customer churn analysis to understand key factors influencing churn.  
3. Generate actionable insights to help the bank design retention strategies.  


## **Project Workflow**  
1. **Data Collection**: Extracted data from provided data assets.  
2. **Data Preprocessing**: Cleaned, merged, and prepared the dataset for analysis.  
3. **EDA (Exploratory Data Analysis)**: Visualized patterns and trends in the data.  
4. **Feature Engineering**: Identified key features influencing churn.  
5. **Churn Analysis**: Applied statistical and machine learning techniques to analyze churn drivers.  
6. **Insights & Recommendations**: Highlighted actionable points for customer retention.  


## **Technology & Tools**  
- Python  
  - Pandas, NumPy: Data manipulation and analysis  
  - Matplotlib, Seaborn: Data visualization  
  - Scikit-learn: Machine learning  
- SQL: Data extraction and transformation  
- Jupyter Notebook: Development environment  


## **Key Insights**  
- **Credit Score**: Customers with lower credit scores are more likely to churn.  
- **Geography**: Location plays a role in churn patterns.  
- **Balance**: Customers with higher account balances are less likely to churn.  
- **Active Members**: Active customers are significantly less likely to exit.  
- **Tenure & Age**: Longer-tenured and older customers show higher loyalty.  


## **How to Run the Project**  
1. Clone the repository to your local machine:  
   ```bash  
   git clone <repository_link>  
   ```  
2. Install the required dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  
3. Run the Jupyter Notebook:  
   ```bash  
   jupyter notebook  
   ```  
4. Explore the provided notebooks to analyze customer churn and view insights.  


![image](https://github.com/user-attachments/assets/c62ba912-5dc1-4dca-b4af-45f3cee8853a)
![Uploading image.png…]()


---

## **Contributors**  
- **Aeni Parmar**  
  Data Analyst | [GitHub](https://github.com/AeniParmar)  

---

Let me know if you'd like additional customization!
