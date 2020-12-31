# Chess Games Exploration (Lichess)


## Dataset

This is a part of a dataset that can be found [here](https://www.kaggle.com/datasnaek/chess) and it contains information about the most recent 20,000 games
 (at its time) played by the top 100 teams on [Lichess](https://www.lichess.org).
 It includes information about each game like; rating of the players, 
opening codes, game rating, number of turns, and who wins each game and how he/she wins it.<br>


## Summary of Findings

**I found that both difference in rating between players and number of turns in a game play important role in deciding the winner and the final game result which yielded, in my exploration, to several findings:**<br>


* Most of the games are played between players of the same or close rating and lasted until about 40 to 70 turns.<br>
* Players, as white or as black, are winning more when their ratings are higher than their opponents compared to when they have less rating than their opponents.<br>
* Games that are played with high difference in rating in the winner's favor tend to end in less number of turns than those with lower difference in rating.<br>
* There are more players as black winning the game with high number of turns specially when the rating difference is small.<br>



**As for the other variables interaction with the variables of interest; winner and victory status, I found the following:**<br>


* Player as white has more advantage over player as black in blitz rating games.<br>
* Highest winning percentage for white is at opening group C while, surprisingly, black has slight advantage when using opening group E.<br>
* Despite the fact that openings of group E are rarely used by the winner, they are popular among players of high ratings.<br>
* For all opening groups, it takes higher number of turns to beat an opponent by checkmate than it takes for a win by opponent resigning.<br>


## Key Insights for Presentation

The focus in my presentation will be on the obvious variations with rating difference and number of turns and I will  leave out some of the subtle variations. 
I will start with a scatterplot showing the variation of winners, as white and as black, with rating difference and number of turns.<br>


Afterwards, I will show how variables like game rating and opening codes have a slight influence on who and how the game is won.
I will use bar plots for the distribution of winning percentages on game ratings and opening codes.
Then, I will show a scatterplot for the distribution of game ratings that are played with different rating difference between players and ended after different number of turns.
Finally, I will show a point plot of the openings that were successfully used by the winners with different victory results and their variation with number of turns.<br>

