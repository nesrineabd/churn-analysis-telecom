# Customer Churn Analysis for Telecom Company

Context : Churn in business refers to how many customers leave a company within a timeframe, often measured in subscription-based industries like telecommunications. It's crucial for companies to understand and analyze churn to boost customer retention and profitability.

## Project Overview

In this project, our objectives are to:

- Analyze and identify patterns among customers who churn by looking at common services or characteristics, using Exploratory Data Analysis (EDA).
- Explore how the churn rate can be explained by the other variables and formulate a series of hypotheses using a comprehensive set of charts and graphs.
- Implement and evaluate various machine learning models to predict churn rates, confirming or refuting the EDA's hypothesis.
- Uncover key findings and actionable insights from data analysis, enabling the business to implement targeted customer retention strategies and reduce churn rates.


## Dataset

The dataset includes information about customers of the telecommunications company, with features that may influence churn. These features include demographic details, service usage, contract types and others.

## Resources:

- The dataset used can also be found at [Telco Customer Churn](https://www.kaggle.com/datasets/palashfendarkar/wa-fnusec-telcocustomerchurn)

- This project was inspired by the notebook [telecom-churn-prediction](https://www.kaggle.com/code/bandiatindra/telecom-churn-prediction/notebook) done by Atindrabandi 


--------------------------------------------------------------
## Key Findings and Actionable Insights
Through our comprehensive data study, we've pinpointed two primary findings and strategic steps to begin resolving and decreasing this rate.

- **1. Optimize Contract Terms**: Short-term contracts are a significant factor contributing to customer churn. it's important to identify the root cause, which can be done through surveys or interviews. Causes may include :
    - Do they lack trust or confidence in the service?
    - Is it a pricing issue?
    - Are short-term contracts more flexible or heavily marketed?

    To address this, consider motivating customers to choose longer-term contracts by improving the value proposition, for example, add :
    - Trial periods before locking in
    - More benefits (eg. premium support, free upgrades, priority service)
    - Discounts for annual or multi-year plans

- **2. Improve Service Offerings**: Investigate why optic fiber internet service and electronic check payment users have higher churn. This likely points to problems with service reliability, customer support, or pricing in those areas. 
    To address this : 

    - Network uptime: Ensure consistent performance with minimal downtime. Invest in infrastructure to enhance reliability
    - Customer support: Offer faster, more accessible support channels. When issues arise, quick, helpful resolutions reduce frustration
    - Proactive maintenance: Notify users ahead of time about scheduled maintenance or outages, so they aren’t caught off-guard
    - Speed and bandwidth guarantees: Offer performance guarantees (eg. "We guarantee speeds of X Mbps") to ensure expectations are clear and met
    - Provide exclusive discounts on these services to encourage greater adoption and long-term commitment

Of course, in addition to these, there could be other underlying factors that weren't captured in the data or that went unreported.
