# Demand-forecasting-on-SKU-s
Jupyter Notebook IDE on forecasting the SKU's demand.
SKU Demand Forecasting & Risk Analysis

Project Overview

The goal of this project is to forecast and analyze SKU demand by combining machine learning and statistical methods. The objective is to comprehend the major variables affecting demand and develop predictive models to enhance supply chain and inventory decisions.

Core Objective

1. Understand market dynamics and identify demand drivers.
a) Total sales by country
b) Top 20 SKUs by revenue
c) Compare ABC classes per region
d) Identify volatility (XYZ) by SKU
e) Correlate price, promotions, and volume
f) Visualise seasonality (monthly & weekly patterns)

2. Forecasting (Statistics + Machine Learning)
Forecast 10 SKUs with different demand profiles.


Dataset Description

This dataset contains more than 1,100,000 rows of highly realistic FMCG sales data
generated for professional demand planning, forecasting, and supply chain analytics.
It simulates a multi-country FMCG environment, with:
a) 350+ SKUs (An SKU is lets say, 3kg of salt is sold at 300 shillings - now that
“30kg” is called an SKU)
b) 3 full years of daily sales
c) 15 countries, 60+ cities (with real lat/lon coordinates)
d) Multiple sales channels (Modern Trade, Traditional Trade, Wholesale,
E-commerce)
e) Promotional effects & price elasticity
f) Seasonality patterns (weekly, monthly, yearly)
g) ABC/XYZ segmentation
h) Lead time variability
i) Stockouts & safety stock parameters

Tools & Technologies
> Used Python Libraries such as:

- Pandas & NumPy for Data manipulation and arithmetic operation.
- Matplotlib & Seaborn for barplots, lineplots, and histogram visuals and advanced visuals like heatmap.
- Scikit-learn for a supervised-model algorithm on training set and prediction on test data in Machine Learning algorithms. 
- Statsmodels for carrying out OLS and regression analysis on significance test of estimators.

Research Methodology

STEP 1. Data Preprocessing
- Data import into Python IDE (Jupyter Notebook)
- Performing Automated EDA on each block of column using Pandas_profiling report, to give a Quantile statistics; median, minimum, maximum, range, and IQR, and Descriptive statistics; Standard deviation, variance, coefficient of variance, mean, skewness and kurtosis.
- Feature engineering i.e  label encoding categorical variable into numeric data types.)
- Scaling and transformation 

STEP 2. Exploratory Data Analysis (EDA)
- Trend and seasonality analysis
- Correlation analysis and heatmap visual.
- Visualization of demand patterns monthly and weekly.

STEP 3. Model Building
- Ordinary Least Squares (OLS)
- Linear regression ML model


STEP 4. Model Evaluation
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R-squared (R²)
- P-value
- T-Statistic value.

Key Insights
--> Demand shows patterns influenced by time and external factors
--> weekofyear, weekday, is_holiday, temperature, rain_mm, stock_on_hand, lead_tim_days, supplier_id, purchase_cost, margin_pct; tend to have a less significant effect on the unit sold.
--> promo_flag, discount_pct, list_price, and units_sold variables have strong correlation with units sold
--> Multinational FMCG company faces a high demand volatility using the XYZ Segmentation in the SKU'S. 


Clone the repository:
   ```bash
   git clone https://github.com/feloh-1a2b3c4d/Demand-forecasting-on-SKU-s.git.git
