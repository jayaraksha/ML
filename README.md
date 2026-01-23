# Exploratory Data Analysis (EDA) Scenarios

---

## Scenario 1: E-commerce Sales Behavior Analysis

### Overview
This project applies **Exploratory Data Analysis (EDA)** to a retail dataset to decode product performance, identify emerging trends, and assess data integrity.

### Objectives
- Load the dataset to evaluate its structural health  
- Calculate summary statistics  
- Pinpoint null values  
- Generate bar and line charts to visualize sales trajectories  

### Tech Stack
- Python  
- Pandas  
- Matplotlib  

### Data Source
- Kaggle: https://www.kaggle.com/datasets/carrie1/ecommerce-data

### Core Insights
- Sales distribution is highly skewed  
- A minority of **"hero" products** drive the bulk of revenue  
- Significant data gaps were identified, requiring cleaning before reliable sales forecasting  

---

## Scenario 2: Patient Health & Diabetes Metrics

### Overview
A focused EDA of medical records aimed at identifying missing clinical metrics and understanding the distribution of biological markers associated with diabetes.

### Objectives
- Utilize Pandas for initial data inspection  
- Detect invalid or `"zero"` health metrics  
- Employ histograms and box plots to analyze age and glucose distributions  

### Tech Stack
- Python  
- Pandas  
- Matplotlib  

### Data Source
- Kaggle: https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database

### Core Insights
- Critical data quality issues were uncovered  
- Clear patterns emerged linking **age** and **glucose fluctuations**  
- Provides a strong foundation for future healthcare predictive modeling  

---

## Scenario 3: Housing Market Trends & Price Drivers

### Overview
This analysis explores a real estate dataset to uncover how various property attributes influence market pricing and to identify gaps in the data features.

### Objectives
- Audit the dataset for missing values  
- Visualize correlations between numerical features using scatter plots  
- Utilize heatmaps to identify the strongest price predictors  

### Tech Stack
- Python  
- Pandas  
- Seaborn / Matplotlib  

### Data Source
- Kaggle: https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction

### Core Insights
- **Total area** is the primary driver of housing cost  
- Bedrooms and bathrooms show positive correlation but are secondary to square footage  
- Preprocessing is essential due to incomplete feature sets  

---

## Scenario 4: Customer Personality & Segmentation

### Overview
An investigation into demographic and spending data to better understand consumer behavior and refine marketing segmentation strategies.

### Objectives
- Identify column data types and missing entries  
- Visualize age demographics using bar plots  
- Compare income levels against spending habits using box plots  

### Tech Stack
- Python  
- Pandas  
- Matplotlib  

### Data Source
- Kaggle:https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis

### Core Insights
- Income data requires significant cleaning due to missing values  
- Majority of customers are **middle-aged**  
- High-spending outliers indicate a niche **"luxury" segment** suitable for targeted marketing  

---
