# LITA-Customer-Project
This repository contains an analysis of customer subscription data, focusing on subscription duration, popularity, cancellations, revenue, and regional insights. The analysis utilizes Excel for exploratory data analysis (EDA), SQL for querying, and Power BI for visualization
__________
# Project Title:
Customer Subscription Analysis and Insights
_________
# Outline
[Project Summary](#project-summary)

[Project Objectives](#project-objectives)

[Data Source](#data-source)

[Dataset](#dataset)

[Tools used](#tools-used)

[Data Cleaning and Preparation](#data-cleaning-and-preparation)

[Instructions](#instructions)

[Data Analysis](#data-analysis)
- [Excel](#excel)
- [SQL](#sql)

  [Key Findings](#key-findings)

  [Recommendation](#recommendation)

  [Conclusion](#conclusion)
## Project Summary
This repository provides a detailed analysis of customer subscription data to derive insights related to subscription duration, popularity, cancellations, revenue, and regional preferences. The analysis aims to support decision-making for enhancing customer retention and optimizing subscription offerings.
![Screenshot (85)](https://github.com/user-attachments/assets/9791ab84-30c6-417b-a086-fa43c3f7cba2)
__________
## Project Objectives
The objective of this project is to conduct a comprehensive analysis of customer subscription data to identify trends in subscription duration, popularity, and revenue generation across different subscription types and regions. By leveraging Excel for exploratory data analysis (EDA), SQL for data querying, and Power BI for data visualization, the project aims to:
- Assess customer loyalty and retention through average subscription duration.
- Determine the most popular subscription types and analyze factors contributing to their success.
- Evaluate cancellation rates and identify potential areas for customer retention improvement.
- Analyze revenue streams by subscription type and region to inform marketing strategies.
- Provide actionable insights and recommendations to enhance customer satisfaction, optimize subscription offerings, and improve overall business performance.
  
**This project ultimately seeks to support data-driven decision-making for subscription management and marketing efforts.**
________
## Data Source
The dataset for this project was provided as part of a class assignment and contains simulated retail sales data for analysis purposes.
_______
## Dataset
- CustomerID: Unique identifier for each customer
- SubscriptionType:	Type of subscription (e.g., Basic, Premium, Standard)
- SubscriptionStart:	Date when the subscription started	
- SubscriptionEnd:	Date when the subscription ended 
- Cancelled:	Indicates if the subscription was cancelled (TRUE/FALSE)
- Revenue: Total revenue generated from the subscription
- Region:	Geographic region of the customer	
______
## Tools Used
- **Excel**: For Exploratory Data Analysis (EDA)
- **SQL**: For querying data
- **Power BI**: For visualization
___________
## Data Cleaning and Preparation
The data cleaning process is crucial to ensure the integrity and reliability of the analysis. 
![Screenshot (63)](https://github.com/user-attachments/assets/f8f31880-6da3-4310-a505-bbf38a343518)

#### Duplicate Removal

- Action: Identified and removed 41,213 duplicate records from the dataset, resulting in 33,787 unique values remaining.
- Reason: Duplicate entries can skew analysis results by inflating customer counts, revenue figures, and other metrics. Removing duplicates helps ensure that each customer is represented only once, leading to more accurate insights and conclusions.
#### Missing Values Check

- Action: Conducted a thorough check for missing values across all columns, confirming that there were no missing values present in the dataset.
- Reason: Missing values can lead to incomplete analyses and may result in biases or inaccuracies in the findings. Ensuring a complete dataset allows for a more robust and reliable analysis.
#### Adding Duration Column

- Action: Created a new column labeled "Duration" by calculating the difference between the subscription end date (SubscriptionEnd) and the subscription start date (SubscriptionStart).
- Reason: The Duration column provides critical insights into customer retention and subscription behavior. By quantifying the length of each subscription, we can analyze trends in customer loyalty, average subscription lengths, and cancellation patterns, which are essential for making informed business decisions.
 ![Screenshot (86)](https://github.com/user-attachments/assets/48ffaefd-1c00-4980-af5f-1089a4c52030)
_________
## Instructions
1. Excel:
- Calculate the average subscription duration
- identify the most popular subscription types.
- Create any other interesting reports.
2. SQL: Write queries to extract key insights based on the following questions. 
- retrieve the total number of customers from each region.
- find the most popular subscription type by the number of customers.
- find customers who canceled their subscription within 6 months.
- calculate the average subscription duration for all customers.
- find customers with subscriptions longer than 12 months.
- calculate total revenue by subscription type.
- find the top 3 regions by subscription cancellations.
- find the total number of active and canceled subscriptions.
3. Power BI:
- Build a Power BI dashboard that visualizes key customer segments, 
cancellations, and subscription trends. Include slicers for interactive analysis
________
# Data Analysis
____
## Excel
#### Calculate the average subscription duration: 
- Average Duration: 365.35 days
- Insight: The average subscription duration being around one year indicates that many customers remain subscribed for a significant period. This is a positive sign for customer loyalty and retention.
#### identify the most popular subscription types.
•  The Basic subscription is the clear favorite among customers, with 16,921 customers subscribing.
#### Create any other interesting reports.
![Screenshot (88)](https://github.com/user-attachments/assets/8b05aeeb-8b9a-4cf7-8c53-be7e72396f7a)

**Insights**: The data indicates that while the East region demonstrates excellent customer retention with no cancellations, the North, South, and West regions face challenges with high cancellation rates. The high number of cancellations in these regions may reflect underlying issues such as dissatisfaction with the service, pricing concerns, or better offerings from competitors. It is recommended to conduct further research, such as customer surveys or focus groups, to identify specific pain points and areas for improvement. Addressing these concerns can help improve retention rates and overall customer satisfaction across all regions.
____________
## SQL
#### retrieve the total number of customers from each region.
![Screenshot (66)](https://github.com/user-attachments/assets/f9b393e7-1a8a-4160-9578-14df45b4506d)
![Screenshot (90)](https://github.com/user-attachments/assets/2a5554e8-a9a9-47a4-b852-28f950f734f6)
- Insight: The analysis of customer counts by region reveals a relatively balanced customer distribution, with opportunities for growth and improvement in customer retention strategies across all areas. Focusing on understanding regional differences and enhancing customer satisfaction can lead to increased loyalty and a stronger overall customer base.
________
#### find the most popular subscription type by the number of customers.
![Screenshot (68)](https://github.com/user-attachments/assets/bdc26c00-9b14-4903-87b2-2e5d0181e94b)
________
#### find customers who canceled their subscription within 6 months.
![Screenshot (78)](https://github.com/user-attachments/assets/b267d29e-6ebe-4d5f-8e57-d1cf8d25b7a8)
![Screenshot (77)](https://github.com/user-attachments/assets/55454b66-cb93-4692-a2df-b375ec1c5052)
- Observation: During the analysis period, there were no cancellations reported among customers within the first six months of their subscription.
- Insight: This finding indicates a strong initial engagement and satisfaction level among new subscribers, suggesting that the onboarding process and early customer experience are effective. Customers who remain engaged during the first six months are likely to become loyal subscribers.
  _________
#### calculate the average subscription duration for all customers.
![Screenshot (70)](https://github.com/user-attachments/assets/e44eb9cf-69bd-405f-aebf-06fd616b8e42)
________
#### find customers with subscriptions longer than 12 months.
![Screenshot (79)](https://github.com/user-attachments/assets/d0bd4c36-dd14-41a7-b1ab-778d8bda6ed4)
-Observation: There were no reported cancellations among customers within the first twelve months of their subscription.
-Insight: This finding reflects a strong customer satisfaction and loyalty level during the initial year of service. The absence of cancellations indicates that the product or service effectively meets customer needs and expectations during this critical retention period
_________
#### calculate total revenue by subscription type.
![Screenshot (72)](https://github.com/user-attachments/assets/fe7bce55-f6c8-4d7c-81f2-dbd9c289030c)
![Screenshot (83)](https://github.com/user-attachments/assets/f96616e8-7bae-400a-ba41-abe1d6696f10)
- Insights: The Basic subscription type generates the highest revenue by a substantial margin, indicating it may be the most popular option among customers. The Premium and Standard types generate significantly less revenue, suggesting either fewer customers or lower pricing.
______
#### find the top 3 regions by subscription cancellations.
![Screenshot (73)](https://github.com/user-attachments/assets/daf462eb-0ef8-42a0-9db3-5e70b2897251)
![Screenshot (82)](https://github.com/user-attachments/assets/273ff754-253b-48e5-a662-f4694e329baf)
_________
#### find the total number of active and canceled subscriptions.
![Screenshot (74)](https://github.com/user-attachments/assets/94290e2e-8cd7-4976-95f4-aeca30b251b7)
![Screenshot (81)](https://github.com/user-attachments/assets/3ee5de22-ded5-41cb-8c75-54f755fc4a98)
- Insight: There are more active subscriptions than cancelled ones, indicating a positive customer retention trend. However, the cancellation rate is still significant, warranting investigation into customer dissatisfaction.
__________
## Key Findings
- Strong Retention in the East Region: The East region has 1,790,776 active subscriptions and zero cancellations. This indicates exceptional customer loyalty and satisfaction, suggesting that the offerings in this region are well-aligned with customer needs.
-High Cancellation Rates in North, South, and West Regions: The North region has a significant cancellation count of 1,079,291, with only 683,258 active subscriptions. Similarly, the South region shows 1,043,180 cancellations against 730,544 active subscriptions, and the West region has 1,076,340 cancellations with 709,008 active subscriptions.
In all three regions, the number of cancellations surpasses the number of active subscriptions, highlighting a potential crisis in customer retention.
- Customer Base Insights: The total customer base in the North (1,762,549), South (1,773,724), and West (1,785,348) regions is substantial; however, the high cancellation rates may indicate underlying dissatisfaction or competitive pressures.
- Potential Areas for Improvement: The high number of cancellations in the North, South, and West regions suggests an urgent need to investigate customer dissatisfaction. This could involve analyzing customer feedback, conducting surveys, and reviewing service offerings to identify pain points.
- Need for Targeted Retention Strategies: Given the variation in retention rates across regions, it may be beneficial to develop targeted retention strategies tailored to the specific challenges faced in the North, South, and West regions. These strategies could include enhanced customer support, loyalty programs, and service improvements.
- Market Opportunities: The low cancellation rate in the East region presents an opportunity to leverage this success in other regions. Best practices from the East could be analyzed and adapted for implementation in regions with higher cancellation rates.
### Recommendation
- Enhance Customer Engagement Strategies: Continue to build on the strong customer satisfaction observed during the first twelve months by implementing regular engagement strategies. This could include personalized communication, newsletters, and updates about new features or offerings to keep customers informed and engaged.
- Implement Loyalty Programs: Develop loyalty programs that reward customers for their continued subscription. Incentives such as discounts, exclusive content, or early access to new features can motivate customers to maintain their subscriptions beyond the initial period.
- Conduct Regular Customer Feedback Surveys: Periodically gather customer feedback to identify areas for improvement. Understanding customer needs and preferences can help tailor services and address any potential issues before they lead to cancellations.
- Strengthen Onboarding Processes: Since there were no cancellations within the first year, it’s crucial to maintain the effectiveness of the onboarding process. Provide comprehensive training and resources for new subscribers to ensure they fully understand how to utilize the product or service effectively.
- Monitor Customer Behavior: Use data analytics to track customer engagement and behavior patterns. Identifying trends can help pinpoint at-risk customers and allow for timely interventions to address any issues that may arise before they lead to cancellations.
- Offer Flexible Subscription Plans: Consider introducing more flexible subscription options, such as monthly payment plans or tiered pricing models. This can attract a broader audience and make it easier for customers to find a subscription type that fits their needs and budget.
- Personalize Customer Experience: Leverage customer data to create personalized experiences. Tailoring recommendations, communication, and support based on individual customer preferences can enhance satisfaction and loyalty.
- Strengthen Support Services: Ensure that customer support is readily available and responsive. Providing multiple channels for support (e.g., chat, email, phone) can help address customer issues quickly, enhancing their overall experience.
- Utilize Case Studies and Testimonials: Share success stories and testimonials from satisfied customers to build trust and encourage new subscribers. Highlighting positive experiences can help reinforce the value of the service and attract potential customers.
- Focus on Continuous Improvement: Regularly review and update service offerings based on customer feedback and market trends. Staying responsive to changes in customer needs and preferences will help maintain high satisfaction levels and reduce the likelihood of cancellations.

### Conclusion
The analysis of subscription data has provided valuable insights into customer behavior, preferences, and retention trends. Key findings indicate that the Basic subscription type is the most popular among customers, significantly outpacing Premium and Standard subscriptions. The absence of cancellations within the first twelve months reflects strong customer satisfaction and effective onboarding processes, suggesting that customers find value in their subscriptions during this critical period.

Despite the overall positive trends in customer retention, the analysis also revealed areas for improvement. The presence of cancellations in certain regions highlights the need for targeted strategies to enhance customer engagement and satisfaction. Furthermore, monitoring customer behavior and gathering feedback will be essential in identifying potential issues early on.

By implementing the recommended strategies, such as enhancing customer engagement, establishing loyalty programs, and personalizing experiences, the organization can strengthen its relationship with subscribers and improve retention rates. Continuous improvement based on customer feedback and market trends will ensure that the service remains relevant and valuable to customers.

In conclusion, while the current subscription landscape shows promise with high customer retention and satisfaction, there are opportunities to further enhance loyalty and growth. Fostering a customer-centric approach will be crucial in maintaining and building upon these positive trends, ultimately driving the organization towards sustained success in a competitive market.
