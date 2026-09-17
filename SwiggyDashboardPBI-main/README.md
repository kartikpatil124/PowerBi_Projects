# 🍔 Swiggy Executive Intelligence Dashboard

## 📌 Project Overview

The Swiggy Executive Intelligence Dashboard is an interactive Business Intelligence solution developed in Power BI to analyze restaurant performance, customer ratings, cuisine distribution, pricing patterns, and delivery efficiency across multiple cities.

This dashboard transforms raw restaurant data into actionable business insights, enabling decision-makers to identify growth opportunities, optimize delivery operations, understand customer preferences, and monitor platform performance through a centralized analytics interface.

The project follows a modern executive reporting approach by combining KPI monitoring, geographical analysis, customer experience metrics, and pricing intelligence into a single dashboard.

---

# 🎯 Business Problem

Food delivery platforms operate across thousands of restaurants, multiple cities, and diverse cuisines. Without centralized analytics, it becomes difficult to answer critical business questions such as:

- Which cities have the highest restaurant concentration?
- Which locations provide the best customer experience?
- Which cuisines dominate the platform?
- Do expensive restaurants receive better ratings?
- How does pricing affect delivery performance?
- Which areas represent potential growth opportunities?

This dashboard provides data-driven answers to these questions.

---

# 🚀 Dashboard Objective

The primary objective of this dashboard is to:

- Monitor overall platform performance.
- Analyze restaurant distribution across cities.
- Understand cuisine popularity.
- Evaluate customer satisfaction through ratings.
- Analyze delivery efficiency.
- Identify pricing trends and patterns.
- Support strategic business decisions through visual analytics.

---

# 📊 Key Performance Indicators (KPIs)

The dashboard tracks the following high-level metrics:

### Total Restaurants
Measures the total number of restaurants available on the platform.

### Total Cities
Represents the total number of cities covered.

### Average Rating
Provides an overview of customer satisfaction.

### Average Delivery Time
Tracks overall delivery efficiency.

### Average Price
Represents the average restaurant pricing across the platform.

---

# 📈 Dashboard Components

## 1. Executive Overview

Provides a high-level summary of business performance.

### KPIs Included:
- Total Restaurants
- Total Cities
- Average Rating
- Average Delivery Time
- Average Price

---

## 2. Restaurant Distribution Analysis

Visualizes restaurant concentration across cities.

### Business Value:
- Identifies high-density markets.
- Highlights expansion opportunities.
- Helps understand geographical presence.

### Key Questions Answered:
- Which city has the highest restaurant count?
- Which markets are underrepresented?

---

## 3. Customer Rating Analysis

Analyzes average ratings across cities and restaurants.

### Business Value:
- Measures customer satisfaction.
- Identifies high-performing regions.
- Supports quality improvement initiatives.

### Key Questions Answered:
- Which city maintains the best ratings?
- Which restaurants consistently perform well?

---

## 4. Cuisine Popularity Analysis

Analyzes food type distribution across the platform.

### Business Value:
- Identifies customer preferences.
- Supports marketing campaigns.
- Assists restaurant acquisition strategy.

### Key Questions Answered:
- Which cuisines dominate the platform?
- Which food categories are growing?

---

## 5. Price vs Rating Analysis

Scatter plot visualization comparing pricing and customer ratings.

### Business Value:
- Evaluates value-for-money perception.
- Identifies premium restaurant performance.
- Supports pricing strategy decisions.

### Key Questions Answered:
- Do expensive restaurants receive better ratings?
- Is there a relationship between pricing and customer satisfaction?

---

## 6. Delivery Performance Analysis

Analyzes delivery times across different price ranges.

### Business Value:
- Identifies operational bottlenecks.
- Supports delivery optimization.
- Improves customer experience.

### Key Questions Answered:
- Do premium restaurants take longer to deliver?
- Which price segments provide the fastest service?

---

## 7. Interactive Filtering System

Users can dynamically filter the dashboard by:

- City
- Area
- Food Type
- Rating Range
- Price Range

