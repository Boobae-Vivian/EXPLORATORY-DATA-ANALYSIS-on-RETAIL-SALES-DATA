# EXPLORATORY-DATA-ANALYSIS-on-RETAIL-SALES-DATA
## INTRODUCTION
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In today's competitive retail industry, data-driven insights play a vital role in business growth and decision-making. This project focuses on analyzing a dataset containing 1,000 rows and 9 columns of retail sales data using Python. The primary objective is to perform Exploratory Data Analysis (EDA) to uncover patterns, trends, and key insights that can help the retail business optimize sales, improve inventory management, and enhance overall performance.  
By leveraging Python libraries such as Pandas, Matplotlib, and Seaborn, this analysis will involve data cleaning, visualization, and statistical exploration to identify key sales drivers and customer behavior trends. The findings from this study will provide actionable recommendations to support data-driven decision-making and business strategy improvements.
## PROBLEM STATEMENT
1. Descriptive Statistics: Calculate key statistics (mean, median, mode, and standard deviation) for:
   - Quantity
   - Price per Unit
   - Total Amount
2. Sales Trend Analysis:
   - Calculate total monthly sales performance over time
   - Analyze the average monthly sales trend
3. Customer Demographics & Purchasing Behavior:
   - Analyze gender distribution of customers
   - Identify total revenue and average spending per customer
   - Calculate average spending per gender to assess purchasing patterns
4. Visualization:
   - Group sales by product category
   - Identify and visualize the top three best-selling product categories
   - Compute and visualize the correlation matrix between Quantity, Price per Unit, and Total Amount to identify relationships between these variables.
## SKILLS AND CONCEPTS DEMONSTRATED 
1. Data Manipulation & Cleaning
2. Descriptive Statistics & Exploratory Data Analysis (EDA)
3. Time Series Analysis
4. Data Visualization
5. Customer & Product Analysis
6. Correlation & Insights Extraction
 
By completing this project, I demonstrated proficiency in data analysis, visualization, and business insights generation, which are valuable skills for a Data Analyst role.

## STAGES TO NAVIGATE IN THE EXPLORATORY DATA ANALYSIS PROJECT on RETAIL SALES DATA

The project comprises four critical stages essential for successful completion, which encompass:
1. Libraries and Data Importation
2. Data Assessment to Detect Data Quality Issues
3. Data Cleaning
4. Data Manipulation and Data Visualization

#### EXPLANATIONS

1. "Libraries and Data Importation":
   ---  
The first step of this project is to import the essential libraries required for data analysis and visualization. In this case, the following libraries are used:
- Pandas (pd) for data importation and manipulation.
- Numpy as (np) for numerical operations
- Datetime (dt) to handle date-related operations.
- Matplotlib.pyplot (plt) and Seaborn (sns) for data visualization.
- Warnings to suppress unnecessary warnings during execution.
  
Once these libraries are imported, the next step is to load the sales dataset into the Jupyter Notebook environment as a DataFrame using the pd.read_csv() function. The dataset is assigned to a variable named df, allowing easy reference throughout the analysis.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The following code snippet imports the necessary Python libraries for data analysis and visualization:

```python
import pandas as pd   
import numpy as np  
import datetime as dt  
import matplotlib.pyplot as plt     
import seaborn as sns   
import warnings   
warnings.filterwarnings('ignore')  

df = pd.read_csv(r'C:\Users\HP\Downloads\retail_sales_dataset.csv')  
df
```
LIBRARIES AND DATA IMPORTATION
:-----------------------------:
![](library.png)


