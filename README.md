# AdPerformace
Tracking the Performance of Ad in Facebook and Instagram for better conversion.

1.	Project Title:
              Ad Performance Tracking–This project analyzes a performance tracking report for campaigns running in Facebook and Instagram. This report will provide visibility into campaign, reach, engagement, conversion and budget utilization. This enables the marketing team to identify the effective platforms, tracks Return on Investment, optimize budget allocations and audience engagement patterns.

2.	Short Description:
                      Data is imported from Excel to Power Bi. DAX functions likes DATEVALUE, HOUR, CALENDAR, MIN, MAX, WEEKDAY, WEEKNUM, SELECTEDVALUE, COUNTROWS, FILTER, DIVIDE, SUM, and AVERAGE are used for creating measures. Data modelling- Create relationship between table. Data Visualization - Creating dashboard using different charts, slicers and generating insights from charts.

3.	Data Source:

  •	The data in this table represents tracking of Meta Ad Performance. It includes Key Performance Indicator such as Impressions - how often ads are seen, Clicks – engagement with ads, Purchases – Conversions, Efficiency Metrics – Cost per Measure, Cost per Click, Click through Rate, Return on Ad spent.

  •	ad_events – captures every event between a user and ad. It helps to analyze when and how users interacts with ads. This is the fact table in the model because all KPIs are derived from events.

  •	ads - stores details of each ad creative. It defines targeting criteria and which campaign ad belongs to. Platform level & Creative type level analysis (FB Image Ads vs. Instagram Video Ads).

  •	campaigns – contain campaign level information such as budget, duration  strategy and used to calculate cost based KPIs such as Cost per Measure, Cost per Click, Return on Ad spent.

  •	Users – stores user demographic and interest details of users engaging with ads. It helps measure audience segmentation (gender,age,country,location,interests) and targeting efficiency(ad reaches right audience)           

4.	Dashboard in Power BI:

   •	Donut Chart - It visualize performance split by target gender and identifies which gender segment contributes most to the selected metric.
   
   •	Card – It displays Impressions, Clicks, Shares, Comments, Purchases, Engagements, Click Through rate, Purchase Rate, Engagement Rate, Total Budget, Average Total budget and Conversion Rate.
   
   •	Bar Chart- It visualize engagement across age groups defined in table and highlights which age group is most responsive to campaigns.
   
   •	Filled Map- It displays performance by country from users table and provides geographic view of campaign & engagement.
   
   •	Heat Map- It will plot performance at monthly level from ad events table timestamp fields and detect seasonal trends, peak ad months, and low activity periods.
   
   •	Stacked Column Chart- It display weekly performance trends by comparing ad type contributions over a week from ad events table in week number fields.
   
   •	 Area Chart- It shows the hour of the activity from ad events table in time of day field so that understanding the patterns through day.
   
   •	Matrix Chart- It compares performance across ad types by selected metrics & breakdown through platforms. Rows  Ad types, Columns  Platforms, Values Selected Metrics (Impressions, Clicks, Click through Rate,     Purchase Rate, Engagement Rate and Conversion Rate).

5.	Business Recommendations: 

   	Strong Awareness & Engagement but Low Purchase funnel. It needs better conversion strategy.
   	Target Audience: Primarily, Females aged 22–30 in the United States and India. Run campaigns in specific country for better conversions.
   	Timing: Schedule Ads during peak engagement hours ( i.e. ) Afternoon and Evening.
   	Best Ad Formats: Image Ads for better reach. Video & stories Ads for better conversions.
   	Budget Optimization: Shift more spend to High Performing Geographies and ad formats.
   	Action: Improve landing pages, give offers and retargeting campaigns.

Ad Performance Dashboard:  https://github.com/Subha-S-Techy/AdPerformace/blob/main/Ad%20Performance.jpg
