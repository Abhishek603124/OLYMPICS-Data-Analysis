# 🏅 Olympic Medal Analysis

This project presents an in-depth analysis of athletes and medal distributions across different Olympic Games using the **Athlete Events** and **NOC Regions** datasets. The analysis focuses on medal tallies, trends over time, and participation diversity, utilizing powerful data handling and visualization tools in Python.

---

## 📁 Dataset Used

- **`athlete_events.csv`**  
  Contains athlete-level data including demographics, sport, event, and medal information.

- **`noc_regions.csv`**  
  Maps National Olympic Committee (NOC) codes to corresponding countries/regions.

---

## 📊 Key Steps & Analysis

### 1. 🔄 Data Loading & Cleaning
- Loaded datasets using `pandas`.
- Filtered for **Summer Olympics** only.
- Merged region data with athlete information via NOC codes.
- Removed duplicate entries for consistent analysis.

### 2. ⚙️ Feature Engineering
- Created binary indicators for medal types (Gold, Silver, Bronze).
- Used `groupby` operations to aggregate medal data by country and year.

### 3. 🥇 Medal Tally Calculation
- Computed sorted medal tallies by country using aggregation.
- Calculated total medals per nation.
- Defined a function `fetch_medal_tally(year, country)` to retrieve medal stats dynamically.

### 4. 📈 Exploratory Data Analysis (EDA)
- Explored diversity in:
  - Countries (NOC codes)
  - Sports and Events
  - Age distributions of athletes
- Analyzed growth in number of participating countries over Olympic editions.

### 5. 📊 Data Visualization
- Created interactive line charts using **Plotly Express** to visualize country participation over time.
- Utilized **Seaborn** and **Matplotlib** for in-depth statistical plots and trends (e.g., athlete age distributions, sport-wise participation).

---

## 🛠️ Tech Stack

- Python 3
- Pandas
- Seaborn
- Matplotlib
- Plotly Express
- Jupyter / Colab

---

## 📌 Outcomes

- Built reusable functions for flexible medal queries.
- Derived actionable insights on Olympic trends, athlete demographics, and national performances.
- Visualized complex data using both static and interactive charts for better interpretation.

---

## 🚀 Future Enhancements

- Include analysis for Winter Olympics.
- Add medal prediction models using machine learning.
- Deploy interactive dashboard using Streamlit or Dash.

---

## 👤 Author

**Abhishek Singh**  
GitHub: [@Abhishek603124](https://github.com/Abhishek603124)
