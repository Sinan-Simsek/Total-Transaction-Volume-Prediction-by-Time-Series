# Total-Transaction-Volume-Prediction-by-Time-Series

####################### ##############
# Business Problem
####################### ##############

# Iyzico is a financial technologies company that makes the online shopping experience easier for both buyers and sellers.
# It provides payment infrastructure for e-commerce companies, marketplaces and individual users.
# It is expected to estimate the total transaction volume on a merchant_id and daily basis for the last 3 months of 2020.


####################### ##############
# Dataset Story
####################### ##############
# Includes data from 7 member businesses from 2018 to 2020.

# Transaction: Number of transactions
# MerchantID: IDs of member businesses
# Paid Price: Payment amount

####################### ##############
# TASKS
####################### ##############

# Task 1: Exploration of the Dataset
             # 1. Read the iyzico_data.csv file. Change the type of transaction_date variable to date.
             # 2.What are the start and end dates of the data set?
             # 3.What is the total number of transactions in each merchant?
             # 4.What is the total payment amount at each merchant?
             # 5. Observe the transaction count graphs of each member business in each year.

# Task 2: Apply Feature Engineering techniques. Create new features.
             #DateFeatures
             # Lag/Shifted Features
             # Rolling Mean Features
             # Exponentially Weighted Mean Features

# Task 3: Preparation for Modeling
             # 1.Do one-hot encoding.
             # 2.Define Custom Cost Functions.
             # 3. Separate the data set into train and validation.

# Task 4: Create the LightGBM Model and observe the error value with SMAPE.
