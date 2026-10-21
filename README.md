# Indian CPI Inflation Analysis (2013–2023)

<p align="left">
  <img src="https://img.shields.io/badge/Tool-Microsoft%20Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" alt="Microsoft Excel" />
  <img src="https://img.shields.io/badge/Project-Data%20Analytics-2563EB?style=for-the-badge" alt="Data Analytics" />
  <img src="https://img.shields.io/badge/Focus-CPI%20%26%20Inflation-F59E0B?style=for-the-badge" alt="CPI and Inflation" />
  <img src="https://img.shields.io/badge/Period-2013--2023-7C3AED?style=for-the-badge" alt="2013 to 2023" />
</p>

## 📌 Project Overview

This project uses Microsoft Excel to explore India's Consumer Price Index (CPI) data across categories and time. It reviews category distribution, year-on-year CPI trends, food-price movements, pre/post-COVID comparisons, and correlations between Fuel & Light and other CPI components.

The goal is to turn historical economic data into clear, practical insights through spreadsheet analysis and visualisation.

## 📁 Project Files

| File | What it contains |
|---|---|
| [📊 India_CPI_Inflation.xlsx](./India_CPI_Inflation.xlsx) | Main Excel workbook with data, calculations, charts, and analysis sheets |
| [📝 Insights.md](./Insights.md) | Written insights for the key problem statements |
| [📄 README.md](./README.md) | Project overview, preview charts, findings, and usage guide |

## 📸 Project Visuals

The preview charts below summarise selected findings recorded in the workbook summary. They are **illustrative visual previews**, not screenshots of the Excel interface. Open the workbook above to inspect the original sheets and charts.

### 1. Category Distribution

