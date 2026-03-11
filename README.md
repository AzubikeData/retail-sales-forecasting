
# Retail Sales Forecasting

---

## Project Overview
This project develops a machine learning model to forecast retail sales using historical transaction data, promotions, oil prices, and store information. The objective is to understand the factors influencing sales and build a predictive model capable of estimating future demand.

---

## Dataset
The project uses multiple datasets that capture different aspects of retail operations:

- **train.csv** – Historical daily sales data  
- **test.csv** – Dataset used for generating predictions  
- **stores.csv** – Store information such as location and type  
- **transactions.csv** – Daily transaction counts per store  
- **oil.csv** – Daily oil price data  
- **holidays.csv** – Holiday and event information  

---

## Data Preparation
Several preprocessing steps were performed to prepare the data for analysis and modeling:

- Data validation and quality checks  
- Handling missing values  
- Merging multiple datasets into a unified analytical table  
- Feature engineering from date variables *(year, month, day of week)*  
- Log transformation of the sales variable to reduce skewness  

---

## Exploratory Data Analysis
Exploratory data analysis was conducted to understand the distribution and relationships between key variables.

Visualizations created include:

- Sales distribution  
- Transactions distribution  
- Oil price trend over time  
- Promotion distribution  
- Feature correlation heatmap  

---

## Model Development
A **Linear Regression model** was trained to predict sales using engineered features such as:

- Promotions  
- Transaction counts  
- Oil prices  
- Temporal features derived from the date  

---

## Model Evaluation

Model performance was evaluated using **Root Mean Squared Error (RMSE)**.

- **RMSE (Log Scale):** ~1.27  
- **RMSE (Original Sales Scale):** ~94,888  

An **Actual vs Predicted Sales** visualization was also created to compare the model’s predictions with real sales values.

---

## Key Insights

- Promotions have a strong positive influence on retail sales.
- Higher transaction volumes are associated with higher sales.
- Some product families contribute significantly more to total sales.
- Sales data is highly skewed, which required log transformation before modeling.

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Author
**Azubike Miracle Nwaejike**
