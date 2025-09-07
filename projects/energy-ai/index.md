---
layout: default
title: Energy & AI — Electricity Consumption
permalink: /projects/energy-ai/
---

{% include nav.html %}

# Energy & AI — Electricity Consumption

> **Guiding question:** How does AI-related electricity demand compare with global energy trends and emissions?

---

## Line vs Stacked Area (Energy Mix)

> **Guiding question:** How does the choice of visualization affect our perception of renewable energy growth compared to fossil fuels?

> A line chart of renewables suggests they’re on a strong rise — almost overtaking fossil fuels. But when we switch to a stacked area chart, we see a different picture: coal and gas still dominate the global electricity mix. **Takeaway:** chart type can dramatically shift perception.

### Line Chart — Growth of Different Energy Types
<div style="width:100%;max-width:1400px;margin:0 auto;">
  <iframe src="/projects/energy-ai/line_chart_energy_mix.html" width="100%" height="640" style="border:none;"></iframe>
</div>

### Stacked Area Chart — Contribution of Different Energy Types
<div style="width:100%;max-width:1400px;margin:0 auto;">
  <iframe src="/projects/energy-ai/stacked_area_energy_mix.html" width="100%" height="640" style="border:none;"></iframe>
</div>

### Bar Chart — Electricity by Source (2022)
<div style="width:100%;max-width:1400px;margin:0 auto;">
  <iframe src="/projects/energy-ai/bar_chart_energy_mix.html" width="100%" height="640" style="border:none;"></iframe>
</div>

---

## Grouped Bar Chart (Future Scenarios)

> **Guiding question:** What possible futures do we see for AI data center electricity demand, and how do scenarios compare?

> **Base:** Steady growth continuing broadly as today.  
> **Lift-Off:** Rapid adoption, fueled by investment and policy leniency.  
> **High Efficiency:** Technology & operational breakthroughs improve efficiency (e.g., advanced cooling, optimization).  
> **Headwinds:** Growth slows due to economic conditions, regulation, or demand pullback.

<div style="width:100%;max-width:1400px;margin:0 auto;">
  <iframe src="/projects/energy-ai/iea_energy_ai_grouped_bar_chart.html" width="100%" height="640" style="border:none;"></iframe>
</div>

---

## Energy & AI — Data Center Types & Metrics

The following visualizations compare three types of AI data centers:

- **Hyperscale** — Owned by giant tech companies (e.g., Meta, Google, Microsoft).
- **Colocation & Service Providers** — Third-party facilities (e.g., Equinix) that rent space/power/cooling.
- **Enterprise** — Owned by a single organization (e.g., a bank or hospital) for internal use.

**Key metrics:**
- **Installed Capacity (GW):** Maximum power draw (size of facility power supply).  
- **Power Usage Effectiveness (PUE):** Total facility energy ÷ IT energy (lower is better).  
- **Load Factor:** Actual consumption ÷ (capacity × time) — utilization level.

> **Guiding question:** How do hyperscale, colocation, and enterprise data centers differ in scale, efficiency, and utilization?

> Hyperscale data centers — owned by tech giants — clearly stand apart. With deep expertise and resources, they optimize for efficiency (low PUE) and utilization (high load factor). Colocation/service providers and enterprise data centers are still playing catch-up. The bubble chart makes these differences easy to see at a glance.

### Bubble Chart — Capacity vs Load Factor (Bubble = PUE)
<div style="width:100%;max-width:1400px;margin:0 auto;">
  <iframe src="/projects/energy-ai/iea_energy_ai_bubble_chart.html" width="100%" height="640" style="border:none;"></iframe>
</div>

---

## Regional Line Chart (AI Data Center Consumption)

> **Guiding question:** Which regions are consuming the most electricity for AI data centers, and what might explain these differences?

> The United States currently leads, followed by China, then Europe. One possible reason: Europe’s more proactive digital/AI regulation and energy policy have moderated growth, while the U.S. and China have pursued more aggressive expansion.

<div style="width:100%;max-width:1400px;margin:0 auto;">
  <iframe src="/projects/energy-ai/iea_energy_ai_line_chart.html" width="100%" height="640" style="border:none;"></iframe>
</div>

### Dumbbell Chart — 2024 → 2030 Change by Data Center Type
<div style="width:100%;max-width:1400px;margin:0 auto;">
  <iframe src="/projects/energy-ai/iea_energy_ai_dumbbell_chart.html" width="100%" height="640" style="border:none;"></iframe>
</div>

---

## Choropleth — CO₂ Emissions Per Capita

> **Guiding question:** Which countries have the highest CO₂ emissions per person, and what does that reveal about lifestyle, infrastructure, and inequality in energy use?

> Before looking at the choropleth, I assumed India and China would have the highest CO₂ per capita because of their large populations. The data showed the opposite: the U.S., Canada, and Australia are higher. **Per capita** emissions reflect lifestyle and infrastructure (energy-intensive housing, transport, industry) rather than population size alone.

<div style="width:100%;max-width:1400px;margin:0 auto;">
  <iframe src="/projects/energy-ai/co2_emissions_choropleth.html" width="100%" height="640" style="border:none;"></iframe>
</div>

> **Tip:** Hover to see exact values. Use the legend to toggle scenarios or categories where available.

---
