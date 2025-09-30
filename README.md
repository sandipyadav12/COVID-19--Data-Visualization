# 📊 Project Overview

The main goals of this project are:

- Transform raw COVID-19 data into visual formats such as bar charts, scatter plots, heatmaps, and interactive maps.
- Calculate key metrics such as **Mortality Rate** and **Recovery Rate** for each country.
- Highlight the most affected countries and key insights using compelling visual storytelling.
- Create an interactive and exploratory environment using Plotly for global cases and deaths.


## 🛠️ Tools & Libraries

- Python 3  
- Pandas – for data manipulation  
- Matplotlib & Seaborn – for static visualizations  
- Plotly – for interactive visualizations  
- Jupyter Notebook / Google Colab – for running and sharing the project

- ## 📂 Dataset

- The dataset used is `country_wise_latest.csv` containing the latest COVID-19 statistics by country.
- Key columns include:
  - `Country/Region`
  - `Confirmed`
  - `Deaths`
  - `Recovered`
  - `Active`
- Additional calculated metrics:
  - `MortalityRate = Deaths / Confirmed * 100`
  - `RecoveryRate = Recovered / Confirmed * 100`


## 🔹 Visualizations Included

1. **Bar Chart** – Top 10 countries by confirmed cases.  
2. **Scatter Plot** – Mortality vs Recovery rates by country.  
3. **Heatmap** – Correlation of COVID-19 metrics.  
4. **Interactive Choropleth Maps** – Global confirmed cases and deaths.  
5. **Optional Visualizations**:
   - Pie Chart – Global distribution of active, deaths, recovered.  
   - Bubble Chart – Confirmed vs Deaths with bubble size = Recovered.  
   - Treemap – Hierarchical view of cases by country.


## 📝 Key Insights

- Countries with the **highest confirmed cases** are clearly identified.  
- Countries with **highest mortality rates** and **highest recovery rates** are visualized.  
- Correlation heatmap highlights relationships between metrics like Confirmed, Deaths, and Recovered.  
- Interactive maps provide a global overview of the pandemic’s impact.  
