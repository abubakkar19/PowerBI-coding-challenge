# 🛍️ Retail Business Performance Dashboard

This project presents an end-to-end Power BI analysis of retail sales data across major cities and states in India.  
The dataset includes customer details, product information, pricing, discounts, and calculated total sales, enabling a complete retail performance study.

---

## 📌 About the Dataset
The dataset contains **1500+ retail transactions** from customers across different Indian cities and states.  
It includes key metrics such as:

- Customer demographics (Name, Gender, City, State)  
- Product Category, Product Name, Brand  
- Quantity, Unit Price, Discount%  
- Calculated Total Amount  
- Several missing values for cleaning practice  
- Naturally occurring duplicate rows (for Power Query transformation)

This dataset is ideal for practicing **Power BI data cleaning, modeling, DAX, dashboard design, and storytelling**.

---

## 🛠️ Data Cleaning Performed

### ✔ Handling Missing Values
- **Quantity column** contained null values → Replaced with the **average quantity** using Power Query.
- **Unit Price column** had null values → Filled using the **average unit price** through Replace Values.
- **Discount% column** had null entries → Filled using the column’s average.
- **Total Amount** nulls recalculated using a **Custom Column formula**:  
  `Quantity * Unit_Price * (1 - Discount_%/100)`

### ✔ Other Cleaning Steps
- Data types corrected for numerical columns.
- Duplicate rows identified and removed.
- Columns renamed and sorted for clarity.

---

## 📊 Dashboard Overview

The dashboard provides insights on:

- ⭐ Total Sales Amount  
- ⭐ Total Transaction Count  
- ⭐ State-wise & City-wise Sales Performance  
- ⭐ Product Category & Brand Analysis  
- ⭐ Gender-based Customer Insights  
- ⭐ Quantity & Discount Impact on Sales  
- ⭐ Slicer-based dynamic filtering  

Key KPIs displayed include:

- **Sum of Total Amount**
- **Total Count**
- **Tamil Nadu Total Amount**

---

## 📈 Insights Discovered

- Maharashtra, Karnataka, and Uttar Pradesh contribute the highest revenue.  
- Clothing and Accessories are the most purchased product categories.  
- Brands like Snitch, H&M, Boat, Adidas, and Levis demonstrate strong customer demand.  
- Tamil Nadu alone contributes over ₹629K in sales, indicating strong regional performance.  
- Applying slicers shows large shifts in KPI values, revealing strong segmentation opportunities.

---

## 🎯 Conclusion
The analysis highlights strong demand in metro cities and high-performing product categories, with brand preferences shaping customer purchasing behavior.  
These insights support improved decision-making for pricing, inventory, and marketing strategies.

---

## 🧰 Tools Used
- **Power BI Desktop**
- **Power Query**
- **DAX (Data Analysis Expressions)**
- **Excel (for initial data review)**

---

## 🙌 Author
**Abubakkar**  
Power BI Enthusiast | Data Analytics Learner  
