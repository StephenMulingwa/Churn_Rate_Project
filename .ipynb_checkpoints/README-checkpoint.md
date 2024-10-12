# Investigating Churn Rate in telecommunication companies using Neural Networks.
By: [STEPHEN MULINGWA](https://www.linkedin.com/in/stephen-mulingwa-105522205/)

![image](https://github.com/user-attachments/assets/7e6a6b31-2dd7-4df2-9978-65ee54cd3b2b)

## Overview

The Customer Churn Rate Project aims to address the pressing issue of high customer attrition within Kenya's e-commerce sector, where the retention rate stands at a low 4.6%. The project focuses on developing and implementing advanced machine learning models, specifically Recurrent Neural Networks (RNN) and Convolutional Neural Networks (CNN), to predict and mitigate customer churn. By analyzing customer behavior and identifying key churn indicators, businesses can proactively implement targeted strategies to retain customers. The project compares the performance of RNN and CNN models using metrics such as accuracy, precision, recall, F1 score, and ROC-AUC. Ultimately, the goal is to equip e-commerce companies with a reliable tool to enhance customer loyalty and improve long-term profitability.

### Business Problem:
Kenya’s e-commerce sector is experiencing a significant challenge with customer churn, as the retention rate has dropped to a concerning 4.6%. This high rate of customer attrition negatively impacts profitability and business sustainability. Traditional methods of managing customer churn often fall short as they focus primarily on immediate financial outcomes without adequately addressing the long-term effects of customer loss. Therefore, businesses need a more effective, data-driven approach to predicting and preventing customer churn in order to retain their customer base and sustain growth in a competitive market. The project aims to:
1. Develop a Customer Churn Prediction Model: Implement advanced machine learning models such as Recurrent Neural Networks (RNN) and Convolutional Neural Networks (CNN) to accurately predict customer churn in the e-commerce sector.
2. Optimize Model Performance: Fine-tune the architectures and hyperparameters of the RNN and CNN models to maximize their predictive capabilities and enhance overall model performance.
3. Compare Prediction Models: Conduct a thorough comparison between the RNN and CNN models using performance metrics such as accuracy, precision, recall, F1 score, and ROC-AUC to determine the most effective model for predicting churn.
4. Support Business Decision-Making: Leverage insights from the churn prediction models to inform and guide e-commerce companies in developing targeted retention strategies, thus reducing churn and increasing customer loyalty.

### Data
The dataset represents customer information from an e-commerce platform, including detailed demographic, service usage, and subscription data. It features variables such as customer location (city, state, county, zip), personal details (age, gender, marital status, education, employment), and service-related attributes like internet service type, contract duration, and payment method. The dataset also tracks customer churn, a key indicator of whether a customer has discontinued the service, along with other behavioral factors like yearly equipment failures, outage seconds per week, and email or contact frequency. Additionally, variables related to customer usage patterns, such as bandwidth and monthly charges, are included to analyze and predict customer churn rates.

## Methods
The Telecommunications data is analysed by use of visualizations. Sample visualizations include:

i. Churn Bar Plot

![image](https://github.com/user-attachments/assets/7adff770-8b88-4a0b-8358-784a0a47b4ae)

From the bar plot 26.5% of the Telecommunication customers churned in the company while 73.5% did not churn. 

ii. Tenure Bar Chat

![image](https://github.com/user-attachments/assets/93391b05-5f6b-4b3f-bc17-e9c059eb82b5)

From the tenure bar chart, it is evident that with increase in tenure the probability of a customer churn decreases. The highest churning customers in the telecommunication company are the new customers in the company.

iii. Monthly Charge Bar Chart

![image](https://github.com/user-attachments/assets/2d2de081-1a7b-4f73-9c53-5d3f870d462c)

From the monthly bar chart above it is evident with an increase in the monthly charge of customers the number of churning customers increases.

iv. Confusion Matrix

![image](https://github.com/user-attachments/assets/57c828aa-5410-4f0d-834a-f95a394ef428)

The confusion matrix shows that the model performed well, achieving an accuracy of 91.2%. It correctly predicted 1327 "No" cases (true negatives) and 468 "Yes" cases (true positives), with a recall of 86%, meaning it identified most positive cases accurately. However, the model produced 129 false positives (predicting "Yes" when it should be "No") and 76 false negatives (predicting "No" when it should be "Yes"). While the precision for "Yes" predictions is 78.4%, indicating some room for improvement in minimizing false positives, the overall balance between precision and recall reflects a solid predictive performance. This matrix suggests the model is reliable, though further tuning might be needed if reducing false positives or false negatives is critical for the task.

v. RNN and CNN Model Comparison

![image](https://github.com/user-attachments/assets/b522e4d4-7fae-4543-86a3-c32de17c335a)

**RNN Model Accuracy: 0.8870000243186951 **
This value represents the accuracy achieved by the RNN model. Accuracy is a measure of the proportion of correct predictions made by the model out of the total number of predictions. In this case, an accuracy of approximately 0.887 indicates that the RNN model correctly predicted the class of 88.7% of the samples in the dataset used for evaluation.
**CNN Model Accuracy: 0.8974999785423279**
This value represents the accuracy achieved by the CNN model. Similarly, an accuracy of approximately 0.897 indicates that the CNN model correctly predicted the class of 89.75% of the samples in the dataset used for evaluation.
In summary, the output provides a comparison of the performance of the RNN and CNN models in predicting churn rate based on their respective accuracies. The CNN model has a slightly higher accuracy than the RNN model, suggesting that it may perform slightly better in correctly classifying instances of churn and non-churn.

## **Conclusion:**

This study focused on predicting customer churn in the telecommunication industry using CNN and RNN models, with the goal of identifying at-risk customers and improving retention strategies. We found that approximately 26.5% of customers churned, highlighting the significance of churn prediction for the company. Both models performed well, with CNN slightly outperforming RNN in accuracy. Key factors such as customer tenure, monthly charges, and onboarding experience were closely associated with churn rates. These insights emphasize the importance of data-driven approaches to identifying churn behaviors and implementing proactive strategies to mitigate customer loss. By leveraging predictive analytics, telecommunication companies can better anticipate customer needs, optimize their offerings, and foster long-term loyalty.

### Recommendations:

1. Implement Predictive Models: Telecommunication companies should utilize CNN and RNN models to predict customer churn and intervene early with retention initiatives tailored to individual customers.
2. Improve Onboarding for New Customers: Companies should enhance the onboarding experience with personalized support and proactive engagement to reduce churn among new subscribers.
3. Optimize Pricing Strategies: Review and adjust pricing structures to balance customer satisfaction and profitability, offering flexible plans and incentives for long-term customers.
4. Enhance Customer Engagement: Invest in continuous communication through loyalty programs, personalized marketing, and real-time feedback mechanisms to build customer loyalty and reduce churn.