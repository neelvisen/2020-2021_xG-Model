The goal of this project is to build a predictive model for simulating the remainder of the 2020-2021 Premier League season as of the end of game week 12. The following report uses an expected goals (xG) model to create relative team ratings based on xG and xGA. This data is applied to determine a lambda for a Poisson process that is used in a Monte Carlo simulation of the remaining two-thirds of the season.

Besides the two report files, this report contains 4 csv files that are used to help run the code in the Rmd file.

understat_all_teams.csv refers to the primary dataset used in the Rmd file, containing all relevant xG data from the first 12 gameweeks of the season. This file was adoped from 
Vaastav Anand's repository linked at: https://github.com/vaastav/Fantasy-Premier-League/tree/master/data/2020-21

current league standings.csv contains the league standings at the end of gameweek 12.

remaining fixtures.csv contains the unplayed fixtures of the 2020-2021 season as of gameweek 12.

remaining fixtures tabulated.csv contains the predicted home and away goals of my model for every remaining fixture in the 2020-2021 season. 

Any questions regarding this repo and its contents can be sent to neel.visen@mail.utoronto.ca
