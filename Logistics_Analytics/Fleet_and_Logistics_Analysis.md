# Logistics Operations & Performance Analytics
## Project Overview
This project focuses on analysing logistics operations and business performance using Microsoft Power BI. It explores key operational and financial activities within a logistics business, providing insights into revenue generation, driver performance, route efficiency, fleet utilisation, fuel consumption, maintenance costs, customer activity, and safety performance.

Using a structured analytical approach, the project transforms raw logistics data into interactive dashboards and actionable business insights to help management understand operational performance, identify inefficiencies, monitor costs, and uncover opportunities for business growth.

The analysis is organised into five interactive dashboard pages, each addressing a critical area of the business and supporting data-driven decision-making.

The ultimate goal is to provide management with a clear understanding of how the business is performing, what drives its performance, where improvements are needed, and what strategic actions can strengthen operational efficiency and sustainable business growth.
## Business Problem
The logistics industry operates in a highly competitive environment where profitability and service quality depend on efficient fleet management, cost control, timely deliveries, and effective resource utilisation.

However, without proper data analysis, management may struggle to identify operational inefficiencies, understand the factors driving business performance, control rising operating costs, and recognise areas requiring improvement.

This project addresses the need for a centralised analytical solution that enables management to evaluate logistics operations, monitor key performance indicators, identify performance gaps, and make informed strategic decisions.

The analysis seeks to answer the following business questions:

1. Business Performance: How is the business performing in terms of revenue, estimated operating profit, and overall operational efficiency?

2. Driver Performance: Which drivers demonstrate the strongest performance in mileage, fuel efficiency, and on-time delivery?

3. Route Performance: Which routes contribute most to business revenue, and where are operational improvements needed?

4. Fleet Utilisation: How efficiently are trucks being utilised across logistics operations?

5. Fuel & Maintenance Costs: What are the major drivers of fuel consumption, maintenance expenditure, and vehicle downtime?

6. Customer Performance: Which customers and freight types contribute most to business revenue?

7. Safety Performance: What are the most common safety incidents, and how many are preventable?

8. Management Priorities: Where should management focus to reduce operating costs, improve service delivery, strengthen operational efficiency, and support sustainable business growth?
## Project Objectives

The primary objective of this project is to develop an interactive Power BI analytics solution that provides comprehensive insights into logistics operations and supports effective, data-driven management decisions.

The specific objectives are to:

1. Analyse overall business performance using revenue, estimated operating profit, and operational performance indicators.

2. Evaluate driver performance through mileage, fuel efficiency, and on-time delivery metrics.

3. Assess route performance to identify revenue-generating routes and potential operational inefficiencies.

4. Monitor fleet utilization and evaluate truck performance.

5. Analyse fuel consumption, maintenance expenditure, and vehicle downtime to identify opportunities for cost reduction.

6. Evaluate customer revenue contributions and identify high-performing freight types.

7. Examine safety incidents and assess the proportion of preventable incidents.

8. Develop dynamic insights and actionable recommendations to improve operational efficiency, control costs, enhance service delivery, and support sustainable business growth.

## Tools & Technologies
The following tools and technologies were used throughout the project:

* Microsoft Power BI Desktop: Used to develop interactive dashboards, create data visualizations, analyse business performance, and communicate actionable insights.

* Power Query: Used for data cleaning, transformation, data quality checks, and preparation before loading the data into Power BI.

* DAX (Data Analysis Expressions): Used to create calculated measures, key performance indicators, dynamic insights, and management recommendations.

* Power BI Data Modelling: Used to establish relationships between datasets and organize data for effective analysis.

* Microsoft Excel: Used as the source format for the logistics dataset.

* GitHub: Used for project documentation, version control, and portfolio presentation.

## Dataset Description

The project uses a logistics operations dataset provided in Microsoft Excel format, consisting of 14 interconnected worksheets covering different aspects of logistics and fleet management.

The dataset contains operational, financial, customer, driver, vehicle, maintenance, fuel, delivery, and safety records.

### Dataset Tables

