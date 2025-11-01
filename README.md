# 🚕 NYC Yellow Taxi Trip Records — Exploratory Data Analysis

### 📌 Overview
This project performs an exploratory data analysis (EDA) on New York City Yellow Taxi trip records to uncover mobility patterns, pricing behavior, passenger trends, and spatial trip distributions.

The sampled dataset contains approximately 3.79 million records with details such as vendor id, payment types, timestamps, passenger counts, trip distances, fare components, tips, and pickup/drop-off zone IDs.

The analysis uses:
- Python
- NumPy (numerical python)
- Pandas (data wrangling)
- GeoPandas (geospatial analysis)
- Matplotlib & Seaborn (visualizations)

> ⚠️ Dataset couldn't be included due to GitHub file size limits.
> Full dataset is available from the NYC TLC Open Data Portal.
---

📎 Data Source: [NYC TLC Trip Record Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)

---

### 🎯 Key Objectives
- Understand demand patterns across time and zones  
- Analyze fare structure and tipping behavior  
- Compare vendor pricing approaches  
- Identify high-traffic and congested routes  
- Perform geospatial mapping of trip zones and density  

---

### 🧹 Data Preparation
- Cleaned missing and invalid entries  
- Isolated anomalies rather than deleting records  
- Validated location IDs using official NYC taxi zone shapefile  
- Removed or corrected outlier monetary and distance values  
- Generated time-based and route-based features  

---

### 📊 Analysis Highlights

#### 🕒 Temporal Trends
- Hourly, daily, monthly ride volume patterns  
- Weekday vs weekend activity comparison  
- Late-night vs daytime behavior analysis  

#### 🌍 Geospatial Insights
- Zone-level mapping via GeoPandas  
- Pickup and drop-off density visualization  
- Late-night hotspot identification  

#### 💵 Fare & Tip Behavior
- Fare-per-mile calculation  
- Tip percentage analysis across variables  
- Vendor fare comparison  
- Tier-based pricing analysis (≤2 miles, 2–5 miles, >5 miles)  

#### 🚦 Operational Efficiency
- Route speed estimation (distance ÷ duration)  
- Slow / congested route detection  
- Passenger count variation across time and zones  

---

### 📎 License
Distributed under the MIT License.

---

### 👤 Author
Russel Anthony Reynold Chandanshiv
