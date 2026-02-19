*Call Center Handle Time Predictor*

**Project Overview**

This project uses Machine Learning to predict the Total Handle Time (THT) for call center operations. By analyzing over 135,000 call records, the model identifies patterns in call durations to help management optimize staffing and improve operational efficiency.

**Key Features**

Time-Series Resampling: Aggregated raw call data into 10-minute windows to create a structured timeline for analysis.

Feature Engineering: Implemented "Lags" to provide the models with historical context (memory) of previous call performance.

Multi-Model Comparison: Evaluated and compared three different regression techniques:

Linear Regression (Baseline)

Random Forest Regressor (Non-linear patterns)

Support Vector Regression (SVR) (Complex relationships)

**Tech Stack**

Language: Python

Libraries: Pandas, NumPy, Scikit-Learn, Matplotlib

Concepts: Time-Series Analysis, Feature Engineering, Regression Modeling
