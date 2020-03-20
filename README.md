# predict regular-season mvp in the nba

This project intends to predict the NBA regular season MVP in 2 parts: first, shortlist all MVP-caliber candidates. Second, identify actual MVPs by score.

Sources of data: bbref data for basic & advanced stats for the past 20 seasons.

Background:
The MVP is determined by a coalition of sportswriters and other influential sports pundits. At the end of the regular season, they vote candidates in for 1st, 2nd, and 3rd place. Each placement has an assigned value of points. Once votes are in, all votes and tallied and the values are summed. The player with the highest scored value is thus crowned the MVP.

Oftentimes the MVP vote is colored by criteria other than stats; player narrative is an implicit factor in the voting. This project serves to determine if there is a numerical baseline that can consistently predict the MVP winner regardless of narrative.

For this project to be considered a success we look for at least 90% accuracy (TBD). The output is twofold: firstly, the output will show which candidates are "MVP-caliber." Secondly, the output with show of the MVP-caliber candidates, which one has the highest percentage of being crowned MVP.

New data throughout the year should be processed regularly to see if the predictions are changing. This code should not be run prior to February of each year (the All-Star game is on Presidents Day Weekend and colloquially marks the season half).

ML background:
This is a supervised learning problem since we have labeled data. Within supervised learning, this is a binary classification problem.
