
# 📊 GDP Analysis — Indian States

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-green?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-red?style=for-the-badge&logo=matplotlib&logoColor=white" />
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge" />
</p>

<p align="center">
  <b>A comprehensive data analysis project exploring the Gross Domestic Product (GDP) of Indian States — uncovering economic trends, sectoral contributions, and growth patterns.</b>
</p>

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Objectives](#-objectives)
- [Dataset](#-dataset)
- [Project Structure](#-project-structure)
- [Key Analysis](#-key-analysis)
- [Technologies Used](#-technologies-used)
- [How to Run](#-how-to-run)
- [Results & Insights](#-results--insights)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🌐 Overview

Gross Domestic Product (GDP) is one of the most important economic indicators that reflects the overall health and progress of an economy. This project dives deep into the **GSDP (Gross State Domestic Product)** data of Indian states to:

- Compare economic performance across states
- Identify high-growth and struggling states
- Analyze sectoral contributions (Agriculture, Industry, Services)
- Provide data-driven recommendations for policymakers

> 💡 The goal is to help identify areas of focus that can foster **economic development** across India's diverse states.

---

## 🎯 Objectives

| # | Objective |
|---|-----------|
| 1 | Analyze total and per capita GSDP of all Indian states |
| 2 | Identify the fastest-growing and slowest-growing states |
| 3 | Examine sectoral distribution (Primary / Secondary / Tertiary) |
| 4 | Categorize states by GDP per capita and study sector-wise contributions |
| 5 | Visualize economic trends using clear and informative plots |

---

## 📂 Dataset

The data is sourced from **[data.gov.in](https://data.gov.in/)** — the Open Government Data (OGD) platform of India.

### Data Files:

| File | Description |
|------|-------------|
| `Data I-A` | GSDP (Gross State Domestic Product) for all states and union territories |
| `Data I-B` | Sector-wise GSDP distribution — Primary (Agriculture), Secondary (Industry), Tertiary (Services), Taxes & Subsidies |

**Time Period Covered:** 2013–14 to 2016–17

---

## 📁 Project Structure

```
GDP-Analysis/
│
├── 📓 GDP_Analysis.ipynb       # Main Jupyter Notebook with complete analysis
├── 📁 data/
│   ├── data_ia.csv             # State-wise GSDP data
│   └── data_ib/                # Sector-wise data (one file per state)
├── 📁 plots/                   # Exported charts and visualizations
└── 📄 README.md                # Project documentation
```

---

## 🔍 Key Analysis

### Part 1 — GDP Analysis of Indian States

- ✅ Calculated **average growth rates** of states over 2013–14 to 2015–16
- ✅ Compared **total GSDP** across states with ordered bar charts
- ✅ Compared **per capita GSDP** to identify living standard differences
- ✅ Identified **top performers** and **economically lagging** states
- ✅ Categorized states into **4 groups** based on GDP per capita

### Part 2 — Sectoral Contribution Analysis

- ✅ Analyzed which sectors (**Agriculture / Industry / Services**) dominate each category
- ✅ Compared sector-wise contributions for different GDP tiers
- ✅ Identified economic structural differences between rich and poor states

---

## 🛠️ Technologies Used

| Library | Purpose |
|---------|---------|
| `Python 3.8+` | Core programming language |
| `Pandas` | Data manipulation and cleaning |
| `NumPy` | Numerical computations |
| `Matplotlib` | Static data visualizations |
| `Seaborn` | Enhanced statistical plots |
| `Jupyter Notebook` | Interactive analysis environment |

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/Sumitsharma12321/GDP-Analysis.git
cd GDP-Analysis
```

### 2. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 3. Launch the Notebook

```bash
jupyter notebook GDP_Analysis.ipynb
```

> Make sure your data files are placed in the correct directories as shown in the project structure above.

---

## 📈 Results & Insights

Here are some of the key findings from the analysis:

- 🏆 **Fastest Growing States:** States like Telangana, Andhra Pradesh, and Gujarat showed consistently high GSDP growth rates.
- 📉 **Struggling States:** Some northeastern and smaller states showed lower and inconsistent growth.
- 🌾 **Agriculture-heavy states** showed lower per capita GSDP compared to states dominated by **Services and Industry**.
- 🏙️ States with a strong **tertiary (services) sector** tend to have significantly higher per capita income.
- 📊 A clear **economic disparity** exists between high-income and low-income states, indicating the need for targeted policy intervention.

---

## 🤝 Contributing

Contributions are welcome! If you'd like to improve the analysis or add new features:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License** — feel free to use, modify, and distribute.

---

<p align="center">
  Made with ❤️ by <a href="https://github.com/Sumitsharma12321"><b>Sumit Sharma</b></a>
  <br/>
  ⭐ If you found this project helpful, please give it a star!
</p>
