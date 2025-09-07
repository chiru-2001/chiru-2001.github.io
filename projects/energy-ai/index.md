---
layout: default
title: Energy & AI — Electricity Consumption
permalink: /projects/energy-ai/
---

{% include nav.html %}

# Line vs Stacked Area (Energy Mix)

How does the choice of visualization affect our perception of renewable energy growth compared to fossil fuels?

“A line chart of renewables suggests they’re on a strong rise — almost overtaking fossil fuels. But when we switch to a stacked area chart, we see a different picture: coal and gas still dominate the global electricity mix. The takeaway? Chart type can dramatically shift perception.”

# Line Chart - Growth of Different Energy Types

<iframe src="/projects/energy-ai/line_chart_energy_mix.html"
        width="100%" height="640" style="border:none;"></iframe>

# Stacked Area Chart - Contribution of Different Energy Types
        
<iframe src="/projects/energy-ai/stacked_area_energy_mix.html"
        width="100%" height="640" style="border:none;"></iframe>

# Bar Chart - Electricity produced by Different Energy Types in Year 2022

<iframe src="/projects/energy-ai/bar_chart_energy_mix.html"
        width="100%" height="640" style="border:none;"></iframe>

# Grouped Bar Chart (Future Scenarios)

What possible futures do we see for AI data center electricity demand, and how do scenarios like Base, Lift-Off, High Efficiency, and Headwinds compare?

“The projections for AI data centers diverge depending on which future unfolds:

**Base Case** → things continue as they are today, with steady growth in AI demand.

**Lift-Off** → rapid adoption, fueled by investment and government leniency.

**High Efficiency** → breakthroughs in technology (e.g., advanced cooling, maybe even quantum computing) make data centers much more efficient.

**Headwinds** → AI growth stalls, perhaps due to economic downturns, stricter regulations, or even an ‘AI bubble’ bursting.”

<div style="width:100%; max-width:1400px; margin:0 auto;">
  <iframe src="/projects/energy-ai/iea_energy_ai_grouped_bar_chart.html" 
          width="100%" height="640" style="border:none;"></iframe>
</div>

# Energy & AI - Data Center Types & Metrics

The following visualizations show the performance of three types of AI data centers:

- **Hyperscale** – Data Centers owned by giant tech companies like Meta, Google, Microsoft
- **Colocation & Service Providers** – Third-party vendors that rent data centers to other companies - e.g. Equinix  
- **Enterprise** – Data Centers owned by a enterprise like a bank (non-tech company)

The performance of these types of data centers is measured by three factors:

- **Installed Capacity (GW)** – Total maximum power a data center can draw (size of its power supply).
- **Power Usage Effectiveness** – Total facility energy ÷ IT equipment energy (efficiency benchmark).
- **Load Factor** – Ratio of actual electricity consumed vs maximum possible (capacity × time).

How do hyperscale, colocation, and enterprise data centers differ in terms of scale, efficiency, and utilization?

“Hyperscale data centers — owned by tech giants like Google, Meta, and Amazon — clearly stand apart. With deep expertise and resources, they’ve optimized for efficiency (low PUE) and utilization (high load factor). In contrast, colocation/service providers and enterprise data centers are still playing catch-up. The bubble chart makes these differences easy to see at a glance.”

# Bubble Chart (IEA Data Centers)

<iframe src="/projects/energy-ai/iea_energy_ai_bubble_chart.html"
        width="100%" height="640" style="border:none;"></iframe>

Which regions are consuming the most electricity for AI data centers, and what might explain these differences?

“Looking at electricity consumption, the United States leads AI data centers by a wide margin, followed by China, then Europe. One possible reason? Europe has been more proactive in regulating AI and digital infrastructure, while the U.S. and China have taken a more aggressive growth approach.”

# Regional Line Chart (AI Data Center Consumption) 

<iframe src="/projects/energy-ai/iea_energy_ai_line_chart.html"
        width="100%" height="640" style="border:none;"></iframe>

<div style="width:100%; max-width:1400px; margin:0 auto;">
  <iframe src="/projects/energy-ai/iea_energy_ai_dumbbell_chart.html" 
          width="100%" height="640" style="border:none;"></iframe>
</div>

# Choropleth - CO2 Per Capita

Which countries have the highest CO₂ emissions per person, and what does this reveal about lifestyle, infrastructure, and inequality in energy use?

“Before looking at the choropleth, I assumed India and China would have the highest CO₂ per capita, because of their large populations. But the data showed the opposite: the U.S., Canada, and Australia are far higher. This makes sense — per capita emissions reflect lifestyle and infrastructure, not just population size. In countries like the U.S., more energy-hungry homes, cars, and industries drive up emissions per person, while in India emissions are spread across a much larger population.”

<iframe src="/projects/energy-ai/co2_emissions_choropleth.html"
        width="100%" height="640" style="border:none;"></iframe>

*Tip: Hover over points to see exact values. Use legend to toggle scenarios.*
