# Traffic Volume Prediction

### Project Goal:Predict hourly traffic volume using weather and time data  

## Project Workflow

### 1. Descriptive Statistics
- Summary statistics of weather and traffic
- Understanding distribution and patterns

### 2. Data Preprocessing
- Missing value handling
- Outlier detection (e.g., extreme temps, zero-traffic)
- Inconsistency fixing (e.g., holidays and invalid timestamps)

### 3. Exploratory Data Analysis (EDA)
- Heatmaps, histograms, and line plots
- Identifying peak traffic hours and seasonal patterns
- Correlation matrix for variable relationships

### 4. Feature Engineering
- Extracted hour, weekday, month from datetime
- Categorized time of day (e.g., morning, evening)
- Created weather-related binary flags

##  Model Building
- Algorithms Tried: Linear Regression, Random Forest, XGBoost
- **Evaluation Metrics**: RMSE, MAE, R²
- **Best Performing Model**: Random Forest with engineered features

## Results & Insights
- Traffic volume is highest during peak work hours
- Weather like rain/snow has minor impact; holidays slightly lower volume
- Time-based features (hour, weekday) were most predictive

## Tools Used
- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- Jupyter Notebook
- CSV dataset from UCI
