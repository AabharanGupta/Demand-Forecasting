# Retail Demand Forecasting
## Objective:
Build a machine learning model to forecast product demand using historical inventory, sales, and promotional data from retail stores.

## Exploratory Data Analysis (EDA)
Key analysis included:

1. Outlier detection & removal for Inventory Level, Units Sold, and Demand

2. Boxplots by store and category

3. Time-based trends: Monthly/yearly demand patterns

4. Impact of discounts on demand

5. Epidemic effect on different product categories

6. Demand distribution under different seasons and weather conditions

7. Competitor Pricing vs. Our Pricing vs. Demand

Visualizations were done using matplotlib, seaborn, and pandas.

## Feature Engineering
Created several new features to enhance model performance:

1. Date features: Year, month, week, day, day of week, is weekend

2. Pricing features: Price difference, price ratio, discount effect

3. Inventory metrics: Sell-through rate, order-to-sales ratio

4. Interaction terms: e.g., Price * Seasonality

5. Categorical encoding: LabelEncoded variables like Store ID, Category, Weather, etc.

## Modeling
Used RandomForestRegressor as the baseline model:

Train-Test Split: 80/20

### Evaluation Metrics:

RMSE: 28.14

R² Score: 0.85