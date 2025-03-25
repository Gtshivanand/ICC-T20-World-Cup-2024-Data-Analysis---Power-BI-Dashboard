# 🏏 ICC T20 World Cup 2024 Data Analysis - Power BI Dashboard 🏏

<img src="https://github.com/Gtshivanand/ICC-T20-World-Cup-2024-Data-Analysis-Power-BI-Dashboard/blob/main/Images/icc-men-s-t20-world-cup-logo-2024-free-vector.jpg"/>

<img  src="https://github.com/Gtshivanand/ICC-T20-World-Cup-2024-Data-Analysis-Power-BI-Dashboard/blob/main/Images/ICC%20T20%20World%20Cup%202024.jpg"/>


## 📌 Introduction:
This project analyzes key statistics and performance trends from the ICC Men's T20 World Cup 2024. Using an interactive Power BI Dashboard, it provides valuable insights into team performance, player statistics, match outcomes, and various other aspects to uncover winning strategies.

## 🎯 Project Overview:
The ICC T20 World Cup 2024 saw thrilling encounters, outstanding performances, and crucial turning points. This analysis dives into multiple dimensions to identify trends, strengths, and opportunities across matches, players, and teams.

## 💡 Problem Statement:
Understanding the performance of teams and players in a fast-paced T20 format is essential for identifying winning strategies and enhancing future performance. This project explores the World Cup dataset to uncover hidden insights through interactive visualizations.

## 📊 Dataset Information:

* Source: Official ICC Men's T20 World Cup 2024 Statistics

* Attributes Include:

  * Match Details: Date, Venue, Teams, Winner, Toss, etc.
  
  * Player Stats: Runs, Wickets, Strike Rate, Economy, etc.
  
  * Team Performance: Boundaries, Dot Balls, Bowling Figures

## 📚 Data Definition:

* Match_Date – Date of the match

* Team1 – Name of the first team

* Team2 – Name of the second team

* Winner – Team that won the match

* Player_of_Match – Best performer of the match

* Runs_Scored – Total runs scored by the team

* Wickets_Taken – Total wickets taken by the team

* Overs_Bowled – Number of overs bowled by the team

## ⚙️ Data Model Overview:

<img src="https://github.com/Gtshivanand/ICC-T20-World-Cup-2024-Data-Analysis-Power-BI-Dashboard/blob/main/Images/Data%20Model.png"/>

📂 Data Model Structure

1. t20worldcup_2024_matches

 * Ground, Margin, Match Date, Stage, Team 1, Team 2, Winner
 
 * Primary Key: matchId

2. t20worldcup_2024_batting

 * t20worldcup_2024_bowling
 
 * balls, bowlerName, ECONOMY, FOURS, MAIDENS, NO BALL, OVERS

 * Primary Key: matchId

3. t20worldcup_2024_players

 * Batting Style, Bowling Style, Name, Role, Team
 
 * Primary Key: Name

4. key_Measures
 
* Avg. balls faced

5. Table & Table (2)

 * Placeholder tables for future data integration

## 🔗 Relationships Between Tables:

* t20worldcup_2024_matches.matchId ➡️ t20worldcup_2024_batting.MATCH_ID

* t20worldcup_2024_matches.matchId ➡️ t20worldcup_2024_bowling.matchId

* t20worldcup_2024_players.Name ➡️ t20worldcup_2024_batting.match



## ⚙️ Project Workflow:

1. Data Collection & Cleaning:

  * Imported dataset with match and player-level statistics
  
  * Cleaned data to ensure consistency and accuracy

2. Data Analysis & Transformation:

  * Aggregated key metrics for team and player performance
  
  * Transformed data for Power BI compatibility

3. Dashboard Development:

  * Created visualizations for team and individual performances
  
  * Developed interactive reports using slicers and filters

4. Insights & Recommendations:

  * Extracted actionable insights to improve game strategies

## 📸 Snapshots:

<img src="https://github.com/Gtshivanand/ICC-T20-World-Cup-2024-Data-Analysis-Power-BI-Dashboard/blob/main/Images/Bating%20Summary.png"/>

<img src="https://github.com/Gtshivanand/ICC-T20-World-Cup-2024-Data-Analysis-Power-BI-Dashboard/blob/main/Images/Bowling%20Summary.png"/>

<img src="https://github.com/Gtshivanand/ICC-T20-World-Cup-2024-Data-Analysis-Power-BI-Dashboard/blob/main/Images/Team%20Performance%20Summary.png"/>

## 🔍 Key Insights & Recommendations:

### 📊 Batting Insights:
 
 * Top Scorers: Rahmanullah Gurbaz, Rohit Sharma, and Andries Gous dominated the tournament with consistent performances.
 
 * Batting Impact: High strike rates in the powerplay overs gave teams a strong start.
 
 * Fours & Sixes: Teams scoring high boundary percentages in the death overs had better win rates.

### 🎯 Bowling Insights:

 * Top Wicket-Takers: Arshdeep Singh, Fazalhaq Farooqi, and Anrich Nortje led the wicket tally.
 
 * Bowling Economy: Rachin Ravindra and Tim Southee maintained exceptional economy rates under pressure.
 
 * Dot Ball Percentage: High dot ball percentages correlated with reduced opposition run rates.

### 🏏 Team Performance:

 * Most Wickets: Teams with effective bowling partnerships in the middle overs tended to win crucial matches.
 
 * Powerplay Dominance: Teams maintaining high strike rates in the first six overs created match-winning momentum.
 
 * Strike Rate Leaders: Australia, Canada, and England outperformed other teams in maintaining aggressive strike rates.


## 📈 Results:

* Comprehensive analysis of team, player, and match performance.

* Key trends identified in batting, bowling, and match outcomes.

* Insights to guide teams in optimizing strategies and improving decision-making.

## 🚀 Future Enhancements:

* Predictive Models: Implement machine learning models to forecast match outcomes.

* Real-Time Data Integration: Add live data streaming for real-time analysis and insights.

* Enhanced Player Analysis: Track player consistency across multiple tournaments.

## 📝 Conclusion:

The Power BI dashboard provides a dynamic and insightful view of the ICC T20 World Cup 2024, highlighting performance trends and enabling data-driven decision-making. The insights derived empower teams, analysts, and cricket enthusiasts to refine their strategies and enhance future performances.

## 📧  Feedback and Suggestions:

Thank you for visiting my repository! If you have any questions or feedback, feel free to reach out.

I’d love to hear your thoughts, feedback, and suggestions! Feel free to connect with me:

 LinkedIn: [Shivanand Nashi](https://www.linkedin.com/in/shivanand-s-nashi-79579821a)
 
 Email: shivanandnashi97@gmail.com


Looking forward to connecting and exchanging ideas!

## ✨ Support this project!
If you found this project helpful or interesting, please consider giving it a ⭐ on GitHub!
Your support helps keep the project active and encourages further development.

Thank you for your support! 💖