![Category distribution chart](https://quickchart.io/chart?width=850&height=420&format=png&backgroundColor=white&c=%7B%22type%22%3A%22doughnut%22%2C%22data%22%3A%7B%22labels%22%3A%5B%22Food%20%26%20Beverages%22%2C%22Other%20categories%22%5D%2C%22datasets%22%3A%5B%7B%22data%22%3A%5B44.4%2C55.6%5D%7D%5D%7D%2C%22options%22%3A%7B%22plugins%22%3A%7B%22title%22%3A%7B%22display%22%3Atrue%2C%22text%22%3A%22Category%20Distribution%20%5Cu2014%20Food%20%26%20Beverages%20share%22%7D%2C%22legend%22%3A%7B%22position%22%3A%22bottom%22%7D%7D%7D%7D)

Food & Beverages represents approximately **44.4% of the category distribution** reported in the workbook. This is a category share, **not a food inflation rate**.

### 2. Year-on-Year Trend Snapshot

![Annual inflation trend chart](https://quickchart.io/chart?width=850&height=420&format=png&backgroundColor=white&c=%7B%22type%22%3A%22line%22%2C%22data%22%3A%7B%22labels%22%3A%5B%222022%22%2C%222023%22%5D%2C%22datasets%22%3A%5B%7B%22label%22%3A%22Reported%20annual%20inflation%20%28%25%29%22%2C%22data%22%3A%5B6.6%2C3.2%5D%2C%22fill%22%3Afalse%2C%22tension%22%3A0.2%7D%5D%7D%2C%22options%22%3A%7B%22plugins%22%3A%7B%22title%22%3A%7B%22display%22%3Atrue%2C%22text%22%3A%22Annual%20inflation%20figures%20reported%20in%20workbook%20summary%22%7D%2C%22legend%22%3A%7B%22display%22%3Afalse%7D%7D%2C%22scales%22%3A%7B%22y%22%3A%7B%22beginAtZero%22%3Atrue%2C%22title%22%3A%7B%22display%22%3Atrue%2C%22text%22%3A%22Percent%20%28%25%29%22%7D%7D%7D%7D%7D)

The project summary reports approximately **6.6% for 2022** and **3.2% for 2023**. Confirm the precise measure, calculation, and period in the relevant workbook sheet before quoting these figures outside this project.

### 3. Fuel & Light Correlation

![Fuel and Light correlation chart](https://quickchart.io/chart?width=1000&height=540&format=png&backgroundColor=white&c=%7B%22type%22%3A%22bar%22%2C%22data%22%3A%7B%22labels%22%3A%5B%22Transport%20%26%20Communication%22%2C%22Clothing%20%26%20Footwear%22%2C%22Health%22%2C%22Household%20Goods%20%26%20Services%22%2C%22Education%22%2C%22Food%20%26%20Beverages%22%5D%2C%22datasets%22%3A%5B%7B%22label%22%3A%22Correlation%20with%20Fuel%20%26%20Light%22%2C%22data%22%3A%5B0.66%2C0.42%2C0.4%2C0.31%2C0.23%2C-0.2%5D%7D%5D%7D%2C%22options%22%3A%7B%22indexAxis%22%3A%22y%22%2C%22plugins%22%3A%7B%22title%22%3A%7B%22display%22%3Atrue%2C%22text%22%3A%22Fuel%20%26%20Light%3A%20reported%20category%20correlations%22%7D%2C%22legend%22%3A%7B%22display%22%3Afalse%7D%7D%2C%22scales%22%3A%7B%22x%22%3A%7B%22min%22%3A-0.3%2C%22max%22%3A0.8%2C%22title%22%3A%7B%22display%22%3Atrue%2C%22text%22%3A%22Correlation%20coefficient%22%7D%7D%7D%7D%7D)

| CPI Category | Reported correlation |
|---|---:|
| Transport & Communication | 0.66 |
| Clothing & Footwear | 0.42 |
| Health | 0.40 |
| Household Goods & Services | 0.31 |
| Education | 0.23 |
| Food & Beverages | -0.20 |

Transport & Communication has the strongest positive correlation among the listed categories. Correlation describes association and does not prove that fuel-price changes cause changes in another category.

## 🎯 Business Questions

This analysis focuses on five questions:

1. **Category contribution:** Which categories represent the largest share of the classified CPI distribution?
2. **Year-on-year analysis:** How do CPI trends change over time and across sectors?
3. **Food-price analysis:** Which food categories show greater variation?
4. **Pre- and post-COVID comparison:** How do selected CPI patterns differ across the chosen periods?
5. **Correlation analysis:** How are Fuel & Light movements associated with selected CPI categories?

## 🧰 Tools & Skills

- Microsoft Excel
- Data cleaning and unpivoting
- PivotTables and PivotCharts
- Trend and comparative analysis
- Descriptive analysis
- Correlation analysis
- Data visualisation and business storytelling

## 🔍 Key Insights

- Food & Beverages is a major category in the analysed distribution, with a reported share of approximately **44.4%**.
- Vegetables are highlighted in the workbook as a comparatively volatile food component.
- The workbook summary reports a higher annual figure in 2022 than in 2023; the exact metric should be checked against the underlying calculations.
- Fuel & Light is positively associated with Transport & Communication in the analysed series (reported correlation **0.66**).
- Correlations vary across categories and should be interpreted as relationships, not causal effects.

## 🗂️ Workbook Guide

Open `India_CPI_Inflation.xlsx` in Microsoft Excel and review the sheets in numerical order. The workbook includes analysis areas covering:

- Cleaned and unpivoted CPI data
- Category contribution
- Year-on-year CPI trends
- Food-price analysis
- Pre- and post-COVID comparisons
- Fuel-related correlation analysis
- Key insights accompanying the analysis

Sheet names may vary slightly depending on the current workbook version; use the actual tab names in the file.

## ▶️ How to Use

1. Open [India_CPI_Inflation.xlsx](./India_CPI_Inflation.xlsx).
2. Start with the cleaned/unpivoted data sheet to understand the structure.
3. Review each numbered analysis sheet and its charts.
4. Read [Insights.md](./Insights.md) alongside the corresponding analysis.
5. Verify figures against the workbook calculations before reusing them in a report or presentation.

## ⚠️ Notes & Limitations

- CPI index values and inflation rates are different measures and should not be used interchangeably.
- The findings reflect the dataset and calculations included in this workbook; verify the original data source and definitions for formal research.
- Correlation does not establish causation.
- The analysis covers 2013–2023 and should not be treated as a current inflation update.
- The charts embedded here are preview visuals based on the summary figures, not direct screenshots of workbook tabs.

## 👩‍💻 Author

**Mansi Sharma**  
MBA — IT & Business Management  
Interested in business analysis, data analytics, and translating data into actionable insights.

---

⭐ If this project was useful, feel free to star the repository.
