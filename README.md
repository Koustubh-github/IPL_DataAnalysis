# 🏏 IPL_DataAnalysis

## 📌 Overview
**IPL_DataAnalysis** is a comprehensive data analysis and visualization project based on Indian Premier League (IPL) datasets. It explores match-level and ball-by-ball data to uncover insights into team performance, player statistics, match dynamics, and venue influence.

The project also includes an interactive **Power BI Dashboard** (shown in the final slide of the presentation) for intuitive and dynamic data exploration.

---

## 🎯 Problem Statement
The goal of this project is to analyze historical IPL data to:
- Understand patterns in match outcomes and strategies  
- Evaluate player and team performances  
- Identify key factors like toss, venue, and innings impact  
- Present findings through visualizations and dashboards  

---

## 📂 Dataset Description

### 🔹 Matches Dataset
- Match ID, City, Date, Season  
- Teams, Venue, Toss details  
- Winner, Winning Margin  
- Player of the Match  
- Umpires  

### 🔹 Deliveries Dataset
- Innings, Over, Ball  
- Batsman, Bowler, Non-striker  
- Runs, Extras, Wickets  
- Dismissal types and fielders  

---

## ⚙️ Data Preprocessing
- Handled missing values and inconsistencies  
- Standardized team and venue names  
- Removed "No Result" matches  
- Cleaned and formatted date fields  

### 🔧 Feature Engineering
- `WonByRuns`  
- `WonByWickets`  

---

## 📊 Exploratory Data Analysis

### 🔹 Match & Season Insights
- Matches per season  
- Most successful teams  
- Venue-wise match distribution  

### 🔹 Toss Analysis
- Toss decision trends  
- Toss impact on winning  

### 🔹 Batting Analysis
- Top run scorers and strike rates  
- Boundary analysis (4s and 6s)  
- Runs distribution across overs (Powerplay, Middle, Death)  

### 🔹 Bowling Analysis
- Top wicket takers  
- Economy rates  
- Types of dismissals  

### 🔹 Match Dynamics
- First vs second innings comparison  
- Winning margins  
- Super Over analysis  
- High-scoring team combinations  

---

## 📌 Key Questions Answered
- Which venue hosted the most IPL matches?  
- Which team has the highest wins?  
- How are runs distributed across overs?  
- What is the effect of toss on match results?  
- Who are the top batsmen and bowlers?  
- Which teams dominate specific venues?  
- What are average runs scored per over?  
- Who has the most Player of the Match awards?  

(20+ analytical queries explored :contentReference[oaicite:0]{index=0})

---

## 📈 Visualizations
- Bar charts for player and team comparisons  
- Line plots for seasonal trends  
- Pie charts for win distribution  
- Heatmaps for team vs venue performance  

---

## 📊 Power BI Dashboard
- Multiple dashboards for different perspectives  
- Filters for team, venue, and season  
- Over-wise run distribution  
- Venue-based filtering for deeper insights  

---

## 🛠️ Tech Stack
- **Python** (Pandas, NumPy)  
- **Matplotlib & Seaborn**  
- **Jupyter Notebook**  
- **Power BI**  

---

## 🚀 How to Run

```bash
git clone https://github.com/Koustubh-github/IPL_DataAnalysis.git
cd IPL_DataAnalysis
pip install pandas numpy matplotlib seaborn
jupyter notebook
