FILES
- index.html: the website
- Bowling_2026-2027.xlsx: the workbook read by the website

HOW TO UPDATE
1. Keep the workbook filename exactly Bowling_2026-2027.xlsx.
2. Replace the old workbook in your GitHub repository with the updated workbook.
3. Commit the change. Vercel will redeploy the connected project.
4. The website reads every sheet and refreshes the dashboard from the workbook.

IMPORTANT
- The page uses the SheetJS browser library from jsDelivr. Internet access is required for that library to load.
- The All Workbook Sheets page exposes every sheet as a searchable table.
- Curated dashboard views use the current workbook sheet names. If a sheet name or layout changes substantially, update the corresponding parser in index.html.
