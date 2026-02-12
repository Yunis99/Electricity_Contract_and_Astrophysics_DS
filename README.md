# Python Capstone: Energy Data Cleaning, Forecasting, and Optimization

## Disclaimer

The datasets used in this project have minor modifications for educational purposes.  
The project demonstrates data cleaning, preprocessing, regression modeling, and optimization skills using Python.

---

## Project Overview

This capstone project includes two separate tasks:

1. **Data Cleaning and Electricity Contract Analysis**
   - Analyze smart electricity meter data
   - Clean poorly structured and unsorted datasets
   - Compute hourly and daily usage statistics
   - Compare annual costs across three electricity contracts:
     - No Flex: constant kWh price
     - Monthly Flex: monthly fluctuating kWh price
     - Hourly Flex: hourly fluctuating kWh price
   - Answer business questions based on cleaned data
   - Demonstrates data cleaning, aggregation, and analysis techniques

2. **McKinsey & Company Prohack – DSML Optimization**
   - Predict a composite well-being index for intergalactic populations
   - Perform regression modeling to forecast index values
   - Conduct feature engineering, selection, and preprocessing
   - Apply optimization constraints for energy allocation
   - Allocate a fixed energy resource across galaxies to maximize overall well-being
   - Demonstrates end-to-end data science workflow:
     - Data Cleaning
     - Preprocessing
     - Exploratory Data Analysis (EDA)
     - Feature Engineering
     - Modeling
     - Performance Evaluation
     - Optimization

---

## Data Description

### Electricity Usage Dataset
- Hourly energy consumption (kWh)
- Contract-specific kWh rates
- Historical usage over one year

### DSML Optimization Dataset
- Galaxy-level well-being metrics
- Energy consumption data (DSML units)
- Population and health characteristics
- Constraints for energy allocation optimization

---

## Key Analyses and Implementation

### Task 1: Data Cleaning & Electricity Contract Analysis
- Aggregated hourly usage to daily and monthly levels
- Calculated average electricity usage per hour and per month
- Identified peak usage periods by day and continuous hour blocks
- Computed projected annual costs under different contracts
- Selected optimal contract to minimize costs

### Task 2: Regression & Optimization
- Cleaned and preprocessed intergalactic dataset
- Performed EDA to understand features and correlations
- Built regression models to predict the composite well-being index
- Evaluated model performance with RMSE and R² metrics
- Formulated and solved constrained optimization problem for energy allocation:
  - Max 100 zillion DSML per galaxy
  - Minimum 10% energy for galaxies with index < 0.7
- Allocated energy to maximize total well-being

---

## Skills Demonstrated

- Advanced data cleaning and preprocessing in Python
- Exploratory Data Analysis (EDA)
- Regression modeling (prediction of continuous target)
- Feature engineering and selection
- Business problem translation into data workflows
- Constrained optimization modeling
- Decision-making based on predictive analytics
- End-to-end Python Data Science project workflow

---

## Tools & Technologies Used

- Python (Pandas, NumPy, Scikit-learn, SciPy, Matplotlib, Seaborn)
- Jupyter Notebook
- HTML export for reporting
- Optimization libraries (SciPy.optimize or CVXPY)
- Data visualization and summary analytics

---

## Deliverables

- Jupyter Notebook (*.ipynb) with full implementation and comments
- HTML version of Notebook
- `requirements.txt` with all Python packages
- `submission.csv` for DSML optimization predictions
- Step-by-step answers to multiple-choice questions (Task 1)

---

## Key Learning Outcomes

- Performing advanced data cleaning and preprocessing
- Forecasting continuous variables using regression
- Feature engineering for predictive models
- Converting business and scientific problems into Python workflows
- Applying optimization to allocate constrained resources
- Communicating results via notebooks and visualization

---

## Future Improvements

- Implement non-linear models (e.g., Random Forest, Gradient Boosting) for improved index predictions
- Automate energy allocation dashboards for scenario analysis
- Integrate real-time electricity usage and energy forecast system
- Apply cross-validation and hyperparameter tuning to enhance model robustness

