# E-commerce Food Delivery Analytics: Driving Business Insights
![E-commerce_Food_Delivery](https://github.com/shinilkumars/E-commerce-Food-Delivery-Analytics/assets/173347067/e7e44501-6331-4386-8e85-683b0528fac4)

## Table of Contents
 - [Project Overview](#project-overview)
 - [Key Features](#key-features)
 - [Data Overview and Relationships](#data-overview-and-relationships)
 - [Dashboards and Visualizations](#dashboards-and-visualizations)
 - [Technologies Used](#technologies-used)
 - [Key Insights](#key-insights)
 - [Project Exploration](#project-exploration)

## Project Overview

This project presents a comprehensive analysis of e-commerce food delivery platform sales data, empowering business leaders with valuable insights and an interactive dashboard to make data-driven decisions. Leveraging Excel's powerful data analysis, modeling, and visualization capabilities, this project offers a deep understanding of food delivery business.

## Key Features

- **Interactive Dashboard:** Explore key business metrics, trends, and patterns through a visually appealing and user-friendly Excel dashboard.
- **Data Integration:** Unified data from multiple workbooks using lookup functions for consistent analysis.
- **Data Modeling:**
  - Consolidation of data from separate sheets (sales, city IDs, restaurant IDs) into a unified dataset.
  - Data transformation for optimal analysis, including pivot tables .
  - Creation of calculated fields like AOV (Average Order Value), average discount, average rating, and average delivery time.
  - Establishment of relationships between data entities (orders to restaurants/cities).
  - Data cleansing to ensure quality and consistency.
- **Pivot Table Expertise:** Efficient summarization of key metrics like total revenue, AOV, discount percentage, and average rating.
- **Metric Tracking and Trend Identification:** Monitoring, reporting, and uncovering crucial business performance metrics and trends.
- **Data Visualization:** Interactive visualizations including charts, graphs, pivot tables, and slicers for dynamic filtering and deep drill-down analysis.
- **Key Insights:** Observations and recommendations to support strategic planning and operational improvements.

## Data Overview and Relationships

The analysis is based on a unified dataset integrated from three separate workbook:

1. **Combined Sales Data:** includes order details,customer details and city details.
2. **City ID Mapping:** City ID and corresponding city name.
3. **Restaurant ID Mapping:** Restaurant ID and corresponding restaurant name.

### Key Relationships:
- City to Orders: One-to-Many
- Restaurant to Orders: One-to-Many
- City ID to City Name: One-to-One
- Restaurant ID to Restaurant Name: One-to-One

### Data Dictionary:

| Column            | Details                                                     |
|-------------------|-------------------------------------------------------------|
| Date              | Order date                                                  |
| Order_ID          | Unique order identifier                                     |
| Customer_ID       | Unique customer identifier                                  |
| City_ID           | City ID assigned to every city of the data                  |
| Restaurant_ID     | Restaurant ID assigned to every Restaurant of the data      |
| Revenue           | Revenue generated before discount                           |
| Discount          | Discount amount applicable on the order                     |
| Rating            | Rating given by customer post order delivery                |
| Preparation time  | Order time to pickup time in mins                           |
| Delivery time     | pickup to delivery time in min                              |
| Total Time        | sum of preparation time and delivery time                   |

## Dashboards and Visualizations

- **Overall Business Trend:** Visualizations for overall business performance metrics.
- **City-wise Dashboard:** Visualizations for city-wise performance metrics.
- **Restaurant-wise Dashboard:** Visualizations for restaurant-wise performance metrics.
- **Key Insights:** Observations and insights from the analysis.

## Technologies Used

**Excel** 
  - Data cleaning, modeling, and analysis. 
  - Pivot table creation ,calculated field creation and visualization with slicers for drill-down insights.
  - Lookup functions for data integration.

## Key Insights

1. Total revenue is evenly distributed across all four cities, indicating consistent demand for food delivery services.
2. Increased average order value correlates with higher average discount percentages in May and June, suggesting a need to monitor discount strategies to protect revenue.
3. Certain restaurants, like Haldiram, have longer delivery times that may impact customer satisfaction.
4. The average restaurant rating across all cities is around 3.5, indicating overall satisfaction but with room for improvement.
5. High-rated restaurants like Barbeque Nation should be given more visibility on the platform to attract customers and increase orders.
6. August shows favorable revenue and order trends, presenting an opportunity to replicate this success in other months.
7. Discounts and offers effectively attract customers, as average order value increases with higher discounts.

## Project Exploration

To explore the project and interact with the dashboard:
1. Open the Excel workbook file: [E-commerce Food Delivery Analytics.xlsx](https://github.com/shinilkumars/E-commerce-Food-Delivery-Analytics/raw/main/E-commerce%20Food%20Delivery%20Analytics.xlsx)
2. Navigate through different sheets to explore dashboards, visualizations, and pivot tables.
3. Use slicers for dynamic filtering and in-depth analysis.
