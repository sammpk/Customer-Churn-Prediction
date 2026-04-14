**Customer Churn Prediction (Machine Learning Project)**


This project aims to predict customer churn using machine learning models. Customer churn is a critical problem for businesses as losing customers directly impacts revenue.



**Objective**



To build a predictive model that identifies customers who are likely to leave the company, enabling proactive retention strategies.



**Dataset**



* Telco Customer Churn Dataset
* Contains customer demographics, services, and billing information



**Technologies Used**



* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* scikit-learn



&#x20;**Models Implemented**



* Logistic Regression
* Random Forest



**Model Performance**



| Metric    | Logistic Regression | Random Forest |

| --------- | ------------------- | ------------- |

| Accuracy  | 78.8%               | 78.8%         |

| Precision | 62.1%               | 65.0%         |

| Recall    | **51.8%**               | 43.8%         |

| F1 Score  | **56.5%**               | 52.3%         |



**Key Findings**



* Logistic Regression performed better in identifying churn customers due to higher recall.
* Random Forest had better precision but missed more churn cases.
* In churn prediction, recall is more important than precision.



**Feature Importance Insights**



* Total Charges is the most significant factor influencing churn.
* Customers with shorter tenure are more likely to leave.
* Higher monthly charges increase churn probability.



**Business Recommendations**



* Offer discounts for long-term contracts
* Improve onboarding for new customers
* Optimize pricing strategies
* Enhance service quality for high-risk segments



&#x20;**Conclusion**



Logistic Regression is the preferred model for this problem as it better identifies customers at risk of churn, helping businesses take preventive actions.





