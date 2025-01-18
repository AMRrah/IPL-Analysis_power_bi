# IPL-Analysis_power_bi
  **IPL 2008-2024 Analysis Dashboard**  [IPL Player Stats](https://github.com/AMRrah/IPL-Analysis_power_bi/blob/main/IPL%20Analysis%202008-2024.pbix) 
 # Overview 
 This project is a Power BI dashboard analyzing of the Indian Premier League (IPL) 2008-2024 season. It provides actionable insights into team performance, player statistics like total matches, balls faced by the players, total runs and total of player dismissed from the matches and more that will be displayed in the dashboard with the help of advanced data visualization techniques to present clear and meaningful results.
<hr>

 # Dataset
 ## This Project uses IPL(2008-2024) Matches Dataset
   This dataset provides summary-level information about each IPL match.-[Dataset](https://github.com/AMRrah/IPL-Analysis_power_bi/blob/main/matches.csv)
 ### Columns:   
 1. **match_id**       : Unique identifier for each match.
 2. **season**         : Year of the IPL season.
 3. **date**           : The date the match was played.
 4. **team1**          : Name of the first team.
 5. **team2**          : Name of the second team.
 6. **venue**          : The stadium where the match was played.
 7. **toss_winner**    : Team that won the toss.
 8. **toss_decision**  : Decision made by the toss winner (bat or field).
 9. **winner**         : The team that won the match.
10. **result**         : Type of result (e.g., win by runs, wickets, or a tie).
11. **player_of_match**: Best-performing player in the match.
12. **umpires**        : Names of the umpires officiating the match.  

### Use Cases:
 - Analyzing match outcomes, toss decisions, and team performances.
 - Studying trends in IPL seasons over the years.

## This project uses another dataset IPL(2008-2024) Deliveries Dataset
   This dataset provides ball-by-ball details of each IPL match.-[Dataset](https://github.com/AMRrah/IPL-Analysis_power_bi/blob/main/deliveries.csv)

### Columns:
 1. **match_id**        : Identifier linking to the matches dataset.
 2. **inning**          : The inning number (1 or 2).
 3. **batting_team**    : Name of the batting team.
 4. **bowling_team**    : Name of the bowling team.
 5. **over**            : Over number (1 to 20).
 6. **ball**            : Ball number within the over (1 to 6).
 7. **batter**          : Name of the batsman facing the ball.
 8. **non_striker**     : Name of the batsman at the non-striker’s end.
 9. **bowler**          : Name of the bowler delivering the ball.
10. **batsman_runs**    : Runs scored by the batsman off the delivery.
11. **extra_runs**      : Runs due to extras (wide, no-ball, etc.).
12. **total_runs**      : Total runs scored on the ball (batsman + extras).
13. **dismissal_kind**  : Type of dismissal, if any (e.g., bowled, caught).
14. **player_dismissed**: Name of the dismissed player (if any).

### Use Cases:
 - Ball-by-ball performance analysis of players and teams.
 - Studying batsman and bowler stats.
 - Calculating strike rates, economy rates, and player contributions.

## This Project uses one more dataset player_image_team_info
   This dataset provides Player-Role, Player-Style(batting and Bowler),player images.-[Dataset](https://github.com/AMRrah/IPL-Analysis_power_bi/blob/main/player_image_team_info.csv)

### Columns:
1. **player**       : Name of the batsman.
2. **role**         : Role of the player(Wicketkeeper Batter, Bowler, Batting Allrounder, Bowler Allrounder,Allrounder). 
3. **batting_style**: Style of the player(Right Hand,Left Hand)
4. **Image**        : Image of the player
5. **team**         : Name of the team

### Use Cases:
 - Analyse the Role and Style of the Player.
 - Displaying the image of the player
   
<hr>

![Dashboard](https://github.com/AMRrah/IPL-Analysis_power_bi/blob/main/ipl%20power%20bi%20ss.jpg)
<hr>

![Image](https://github.com/user-attachments/assets/6363e2f9-309c-4eee-997e-e00a259ec696)

![Dashboard](https://github.com/user-attachments/assets/53830b24-bad8-4882-aefe-6a1db595377a)



# System Requirements

### Hardware:
   - **Processor**: Intel(R) Pentium(R) CPU  N3700  @ 1.60GHz   1.60 GHz
   - **RAM**: 8.00 GB (7.85 GB usable)
   - **Storage**: 120 GB (118 GB usable)

### Software:
   - **Operating System**:Windows 10 Pro
   - **Tools**:Microsoft Power BI Desktop (latest version).
   - **Additional**: Microsoft Excel for data preparation.

<hr>

# How to Use

1. Install **Power BI Desktop** if not already available.
2. Download the **.pbix file** from this repository.
3. Open the **.pbix file in Power BI Desktop**.
4. Explore the interactive **dashboards** to **analyze player performance**.
5. Download the **.csv file** to make your own **dashboard**.

   <hr>

# Conclusion

This project was created as part of a Data Analysis course to **create Dashboard** using **Power Bi** with the help of **Dataset**.
