# ISON Johannesburg — Sales Dashboard

> Interactive sales performance dashboard for ISON Johannesburg BPO · May 2026 MTD

## Live Demo

Open `index.html` in any browser — no build step, no server required.  
Or host for free on **GitHub Pages** (see below).

---

## What's Inside

| Metric | Value |
|---|---|
| Total Sales | 8,874 |
| Cancellations | 331 (3.73%) |
| Monthly Premium | R356,891 incl. VAT |
| Active Agents | 113 across 8 team leaders |

### Charts & Panels
- **Daily Sales & Cancellations** — line chart for May 4–30
- **Product Mix** — ranked bar list of 8 DStv products
- **Team Leader Performance** — bar + cancel rate per TL
- **Top 10 Agents** — ranked by sales with colour-coded cancel rate pills
- **Cancel Rate by TL** — horizontal bar, colour-coded (green / amber / red)
- **Sales Share** — doughnut chart with legend

---

## Tech Stack

- Pure **HTML + CSS + vanilla JS** — zero dependencies to install
- **[Chart.js 4.4.1](https://www.chartjs.org/)** loaded from CDN
- Supports **light & dark mode** via `prefers-color-scheme`
- Fully **responsive** down to mobile

---

## How to Deploy on GitHub Pages

```bash
# 1. Create a new repo on github.com, then:
git init
git add .
git commit -m "feat: add ISON sales dashboard"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/ison-dashboard.git
git push -u origin main
```

Then in your repo go to **Settings → Pages → Source → main branch / root** and click **Save**.  
Your dashboard will be live at `https://YOUR_USERNAME.github.io/ison-dashboard/`

---

## Local Preview

```bash
# Option A — just open the file
open index.html

# Option B — serve locally (Python)
python3 -m http.server 8080
# then visit http://localhost:8080
```

---

## Data

Data is embedded directly in `index.html` from the ISON Johannesburg MTD Sales report (May 2026).  
To update with new data, edit the `tlData`, `daily`, `products`, and `agents` arrays in the `<script>` block at the bottom of `index.html`.

---

*Generated with Claude (Anthropic) · June 2026*
