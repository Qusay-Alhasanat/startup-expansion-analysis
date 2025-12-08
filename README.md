# Startup Expansion Data Analysis — Data Science Portfolio Project
**Entry-level / Learning Project**

This project is part of my learning journey in Data Science. The goal is to clean, explore, and analyze a Startup Expansion dataset to understand what drives store expansion across different locations.

---

## Dataset
The dataset `startup-expansion.xlsx` includes information about 150 store locations:

- Store ID  
- City, State  
- Sales Region  
- Marketing Spend  
- Revenue  
- New Expansion (Old/New)

The cleaned dataset `startup-expansion-modified.csv` includes additional engineered features:

- `profits` — net profit after subtracting marketing spend  
- `roms_percent` — Return on Marketing Spend (%)  
- `roms_ratio` — ROMS as a numeric ratio  
- `region_perf` — revenue performance category (Low / Medium / High)  
- `high_marketing_flag` — flag for above-average marketing spend  
- `new_expansion_flag` — numerical target for modeling

---

## Notebook
The full analysis is available in **`Startup_Expansion_Analysis.ipynb`**, which includes:

1. Data loading and initial inspection  
2. Data cleaning and preprocessing  
3. Feature engineering  
4. Exploratory Data Analysis (EDA) with visualizations  
5. Insights about expansion decisions  
6. Preparing the dataset for predictive modeling

---

## Key Insights
Some of the main findings from the analysis:

- Revenue is the strongest factor linked to expansion decisions.  
- Marketing spend does not strongly correlate with revenue or expansion.  
- Certain locations achieve high profits with low marketing spend, indicating stronger regional or managerial performance.  
- Region 2 has the most branches but is not the most profitable.  
- The target variable (`new_expansion`) is highly imbalanced, which must be considered when building predictive models.

These insights are supported by visualizations inside the notebook.

---

## Dashboard & Reporting
You can use `startup-expansion-modified.csv` to build:

- **Power BI dashboards** for exploring revenue and regional performance  
- Visual reports for identifying expansion-worthy store locations  
- Predictive models for estimating expansion probability

---

## How to Run
1. Open `Startup_Expansion_Analysis.ipynb` in **Jupyter Notebook**.  
2. Ensure `startup-expansion.xlsx` is placed in the same directory or in a `data/` folder.  
3. Run all cells sequentially to generate engineered features and visualizations.  
4. The cleaned dataset will be saved as `startup-expansion-modified.csv`.

---

## Author
**Qusay — Data Science Portfolio Project**  
[🔗 LinkedIn Profile](https://www.linkedin.com/in/qusay-alhasanat)  
[🔗 GitHub Profile](https://github.com/Qusay-Alhasanat)  
[📧 Email](mailto:qusay.alhasanat1@gmail.com)
