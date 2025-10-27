# NFL 2025 Offensive Analytics

This repository contains **NFL offensive analytics visualizations** for the 2025 season, built using R and the `nflfastR` play-by-play dataset. The analysis focuses on **team offensive tendencies, efficiency, and play volume** to provide insights that are especially useful for **fantasy football decisions**.

---

## Project Overview

- Analyze **total passes, runs, and passing rate** for each NFL team.
- Identify teams as **Pass-Heavy, Run-Heavy, or Balanced**.
- Visualize **top 10 passing and rushing teams** using **team logos** and colors.
- Evaluate **team efficiency per play** using **Expected Points Added (EPA)**.
- Use **professional, intuitive visualizations** for storytelling.

---

## Data Source

- **NFL Play-by-Play Data:** `nflfastR` package, 2025 season.
- **Team Logos and Colors:** `teams_colors_logos` from `nflfastR`.

---

## Visualizations

1. **Scatter Plot:** Passing Rate vs Total Offensive Plays  
   - Teams represented by logos, grouped by playstyle (Pass-Heavy, Run-Heavy, Balanced).
   - Shows which teams rely more on passing or rushing.

2. **Top 10 Passing Yards Teams:** Horizontal bar chart with logos.  
3. **Top 10 Rushing Yards Teams:** Horizontal bar chart with logos.  
4. **Team Efficiency (EPA per Play):** Side-by-side horizontal bars for passing vs running efficiency.
