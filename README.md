# 📌 Compensation Analysis & Salary Benchmarking Report

## 1. Project Overview
This project focuses on **analyzing employee compensation**, benchmarking salaries against market data, and optimizing bonuses. Using **advanced Excel techniques**, an **interactive Compensation Dashboard** was developed to help HR teams **identify salary discrepancies, optimize pay structures, and ensure fair compensation**.

---

## 2. Data Collection & Preparation
To ensure accurate analysis, **two datasets** were used:

### **Employee Compensation Data (10,000+ records)**
- Contains fields such as **Base Salary, Bonus %, Overtime Hours, Total Compensation, and Experience**.  
- **Goal**: Identify salary trends and compare pay structures across departments.

### **Market Benchmark Data**
- Lists **average industry salaries per job title** for comparison.  
- **Goal**: Help HR teams **spot underpaid and overpaid employees**.

### 🛠 **Data Processing in Excel**
✅ **Power Query** automated **data cleaning**, ensuring there were no duplicates, missing values, or inconsistencies.  
✅ **Formula-Based Salary Calculation** was implemented:  
   ```
   Total Compensation = Base Salary + (Base Salary * Bonus %) + (Overtime Hours * Overtime Rate)
   ```  
✅ **Market salaries were dynamically fetched** using **VLOOKUP** and **INDEX/MATCH** for flexibility.

---

## 3. Advanced Excel Techniques Used
This project extensively used **advanced Excel functions** to transform raw data into a **fully interactive dashboard**.

### ✅ **Salary Benchmarking with VLOOKUP & INDEX/MATCH**
- **Compared employee salaries against market data**.
- Used **INDEX/MATCH instead of VLOOKUP** to handle **non-sequential job titles efficiently**.

### ✅ **Pivot Tables & Pivot Charts for Insights**
- Created **department-wise compensation summaries**.
- Used **Pivot Tables to analyze salary trends based on experience**.
- Developed **Pivot Charts (Bar, Scatter, and Pie)** to make insights **visually compelling**.

### ✅ **Conditional Formatting for Salary Insights**
- **Highlighted underpaid employees in RED** (earning **below 90%** of the market benchmark).
- **Marked highly paid employees in GREEN** (**earning 110%+** of the benchmark).
- **Bonus discrepancies were flagged**, helping HR **restructure incentives**.

### ✅ **Data Validation & Dropdowns for Filtering**
- Created **drop-down menus** to dynamically filter compensation data by:
  - **Department**
  - **Job Title**
  - **Experience Level**
- Allowed **instant insights** without manually changing the dataset.

### ✅ **Macros & VBA for Automation**
- **Developed a Macro** to:
  - **Auto-refresh Pivot Tables when data updates**.
  - **Recalculate total compensation & bonus allocations dynamically**.
- This **eliminated manual recalculations**, improving efficiency.

### ✅ **Excel Solver for Bonus Optimization**
- Used **Solver** to **redistribute bonuses based on budget constraints**.
- Ensured **high-performing employees receive fairer incentives**.
- Solver optimized:
  - **Total bonuses stay within company limits**.
  - **Bonus percentage per employee does not exceed 20%**.
  - **No employee receives a negative bonus adjustment**.

### ✅ **Scenario Analysis for HR Decision-Making**
- Developed **"What-If" Analysis** using **Data Tables**:
  - **Simulated salary hikes** (e.g., **5% vs. 10% increase**).
  - **Analyzed different bonus distribution models**.
  - **Modeled salary adjustments based on inflation**.

---

## 4. Key Insights & Recommendations
The **Compensation Dashboard** provided **clear, data-driven insights** for HR teams:

👌 **30% of employees were underpaid compared to industry benchmarks.**  
👌 **IT & Finance departments had the highest total compensation.**  
👌 **Marketing had the most uneven bonus distribution.**  
👌 **Adjusting base salaries by 5% would align 80% of employees with market rates.**  
👌 **Implementing an optimized bonus structure would improve retention & motivation.**  

---

## 5. Final Deliverables
📊 **Interactive Compensation Dashboard** with real-time salary insights.  
📈 **Pivot Table Summary Reports** for data-driven HR decisions.  
🛠 **Automated salary benchmarking using Power Query & Solver.**  

---

## 6. Conclusion
This project highlights **advanced Excel skills** including **Power Query, Pivot Tables, Solver, VBA, and Scenario Planning** to **analyze, optimize, and automate salary benchmarking**. The **final dashboard provides actionable insights** for HR teams to **make informed compensation decisions, reduce pay gaps, and enhance workforce satisfaction**.

---

### 🚀 Next Steps
Would you like to enhance this further with **Power BI or Python automation**? Let me know how you'd like to improve it! 🚀

