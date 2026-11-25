# Superstore Sales Analysis
## Project overview
Business-focused analysis of the user-provided Sample - Superstore dataset. Deliverables include cleaned data, an Excel dashboard and a PDF report.

## Dataset selection
Three ZIP archives were supplied. `archive.zip` contains `Sample - Superstore.csv` (9,994 rows, 21 columns), selected as the primary dataset because it includes sales, profit, product, category, region and date fields. The other two archives contain the same Online Retail dataset (541,909 rows, 8 columns) in two formats. They were not merged because they are separate datasets and do not include a profit field.

## Key results
- Sales: $2,297,200.86
- Profit: $286,397.02
- Orders: 5,009
- Units sold: 37,873
- Profit margin: 12.47%
- Customers: 793

## Files
- `Dataset/Original_Superstore.csv` - source data.
- `Dataset/Cleaned_Superstore.csv` - prepared data with derived fields.
- `Dashboard/Superstore_Sales_Dashboard.xlsx` - dashboard and analysis worksheets.
- `Report/Sales_Analysis_Report.pdf` - executive report and recommendations.
- `Charts/` - report visuals.

## Data preparation
Checked missing values and exact duplicate rows; none were detected in the selected dataset. Parsed order and ship dates and added Order Year, Order Month, Profit Margin and Shipping Days. Negative-profit transactions were retained.

## Tools
Python, pandas, matplotlib, Excel workbook (openpyxl), PDF report (ReportLab).

## How to use
Open the Excel workbook and start at `Executive Dashboard`. Supporting sheets contain monthly, category, region, sub-category, product, state and cleaned transaction data. Read the PDF for findings and recommendations.
