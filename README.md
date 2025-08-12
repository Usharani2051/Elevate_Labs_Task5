# Elevate_Labs_Task5

# Exploratory Data Analysis on Penguins Dataset

##  Overview
The goal is to perform **Exploratory Data Analysis (EDA)** using the **penguins.csv** dataset to extract meaningful patterns, trends, and anomalies using visual and statistical methods.

---

## Dataset
**Source:** Palmer Penguins Dataset
The dataset contains biological and geographical measurements of penguins from three species:

- Adelie
- Chinstrap
- Gentoo

**Columns:**
- 'species' — Penguin species name
- 'island' — Island where the penguin was found
- 'bill_length_mm' — Length of the bill (mm)
- 'bill_depth_mm' — Depth of the bill (mm)
- 'flipper_length_mm' — Length of the flipper (mm)
- 'body_mass_g' — Body mass (grams)
- 'sex' — Gender of the penguin
- 'year' — Year of measurement

---

## Tools & Libraries
- **Python**
- **Pandas** — Data manipulation & analysis
- **NumPy** — Numerical computations
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical plotting

---

## EDA Steps
1. **Data Loading & Inspection**  
   - 'df.head()', 'df.info()', 'df.describe()', 'df.isnull().sum()'
2. **Data Cleaning**  
   - Handling missing values  
   - Removing duplicates  
3. **Univariate Analysis**  
   - Histograms  
   - Boxplots  
   - Countplots  
4. **Bivariate Analysis**  
   - Scatterplots  
   - Pairplots  
   - Grouped statistics  
5. **Correlation Analysis**  
   - Correlation heatmap  
6. **Observations & Summary**  
   - Written insights for each plot  
   - Overall findings from the dataset

---

## Key Observations
1. **Histograms:** Gentoo penguins have the highest body mass (~5,000g).  
2. **Boxplots:** Adelie species have less variation in size, Chinstrap shows a few outliers.  
3. **Countplots:** Adelie species are the most frequent; gender distribution is mostly balanced.  
4. **Pairplot:** Flipper length and body mass have a strong positive correlation.  
5. **Scatterplot:** Gentoo penguins form a distinct cluster due to larger size.  
6. **Heatmap:** Flipper length & body mass correlation ≈ 0.87; bill length & bill depth show moderate negative correlation.

---

## Summary of Findings
- The dataset contains three distinct species with unique morphological traits.  
- Gentoo penguins are largest; Adelie penguins are smallest.  
- Flipper length is strongly correlated with body mass.  
- Gender distribution is nearly balanced, with a few missing values.  
- Outliers in Chinstrap body mass may require further study.

---

## Files in Repository
- `penguins.csv` — Dataset  
- `penguins_eda.ipynb` — Jupyter Notebook with full EDA code  
- `penguins_EDA.pdf` — Exported PDF of notebook with plots & insights  
- `README.md` — Project documentation (this file)

