# 🚕 Uber Trip Analysis | Power BI Dashboard

## 📌 Project Overview

This project focuses on analyzing Uber trip data using **Microsoft Power BI** to understand booking trends, revenue patterns, trip efficiency, and customer demand. The interactive dashboards help identify peak booking periods, popular pickup and drop-off locations, and vehicle preferences to support data-driven decision-making.

## 🎯 Project Objectives

- Analyze total bookings and booking value.
- Understand trip distance and duration patterns.
- Identify peak and off-peak booking hours.
- Explore popular pickup and drop-off locations.
- Compare trip performance across vehicle types and payment methods.
- Enable interactive analysis through slicers, dynamic measures, and drill-through functionality.

## 🛠️ Tools & Technologies

* **Microsoft Power BI** – Dashboard development and data visualization
* **Power Query** – Data cleaning and transformation
* **DAX** – Measures, calculations, and dynamic visualizations
* **Data Modeling** – Relationships between trip details and location tables

## 📊 Dashboard Features and Preview

### 1. Overview Analysis

<img width="1447" height="816" alt="image" src="https://github.com/user-attachments/assets/ef12bb9d-5564-4ef0-b612-35cbcf88ba4a" />

Provides a high-level view of Uber trip performance through key performance indicators (KPIs).

**Key Metrics:**

- Total Bookings
- Total Booking Value
- Average Booking Value
- Total Trip Distance
- Average Trip Distance
- Average Trip Time

**Visualizations & Analysis:**

- Booking trends by day
- Vehicle type performance comparison
- Payment type analysis
- Trip booking distribution by location
- Top 5 locations by booking volume
- Most frequent pickup and drop-off points
- Longest trip analysis

**Interactive Features:**

- Dynamic measure selector
- Dynamic chart titles
- Date, city, and other slicers
- Tooltips and conditional formatting

### 2. Time Analysis

<img width="1450" height="815" alt="image" src="https://github.com/user-attachments/assets/2c75c327-17dd-468a-b478-eb78f22498b7" />


Examines booking patterns across different times of the day and days of the week.

**Visualizations:**

- **Area Chart:** Booking trends at 10-minute pickup-time intervals
- **Line Chart:** Booking trends from Monday to Sunday
- **Heatmap:** Booking patterns by hour and day of the week

**Key Objectives:**

- Identify peak and off-peak demand periods.
- Compare weekday and weekend booking patterns.
- Understand hourly fluctuations in ride demand.
- Support demand forecasting and resource planning.

### 3. Trip Details

<img width="1410" height="791" alt="image" src="https://github.com/user-attachments/assets/6d4bd2b3-1f92-4775-b0e6-d7a52f87fcb2" />

Provides a detailed view of individual trips with drill-through functionality.

**Key Features:**

- Detailed trip records
- Drill-through from other dashboard visuals
- Filtered and full-data views using bookmarks
- Interactive data exploration

**Data Fields:**

- Trip ID
- Pickup and drop-off times
- Passenger count
- Trip distance
- Pickup and drop-off location IDs
- Payment type
- Fare amount
- Surge fee
- Vehicle type

## 🗂️ Data Model

The project uses two tables:

- **Trip Details Table:** Contains individual ride records, including trip timing, distance, fare information, payment type, and vehicle type.
- **Location Table:** Maps location IDs to location names and cities for geographic analysis.

The relationship between pickup/drop-off location IDs and the Location Table supports location-based analysis, including the use of an inactive relationship where required.

## 💡 Business Value

The dashboard is designed to help stakeholders:

- Understand ride demand and booking trends.
- Identify high-demand locations and time periods.
- Analyze revenue and trip performance.
- Compare vehicle preferences and payment methods.
- Make informed decisions about resource allocation and pricing strategies.

## 🚀 Key Learnings

- Building interactive dashboards in Power BI.
- Creating DAX measures and dynamic metric selectors.
- Designing data models and managing table relationships.
- Using slicers, bookmarks, tooltips, and drill-through.
- Translating trip data into meaningful business insights.

## 👤 Author

**Akanksha Kumari**

Aspiring Data Analyst | Power BI | SQL | Excel | Python | Tableau | Generative AI 
