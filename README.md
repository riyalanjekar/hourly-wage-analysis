# Exploratory Analysis of Hourly Wages

This project examines how hourly wages vary with education, employment experience, gender and marital status in a sample of 525 workers. I completed it for the Programming for Data Analytics module of my MSc in Business Analytics at Aston University.

## Analysis

- Summarised the data and handled missing values using median imputation for numeric variables and mode imputation for categorical variables.
- Used histograms, box plots and scatter plots to explore wage distributions and differences across groups.
- Applied a chi-square test to examine the association between gender and marital status, and Welch's t-test to compare mean wages by gender.
- Fitted an ordinary least squares regression to examine how education, employment experience, gender and marital status were associated with hourly wages.

## Key findings

- Hourly wages were right-skewed, with a small number of observations at the upper end of the distribution.
- Years in employment had a positive correlation with hourly wages (Pearson r = 0.34).
- Workers with at least 14 years of education and at least 5 years in employment had a mean hourly wage of 10.30. The mean was 3.98 for workers with at most 12 years of education and at most 2 years in employment.
- The regression explained roughly one-third of the variation in hourly wages. The results describe associations within the sample.

## Run the notebook

Open [hourly_wage_analysis.ipynb](hourly_wage_analysis.ipynb) in Jupyter or Google Colab. Place `wage.xlsx` in the working directory and run the cells in order.

Dependencies include pandas, NumPy, Matplotlib, seaborn, SciPy, statsmodels and openpyxl.
