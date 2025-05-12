# python-week-8
**COVID-19 Global Data Tracker** project:

---

# 🌍 COVID-19 Global Data Tracker

## 📋 Project Description

The **COVID-19 Global Data Tracker** is a data analysis and visualization project aimed at exploring the global impact of COVID-19. The project focuses on tracking confirmed cases, deaths, and vaccination progress across different countries and over time. It leverages real-world datasets to perform data cleaning, exploratory data analysis (EDA), and data visualization using Python. The end goal is to generate insightful trends and a clear narrative in the form of a Jupyter Notebook report, which can be shared as a PDF or presentation.

---

## 🎯 Project Objectives

* ✅ Import and clean global COVID-19 datasets.
* ✅ Analyze time trends in cases, deaths, and vaccinations.
* ✅ Compare COVID-19 metrics across countries and regions.
* ✅ Visualize global trends using charts, graphs, and maps.
* ✅ Present findings with clear narrative explanations and visuals.

---

## 🧰 Tools & Libraries Used

* **Jupyter Notebook** (recommended via Anaconda)
* **Python 3.x**
* `pandas` – for data manipulation and analysis
* `matplotlib` – for visualizations
* `seaborn` – for advanced statistical plots
* `plotly` (optional) – for interactive choropleth maps
* `geopandas` (optional) – for advanced geospatial analysis

---

## 🚀 How to Run/View the Project

1. **Install Anaconda (Recommended):**

   * Download from: [https://www.anaconda.com/products/distribution](https://www.anaconda.com/products/distribution)

2. **Launch Jupyter Notebook:**

   * Open Anaconda Navigator and launch Jupyter Notebook.

3. **Set Up Project Folder:**

   * Create a working directory.
   * Download and place `owid-covid-data.csv` from [Our World in Data](https://ourworldindata.org/covid-deaths) into the folder.

4. **Open and Run Notebook:**

   * Open the `.ipynb` file provided in the project.
   * Execute cells sequentially to view analysis and visualizations.

5. **Export Report (Optional):**

   * Export notebook as a PDF via File > Download as > PDF via LaTeX (or use browser print to PDF).

---

## 📈 Project Workflow Summary

### 1️⃣ Data Collection

* Source: [Our World in Data COVID-19 Dataset](https://ourworldindata.org/covid-deaths)
* File: `owid-covid-data.csv`

### 2️⃣ Data Loading & Exploration

* Load CSV with `pandas.read_csv()`, inspect structure, check for missing values.

### 3️⃣ Data Cleaning

* Filter countries, handle missing/invalid data, convert dates.

### 4️⃣ Exploratory Data Analysis (EDA)

* Time series plots, comparisons, calculation of death rate, new cases analysis.

### 5️⃣ Vaccination Analysis

* Visualize cumulative vaccinations, % population vaccinated.

### 6️⃣ Optional: Choropleth Maps

* Use Plotly to show global trends by country on a map.

### 7️⃣ Insights & Reporting

* Highlight key trends, outliers, and patterns.
* Embed explanations using Markdown cells.

---

## 💡 Insights & Reflections

* Countries with earlier and more aggressive vaccination campaigns show a significant decrease in new cases and deaths.
* Some countries with high case counts had relatively low death rates, possibly due to better healthcare systems or testing coverage.
* Vaccination rollouts were uneven globally, with wealthier nations often leading, revealing disparities in global health equity.
* Creating choropleth maps added a powerful layer of spatial understanding, helping visualize trends at a global level.
* The project highlighted the importance of clean, reliable data and storytelling through visuals for effective data-driven communication.

---

## 📚 References

* Our World in Data COVID-19 Dataset: [https://ourworldindata.org/covid-deaths](https://ourworldindata.org/covid-deaths)
* Johns Hopkins COVID-19 Repository: [https://github.com/CSSEGISandData/COVID-19](https://github.com/CSSEGISandData/COVID-19)
* Kaggle Datasets: [https://www.kaggle.com/datasets](https://www.kaggle.com/datasets)

---


