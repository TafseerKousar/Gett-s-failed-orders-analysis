# 🚖 Failed Orders Analysis for Gett's Ground Transportation Management (GTM)

This project investigates failed orders on Gett's corporate transportation platform, focusing on cancellations and rejections where customers did not successfully get a car. The analysis provides insights into why orders fail and identifies patterns in failed order distribution by time and location.

## 📊 Project Tasks

1. **Failure Reasons Analysis**  
   - Distribution of failed orders by cancellation and rejection reasons.
   - Identifies which reason category has the highest frequency.

2. **Hourly Failure Distribution**  
   - Visualizes failed orders by hour to detect trends and peak failure times.
   - Explores if specific hours have higher failure rates for certain categories.

3. **Cancellation Time Analysis**  
   - Compares average time to cancellation (with and without driver assignment) by hour.
   - Removes outliers to improve accuracy and draw meaningful conclusions.

4. **ETA Distribution**  
   - Plots average ETA by hour to understand time-to-arrival fluctuations.
   - Reveals potential inefficiencies in driver matching and allocation.

5. **Geospatial Analysis Using Hexagons (Bonus)**  
   - Maps failed order clusters using H3 hexagons, highlighting areas with high failure rates.
   - Calculates the number of hexes that contain 80% of failed orders.

## 🛠️ Tools and Libraries Used

- **Python Libraries:** `pandas`, `matplotlib`, `seaborn` for data processing and visualization
- **Geospatial Libraries:** `h3`, `folium` for hexagon-based mapping and geographic data analysis

## 📈 Insights and Outcomes

- **Primary Failure Causes:** Identified leading causes of failed orders and times of day with the highest failure rates.
- **Cancellation Trends:** Revealed patterns in cancellation times and ETA distributions, indicating areas for potential improvement in matching.
- **High-Failure Locations:** Mapped geographic clusters with the highest failed orders to aid in strategic planning.

## 📂 Data

- `data_orders.csv`: Contains order details including timestamps, locations, and cancellation reasons.
- `data_offers.csv`: Maps order IDs to offer IDs to identify failed offers.

---


--- 
