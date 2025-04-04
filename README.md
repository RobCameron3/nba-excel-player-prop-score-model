# 🏀 NBA Excel Player Prop & Game Simulation Model (Windows-Based)

This Excel model simulates **NBA player stats and game outcomes** using real data from Basketball Reference. Designed specifically for **Windows Excel**, it features Power Query connections, dynamic roster logic, and advanced statistical formulas — all within Excel.

----

## 🔧 Key Features

### ✅ Dynamic Injury-Adjusted Simulation
> 💡 **The best part**: The model **automatically adjusts game outcomes based on live injury reports**. If a player is injured (per CBS Sports), they are removed from the rotation — affecting team scoring, player opportunities, and simulation results in real-time.

- Integrates with the [CBS Sports Injury Report](https://www.cbssports.com/nba/injuries/)
- Automatically removes injured players from the roster
- Updates team scoring projections and win percentages accordingly
- Ensures your simulation reflects **real-time availability**

---

### 📈 Stat + Simulation Highlights

- Pulls **per-game player stats** from [Basketball Reference](https://www.basketball-reference.com/leagues/NBA_2023_per_game.html)
- Supports **year switching** by changing the season in the query URL
- Calculates **Win or Loss outcomes** across 1,000+ game simulations
- Shows **player scoring probabilities**: 10+, 15+, 20+, … up to 40+
- Includes color-coded visual feedback for wins/losses and scoring tiers
- Built with `XLOOKUP`, `INDEX`, `IFERROR`, `SMALL`, and dynamic logic

---

## 🧠 Real-World Applications

- 📊 **Data analysts**: Show off live-adjusted player/team modeling
- 🎥 **Content creators**: Use for dynamic game preview simulations
- 🧠 **Fantasy/DFS players**: Adjust strategy in real time based on injury news
- 💼 **Portfolio builders**: Demonstrate advanced Excel automation

---

## ⚙️ Setup Instructions

1. Open the file in **Windows Excel**
2. Click `Data > Refresh All` to pull live injury and player stat data
3. Select two teams for your matchup
4. The model auto-updates:
   - Player stats
   - Injured player exclusions
   - Team scoring simulations
   - Scoring probabilities and game outcomes

---

## 📁 Included Files

| File | Description |
|------|-------------|
| `NBA_Game_Simulation_Model.xlsx` | Main Excel-based simulation workbook |
| `README.md` | This project guide |
| `media/` (optional) | Screenshots or demo visuals |

---

## 📡 Data Sources

- 📊 [Basketball Reference – Per Game Stats](https://www.basketball-reference.com/leagues/NBA_2023_per_game.html)
- 🩼 [CBS Sports – NBA Injury Tracker](https://www.cbssports.com/nba/injuries/)

---

## 🧰 Tools Used

- Microsoft Excel (Windows)
- Power Query (HTML web scraping)
- Advanced formulas: `XLOOKUP`, `INDEX`, `IFERROR`, `SMALL`, dynamic named ranges, conditional formatting

---

## 👤 Author

Created by [@RobCameron3](https://github.com/RobCameron3)  
NBA analyst • Excel modeler • Simulation designer
