# Enhancing-Credit-Risk-Analysis-for-Lending-Club-through-Machine-Learning
Using machine learning techniques to predict   loan default probability for Lending Club, aiming to improve risk management, enhance revenue, and maintain investor confidence

# Lending Club Credit Risk Analysis Using Machine Learning

## Executive Summary
This project utilizes machine learning techniques to identify at-risk accounts for Lending Club, the leading peer-to-peer lender. By analyzing borrower characteristics beyond credit scores, such as income, property ownership, and default history, we aim to enhance Lending Club's lending capabilities, improve revenue, and minimize losses.

## Opportunity
Credit scores, while useful, provide a limited view of a borrower's risk. Expanding the data analyzed to include additional borrower characteristics can unlock growth opportunities for Lending Club and other peer-to-peer lenders.

## Data Overview
The dataset includes borrower profiles and loan outcomes from January 2007 to January 2015, totaling 887,379 entries across 74 columns. It encompasses information on whether loans were fully paid, defaulted, current, or delayed.

## Solution
We predict the future risk of default for currently active loans using a model trained on past loan outcomes. The approach involves classification models like Logistic Regression, Random Forest, and Gradient Boosted Trees, focusing on the accuracy of predicting defaults due to their significant impact compared to the upside of fully repaid loans.

## Background and Context
The dataset is sourced from Kaggle and encompasses a comprehensive range of borrower information. Credit Risk Analysis is a cornerstone in finance, dealing with the assessment of a borrower's repayment ability. This project seeks to apply machine learning to emulate traditional credit risk assessment techniques used by banks and lenders.

## Analysis
Our analysis indicates the need for data balancing and reveals that loan grade, while a clear determinant for interest rates, does not directly correlate with loan outcomes. This necessitates a model that goes beyond simple statistics to assess default probability.

## Model Formulation
We frame this as a supervised classification problem, aiming to predict the likelihood of default for active loans based on past borrower profiles. Economic assumptions guide the model's classification threshold, aiming for a default probability cut-off less than 12.5% to ensure profitability.

## Models and Results
The project explores Logistic Regression with Lasso Regularization, Random Forest, and Gradient Boosted Trees, evaluating them based on recall, accuracy, F1 score, and MSE. An ensemble approach combining predictions from the best-performing models is adopted to enhance reliability and generalizability.

## Recommendations
Based on the model's predictions, we identify ideal and at-risk borrowers, offering recommendations for Lending Club to address the increase in risky accounts, target specific borrower segments, and adopt proactive measures to mitigate default risks.

## Conclusion
Implementing these models can significantly benefit Lending Club by refining risk analysis, streamlining the loan approval process, and targeting ideal customers more effectively.

## References
- Kaggle Dataset: [Credit Risk Dataset](https://www.kaggle.com/datasets/ranadeep/credit-risk-dataset/data)
- Wikipedia
- LendingClub Homepage
- Stack Overflow
- Official Python Library Documentation
- Investopedia
