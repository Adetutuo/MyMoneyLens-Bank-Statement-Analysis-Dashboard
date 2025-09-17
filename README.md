# 💰 Bank Statement Analysis Dashboard

## 📌 Project Overview  
This project analyzes **three months of personal bank transactions** to uncover spending patterns, track income vs expenses, and highlight areas to cut back or save.  
It marks one of my first practical steps in transitioning from **Architectural Design** to **Data Analytics** — applying data skills to solve real-life problems.

---

## 🛠 Tools & Skills Used  
- **Excel** – data cleaning, transformation, and visualization  
- **Power Query** – handling raw statement data  
- **IF & SEARCH formulas** – transaction categorization logic  
- **PivotTables & Slicers** – interactive analysis and dashboards  

---

## 📊 Dashboard Preview  
![Dashboard Preview](dashboard_screenshot.png)

---

## 📁 Dataset  
[Download the Excel File](PROJECT_001.xlsx)

---

## 📈 Key Insights  
- **Large share of spending fell under “miscellaneous transfers”** with poor or no remarks, which limited accurate categorization.  
- **Monthly cash flow clarity:** Visuals showed clear patterns of inflow vs outflow across the three months.  
- **Top expense drivers identified:** recurring charges (e.g., bank fees, airtime/SMS) and transfers were the main outflows.  
- **Savings opportunity:** Identified categories where small cuts could meaningfully increase monthly savings.

---

## ⚡ Challenges & Lessons Learned  
- **Data quality is critical:** Missing or vague transaction remarks made categorization difficult — a reminder that better tagging/remarks (at source) improves analysis.  
- **Messy exports require preprocessing:** I handled merged rows, split remarks, and blank/spillover rows before analysis.  
- **Rule-based categorization has limits:** I used `IFS` + `SEARCH` logic to auto-tag transactions, but ambiguous descriptions still needed manual review.  
- **Iterative approach wins:** Building the dashboard helped expose new questions — and refining the data logic is an ongoing process.

---

## 🚀 Next Steps  
- Improve the categorization logic (expand keyword rules / use regex in Power Query).  
- Automate the ETL pipeline using **Power Query** or **SQL**.  
- Rebuild and publish the dashboard in **Power BI** for enhanced interactivity.  
- Add anonymized sample data and a step-by-step notebook describing the cleaning logic.

---

## 📁 Files in this Repository  
- `PROJECT_001.xlsx` – cleaned dataset (anonymized)  
- `dashboard_screenshot.png` – dashboard visualization image  
- `README.md` – this file

---

## 📝 Author  
**Adetutu Oluwasemilore**  
Data Analyst | Financial & Business Analytics | Excel · SQL · Power BI | Budgeting & Forecasting
[LinkedIn Profile]([https://www.linkedin.com](http://www.linkedin.com/in/adetutu-oluwasemilore-5a6b6a11a)) 
