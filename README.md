# Finance & Data Analytics Portfolio

You can click the project links below to open folders, view screenshots, or download files directly from this repository.


I am a results-driven finance and data analytics professional with a strong foundation in FP&A, controlling and business analysis. My expertise is in building practical, data-driven solutions such as interactive dashboards, driver-based models and SQL powered reports that help businesses monitor performance, forecast outcomes and make informed decisions. With a Master’s in International Business and hands-on experience across multiple tools and data environments, I focus on turning complex data into clear and actionable insights that support strategic growth.

Hi, I’m Ansar Mukhtar, a finance and data analytics professional with a Master’s in International Business and practical experience in FP&A, controlling, and business analysis.  

I create financial models, dashboards, and analytical tools that turn raw numbers into clear, actionable insights.  
This portfolio presents a selection of my work, covering budgeting and forecasting, Excel-based modeling, and SQL-driven financial reporting.

🔗 **Live Portfolio:** [GitHub Repository](https://github.com/ansarmukhtar/Portfolio)


---

## 📂 Projects

### [1. Budget vs Actuals Dashboard](Projects/bva_powerbi)
 
**Tools:** Power BI, DAX, Excel, SQL  

This interactive dashboard tracks revenue, costs, and variances by region, business unit, and product category.  
It includes month-over-month trends, variance analysis in both absolute and percentage terms, and gross margin KPIs.  
Users can filter results using dynamic slicers for time periods, regions, and product categories.

![BvA Dashboard](Assets/bva_dashboard_Screenshort.png)  

This dashboard started from clean CSVs for budget versus actuals and a calendar table. I connected the data on the date column, set correct data types, and wrote simple DAX measures for revenue, COGS, gross margin, and revenue variance versus budget. The visuals show monthly trends, variance by region, and KPI cards that update with slicers for region, business unit, and product category. The result is a quick month‑end view where variances are easy to spot and discuss in reviews.


---

### [2. Driver-Based Cash-Flow Model](Projects/cashflow_excel)
 
**Tools:** Excel (Formulas, Scenario Analysis)  

A 12-month cash-flow forecast that uses growth rates, COGS percentages, and working-capital assumptions such as DSO, DPO, and inventory days.  
It features a scenario sheet that allows changes in sales growth or payment terms to be tested easily, with automatic updates to forecast results.  
The model outputs the monthly net cash position and ending balance.

![Cash-Flow Model](Assets/cashflow_model_screenshot.png)  

This model began with a simple historical monthly P&L and key working capital metrics. I built a 12-month forecast driven by growth rate, COGS percentage, and DSO, DPO, and inventory days. Formulas calculate monthly revenue, COGS, operating expenses, changes in receivables, payables, and inventory, and ending cash balance. A scenario sheet allows quick adjustments to drivers so the forecast updates instantly, making it useful for planning different growth and payment-term situations.


[Download Model](Projects/cashflow_excel/driver_based_cashflow_model.xlsx)

---

### [3. SQL Finance Mart](Projects/sql_finance_mart)
  
**Tools:** SQLite, SQL, Data Modeling  

A small but complete database designed for finance analytics, containing tables for orders, customers, products, and general ledger transactions.  
The project demonstrates producing P&L by month, identifying top customers, and calculating revenue by region, with queries and results that can feed directly into BI tools.

This project uses a small SQLite database containing orders, customers, products, and general ledger transactions. I wrote queries to produce monthly revenue by region and a P&L by month, using account codes to separate revenue, COGS, and operating expenses. The outputs are exported to CSV so they can be used in BI tools or Excel. This setup simulates a finance data mart and shows how structured queries can quickly deliver reporting-ready datasets.


[View Queries](Projects/sql_finance_mart)

---

## How This Portfolio Was Built
Each project started with structured datasets prepared in CSV or SQLite formats.  
Data was checked for correct data types and cleaned where needed to ensure accuracy in analysis.  
In Power BI, relationships were created between fact and calendar tables, and DAX measures were written for key financial metrics.  
In Excel, formulas were set up to calculate forecasted cash flows based on growth, cost, and working capital drivers.  
In SQL, queries were written to join tables, aggregate results, and produce reporting-ready views.  
All files, screenshots, and descriptions were then organised into a clear GitHub structure so they can be easily reviewed and downloaded.


## Data Sources
All datasets used in this portfolio are synthetic or anonymised to protect confidentiality.  
They were created to simulate realistic finance scenarios, including budget vs actuals data, general ledger transactions, and sales orders with customer and product details.  
This ensures the focus is on demonstrating analytical and technical skills without exposing sensitive business information.

## Open to Opportunities
I am actively seeking roles in FP&A, Controlling, Business Analysis, and Data Analytics.  
If my work aligns with your needs, feel free to connect via LinkedIn or email.  
I am particularly interested in positions where I can combine financial expertise with data analytics to drive business insights and growth.


## 📬 Contact
**Email:** ansarsandhu74@gmail.com  
**LinkedIn:** https://www.linkedin.com/in/ansarmukhtar/  
**GitHub:** https://github.com/ansarmukhtar/Portfolio  

---

*All datasets are anonymised or synthetic and used for demonstration purposes only.*

## Usage
- Click project links to view the folders in GitHub.  
- Click image thumbnails to see a larger preview.  
- Use the download button (top right in GitHub file view) to save PBIX, Excel, or SQL files locally.  
- Power BI files require Power BI Desktop to open, Excel files require Microsoft Excel, and SQL files can be opened in any text editor or SQL client such as DB Browser for SQLite.


## Skills Demonstrated
- Financial Planning & Analysis (FP&A) and variance reporting  
- Power BI modeling, DAX calculations, and KPI design  
- Excel forecasting, scenario analysis, and driver-based modeling  
- SQL querying, P&L generation, and revenue analysis  
- Data cleaning, relationship modeling, and report documentation  
- GitHub project structuring and technical communication