| Table | Records |
|---|---:|
| Customer | 200 |
| Drivers | 150 |
| Trucks | 120 |
| Trailers | 180 |
| Facilities | 50 |
| Routes | 58 |
| Loads | 85,410 |
| Trips | 85,410 |
| Fuel Purchases | 196,442 |
| Maintenance Record | 2,922 |
| Delivery Events | 170,820 |
| Safety Incidents | 170 |
| Driver Monthly Metrics | 4,466 |
| Truck Utilization Metrics | 3,314 |

The dataset provides a broad view of logistics activities, allowing the analysis to examine relationships between customers, drivers, trucks, routes, deliveries, operating costs, and safety performance.

The different tables were used to support a comprehensive evaluation of business performance and operational efficiency.

## Data Cleaning & Preparation

Data cleaning and preparation were performed using **Power Query in Power BI** to improve data quality, consistency, and reliability before analysis.

The following activities were carried out:

1. **Data Inspection:** Examined all 14 worksheets to understand their structure, fields, data types, and overall data quality.
2. **Removal of Empty Rows:** Identified and removed completely blank rows from relevant tables to eliminate unnecessary records.
3. **Duplicate Checks:** Examined key identifiers and duplicate records to identify and remove exact duplicate entries where necessary.
4. **Data Type Correction:** Reviewed and corrected data types to ensure dates, numerical values, text fields, and other columns were appropriately formatted.
5. **Missing Value Assessment:** Identified blank and null values, distinguishing legitimate missing information from incomplete records.
6. **Data Validation:** Checked key identifiers and important fields to improve data consistency and reliability across the tables.
7. **Column Review:** Reviewed column names and removed unnecessary empty columns where applicable.

The cleaned datasets were then loaded into Power BI for data modelling, DAX calculations, and dashboard development.

## Data Modelling

Data modelling was performed in Power BI to establish relationships between the 14 tables and enable integrated analysis across the logistics business.

The following activities were carried out:

1. **Relationship Management:** Reviewed and validated relationships between relevant tables using common identifiers such as customer IDs, driver IDs, truck IDs, route IDs, and trip IDs.
2. **Table Relationships:** Examined relationship cardinality and filter direction to support accurate data aggregation and filtering.
3. **Date Table Creation:** Created a dedicated Date Table using the load date to support time-based analysis, including monthly revenue trends.
4. **Inactive Relationships:** Reviewed inactive relationships and retained them where appropriate, activating specific relationships within DAX calculations when required.
5. **Model Validation:** Checked relationships to ensure that data from different tables could be used together for meaningful business analysis.

The resulting data model provides the foundation for calculating performance metrics, analysing operational activities, and developing interactive dashboards.

## Key Metrics & DAX Measures

DAX (Data Analysis Expressions) was used in Power BI to develop calculated measures, key performance indicators (KPIs), and dynamic business insights.

The following metrics were developed and used across the five dashboard pages:

### 1. Business Performance
- Total Revenue
- Estimated Operating Profit
- Total Loads
- Revenue per Load
- On-Time Delivery Rate

### 2. Driver & Route Performance
- Total Drivers
- Average MPG
- Total Miles Driven
- On-Time Events
- Total Recorded Delivery Events
- On-Time Event Rate

### 3. Fleet, Fuel & Maintenance
- Total Trucks
- Total Fuel Consumed
- Total Fuel Cost
- Total Maintenance Cost
- Total Downtime Hours
- Fuel Cost per Mile
- Maintenance Cost per Truck
- Average Downtime per Maintenance Record

### 4. Customer & Safety Performance
- Total Customers
- Total Safety Incidents
- Preventable Incidents
- Preventable Incident Rate

### 5. Management & Recommendations
- Revenue per Load
- Fuel Cost per Mile
- Maintenance Cost per Truck
- Average Downtime per Maintenance Record

### Dynamic Business Insights

In addition to the numerical measures, dynamic DAX calculations were developed to generate management insights and recommendations based on the selected data and dashboard filters.

These insights help highlight business performance, identify operational strengths and weaknesses, and guide management towards areas requiring attention.

## Dashboard Pages & Features

The Power BI report consists of five interactive dashboard pages, each designed to address a specific area of logistics performance and support management decision-making.

### 1. Executive Overview
Provides a high-level summary of overall business performance.

**Key Features:**
- Total Revenue
- Estimated Operating Profit
- Total Loads
- On-Time Delivery Rate
- Monthly Revenue Trend
- Revenue by Route
- Revenue by Load Type
- Dynamic Executive Overview Insight

