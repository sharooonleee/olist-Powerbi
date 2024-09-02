# olist-Powerbi
![bi sales trend](https://github.com/user-attachments/assets/d7083ed2-9f1f-416a-8467-d21fd906f94a)
![bi orders](https://github.com/user-attachments/assets/2f833d17-835b-483b-b9d0-e130907c8c86)
![bi delivery](https://github.com/user-attachments/assets/89d25584-fe6b-4a3f-8985-4e5f5fe4e7c1)
![bi payment](https://github.com/user-attachments/assets/e876ff08-e993-4b83-af3e-6a09d86d94ae)
![bi reviews](https://github.com/user-attachments/assets/3c2ebbad-51be-4d8f-a696-dc428d1cb8e7)
Data Visualization Mini Project: 
Marketing Analysis on Brazilian E-Commerce Public Dataset by Olist

Project Overview

This project utilizes a Brazilian e-commerce public dataset from Olist Store, focusing on marketing analysis through various visualizations created in Power BI. The dataset includes comprehensive data on 100k orders made between November 2016 and November 2018 across multiple marketplaces in Brazil. The analysis aims to explore order trends, customer behavior, delivery performance, payment methods, and product reviews.

Data Cleaning and Preprocessing


Drop incomplete data
To ensure accuracy and precision in the analysis, data from the incomplete year 2016 and dates after August 2018 were excluded  to avoid biases and ensure the dataset represents a complete time series for the selected period.
Translation of Brazilian  Reviews
For the reviews dataset, due to the fact that the language in the reviews are in Brazilian, we translated all reviews to English.
Sentimental Analysis
In order to determine the overall sentiment (positive, negative, neutral) of each review, we made use of Python libraries  TextBlob for sentiment analysis.

Introduction to PowerBi Interface


Visualizations in our PowerBi interface collectively provide a comprehensive overview of Olist's operations, helping to identify trends, strengths, and areas for improvement across sales, delivery, payment, and ordering processes.

In detail, we mainly focused on the following 5 aspects:

Order Trends and Seasonal Analysis
![bi sales trend](https://github.com/user-attachments/assets/d7083ed2-9f1f-416a-8467-d21fd906f94a)
This visualization aims to offer stakeholders a comprehensive view of Olist's sales performance, which helps stakeholders understand sales dynamics, evaluate business strategies, and make informed decisions to drive growth.
Performance Tracking


Sales and Order Trends: 

Displays the correlation between sales value and order count over time, helping stakeholders track performance and growth.
Growth Analysis
Year-over-Year Growth: 

Highlights significant growth in orders (135.07%) and sales (136.98%), indicating successful strategies or market expansion.
Seasonal Insights


Seasonal Analysis of Orders: 

Identifies patterns in order volumes across different months, aiding in inventory and marketing planning.
Customer and Seller Dynamics


Count of Sellers and Customers: 

Shows the growth in both sellers and customers, providing insights into market penetration and platform expansion.

Findings:
The analysis reveals that  a total of 99k orders from 96k customers and 3095 sellers. The year-over-year (YoY) sales growth is significant at 136.98%, although a month-over-month (MoM) decrease of 4.14% suggests seasonal fluctuations. 
As observed in the sales trend, a noticeable peak in sales is observed towards the end of 2017, likely driven by holiday shopping. Seasonal analysis further illustrates higher sales volumes during certain months, particularly in the latter half of the year. Therefore, we are looking forward to observing a significant sales increase at the end of 2018. 

Customer Behavior
![bi orders](https://github.com/user-attachments/assets/2f833d17-835b-483b-b9d0-e130907c8c86)
This page aimed to provide insights about ordering patterns of customers.
Customer Behavior Insights
Order Volume by Day and Time: Helps identify peak ordering times, allowing stakeholders to optimize staffing, marketing, and operational strategies to meet demand.
Sales and Inventory Management
Best Selling Categories: Provides insights into which products are most popular, aiding in inventory planning and marketing focus.
Operational Efficiency
Average Purchase Value: Offers an understanding of customer spending habits, which can inform pricing strategies and promotional activities.
Strategic Planning
Order Trends: Helps stakeholders understand growth patterns and make informed decisions about scaling operations or entering new markets.

Findings:
Analysis shows that  Monday through Wednesday are the busiest ordering days with a slight decline towards the weekend. Most orders occur in the afternoon (38.58%) and evening (34.3%), with fewer transactions during the morning and midnight hours. The average purchase value is $137.7, with furniture and fashion emerging being the top-selling categories.
Delivery Performance
![bi delivery](https://github.com/user-attachments/assets/89d25584-fe6b-4a3f-8985-4e5f5fe4e7c1)
This page focuses on Olist's delivery performance and logistics, which helps stakeholders understand customer experiences and identify areas for improvement to enhance satisfaction and loyalty.

Enhancing Delivery Efficiency

On-Time Delivery Percentage: At 92.11%, this metric helps stakeholders assess the reliability of the delivery process and identify areas for improvement.
Average and Max Delivery Days: These figures (24.30 days average, 156 days maximum) highlight delivery performance and potential bottlenecks.

Cost Management
Average Delivery Cost: At 19.99, this metric aids in evaluating and optimizing delivery expenses.
Top Cities with Highest Delivery Charges: Identifying cities with high delivery costs can help in renegotiating logistics contracts or adjusting pricing strategies.

Customer Satisfaction
Delivery Lead Time: The distribution of delivery times provides insights into customer experiences and expectations.
Strategic Planning
Sales Distribution Map: Visualizing sales concentration helps identify key markets and optimize logistics routes.

	Findings:
The on-time delivery rate stands at 92.11%, with an average delivery time of 24.3 days and a maximum of 156 days. Most deliveries are completed within 8-30 days. Sao Paulo leads as the city with the most customers, followed by Rio de Janeiro and Belo Horizonte. Delivery costs vary, with Itupiranga incurring the highest average delivery charges.

Payment Methods
![bi payment](https://github.com/user-attachments/assets/e876ff08-e993-4b83-af3e-6a09d86d94ae)
This page analyzes payment methods and preferences, which provides insights into payment behaviors, aiding in financial planning and enhancing customer satisfaction through optimized payment options.

Understanding Customer Preferences
Payment Method Distribution: Identifies the most popular payment methods, such as credit cards, helping stakeholders tailor payment options to customer preferences.

Financial Planning
Installment Preferences: Shows how customers prefer to pay (e.g., in full or in installments), which can inform financing and cash flow strategies.

Sales Optimization
Effect of Payment Method on Sales: Highlights how different payment methods impact total sales, allowing stakeholders to optimize payment offerings to boost revenue.

Strategic Decision-Making
Trends Over Time: Tracks changes in payment method usage over time, helping stakeholders adapt to evolving customer behaviors and market trends.

Findings:
Credit cards dominate as the preferred payment method, accounting for 73.94% of transactions, and the popularity of credit card usage is constantly increasing over time.
The analysis shows that credit card payments result in the highest total sales, making it the most lucrative payment method for the business.
Most customers prefer to pay in full, with 50.6% opting for full-pay rather than installments, which shows that the installments have little effect on sales.
Product Review
The reviews page visualization provides insights into customer feedback and sentiment, which are crucial for understanding customer satisfaction and areas for improvement. Here's how each component can help stakeholders understand the dataset:

Customer Satisfaction
![bi reviews](https://github.com/user-attachments/assets/3c2ebbad-51be-4d8f-a696-dc428d1cb8e7)

Sentiment Analysis: Shows the distribution of positive, neutral, and negative reviews, helping stakeholders gauge overall customer satisfaction.
Service Improvement
Response Rate: Indicates how effectively the company engages with customer feedback, highlighting areas for improving customer service.
Trend Monitoring
Change of Response Rate Over Time: Tracks how response rates have evolved, providing insights into the effectiveness of customer service strategies.
Product and Service Insights
Negative Reviews Word Cloud: Identifies common issues mentioned in negative reviews, enabling targeted improvements in products or services.
Strategic Planning
Review Score Distribution: Helps understand the overall perception of the company’s offerings, guiding product development and marketing strategies.

Limitations
Insufficient information For Customers Analysis
Customer’s personal information, for instance, gender, age…etc, are unavailable. We are unable to further analyze the correlation of customer age/gender and sales performance.
Insufficient information for Late Delivery Analysis
Seller coordinates are unavailable and we are unable to analyze the correlation of late delivery products and the delivery  distance between sellers and customers.

Conclusion
The visualizations in this report provide valuable insights into customer behavior, sales trends, and operational performance. The data highlights key areas such as seasonal spikes in sales, preferred shopping times, and the effectiveness of credit card payments. Additionally, the analysis reveals that while the overall delivery performance is strong, there is room for improvement in reducing delivery lead times. Product reviews indicate general customer satisfaction, with a majority of positive feedback. These insights can guide strategic decisions in marketing, operations, and customer service for the Olist Store.

Reference:
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

Work Distribution
Research: Sharon/Ceci
Powerbi: Sharon/Ceci/Yan
Report: Sharon/Yan

