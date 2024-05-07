# Data Science for Business (Technical) Project
## Credit Risk Assessment for Lending Institutions

## Team Members
- Anubhav Ghildiyal (ag8766@nyu.edu)
- Noel Nebu Panicker (nnp5666@nyu.edu)
- Viraj Parikh (vp2359@nyu.edu)
- Yogya Sharma (ys5250@nyu.edu)

## Project Overview
This project aims to assess credit risk for lending institutions using various data science techniques. The analysis leverages a dataset of credit customers to identify patterns and predict creditworthiness, enabling more informed lending decisions.

## Data Description
The dataset includes 1,000 entries of customer data with the following attributes:
- Checking status
- Loan duration
- Credit history
- Loan purpose
- Credit amount
- Savings status
- Employment duration
- Installment rate
- Personal status and sex
- Other debtors/guarantors
- Present residence since
- Property magnitude
- Age
- Other installment plans
- Housing
- Existing credits at this bank
- Job
- Number of people being liable to provide maintenance for
- Telephone
- Foreign worker
- Credit risk class (Good/Bad)

## Objectives
1. **Data Exploration:** Analyze the dataset to understand the distribution and correlation of various features with credit risk.
2. **Data Preparation:** Transform and select features to improve model predictions.
3. **Modeling:** Implement and compare different machine learning models to predict credit risk. The models include:
   - Random Forest Classifier
   - Logistic Regression
4. **Evaluation:** Assess model performance using metrics like AUC, accuracy, precision, and recall.
5. **Decision Logic:** Utilize the best-performing model to categorize customers into risk groups and suggest appropriate credit limits and interest rates.

## Tools Used
- Python
- Pandas and NumPy for data manipulation
- Matplotlib and Seaborn for data visualization
- Scikit-learn for implementing machine learning models


## Results
The project successfully implements a model that can predict credit risk with an accuracy of 78% and an AUC of 0.82. These insights can help lending institutions minimize risk and make informed decisions.

## Future Work
- Explore more sophisticated algorithms like Gradient Boosting and Neural Networks.
- Integrate more features that might impact credit risk.
- Develop a web application to make real-time predictions.
