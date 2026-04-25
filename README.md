
# Consumer Issue Intelligence Hub

## Tools & Technologies 
Microsoft-Power BI | Excel

## 👥 Team Members
1)	Mamdouh Mansour Mamdouh Abdelrazek
2)	Malak Ahmed Abdel Hamid Ahmed
3)	Ghaidaa Rafat Mahmoud Ismail
4)	Ahmed Snousy Jalal Snousy
5)	Shrouq Mohamed Aboul Fotouh Saber

## 📌 Project Overview
Consumer-Issue-Intelligence-Hub is a high-performance analytics platform that transforms 62,000+ raw consumer complaints into strategic insights. Leveraging a specialized Star Schema and advanced DAX modeling, it evaluates corporate responsiveness and service bottlenecks across 200+ issue categories. The project provides a granular, 51-state geographical analysis integrated with a custom Time-Intelligence framework for trend forecasting. By bridging the gap between raw data and actionable intelligence, it empowers stakeholders to optimize resolution workflows and enhance overall customer experience.
## 🎯 Problem Statement
Organizations often struggle to process massive volumes of fragmented consumer complaint data, leading to slow response times and unidentified service bottlenecks. Without a structured analytical framework, it is nearly impossible to track corporate accountability or detect geographic and product-specific trends in real-time. Consumer-Issue-Intelligence-Hub addresses this by transforming 62,000+ unstructured records into a centralized intelligence system, enabling stakeholders to pinpoint inefficiencies and improve the speed and quality of complaint resolution.
## ⚙️ The ETL Journey:
Initial Format: Data was sourced from large-scale CSV files containing over 62,000 rows.Data Type Calibration: Defined correct data types for dates, integers, and text to prevent calculation errors.Handling Nulls & Noise: Cleaned missing values in critical columns like Consumer Response and Sub-issue to ensure 100% data consistency.Standardization: Unified naming conventions for states and product categories for accurate filtering.2. Data Transformation (The Engineering Stage)Normalization: Deconstructed the flat CSV file into multiple Dimension Tables (Products, States, Issues) to eliminate data redundancy.Feature Engineering: * Calculated Processing Days by creating a custom column to measure the gap between Date received and Date submitted.Generated a custom DAX Calendar Table to enable advanced Time-Intelligence capabilities.Key Mapping: Assigned unique ID keys to each dimension to establish a robust relational framework.3. Data Loading & Modeling (The Star Schema)Schema Design: Successfully migrated the cleaned data into a Star Schema architecture.Relationship Management: Established One-to-Many relationships between dimensions and the central Fact Table.Efficiency: This transformation reduced the file size and significantly increased the dashboard’s cross-filtering speed.
<img width="1430" height="704" alt="image" src="https://github.com/user-attachments/assets/2c918fbc-643f-42be-a2d2-cc4721b3a217" />

## 📊 Dashboard Previews 
[Coming Soon]
## 📈 Key Performance Indicators (KPIs)
To drive actionable insights, the following metrics were defined to evaluate corporate performance and consumer satisfaction:

Total Complaints Volume: Tracks the overall scale of consumer issues, providing a baseline for identifying peak periods and high-risk product categories.

Response Efficiency (Avg. Processing Days): Measures the average time taken by companies to process a complaint, serving as a primary indicator of operational speed.

Timely Response Rate (%): Evaluates corporate accountability by calculating the percentage of complaints resolved within the officially mandated timeframe.

Resolution Quality (Consumer Response): Analyzes the final outcome of the issue (e.g., Monetary relief vs. Explanation) to determine the effectiveness of the resolution process.

Market Saturation Index: Uses geographical and product dimensions to identify which states or financial sectors are experiencing disproportionate levels of consumer friction.
## 
Created as a Final Graduation project for the Microsoft Power BI Specialist track at Egypt Digital Pioneers Initiative.
