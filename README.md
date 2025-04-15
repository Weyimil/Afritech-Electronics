# Afritech-Electronics
AfriTech Electronics faces brand reputation issues due to negative sentiment and product recalls. This project uses PostgreSQL and Power BI to monitor social media and improve customer response.

# Project Title:
Enhancing Brand Reputation through Social Media Sentiment Analysis at AfriTech Electronics Ltd.

# Company Overview: 
AfriTech Electronics Ltd. is a U.S.-based global player in the consumer electronics market, known for its innovation in smartphones, tablets, and wearable 
tech. With 200 employees and $2 million in revenue in 2022, the company has built a strong brand through quality and technology integration.

## Current Challenge: 

Despite past successes, AfriTech is facing a decline in brand reputation due to negative customer reviews, product recalls, and social media backlash. 
These issues are impacting customer trust, satisfaction, and market share.

## Problem Statement
AfriTech Electronics Ltd. is facing a reputational crisis marked by a rise in negative social media sentiment, increased customer complaints, and damaging 
media coverage of product recalls. These issues are eroding customer trust and allowing competitors to gain market share. The company lacks an effective 
system to monitor, analyze, and respond to these challenges in real time. A robust solution is needed to track brand sentiment, detect early signs of crises, 
and improve customer engagement using data-driven insights.


## Purpose of the Project:
The purpose of this project is to leverage social media sentiment analysis to monitor, understand, and improve AfriTech Electronics Ltd's brand reputation by
addressing customer concerns, identifying early warning signs of public relations issues, and enabling data-driven decision-making.

## Project Objectives:
Protect and enhance brand reputation.

Improve customer satisfaction by resolving complaints swiftly.

Use social media monitoring to gain insights and prevent crises.

Leverage data for smarter marketing and communication strategies.

## Data Source:
Social media platforms 
- **Twitter**
- **Facebook**
- **Instagram**
- **Tiktok**

Proposed Tech Stack:
- **PostgreSQL:** For storing, managing, and querying structured data related to customer interactions, sentiment scores, and complaint tracking.
- **Power BI:** For data visualization and sentiment analysis.
- **PowerPoint:** For presenting findings, insights, and strategic recommendations to stakeholders in a clear and engaging manner.

# Exploratory Data Analysis (EDA) and Cleaning Process Overview

1. **Data Ingestion & Staging**  
   I began by creating a **staging area** to efficiently import the raw data into **PostgreSQL**, establishing a pipeline to support data transformation and analysis.

![Image](https://github.com/user-attachments/assets/aca6c33d-2574-4711-a943-1fa8b8b9e842)

![Image](https://github.com/user-attachments/assets/470a648f-d531-47e4-8daa-c8b26446bb97)

3. **Data Modeling**
   The data was structured into fact and dimension tables, resulting in three key tables:
   - **Customer Table**
   - **Social Media Table**
   - **Transactions Table**
   After modeling the data, I established relationships between the tables to enable efficient querying and analysis.

4. **Data Cleaning**  
   I cleaned the dataset by removing **duplicate records**, handling **missing values**, and eliminating **irrelevant or empty columns** to ensure data quality and consistency.

5. **Exploratory Data Analysis (EDA)**  
   With a clean and structured dataset, I conducted a thorough EDA focused on identifying key performance indicators (KPIs), including:  
   - **Sentiment Scores**  
   - **Customer Engagement Metrics**  
   - **Product Recalls**  
   - **Trends in Negative Sentiments**  
   - And other relevant insights for deeper business understanding.


### **Project Workflow Summary**

After completing my **Exploratory Data Analysis (EDA)** in Postgresql, I proceeded with the following structured workflow to prepare data-driven insights and visualizations for higher management:

---

### **1. Database Integration**
- Connected **Power BI** directly to the **PostgreSQL** database using built-in connectors.
- Ensured secure authentication and optimized the connection for real-time data updates.
- Selected relevant tables and views required for reporting and KPI tracking.

---

### **2. Data Preparation & Modeling**
- Performed **data transformation and cleaning** using Power Query Editor.
- Created **relationships between tables** to enable seamless cross-filtering and interaction.
- Established **calculated columns and measures** using DAX for dynamic insights and aggregated KPIs.

---

### **3. KPI Development**
- Identified key business metrics based on stakeholder priorities, such as:
  - Total Sales
  - Revenue by Customer Segment
  - Product Category Performance
  - Regional Sales Distribution
  - Average Resolution Time for Complaints
- Created **KPI cards** in Power BI to display these metrics in real time.

---

### **4. Interactive Visualizations**
- Designed and developed three dynamic, interactive dashboards:
   Customer Demographics Dashboard – to analyze customer profiles, behavior, and segmentation.
   Sales Dashboard – to monitor performance by product, region, and customer type.
   Social Media Insights Dashboard – to evaluate platform engagement, content type effectiveness, and trends.

- Incorporated **slicers and filters** to allow management to drill down by region, customer type, and product.
- Designed dashboards with **user experience and executive readability** in mind.
- Ensured a clean, executive-friendly layout suitable for both desktop and mobile viewing.

---

### **5. Dashboard Testing and Optimization**
- Conducted testing for:
  - Data accuracy and refresh reliability
  - Cross-filtering and visual responsiveness
  - Layout consistency across devices (desktop, tablet)
---

### **6. Presentation Preparation**
- Exported key visuals and summary insights from Power BI.
- Created a **professional PowerPoint presentation** tailored for higher management.
- Structured the slides to include:
  - Executive Summary
  - Sales Insights
  - Customer Segmentation
  - Crisis Response Analysis
  - Social Media Engagement Metrics
  - Strategic Recommendations
    
![Image](https://github.com/user-attachments/assets/991201b3-9c6b-467d-bc1c-603fb1727863)

---

### **7. Final Review and Delivery**
- Reviewed the presentation with internal stakeholders for accuracy and clarity.
- Delivered the presentation to senior management, with supporting data available via live Power BI dashboards.

---
