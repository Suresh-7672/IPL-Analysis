# IPL-Analysis
🏏 IPL Analysis Dashboard | Power BI

An interactive IPL Analysis Dashboard built using Microsoft Power
BI to analyze Indian Premier League data from 2008 to 2025.

The dashboard transforms raw IPL match and ball-by-ball data into
interactive insights about team performance, player performance,
batting, bowling, champions, and season-wise statistics.

📊 Dashboard Preview

Add your Power BI dashboard screenshot here.

![IPL Analysis Dashboard](images/ipl-dashboard.png)

🎯 Project Objective

The objective of this project is to analyze IPL data across multiple
seasons and build an interactive dashboard that helps users quickly
understand:

Season-wise IPL performance

Team performance and points

Top run scorers

Top wicket takers

Batting statistics

Bowling statistics

Match and tournament-level KPIs

Champion and runner-up trends

📌 Key Dashboard Features

🏆 Season Analysis

Season-wise champion

Runner-up

Number of teams

Number of matches

Interactive season filtering from 2008--2025

🟠 Orange Cap Analysis

Identify the leading run scorer for the selected season

Analyze player batting performance

🟣 Purple Cap Analysis

Identify the leading wicket taker for the selected season

Exclude wickets that should not be credited to the bowler, such as:

Run out

Retired hurt

Obstructing the field

Retired out

🏏 Batting Analysis

Total runs

Sixes

Fours

Centuries

Half-centuries

📋 Team Performance

Team-wise points table

Wins and losses

Season-wise team performance

🛠️ Tools & Technologies

Tool / Technology                   Usage

Power BI                        Dashboard development and
visualization

DAX                             Measures and calculated metrics

Power Query                     Data cleaning and transformation

Data Modeling                   Relationships between IPL datasets

🗂️ Data Sources

The project uses IPL datasets containing information related to:

IPL matches

Seasons

Teams

Players

Ball-by-ball deliveries

Runs

Wickets

Match results

Main Tables

ipl_matches_data

ball_by_ball_data

The match-level table contains season and match information, while the
ball-by-ball table contains delivery-level information such as runs,
wickets, batsmen, and bowlers.

🔄 Data Workflow

Raw IPL Data
     ↓
Data Cleaning & Transformation
     ↓
Power BI Data Model
     ↓
DAX Measures
     ↓
Interactive Visualizations
     ↓
IPL Analysis Dashboard

🧮 DAX & Data Modeling

DAX was used to create dynamic calculations for metrics such as:

Total matches

Total runs

Total fours

Total sixes

Centuries

Half-centuries

Season-wise wickets

Orange Cap

Purple Cap

Team points

The dashboard uses relationships between the match-level and
ball-by-ball datasets to dynamically calculate metrics based on the
selected season.

💡 Key Insights

The dashboard can be used to answer questions such as:

Who was the Orange Cap holder in a selected IPL season?

Who was the Purple Cap holder?

Which team won a particular season?

Which team finished as runner-up?

How many matches were played in each season?

How many teams participated in a season?

Which players scored the most runs?

Which bowlers took the most wickets?

How many sixes and fours were scored?

How did team performance change across seasons?

🎨 Dashboard Design

The dashboard was designed with a focus on:

Clean and simple layout

Interactive season slicer

KPI cards

Player-focused insights

Team performance tables

Easy navigation

Data storytelling

🚀 Skills Demonstrated

This project demonstrates practical experience in:

Data Analysis

Power BI

DAX

Power Query

Data Cleaning

Data Modeling

KPI Development

Interactive Dashboard Design

Data Visualization

Business/Data Storytelling

📁 Suggested Repository Structure

IPL-Analysis-PowerBI/
│
├── README.md
│
├── Dashboard/
│   └── IPL_Analysis_Dashboard.pbix
│
├── Dataset/
│   ├── ipl_matches_data.csv
│   └── ball_by_ball_data.csv
│
├── Screenshots/
│   └── ipl-dashboard.png
│
└── Documentation/
    └── Project_Documentation.pdf

📷 Dashboard Screenshot

Replace the image path below with your actual screenshot:

![IPL Analysis Dashboard](Screenshots/ipl-dashboard.png)

📈 Future Enhancements

Possible future improvements include:

Player comparison page

Team head-to-head analysis

Venue-wise performance

Toss impact analysis

Batting strike-rate analysis

Bowling economy analysis

Win prediction analysis

Player performance trends

Advanced season-over-season analysis

👨‍💻 Author

Suresh Thalluri

Aspiring Data Analyst | Power BI | SQL | Python | Excel

Connect with me

LinkedIn: https://www.linkedin.com/in/suresh-thalluri

⭐ If you find this project useful

If you like this project, consider giving the repository a ⭐ and
sharing your feedback!
