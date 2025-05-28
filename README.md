# 🌍 Global Health Dashboard

This project visualizes and analyzes global trends in **life expectancy** and **health expenditure per capita** using public datasets from **Our World in Data** and the **World Bank**. It explores geographic patterns, relationships, and outliers in health outcomes and spending.

---

### 📁 Datasets Used

The following datasets are **included in this repository** for convenience:

- **Life Expectancy** – From [Our World in Data (UN WPP)](https://ourworldindata.org/life-expectancy)  
  → `life-expectancy-unwpp.csv`

- **Health Expenditure Per Capita** – From [World Bank](https://data.worldbank.org/indicator/SH.XPD.CHEX.PC.CD)  
  → `API_SH.XPD.CHEX.PC.CD_DS2_en_csv_v2_87561.csv`

No need to download externally — everything needed to run the notebook is already here.


---

## 📊 Key Visualizations

- 🗺️ **Choropleth Map**: Life expectancy by country
- 📈 **Scatter Plot**: Health spending vs life expectancy
- 📉 **Correlation Heatmap**: Strength of relationship between spending and outcomes
- 🏆 **Top 10 Countries**: Life expectancy leaders
- ⚠️ **Outlier Analysis**: High spending with low life expectancy

---

## 🔍 Insights

- **Correlation (0.63)** between health expenditure per capita and life expectancy suggests a strong but not perfect relationship.
- Countries like **Monaco, Japan, Switzerland, Australia** lead in life expectancy.
- Outliers like the **United States** show high health spending with relatively moderate outcomes.
- Effective healthcare is not just about money — policy and access matter too.

---

## 🧰 Tools & Libraries

- Python
- Pandas
- Matplotlib & Seaborn
- Plotly Express
- Jupyter Notebook

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
jupyter notebook global_health_dashboard.ipynb

