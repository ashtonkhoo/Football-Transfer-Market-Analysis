# Football Transfer Market Analysis
Analysis of the Transfer Market in Association Football from 2000 to 2018

## Link to Tableau workbook
https://public.tableau.com/profile/chun.wen.khoo#!/vizhome/Assignment1_15685397256820/FinalDashboard

## About
In association football, relevant time periods can be categorised into the season itself, and the transfer market. Teams can delve into the transfer market to buy and sell players for an agreed fee. By analysing the trends, and the frequency of transfers between teams of different leagues, one can visualize and analyse the fluctuations and inflations of the transfer market.

The transfer market can be described as an arena, where football athletes are available for transfer to other clubs. Teams from all over the world can scout and determine players that would best fit their needs. As an example, teams can buy players to bolster their ranks as they challenge for titles, to replace players who have suffered long-term injuries, or even utilize the market to dispense of unhappy players.

## Dataset
The dataset used for this visualization consists of the top 250 transfers made in each season of association football, starting from the year 2000, until the summer of 2018. It has a total of 4,700 rows, with 10 features describing the details of each transfer. However, the data for the final season is incomplete, hence I have removed the data, and the analysis does not include the 2018-2019 data. 

The variables are as follows:
* Name: The name of the player involved in the transfer from one team to another.
* Position: The position that they take up on the playing field.
* Age: The age of the player at the time the transfer occurred.
* Team_from: The team that they player transferred from.
* League_from: The league from which the team competes in.
* Team_to: The team that the player transferred to.
* League_to: The league where the player's new team competes in.
* Season: The season during which the transfer occurred. This is usually denoted between 2 years, due to the fact that a season of association football in the major leagues start during the middle of the year, and would take approximately 9 months to complete.
* Market_value: The value of the player based on numerous factors, such as player reputation, performances, age, skill, etc. Data for this contains null values, as it has only recently been recorded. As such, null values have been left as is, instead of attempting to extrapolate/interpolate values.
* Transfer_fee: The actual fee paid by the Team_to to the Team_from in order to acquire the services of the corresponding player.

The dataset can be found at this link: https://www.kaggle.com/vardan95ghazaryan/top-250-football-transfers-from-2000-to-2018/version/1

## Summary
