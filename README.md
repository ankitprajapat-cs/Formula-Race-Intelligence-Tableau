# Formula 1 Race Intelligence Dashboard & Analytics

Explore F1 history with this interactive Tableau dashboard. Analyzing 13.7k+ records across 17 seasons, it features dynamic visualizations like a Top N Driver Leaderboard, Team Championship trends, and vehicle reliability analytics. Built with relational data modeling, calculated fields, and global filters for deep motorsport insights.

## 📊 Project Overview & Visualizations
1. **Driver Leaderboard:** Analysis of all-time leading drivers based on average and cumulative championship points.
2. **Team Points Trajectory:** Multi-season performance trend analysis comparing top constructors (Red Bull, Mercedes, Ferrari, McLaren).
3. **DNF & Reliability Analysis:** Breakdown of Did-Not-Finish (DNF) occurrences across engine failures, mechanical issues, and collision damages.
4. **Global Circuits Map:** Geospatial visualization of Formula 1 circuits across the globe with race count volume indicators.
5. **Interactive Dashboard & Story:** Multi-scene story board synthesizing constructor battles, driver dominance, and track intelligence.

---

## 🛠️ Tech Stack & Tools
- **BI & Visualization Tool:** Tableau Public / Tableau Desktop
- **Data Source:** Microsoft Excel (Multi-table relational schema: Race Results, Circuits, Championship Standings, Lap Intelligence, Qualifying Results)
- **Data Modeling:** Noodle-based relationships on composite keys (`Race Id`, `Circuit Id`, `Season`, `Driver`)
