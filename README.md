# 📊 KK’s Customer Behavior & Retention Dashboard
<img width="800" height="400" alt="overview-dashboard" src="https://github.com/user-attachments/assets/81fa39bc-d7e0-41cc-a706-52e6c391c6b1" />

# 📊 KK’s Customer Behavior & Retention Dashboard

![Project Cover](assets/project-cover.png)

A Power BI dashboard project focused on analyzing **customer segments**, **customer retention**, and **purchase behavior** to uncover actionable business insights and support data-driven decision-making.

---

## 📌 Table of Contents

- [📖 Project Overview](#-project-overview)
- [🎯 Project Objectives](#-project-objectives)
- [🧾 Dataset Overview](#-dataset-overview)
- [🧹 Data Cleaning & Preparation](#-data-cleaning--preparation)
- [🗂 Data Model & Supporting Tables](#-data-model--supporting-tables)
- [📊 Dashboard Structure](#-dashboard-structure)
- [📈 Key Dashboard Insights](#-key-dashboard-insights)
- [💡 Business Recommendations](#-business-recommendations)
- [🛠 Tools Used](#-tools-used)
- [📂 Project Files](#-project-files)
- [🖼 Dashboard Preview](#-dashboard-preview)
- [📽 Presentation](#-presentation)
- [🙋‍♂️ About Me](#-about-me)

---

## 📖 Project Overview

This project was built to explore how customer transaction data can be transformed into meaningful business insights using **Power BI**.

The goal of this dashboard was not just to visualize sales activity, but to understand:

- who the customers are
- how they behave
- how often they return
- what influences their purchase activity
- and where the business can improve retention and customer value

This project simulates a real-world customer analytics use case where a business wants to better understand customer performance across multiple dimensions.

---

## 🎯 Project Objectives

The main objectives of this project were to:

- Identify key customer segments
- Measure customer retention and repeat purchase behavior
- Analyze customer purchase patterns
- Understand customer activity across devices, payment methods, and acquisition channels
- Create an interactive dashboard that supports business decision-making

This project was designed to answer both **descriptive** and **behavioral** business questions using data.

---

## 🧾 Dataset Overview

The dataset used for this project was intentionally created as a **dirty customer transaction dataset** to simulate a more realistic business environment.

It contained over **2,000 rows** and included a wide range of customer and order-related fields such as:

- Transaction ID
- Customer ID
- Customer Name
- Order Date
- Country / City
- Customer Segment
- Product Category
- Product Name
- Quantity
- Unit Price
- Currency
- Discount
- Shipping Fee
- Payment Method
- Device Type
- Acquisition Channel
- Customer Rating
- Order Status

The dataset also included **multi-currency values**, missing values, inconsistent entries, and fields that required transformation before meaningful analysis could be carried out.

---

## 🧹 Data Cleaning & Preparation

The dataset required several cleaning and transformation steps before it could be used for dashboard analysis.

### Key data preparation tasks included:

- Standardizing customer and transaction fields
- Cleaning inconsistent text values
- Handling missing and blank values
- Creating a clean revenue field
- Converting multiple currencies into a common reporting value
- Creating customer-level retention and behavior fields
- Building analytical supporting tables for better reporting

### Some of the transformations performed included:

- Revenue calculation
- Currency normalization
- Customer repeat purchase logic
- Recency calculations
- Customer segmentation support
- Time-based analysis setup

Both **Power Query** and **DAX** were used throughout the data preparation process.

---

## 🗂 Data Model & Supporting Tables

To improve the quality of analysis and reporting, the project was structured into multiple tables instead of relying on only one raw dataset.

### Main tables used:

### 1️⃣ Customer_Transactions
This was the **main fact table** containing customer purchase records and transactional activity.

### 2️⃣ Currency_Table
This supporting table was created to help standardize transactions recorded in different currencies.

### 3️⃣ Date_Table
A calendar table was created to support time intelligence, trend analysis, and proper monthly reporting.

### 4️⃣ Customer_Summary
A customer-level summary table was created to make retention and behavior analysis easier by aggregating customer activity into one record per customer.

This structure helped improve:

- reporting clarity
- dashboard performance
- measure accuracy
- customer-level analysis

---

## 📊 Dashboard Structure

The dashboard was built across **3 main analytical pages**:

---

### 1️⃣ Customer Overview

This page focused on giving a high-level summary of customer and business activity.

It included visuals such as:

- Total Customers
- Total Orders
- Total Revenue
- Revenue by Customer Segment
- Customer Count by Country
- Monthly Purchase Trend
- Product Category Performance

---

### 2️⃣ Customer Retention

This page focused on understanding how often customers return and how loyal they are over time.

It included visuals such as:

- Retention Rate
- Repeat vs One-Time Customers
- Purchase Frequency
- Returning Customers by Month
- Repeat Customers by Segment
- Days Since Last Purchase Distribution

---

### 3️⃣ Customer Purchase Behavior

This page focused on how customers buy, how much they spend, and what influences their purchase activity.

It included visuals such as:

- Customer Lifetime Value (CLV)
- Average Quantity per Order
- Payment Method Analysis
- Device Type Analysis
- Acquisition Channel Performance
- Purchase Frequency vs Total Spend

---

## 📈 Key Dashboard Insights

The dashboard revealed several useful business insights.

### Some of the most important findings include:

### 🔹 Customer Overview Insights
- The business recorded **653 total customers** and **2,078 total orders**
- Total revenue reached approximately **₦2.97bn**
- The **Retail segment** generated the highest revenue
- **Electronics** and **Home** categories attracted strong customer spending
- Customer activity showed noticeable monthly fluctuations

---

### 🔹 Customer Retention Insights
- The dashboard recorded an **84% retention rate**
- **Repeat customers** significantly outnumbered one-time buyers
- Purchase frequency showed that customers bought more than once on average
- The **Retail segment** also led in repeat customer activity
- Recency distribution suggested that some customers may require re-engagement

---

### 🔹 Customer Purchase Behavior Insights
- Customer Lifetime Value (CLV) was approximately **₦4.55M**
- Customers purchased an average of **4.57 items per order**
- **Transfer** and **Card** were the most preferred payment methods
- **Mobile** was the most used device for purchases
- Acquisition channels such as **Website**, **TikTok**, and **Facebook** performed strongly
- Customer ratings suggested there may be room for service or experience improvement

---

## 💡 Business Recommendations

Based on the dashboard findings, the following recommendations were made:

### 1. Prioritize retention campaigns
Focus more on retaining high-value customer groups, especially segments already contributing strong repeat purchase behavior.

### 2. Re-engage inactive customers
Customers who have not purchased recently should be targeted with reactivation campaigns, reminders, or personalized offers.

### 3. Improve customer satisfaction
The customer rating trend suggests the need to review areas such as product quality, service delivery, and customer support.

### 4. Strengthen high-performing acquisition channels
Marketing efforts can be optimized further around channels already showing strong customer acquisition performance.

### 5. Optimize the mobile purchase experience
Since mobile was the most used purchase device, improving mobile user experience could positively impact customer conversion and retention.

### 6. Promote strong-performing product categories
Top-spending categories such as Electronics and Home can be strategically promoted through campaigns and bundles.

---

## 🛠 Tools Used

The following tools were used in this project:

- **Power BI**
- **Power Query**
- **DAX**
- **Excel**

---

## 📂 Project Files

This repository contains the following project files:

- `KK_Customer_Behavior_Retention_Dashboard.pbix` → Power BI dashboard file
- `Customer_Behavior_Dataset.xlsx` → Dataset used for the analysis
- `KK_Customer_Behavior_Retention_Dashboard_Presentation.pptx` → Project PowerPoint presentation
- `screenshots/` → Dashboard screenshots
- `assets/` → Supporting visual assets

---

## 🖼 Dashboard Preview

### Customer Overview
<img width="599" height="338" alt="overview-dashboard" src="https://github.com/user-attachments/assets/2c96fb43-179c-4966-a0d6-f04e3b217a27" />


### Customer Retention
<img width="599" height="337" alt="retention-dashboard" src="https://github.com/user-attachments/assets/160167bf-26b0-4575-93f9-64a74239a797" />

### Customer Purchase Behavior
<img width="599" height="337" alt="retention-dashboard" src="https://github.com/user-attachments/assets/160167bf-26b0-4575-93f9-64a74239a797" />

---

## 📽 Presentation

The full project presentation is also included in this repository:

- `KK_Customer_Behavior_Retention_Dashboard_Presentation.pptx`

This presentation summarizes the dashboard objectives, insights, and business recommendations.

---

## 🙋‍♂️ About Me

I’m building practical projects in **data analytics**, **Power BI**, **Excel**, and **business intelligence** to turn raw data into clear and useful business insights.

This project is part of my growing analytics portfolio, where I focus on building dashboards and solving business problems with data.

If you’d like to connect, collaborate, or discuss opportunities, feel free to reach out.

---

## ⭐ If you found this project interesting...

Feel free to **star this repository** and connect with me on Linkedln  @https://www.linkedin.com/in/kelvin-etisi-39704a259/overlay/contact-info
