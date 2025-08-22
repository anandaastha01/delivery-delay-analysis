# delivery-delay-analysis
# Project Structure
Delivery-Delay-Analysis
│
├── Zomato_Cleaned.csv                                # Cleaned dataset for analysis

├── ZD_DataAnalysis.ipynb                             # Jupyter Notebook for data cleaning

├── zd_dataanalysis.py                                # Python script version

├── Delivery_Delay_Analysis_Report.pdf                # Detailed project report

├── Presentation-Delivery-Delay-Analysis.pdf          # Project presentation

├── ZomatoBI.pbix                                     # Power BI dashboard file

├── Zomato Dataset.csv.zip                            # Original dataset (compressed)

└── README.md                                         # Project documentation (this file)

# Project Overview
This project focuses on analyzing food delivery delays to identify patterns and factors affecting delivery times. The goal was to find which zones and time slots experience the highest delays and understand the role of weather, traffic, and other operational factors.
The analysis was carried out using Python (for data cleaning & preparation) and Power BI (for dashboard and visualization).The challenge was to analyze real-world delivery data, identify problem zones and time slots, and provide actionable insights to optimize operations.
# Dataset Details
Original Size: 45,584 rows × 20 columns
After Cleaning: 34,487 rows
Date Range: 2022-02-11 to 2022-04-06
Key Columns:
city (Metropolitan, Urban, Semi-Urban)
time_orderd, time_order_picked
time_taken_min (total time in minutes)
weather_conditions, road_traffic_density
festival, multiple_deliveries
Cleaning Steps:
Removed duplicates and unnecessary columns (IDs, lat/long)
Handled missing values (median for age, ratings, 0 for multiple deliveries)
Standardized text fields
Converted date/time columns to proper format
# Tools & Tech Used
Python: Data Cleaning & Preprocessing
Power BI: Data Modeling, DAX Measures, Dashboard Creation
# Dashboard Highlights
Page 1: Overview
KPIs: Average Delay, % Delayed Orders, Total Orders
Bar Chart: Zone-wise Delay Analysis

Page 2: Time & Zone Analysis
Heatmap: Delay by Zone × Time Slot
Line Chart: Hourly Delay Trends
Slicers: Date, Festival, Weather

Page 3: Delay Drivers
Weather & Traffic impact
Multiple Deliveries vs Delay
## Author
[AASTHA ANAND]
Computer Science & Data Analytics Undergraduate|IIT PATNA
