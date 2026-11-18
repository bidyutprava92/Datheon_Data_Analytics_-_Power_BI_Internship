# Datheon Data Analytics & Power BI Internship

Two projects on the Superstore sales dataset (9,994 orders, 2015-2018): an exploratory data analysis in Python and an executive dashboard in Power BI.

## Repository Structure
- `Task1_Superstore_EDA/`: Python EDA notebook, dataset and README
- `Task2_PowerBI_Dashboard/`: Power BI dashboard (.pbix), PDF export, screenshot and README

## Task 1: Superstore Sales EDA (Python)
Tools: Python, pandas, matplotlib, seaborn, Jupyter Notebook.

Key findings:
- Technology has the best margin (about 17%); Furniture has the lowest (about 2.5%).
- West is the most profitable region (14.9% margin); Central is the weakest (7.9%).
- Tables lose money (about -17.7K profit).
- Texas, Ohio, Pennsylvania and Illinois are loss-making states.
- Top 10 customers contribute only about 6.7% of sales.
- Sales peak in September, November and December.

Details: see `Task1_Superstore_EDA/README.md` and the notebook.

## Task 2: Executive Sales & Profit Dashboard (Power BI)
Tools: Power BI Desktop, Power Query, DAX.

- Star schema: Fact Orders, Dim Customer, Dim Product, Dim Date
- 5 KPI cards: Total Sales 2.30M, Total Profit 286.40K, Profit Margin 12.47%, Total Orders 5,009, YoY Sales Growth %
- Visuals: monthly sales trend, profit by category and sub-category, sales by region, sub-category table, Year and Region slicers

Details: see `Task2_PowerBI_Dashboard/README.md`.

## Author
Bidyutprava Sethy
