# Customer Behavior Analysis Dashboard (Power BI)

## 📌 Project Overview
This project presents a comprehensive analysis of customer purchasing patterns using a dataset of **3,900+ records**. The primary objective was to transform raw sales data into actionable business insights, focusing on revenue drivers, demographic segmentation, and customer satisfaction.

## 📊 Key Business KPIs
* **Total Customers Analyzed:** 3,900+
* **Average Purchase Amount:** $59.76
* **Average Review Rating:** 3.75 / 5.0
* **Subscription Rate:** 27% (73% Non-subscribers)

## 🔍 Major Insights
* **Top Revenue Segment:** **Young Adults** are the primary revenue contributors across all categories.
* **Category Performance:** **Clothing** and **Accessories** are the highest-performing categories in terms of both sales volume and revenue.
* **Customer Loyalty:** Identified a significant gap between subscribers and non-subscribers, suggesting an opportunity for targeted loyalty programs.
* **Seasonal Trends:** Analyzed purchasing behavior across Fall, Spring, Summer, and Winter to assist in inventory planning.

## 🛠️ Technical Workflow
### 1. Data Cleaning & ETL (Power Query)
* Performed data profiling to ensure consistency across 3,900+ rows.
* Handled missing values and standardized categorical columns like `Shipping Type` and `Payment Method`.
* Engineered new features such as **Age Bins** (Young Adult, Adult, Senior) and **Seasonal Groups**.

### 2. Data Modeling & DAX
* Created a robust data model to support multi-dimensional analysis.
* **DAX Implementation:** Developed custom measures for:
  * `Average Purchase Value`
  * `Subscription Percentage`
  * `Revenue by Age Group`

### 3. Interactive Visualization
* **Dynamic Slicers:** Integrated 6+ slicers (Gender, Season, Shipping Type, etc.) for real-time data filtering.
* **Advanced Visuals:** * **Donut Charts:** To visualize Payment Method distribution and Subscription status.
  * **Stacked Bar Charts:** For Revenue vs. Age Group comparison.
  * **KPI Cards:** For immediate visibility of high-level metrics.
<img width="748" height="422" alt="image" src="https://github.com/user-attachments/assets/cec9c00e-698e-466d-95b5-1bf17cdf31be" />


**Note:** This project was developed as part of a Data Analytics portfolio to demonstrate proficiency in ETL, DAX, and storytelling with data.
