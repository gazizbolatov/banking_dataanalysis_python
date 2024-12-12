# Bank Marketing Data Analysis

## Overview
In this project, we analyze customer data from a bank to understand which characteristics are most commonly associated with acquiring loans and mortgages. The data used for this project is sourced from Kaggle's Bank Marketing Dataset.

The project focuses on analyzing customer age groups and their preferences regarding mortgage loans, as well as testing the hypothesis about the average age of clients who have loans. Based on the analysis, several key findings and recommendations have been made for the bank's business strategy.

## Project Steps

### 1. Data Preprocessing:
- The data was cleaned by removing any missing or inconsistent entries.
- We mapped categorical values into numerical values for further analysis (e.g., converting 'yes' and 'no' to 1 and 0 for loan status).

### 2. Hypothesis Testing:
- We tested the hypothesis that the average age of customers with loans is greater than 30 years using a t-test for the mean.
- The result showed that the mean age is indeed greater than 30 years, which was statistically significant, with a very low p-value (p < 0.05).

### 3. Data Modeling:
- Logistic Regression was used to predict the probability of acquiring a loan based on customer age.
- The model achieved an accuracy of 87.55%, which indicates that age is a strong predictor of loan acquisition.

### 4. Visualization:
- Various plots were used to visualize the distribution of loan applicants across different age groups.
- The results were presented visually to identify trends, such as higher loan acquisition rates in the 30-40 age group.

## Key Findings and Recommendations

### 1. Average Age of Clients with Loans:
- The average age of clients with loans was found to be around 40 years, significantly higher than 30 years. This confirms that older customers are more likely to apply for loans or they still have unpaid loans.

**Recommendation:** Focus marketing and loan offerings on the 30-40 age group, as they are more likely to be actively acquiring mortgages. Offer flexible terms and smaller loans for the younger demographic (under 30 years).

### 2. Mortgage Acquisition by Age Groups:
- Younger individuals (under 29 years) are less likely to acquire mortgages. This could be due to limited financial stability, as many in this group may still live with their parents as studies show.
- Customers aged 30-40 years tend to have more mortgages than younget generation
- People over 50 years old are less likely to have active mortgages, as they may have already repaid their loans or used the reduced purchasing power when buying a house.

**Recommendation:** Offer tailored mortgage programs for younger individuals with lower interest rates or debt restructuring options to encourage more young people to consider home ownership.

### 3. Client Demographics:
- The primary customer base of the bank consists of working individuals aged 30-40 years. This group is more likely to still have mortgages, which is a crucial segment for the bank.

**Recommendation:** Increase targeted marketing and offer special mortgage products for this group. Additionally, partner with large employers to provide exclusive mortgage options for younger employees (up to 29).

### 4. Loan Probability by Age:
- The probability of acquiring a loan decreases as age increases. Clients aged 20 years have a 14.82% chance of getting a loan, while those aged 50 years have only a 12.75% chance.

**Recommendation:** Develop personalized loan products for different age groups, especially creating new ways to acquire young customers with flexible payment plans

## Model Performance
The Logistic Regression model achieved an accuracy of 87.55%, which demonstrates its effectiveness in predicting loan acquisition based on customer age.

## Conclusion
This analysis provides valuable insights for optimizing the bank's marketing strategies and improving customer targeting. The findings suggest that age plays a significant role in loan acquisition, with the 30-40 age group being the most likely to acquire mortgages. By offering tailored products and promotions to different age groups, the bank can increase its customer base and improve loan acquisition rates. Additionally, enhancing the predictive model with more customer features could further improve its performance and help better target potential clients.

## Technologies Used
**Python Libraries:**
- Pandas
- NumPy
- Matplotlib & Seaborn for data visualization
- Plotly for interactive visualizations
- Scikit-learn for machine learning models and metrics

Screenshot of the work:
![screenshot_banking](https://github.com/user-attachments/assets/9b1f0c13-c19e-4d96-9b16-55f56ee80b4c)
