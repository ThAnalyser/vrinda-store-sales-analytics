# 📊 Vrinda Store Annual Sales Analysis 2022

<div align="center">

![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data_Analysis-FF6B6B?style=for-the-badge)
![Dashboard](https://img.shields.io/badge/Dashboard-4CAF50?style=for-the-badge)

**A comprehensive e-commerce sales analysis dashboard for Vrinda Store's 2022 operations**

[Overview](#-overview) • [Dataset](#-dataset) • [Key Insights](#-key-insights) • [Dashboard](#-dashboard) • [Analysis](#-analysis) • [Recommendations](#-recommendations)

</div>

---

## 📋 Overview

This project delivers an **end-to-end sales analytics solution** for Vrinda Store, analyzing **31,047 orders** across 2022 to uncover customer behavior patterns, sales trends, and operational insights. The interactive Excel dashboard enables stakeholders to make data-driven decisions for 2023 growth strategy.

### 🎯 Project Objectives

- **Customer Segmentation**: Identify high-value customer demographics
- **Channel Performance**: Evaluate sales across different e-commerce platforms
- **Geographic Analysis**: Map sales distribution across India
- **Trend Analysis**: Discover seasonal patterns and peak sales periods
- **Operational Insights**: Assess order fulfillment and delivery patterns

---

## 📁 Dataset

### Data Structure
- **Records**: 31,047 orders
- **Time Period**: January - December 2022
- **Columns**: 21 attributes
- **File Size**: Multi-sheet Excel workbook

### 📊 Data Dictionary

| Column | Type | Description |
|--------|------|-------------|
| **Order ID** | String | Unique identifier for each order |
| **Cust ID** | Integer | Customer identification number |
| **Gender** | String | Customer gender (Men/Women) |
| **Age** | Integer | Customer age |
| **Age Group** | String | Categorized age ranges (Teenager/Adult/Senior) |
| **Date** | DateTime | Order placement date |
| **Month** | String | Month of order (Jan-Dec) |
| **Status** | String | Order status (Delivered/Cancelled/Returned/Refunded) |
| **Channel** | String | Sales platform (Myntra/Ajio/Amazon/Flipkart/Others) |
| **SKU** | String | Stock Keeping Unit identifier |
| **Category** | String | Product category (Kurta/Set/Top/Saree/Western Dress/Ethnic Dress/Blouse) |
| **Size** | String | Product size (S/M/L/XL/XXL/Free/3XL-10XL) |
| **Qty** | Integer | Quantity ordered |
| **Currency** | String | Transaction currency (INR) |
| **Amount** | Integer | Order value in rupees |
| **ship-city** | String | Delivery city |
| **ship-state** | String | Delivery state |
| **ship-postal-code** | Integer | Delivery PIN code |
| **ship-country** | String | Delivery country (IN) |
| **B2B** | Boolean | Business-to-Business order flag |

---

## 🔍 Key Insights

### 👥 Customer Demographics

**Gender Distribution**
- **Women**: Primary customer base (majority of orders)
- **Men**: Secondary segment
- **Target Market**: Predominantly female-focused ethnic wear

**Age Analysis**
- **Adult** (30-50): Largest customer segment
- **Teenager** (18-29): Growing market
- **Senior** (50+): Emerging opportunity

### 📈 Sales Performance

**Top Performing States**
1. Maharashtra
2. Karnataka
3. Uttar Pradesh
4. Telangana
5. Tamil Nadu

**Major Cities**
- Bangalore
- Hyderabad
- Mumbai
- Delhi
- Chennai

### 🛒 Channel Performance

**Leading Platforms** (Sample data):
- **Myntra**: Primary sales channel
- **Ajio**: Strong secondary platform
- **Amazon**: E-commerce giant presence
- **Flipkart**: Significant market share
- **Others**: Meesho, Nalli, Myntra, SSC

### 📅 Seasonal Trends

**Monthly Performance** (Sample insights):
- **Peak Months**: March, May, July (festival seasons)
- **High Revenue Periods**: Q2 & Q3
- **Strong Order Volumes**: July (32 orders), February (22 orders)

**Order Status Distribution**
- **Delivered**: 28,641 orders (92.25% success rate)
- **Returned**: 1,045 orders (3.37%)
- **Cancelled**: 844 orders (2.72%)
- **Refunded**: 517 orders (1.67%)

### 👗 Product Insights

**Top Categories**
- **Kurta**: Bestselling category
- **Set**: Popular combo purchases
- **Ethnic Wear**: Strong demand
- **Western Dress**: Growing segment

**Size Preferences**
- **M & L**: Most popular sizes
- **XL & XXL**: Significant demand
- **S**: Moderate sales
- **Plus Sizes**: Niche market (3XL-10XL)

---

## 📊 Dashboard

### Interactive Features

The Excel dashboard includes:

1. **Monthly Sales Trend** 📈
   - Order count visualization
   - Revenue tracking
   - MoM growth analysis

2. **Channel Breakdown** 🏪
   - Platform-wise sales distribution
   - Performance comparison
   - Revenue contribution

3. **Geographic Heatmap** 🗺️
   - State-wise sales mapping
   - Top cities identification
   - Regional performance

4. **Customer Segmentation** 👤
   - Age group analysis
   - Gender distribution
   - Demographic insights

5. **Product Analysis** 👔
   - Category performance
   - Size distribution
   - SKU insights

6. **Order Status Overview** ✅
   - Fulfillment metrics
   - Return/cancellation rates
   - Delivery success rate

### Dashboard Components

**Sheet 1: Vrinda Store** (Raw Data)
- Complete transaction dataset
- 31,047 detailed records
- All customer and order attributes

**Sheet 2: Pivot Analysis**
- Monthly aggregations
- Order count summaries
- Revenue totals by month

**Sheet 3: Dashboard** (Visual Layer)
- Interactive charts
- KPI cards
- Dynamic filters
- Comparative analysis

---

## 🔬 Analysis

### Key Performance Indicators (KPIs)

```
📦 Total Orders: 31,047
💰 Total Revenue: ₹2.12 Crores (₹21,176,377)
📊 Average Order Value: ₹682.07
👤 Unique Customers: 28,437
✅ Delivery Success Rate: 92.25%
📍 States Covered: 20+ across India
🏪 Sales Channels: 8+ platforms
```

### Customer Behavior Analysis

**Purchase Patterns**
- **Single-item orders**: Predominant (Qty = 1)
- **Multi-item purchases**: Occasional
- **Repeat customers**: Tracked via Cust ID
- **B2B orders**: Limited (mostly B2C)

**Geographic Concentration**
- **Urban dominance**: Metro cities lead sales
- **State clusters**: Southern & Western India strong
- **PIN code diversity**: 1000+ unique delivery locations

### Channel Strategy

**Platform Effectiveness**
- **Marketplace dependency**: Heavy reliance on established platforms
- **Diversification**: Presence across multiple channels
- **Own website**: Minimal compared to marketplaces

### Product Mix

**Category Insights**
- **Ethnic wear focus**: Kurtas, Sets, Sarees dominate
- **Size standardization**: Wide range from S to 10XL
- **SKU variety**: Diverse product codes indicating large catalog

---

## 💡 Recommendations

### 🎯 Strategic Recommendations

1. **Expand High-Performing Channels**
   - Increase investment in Myntra and Ajio
   - Negotiate better terms with top platforms
   - Consider exclusivity deals

2. **Geographic Expansion**
   - Target underperforming states
   - Focus on tier-2 city penetration
   - Strengthen logistics in Northeast region

3. **Customer Retention**
   - Implement loyalty programs for repeat customers
   - Personalized recommendations based on age groups
   - Gender-specific marketing campaigns

4. **Seasonal Planning**
   - Stock up for peak months (March, May, July)
   - Festival-focused inventory management
   - Pre-season promotional campaigns

5. **Product Strategy**
   - Expand popular categories (Kurtas, Sets)
   - Introduce new sizes based on demand patterns
   - Phase out slow-moving SKUs

### 📊 Data-Driven Actions

**Immediate (0-3 months)**
- Reduce cancellation and return rates
- Improve delivery times in low-performing regions
- Optimize inventory for M/L sizes

**Short-term (3-6 months)**
- Launch targeted campaigns for male customers
- Expand product range in bestselling categories
- Strengthen presence on emerging platforms

**Long-term (6-12 months)**
- Build owned e-commerce platform
- Implement predictive analytics for demand forecasting
- Develop customer segmentation for personalized marketing

---

## 🛠️ Technical Details

### Tools & Technologies

- **Microsoft Excel**: Data analysis and visualization
- **Pivot Tables**: Data aggregation and summarization
- **Excel Charts**: Visual representations
- **Conditional Formatting**: Data highlighting
- **Data Validation**: Input controls
- **Formulas**: VLOOKUP, SUMIFS, COUNTIFS, Date functions

### Data Processing

**Transformations Applied**
- Date parsing to extract Month
- Age grouping (Teenager/Adult/Senior)
- Status categorization
- Channel standardization
- Currency formatting

**Calculations**
- Monthly revenue summaries
- Order count aggregations
- Average order values
- Fulfillment percentages
- Geographic distributions

---

## 📈 Dashboard Usage

### How to Use This Dashboard

1. **Open the Excel File**
   - Navigate to the "Dashboard" sheet
   - Enable macros if prompted

2. **Explore Filters**
   - Select Month to view period-specific data
   - Filter by Channel for platform analysis
   - Choose State for geographic insights

3. **Interpret Visualizations**
   - Hover over charts for detailed values
   - Compare trends across different dimensions
   - Identify patterns and outliers

4. **Export Reports**
   - Take screenshots of key insights
   - Copy data tables for presentations
   - Use pivot tables for custom analysis

---

## 🎓 Learning Outcomes

### Skills Demonstrated

✅ **Data Cleaning**: Handled 31K+ records with consistency  
✅ **Excel Proficiency**: Advanced formulas and pivot tables  
✅ **Data Visualization**: Created interactive dashboards  
✅ **Business Analytics**: Translated data into insights  
✅ **Statistical Analysis**: Trend identification and pattern recognition  
✅ **Storytelling**: Presented findings effectively  

### Business Impact

- **Actionable Insights**: Clear recommendations for stakeholders
- **Revenue Optimization**: Identified high-value segments
- **Operational Efficiency**: Highlighted process improvements
- **Strategic Planning**: Data foundation for 2023 roadmap

---

## 📞 Contact & Connect

### Project Creator

**Hanzala Raja**  
Data Analyst | Business Intelligence Enthusiast

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/hanzalaraja)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ThAnalyser)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your.email@example.com)

---

## 📄 License & Usage

This project is part of my data analytics portfolio. Feel free to:
- ✅ Use for learning and reference
- ✅ Adapt for similar projects
- ✅ Share with attribution

**Please provide credit when using this work:**
```
Vrinda Store Analysis by Hanzala Raja
https://github.com/ThAnalyser
```

---

## 🌟 Acknowledgments

- **Data Source**: Vrinda Store operational data
- **Tools**: Microsoft Excel
- **Inspiration**: Real-world e-commerce analytics challenges

---

<div align="center">

**⭐ Star this project if you found it helpful!**

Made with ❤️ and 📊 by Hanzala Raja

</div>
