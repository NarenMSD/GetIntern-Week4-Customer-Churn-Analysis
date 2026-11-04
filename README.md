📊 Customer Churn Storyboard: Data-Driven Analysis

  Python (https://img.shields.io/badge/Python-3.8%2B-blue) (https://www.python.org/)

  Pandas (https://img.shields.io/badge/Pandas-Data%20Wrangling-orange) (https://pandas.pydata.org/)

  Seaborn (https://img.shields.io/badge/Seaborn-Visualization-green) (https://seaborn.pydata.org/)

  📌 Executive Summary

  This project is a comprehensive exploratory data analysis (EDA) conducted as part of the Week 4 Milestone of the Data Science Internship at GetIntern.in.
  The primary objective was to synthesize data cleaning and visualization skills to uncover why customers are leaving the telecommunications service
  (Churn).

  By analyzing the Telco Customer Churn dataset, I identified three primary drivers of attrition: Contract Flexibility, Payment Friction, and Baseline
  Stability.

  ---

  🛠️ Technical Stack

  - Environment: Google Colab (Jupyter Notebook)
  - Data Manipulation: Pandas, NumPy
  - Visualization: Seaborn, Matplotlib

  ---

  🔍 Business Questions & Findings

  1. What is the company's baseline churn rate?

  - Finding: The baseline churn rate is approximately 26.5%.
  - Insight: Nearly 1 in 4 customers are leaving the service. This provides a clear benchmark for measuring the success of future retention campaigns.

  2. How do contract durations influence churn?

  - Finding: Customers on Month-to-Month contracts churn at a significantly higher rate than those on one-year or two-year contracts.
  - Insight: Long-term contracts act as a "lock-in" mechanism. The high churn in month-to-month users suggests they have low switching costs and lower
    loyalty.

  3. Does the payment method correlate with churn?

  - Finding: The Electronic Check method shows a disproportionately high churn rate compared to Credit Card or Bank Transfer methods.
  - Insight: This indicates a potential "pain point" in the electronic check payment process, which may be causing customer frustration.

  ---

  💡 Strategic Recommendations

  Based on the data analysis, I propose the following business actions:
  1. Incentivize Contract Migration: Offer a small discount or bonus to Month-to-Month customers who switch to a 1-year contract.
  2. Payment Process Audit: Conduct a UX (User Experience) review of the Electronic Check payment flow to identify and fix bugs or friction.
  3. Loyalty Rewards: Implement a reward system for customers reaching the 12-month mark to reduce the "churn cliff" seen in short-term contracts.

  ---

  🖼️ Visual Storyboard


  ┌────────────────────────────────────────────┬─────────────────────────────────────────────┬───────────────────────────────────────────┐
  │             Overall Attrition              │             Contract Influence              │            Payment Correlation            │
  ├────────────────────────────────────────────┼─────────────────────────────────────────────┼───────────────────────────────────────────┤
  │ Baseline Churn (images/baseline_churn.png) │ Contract Impact (images/contract_churn.png) │ Payment Method (images/payment_churn.png) │
  ├────────────────────────────────────────────┼─────────────────────────────────────────────┼───────────────────────────────────────────┤
  │        Baseline Churn Distribution         │           Churn by Contract Type            │          Churn by Payment Method          │
  └────────────────────────────────────────────┴─────────────────────────────────────────────┴───────────────────────────────────────────┘

  ---

  📂 Project Structure

  ├── Customer_Churn_Analysis_Week4.ipynb    # Full analysis with code & narratives
  ├── images/                                # Folder containing exported charts
  └── README.md                              # Project documentation

  👤 Author

  - Name: Narendra Mampa
  - Internship: Data Science Intern @ GetIntern.in
  - GitHub: 
