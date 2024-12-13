# Credit Card Analysis Report 
## Project Overview 
This project includes a dynamic and interactive **Credit Card Transaction and Customer** dashboard designed to analyze weekly credit card operations data, providing stakeholders with real-time actionable insights into key performance metrics and trends to enhance decision-making and optimize performance.

## Tools Used 
- CSV : Initial source format for dataset
- MySQL : For data integration and transformation
- Power BI : For data visualization and designing dynamic dashboard 
- Power Query : For data processing and transformation
- DAX : For creating Calculated Columns and Measures

## Data Source 
The dataset comprises CSV files containing credit card transaction and customer data:
- credit_card.csv: Weekly credit card transaction data.
- customer.csv: Customer details and demographic information.
- cc_add.csv and cust_add.csv: Updated data files for the subsequent week (Week 53).

## Key Metrics 
- **Total Revenue**: $57M
- **Total Interest**: $8M
- **Total Transactions**: $46M
- **Transaction Count**: 667K
- **Top States by Revenue**: TX, NY, CA, FL, NJ

## Workflow 
1. **Data Source**: The dataset was initially provided as a CSV file containing credit card operatiins and customer data.
2. **Data Integration**: Imported the data from CSV file into MySQL to create structured relational database.
3. **Data Extraction**: Imported the dataset from MySQL to Power BI for designing interactive dashboard.
4. **Advanced DAX Queries**: Created Calculated columns and Measures
5. **Data Visualization**: Designed a dynamic dashboard to analyze key metrics and trends

## Dashboard Preview

![Screenshot 2024-11-23 210001](https://github.com/user-attachments/assets/378fe5af-3e43-4629-9b11-eacfeb75d5e7)

![Screenshot 2024-11-23 210032](https://github.com/user-attachments/assets/7b3a61e2-0665-4f03-a24d-4749964fccdb)

## Live Dashboard Link - [Credit Card Analysis](https://app.powerbi.com/view?r=eyJrIjoiZTJkZmY4OTUtNThjZi00YjgzLTk1NWMtMTA0ODI0YWNhYjNhIiwidCI6Ijk0YjBjYWUyLTcyMzgtNDQ4OC05NTRmLWZjOTAyNWFmYzYxYSJ9&pageName=11b8942e1670cae190e4)

## Insights 
  - Revenue increased by **28.8 %** (week 53) compared to last week.
  - **Blue card** contributing **90%** to overall revenue.
  - Customers aged 40-50 and with high salaries are the most valuable.
  - **Swipe** transactions contribute the most revenue **($36M)**, followed by **chip-based** transactions.  
  - **TX, NY, and CA** are the leading states in revenue generation.
  - Overall **Delinquent Rate** is **6.06%**.
  - Overall **Activation Rate** is **57.5%**.

## Skills Learned 
- Data Integration from various sources such as CSV file/Excel, MySQL database etc.
- Data Visualization and dashboard designing
- Calculated columns and Measures using DAX queries
- Data Analysis 
- Data Interpretation
- Identifying KPI's to support data driven decision making


  

