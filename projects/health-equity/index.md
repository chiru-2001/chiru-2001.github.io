---
layout: default
title: Redesigning Health Equity — WHO Global Health Expenditure
permalink: /projects/health-equity/
---

{% include nav.html %}

<style>
  /* ===== Layout knobs you can tweak ===== */
  :root{
    --navH: 64px;          /* your nav height */
    --vizW: 1800px;        /* width of each full-screen panel */
    --bg: #ffffff;
  }

  /* Make the whole page horizontally scrollable */
  html, body {
    margin: 0; padding: 0;
    overflow-x: auto;          /* enable horizontal scroll */
    background: #f6f8fa;
  }

  /* Optional: hide the nav in true browser fullscreen */
  body:fullscreen nav, body:-webkit-full-screen nav { display: none !important; }

  /* A horizontal scroller that holds all panels side-by-side */
  .hscroll {
    display: flex;
    gap: 24px;
    padding: 16px 24px 40px;
    width: max-content;        /* expand to fit children */
  }

  /* Each panel = one full-screen “slide” */
  .panel {
    background: var(--bg);
    border-radius: 14px;
    box-shadow: 0 10px 30px rgba(0,0,0,.08);
    width: var(--vizW);                     /* super wide */
    height: calc(100vh - var(--navH) - 40px);
    padding: 12px 12px 0;
    display: flex;
    flex-direction: column;
  }

  .panel h2, .panel p.caption {
    margin: 8px 12px;
  }

  .viz-wrap {
    position: relative;
    flex: 1 1 auto;
    border-radius: 10px;
    overflow: hidden;
    background: #fff;
  }

  .viz-wrap iframe {
    position: absolute; inset: 0;
    width: 100%; height: 100%;
    border: 0;
  }

  /* Center the page title and keep normal vertical flow above the scroller */
  .page-intro { max-width: 900px; margin: 0 auto 12px; text-align: center; }
</style>

<!-- Optional: keep your nav include as-is -->

{% include nav.html %}


<div class="page-intro">
  <h1>🩺 Redesigning Health Equity — WHO Global Health Expenditure</h1>
  <p>Scroll <b>horizontally</b> to view each full-screen panel.</p>
</div>

<div class="hscroll">
  <!-- Panel 1 -->
  <section class="panel">
    <h2>1️⃣ Who Can Afford Care</h2>
    <p class="caption">CHE per capita by income group, 2000–2022. Use filters in the viz.</p>
    <div class="viz-wrap">
      <iframe
        src="https://public.tableau.com/views/Project2_17591302209210/Dashboard1?:showVizHome=no&:embed=true"
        loading="lazy"
        allowfullscreen
      ></iframe>
    </div>
  </section>

  <!-- Panel 2 -->
  <section class="panel">
    <h2>2️⃣ Who Pays for Care?</h2>
    <p class="caption">Goverment Spending and Out Of Pocket</p>
    <div class="viz-wrap">
      <iframe
        src="https://public.tableau.com/views/Project2_17591302209210/Dashboard4?:showVizHome=no&:embed=true"
        loading="lazy"
        allowfullscreen
      ></iframe>
    </div>
  </section>

  <!-- Panel 3 -->
  <section class="panel">
    <h2>3️⃣ The Care Gap</h2>
    <p class="caption">Country distribution of CHE per capita (2022), grouped by income.</p>
    <div class="viz-wrap">
      <iframe
        src="https://public.tableau.com/views/Project2_17591302209210/Dashboard3?:showVizHome=no&:embed=true"
        loading="lazy"
        allowfullscreen
      ></iframe>
    </div>
  </section>
</div>
---

## ✳️ Design Principles Applied

**Gestalt Principles** — Alignment, proximity, and color similarity unify the dashboards into one story.  
**Pre-attentive Attributes** — Size and hue highlight high-income vs low-income differences instantly.  
**Clutter Reduction** — Minimal legends and muted gridlines improve focus.  
**Color Psychology** — Cool blues represent stability and investment; warm oranges suggest strain and scarcity.  
**Storytelling Flow** — Question-based sections guide the viewer from *who can afford care* → *who pays* → *who is left behind*.

---

## 🎯 Key Takeaways

- **Wealth shapes health:** Income remains the strongest predictor of healthcare access.  
- **Public funding matters:** Countries investing through government spending reduce household risk.  
- **Design reveals inequality:** Clean, minimal visuals make disparities both intuitive and undeniable.

---

## Explore the Full Interactive Dashboard
[View on Tableau Public →]([https://public.tableau.com/views/GlobalHealthDashboard/Overview](https://public.tableau.com/views/Project2_17591302209210/Story1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link))