This enables personalized exploration of business insights.

---

# 🛠 Tools & Technologies

| Technology | Purpose |
|------------|----------|
| Power BI | Dashboard Development |
| Power Query | Data Transformation |
| DAX | Calculations & Measures |
| Data Modeling | Relationship Management |
| CSV Dataset | Source Data |

---

# 📂 Dataset Information

### Dataset Features

- Restaurant Name
- City
- Area
- Cuisine Type
- Price
- Rating
- Delivery Time
- Total Ratings

### Data Scope

- Multiple Indian Cities
- Thousands of Restaurants
- Multiple Cuisine Categories
- Customer Experience Metrics
- Pricing Information

---

# 📌 Key Business Insights

### Market Presence
Major metropolitan cities dominate restaurant concentration, indicating stronger market penetration.

### Customer Satisfaction
Average ratings remain relatively stable across cities, suggesting consistent service quality.

### Cuisine Trends
North Indian and Chinese cuisines represent a significant share of platform offerings.

### Pricing Behavior
Higher pricing does not necessarily guarantee higher customer ratings.

### Delivery Efficiency
Certain price segments experience longer delivery times, indicating potential operational optimization opportunities.

---

# 📈 DAX Measures Used

### Total Restaurants

```DAX
Total Restaurants = COUNT(swiggy[Restaurant])
```

### Total Cities

```DAX
Total Cities = DISTINCTCOUNT(swiggy[City])
```

### Average Rating

```DAX
Avg Rating = AVERAGE(swiggy[Avg ratings])
```

### Average Delivery Time

```DAX
Avg Delivery Time = AVERAGE(swiggy[Delivery time])
```

### Average Price

```DAX
Avg Price = AVERAGE(swiggy[Price])
```

---

# 🎨 Dashboard Design Philosophy

The dashboard follows a modern executive reporting design inspired by contemporary SaaS analytics platforms.

### Design Features

- Dark Premium Theme
- Swiggy Brand Colors
- Interactive KPI Cards
- Responsive Layout
- Minimalistic Visual Design
- Executive-Level Insights Section
- Clean Typography
- High Visual Hierarchy

---

# 💡 Business Impact

This dashboard enables stakeholders to:

- Monitor platform growth.
- Improve operational efficiency.
- Enhance customer satisfaction.
- Identify expansion opportunities.
- Optimize restaurant partnerships.
- Support data-driven decision-making.

---

# 🏆 Skills Demonstrated

This project demonstrates proficiency in:

### Data Analytics
- Exploratory Data Analysis
- Business Intelligence
- KPI Design

### Power BI
- Data Modeling
- Power Query
- DAX Calculations
- Interactive Visualizations
- Dashboard Design

### Business Understanding
- Customer Analytics
- Operational Analytics
- Market Analysis
- Performance Monitoring

### Data Visualization
- Storytelling with Data
- Executive Dashboarding
- Insight Generation

---

# 📸 Dashboard Preview

The dashboard includes:

✔ Executive KPI Overview  
✔ Restaurant Distribution Analysis  
✔ Customer Rating Insights  
✔ Cuisine Popularity Analysis  
✔ Price vs Rating Relationship  
✔ Delivery Performance Monitoring  
✔ Interactive Filters  
✔ Executive Business Insights

---

# 🔮 Future Enhancements

- Revenue Forecasting
- Restaurant Performance Ranking
- Geospatial Mapping
- Customer Segmentation
- Time-Series Trend Analysis
- Delivery Route Optimization
- AI-Powered Insights
- Predictive Analytics

---

# 👨‍💻 Author

**Kartik Patil**

Aspiring Data Analyst passionate about transforming data into actionable business insights through Power BI, SQL, Excel, and Analytics.

---

## ⭐ Project Outcome

Developed a professional executive-level Power BI dashboard that converts raw restaurant data into strategic business intelligence, helping stakeholders monitor performance, identify opportunities, and make informed decisions through interactive analytics.
