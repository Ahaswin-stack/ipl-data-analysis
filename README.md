IPL Match Analysis (Till 2017) - Databricks
Overview
This project utilizes Apache Spark within  Databricks to analyze Indian Premier League (IPL) matches up until the 2017 season. The analysis focuses on exploring match statistics, aggregating key features, and providing insights into match outcomes without using machine learning models. The goal is to understand how various match-related factors, such as runs scored, extras, and player performance, influence match results.

Key Features:
Data Preprocessing: Cleaning and structuring IPL match data.

Data Aggregation: Aggregating match statistics like total runs, extras, and batting performance.

Exploratory Data Analysis (EDA): Visualizing and summarizing key statistics and patterns in IPL match data.

Match Outcome Analysis: Analyzing the factors that contribute to match outcomes and exploring the relationship between various match statistics.

Requirements
To run this project in Databricks, you'll need the following libraries:

Databricks environment: Use a Databricks workspace or cluster.

Pandas: For data manipulation and aggregation.

Matplotlib & Seaborn: For creating visualizations.
Dataset
The dataset used in this analysis contains IPL match data up until the 2017 season. It includes the following columns:

match_id: Unique identifier for each match.

over_id: Identifier for each over in a match.

ball_id: Identifier for each ball in an over.

innings_no: Inning number (1 or 2).

team_batting: The team currently batting.

team_bowling: The team currently bowling.

striker_batting_position: Position of the striker in the batting order.

extra_type: Type of extra (e.g., wide, no-ball).

runs_scored: Runs scored by the batter.

extra_runs: Runs awarded as extras (wides, no-balls, etc.).

wides, legbyes, byes, noballs, penalty, bowler_extras: Various categories of extras.

out_type: Type of dismissal (bowled, caught, run out, etc.).

match_winner: The team that won the match (target variable).

Data Processing and Analysis in Databricks
1. Data Preprocessing:
The raw match data is cleaned and processed to create features such as total runs scored and extra runs for each team in each match.

2. Exploratory Data Analysis (EDA):
In this step, visualizations and statistical summaries are generated to analyze the trends in match outcomes and various statistics like runs scored, extras, and team performance.
3. Match Outcome Analysis:
This analysis investigates the relationship between key statistics (such as runs scored, extra runs, wides, no-balls) and the outcome of the match.
4. Saving Results in Databricks:
You can save the processed data or visualizations to Databricks File System (DBFS) for future use.

Future Enhancements
Advanced Statistical Analysis: Implement statistical tests like T-tests or ANOVA to understand the significance of features such as extras, team performance, and match outcomes.

More Complex Visualizations: Use advanced visualizations like heatmaps and correlation matrices to uncover deeper insights in the data.

Feature Engineering: Add more features such as player performance, weather conditions, or toss outcomes to further analyze match results.
