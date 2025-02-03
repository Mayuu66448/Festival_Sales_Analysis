# Festival_Sales_Analysis

## Overview
This project analyzes Festival sales data to identify key insights about customers, purchasing trends, and sales distribution. The dataset is cleaned and explored using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn. Various visualizations are used to understand buyer demographics, purchase behavior, and product category preferences.

## Dataset
The dataset contains information about orders, customer demographics (gender, age, marital status, occupation, state), and sales amount.

## Data Cleaning and Preprocessing
- Loaded the dataset and checked for missing values.
- Dropped unnecessary columns (`Status`, `unnamed1`).
- Removed null values.
- Converted `Amount` column to integer data type for accurate analysis.

## Exploratory Data Analysis (EDA)
### 1. Gender-wise Analysis
- More female buyers than male buyers.
- Female customers contributed the highest sales revenue.

### 2. Age Group Analysis
- Most buyers belong to the 26-35 years age group.
- This age group also generated the highest revenue.

### 3. State-wise Sales
- Top states by orders: Uttar Pradesh, Maharashtra, Kerala.
- Top states by total revenue: Uttar Pradesh, Maharashtra, Karnataka.

### 4. Marital Status & Purchasing Power
- Married individuals, especially women, are the highest spenders.

### 5. Occupation Analysis
- Highest number of buyers are from IT, Healthcare, and Aviation sectors.
- These professions also contributed the most to sales revenue.

### 6. Product Category Analysis
- Top-selling categories: Food, Clothing, Electronics.
- These categories generated the most revenue.

## Key Insights & Conclusion
- Married women aged 26-35 years from Uttar Pradesh, Maharashtra, and Karnataka working in IT, Healthcare, and Aviation industries are the most frequent buyers.
- Food, Clothing, and Electronics are the most popular product categories.

## Technologies Used
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Jupyter Notebook** for analysis and visualization

## Repository Structure
- `Festival Sales Analysis.ipynb` - Jupyter Notebook with full analysis
- `Festival_sales_data.csv` - Dataset used for analysis
- `README.md` - Summary of analysis and insights

## Future Improvements
- Perform predictive analysis using machine learning.
- Develop a dashboard for interactive data visualization.
- Analyze customer behavior based on purchase frequency and spending habits.

