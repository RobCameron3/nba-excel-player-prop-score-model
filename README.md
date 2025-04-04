# 🏀 NBA Excel Player Prop & Game Simulation Model (Windows-Based)

This Excel model simulates **NBA player stats and game outcomes** using real data from Basketball Reference. Designed specifically for **Windows Excel**, it includes dynamic Power Query connections, roster logic, and advanced statistical formulas for predictive modeling — all within Excel.

---

## 🔧 Key Features

### ✅ Automated Roster & Injury Updates
- Pulls **per-game player stats** from Basketball Reference via Power Query
- Easily switch seasons by modifying the URL (e.g., `NBA_2023_per_game.html`, `NBA_2024_per_game.html`)
- Tracks **active/injured players** via CBS Sports NBA Injury Report and removes them from simulations

### 🎯 Game Simulation Logic
- Simulates full team scoring based on predicted minutes and player performance
- Automatically determines **Win or Loss** outcomes across thousands of trials
- Calculates **team win percentages** based on simulation results
- Uses **color-coded formatting with custom icons** for clean visual output

### 📊 Player Scoring Probabilities
- Calculates the probability that each player scores:
  - 10+ points  
  - 15+  
  - 20+  
  - 25+  
  - 30+  
  - 35+  
  - 40+  
- Based on actual averages and projected game minutes

### 📈 Over/Under Game Totals
- Simulates total combined points for each matchup
- Shows exact **% chance that game totals exceed common thresholds** (e.g. 130, 150, 200, etc.)
- Helps model prop-style outcomes or public-facing content for betting/strategy discussions

---

## 🧠 Real-World Applications

- 📊 **Data analysts**: Showcase advanced Excel modeling
- 🎥 **Content creators**: Use for matchup breakdowns or simulations
- 📈 **DFS players or bettors**: Analyze player output & game flow probabilities
- 🧠 **Portfolio builders**: Demonstrate statistical thinking and spreadsheet design

---

## ⚙️ Setup Instructions

1. Open in **Windows Excel**
2. Go to `Data > Refresh All` to pull current injury & stat data
3. Select any two teams for a matchup
4. Model updates automatically with:
   - Player stats
   - Active roster
   - Simulated team scores
   - Scoring probabilities
   - Game outcome %s

---

## 📁 Included Files

| File | Description |
|------|-------------|
| `NBA_Game_Simulation_Model.xlsx` | Main Excel-based simulation model |
| `README.md` | Project overview & usage guide |
| `media/` (optional) | Screenshots or walkthroughs |

---

## 📡 Data Sources

- 🏀 [Basketball Reference – Per Game Stats](https://www.basketball-reference.com/leagues/NBA_2023_per_game.html)
- 🩼 [CBS Sports – NBA Injury Tracker](https://www.cbssports.com/nba/injuries/)

---

## 🧰 Tools Used

- Microsoft Excel (Windows)
- Power Query (HTML import)
- Advanced formulas: `XLOOKUP`, `INDEX`, `IFERROR`, `SMALL`, dynamic named ranges, conditional formatting

---
