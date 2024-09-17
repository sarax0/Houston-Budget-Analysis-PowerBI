# Houston Budget Analysis Power BI Project

## Overview

This project analyzes Houston's budget data over multiple years using Power BI. It features interactive dashboards to explore spending, revenue, and budget variances, providing clear insights into financial performance and fund allocation.

---

## Features

- **Navigation**: A sidebar with three buttons for easy access to different dashboards.
- **Filtering**: Uniform slicers across all pages for filtering data.
- **Dashboards**:
  - **Budget Overview**: Compares total budget vs. actual spending, highlights high-expenditure account categories, and evaluates overall financial performance.
  - **Department Dashboard**: Compares actual spending to budget by department, tracks budget variances, and shows spending trends.
  - **Fund Dashboard**: Identifies fund variances, monitors changes in fund balances, and reviews fund balances by type.

---

## Project Details

### 1. Data Loading and Transformation
- Imported Houston budget data from four yearly files using the folder data source in Power BI.
- In Power Query:
  - Created a star schema with a `Budget` fact table and dimension tables for `Year`, `Function`, `Account Department`, and `Type`.
  - Added index keys, removed duplicates, and merged dimensions to form the fact table with necessary columns.
![Data Model](https://github.com/user-attachments/assets/630d8292-c32c-48eb-8389-c4985d86824b)

### 2. Measures Created

- **Total Actual**, **Total Adopted**, **Total Current**, **Budget Variance**, **Fund Balance**, **Revenue**

### 3. Dashboard Pages

#### **1. Budget Overview Page**

This page answers key questions such as:
- What is the total budget vs. actual spending over time?
- Which account categories have the highest actual expenditures?
- Are we earning more than we're spending?
![Budget Overview Page](https://github.com/user-attachments/assets/85fd0833-7fb4-4e3e-a60a-914fbef386bb)


#### **2. Department Budget Analysis**

This page provides insights into department-level spending:
- How does actual spending compare to the budget in each department?
- What are the budget variances by department?
- How are funds allocated to each department?
- What is the trend of actual spending per department over time?
![Department Dashboard](https://github.com/user-attachments/assets/2f7e24d8-4ae8-4d63-a6da-e197493d14b5)

#### **3. Fund Managment**

This page focuses on fund allocation and balances:
- Which fund has the largest variance between budget and actual spending?
- How have fund balances changed over time?
- What is the fund balance for each fund type?
- What are the balances in each fund?
![Fund Dashboard](https://github.com/user-attachments/assets/a727dc07-77c2-4a81-8042-c44e71156811)

### 4. Navigation and Filtering

- **Sidebar**: A sidebar with **three buttons** allows users to navigate between the dashboards.
- **Menu Pane**: A unified slicer pane is available on all pages, enabling users to filter the data dynamically based on dimensions like year, department, and account type.
![Menu Pane](https://github.com/user-attachments/assets/38b669a8-1ea6-4b27-b1c4-eca378480935)

---

## How to Use the Dashboard

1. **Navigate**: Use the sidebar buttons to switch between the **Budget Overview**, **Department**, and **Fund** dashboards.
2. **Filter Data**: Adjust the slicers on the menu pane to filter by year, department, and other categories.
3. **Explore**: Dive into specific metrics such as total spending, revenue, and variances using the interactive visuals like cards, matrices, and charts.

---

## Conclusion

This Power BI project offers a comprehensive view of Houston’s budget, enabling stakeholders to analyze spending patterns and fund allocation effectively. With interactive visuals and filters, users can quickly derive insights and make informed financial decisions.
