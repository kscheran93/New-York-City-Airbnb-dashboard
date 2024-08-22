# New York City Airbnb Dashboard

## Snapshot of Dashboard (Power BI Service)

![Dashboard_Snapshot](Your_Snapshot_Link_Here)

### Dashboard Link: [View Dashboard](https://github.com/kscheran93/New-York-City-Airbnb-dashboard/blob/main/Airbnb%20Dashboard.png)

## Problem Statement

This dashboard provides insights into the New York City Airbnb market. It analyzes various aspects such as booking trends, neighborhood distribution, room types, pricing, and host activity. By exploring these insights, stakeholders can better understand the dynamics of the Airbnb market in New York City, including popular neighborhoods, pricing strategies, and host performance.

### Filters

- **Neighbourhood Group**
  - **Field:** `neighbourhood_group`
- **Room Type**
  - **Field:** `room_type`

### Cards

1. **Average Reviews per Month**
   - **Field:** Average of `reviews_per_month`
2. **Total Number of Reviews**
   - **Field:** Sum of `number_of_reviews`
3. **Count of Neighbourhoods**
   - **Field:** Count of `neighbourhood`
4. **Count of Hosts**
   - **Field:** Count of `host_id`

### Visualizations

1. **Clustered Column Chart: Total Last Reviews by Year**
   - **X-Axis:** `last_review` (Year)
   - **Y-Axis:** Count of `last_review`

2. **Clustered Bar Chart: Total Bookings by Neighbourhood Group**
   - **Y-Axis:** `neighbourhood_group`
   - **X-Axis:** Count of `name`

3. **Clustered Column Chart: Total Reviews by Month**
   - **X-Axis:** `last_review` (Month)
   - **Y-Axis:** Sum of `reviews_per_month`

4. **Clustered Bar Chart: Average Price by Neighbourhood**
   - **Y-Axis:** `neighbourhood`
   - **X-Axis:** Average of `price`

5. **Clustered Bar Chart: Top 5 Hosts by Total Reviews**
   - **Y-Axis:** `host_name`
   - **X-Axis:** Sum of `number_of_reviews`
   - **Filters:** Top 5 Hosts

6. **Matrix Chart: Average Price by Neighbourhood Group and Room Type**
   - **Rows:** `neighbourhood_group`
   - **Columns:** `room_type`
   - **Values:** Average of `price`

7. **Doughnut Chart: Total Neighbourhood by Group**
   - **Legend:** `neighbourhood_group`
   - **Values:** Count of `neighbourhood`

8. **Matrix Chart: Average Reviews by Month by Neighbourhood Group and Room Type**
   - **Rows:** `neighbourhood_group`
   - **Columns:** `room_type`
   - **Values:** Average of `reviews_per_month`

### Data Source

- Dataset Link: [Kaggle - New York City Airbnb Open Data](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data)

### Insights

1. **Total Last Reviews by Year:**
   - The clustered column chart shows the distribution of last reviews by year, helping to identify recent activity and trends in reviews over time.

2. **Total Bookings by Neighbourhood Group:**
   - The clustered bar chart highlights which neighborhood groups have the highest number of bookings, offering insights into popular areas for Airbnb stays in NYC.

3. **Total Reviews by Month:**
   - This chart reveals how review activity varies by month, providing insights into seasonal trends in guest feedback.

4. **Average Price by Neighbourhood:**
   - The average price by neighborhood chart helps identify the pricing landscape across different areas of NYC, useful for hosts to set competitive prices.

5. **Top 5 Hosts by Total Reviews:**
   - The top hosts chart showcases the most active hosts based on total reviews, highlighting key players in the NYC Airbnb market.

6. **Average Price by Neighbourhood Group and Room Type:**
   - The matrix chart provides a detailed view of how prices vary by neighborhood group and room type, helping to understand the impact of location and room type on pricing.

7. **Total Neighbourhood by Group:**
   - The doughnut chart shows the distribution of neighborhoods across different groups, giving a quick overview of the spread of Airbnb listings.

8. **Average Reviews by Month by Neighbourhood Group and Room Type:**
   - This matrix chart offers insights into the average number of reviews received per month across different neighborhood groups and room types, helping to identify which combinations perform best.
