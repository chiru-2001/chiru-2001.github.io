# Project 3 — Design Report  
### *AI’s Carbon Footprint: The Energy Race We’re Not Ready For*  
**Course:** Visual Analytics (Fall 2025)  
**Student:** Chirasmayee B  
**Tool:** Plotly + HTML + Netlify Deployment  
**Data Sources:** IEA Energy & AI (2024), OWID Energy Data (2024), OWID CO₂ Emissions (2024)  

---

## 1. Audience & Intent
This dashboard is designed for a **general public and policy-minded audience** — readers who have heard about the rapid rise of artificial intelligence but may not have considered its **environmental cost**.  

The intent is to make users **feel the scale and urgency** of AI’s energy use, to see **how it connects to global energy dependence and carbon inequality**, and to leave with a **call to rethink how AI is powered** — not just how fast it grows.

**What I want them to learn, feel, or do:**
- **Learn:** AI data centers already consume electricity comparable to small nations, and this demand will grow exponentially.  
- **Feel:** AI progress has a tangible energy and carbon footprint; innovation is not free.  
- **Do:** Advocate for sustainable AI development, policy action, and investment in green data-center infrastructure.  

---

## 2. Story & Structure
The visualization follows a **narrative progression** — each section answers one question that naturally leads to the next:  

| Story Section | Visual | Question Answered |
|----------------|---------|-------------------|
| **1. The Rise of AI’s Energy Appetite** | IEA Grouped Bar Chart | How fast is AI electricity demand growing under different scenarios? |
| **2. Where Does This Energy Come From?** | OWID Energy Mix Stacked Area | What fuels power AI computation? |
| **3. The Carbon Cost of Intelligence** | CO₂ Emissions Choropleth | Which regions generate AI’s electricity most cleanly or dirtily? |
| **4. The Unequal Impact** | Combined text + context | Who bears the externalities of AI’s energy race? |
| **5. A Call to Design Better Futures** | Reflection section | How can we power AI responsibly? |

The story moves from **data to implication to emotion**, intentionally narrowing from the global energy system to human accountability.

---

## 3. Design Choices

### Color Palette  
A consistent palette reinforces meaning throughout:
| Concept | Color | Purpose |
|----------|--------|---------|
| Primary Blue `#2B6CB0` | AI / Technology | Header & titles |
| Accent Orange `#ED8936` | Energy Growth / Warning | IEA bars |
| Green `#68D391` | Renewables / Hope | Clean energy areas |
| Red `#E53E3E` | CO₂ / Risk | High emission regions |
| Gray `#4A5568` + `#F7FAFC` | Neutral text / background | Clarity & balance |

### Layout & Typography  
- **Vertical storytelling layout**: one chart per section with contextual text; the reader scrolls linearly like reading an article.  
- **Typography:** system-UI font family for accessibility and clean readability.  
- **Whitespace & clutter reduction:** generous padding, soft drop-shadows, rounded cards. No gridlines, legends trimmed for clarity.  
- **KPI cards:** minimalist white panels with short titles, bold numerals, and captions — a quick factual snapshot before deeper visuals.  

### Perception & Design Principles Applied  
- **Gestalt Proximity & Similarity:** Related visuals (KPI cards) grouped together; shared background color and consistent spacing unify them.  
- **Pre-attentive Attributes:** Color and size draw attention — the orange “Lift-Off 2035” bar stands out immediately.  
- **Clutter Reduction:** Only the essential data-ink retained; legends, gridlines, and axes are minimal.  
- **Focus & Hierarchy:** Headings use blue for continuity; key metrics in contrasting colors to guide reading order.  

---

## 4. Reflection
**What worked well**
- The **narrative flow** feels natural — the reader scrolls through a complete cause-effect story.  
- The **color harmony** unites three very different datasets visually.  
- The **KPI cards** set the tone immediately with context before data deep-dives.  

**Challenges**
- Balancing **data authenticity vs. design cohesion** — different sources had varied structures, requiring preprocessing.  
- Keeping the **Plotly visuals responsive** in Netlify without distortion.  
- Achieving narrative emotion while maintaining factual precision.  

**If given more time**
- Add a **carbon-intensity-per-TWh** metric to connect AI demand directly to emissions.  
- Integrate a small **interactive slider** to simulate efficiency gains.  
- Explore **animated transitions** between charts for smoother storytelling.  

---

## 5. Access & Publication
**Live Dashboard:** [https://ai-energy-footprint.netlify.app](https://ai-energy-footprint.netlify.app)  
**Source Code & Data:**  
- `/plots/` — HTML exports of Plotly visuals (IEA Grouped Bar, Energy Mix, CO₂ Map)  
- `/data/` — Cleaned IEA and OWID datasets (2024)  
- `index.html` — Story layout + styling  
- Hosted on **Netlify Drop** for public access.  

---

### Final Reflection Line
> *AI’s intelligence may be artificial — but its emissions are real.*  
> The design of our energy future will decide whether the next wave of intelligence is **sustainable or self-destructive.**

