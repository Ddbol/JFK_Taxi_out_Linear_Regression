# JFK_Taxi_out_Linear_Regression Nov 2019 – Jan 2020

Files:

M1_final.csv - data input

Linear_regression_JFK DBoland Feb 2025.ipynb - code

JFK Taxi_out Linear Regression DBoland Feb 2025.pptx - Presentation of data analysis, visualisation and linear regression (View raw to view online and interact with links)

JFK Taxi_out Linear Regression DBoland Feb 2025.pdf - Pdf of presentation of data analysis, visualisation and linear regression

Objective: 
At JFK airport Taxi-Out prediction is an important concept for calculating runway time and directly impacts the cost of  flights. Create Linear Regression Model  of  JFK Taxi-Out, using data scraped from an Academic Paper under Review by IEEE transportation covering Nov 2019- Jan 2020 (D Kansal, Kaggle dataset)

Summary:
Conducted an exploratory data analysis and found very little correlation of the numeric features to the Taxi-out target variable. Generated linear regression models - Multi Linear Regression (MLR) or Ordinary Least Squares (OLS), Lasso and Ridge. Compared r2 of models when generated with 3 (highest correlation) ,8 (mid correlation) or 14 (most features regardless correlation) features. More features slightly increased r2 but only from 0.06 to 0.08. Linear regression was found not to be appropriate for modelling Taxi-out based on this dataset. 

Tools used:
Python, pandas, numpy, matplotlib, seaborn, scikitlearn, standard scalar, Linear Regression, Ridge, Lasso
