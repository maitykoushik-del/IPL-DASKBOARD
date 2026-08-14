🏏 IPL Analysis Dashboard | Power BI

📊 Project Overview

This project is an **IPL Analysis Dashboard** created using **Microsoft Power BI** to analyze IPL data from **2008 to 2025**.

The dashboard provides an interactive view of IPL seasons, teams, players, batting and bowling performances, and tournament results. It uses **DAX, Power Query, data modeling, and interactive visualizations** to transform raw IPL data into meaningful insights.

🎯 Project Objectives

The main objectives of this project are:

* Analyze IPL performance season by season
* Identify champions and runner-up teams
* Analyze batting and bowling performances
* Identify Orange Cap and Purple Cap holders
* Compare team performance using a points table
* Track important batting statistics such as 4s, 6s, centuries, and half-centuries
* Create an interactive and user-friendly Power BI dashboard

📌 Dashboard Features

🏆 Tournament Analysis

* Champion team
* Runner-up team
* Season-wise analysis
* Total matches
* Total teams

### 🟠 Orange Cap Analysis

* Orange Cap holder
* Total runs
* Player's team
* Player image
* Season-wise dynamic selection

### 🟣 Purple Cap Analysis

* Purple Cap holder
* Total wickets
* Player's team
* Player image
* Season-wise dynamic selection

### 🏏 Batting Statistics

* Total 4s
* Total 6s
* Centuries
* Half-centuries
* Top 4s player
* Top 6s player

### 📋 Team Points Table

The dashboard includes a team-wise points table containing:

* Team
* Matches Played
* Wins
* Losses
* No Result (NR)
* Ties
* Total Points

🛠️ Tools & Technologies

| Tool                   | Purpose                              |
| ---------------------- | ------------------------------------ |
| **Microsoft Power BI** | Dashboard development                |
| **DAX**                | Measures and calculations            |
| **Power Query**        | Data cleaning and transformation     |
| **Data Modeling**      | Relationships between tables         |
| **Data Visualization** | Charts, KPIs and interactive visuals |

---

📂 Project Structure

```text
IPL-Analysis-PowerBI/
│
├── 📊 IPL Analysis Dashboard.pbix
│
├── 📁 Dataset/
│   └── IPL Dataset files
│
├── 📁 Images/
│   └── Player and team images
│
├── 🖼️ Dashboard.png
│
└── 📄 README.md
```

---

📈 Key KPIs

The dashboard provides important IPL statistics including:

* Total Matches
* Total Teams
* Total 4s
* Total 6s
* Total Centuries
* Total Half-Centuries
* Total Runs
* Total Wickets
* Team Points

🔄 Interactive Features

The dashboard includes a **Season slicer**, allowing users to select a particular IPL season and dynamically update:

* Champion
* Runner-up
* Orange Cap
* Purple Cap
* Top 4s
* Top 6s
* Team standings
* Season statistics

 🧮 DAX

DAX measures were used to calculate dynamic statistics such as:

* Total Runs
* Total Wickets
* Total 4s
* Total 6s
* Centuries
* Half-Centuries
* Orange Cap Holder
* Purple Cap Holder
* Top 4s Player
* Top 6s Player
* Team Points

Example:

```DAX
Total Runs = 
SUM(Batting[Runs])
```

 📷 Dashboard Preview

![IPL Analysis Dashboard]([Dashboard.png](https://github.com/maitykoushik-del/IPL-DASKBOARD/blob/main/IPL%20ANALYSIS%20DASKBOARD.png))

💡 Key Insights

This dashboard makes it easier to understand:

* How IPL team performance changes across seasons
* Which players dominate batting and bowling
* Who won the Orange Cap and Purple Cap in each season
* Team-wise tournament performance
* Major batting achievements across IPL seasons

🚀 Future Improvements

Possible future enhancements include:

* Player performance comparison
* Team performance trends
* Venue-wise analysis
* Head-to-head team analysis
* Bowling economy and strike-rate analysis
* Player career statistics
* Match-level detailed analysis
* Advanced Power BI tooltips
* More interactive charts and drill-through pages

👨‍💻 Author

**Koushik Maity**

🎓 Diploma – Computer Science & Technology
📊 Aspiring Data Analyst | Power BI | Excel | SQL | Python

---

## ⭐ If You Like This Project

If you find this project useful or interesting, please consider giving the repository a **⭐ Star** on GitHub!

**#PowerBI #DAX #DataAnalytics #IPL #DataVisualization #BusinessIntelligence**
