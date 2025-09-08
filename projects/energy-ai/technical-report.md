# Technical Report – Project 1  
**Course:** Visual Analytics  
**Student:** Chirasmayee B  
**Project:** Energy & AI — Electricity Consumption  

---

## 1. Dataset Origin & Description  

### IEA Energy & AI Dataset  
- **Source:** International Energy Agency (IEA)  
- **Content:** Projections of AI data center electricity demand under four scenarios: Base, Lift-Off, High Efficiency, Headwinds.  
- **Variables:** Installed capacity (GW), Power Usage Effectiveness (PUE), Load Factor, regional breakdowns, data center types (Hyperscale, Colocation & Service Provider, Enterprise).  
- **Structure:** Multiple sheets by region and type; structured around years (2020, 2023, 2024, 2030, 2035).  

### OWID Energy Mix Dataset  
- **Source:** Our World in Data (OWID)  
- **Content:** Annual electricity generation and demand by source (coal, gas, renewables, nuclear, etc.) for each country.  
- **Variables:** Electricity generation (TWh), per capita demand, shares of renewables/fossils, carbon intensity.  
- **Structure:** Country–year rows; 100+ columns of energy variables.  

### OWID CO₂ Emissions Dataset  
- **Source:** Our World in Data (OWID)  
- **Content:** CO₂ emissions per capita, total CO₂, emissions by source (coal, oil, gas), global + regional data.  
- **Variables:** Tons per capita, tons total, by year and country.  
- **Structure:** Country–year rows spanning 1750–2023.  

---

## 2. Preprocessing & Cleaning  

- **IEA Dataset:**  
  - Extracted specific rows for Hyperscale, CSP, Enterprise.  
  - Reshaped wide sheets into tidy Year–Scenario–Value format.  
  - Dropped blank cells and footnotes.  

- **OWID Energy Mix:**  
  - Filtered variables relevant to electricity mix (coal, gas, renewables).  
  - Selected years 2000–2022 for clarity.  
  - Aggregated world-level and regional totals.  

- **OWID CO₂ Emissions:**  
  - Focused on per capita emissions.  
  - Filtered for selected years and key countries (U.S., China, India, Canada, Australia).  
  - Removed missing/nulls in early historical data.  

---

## 3. Visualization & Design Choices  

- **Line vs Stacked Area Chart (Energy Mix):**  
  - Line highlights growth of renewables, but risks misinterpretation.  
  - Stacked area contextualizes relative share → shows fossils still dominate.  

- **Grouped Bar Chart (IEA Scenarios):**  
  - Useful to compare multiple futures side by side.  
  - Clearer than separate lines, avoids gaps between projection years.  

- **Bubble Chart (Data Center Types):**  
  - X = Installed Capacity, Y = Load Factor, Bubble size = PUE.  
  - 3 metrics in one view → performance differences visible.  

- **Regional Line Chart:**  
  - Shows U.S., China, Europe electricity consumption.  
  - Interpretive story: Europe’s stricter regulation vs U.S. & China’s expansion.  

- **Dumbbell Chart:**  
  - Highlights small changes between 2024 and 2030.  
  - More effective than absolute bar/line values.  

- **Choropleth (CO₂ Per Capita):**  
  - Captures inequality in emissions across regions.  
  - Developed countries have much higher per capita emissions than populous nations like India.  

---

## 4. Reflection  

- **What worked:**  
  - Chart variety revealed different perspectives on the same data.  
  - Storytelling examples (line vs stacked area, bubble vs scatter) highlighted perception shifts.  
  - Interactive visualizations (choropleth, bubble) engaged more than static plots.  

- **Challenges:**  
  - IEA dataset required reshaping across multiple sheets.  
  - OWID datasets were very wide; filtering needed to avoid clutter.  
  - Balancing code vs storytelling was tricky → solved by separating portfolio post from technical report.  

- **Next steps / improvements:**  
  - Add statistical analysis (e.g., correlations between AI demand and CO₂ emissions).  
  - Improve annotations in charts to highlight insights directly.  
  - Consider building a dashboard to connect datasets interactively.  

---

## 5. Code  

- **GitHub Repo:** [https://github.com/chiru-2001/chiru-2001.github.io/tree/master/projects/energy-ai]  
- **Notebook:** Jupyter Notebook with preprocessing + Plotly visualizations included.  
- Code is reproducible with the following packages:  
  - `pandas`  
  - `plotly`  
  - `matplotlib`  
  - `openpyxl`  

---
