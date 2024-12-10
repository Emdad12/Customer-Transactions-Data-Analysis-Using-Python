# Customer-Transactions-Data-Analysis-Using-Python
### Project Overview
This project focuses on analyzing transaction data to understand customer behavior, purchasing patterns, and sales trends. Using Python, I explored the dataset to uncover actionable insights through statistical analysis and data visualization. The dataset provides rich information about transactions, including customer details, payment methods, seasonal trends, and promotional effectiveness, making it ideal for customer segmentation, sales analysis, and market basket analysis.
### Dataset Information
The dataset contains the following columns, each offering valuable insights into transactions and purchasing behavior:

- Transaction_ID: A unique identifier for each transaction.
- Date: The timestamp of the transaction.
- Customer_Name: The name of the customer who made the purchase.
- Total_Items: The total number of items purchased.
- Amount($): The total cost of the purchase in USD.
- Payment_Method: Payment type, such as cash, credit card, or mobile payment.
- City: The location of the purchase.
- Store_Type: The type of store where the transaction occurred.
- Discount_Applied: Whether a discount was applied (True/False).
- Customer_Category: The demographic category or age group of the customer.
- Season: The season during which the purchase was made.
- Promotion: The promotion type applied, if any (e.g., "BOGO," "Discount on Selected Items").
### Objectives
- Understand purchasing trends across different cities and store types.
- Evaluate the impact of promotions and discounts on sales.
- Analyze seasonal variations in transaction amounts and item counts.
- Segment customers based on purchasing behavior for targeted strategies.
### Tools and Technologies
- Python: For data analysis and visualization.
- Pandas: For data manipulation and cleaning.
- Matplotlib & Seaborn: For creating insightful visualizations.
- Jupyter Notebook: For interactive data exploration.
### Process
1. Data Cleaning

- Addressed missing values in columns like Customer_Name and Amount($).
- Converted Date column into datetime format and extracted features like year, month, and day.
- Standardized categorical data in columns like Store_Type and Promotion.
3. Exploratory Data Analysis (EDA)
  
- Analyzed transaction volume by city, store type, and season.
- Explored correlations between discounts, promotions, and total sales.
- Examined customer categories to identify high-value groups.
4. Visualizations
  
B- ar charts for transaction counts by store type and city.
- Line plots for sales trends over time.
- Pie charts to show the distribution of payment methods.
- Heatmaps to visualize correlations between numerical features.
5. Key Metrics
  
- Average Sales per Transaction
- Discount Effectiveness Rate
- Seasonal Sales Variations
- Customer Lifetime Value
### How to Use
1. Navigate to the project directory:  
bash
Copy code
cd transaction-analysis-python  
2.Install the required libraries using the requirements(libraries are matplotlib,numpy,pandas,seaborn,statistics.txt file:

bash
Copy code
pip install -r requirements.txt  
3.Open the Jupyter Notebook file (Transaction_Analysis.ipynb) to explore the analysis.
### Deliverables
- Jupyter Notebook: Includes the full data cleaning, analysis, and visualization workflow.
- Dataset: A cleaned version of the dataset (if publicly shareable).
### Next Steps
- Implement customer segmentation using clustering techniques (e.g., K-Means).
- Build a predictive model to forecast sales based on historical data.
- Automate the analysis workflow for real-time insights.
