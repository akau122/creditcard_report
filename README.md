# creditcard_report
This project analyzes **credit card customer profiles and transaction behavior** using **Power BI**.  
By combining customer demographics with transaction records, the dashboard delivers insights into **revenue drivers, spending patterns, and customer segments**, helping financial institutions design **data-driven marketing strategies**.  

---

## 🔹 Project Objectives  
- Understand **which customer groups drive the most revenue**  
- Analyze **transaction trends** (by card type, payment method, time period)  
- Segment customers by **age, income, education, and job type**  
- Identify **high-value customers** and untapped growth opportunities  
- Provide recommendations to improve **customer satisfaction and product adoption**  

---

## 🔹 Key Features of Dashboard  
- **KPIs:** Revenue, Transaction Volume, Transaction Amount, Interest Earned, Income, Satisfaction Score  
- **Segmentation:** Revenue by **job, education, income group, age group, marital status, card category**  
- **Trends:** Weekly and quarterly revenue trends with current vs. previous week comparisons  
- **Geography:** Top 5 states contributing to revenue  
- **Interactive Filters:** Quarter, income level, card category, gender  

---

## 🔹 DAX Measures Used  
- **Age Grouping** (20–30, 30–40, 40–50, 50–60, 60+)  
- **Income Grouping** (Low, Medium, High)  
- **Revenue Calculation** = Annual Fees + Transaction Amount + Interest Earned  
- **Current Week vs. Previous Week Revenue** using `CALCULATE` + `FILTER`  
- **Dynamic Week Number Extraction** for trend analysis 


