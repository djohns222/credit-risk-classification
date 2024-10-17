# credit-risk-classification
Overview 

The purpose of this analysis is to evaluate a logistic regression model trained to predict loan statuses as either healthy (0) or high-risk (1). By analyzing the model's performance using metrics such as accuracy, precision, recall, and the F1 score, the intent is to determine the model’s effectiveness on classifications of loans based on their risk levels. The goal is to provide insights that can help the company make informed lending decisions, minimize defaults, and improve overall financial outcomes. The dataset utilized includes financial information on borrowers, including features such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The primary prediction target is the loan status variable which indicates whether a loan is healthy (0) or high-risk (1). To understand the distribution of the target variable, the value counts were analyzed. This revealed a significant imbalance with a higher number of healthy loans compared to high-risk loans. The methodology leveraged in this challenge consisted of data preparation, feature selection, model training, and model evaluation. 

Results

•	Accuracy:
  o	99.26%: The model correctly predicts the loan status for over 99% of the test instances.
•	Precision:
  o	Healthy Loans (0): 1.00 (100% precision)
  o	High-Risk Loans (1): 0.84 (84% precision)
•	Recall:
  o	Healthy Loans (0): 0.99 (99% recall)
  o	High-Risk Loans (1): 0.94 (94% recall)
•	F1 Score:
  o	Healthy Loans (0): 1.00
  o	High-Risk Loans (1): 0.89

Summary and Recommendation 

The logistic regression model demonstrates exceptional performance in predicting loan statuses. The accuracy of 99.26% indicates the model is highly reliable overall. I would recommend this be used by the company based on its accuracy and recall for both healthy and high-risk loans. The ability to predict healthy loans at a near perfect rate would eliminate any inefficiencies for high credit, low risk borrowers. However, with precision dipping slightly in predicting high-risk loans, I would recommend the company seek supplementary resources to enhance and justify the high-risk outcomes. The capability of the model to predict high-risk loans is ultimately more important than identifying healthy ones due to the desire to manage risk effectively and ultimately to avoid loan default. The statistics back reliability, but to ensure precision compared to healthy loan predictions, further fine tuning and analysis should be considered.
