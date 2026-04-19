# 🏥 Hospital Quality Performance Dashboard

## 📌 Project Overview

This project presents a complete hospital quality performance analysis dashboard built in Power BI using publicly available hospital performance data. The dashboard is designed to help stakeholders compare hospitals, evaluate quality metrics, monitor safety performance, and identify areas needing improvement.

The project transforms raw hospital data into a clean, interactive, and decision ready reporting solution that supports hospital benchmarking and operational analysis.


## 🎯 Project Objectives

* Compare hospitals across multiple quality indicators
* Identify high and low performing hospitals
* Analyze patient safety and readmission measures
* Understand hospital ownership, type, and service patterns
* Support management level decision making using interactive visuals
* Provide benchmarking across states and hospital categories


## 🗂️ Dataset Used

The project uses hospital level quality and performance data including:

* Hospital name and location
* State and region details
* Ownership type
* Emergency service availability
* Measure name and category
* Better, worse, and no different performance indicators
* Readmission and mortality measures
* Patient safety measures
* Overall hospital ratings


## 🧹 Data Cleaning and Preparation

Several data cleaning and transformation steps were performed before building the dashboard:

* Removed duplicate records
* Handled missing and blank values
* Standardized hospital names and state names
* Corrected inconsistent data formats
* Created calculated columns and DAX measures
* Built relationships between fact and dimension tables
* Designed the data model using a star schema approach


## 🏗️ Data Model Design

The dashboard follows a star schema model for better performance and scalability.

### Main Fact Table

* FactPerformance

### Dimension Tables

* Hospital Dimension
* Measure Dimension
* State Dimension
* Ownership Dimension
* Rating Dimension

This structure improves filtering, relationship management, and reporting speed.


## 📊 Dashboard Pages

### 1. Executive Overview Dashboard

Provides a high level summary of:

* Total hospitals
* Total measures
* Better and worse performance counts
* Average hospital rating
* State wise comparison
* Hospital ownership breakdown

### 2. Hospital Performance Dashboard

Focused on individual hospital level analysis:

* Compare hospitals across quality measures
* Track safety and readmission performance
* Analyze overall ratings
* Identify strongest and weakest hospitals

### 3. Measure Analysis Dashboard

Detailed analysis of:

* Measure categories
* Better, worse, and no different results
* Performance distribution across hospitals
* Readmission and mortality measures

### 4. State Wise Dashboard

Shows regional insights including:

* Hospital distribution by state
* State wise performance trends
* Best and worst performing states
* Comparison of hospital ratings across regions


## 📈 Key KPIs Used

* Total Hospitals
* Total Measures
* Better Performance Count
* Worse Performance Count
* No Different Count
* Average Rating
* Better Percentage
* Worse Percentage
* Readmission Better Count
* Safety Better Count
* Threshold Based Performance Measures


## ⚙️ DAX Measures Created

Some important DAX measures used in this project include:

* Total Hospitals
* Total Measures
* Better Count
* Worse Count
* No Different Count
* Average Rating
* Better Percentage
* Worse Percentage
* Hospitals Above Threshold
* Projected Safety Better
* Projected Readmission Better

These measures help make the dashboard dynamic and interactive.


## 🎨 Visualizations Used

* KPI Cards
* Clustered Bar Charts
* Stacked Column Charts
* Donut Charts
* Matrix Tables
* Line Charts
* Maps
* Slicers
* Conditional Formatting
* Drill Through Pages
* Tooltips


## 🔍 Key Insights

* Some hospitals consistently perform better across safety and readmission measures
* Certain states have a higher concentration of low rated hospitals
* Emergency service availability is linked with larger hospitals
* Better performance counts are higher in some quality categories, while readmission measures often show weaker performance
* Matrix analysis helps identify hospitals with repeated poor performance across multiple measures
* Ownership type also impacts hospital quality trends


## 🚀 Tools and Technologies Used

* Microsoft Power BI
* Power Query
* DAX
* Excel / CSV Data Sources
* Data Modeling
* Star Schema Design



## 📌 Business Value

This dashboard helps healthcare stakeholders:

* Monitor hospital quality
* Compare performance across hospitals and states
* Identify underperforming hospitals quickly
* Improve operational and patient care decisions
* Support quality improvement initiatives


## 📷 Dashboard Screenshots
Executive Overview Dashboard

This dashboard provides a high level summary of hospital performance across multiple quality indicators. It includes KPIs such as total hospitals, total measures, average rating, better performance count, worse performance count, and ownership distribution.

Hospital Performance Dashboard

This page focuses on individual hospital level analysis. It helps compare hospitals across quality measures, patient safety indicators, readmission performance, and overall ratings.

State Wise Dashboard

This dashboard shows state level performance trends and comparisons. It helps identify the best and worst performing states, hospital distribution, and differences in hospital ratings across regions.

Data Model View

The project follows a star schema data model. The fact table stores detailed hospital performance data, while dimension tables support filtering by hospital, state, ownership, measure category, and ratings.

DAX Measures Section

Several DAX measures were created to make the dashboard interactive and dynamic. These include Better Count, Worse Count, Average Rating, Better Percentage, Hospitals Above Threshold, Projected Safety Better, and Projected Readmission Better.

Power Query Cleaning Steps

Power Query was used to clean and prepare the raw dataset before building the dashboard. This included removing duplicates, handling missing values, correcting data formats, standardizing names, and creating calculated columns for analysis.

## 📁 Project Deliverables

* Power BI Dashboard File
* Cleaned Dataset
* Data Model
* DAX Measures
* Project Documentation
* Dashboard Screenshots


## 🌟 Conclusion

This project demonstrates end to end business intelligence development using Power BI, including data cleaning, modeling, DAX creation, dashboard design, and insight generation. It highlights the ability to convert raw healthcare data into a powerful decision support tool for hospital performance analysis.
