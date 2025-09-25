# Retail Sales Analytics & Customer Insights Dashboard
Built an end‑to‑end Sales and Customer Insights project: Python data cleaning and RFM, SQLite SQL analytics, and a 3‑page Power BI dashboard showing KPIs, Top customers, New vs Repeat, and Region performance; repo includes reproducible notebooks and screenshots for rapid review.

Problem and outcome:
⦁	Goal: Clean retail orders, build core KPIs, and ship a three‑page Power BI dashboard to explain revenue drivers, customers, and regions.
⦁	Result: 3 report pages with KPIs, time trend, Top customers, New vs Repeat, and Region map/table; reproducible notebooks for data prep and SQL analytics.

Data and steps:
⦁	Data: List of Orders, Order Details, Sales target (2018–2019) placed in data/raw.
⦁	Steps: Step1 profiling, Step2 cleaning/features exporting star‑like CSVs, Step3 SQLite analytics views powering visuals.

How to run:
⦁	pip install -r requirements.txt, then run notebooks/Step2.ipynb to regenerate cleaned CSVs and notebooks/Analytics-Queries.ipynb to export view CSVs for quick validation.
⦁	Open Power BI file or use the three screenshots with the measures listed to review outputs if PBIX isn’t shared; replicate visuals using CSVs in data/cleaned.

Key KPIs to verify:
⦁	Total Revenue, Total Profit, Total Orders, Avg Order Value, Items per Order; cross‑check card totals vs v_revenue_by_month from Analytics-Queries.ipynb.

Files:
⦁	notebooks/Profiling.ipynb , notebooks/features-star-CSVs.ipynb , notebooks/Analytics-Queries.ipynb
