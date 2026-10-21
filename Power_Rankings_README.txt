EPL Power Rankings

Project Overview

This project develops a Premier League Power Ranking system using historical match performance data from the previous 2 seasons

The objective is to produce an objective ranking of Premier League clubs based on:

-Goal Scoring Performance
-Defensive Performance
-Shot Creation
-Shot Prevention

Data Source

Data provided by 
-football-data.co.uk

Historical Seasons Used:

-2024/2025
-2025/2026

Methodology

Attack Rating

Measures goals scored per match relative to league average

Defense Rating

Measures goals conceded per match relative to league average

Shot Creation Rating

Measures shots generated per match relative to league average

Shot Prevention Rating

Measures shots prevented per match relative to league average

Power Rating

Power Rating combines:

-Offensive Strength
-Defensive Strength

Offensive Strength =

-Attack Rating
-Shot Creation Rating

Defensive Strength = 

-Defense Rating
-Shot Prevention Rating

Final Power Rating = 

-Offensive Strength
-Defensive Strength

Project Output

Example

Rank	Team	Power Rating
1	Arsenal		5.847
2	Man City	5.517
3	Liverpool	5.161

Repository Structure

EPL_Power_Rankings
|
|---data
|---notebooks
|---outputs
|---docs
|---README.md

Future Enhancements

Planned Improvements:

-Current Season xG Integration
-Recent Form Ratings
-Home Advantage Metrics
-Season Simulations
-Betting Market Analysis

Technologies Used:

-Python
-Pandas
-NumPy
-Jupyter Notebook

Sample Output:

power_rankings_v1.png


Author 

Sam Harvey