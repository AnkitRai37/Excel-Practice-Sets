# 📊 Excel Practice Sets

<div align="center">

**A complete, hands-on Excel practice repository covering every skill a Data Analyst needs — from basics to dashboards.**


[🚀 Getting Started](#-getting-started) • [📚 Roadmap](#-learning-roadmap) • [📁 Repo Structure](#-repository-structure) • [✅ Progress Tracker](#-progress-tracker)

</div>

---

## 🧭 About This Repository

This repo is my personal practice ground for mastering **Excel for Data Analysis**, following a structured 18-topic roadmap — each topic with **dedicated practice files, exercises, and solutions**.

> 🎯 **Goal:** Build job-ready Excel skills for a Junior Data Analyst role — data cleaning, analysis, forecasting, what-if modeling, and dashboards.

---

## 🚀 Getting Started

1. **Clone the repo**

```bash
   git clone https://github.com/<your-username>/excel-practice-sets.git
```

2. **Open any `.xlsx` file** in Excel (2019 or later recommended)
3. **Practice first, then check** — every topic has a `practice/` file (exercises with empty cells) and a `solution/` file (completed version)
4. Track your progress in the [Progress Tracker](#-progress-tracker) below ✅

---

## 📚 Learning Roadmap

> ⭐ = Interview-heavy topics | 🔥 = Advanced topics

| # | Topic | Practice Focus | Status |
| --- | --- | --- | --- |
| 01 | Excel Basics | Interface, workbooks, cell formatting, shortcuts | ⬜ |
| 02 | Data Cleaning ⭐ | Duplicates, whitespace, inconsistent formats, TRIM/CLEAN/PROPER | ⬜ |
| 03 | Sorting & Filtering | Multi-level sort, custom filters, filter by color | ⬜ |
| 04 | Excel Tables | Structured references, table styles, auto-expansion | ⬜ |
| 05 | Conditional Formatting ⭐ | Highlight rules, data bars, color scales, custom formulas | ⬜ |
| 06 | Basic Formulas & Functions | SUM, AVERAGE, MIN/MAX, COUNT, absolute vs relative refs | ⬜ |
| 07 | IF / IFS / AND / OR ⭐ | Nested logic, error handling with IFERROR | ⬜ |
| 08 | Text Functions | LEFT, RIGHT, MID, LEN, FIND, CONCAT, TEXTSPLIT | ⬜ |
| 09 | Date & Time Functions | DATEDIF, EOMONTH, NETWORKDAYS, date math | ⬜ |
| 10 | Lookup Functions ⭐ | XLOOKUP, INDEX-MATCH, two-way lookups, approximate match | ⬜ |
| 11 | SUMIFS / COUNTIFS / AVERAGEIFS ⭐ | Multi-criteria aggregation, wildcards | ⬜ |
| 12 | Excel Charts | Column, line, combo charts, chart formatting best practices | ⬜ |
| 13 | Pivot Tables ⭐ | Grouping, calculated fields, % of total, drill-down | ⬜ |
| 14 | Pivot Charts & Slicers | Interactive filtering, timelines, connected slicers | ⬜ |
| 15 | Statistical Analysis | Mean, median, mode, std dev, correlation, quartiles | ⬜ |
| 16 | ⭐ Forecasting 🔥 | Moving averages, FORECAST.LINEAR, TREND, FORECAST.ETS, MAE/MAPE/RMSE, trendlines, Forecast Sheet | ⬜ |
| 17 | What-if Analysis 🔥 | Goal Seek, Scenario Manager, one & two-variable Data Tables | ⬜ |
| 18 | Advanced Excel Dashboard 🔥 | KPI cards, Pivot-driven dashboards, slicers, professional layout | ⬜ |

---

## 📁 Repository Structure

```javascript
excel-practice-sets/
│
├── 01-excel-basics/
│   ├── practice/
│   └── solution/
├── 02-data-cleaning/
│   ├── practice/
│   └── solution/
├── ...
├── 16-forecasting/
│   ├── practice/
│   │   ├── 01-moving-averages.xlsx
│   │   ├── 02-forecast-linear.xlsx
│   │   ├── 03-trend-growth-slope.xlsx
│   │   ├── 04-trendline-r2.xlsx
│   │   ├── 05-forecast-sheet.xlsx
│   │   └── 06-accuracy-mae-mape-rmse.xlsx
│   └── solution/
│
├── datasets/                    # Raw practice data (CSV + XLSX)
├── resources/                   # Shortcuts PDF, formula cheat sheets
├── screenshots/                 # Expected output images
└── README.md
```

---

## 🎯 Topic 16 — Forecasting (Deep Dive)

The most job-relevant block, expanded from the roadmap:

| Sub-topic | File | Key Skills |
| --- | --- | --- |
| Moving Averages | `01-moving-averages.xlsx` | 3/6/12-month MA, window size trade-offs |
| Linear Forecast | `02-forecast-linear.xlsx` | `FORECAST.LINEAR()`, manual SLOPE × date + INTERCEPT |
| Trend Functions | `03-trend-growth-slope.xlsx` | `TREND()`, `GROWTH()`, `RSQ()` |
| Chart Trendlines | `04-trendline-r2.xlsx` | Linear trendline, equation, R² interpretation |
| Forecast Sheet | `05-forecast-sheet.xlsx` | ETS forecast, seasonality, confidence intervals |
| Accuracy Metrics | `06-accuracy-mae-mape-rmse.xlsx` | Forecast error, MAE, MAPE, RMSE — validating every method |

**Forecasting mini-project:** Clean 24 months of sales data → linear vs ETS forecast → compare MAPE → present with confidence bands.

---

## ✅ Progress Tracker

- [ ] **Foundation** — Topics 01–06
- [ ] **Core Analysis** — Topics 07–11
- [ ] **Visualization** — Topics 12–14
- [ ] **Statistics** — Topic 15
- [ ] **Forecasting** — Topic 16 ⭐
- [ ] **Modeling** — Topic 17
- [ ] **Capstone Dashboard** — Topic 18

**Overall:** `0 / 18 topics complete`

---

## 💡 Practice Method (that actually works)

1. 🔹 **Attempt first** — open the practice file, solve without help
2. 🔹 **Check against solution** — don't just copy; compare *logic*
3. 🔹 **Redo after 3 days** — spaced repetition locks it in
4. 🔹 **One mini-project per topic** — small real-world scenario (sales, HR, marketing data)
5. 🔹 **Time yourself** — 30 min per exercise set, analyst-speed matters

---

## 🛠️ Requirements

- Microsoft Excel **2019 / 2021 / 365** (XLOOKUP, TEXTSPLIT & FORECAST.ETS need these)
- OR **Excel for the web** (free with a Microsoft account — most files work)
- Data Analysis ToolPak enabled for statistical/forecasting exercises *(File → Options → Add-ins → Excel Add-ins)*

---

## 📖 Resources

- [Microsoft Excel Formula Reference](https://support.microsoft.com/en-us/excel)
- [FORECAST.ETS documentation](https://support.microsoft.com/en-us/office/forecast-ets-function-15389b8b-677e-4fbd-bd95-21d464333f41)
- Practice datasets: [Kaggle](https://www.kaggle.com/datasets) • [Maven Analytics](https://mavenanalytics.io/data-playground)

---

## 📜 License

MIT — feel free to use these practice sets for learning. Give a ⭐ if this repo helps you!

---

<div align="center">

**⭐ Star this repo to follow the journey from Excel basics to analyst-ready dashboards! ⭐**

</div>
