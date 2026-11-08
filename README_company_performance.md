# Company Performance and Cash Flow Dashboard

A Power BI dashboard that analyzes the financial performance of publicly traded companies using their income statements, balance sheets, and cash flow statements.

**Tools:** Power BI, Power Query, DAX
**Data:** Kaggle, financial data of 4,400 public companies (annual and quarterly statements)

![Dashboard preview](images/dashboard_preview.png)

<!-- TODO: add a screenshot of your main page at images/dashboard_preview.png -->

## Project Overview

This project turns raw financial statements into an interactive dashboard that answers a simple question: how is a company performing, and is that performance backed by real cash?

The dashboard lets a user pick a company and a time period, then review revenue, profit, balance sheet position, and cash flow in one place.

## Business Questions

- How have a company's revenue and profit changed over time?
- Is the company's profit supported by cash generated from operations?
- How strong is the company's balance sheet (assets, liabilities, and equity)?
- How do companies compare with each other on the same measures?

<!-- TODO: edit this list so it matches the questions your dashboard actually answers -->

## Dataset

The data comes from a public Kaggle dataset of about 4,400 publicly traded companies. It contains six files: annual and quarterly versions of the balance sheet, income statement, and cash flow statement.

- Source: [add the Kaggle dataset link here]
- The raw data files are not included in this repository. Please download them from Kaggle.

## What I Did

1. **Data preparation (Power Query):** loaded the statement files, cleaned column names and data types, and shaped the tables for reporting.
2. **Data model:** connected the statement tables through the company identifier and date, so one filter controls every page.
3. **Measures (DAX):** created measures for the key financial figures shown on the dashboard.
4. **Dashboard design:** built the report pages with consistent layout, colors, and slicers.

<!-- TODO: add or remove steps so this matches your real workflow -->

## Dashboard Pages

| Page | What it shows |
|---|---|
| Overview | [add: headline figures and trends] |
| Income Statement | [add: revenue, costs, and profit] |
| Balance Sheet | [add: assets, liabilities, and equity] |
| Cash Flow | [add: operating, investing, and financing cash] |

<!-- TODO: keep only the pages that exist in your .pbix file and describe each in one line -->

## Key Metrics

| Metric | Definition |
|---|---|
| [Revenue] | [definition] |
| [Net income] | [definition] |
| [Operating cash flow] | [definition] |
| [Free cash flow] | [definition] |

<!-- TODO: list the main DAX measures you created -->

## Key Insights

- [Add 3 to 5 findings from your dashboard, with real numbers]
- [For example: which company or period stands out, and why]

## Repository Contents

| File | Description |
|---|---|
| `company_performance_dashboard.pbix` | Power BI report file |
| `company_performance_dashboard.pdf` | PDF export of all pages |
| `README.md` | This file |

<!-- TODO: rename the files above to match your real file names -->

## How to Use

1. Download the `.pbix` file and open it in Power BI Desktop.
2. Use the slicers to choose a company and time period.
3. If Power BI asks for data, point it to the Kaggle files you downloaded.

## Limitations

- The data is a snapshot from a public dataset, and it may contain gaps or reporting differences between companies.
- This project is for learning and portfolio purposes. It is not investment advice.

## Author

**Waqar Ahmad**
Data Analyst | SQL, Power BI, Excel, Power Query
[LinkedIn](https://www.linkedin.com/in/waqar-ahmad-10735b276)

See also: [Credit Risk & Loan Default Analysis](add-your-credit-risk-repo-link-here)
