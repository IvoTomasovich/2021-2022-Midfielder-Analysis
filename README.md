**Introduction**

Soccer, or football as it is known globally, is the world's most popular sport. Clubs spend a significant amount of resources scouting and acquiring players to give their teams a better result. Among all positions, midfielders play a crucial role, bridging defense and attack. They can directly influence game outcomes through their versatility. Defenders and attackers generally specialize at their positions needs, that being either scoring and adding to an attack versus defending and stopping an attack. Midfielders have to do a combination of both of those making them trickier to value because some may be better at one aspect versus the other. Our project investigates midfielders in the top five European leagues—Premier League, La Liga, Serie A, Bundesliga, and Ligue 1—to determine:

Which league has the best-performing midfielders on average.
Which leagues offer the most accurate market value based on players perfomance.
Our findings aim to provide soccer scouts and analysts with a data-driven starting point to identify undervalued talent pools of midfielders and better allocate scouting resources.

**Motivation**

Understanding the value and performance of midfielders across leagues is crucial for clubs operating within constrained budgets. The results of this analysis can help scouts focus on leagues that provide the highest return on investment or fulfill specific tactical needs. By combining performance statistics and market value data, we create a resourceful analysis that bridges raw player stats with economic insights.

**Data Sources**
Our analysis utilizes two primary datasets:

The first data set is a Player Statistics Dataset.

It Contains over 100 performance statistics for every player across all five leagues from the 2021–2022 season. Source: Kaggle (https://www.kaggle.com/datasets/vivovinco/20212022-football-player-stats)

This dataset is great for our analysis because of the quantity of different stats; we're able to get a very good understanding of the quality of a player.

**Key stats include:**

Passing metrics to support the attack such as completion rates, progressive passes, and assists

General stats like minutes played, goals scored, and position

Our second dataset was our Market Value Dataset.

This data set will allow us to put a monetary value on stats and other variables that are looked at when scouting players, which furthers our primary objective to make it easier for scouts to find effective, under-valued players.

It provides players market values and was scraped from TransferMarkt using BeautifulSoup. Source: TransferMarkt (https://www.transfermarkt.us/)

**Key features include:**

Player name, nationality, league, and position

Market value in euros The datasets were merged and cleaned to focus exclusively on midfielders.

We merge bring datasets together to provide scouts with a way to see which leagues have players with better stats compared to how they are valued per Euro
