
# 1. Business Problem Overview


SyriaTel, a telecommunications company, is experiencing customer churn, which is when customers stop using the company’s services. Customer churn is a significant issue as acquiring new customers is often more expensive than retaining existing ones. Therefore, predicting which customers are likely to churn ("soon" stop doing business) can help SyriaTel take proactive measures to retain these customers, thereby reducing churn rates and associated revenue loss.

# 2. Objective

The primary objective of this project is to build a binary classification model to predict whether a customer will stop using SyriaTel's services in the near future. By identifying customers at risk of churning, SyriaTel can implement targeted retention strategies to maintain its customer base and minimize revenue loss.

# 3. Key Business Questions

**i. Who are the customers most likely to churn?**

Understanding the characteristics and behavior of customers at risk of churning will help SyriaTel tailor its marketing and customer service efforts.

**ii. What are the main factors influencing customer churn?**

Identifying key factors that contribute to customer churn will enable the company to address those issues, improve customer satisfaction, and enhance service offerings.

**iii. How can SyriaTel reduce the churn rate effectively?**

By knowing which customers are likely to leave, SyriaTel can offer targeted promotions, improve customer service, and make strategic business decisions to enhance customer loyalty.

# 4. Potential Impact and Benefits

**Revenue Retention**: By reducing churn, SyriaTel can save on costs associated with acquiring new customers and retain revenue from existing ones.

**Customer Lifetime Value (CLV)**: Retaining customers increases their lifetime value, enhancing overall profitability.

**Improved Customer Satisfaction**: By addressing the root causes of churn, SyriaTel can improve its services and customer satisfaction levels.

**Competitive Advantage**: Understanding churn patterns can give SyriaTel a competitive edge by allowing them to respond faster and more effectively to customer needs and market changes.


# 5. Key Metrics for Success


**Model Accuracy**: The ability of the predictive model to correctly classify customers as churn or non-churn.

**Precision and Recall**: Precision measures the accuracy of predicting churn among all churn predictions, while recall measures how many actual churners were correctly predicted.

# 6. Findings and Recommendations

**The Decision Tree model outperforms the Logistic Regression model in terms of;  accuracy where it has a higher accuracy of 87% indicating it performs better overall in correctly classifying instances in the training set, precision score of 59% meaning it is more reliable in terms of the proportion of predicted positives that are truly positive compared to the logistic regression model. The logistic regression model though does have a slightly higher recall, indicating it identifies a slightly higher proportion of actual positives. However, the difference is not significant.**

**Based on these results, the Decision Tree model seems to better predict churn rate aamong SyriaTel`s customers as it does a better job at predicting churn rate based on accuracy score and precision**

**Customers who incur high total day charges, make many customer service calls and have a high total evening charge are most likely to stop using SyriaTel`s Services.**

**The company should prioritise lowering their day charges through probably offering discounts during day time hours, ensuring customer queries are sorted in a first and timely manner and also lowering evening charges to retain customers and reduce the churn rate among their customers**
