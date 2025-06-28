# PRODIGY_DS_01

# Internship Task 01 – Population Distribution Visualization

This project explores and visualizes the **2020 population data by country** using bar charts and histograms. The goal is to analyze the distribution of global populations, identify the most populous countries, and understand patterns in the data. The data was sourced from the **World Bank Open Data Portal**.


## 📊 Visualizations Included

### 1 Bar Chart – Top 10 Most Populous Countries (2020)
- Displays a horizontal bar chart of the **top 10 countries by population**.
- Implemented using both **Seaborn** and **Plotly** for static and interactive views.
- A custom color palette is used to enhance readability and visual appeal.

### 2️ Histogram – Population Distribution Across All Countries (2020)
- Shows how population values are distributed across all countries.
- The distribution is **right-skewed**, meaning most countries have smaller populations, and a few countries (like India and China) have very large populations.
- A **KDE (Kernel Density Estimation)** curve is added to show the smooth density trend.
- The KDE helps understand the shape of the data beyond just raw bin counts.

---

## Key Insights

- **India and China** dominate the global population landscape.
- A large number of countries have populations below 50 million.
- The histogram reveals a **right-skewed distribution** with few outliers.
- Using both static and interactive charts improves the effectiveness of communication.


## Tools & Libraries Used

- **Google Colab**
- **Python 3**
  - pandas
  - matplotlib
  - seaborn
  - plotly
- **Dataset**:  
  [🔗 World Bank – Total Population (SP.POP.TOTL)](https://data.worldbank.org/indicator/SP.POP.TOTL)


## How to Run This Project

1. Clone or download this repository.
2. Open `population_analysis.ipynb` using Google Colab or Jupyter Notebook.
3. Upload the `API_SP.POP.TOTL_DS2_en_csv_v2.csv` file (after extracting the ZIP from the World Bank site).
4. Run the notebook to generate and view the visualizations.





