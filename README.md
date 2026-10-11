# Retail Sales & Business Performance Dashboard — Task 1

## Important data note
The task PDF did not include a source retail dataset. This project uses a **synthetic illustrative dataset** of 500 unique orders to demonstrate the workflow. Do not report these values as real-world company findings. Replace the data with an approved dataset if one was supplied separately.

## Deliverables
- `Task1_Retail_Sales_Dashboard.xlsx` — dashboard, raw-style data, cleaned data, summary tables, executive summary, README.
- `cleaned_retail_sales.csv` — cleaned dataset.
- `executive_summary.docx` — report and recommendations.
- `dashboard_screenshot.png` — dashboard preview.

## Workbook sheets
- **Dashboard:** KPI cards and charts for monthly revenue, regional revenue, category revenue, and customer segment.
- **Raw_Data:** source-style data including a few intentional data-quality issues for cleaning practice.
- **Clean_Data:** standardized records and derived time/margin fields.
- **Summary_Tables:** monthly, regional, category, product, segment, and channel aggregations.
- **Executive_Summary:** KPI snapshot, findings, recommendations, and limitations.
- **README:** methodology and refresh guidance.

## Cleaning performed
- Trimmed whitespace in text fields.
- Replaced missing customer segment with `Unknown`.
- Converted dates and numeric columns.
- Removed duplicate Order IDs.
- Added Month, Month Number, Year, and Profit Margin.

## Illustrative KPI results
- Revenue: ₹320,564.45
- Profit: ₹110,005.45
- Units sold: 3,958
- Unique orders: 500
- Profit margin: 34.3%

## Native PivotTables and interactivity
The summary tables are Pivot-style aggregated reports for compatibility. In Excel, select the `Clean_Data` table and choose **Insert → PivotTable** to create native PivotTables. Add slicers for Region, Category, Customer Segment, and Sales Channel, then connect them to relevant PivotTables/charts.

## Suggested GitHub repository structure
```text
task-1-retail-sales-dashboard/
├── Task1_Retail_Sales_Dashboard.xlsx
├── cleaned_retail_sales.csv
├── executive_summary.docx
├── dashboard_screenshot.png
└── README.md
```
