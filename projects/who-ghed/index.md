---
layout: default
title: Global Health Expenditure Dashboard — WHO Data
permalink: /projects/who-ghed/
---

{% include nav.html %}

# 🌍 WHO Global Health Expenditure Dashboard

**Live Dashboard:**  
[View the interactive Tableau Dashboard →](https://public.tableau.com/app/profile/your-link-here)  
*(Hosted on Tableau Public)*  

---

## 🩺 Project Overview

This dashboard explores **global patterns in healthcare spending**, based on data from the **World Health Organization (WHO) Global Health Expenditure Database (2000–2022)**.  
It focuses on understanding **how income and region influence healthcare affordability, financing, and equity** across the world.

The interactive dashboard is designed for **policy analysts, researchers, and global health organizations** who want to track **key performance indicators (KPIs)** and compare health financing structures across income and regional lines.

---

## 📊 Key Performance Indicators (KPI Cards)

The dashboard opens with four KPI cards that summarize global health spending measures:

| KPI | Description | Interpretation |
|------|--------------|----------------|
| **CHE per Capita (USD)** | Health expenditure per person | Reflects how much is invested in an average citizen’s healthcare |
| **CHE as % of GDP** | Share of total economic output spent on health | Indicates national health spending priority |
| **Government Health Expenditure (% CHE)** | Public share of total spending | Higher values = stronger government role |
| **Out-of-Pocket Expenditure (% CHE)** | Portion paid directly by households | Higher values = less financial protection |

🧭 *Users can filter by Year and WHO Region to explore temporal and spatial trends.*

---

## 📈 Health Spending Over Time (Line Charts)

These line charts track **average CHE per capita** and **CHE as % of GDP** from 2000–2022 by WHO region.

> **Insight:**  
> - High-income regions such as **Europe and the Americas** maintain steady growth and high per capita spending.  
> - **African and South-East Asian** regions show gradual increases, but the gap remains large.  
> - This demonstrates how **economic growth strongly correlates with health spending capacity.**

---

## 🧮 Regional Composition of Health Financing (Stacked Bar Chart)

This visualization compares **Government**, **Out-of-Pocket**, and **External** spending as shares of total health expenditure, grouped by **income class**.

> **Insight:**  
> - High-income countries rely heavily on **government spending**, offering stronger financial protection.  
> - In contrast, **low- and lower-middle-income countries** depend more on **out-of-pocket** and **external funding**, revealing greater vulnerability and inequity.  
> - The stacked structure visually emphasizes how the balance of financing shifts with national income.

---

## 💵 Health Expenditure Distribution by Income (Jittered Plot)

Each dot represents a **country’s per capita health expenditure**, color-coded by income group.

> **Insight:**  
> - High-income countries cluster far above the rest, with some exceeding \$10,000 per person.  
> - The spread in **upper-middle** and **lower-middle** income groups shows internal inequality — some nations perform far better than others within the same tier.  
> - The bottom-heavy distribution highlights how **income inequality drives healthcare inequity** globally.

*(A jitter effect is applied to prevent overlap and reveal individual countries.)*

---

## 🗺️ Regional Overview Map

A **choropleth map** visualizes each country by its **WHO region**, allowing users to identify where spending disparities cluster geographically.

> **Insight:**  
> - The map provides a global context for the other charts, making it easy to see regional composition and membership.  
> - Users can hover or filter by region to focus on specific geographic patterns.

---

## 🎯 Dashboard Interactivity & Design Choices

- **Unified Filters**: Year and Region filters control all charts simultaneously.  
- **Color Encoding**: Consistent regional and income color palettes aid pattern recognition.  
- **Layout Flow**: KPI summary → Trend → Distribution → Composition → Map.  
- **Tooltips**: Provide details such as region, income class, and expenditure values.  
- **Responsiveness**: Designed to display cleanly on Tableau Public and embedded views.

---

## 🧠 Reflections

Designing this dashboard showed how **interactivity transforms analysis into exploration**:
- Users can discover their own insights rather than being told a fixed narrative.  
- Linking region, year, and income together helps expose underlying **health financing inequities**.  

> The project reinforced the idea that *data visualization isn’t just about showing data — it’s about revealing structure, context, and fairness.*

---

### 📎 Resources

- **Dataset**: [WHO Global Health Expenditure Database (2025)](https://apps.who.int/nha/database/DocumentationCentre/Index/en)  
- **Dashboard**: [View on Tableau Public](https://public.tableau.com/app/profile/venkata.sai.chirasmayee.b/viz/Project2_17591302209210/Story1)  
- **Author**: Chirasmayee B. — UNC Charlotte, Visual Analytics

---

*Last updated: {{ site.time | date: "%B %Y" }}*

