
# 📊 GDP Analysis — Indian States


<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white)

**Exploring Economic Performance, Growth Trends, and Sectoral Contributions across Indian States**

</div>

## 📌 Project Overview

This project performs a comprehensive **data analysis of Gross State Domestic Product (GSDP)** of Indian states and union territories using publicly available data from **data.gov.in**.

The analysis covers the period **2013–14 to 2016–17** and focuses on:
- Total and per capita GSDP
- Year-over-year growth rates
- Sector-wise contributions (Agriculture, Industry, Services)
- Regional economic disparities
- Identification of fastest and slowest growing states

The project is organized into multiple Jupyter Notebooks, each addressing a specific aspect of the analysis, making the learning and exploration process step-by-step and easy to follow.

## 📁 Repository Structure


GDP-Analysis/
├── gdp.csv                          # Main dataset
├── 1.GDP_Analysis_WalkThrough.ipynb
├── 2.GDP_Growth_Of_a_Country.ipynb
├── 3.GDP_Growth_on_Whole_Dataset.ipynb
├── 4.GDP_Plotting_Graph_using_Plotly.ipynb
├── 5.GDP_Plotting_Graph_In_Bulks.ipynb
├── 6.GDP_Compare_GDP_Across_Countries.ipynb
├── 7.GDP_Comparision_Across_Countries_advance.ipynb
├── 8.GDP_Compare_GDP_Growth_Across_Countries_advance.ipynb
├── Plotting Graph using Plotly.ipynb
├── README.md
└── LICENSE


## 🛠️ Technologies & Libraries Used

- **Python**
- **Pandas** – Data cleaning and manipulation
- **NumPy** – Numerical operations
- **Matplotlib & Seaborn** – Static visualizations
- **Plotly** – Interactive and bulk visualizations
- **Jupyter Notebook** – Interactive development

## 📊 Notebooks & What They Cover

| Notebook | Description |
|---------|-----------|
| **1. GDP_Analysis_WalkThrough.ipynb** | Complete step-by-step walkthrough of data loading, cleaning, and initial exploration. |
| **2. GDP_Growth_Of_a_Country.ipynb** | Calculates and visualizes GDP growth for individual states. |
| **3. GDP_Growth_on_Whole_Dataset.ipynb** | Aggregate growth analysis across all states and years. |
| **4 & Plotting Graph using Plotly.ipynb** | Interactive visualizations using Plotly (line charts, bar plots, etc.). |
| **5. GDP_Plotting_Graph_In_Bulks.ipynb** | Generates multiple graphs efficiently in bulk for different states/metrics. |
| **6. GDP_Compare_GDP_Across_Countries.ipynb** | Basic comparison of total GSDP across states with ordered bar charts. |
| **7. GDP_Comparision_Across_Countries_advance.ipynb** | Advanced per capita GSDP analysis + categorization of states into 4 economic groups (High, Medium, Low, Very Low). |
| **8. GDP_Compare_GDP_Growth_Across_Countries_advance.ipynb** | Advanced growth rate comparison to identify top and bottom performers. |

## 🔍 Key Insights

### 1. Growth Performance
- **Fastest growing states**: Telangana, Andhra Pradesh, and Gujarat showed consistently high GSDP growth.
- **Slowest growing states**: Several Northeastern states and smaller economies lagged behind in growth.

### 2. Economic Structure & Per Capita Income
- States with higher dependence on the **Primary sector (Agriculture)** generally have **lower per capita GSDP**.
- States dominated by the **Tertiary (Services)** and **Secondary (Industry)** sectors exhibit significantly **higher per capita income** and better economic performance.

### 3. Regional Disparities
- There is a clear divide between economically advanced and lagging states.
- The economic structure varies widely — richer states rely more on services, while poorer states remain heavily dependent on agriculture.

### 4. Policy Relevance
The analysis highlights the need for targeted policy interventions to:
- Reduce regional economic disparities
- Promote structural transformation (shift from agriculture to industry & services)
- Support underperforming states through focused development programs

## 📈 Visualizations

The project includes:
- Interactive Plotly charts
- Comparative bar charts (total GSDP & per capita)
- Growth trend line plots
- Bulk visualizations for multiple states
- Categorized analysis plots (states grouped by economic performance)

📄 Data Source

Source: Kaggle
Datasets Used: gdp.csv

📜 License
This project is licensed under the MIT License – see the LICENSE file for details.
