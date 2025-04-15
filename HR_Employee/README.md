# 📊 HR Dashboard – Power BI

This is a simple HR dashboard built using **Microsoft Power BI**, designed as a practice project to showcase basic data visualization and analysis skills. It uses fictional employee data to track key HR metrics in an interactive format.

## 🔍 Overview

The dashboard provides a quick view of the company's HR metrics, including:

- Total Employees
- Active Employees
- Monthly Turnover Rate
- Salary by Age
- Monthly Salary by Department
- Number of Employees per Department
- Monthly Turnover Rate per Department
- Date filter (via slicer)

## 🛠️ Technical Details

- **Tool**: Microsoft Power BI Desktop  
- **Data Source**: Mock employee dataset (`funcionarios-rh`)
- **Tables Used**:
  - `funcionarios-rh`: Employee data (age, salary, department, employment status, hire date, etc.)
  - `Calendario`: Date table used for time-based filtering

## 📈 Visuals

- **Cards (KPIs)**: Total Employees, Active Employees, Turnover Rate
- **Area Chart**: Salary by Age
- **Clustered Column Charts**:
  - Turnover Rate per Department
  - Monthly Salary by Department
  - Employee Count by Department
- **Date Slicer**: Enables dynamic filtering over time

## 📊 Key Measures & Calculations

- `Qtd_Funcionarios`: Count of employees by department
- `Taxa de Rotatividade`: Monthly turnover rate calculation
- `Funcionario_Ativo`: Used to count currently active employees
- `SUM(Salario)`: Aggregated salary

## 🎯 Purpose

This dashboard was created for **educational purposes**, aimed at practicing:

- Simple data modeling in Power BI
- Building interactive dashboards
- Using date filters and slicers
- Creating basic HR metrics


## 📁 How to Use

1. Download the `.pbix` file
2. Open it in Power BI Desktop
3. Explore the visualizations and filters
4. Customize or extend with your own metrics

---

Feel free to fork this project, explore improvements, or use it as a template for your own HR analytics dashboard!
