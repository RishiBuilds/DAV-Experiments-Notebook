# DAV Experiments Notebook

## Experiment Index

| Sr. No | Name of Experiment |
|--------|-------------------|
| 1 | Data Preparation and Cleaning |
| 3 | Simple Linear Regression |
| 5 | Hypothesis Testing |
| 7 | ARIMA Model |

---

## Experiment 1: Data Preparation and Cleaning

### Experiment Title
To implement Data Preparation and Cleaning using Python Programming

### Software Tool Required
- Python 3.x
- Pandas
- NumPy
- Jupyter Notebook

### Related Theory / Description
Data preparation and cleaning is a crucial step in the data analysis pipeline. It involves handling missing values, removing duplicates, handling outliers, data transformation, and standardizing data formats. Clean data ensures accurate and reliable results in subsequent analysis and modeling.

**Key Steps:**
- Loading and exploring datasets
- Handling missing values (removal/imputation)
- Removing duplicate records
- Detecting and treating outliers
- Data type conversion
- Feature scaling and normalization

### Result
- Successfully loaded and explored dataset structure
- Identified and handled missing values using appropriate strategies
- Removed duplicate records to ensure data integrity
- Detected outliers using statistical methods (IQR/Z-score)
- Transformed data into clean, analysis-ready format

### Conclusion
Data preparation and cleaning is essential for reliable data analysis. Proper handling of missing values, duplicates, and outliers significantly improves data quality and the accuracy of subsequent machine learning models.

---

## Experiment 3: Simple Linear Regression

### Experiment Title
To implement Simple Linear Regression using Python Programming

### Software Tool Required
- Python 3.x
- Scikit-learn
- Pandas
- NumPy
- Matplotlib / Seaborn
- Jupyter Notebook

### Related Theory / Description
Simple Linear Regression is a statistical method that models the relationship between a dependent variable (Y) and an independent variable (X) using a linear equation: Y = β₀ + β₁X + ε, where β₀ is the intercept, β₁ is the slope, and ε is the error term. It is used to predict continuous outcomes based on a single predictor variable.

**Key Concepts:**
- Relationship between variables
- Least squares method for finding best-fit line
- Coefficient of determination (R²)
- Mean Squared Error (MSE)
- Model evaluation metrics

### Result
- Successfully implemented linear regression model
- Calculated regression coefficients (intercept and slope)
- Achieved R² score indicating model performance
- Visualized regression line with scatter plot
- Evaluated model using MSE and RMSE metrics

### Conclusion
Simple Linear Regression provides a straightforward approach to modeling linear relationships between variables. The model's performance metrics (R², MSE) help assess its predictive capability. This technique serves as a foundation for more complex regression models.

---

## Experiment 5: Hypothesis Testing

### Experiment Title
To implement Hypothesis Testing using Python Programming

### Software Tool Required
- Python 3.x
- SciPy (stats module)
- Pandas
- NumPy
- Jupyter Notebook

### Related Theory / Description
Hypothesis testing is a statistical method used to make decisions about population parameters based on sample data. It involves setting up null (H₀) and alternative (H₁) hypotheses, selecting significance level (α), calculating test statistics, and making decisions based on p-values.

**Common Tests:**
- One-sample t-test
- Two-sample t-test (independent/paired)
- Chi-square test
- Z-test
- ANOVA

**Key Concepts:**
- Null and alternative hypotheses
- Significance level (α = 0.05 typically)
- p-value interpretation
- Type I and Type II errors
- Confidence intervals

### Result
- Formulated appropriate null and alternative hypotheses
- Selected suitable statistical test based on data characteristics
- Calculated test statistic and corresponding p-value
- Compared p-value with significance level (α = 0.05)
- Made statistical decision (reject/fail to reject H₀)

### Conclusion
Hypothesis testing provides a systematic framework for making data-driven decisions. Understanding p-values and significance levels is crucial for correctly interpreting statistical results. Proper test selection based on data distribution and sample characteristics ensures valid conclusions.

---

## Experiment 7: ARIMA Model

### Experiment Title
To implement ARIMA Model using Python Programming

### Software Tool Required
- Python 3.x
- Statsmodels (ARIMA)
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

### Related Theory / Description
ARIMA (AutoRegressive Integrated Moving Average) is a popular time series forecasting model. It combines three components: AR (AutoRegressive) - uses past values, I (Integrated) - differencing for stationarity, and MA (Moving Average) - uses past forecast errors. The model is denoted as ARIMA(p,d,q) where p=AR order, d=differencing order, q=MA order.

**Key Steps:**
- Check stationarity using ADF test
- Determine differencing order (d) if needed
- Select AR (p) and MA (q) orders using ACF/PACF
- Build and fit ARIMA model
- Forecast future values
- Evaluate model performance

### Result
- Verified time series stationarity using Augmented Dickey-Fuller test
- Applied differencing to achieve stationarity (if required)
- Identified optimal ARIMA parameters (p, d, q)
- Built and trained ARIMA model on historical data
- Generated forecasts with confidence intervals
- Evaluated accuracy using MAE, RMSE, and MAPE metrics

### Conclusion
ARIMA models are effective for univariate time series forecasting when data exhibits patterns and stationarity can be achieved. Proper parameter selection through ACF/PACF analysis and stationarity testing is crucial for model accuracy. The model provides interpretable forecasts useful for trend analysis and future planning.

---

## Author
For Odd Roll Number Students

## Repository
https://github.com/RishiBuilds/DAV-Experiments-Notebook