# 📘 Power BI Chart Practice – Visuals with Description and Examples

A visual revision notebook for understanding when and how to use Power BI visuals, with actual examples from practice (`My prac` folder).

---

### 📊 Area Chart  
**📝 Description:**  
Used to represent quantitative data over time. Stacked area charts show part-to-whole relationships.  

**🧠 Use When:**  
- Showing trends over time.  
- Demonstrating volume or cumulative data.  

![Area](./Area.png)

---

### 📊 Bar Chart  
**📝 Description:**  
Displays data with rectangular bars. Ideal for comparing values across categories.

**🧠 Use When:**  
- Comparing values horizontally.  
- Dealing with long category labels.  

![Bar Chart](./Bar%20Chart.png)

---

### 📊 Clustered Bar Chart  
**📝 Description:**  
Groups bars by category, showing subcategories side by side.  

**🧠 Use When:**  
- Comparing multiple subcategories per main category.  

![Cluster Bar](./Cluster%20Bar.png)

---

### 📊 Clustered Column Chart  
**📝 Description:**  
Vertical version of clustered bar. Emphasizes category over subcategory.

**🧠 Use When:**  
- Grouped comparisons with vertical emphasis.  

![Cluster Column](./Cluster%20Column.png)

---

### 📊 Column Chart with Legend  
**📝 Description:**  
Includes a legend to distinguish series values (e.g., by region, product type).

**🧠 Use When:**  
- Charting multiple data series with different colors.  

![Column Chart legend](./Column%20Chart%20legend.png)

---

### 📊 Column Chart – Small Multiples  
**📝 Description:**  
Visual split into small panels based on category fields.

**🧠 Use When:**  
- Viewing patterns or trends across multiple groups.

![Column Chart small multiples](./Column%20Chart%20small%20multiples.png)

---

### 🌳 Decomposition Tree  
**📝 Description:**  
AI-powered visual for drilling down into data and understanding root causes.  

**🧠 Use When:**  
- You want to explore contributing factors behind a value.

![Decomposition Tree](./Decomposition%20Tree.png)

---

### 📉 Funnel Chart  
**📝 Description:**  
Represents stages in a process (like a sales funnel).  

**🧠 Use When:**  
- Showing reduction across sequential stages.  

![Funnel Chart](./Funnel%20Chart.png)

---

### ⏱ Gauge Chart  
**📝 Description:**  
Shows progress toward a goal with a needle indicator.  

**🧠 Use When:**  
- Tracking performance against target.  

📌 **Formulas used:**  
```DAX
Minimum Value = 0.1 * SUM(Sheet1[Sales])  
Target Value = 0.15 * SUM(Sheet1[Sales])  
Maximum Value = 0.25 * SUM(Sheet1[Sales])
