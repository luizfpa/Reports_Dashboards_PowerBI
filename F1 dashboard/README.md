# 🏎️ Formula 1 Dashboard – Power BI

This is a comprehensive Formula 1 dashboard created using **Microsoft Power BI**, designed to analyze F1 data. It visualizes key metrics for teams, races, and drivers. The dataset is sourced from official F1 records (e.g., Ergast API or similar) and serves as an analytical tool for enthusiasts and analysts.

## 🔍 Overview

The dashboard provides insights into:

- Total races, seasons, drivers, and teams
- Podiums, victories, and points over time (1950 – 2022)
- Podiums by team (1st, 2nd, 3rd place breakdown)
- Detailed team stats (nationality, races, podiums, victories, points)
- Winning teams by Grand Prix 
- Additional pages for Races and Drivers analysis

## 🛠️ Technical Details

- **Tool**: Microsoft Power BI Desktop  
- **Data Source**: F1 dataset 
- **Tables Used**:
  - `Races`: Race details (`circuitId`, `year`, `name`) 🏁
  - `Teams`: Team info (`name`, `nationality`) 🤝
  - `Results`: Performance metrics (`podiums`, `victories`, `points`) 📊
  - `Circuits`: Circuit info (`circuitId`, `name`, `location`) 🏟️

## 📈 Visualizations

- **KPI Cards**: Total Races, Seasons, Drivers, and Teams 📊
- **Line Chart with Bars**: Podiums, Victories, and Points over time (1950 - 2022) 📉
- **Stacked Bar Chart**: Podiums by Team (1st, 2nd, 3rd place) 🏆
- **Table**: Detailed Team Stats (nationality, races, podiums, victories, points) 🏠
- **List**: Winner Team by Grand Prix 
- **Year Slicer**: Filter data by year range (1950 – 2022) 🔎

## 📊 Key Measures

- `Total Points = SUM(Results[points])`: Calculates total points 💯
- Filtering and sorting by team and year for dynamic visuals 🔍

## 🎯 Purpose

This project was built for **exploring F1 data and showcasing Power BI skills**, focusing on:

- Dashboard design with F1 branding 🖤💛
- Using slicers and filters for interactive exploration 🔎
- Creating performance-related KPIs for teams 📈
- Visualizing historical trends and Grand Prix wins over time 📅


## 📁 How to Use

1. Download the `.pbix` file 📥
2. Open it with Power BI Desktop 💻
3. Interact with the filters and visuals 🔍
4. Customize it further to fit new scenarios or datasets 🛠️

---

Feel free to fork, modify, or use this as a base for your own Power BI projects! 🚀
