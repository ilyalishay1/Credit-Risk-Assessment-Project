# Credit-Risk-Assessment-Project
Project Goals:

Analyze borrower profiles and their financial behavior
Create a classification model to identify reliable and high-risk clients.
Build a dashboard to highlight segments that may be riskier, more profitable, or require different underwriting policies
Project Stages:

Data Preparation

Removing duplicates, handling missing values and outliers, analyzing variable distributions
Exploratory Analysis:

Financial Profile:

What is the average loan_percent_income across different income levels?
Who most often takes out large loans — by age, experience, property type?
How are income and interest rate (loan_int_rate) related?
How does loan_percent_income vary depending on credit grade (loan_grade)?
Credit History and Risk:

How does credit history length (cred_hist_length) affect loan amount?
What is the average credit history length across age groups?
How is default history (cb_person_default_on_file) related to interest rate?
Who has more defaults — by age, loan purpose, or employment status?
Dependence on Loan Purpose:

Which loan purposes are more often linked to large amounts?
Which loan intents have a higher share of borrowers with default history?
For the Classification Model:

Encoding categorical variables and scaling all features
Which features are most informative for predicting default?
Which features are correlated?
How does loan_grade affect default probability?
Is there multicollinearity — especially among features like interest rate / amount / income?
Model Building

Choosing an algorithm and building the classifier
Evaluating and improving the model
Predicting client classes on new data
Dashboard Creation

Creating visualizations:
What is the average loan amount by loan purpose?
How do interest rates differ by loan purpose?
How is borrower age distributed by loan purpose?
What is the average credit burden by loan purpose?
How does homeownership category vary by loan purpose?
How is credit score related to loan purpose?
