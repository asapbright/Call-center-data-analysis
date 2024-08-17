Call Center Data Analysis
This project involves the analysis of a call center dataset to assess customer sentiment, satisfaction, and operational efficiency. The dataset contains information about customer interactions with a call center, including sentiment, CSAT scores, call duration, reason for the call, and more.

Project Overview
The goal of this project is to extract meaningful insights from the call center data, identify patterns, and make recommendations for improving customer service performance. The analysis covers aspects such as sentiment distribution, customer satisfaction, and operational metrics.

Key Objectives:
Sentiment Distribution Analysis: Understanding the overall distribution of customer sentiments (e.g., Positive, Neutral, Negative).
Customer Satisfaction Analysis: Evaluating CSAT scores and their correlation with other factors like call duration and channel.
Operational Efficiency: Assessing SLA adherence and identifying areas for improvement in service delivery.
Channel Performance: Comparing performance across different communication channels (Call-Center, Chatbot, Email, Web).
Geographical Insights: Analyzing how customer experiences vary by location (city/state).
Dataset
The dataset used in this project is a CSV file containing the following columns:

id: Unique identifier for each interaction.
customer_name: Name of the customer.
sentiment: Customer sentiment (e.g., Very Positive, Positive, Neutral, Negative, Very Negative).
csat_score: Customer Satisfaction score (scale of 1-10).
call_timestamp: Date of the interaction.
reason: The reason for the customer's call (e.g., Billing Question, Payments).
city: City where the customer is located.
state: State where the customer is located.
channel: Channel used for the interaction (e.g., Call-Center, Chatbot, Email, Web).
response_time: Whether the response time was within SLA (Service Level Agreement).
call_duration: Duration of the call in minutes.
call_center: The call center handling the interaction (e.g., Los Angeles/CA).

Analysis Steps
Data Cleaning:
Address missing values in the csat_score column.
Ensure consistency in the call_center column by splitting it into city_call_center and state_call_center.
Exploratory Data Analysis (EDA):
Calculate the distribution of customer sentiments.
Analyze the correlation between CSAT scores and other variables like call duration and channel.
Visualize the distribution of calls by channel, sentiment, and location.
Operational Insights:
Evaluate SLA adherence and identify trends in response times.
Compare the performance of different call centers based on key metrics.
Recommendations:
Based on the analysis, provide actionable recommendations to improve customer satisfaction and operational efficiency.

Results
Sentiment Analysis: The analysis revealed that a significant portion of customer interactions resulted in negative sentiment, indicating potential areas for service improvement.
CSAT Scores: The average CSAT score was found to be X (if applicable), with certain channels and call centers performing better than others.
Operational Efficiency: The majority of interactions were handled within SLA, but certain areas (e.g., specific call centers or reasons for calls) showed room for improvement.

Tools Used
Excel: For data cleaning, exploratory analysis, and visualization.
GitHub: For version control and sharing the project.
How to Use This Repository
Clone the repository:
bash

Copier
git clone https://github.com/asapbright/call-center-analysis.git
Open the data file:
The main dataset is provided as Call Center.csv.
Review the analysis:
Analysis is provided in the form of Excel files with PivotTables, charts, and summary statistics.
If Python scripts are included, you can run them to reproduce the analysis.
Conclusion
This project showcases the application of data analysis techniques to real-world call center data, uncovering insights that can drive improvements in customer service. The findings and recommendations are intended to help call center managers enhance customer satisfaction and operational performance.

Contact
For any questions or feedback, feel free to reach out to me at brightsegla@proton.me.

