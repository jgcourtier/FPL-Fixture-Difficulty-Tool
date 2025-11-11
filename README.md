# FPL-Fixture-Difficulty-Tool
A tool to calculate upcoming fixture difficulty in FPL, using Elo ratings.


As a Chess player, I can't help but accept that Elo ratings are an effective and accurate determinant of skill. As a result, it makes sense to use ClubElo's ranking of football clubs as a way to determine upcoming fixture difficuly in Fantasy Premier League.

The following works by calling both FPL and ClubElo APIs, for the upcoming FPL fixtures and the current Elo ratings of the Premier League clubs. Using the following equation, we can also work out the win probability based on the Elo ratings.


<img width="630" height="270" alt="image" src="https://github.com/user-attachments/assets/34d8f6cc-1c4e-4ceb-bd6d-efb22114bf96" />


As a result, the best way to use this tool is to find the teams that have a low average opponent Elo in the upcoming games coupled with a high average win probability. This is because purely looking at the opponent Elo in isolation ignores who is actually playing them. It's all well and good Burnley having fantastic fixtures, but they themselves will likely perform poorly due to their own low Elo.

When prompted, input the number of gameweeks you would like see calculated ahead.
