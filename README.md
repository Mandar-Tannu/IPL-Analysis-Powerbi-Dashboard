# IPL Analysis Power BI Dashboard

An end-to-end IPL data analysis project (2008–2022) using Power BI. Raw data stored in PostgreSQL; data cleaning, transformation, and modeling done in Power BI. The dashboard reveals insights on team wins, player stats, toss decisions, match outcomes, and season highlights.

![Dashboard Screenshot](screenshots/dashboard-screenshot.png)

---

## 📝 Project Summary

This project involves developing an interactive and visually engaging Power BI dashboard to analyze the Indian Premier League (IPL) cricket data. The dashboard provides comprehensive insights into team performances, player statistics, match outcomes, and historical trends. It empowers cricket analysts, fans, and stakeholders to explore data-driven insights, make informed decisions, and understand the dynamics of the IPL season-by-season.

---

## 📌 Objective 

The goal of this project is to build a dynamic and interactive dashboard using Power BI that provides meaningful insights into team performances, player statistics, match outcomes, and historical trends based on Indian Premier League (IPL) cricket data.

---

## 🛠️ Tools & Technologies

- Power BI Desktop: For designing and building the interactive IPL dashboard.
- DAX (Data Analysis Expressions): For creating custom measures and calculations to analyze player and team statistics.
- Power Query: For data cleaning, transformation, and shaping IPL match and player data.
- PostgreSQL: For storing and managing IPL datasets, enabling efficient querying and data retrieval.
- CSV/Excel Files: As the primary data sources containing match results, player stats, and team details.

---

## 📊 Dashboard Features

- **Overall Tournament KPIs**:  
  - Title Winner (Champion Team)  
  - Orange Cap Holder (Top Run-Scorer)  
  - Purple Cap Holder (Top Wicket-Taker)  
  - Total Sixes Hit in the Tournament  
  - Total Fours Hit in the Tournament  

- **IPL Batting Statistics KPIs**:  
  - Total Runs Scored  
  - Number of Sixes  
  - Number of Fours  
  - Batting Strike Rate  

- **IPL Bowling Statistics KPIs**:  
  - Total Wickets Taken  
  - Bowling Economy Rate  
  - Bowling Average  
  - Bowling Strike Rate  

- **Analytical Charts**:  
  - Matches Won Based on Toss Decision (Batting or Fielding First)  
  - Matches Won by Result Type (Normal Win, Tie, Super Over, etc.)  
  - Matches Won by Venue (Stadium-wise Analysis)  
  - Total Wins by Each Team for a Selected Season  

- **Filters & Slicers for Interactive Analysis**:  
  - Season Selector  
  - Batsman Selector  
  - Bowler Selector  

---

## 🗂️ Project Structure

```plaintext
IPL-Analysis-Powerbi-Dashboard/
│
├── dataset/
│   ├── ipl_matches_2008_2022.csv
│   └── ipl_ball_by_ball_2008_2022.csv
│
├── database/
│   └── Queries to Create Tables in PostgreSQL
│
├── dashboard/
│   └── IPL Analysis Dashboard.pbix
│
├── assets/
│   └── IPL Images/
│       └── (team logos, icons, etc.)
│
├── screenshots/
│   └── dashboard-screenshot.png
│
└── README.md
```
