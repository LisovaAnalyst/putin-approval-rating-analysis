# Autocratic Stability: Putin's Approval Rating Analysis (1999–2026)

A comprehensive data analytics project investigating the socio-political dynamics and public opinion stability in Russia over a 26-year timeline. This project utilizes quarterly data from the independent Levada-Center to decode how geopolitical shocks, economic crises, and state control transform public support.

---

## 📊 Core Analytical Insights

* **The Volatility Trajectory:** Linear analysis reveals that historical approval peaks strictly correlate with major military escalations (1999, 2008, 2014, 2022), reflecting the classic *'rally around the flag'* sociological phenomenon.
* **The Decay Rate Shift:** Comparative analysis of ratings at the event peak versus 1 year later highlights a regime evolution. While popularity from the Chechen (1999) and Georgian (2008) wars naturally faded within a year by 6–8%, post-2022 ratings remain artificially "cemented" ($82\% \rightarrow 80\%$).
* **Statistical Suppression (IQR):** Interquartile Range (IQR) analysis using boxplots mathematically proves that the **War Era (2022–2026)** has the narrowest variance in modern Russian history. This compressed distribution visualizes the transition from a hybrid autocracy to total information suppression, where fear alters polling behavior.

---

## 📈 Visualizations Included

1. **`1_rating_timeline.png`**: Comprehensive time-series trend line annotated with key historical inflection points (Crimea, Bolotnaya, Pension Reform, Full-scale invasion).
2. **`2_war_decay_rate.png`**: Grouped bar chart comparing the resilience of wartime popularity shocks exactly 12 months post-escalation.
3. **`3_eras_boxplot.png`**: Boxplot distribution tracking rating variance and median shifts across four distinct political eras.

---

## 🛠️ Tech Stack & Methodology

* **Language:** Python
* **Data Manipulation:** `pandas` (Data aggregation, handling missing/bad lines, feature engineering).
* **Data Visualization:** `matplotlib.pyplot`, `seaborn` (Statistical visualization, customized theme architectures, precise annotations).
* **Source Material:** Independent Levada-Center quarterly polling dataset (1999 – Early 2026).

---

## 📂 Project Structure

```text
├── putin_approval_levada_1999_2026.csv  # Cleaned source dataset
├── putin_rating_analysis.ipynb          # Core Jupyter Notebook with documented Python code
├── 1_rating_timeline.png                # Exported Line Chart
├── 2_war_decay_rate.png                 # Exported Bar Chart
└── 3_eras_boxplot.png                  # Exported Boxplot Chart
