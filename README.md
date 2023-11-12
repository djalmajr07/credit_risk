# Credit Risk Data Project

## A short description of the project
Many people struggle to get loans due to insufficient or non-existent credit histories. And, unfortunately, this population is often taken advantage of by untrustworthy lenders.

Home Credit Group

Home Credit strives to broaden financial inclusion for the unbanked population by providing a positive and safe borrowing experience. In order to make sure this underserved population has a positive loan experience, Home Credit makes use of a variety of alternative data including telco and transactional information--to predict their clients' repayment abilities.

While Home Credit is currently using various statistical and machine learning methods to make these predictions, they're challenging Kagglers to help them unlock the full potential of their data. Doing so will ensure that clients capable of repayment are not rejected and that loans are given with a principal, maturity, and repayment calendar that will empower their clients to be successful.

#### This project was made by Djalma Jr.

# 1. Business Problem.
The business case for predicting home credit default risk is multi-faceted. Home Credit aims to optimize its lending process by identifying applicants who are more likely to default on their loans. This proactive approach enables the company to:

Reduce Default Rates: By accurately assessing credit risk, Home Credit can minimize the number of loans extended to individuals with a higher likelihood of default, thus reducing overall default rates.

Improve Profitability: Lower default rates contribute to increased profitability, as the company can allocate resources more efficiently and focus on borrowers with a better repayment history.

Enhance Customer Experience: Targeted lending based on credit risk analysis helps in tailoring loan terms and conditions. This, in turn, improves the customer experience by aligning loan offerings with individual financial capabilities.

Maintain Regulatory Compliance: Sound risk assessment practices also contribute to regulatory compliance, ensuring that Home Credit adheres to industry standards and legal requirements.

By predicting home credit default risk accurately, Home Credit aims to strike a balance between expanding its customer base and managing credit risk effectively, ultimately fostering sustainable and responsible lending practices.

# 2. Business Assumptions.

# 3. Solution Strategy

My strategy to solve this challenge was:

## `Step 00. Settings and Data Extraction`
* Import of required libraries, packages and functions.
* Loading and checking available data via a CSV file.

## `Step 01. Data Description`
* Renaming of columns and checking the size of the dataset (assessing the need for tools to handle large volumes of data).
* Verification of data types in each column and type changes that are necessary for better treatment by the algorithms later
* Verification of missing data and decision on how to treat them (removal, artificial resampling, solution infeasibility)
* Brief statistical description of the numerical and categorical attributes in order to detect anomalies that are outside the scope of the problem, as well as the presence of possible outliers that will impact the performance of the algorithms later.

## `Step 02. Data Filtering`
* Filtering rows and deleting columns that do not contain information relevant to modeling or do not help to solve the problem.

## `Step 03. Feature Engineering`
Creation of variables (features) relevant to solving the problem

## `Step 04. Exploratory Data Analysis
* Isolated analysis of each feature and its relationship with the others.
* Exploration of the data in order to obtain an intuition of their distribution in the data space (embedding exploration).

## `Step 05. Data Preparation`
* Data preparation to help machine learning models learn and perform more accurately.
* Selection of the embedding space best suited to the problem

## `Step 06. Feature Selection`
* Selection of the most relevant features to train the models

## `Step 07. Hyperparameter Fine Tuning`
* Testing different machine learning models and selecting the one with the best performance based on the chosen metrics (silhouette score)
* Choosing the best values for each parameter from the tested models that maximize performance

## `Step 08. Model Training`
* Training the models with the best parameters found and measuring their performance

## `Step 09. Cluster Analysis`
* Visual inspection of the data space assembled by each model
* Analysis of the profile (attributes) of each cluster for each model trained
* Choice of the final model that presents the best performance

## `Step 10. Exploratory Data Analysis for Business`
* Creation and testing of business hypotheses and elaboration of answers to business questions

## `Step 11. Deploy to Production`
* Planning and implementation of the model deployment architecture
* Creation of the database that will be used to solve the problem

# 4. Top 3 Data Insights

**Hypothesis 01:**

**True/False.**

**Hypothesis 02:**

**True/False.**

**Hypothesis 03:**

**True/False.**

# 5. Machine Learning Model Applied

# 6. Machine Learning Modelo Performance

# 7. Business Results

# 8. Conclusions

# 9. Technologies

# 10. Lessons Learned

# 11. Next Steps to Improve


# Author

Djalma Luiz da Silva Junior



[<img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>](https://www.linkedin.com/in/djalmajunior07)
