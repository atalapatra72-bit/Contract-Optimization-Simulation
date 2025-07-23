# Contract Optimization Simulation

By Arjun Talapatra

## 🔍 Objective

This project analyzes how NBA player performance evolves with age, using 2022–23 season data (539 players). We explore whether age 27 is truly a universal peak — or whether it varies across positions, volume stats, and efficiency metrics.

## 🛠️ Tools Used

- **SQLite (via DB Browser)** — for querying and aggregating the data
- **Tableau Public** — for visualizing player trends and comparisons
- **Excel** — for lightweight cleaning before import

## 📁 Dataset

- **Source**: https://www.kaggle.com/datasets/jamiewelsh2/nba-per-game-player-statistics-2022-2023-season
- Files Used:
  - `nba_per_game_processed.csv`
  - `nba_2022-23_all_stats.csv`

## 🧠 Key Analysis Areas

1. **Box Score Trends** – Points, rebounds, assists, etc., by age group
2. **Position-Specific Aging** – Differences in peak age for guards, wings, and bigs
3. **Advanced Metrics** – TS%, BPM, VORP, PER, and others
4. **Shot Selection** – Changes in FGA, 3PA, and FTA across age groups

## 📊 Key Findings

- Most volume stats peak between **ages 26–29**
- **Forwards** tend to peak later than guards and bigs
- **Guards** retain playmaking impact into their 30s (e.g. assists/game peaks at 30+)
- Shot diet shifts toward **more 3PA and fewer drives** after age 30
- Advanced metrics (TS%, BPM, etc.) also reflect a **position-based aging curve**

## 📈 Tableau Dashboard

https://public.tableau.com/app/profile/arjun.talapatra/viz/NBAProject_17520051567140/ShotSelection

## 📄 Report

See `https://github.com/atalapatra72-bit/NBA-Data-Analysis/blob/main/NBA%20Data%20Analysis%20Report.pdf` for the full write-up with methodology, SQL queries, and detailed charts.

## 🚀 Business Applications

- Smarter contract design: Avoid overpaying bigs in their 30s
- Development focus: Emphasize shooting for young bigs to extend career impact
- Roster strategy: Anchor cores around age 26–29, with veteran wings for support

## 🧪 Limitations

- One-season snapshot — does not reflect full-career arcs
- No injury-adjustment or minute thresholds applied
- Positions self-reported (may be inconsistent)

---

