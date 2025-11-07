# 🛒 Retail Sales Analysis

![Retail Sales Dashboard] 

<img width="1304" height="742" alt="dashboard" src="https://github.com/user-attachments/assets/f72d832b-f85a-4f72-a05a-857d0addc825" />

*Comprehensive Power BI Dashboard showcasing key metrics and performance insights from the merged dataset.*

## Overview

Retail businesses generate large amounts of transactional data every day — sales, returns, promotions, inventory movements and more. This project analyzes retail sales data to uncover patterns and trends that drive performance. The analysis was done using **Python** for data preprocessing and **Power BI** for visualization and storytelling.

---

## 🎯 Project Summary

- The raw data consisted of **8 separate datasets** covering customers, orders, products, reviews, payments, and logistics.  
- Using **Python (Pandas and NumPy)**, all 8 datasets were cleaned and **merged into a single comprehensive dataset** based on relational keys (order IDs, customer IDs, product IDs).  
- The **merged dataset** served as the foundation for developing a detailed **Power BI Dashboard** that visualizes performance across sales, delivery, and customer metrics.  
- Key metrics visualized include: total revenue, total orders, customer distribution, payment modes, average delivery days, and average review scores.

---

## 📈 Dashboard Overview

The **Retail Sales & Performance Insights Dashboard** (see image above) provides a 360° view of retail operations. It enables users to filter and analyze trends across time, geography, and product categories.

### Key Highlights from the Dashboard
- **Total Orders:** 99K  
- **Total Revenue:** 16.6M  
- **Total Customers:** 95K  
- **Average Review Score:** 4.02  
- **Average Delivery Days:** 11.76  
- **Total Freight Value:** 2.36M  

### Visual Sections
1. **Revenue by Product Category:** Identify which product categories contribute most to overall sales.
2. **Revenue by Payment Type:** Breakdown of customer payment preferences (credit card, boleto, etc.).
3. **Revenue by Year:** Year-on-year growth analysis (2016–2018).
4. **Delivery Insights:** Average delivery days by state and percentage of delayed vs. on-time deliveries.
5. **Customer Behavior:** Average review scores by category, highlighting customer satisfaction trends.

---

## 🧰 Tools & Technologies

- **Python** — for data cleaning, preprocessing, and merging 8 datasets.
- **Pandas, NumPy** — for efficient data manipulation and integration.
- **Power BI** — for interactive dashboard creation and performance insights.
- **Excel** — for validation and quick checks.
- **GitHub** — for version control and collaboration.

---

## 🧪 Data Processing Workflow

1. **Data Cleaning & Preparation**  
   - Removed null values and duplicates from all 8 datasets.  
   - Standardized column names and data formats.  
   - Ensured consistency between relational IDs (customer_id, order_id, product_id).

2. **Data Merging**  
   - Joined datasets using common keys: `order_id`, `customer_id`, `product_id`.  
   - Combined the datasets into a **single master dataset** with all necessary dimensions (orders, reviews, products, payments, deliveries).  
   - Saved the cleaned, merged dataset for Power BI integration.

3. **Feature Engineering**  
   - Added computed fields like: `Delivery_Duration`, `Profit Margin`, `Review_Impact_Score`.  
   - Categorized payment types, delivery flags, and customer states.

4. **Power BI Dashboard Development**  
   - Imported the merged dataset into Power BI.  
   - Created data relationships, measures, and KPIs.  
   - Designed visualizations: clustered bar charts, cards, line charts, and maps.

---

## 📊 Insights Extracted

- **Top Product Categories:** Electronics, beauty, and fashion contribute the most to revenue.
- **Customer Review Trends:** Average review score is consistently above 4.0, indicating strong customer satisfaction.
- **Delivery Analysis:** Around 16% of orders are delayed; optimization could improve average delivery time.
- **Payment Behavior:** Over 75% of customers use credit cards; digital payment channels dominate.
- **Revenue Growth:** Total revenue grew steadily between 2016 and 2018, indicating increasing order volumes.

---

## 🚀 How to Use

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Komerlasriram/Retail-Sales-Analysis.git
   cd Retail-Sales-Analysis
   ```

2. **Install Dependencies**
   ```bash
   pip install pandas numpy
   ```

3. **Run Data Preparation Scripts (if available)**  
   Clean and merge the datasets into one CSV or Excel file.

4. **Open Power BI Dashboard**  
   - Extract the `.pbix` file from `Power bi File.zip`.  
   - Load the merged dataset.  
   - Explore dashboards interactively (filter by category, region, payment type, etc.).

---

## 📬 Contact

**Author:** Komerla Sriram  
📧 Email: [komerlasriram2002@gmail.com](mailto:komerlasriram2002@gmail.com)  
💼 LinkedIn: [linkedin.com/in/KomerlaSriram](https://linkedin.com/in/KomerlaSriram)

---

## 🌟 Conclusion

This project demonstrates how multiple data sources can be unified and analyzed to generate clear, data-driven insights for the retail industry. The final Power BI dashboard not only visualizes KPIs but also empowers business leaders to track performance, detect inefficiencies, and make better strategic decisions.

> *“Turning multiple datasets into one unified story of retail success through data.”*

