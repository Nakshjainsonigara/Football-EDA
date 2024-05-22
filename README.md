
# Data-Driven Goals: A Comprehensive EDA of Football

This project is focused on in-depth exploratory data analysis of football data, aiming to uncover the intricate patterns and dynamics that define the sport.

View the [Kaggle Notebook](https://www.kaggle.com/code/nakshjain11/football-eda) or [Interactive EDA Notebook](https://nbviewer.org/github/Nakshjainsonigara/Football-EDA/blob/85c6528f326f40c531222a88a703a430f7a8f2fa/EDA.ipynb#)  for interactive visualizations.

## Contributors

- [Naksh Jain Sonigara](https://www.linkedin.com/in/naksh-jain-sonigara-16a970215/)
- [Soumya Chauhan](https://www.linkedin.com/in/soumyachauhandotcom/)


 
 ## Project Overview

In this project, we embarked on an in-depth exploratory data analysis to explore the intricate and diverse world of football. Our extensive dataset, comprising player appearances, club games, clubs, competitions, game events, games, player valuations, and player profiles, provided a robust foundation for our study. By analyzing this rich collection of data, we sought to uncover the key patterns and dynamics that shape the sport. This exploration allowed us to investigate multiple facets of football, including individual player performances, disciplinary records, club success rates, and the competitive structures of various leagues.

Our analysis began with data preprocessing, where we meticulously cleaned and integrated information from multiple sources. This involved complex merging operations across eight distinct datasets, a challenging task due to the varying formats and structures of the data. We utilized a range of Python libraries, including pandas for data manipulation, NumPy for numerical operations, and Scipy for statistical analysis. Visualization tools like Matplotlib and Plotly were employed to create compelling and interactive charts, enabling us to present our findings in a clear and insightful manner.

Throughout the project, we encountered and addressed several challenges, such as handling missing values, ensuring data consistency, and performing advanced statistical tests to validate our hypotheses. By overcoming these obstacles, we were able to provide a detailed analysis of factors influencing club performance, player contributions, and the impact of various game events. Our findings offer valuable insights that can inform decision-making for clubs, enhance fan engagement, and guide further research in football analytics. 

## Data Description

The data has been sourced from [Kaggle](https://www.kaggle.com/datasets/thedevastator/football-data-competitions-clubs-players-statist)

1. **Appearances**: appearance_id, game_id, player_id, player_club_id, player_current_club_id, date, player_name, competition_id, yellow_cards, red_cards, goals, assists, minutes_played. 

2. **Clubs**: club_id, club_code, name, domestic_competition_id, total_market_value, squad_size, average_age, foreigners_number, foreigners_percentage, national_team_players, stadium_name, stadium_seats, net_transfer_record, coach_name, last_season, url 

3. **Club_games**: game_id, club_id, own_goals, own_position, own_manager_name, opponent_id, opponent_goals, opponent_position, opponent_manager_name, hosting, is_win  

4. **Competitions**: competition_id, competition_code, name, sub_type, type, country_id, country_name, domestic_league_code, confederation, url  

5. **Games**: game_id, competition_id, season, round, date, home_club_id, away_club_id, home_club_goals, away_club_goals, home_club_position, away_club_position, home_club_manager_name, away_club_manager_name, stadium, attendance, referee, url, home_club_name, away_club_name, aggregate, competition_type 

6. **Game_events**: game_id, minute, type, club_id, player_id, description, player_in_id  

7. **Players**: player_id, first_name, last_name, name, last_season, current_club_id, player_code, country_of_birth, city_of_birth, country_of_citizenship, date_of_birth, sub_position, position, foot, height_in_cm, market_value_in_eur, highest_market_value_in_eur, contract_expiration_date, agent_name, image_url, url, current_club_domestic_competition_id, current_club_name  

8. **Player_valuations**: player_id, last_season, datetime, date, dateweek, market_value_in_eur, n, current_club_id, player_club_domestic_competition_id


## Exploratory Data Analysis
1. Player Club Appearances Overview
2. Player Height Distribution Analysis for Centre-Forwards
3. Analyzing Player Mobility and Transfer Frequencies
4. Player Market Value Trends Over Time
5. Club Yellow and Red Card Analysis
6. Player Nationality Analysis
7. Home vs Away Performance Analysis
8. Club Performace Report
9. Age Group Dynamics and Performance in Football Clubs
10. Exploring the Relationship Between Squad Size and Win Rates
11. Top 5 players of individual club
12. Top performing clubs of each competitions
13. Top Scorer Analysis

## Technical Requirements
 Libraries required are `numpy` ,`pandas` ,`seaborn` ,`matplotlib` ,`plotly` ,`dash` ,`ipywidgets` ,`scipy` and `scikit-learn`.

## Acknowledgments
 * We extend our gratitude to [dcereijo](https://data.world/dcereijo) for providing the dataset used in this analysis.
 * We appreciate the contributions of the open-source community and the various libraries utilized in this project.

## Contact 
For constructive feedback, inquiries, or collaboration opportunities, please contact [jainnaksh576@gmail.com](jainnaksh576@gmail.com) or [soumyachauhan05@gmail.com](soumyachauhan05@gmail.com) .

