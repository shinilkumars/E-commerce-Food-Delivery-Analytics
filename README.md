# E-commerce Food Delivery Analytics: Driving Business Insights
This project presents a comprehensive analysis of e-commerce food delivery platform sales data, empowering business leaders with valuable insights and an interactive dashboard to make data-driven decisions. Leveraging Excel's powerful data analysis, modeling, and visualization capabilities, this project offers a deep understanding of food delivery operations.

## Key Features

- **Interactive Dashboard:** Explore key business metrics, trends, and patterns through a visually appealing and user-friendly Excel dashboard.
- **Data Integration:** Unified data from multiple sources using lookup functions for consistent analysis.
- **In-Depth Data Modeling:**
  - Consolidation of data from separate sheets (sales, city IDs, restaurant IDs) into a unified dataset.
  - Data transformation for optimal analysis, including pivot tables and column unpivoting.
  - Creation of calculated fields like AOV (Average Order Value), average discount, average rating, and average delivery time.
  - Establishment of relationships between data entities (orders to restaurants/cities).
  - Data cleansing to ensure quality and consistency.
- **Pivot Table Expertise:** Efficient summarization of key metrics like total revenue, AOV, discount percentage, and average rating.
- **Metric Tracking:** Monitoring and reporting of crucial business metrics.
- **Trend Identification:** Uncovering seasonal trends, restaurant performance, and customer behavior patterns.
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

Data Dictionary:

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

- **Overall Business Trend:** Trend charts for revenue, orders, AOV, and discount percentage.
- **City-wise Dashboard:** Visualizations for city-wise performance metrics.
- **Restaurant-wise Dashboard:** Visualizations for restaurant-wise performance metrics.
- **Key Insights:** Written observations and insights from the analysis.

## Technologies Used

**Excel** 
  - Data cleaning, analysis and modeling. 
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
1. Open the Excel workbook file: `e-commerce-food-sales-analysis.xlsx`
2. Navigate through different sheets to explore dashboards, visualizations, and pivot tables.
3. Use slicers for dynamic filtering and in-depth analysis.
