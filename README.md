# 🍽️ Zomato Insight Dashboard – Power BI  
**Designed & Developed by Lija Sahoo**

---

## 📌 Project Overview  
An interactive Power BI dashboard built using a Zomato restaurant dataset to uncover patterns in customer satisfaction, restaurant trends, delivery performance, and cuisine popularity. Designed for stakeholders who want actionable insights through clean visuals.

---

## 📊 Dashboard Features & Insights  
- 🔝 **Top Restaurants** by order amount  
- 😊 **Customer Satisfaction**: Ratings, Order Value, Delivery Time  
- 🍲 **Cuisine Popularity** breakdown by city  
- 📈 **Yearly Order Trends** visualization  
- ⭐ **Ratings Distribution** by restaurant  
- 🕒 **Delivery Time by Location** heatmaps and averages

---

## 🖼️ Dashboard Preview  
![Zomato Dashboard Preview](Screenshots/dashboard-preview.png)

---

## 🛠 Technologies Used  
- 🧠 **Power BI** – for building the dashboard  
- 🔄 **Power Query** – for cleaning and shaping data  
- 📐 **DAX** – to create dynamic KPIs and calculated fields  
- 📊 **Excel** – as the raw dataset source  
- 🎨 **Figma/Canva** – for UI polish (optional)

---

## 📂 Dataset Information  
- 📌 **Source**: Zomato restaurant data (open-source)  
- 🔢 **Entries**: 10,000+ restaurant records  
- 📊 **Key Fields**:
  - Restaurant Name, Location, City  
  - Cuisine, Rating, Votes, Cost for Two  
  - Delivery Time, Order Value, Online Delivery  
- 📁 **Categories Analyzed**:
  - Cities (50+)  
  - Cuisine Types (e.g., Indian, Chinese, Italian)  
  - Rating Scale (1.0–5.0)  
  - Delivery Duration Groups

---

## 🔄 Data Processing Workflow  
- ✅ Removed nulls and duplicates  
- 🔤 Standardized city and cuisine text fields  
- 📅 Created columns for year and time-based analysis  
- 🍴 Split multiple cuisines into separate entries  
- 🧮 Built rating and cost categories for filtering

---

## 🧠 Data Modeling Approach  
- 🌟 **Star schema** structure  
- 📊 **Fact Table**: `Zomato Orders`  
- 📚 **Lookup Tables**:
  - Cities  
  - Cuisine Types  
  - Ratings  
  - Time Groups  
- ➕ **DAX Measures**:
  - Total Orders  
  - Average Delivery Time  
  - Most Voted Restaurants  
  - Year-wise Growth  

---

## 📈 Key Results & Evaluation  
- 🏙️ Top Cities: Delhi, Mumbai, Bangalore lead in orders  
- 🚚 Fastest Delivery: Metro areas dominate  
- 🍛 Popular Cuisines: North Indian, Chinese top the charts  
- ⭐ Ratings: 4.0+ rating group dominates user trust  
- 💸 Price Band: Medium pricing attracts most customers  
- 📆 Orders: Growth observed post-2019

---

## 📘 Usage Instructions  
- ⬇️ Download the `.pbix` file  
- 🖥️ Open in **Power BI Desktop**  
- 📂 Use available tabs:
  - **Welcome**  
  - **Overview**  
  - **Explore**  
- 🔍 Use slicers for:
  - City, Cuisine, Year, Delivery Time, Rating  
- 🖱️ Hover over visuals for additional details

---

## 🔮 Future Enhancements  
- 🔗 Real-time Zomato API integration  
- 🗺️ Geo-visualization of delivery zones  
- 🧠 Predictive analytics with Power BI Forecast  
- 🔐 Deploy with Row-Level Security (RLS)  
- 👤 Add customer persona segmentation

---

## 🔗 Connect With Me  
- 💼 [LinkedIn](linkedin.com/in/lija-sahoo-4b3389259)  
- 💻 [GitHub](https://github.com/Lija12sahoo)  
- 📧 Email: lijasahoo@example.com

---

© 2025 | Lija Sahoo  
