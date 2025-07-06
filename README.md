🏏 T20 World Cup Player Analysis – Power BI End-to-End Project
📌 Problem Statement
The goal of this project is to identify the top 11 players for a T20 cricket team by analyzing real-world performance data. This project scrapes player statistics from ESPNcricinfo using Bright Data, cleans and transforms the data using Python (Pandas), and visualizes key performance metrics in an interactive Power BI dashboard to aid in strategic team selection.

🎯 Project Objective
Scrape T20 player performance data from ESPNcricinfo using Brightdata.

Clean and preprocess the data using Pandas in Python.

Create calculated metrics and transformations for better evaluation.

Use Power BI to build a comprehensive report showing batting, bowling, and all-round performance.

Categorize players based on their strengths and select an optimal Playing XI for the team.

🔧 Tools & Technologies Used
Tool	Purpose
Brightdata	Web scraping tool to extract live stats
Python (Pandas)	Data cleaning, transformation, and feature engineering
Power BI	Interactive visual analytics and dashboard
Excel (optional)	Supporting exploration and transformation

🧹 Data Workflow
Data Scraping – Extracted structured data from ESPNcricinfo for T20 batting, bowling, and all-round stats.

Data Cleaning – Used Pandas to remove nulls, standardize formats, and create derived columns.

Feature Engineering – Created new metrics such as:

Batting average and strike rate

Bowling economy and average

All-rounder impact score

Data Visualization – Built a Power BI dashboard with filters and charts to:

Compare players across performance metrics

Identify role-based players (e.g., finishers, bowlers)

Shortlist top 11 based on strategic needs

🏏 Player Selection Strategy
The dashboard helps shortlist players in the following categories:

Openers

Middle-order Anchors

Finishers

All-rounders

Specialist Fast Bowlers

Spinners (if applicable)

The final Top 11 team is selected based on a balanced mix of batting depth, bowling variety, and match impact.

📊 Power BI Dashboard Overview
Filters by format, match count, performance metrics

Comparative bar charts for batting/bowling stats

Role-wise player list with scorecards

Final Selected XI View

📎 Project Structure
plaintext
Copy code
📦T20-Cricket-Team-Selection
 ┣ 📂Data
 ┃ ┗ 📄t20_player_stats.csv
 ┣ 📂Scripts
 ┃ ┗ 📄data_cleaning_and_transformation.py
 ┣ 📂Dashboard
 ┃ ┗ 📄T20_Team_Selection_Report.pbix
 ┣ 📄README.md
 ┣ 📄requirements.txt
📌 Key Takeaways
Real-time data scraping and transformation for sports analytics

KPI-driven player selection using data visualization

End-to-end project workflow suitable for portfolio presentation or interview discussion

