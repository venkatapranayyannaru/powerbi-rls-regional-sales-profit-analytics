# RLS-Enabled Regional Sales & Profit Analytics | Power BI

An interactive Power BI dashboard for a retail organisation selling technology and office supplies across regions in India. It tracks sales, profit, customer behaviour and shipping performance, and uses Row-Level Security so each Regional Manager sees only their own region.

## Tools Used
- Power BI Desktop (Power Query, DAX, data modelling)
- Excel (Superstore retail dataset)

## Project Phases
1. **Data Import & Cleaning:** loaded the dataset, fixed data types, removed blanks and duplicates, created calculated columns such as Delivery Days
2. **Data Modelling & DAX:** built a star schema with a Date table and measures for Total Sales, Total Profit, Profit %, Total Orders, Discount % and Delivery Days
3. **Dashboard Development:** built a 4-page report
4. **Advanced Features:** Row-Level Security, bookmarks, drill-through, custom tooltips
5. **Final Report & Presentation:** report, PPT deck and insight summary

## Dashboard Pages
- **Sales Overview:** KPIs, category and sub-category breakdown, sales by state map, monthly trend, top and bottom products
- **Customer Insights:** customer segments, top and bottom customers, region vs customer sales, drill-through to customer profile
- **Product & Discount Impact:** discount % vs profit scatter plot, product ranking, delivery time analysis
- **Region & Manager View:** Region > State > City drill-down, regional profit comparison, trend charts, navigation buttons

## Key Features
- Static Row-Level Security by Regional Manager
- Bookmarks and navigation buttons
- Custom tooltips for customer and product details
- Drill-through pages

## Files in This Repository
- `Power-Bi Project DA.pbix`: the Power BI report file
- `RLS_Enabled_Regional_Sales_Profit_Final_Submission_Report.docx`: full project report
- `RLS_Sales_Profit_Analytics.pptx`: presentation deck
- `Final insight summary.docx`: summary of insights and recommendations

## Author
Venkata Pranay Yannaru | Data Analyst Intern
