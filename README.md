# 📊 SuperStore Sales Dashboard (Power BI)

## 📌 Project Overview  
This Power BI project analyzes and visualizes SuperStore sales data to uncover key business insights and forecast future performance. The dashboard provides a comprehensive overview of **sales trends, profits, customer segments**, and includes a **15-day sales forecast**.

---

## 🎯 Objectives  
- Analyze sales performance across **regions, categories, and customer segments**  
- Identify high-performing **states, ship modes, and products**  
- Track **monthly trends in sales and profit** over time  
- Forecast **future sales for 15 days** using time series techniques  
- Build an **interactive dashboard** for real-time insights and decision-making  

---

## 📊 Dashboard Highlights

### 📍 Page 1 – Sales Overview  
- **KPIs**: Total Sales (1.6M), Orders (22K), Profit (175K), Avg Ship Time (4 days)  
- **Sales by**:
  - 🗂️ Region (West 33%, East 29%, Central 22%, South 16%)  
  - 💳 Payment Mode (COD 43%, Online 35%, Cards 22%)  
  - 👥 Segment (Consumer 48%, Corporate 33%, Home Office 19%)  
  - 🚚 Ship Mode (Standard Class leads with 0.91M)  
- **Monthly Trends**:
  - 📈 Monthly Sales and Profit Year-over-Year  
- **Top Categories/Sub-Categories**:
  - Categories: Office Supplies, Technology, Furniture  
  - Sub-categories: Phones, Chairs, Binders, Storage

### 📍 Page 2 – Sales Forecast (15 Days)  
- Forecast based on past sales trends using **time series decomposition**  
- Highlights upcoming growth or dips in sales  
- Interactive zoom slider to explore short-term movements  
- **Top States by Sales**: California (0.34M), New York, Texas, Washington, etc.

---

## 🛠️ Tools & Technologies  

| Tool        | Purpose                        |
|-------------|--------------------------------|
| Power BI    | Dashboard creation & visualization |
| DAX         | Custom calculations and KPIs   |
| Power Query | Data transformation and shaping |
| Excel/CSV   | Data source format             |

---

## 🗂️ Folder Structure  

```
├── SuperStore Sales Dashboard.pbix # Power BI dashboard file

├── SuperStore_Sales_Dataset.csv # Source data
```

## 📌 Key Insights
- The **West** region generated the highest revenue
- **Consumer** segment is the largest contributor to sales
- **Standard Class** dominates ship mode preferences
- **Phones** and **Chairs** lead in sub-category revenue
- **California** is the top performing state by revenue
