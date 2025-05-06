# 📊 Stock Portfolio Dashboard (Version 2)

## 📘 Introduction

This Excel workbook provides a detailed dashboard for managing and analyzing a stock investment portfolio. It allows users to monitor portfolio value, visualize asset allocation, calculate returns, and track individual transactions. Version 2 includes enhancements to formulas, layout, and possibly new features or sheets for improved user experience and performance tracking.

---

## 🔍 Excel Formulas Used in This File

The workbook makes extensive use of both basic and advanced Excel functions, including:

### ✅ Logical & Error Handling
- `IF()` – For conditional logic.
- `IFERROR()` – Handles formula errors gracefully.
- `ISNUMBER()` / `ISTEXT()` – Type checks.

### 📊 Math & Aggregation
- `SUM()` – Total portfolio values.
- `AVERAGE()` – Calculate average performance metrics.
- `ROUND()`, `ROUNDUP()`, `ROUNDDOWN()` – For formatting financial outputs.
- `COUNTIF()`, `SUMIF()`, `SUMIFS()` – Conditional calculations.

### 📈 Financial Functions
- `XIRR()` – Calculates the extended internal rate of return.
- `IRR()` – For evaluating profitability of investments.

### 📅 Date Functions
- `TODAY()` – Inserts current date.
- `YEAR()`, `MONTH()` – Used to group or filter data chronologically.

### 🔎 Lookup & Reference
- `VLOOKUP()` / `XLOOKUP()` – For retrieving data from reference tables.
- `INDEX()` + `MATCH()` – Advanced lookup combination.
- `INDIRECT()` – For dynamic referencing.

### 📊 Dynamic Arrays (Excel 365+)
- `SORT()`, `FILTER()`, `UNIQUE()` – Used in dynamic tables for real-time data reshaping.

---

## 📁 Sheet Overview (Assumed)

| Sheet Name       | Description |
|------------------|-------------|
| `Dashboard`      | Main interface showing KPIs, graphs, and portfolio summary. |
| `Holdings`       | Detailed list of current stock holdings. |
| `Transactions`   | Log of buy/sell transactions with dates, quantities, and prices. |
| `Returns`        | Calculates IRR, gains/losses, and dividend returns. |
| `Lookups`        | Contains lists and helper tables for data validation. |

---

## 🛠 Requirements

- Microsoft Excel 365 or later (due to dynamic array formulas).
- Optional: Internet connection if using stock data plugins or live updates.
