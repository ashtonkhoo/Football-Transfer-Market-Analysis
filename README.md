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
In recent history, the majority of high profile transfers made are usually related to Europe's top 5 leagues. This can be attributed to their reputation, the number of fans these teams have, and the quality of football played. Fans want to see the best players, and these players are usually on show for the best teams in world football. From the analysis of the top 5 leagues, observe that teams in the Premier League in England are involved in transfers between these leagues the most. They are regarded as the most competitive league in the world, and players are more likely to want to see how they fare against top quality opponents. On the other hand, the German Bundesliga are involved in the least amount of transfers, as it is not as competitive, with Bayern Munich usually dominating the league, and buying the best players from rival teams, thus effectively strenghtening themselves while weakening their rivals. During this period of time, the German Bundesliga might not have been viewed as an attractive destination for players looking to further their careers. 

Through the years, F.C. Porto from Portugal have garnered the most revenue from player sales. They consistently produce high quality players, but are forced to sell them due to the fact that the Portuguese league is not as competitive, nor is it as attractive as Europe's top 5 leagues, as players look for a new challenge in an effor to further their careers. Alternatively, Chelsea F.C. from England's premier division have spent the most during this period. In 2003, Russian billionaire businessman and politician Roman Abramovich took over the club, and has since invested heavily in the team to bring glory to the London based team. They have spent even more than the likes of Real Madrid C.F., who are known to spend big on high profile players, including world record fees (at the time) for star players Cristiano Ronaldo and Gareth Bale.

Overall, we can see that prior to the 2010-2011 season, teams usually pay close to the market value to acquire a player. However, since the turn of the decade, teams have started to pay more than what the players are actually worth. With television broadcasting deals and sponsorship money, even mediocre teams are unwilling to sell their best players unless they become unhappy and are seen as detrimental to the squad's harmony. Thus, teams have to propose lucrative deals to the selling team to tempt them into selling the wanted player. 

Teams that do overpay for players, do so for several reasons, such as:
* Paying a premium for star players.
* Player may have multiple suitors, thus buying team has to offer more money to secure transfer.
* Selling team haggles and delays transfer until end of transfer window, forcing buying club to fork out more money to secure transfer.

There are also instances where teams underpay for players, where:
* The player is approaching the end of their prime, and are seen as dispensable.
* The player is unhappy and has forced the selling club into accepting a less-than-ideal offer.
