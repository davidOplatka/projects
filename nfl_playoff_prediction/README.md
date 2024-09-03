A lot of people try different ways to predict sports, from picking every single game or just based on how you feel a team may perform in a given year.
I decided that I want to take a very simple approach for predicting the 2024-2025 NFL regular season:
Assign win probabilities to each team based on my perceived ranking and let a basic probabilistic simulation handle the rest.

For this project, I ranked all 32 NFL teams into tiers based on online power rankings and my own feelings about how each team ranks going into this season (so yes, there is definitely some human bias in this model).
I then assigned win probabilities for each of the tiers based on the projected number of wins.
For example, in the top tier with 4 teams, I expect each of them to win around 12.5 games (I got this number by looking at the records of the top 4 teams over the last few NFL seasons).
Thus, I gave teams in this tier a win probability of $\frac{12.5}{17}$, or about 0.74, win probability for any given game in the regular season.

With these probabilities, I then use a random number generator to simulate each NFL regular season game and then record all of the results.
I ran this kind of simulation 10,000 times and then determined the most likely scenarios to determine my final predictions.

Check out each of the notebooks to see how I built my data tables, ran my simulations, and segmented the results to come to a final prediction.
