Marketing Analytics Dashboard with SQL and Sentiment Analysis
Overview
This repository contains a comprehensive marketing analytics solution developed for ShopEasy, an online retail business. The project aims to identify the causes of declining customer engagement and conversion rates and provide actionable insights through data analysis, SQL queries, sentiment analysis, and a Power BI dashboard.

Project Components
1. SQL Data Operations
Files: [SQL Queries]
Tools: Microsoft SQL Server
The SQL scripts included in this repository were used to:
Clean and structure the raw marketing data.
Perform operations such as aggregations, joins, and filtering to extract relevant insights.
Address issues with the data, such as missing values and duplicate records.
Post the SQL operations, the clean and optimized data was connected to Power BI through an SQL connection to visualize and further analyze the data.
2. Power BI Dashboard
File: Marketing Analytics_Dashboard.pbix
Tool: Power BI
The dashboard built in Power BI offers interactive insights on key performance indicators (KPIs) such as:
Conversion Rates: The percentage of website visitors who make a purchase.
Customer Engagement: Interactions such as clicks, likes, and comments on marketing content.
Average Order Value (AOV): The average amount spent by a customer per transaction.
Customer Feedback Scores: Analyzed from customer reviews and comments.
This dashboard answers critical business questions such as:
What factors are contributing to the drop in conversion rates?
Which types of marketing content lead to the highest engagement?
How can we improve customer feedback and overall satisfaction?
3. Sentiment Analysis of Customer Reviews
File: MarketingAnalytics_SentimentAnalysis.ipynb
Tool: Python, NLTK Library
Using Python and the Natural Language Toolkit (NLTK), sentiment analysis was performed on customer reviews to categorize feedback as positive, negative, or neutral.
The results were integrated into the Power BI dashboard to provide deeper insights into customer opinions and guide improvements in marketing and product strategies.
Key Insights from the Project
Conversion Funnel Drop-off: The SQL and Power BI analysis revealed critical drop-off points in the conversion funnel where customers abandoned their shopping journey. Recommendations were made to optimize these stages.
Content Engagement: By analyzing different marketing content types, it was discovered that visual and interactive content had the highest engagement rates.
Sentiment Feedback: The sentiment analysis indicated recurring themes in customer dissatisfaction, which were primarily related to product availability and website user experience. These insights informed changes in product listings and site navigation.
Files in this Repository
Power BI Dashboard: Marketing Analytics_Dashboard.pbix
SQL Queries:
SQL_Marketing.sql: Contains the main SQL queries used for data operations.
Additional SQL files (SQLQuery3.sql, SQLQuery4.sql, etc.) contain specific queries for filtering, aggregating, and cleaning the marketing data.
Python Sentiment Analysis Notebook: MarketingAnalytics_SentimentAnalysis.ipynb: The Jupyter notebook containing the sentiment analysis code using the NLTK library.
How to Run This Project
SQL Queries:

Load the SQL files into Microsoft SQL Server and run them to generate the necessary tables and outputs for Power BI integration.
Power BI Dashboard:

Open the .pbix file in Power BI Desktop.
Ensure that the SQL connection is established to fetch the data from your SQL server. Adjust the connection string as necessary.
Sentiment Analysis:

Install the required Python libraries (nltk, pandas, etc.) using the following command:
bash
Copy code
pip install -r requirements.txt
Run the Jupyter notebook MarketingAnalytics_SentimentAnalysis.ipynb to perform sentiment analysis on the provided customer review data.
Conclusion
The project successfully addresses the key business problems faced by ShopEasy by providing a thorough analysis of marketing efforts and customer sentiment. The SQL operations, sentiment analysis, and Power BI dashboard together form a cohesive solution for enhancing customer engagement, improving conversion rates, and making data-driven marketing decisions.


