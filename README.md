# Project for Analyzing Credit Card Approvals
<p>Commercial banks receive <em>a lot</em> of applications for credit cards. Many of them get rejected for many reasons, like high loan balances, low income levels, or too many inquiries on an individual's credit report, for example. Manually analyzing these applications is mundane, error-prone, and time-consuming (and time is money!). Luckily, this task can be automated with the power of machine learning and pretty much every commercial bank does so nowadays. In this notebook, we will build an automatic credit card approval predictor using machine learning techniques, just like the real banks do.</p>
<p><img src="https://assets.datacamp.com/production/project_558/img/credit_card.jpg" alt="Credit card being held in hand"></p>

We'll deal with the <a href="http://archive.ics.uci.edu/ml/datasets/credit+approval">Credit Card Approval dataset</a> from the UCI Machine Learning Repository. The analysis of this dataset notebook is performed in the following steps:
1. Once we load the dataset, we inspect the datatypes, statistics, and the missing values.
2. We will preprocess the dataset by imputing the missing values in the columns of both numeric and categorical data.
3. We build a simple machine learning model that can predict if an individual's application for a credit card will be accepted.

Note that since this data is confidential, the contributor of the dataset has anonymized the feature names.