# Data Science Portfolio: EDA, Predictive Modeling & Machine Learning
 
A collection of four hands-on data science projects demonstrating exploratory data analysis, classification, regression, clustering, and time series forecasting using Python, scikit-learn, and Prophet.
 
**Author:** Hitik Sharma | M.Sc. Computer Science, University of Passau  
**GitHub:** [github.com/hitiksharma](https://github.com/hitiksharma)  
**LinkedIn:** [linkedin.com/in/hitik-sharma-29966a18b](https://www.linkedin.com/in/hitik-sharma-29966a18b/)
 
---
 
## Projects
 
### 1. Customer Churn Analysis (EDA + Classification)
**Dataset:** Telco Customer Churn (7,043 records, 21 features)  
**Objective:** Identify factors driving customer churn and predict churn using ML models.
 
**What was done:**
- Complete EDA pipeline: missing value treatment, data type correction, feature engineering (tenure grouping, dummy encoding)
- Univariate and bivariate analysis revealing key churn drivers
- StandardScaler preprocessing and train/test split
- Trained and compared 4 classification models
**Results:**
 
| Model | Accuracy |
|-------|----------|
| KNN | 75.26% |
| Decision Tree | 72.94% |
| Random Forest | 79.81% |
| **AdaBoost** | **82.46%** |
 
**Key Insights:**
- Monthly contract customers churn significantly more than yearly/two-year contracts
- Electronic check payment method correlates with higher churn
- Customers in the 1-12 month tenure range are most likely to churn
- High monthly charges + low total charges = strongest churn indicator
- Data imbalance: 73:27 ratio (non-churn vs churn)
**Tech:** Python, pandas, NumPy, matplotlib, seaborn, scikit-learn (KNN, DecisionTree, RandomForest, AdaBoost)
 
---
 
### 2. Time Series Forecasting
**Dataset:** AirPassengers (classic airline passenger data)  
**Objective:** Forecast future passenger numbers using time series decomposition and Prophet.
 
**What was done:**
- Time series visualization and trend analysis
- Facebook Prophet model with changepoint detection
- Future period forecasting with confidence intervals
**Tech:** Python, pandas, Prophet
 
---
 
### 3. Customer Segmentation (K-Means Clustering)
**Dataset:** Mall Customers (spending score + annual income)  
**Objective:** Segment customers into distinct groups based on spending behavior.
 
**What was done:**
- Elbow method (WCSS) to determine optimal number of clusters
- K-Means clustering implementation
- Cluster visualization and interpretation
**Tech:** Python, pandas, NumPy, matplotlib, seaborn, scikit-learn (KMeans)
 
---
 
### 4. Multiple Linear Regression — Startup Profit Prediction
**Dataset:** 50 Startups (R&D Spend, Administration, Marketing, State, Profit)  
**Objective:** Predict startup profit based on spending across categories.
 
**What was done:**
- Feature analysis: R&D Spend vs Profit relationship
- One-Hot Encoding for categorical variable (State)
- Multiple Linear Regression model: y = m1x1 + m2x2 + ... + m6x6
- Out-of-sample prediction (~150K profit prediction)
**Tech:** Python, pandas, NumPy, matplotlib, scikit-learn (LinearRegression)
 
---
 
## Technical Skills Demonstrated
 
- **EDA:** Data cleaning, missing value treatment, outlier detection, distribution analysis, correlation analysis
- **Feature Engineering:** Dummy encoding, one-hot encoding, binning, standardization
- **Visualization:** Distribution plots, heatmaps, bar charts, scatter plots, time series plots
- **Classification:** KNN, Decision Tree, Random Forest, AdaBoost
- **Regression:** Multiple Linear Regression
- **Clustering:** K-Means with Elbow Method
- **Time Series:** Facebook Prophet with changepoint detection
- **Libraries:** pandas, NumPy, scikit-learn, matplotlib, seaborn, Prophet
---
 
## How to Run
 
```bash
# Clone the repository
git clone https://github.com/hitiksharma/Data-Science-Portfolio.git
cd Data-Science-Portfolio
 
# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn prophet kagglehub
 
# Open notebooks
jupyter notebook
```
 
## License
This project is for educational and portfolio purposes.