### 2. Driver & Route Performance
Evaluates driver productivity, fuel efficiency, mileage, and delivery performance.

**Key Features:**
- Total Drivers
- Average MPG
- Total Miles Driven
- Top 10 Drivers by Mileage
- Average MPG by Driver
- On-Time Delivery Rate by Driver
- Dynamic Driver & Route Performance Insight

### 3. Fleet, Fuel & Maintenance
Examines fleet operations, fuel consumption, maintenance expenditure, and vehicle downtime.

**Key Features:**
- Total Trucks
- Total Fuel Consumed
- Total Maintenance Cost
- Total Downtime Hours
- Fuel Consumption by Truck
- Maintenance Cost by Maintenance Type
- Downtime Hours by Maintenance Type
- Fuel Consumption Trend

### 4. Customer & Safety Analysis
Explores customer revenue contributions, freight patterns, and safety performance.

**Key Features:**
- Total Customers
- Total Safety Incidents
- Preventable Incidents
- Preventable Incident Rate
- Top 10 Customers by Revenue
- Safety Incidents by Incident Type
- Preventable vs Non-Preventable Incidents
- Revenue by Freight Type
- Dynamic Customer & Safety Insight

### 5. Management & Recommendations
Provides management with performance indicators and insights to support strategic business decisions.

**Key Features:**
- Revenue per Load
- Fuel Cost per Mile
- Maintenance Cost per Truck
- Average Downtime per Maintenance Record
- Operating Cost Breakdown
- Maintenance Cost by Truck
- Revenue per Load by Load Type
- Revenue vs Estimated Operating Profit by Load Type
- Dynamic Management Recommendations

### Interactive Features
- Interactive slicers for exploring business performance across relevant dimensions.
- Dynamic DAX insights that respond to report filters.
- Consistent visual formatting and dashboard navigation.
- KPI cards and charts designed to communicate important business findings.

## Key Business Insights

The analysis revealed ten important findings across the company's logistics operations:

### Revenue & Business Performance

1. **Revenue and Profitability:** The business generated approximately $298.62 million in revenue from 85,410 loads, with an estimated operating profit of $197.30 million after recorded fuel and maintenance costs. This indicates a positive operating performance based on the costs included in the analysis.

2. **Revenue Trends and Load Types:** The annual revenue trend shows that July 2022 recorded the highest revenue within the reporting period. Of the two load types analysed, Refrigerated generated more revenue than Dry Van, making it the leading revenue contributor.

### Driver & Route Performance

3. **Driver Productivity and Fuel Efficiency:** Driver Productivity and Fuel Efficiency: The business recorded approximately 122.16 million miles across 150 drivers, with an average fuel efficiency of 6.50 MPG. Driver DRV00051 recorded the highest total mileage, highlighting differences in driver workloads and mileage contributions.

4. **On-Time Delivery Performance:** The Executive Overview recorded an overall on-time delivery rate of 33.4%. The driver performance dashboard further compares delivery rates across drivers, providing management with an opportunity to identify performance gaps and improve delivery reliability.

### Fleet, Fuel & Maintenance

5. **Fuel Consumption and Operating Costs:** The fleet consumed approximately 8.24 million gallons of fuel, with fuel expenditure reaching $95.59 million. Fuel accounted for approximately 94.34% of the combined fuel and maintenance costs, making it the largest recorded operating cost and an important area for cost control initiatives.

6. **Maintenance and Vehicle Downtime:** The business recorded approximately $5.73 million in maintenance expenditure and 72,230 hours of vehicle downtime across 120 trucks. Downtime occurred across different maintenance categories, highlighting the importance of preventive maintenance planning and effective vehicle availability management.

### Customer & Safety Performance

7. **Customer and Freight Contributions:** The business generated approximately $298.62 million in revenue across 200 customers. Automotive was the leading freight type by revenue, highlighting its importance to the company's overall revenue contribution and future customer growth strategy.

8. **Preventable Safety Incidents:** A total of 170 safety incidents were recorded, with 64 (37.6%) classified as preventable and 106 (62.4%) as non-preventable. Management should strengthen safety procedures, driver training, and incident prevention measures to reduce avoidable incidents.

### Management & Financial Performance

