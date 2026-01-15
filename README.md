# 📊 Google Looker Studio Lab - Interactive Customer Analytics Dashboard

<p float="left">
    <img src="https://images.credly.com/size/680x680/images/31a24eb9-5fb6-4d3b-b2be-c286c3cc3489/Coursera_20Data_20Engineering_20Professional_20Cert_20V3.png" width="300" />
    <img src="https://github.com/Willie-Conway/Interactive-Customer-Analytics-Dashboard/blob/6ed28372627cdacd0b5a6c889baa91d6de8a4b85/Interactive%20Customer%20Analytics%20Dashboard/Screenshots/Customer%20Analytics.png" width="300" />
</p>

![Google Looker Studio](https://img.shields.io/badge/Google_Looker_Studio-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Data Visualization](https://img.shields.io/badge/Data_Visualization-FF6B6B?style=for-the-badge&logo=plotly&logoColor=white)
![Dashboard Analytics](https://img.shields.io/badge/Interactive_Dashboard-008DE4?style=for-the-badge&logo=dash&logoColor=white)
![Business Intelligence](https://img.shields.io/badge/Business_Intelligence-FF9E0F?style=for-the-badge)
![Customer Analytics](https://img.shields.io/badge/Customer_Analytics-3498DB?style=for-the-badge)

## 🎯 Project Overview

This Looker Studio project demonstrates advanced business intelligence skills through comprehensive customer loyalty program analysis. As a Data Visualization Specialist, I created an interactive multi-page dashboard that transforms raw customer transaction data into actionable business insights using Google's Looker Studio platform.

<p float="left">
    <img src="Screenshots/Page1_Product_Sales.png" width="300" />
    <img src="Screenshots/Page2_Customer_Analytics.png" width="300" />
    <img src="Screenshots/Page3_City_and_Sales_Insights" width="300" />
    <img src="Screenshots/Page4_Geographic_Insights.png" width="300" />
    <img src="Screenshots/City_and_Sales_Performance.png" width="300" />
    <img src="Screenshots/Page6_Regional_Revenue_Map.png" width="300" />
    <img src="Screenshots/Page7_Revenue_Fluctuations_Across_Countries.png" width="300" />
</p>

## 📊 Live Dashboard

[![Looker Studio](https://img.shields.io/badge/📊_View_Interactive_Dashboard-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://lookerstudio.google.com/s/lz8wjFuj5Nw) ![Preview](https://img.shields.io/badge/Preview-F97316?style=for-the-badge&logo=google&logoColor=white)
![Google Looker Studio Customer Analytics]()



## 📁 Project Structure

```
📂 Interactive-Customer-Analytics-Dashboard/
│
├── 📂 Data/
│   ├── CustomerLoyaltyProgram.csv    # Primary dataset (1,000+ records)
│   ├── cust_loyalty_table.csv        # Transaction data subset
│   └── cust_table.csv                 # Customer demographic data
│
├── 📂 Screenshots/
│   ├── Page1_Product_Sales.png
│   ├── Page2_Customer_Analytics.png
│   ├── Page3_City_Sales_Performance.png
│   ├── Page4_Geographic_Insights.png
│   ├── Page5_City_Sales_Performance
│   ├── Page6_Regional_Revenue_Map.png
│   └── Page7_Revenue_Fluctuations_Across_Countries.png
│
├── 📜 README.md                         # This documentation
└── 📜 Simple_Dashboard.pdf             # Dashboard documentation
```

## 📈 Lab Exercises & Visualizations

### **Exercise 1: Multi-Page Dashboard Configuration**
- **Page Customization**: Professional blue background with landscape layout
- **Multi-Page Structure**: 4 distinct analytical pages with logical organization
- **Page Management**: Renamed pages (A - Product Sales, B - Customer, etc.)
- **Navigation Setup**: Intuitive page switching and management system

### **Exercise 2: Advanced Data Blending & Analysis**
- **Data Integration**: Uploaded and configured 3 separate CSV data sources
- **Table Relationships**: Established Left Outer Join on Customer ID
- **Blended Bar Chart**: Gender-based quantity sold analysis with dual datasets
- **Dynamic Aggregation**: Implemented SUM/AVG metric toggling with sorting

### **Exercise 3: Interactive Controls Implementation**
- **Drop-down Controls**: Gender selection for dynamic chart filtering
- **Fixed-size Lists**: Product line selection with checkbox interface
- **Advanced Filters**: Year-based and country exclusion filters
- **User Testing**: Validated all controls in View mode for optimal UX

### **Exercise 4: Advanced Visualization Types**
- **Geographic Bubble Map**: City-based sales distribution with product line colors
- **Interactive Heatmap**: Quantity sold density visualization with satellite layer
- **Hierarchical Treemap**: Country → Province → City drill-down analysis
- **Temporal Slider**: Year range selection (2017-2020) for time-based filtering

## 🔍 Key Business Insights

### **Customer Demographics Analysis**
- **Gender Purchasing Patterns**: Distinct quantity sold differences between males and females
- **Regional Performance**: Geographic hotspots for different product categories
- **Customer Segmentation**: Loyalty status impact on purchasing behavior

### **Product Performance Metrics**
- **Revenue vs Unit Price**: Correlation analysis across different cities
- **Product Line Comparison**: Performance variations across categories
- **Seasonal Trends**: Year and quarter-based sales patterns

### **Geographic Distribution Insights**
- **Sales Concentration**: Major cities driving majority of revenue
- **Regional Preferences**: Product line popularity by geographic area
- **Market Penetration**: Customer density mapping for expansion planning

## 🛠️ Technical Skills Demonstrated

### **Looker Studio Proficiency**
![Looker Studio](https://img.shields.io/badge/Looker_Studio-Expert-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Data Blending](https://img.shields.io/badge/Data_Blending-FF6384?style=for-the-badge)
![Interactive Controls](https://img.shields.io/badge/Interactive_Controls-27AE60?style=for-the-badge)
![Geospatial Visualization](https://img.shields.io/badge/Geospatial_Viz-8E44AD?style=for-the-badge)
![Dashboard Design](https://img.shields.io/badge/Dashboard_Design-3498DB?style=for-the-badge)

### **Advanced Visualization Techniques**
- **Multi-Table Data Blending** with Left Outer Joins
- **Google Maps Integration** with bubble and heatmap layers
- **Hierarchical Data Representation** using treemaps
- **Dynamic Parameter Controls** for user-driven exploration
- **Professional Color Schemes** with consistent branding

### **Dashboard Architecture**
- **Multi-Page Navigation** with logical information flow
- **Responsive Design Principles** for different screen sizes
- **User-Centric Interface** with intuitive control placement
- **Data Hierarchy Implementation** for drill-down capabilities
- **Filter Propagation** across related visualizations

## 📊 Data Dictionary

| Column | Description | Type | Source Table |
|--------|-------------|------|--------------|
| `Customer_ID` | Unique customer identifier | String | Both Tables |
| `Full_Name` | Customer's complete name | String | cust_table |
| `Gender` | Customer gender | String | cust_table |
| `City` | Customer location city | String | Both Tables |
| `Country` | Customer location country | String | Both Tables |
| `Order_Year` | Transaction year (2015-2020) | Integer | cust_loyalty_table |
| `Product_Line` | Product category | String | cust_loyalty_table |
| `Quantity_Sold` | Units sold per transaction | Integer | cust_loyalty_table |
| `Unit_Sale_Price` | Price per unit | Float | cust_loyalty_table |
| `Revenue` | Total transaction revenue | Float | cust_loyalty_table |
| `Loyalty_Status` | Customer loyalty level | String | cust_loyalty_table |
| `Months_As_Member` | Loyalty program duration | Integer | cust_loyalty_table |

## 🚀 How to Use This Dashboard

### **For Business Stakeholders**
1. **Start with Product Sales Page**: Review overall sales performance
2. **Analyze Customer Demographics**: Understand purchasing patterns by gender
3. **Explore Geographic Distribution**: Identify sales hotspots and opportunities
4. **Use Interactive Controls**: Filter data by year, product line, and location

### **For Data Professionals**
1. **Study Data Blending**: Examine the Left Outer Join implementation
2. **Analyze Control Configuration**: Review drop-down and slider setups
3. **Evaluate Visualization Choices**: Understand chart type selection rationale
4. **Replicate Techniques**: Apply similar approaches to your projects

### **For Looker Studio Learners**
1. **Follow Exercise Sequence**: Complete the 4 exercises step-by-step
2. **Experiment with Controls**: Test all interactive elements
3. **Modify Visualizations**: Practice with different chart configurations
4. **Extend Functionality**: Add additional data sources or visualizations

## 🏆 Project Achievements

✅ **4 Comprehensive Dashboard Pages** with distinct analytical focuses  
✅ **10+ Advanced Visualization Types** including maps and treemaps  
✅ **Multiple Data Source Integration** with seamless blending  
✅ **Complete Interactive Controls Suite** for user exploration  
✅ **Professional Dashboard Design** following BI best practices  
✅ **Geospatial Analysis Implementation** with Google Maps integration  

## 📋 Lab Prerequisites & Setup

### **Required Platform**
- Google Account (free)
- Looker Studio access (available at no charge)
- Web browser with internet connection

### **Data Sources**
- **Primary**: `CustomerLoyaltyProgram.csv` (IBM Cognos Analytics showcase)
- **Derived**: `cust_loyalty_table.csv` and `cust_table.csv` subsets
- **Total Records**: 1,000+ customer transactions
- **Time Range**: 2015-2020 data

## 📝 Methodology

### **1. Data Preparation & Import**
- Uploaded 3 CSV files to Looker Studio
- Validated data types and field formats
- Created calculated fields for enhanced analysis

### **2. Page Configuration & Structure**
- Established 4-page dashboard architecture
- Applied consistent color scheme and styling
- Implemented professional layout principles

### **3. Advanced Data Blending**
- Configured table relationships using Customer ID
- Implemented Left Outer Join for comprehensive analysis
- Created blended data sources for cross-table queries

### **4. Interactive Control Implementation**
- Added user controls for dynamic filtering
- Configured filter propagation across visualizations
- Tested all controls in View mode for optimal UX

### **5. Advanced Visualization Development**
- Created geographic maps with multiple layers
- Implemented hierarchical treemaps with drill-down
- Added temporal filtering with slider controls

## 🎨 Design Choices & Best Practices

### **Color Scheme**
- **Primary**: Professional blue theme across all pages
- **Highlighting**: Contrast colors for important metrics
- **Consistency**: Uniform palette for brand recognition

### **Layout Architecture**
- **Logical Flow**: Progressive analysis from overview to details
- **Information Hierarchy**: Clear visual hierarchy for data presentation
- **White Space Management**: Optimal spacing for readability

### **User Experience**
- **Intuitive Navigation**: Clear page switching and controls
- **Responsive Design**: Adaptable to different screen sizes
- **Accessible Design**: Color choices for visibility

## 🔗 Additional Resources

- [Google Looker Studio Documentation](https://cloud.google.com/looker-studio)
- [IBM Cognos Analytics Resources](https://www.ibm.com/products/cognos-analytics)
- [Data Visualization Best Practices](https://www.tableau.com/learn/articles/data-visualization)
- [Business Intelligence Trends](https://www.gartner.com/en/information-technology/insights/business-intelligence-analytics)

## 👥 Acknowledgments

- **IBM** for the comprehensive Business Intelligence curriculum
- **Google** for providing Looker Studio as a free BI platform
- **Coursera** for the structured learning environment
- **Business Intelligence Community** for best practices and inspiration

## 📄 License

This educational project uses IBM's showcase dataset for learning purposes. The dashboard implementation and visualization techniques are shared for educational and portfolio development.

---

⭐ **If you find this dashboard insightful, please share feedback!** ⭐

*Lab Completed: December 2025*  
*Last Updated: December 2025*
