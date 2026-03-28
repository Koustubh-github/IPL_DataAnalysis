# 🏏 IPL Data Analysis & Visualization Project

## 📌 Overview
This project performs a comprehensive analysis of Indian Premier League (IPL) data using match-level and ball-by-ball datasets. It focuses on extracting meaningful insights about team strategies, player performance, match trends, and venue influence through data analysis and visualization.

The project also includes an interactive **Power BI Dashboard** (shown in the final slide of the PPT) for dynamic exploration of insights.

---

## 🎯 Problem Statement
The objective is to analyze historical IPL data to:
- Understand match dynamics and outcomes  
- Identify patterns in team strategies and player performance  
- Use visualization techniques to present insights effectively  
- Support applications like fantasy cricket, strategy planning, and sports analytics  

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
- Dismissal type, fielders involved  

---

## ⚙️ Data Preprocessing
- Handled missing values and inconsistencies  
- Standardized team names and venues  
- Removed “No Result” matches  
- Fixed date formats  

### 🔧 Feature Engineering
- `WonByRuns`  
- `WonByWickets`  

---

## 📊 Exploratory Data Analysis (EDA)

### 🔹 Match & Season Analysis
- Matches played per season  
- Venue-wise match distribution  
- Most successful teams  

### 🔹 Toss Analysis
- Toss decision trends  
- Toss impact on match outcome  

### 🔹 Batting Insights
- Top run scorers  
- Strike rate analysis  
- Boundary distribution (4s & 6s)  
- Runs across Powerplay, Middle, Death overs  

### 🔹 Bowling Insights
- Top wicket takers  
- Economy rates  
- Dismissal type distribution  

### 🔹 Match Dynamics
- First vs Second innings comparison  
- Winning margins  
- Super Over occurrences  
- Highest scoring team combinations  

---

## 📌 Key Questions Answered
- Which venue hosted the most matches?  
- Which team has the most wins?  
- How are runs distributed across overs?  
- What is the impact of toss on results?  
- Who are the top batsmen and bowlers?  
- Which teams dominate specific venues?  
- What are average runs scored per over?  
- Which players have most Player of the Match awards?  

(20+ analytical queries explored in total :contentReference[oaicite:0]{index=0})

---

## 📈 Visualizations
- Bar charts (top players, teams)  
- Line graphs (season trends)  
- Pie charts (win distribution)  
- Heatmaps (team vs venue performance)  

---

## 📊 Power BI Dashboard
An interactive dashboard was built to enhance visualization and usability:
- Multiple dashboards for different insights  
- Filters for teams, venues, and seasons  
- Over-wise run distribution analysis  
- Venue-based filtering for deeper insights  

---

## 🛠️ Tech Stack
- **Python** (Pandas, NumPy)  
- **Matplotlib & Seaborn** (Visualization)  
- **Jupyter Notebook**  
- **Power BI** (Dashboarding)  

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ipl-analysis.git
   cd ipl-analysis