9. **Cost Efficiency:** The business generated an average revenue of $3,496.33 per load, while fuel costs averaged $0.78 per mile. Fuel accounted for 94.34% of the combined fuel and maintenance expenditure, compared with 5.66% for maintenance. This highlights the importance of monitoring fuel consumption and improving operational cost efficiency.

10. **Truck Maintenance Costs:** Average maintenance expenditure was $47,754.78 per truck, with an average downtime of 24.7 hours per maintenance record. Truck TRK000003 recorded the highest maintenance cost. Management should review its maintenance history, strengthen preventive maintenance planning, and monitor vehicles with high maintenance expenditure.

## Management Recommendations

Based on the findings from the analysis, the following recommendations are proposed to improve logistics operations, strengthen financial performance, and support sustainable business growth.

1. **Improve Fuel Cost Management:** Since fuel accounts for approximately 94.34% of the combined fuel and maintenance expenditure, management should monitor fuel consumption, improve route planning, reduce unnecessary idling, and encourage fuel-efficient driving practices.

2. **Strengthen Delivery Performance:** With an overall on-time delivery rate of 33.2%, management should investigate the causes of delivery delays, monitor driver performance, review route efficiency, and improve delivery scheduling.

3. **Implement Preventive Fleet Maintenance:** Management should establish consistent preventive maintenance schedules, monitor vehicles with high maintenance expenditure, and investigate trucks with excessive downtime to improve fleet availability and reduce repair costs.

4. **Improve Driver Productivity and Safety:** Regular driver performance reviews, training programmes, and safety awareness initiatives should be introduced to improve fuel efficiency, delivery reliability, and reduce preventable safety incidents.

5. **Strengthen Customer and Revenue Growth:** Management should maintain strong relationships with major revenue-generating customers, particularly within the Automotive freight segment, while exploring opportunities to attract new customers and expand other freight categories.

6. **Monitor Financial and Operational Performance:** Management should regularly track revenue per load, estimated operating profit, fuel cost per mile, maintenance expenditure, and vehicle downtime to identify inefficiencies and make informed operational decisions.

7. **Promote Data Driven Decision-Making:** Management should use the interactive Power BI dashboards for regular performance monitoring, identifying emerging operational challenges, evaluating business growth opportunities, and measuring the impact of improvement strategies.

## Project Outcomes

The project successfully transformed raw logistics data into an interactive Power BI reporting solution that provides visibility into the company's operational and financial performance.

Key outcomes include:

- Developed five interactive dashboard pages covering executive performance, driver and route efficiency, fleet and maintenance, customer and safety, and management recommendations.
- Consolidated data from 14 related tables into a structured analytical data model.
- Created DAX measures to evaluate revenue, estimated operating profit, delivery performance, fuel consumption, maintenance expenditure, and other key operational metrics.
- Identified major cost drivers, revenue contributors, driver performance patterns, and safety concerns.
- Implemented interactive slicers, dynamic insights, tooltips, and report navigation to support business analysis.
- Provided management with practical recommendations for improving cost efficiency, fleet utilisation, delivery reliability, customer growth, and operational safety.

Overall, the project demonstrates how Power BI can support data driven decision making by turning complex operational data into meaningful business insights.

## Conclusion

The Logistics Operations & Performance Analytics project demonstrates the value of data analytics in understanding and improving logistics business performance.

By analysing revenue, profitability, driver productivity, route efficiency, fuel consumption, fleet maintenance, customer activity, and safety performance, the project provides a comprehensive view of the company's operations.

The interactive Power BI dashboards transform raw operational data into meaningful insights, helping management identify performance gaps, monitor key metrics, control operating costs, and recognise opportunities for business growth.

Ultimately, this project highlights how data driven decision making can support improved operational efficiency, stronger financial performance, safer logistics operations, and sustainable business growth.

## Author

**Sodiq Olamilekan Jimoh** 👨‍💻

- **Qualification:** B.Sc. Political Science (Hons)
- **Institution:** University of Ibadan
- **Certification:** IFEXA Certified Data Analyst
- **Area of Interest:** Data Analytics, Business Intelligence, Data Visualisation, and Data Driven Decision Making.

This project reflects my commitment to using data analytics and business intelligence tools to solve real world business problems and support informed decision making.

**Connect with me on GitHub:** (https://github.com/Olami8)
