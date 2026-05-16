# 🏏 IPL Data Analysis (2008–2023)

A complete IPL Cricket Analytics project using Python, Pandas, Matplotlib, Seaborn, and ReportLab. This project performs detailed ball-by-ball analysis of IPL matches from 2008 to 2023 to uncover insights related to batting, bowling, match strategies, venues, toss impact, team performances, and player statistics.

---

  Download Dataset : 

# 📌 Project Overview

The Indian Premier League (IPL) is one of the biggest T20 cricket tournaments in the world. This project analyzes delivery-level IPL data to identify hidden patterns, match-winning strategies, and player performances using data science techniques and visual analytics.

The analysis covers:

- Team performance trends
- Match-winning strategies
- Batting dominance
- Bowling effectiveness
- Toss impact on matches
- Venue analysis
- Chasing vs defending performance
- Powerplay and death-over analysis

The project includes:
- Jupyter Notebook analysis
- Professional PDF report
- Visualizations and charts
- Advanced cricket insights

---

# 📊 Dataset Information

## 📁 Dataset Used
- **Dataset Name:** `CRICKET_DATASET.csv`
- **Dataset Type:** Ball-by-Ball IPL Dataset
- **Format:** CSV

---

## 📌 Dataset Highlights

| Attribute | Details |
|---|---|
| Seasons Covered | 2008 – 2023 |
| Total Seasons | 16 |
| Matches Covered | 950+ |
| Teams Included | 74+ |
| Players Included | 250+ |
| Data Granularity | Ball-by-ball delivery-level |

---

## 🧾 Important Dataset Columns

| Column Name | Description |
|---|---|
| `match_id` | Unique match identifier |
| `season` | IPL season |
| `date` | Match date |
| `venue` | Stadium name |
| `batting_team` | Batting team |
| `bowling_team` | Bowling team |
| `batter` | Batter name |
| `bowler` | Bowler name |
| `batsman_runs` | Runs scored by batter |
| `extra_runs` | Extra runs |
| `total_runs` | Total runs scored |
| `is_wicket` | Wicket indicator |
| `wicket_kind` | Type of dismissal |
| `player_out` | Dismissed batter |
| `fielder` | Fielder involved |
| `over` | Over number |
| `ball` | Ball number |
| `toss_winner` | Toss-winning team |
| `toss_decision` | Batting/Fielding decision |
| `winner` | Match-winning team |

---

# 🧹 Data Preprocessing

The dataset was cleaned and transformed before analysis.

### ✔️ Preprocessing Steps
- Removed missing values
- Converted date columns into datetime format
- Handled duplicate records
- Filtered wicket deliveries
- Aggregated batting and bowling statistics
- Created match phases:
  - Powerplay (Overs 1–6)
  - Middle Overs (Overs 7–15)
  - Death Overs (Overs 16–20)

---

# 🚀 Features & Analysis Included

## 📈 Match Analysis
- Toss Impact Analysis
- Match Phase Analysis
- Chasing vs Defending Analysis
- Wicket Type Distribution
- Match-winning trends

---

## 🏏 Batting Analysis
- Orange Cap Winners (Season-wise)
- All-Time Top Batters
- Most Sixes in IPL History
- Most Fours in IPL History
- Strike Rate Analysis

---

## 🎯 Bowling Analysis
- Purple Cap Winners (Season-wise)
- All-Time Top Bowlers
- Economy Rate Analysis
- Bowling Phase Performance

---

## 🏟️ Team & Venue Analysis
- Most Successful IPL Teams
- Team Win Records
- Top IPL Venues
- Lucky & Unlucky Venues
- Home Ground Advantage

---

## 📊 Advanced Insights
- Toss Decision Trends
- Phase-wise Strike Rates
- Bowling Economy Trends
- Tactical T20 Cricket Insights
- Match-winning patterns

---

# 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Core Programming |
| Pandas | Data Manipulation |
| NumPy | Numerical Computing |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Charts |
| ReportLab | PDF Report Generation |
| Jupyter Notebook | Development Environment |

---

# 📂 Project Structure

```bash
IPL-Data-Analysis/
│
├── IPL_ANALYSIS_CODE.ipynb
├── ANALYSIS_REPORT.pdf
├── CRICKET_DATASET.csv
├── README.md
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/IPL-Data-Analysis.git
cd IPL-Data-Analysis
```

---

## Install Dependencies

```bash
pip install numpy pandas matplotlib seaborn reportlab
```

---

# ▶️ Usage

## Run Jupyter Notebook

```bash
jupyter notebook IPL_ANALYSIS_CODE.ipynb
```

---

## Load Dataset

```python
import pandas as pd

df = pd.read_csv("CRICKET_DATASET.csv", low_memory=False)

df['date'] = pd.to_datetime(df['date'])

print(df.head())
```

---

# 📊 Key Insights from Analysis

## 🏆 Team Insights
- Mumbai Indians recorded the highest IPL wins.
- Chennai Super Kings consistently dominated home venues.
- Teams with strong death-over batting won more close matches.

---

## 🔥 Batting Insights
- Virat Kohli became the highest IPL run scorer.
- Chris Gayle hit the most sixes in IPL history.
- Kohli’s 973-run season remains the highest single-season IPL tally.

---

## 🎯 Bowling Insights
- Yuzvendra Chahal emerged as the highest wicket-taker.
- Bowlers like Dwayne Bravo and Lasith Malinga dominated death overs.

---

## 📌 Match Strategy Insights
- Chasing teams won approximately 55.6% of matches.
- Toss impact exists but is not highly decisive.
- Death overs produced the highest scoring rates.

---

# 📈 Visualizations Included

The project contains multiple professional charts and visualizations:

- Bar Charts
- Pie Charts
- Team Comparison Graphs
- Venue Analysis Charts
- Match Phase Visualizations
- Player Ranking Charts

Generated using:
- Matplotlib
- Seaborn

---

# 📄 Project Report

A complete professional report is included in:

```bash
ANALYSIS_REPORT.pdf
```

The report contains:
- Executive Summary
- Team Analysis
- Batting & Bowling Statistics
- Match Insights
- Visual Analytics
- Final Conclusions

---

# 🎯 Future Improvements

Possible future enhancements:
- IPL Match Prediction Models
- Win Probability Systems
- Machine Learning-based Analysis
- Streamlit Dashboard
- Real-time IPL Analytics
- Power BI Integration

---

# 👨‍💻 Author

## Pranav Mishra

- Data Science & Machine Learning
- Full Stack Developer
- AI & Data Science Enthusiast
- Sports Analytics Researcher

---

# 📌 Conclusion

This project demonstrates how data science and visualization techniques can be applied to sports analytics using real-world IPL cricket data. By leveraging delivery-level datasets and Python libraries, the analysis uncovers strategic insights into batting, bowling, match outcomes, and team performances.

Ball-by-ball IPL datasets provide excellent opportunities for advanced analytics, machine learning, and predictive modeling in modern cricket analytics.
