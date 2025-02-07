## Customer Churn Analysis and Predictive Modeling:

In this project, we analyze the factors influencing customer churn and develop a predictive model to anticipate this behavior. The goal is to help companies identify the customers most likely to cancel their subscription in order to implement targeted loyalty actions.

We start with a data exploration, accompanied by visualizations to illustrate the impact of the different variables on the churn decision. Statistical tests are also performed to confirm the significance of the observed relationships.

For the development of the predictive model, we perform an analysis of the importance of the variables to identify those that most influence the customer decision. As part of the feature engineering, we select the relevant variables and make the necessary adjustments to optimize the data quality.

Using pipelines, we test several algorithms in parallel. Based on performance criteria (precision, recall, F1-score), we retain the best performing model: XGBoost. The latter is then refined to obtain the best possible version.

Finally, we evaluate the robustness of the model through several methods: ROC curve, confusion matrix, and cross-validation, thus ensuring its reliability and its ability to generalize on new data.

Data from: A fictional telco company that provided home phone and Internet services to 7043 customers in California in Q3. https://www.kaggle.com/datasets/yeanzc/telco-customer-churn-ibm-dataset/data
