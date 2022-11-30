# Amex_default_prediction
Credit Decision Model in Lending Industry
Industry Overview:
The global FinTech lending market size was valued 449.85 USD Bn in 2020 and is projected to reach 4957.16 USD Bn by 2030, growing at a CAGR of 27.4% from 2021 to 2030.
Top Indian Companies in market - 
Jupiter Money
          Slice
          Fi Money
          Unicard
          Razorpay
          Navi
Facilities provided - 
          Credit Card
          Buy Now Pay Later
          Super Card
          Personal Loans
          
Problem Statement:
How to check credit worthiness of a customer?
How much credit limit to be given?
How to decide the interest rate for a particular customer?

Data-Driven Solution: 
Predict the probability that customer does not pay back balance their credit card/ pay later card/ super card based on demographic & historical credit history data

Source:
American Express is a globally integrated payments company. The largest payment card issuer in the world, they provide customers with access to products, insights, and experiences that enrich lives and build business success.
Shape of data 
Rows - 924621
Columns - 190
Performance window - 18 months
Target variable - 120+ DPD latest statement

Features are anonymized and normalized, and fall into the following general categories:
    D_* = Delinquency variables
    S_* = Spend variables
    P_* = Payment variables
    B_* = Balance variables
    R_* = Risk variables

Pre-Processing/Cleaning:
Stratified sample of 10000 data is chosen
Checking data info
Checking duplicates value
Checking Null Values
Dropped columns with 80% Null values
Filling remaining Null values with appropriate methods

EDA, Feature Engineering & Feature Selection
    Univariate Analysis
    Log Transformation
    Impute null values with appropriate methods
    Select top features based on feature importance values
    
Feature Selection Methods:
    Traditional - Bi-variate trend & WoE-IV values
    Random Forest feature importance
 
Business Outcome:
    Decide threshold to Approve/Reject customers
    Dynamic Limit Assignent
    Increase / Decrease limit / block card 
    Risk based pricing
    Customer segmentation & Portfolio analysis
    Spending behavior analysis


