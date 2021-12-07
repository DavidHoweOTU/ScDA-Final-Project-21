# Can We Use Statistics To Get Better At Among Us?

## About us:
The people involved with this project were: \
David Howe ([@DavidHoweOTU](https://github.com/DavidHoweOTU)) \
Dewan Mohammad Tasinuzzaman ([@Dewan-Mohammad-Tasinuzzaman](https://github.com/Dewan-Mohammad-Tasinuzzaman)) \
Sameer Khan ([@sameermkhan-creator](https://github.com/sameermkhan-creator))

## Introduction
If you were bored during the pandemic in 2020, chances are you played "Among Us" with your friends.
It's a simple multiplayer-based indie game where "crewmates" work together to find which players in the group
are "imposters" before the imposters can kill them all. It's a game full of deception and reasoning, so
understandably, every player plays the game with their own strategies. But which one is the best? \
\
Is it smarter to focus on voting out imposters or go for a task win? Does completing more tasks or fixing sabotages increase your chances of getting killed? How often do players on average, correctly vote out imposters? And which one is really the easiest? Playing as a crewmate or an imposter? These are the questions we set out to answer, and through the power of data analysis, here's what we found...

## Discussion
1/ Does voting out imposters significantly increase your chance of winning compared to doing all your tasks?
To analyse the data more visually regarding the win rate depending on if you voted or completed tasks, a pie chart is used which is also color coded.

Looking at this data analysis pie chart, it shows the win rate by voting the imposter out is 29.3% which is the higher win rate compared to doing the tasks which was 26.4%.

But on the other hand the loss rate of voting (27.03%) is way higher than the loss rate of losing (17.26%).

Working together to vote the imposter out it is the best chance to win the game, but if you taskmates want to play it safe and complete the set out tasks you have a extremely less likely chance of losing the game.

2/ Is it easier to win as a crewmate or as an imposter? 
To analyse the data more visually regarding the win rate depending on if you are imposter or crewmate,a pie chart is used which is also color coded.

Firstly, looking at the pie chart used to analyse this specific scenario, it is very clear that being a crewmate you have the highest win rate (44.1%) but also the highest losing rate (35%).
Secondly, being imposter the win rate is low (11.7%) but not too much different from the losing rate (9.2%)

Being a crewmate you have a significantly higher winrate due to numbers (multiple crewmates and maximum 2 imposters). BUT this high winrate is couples with a high losing rate so that means your chances of winning weigh highly on you having a capable set of crewmates that can work together to a win. Now looking at the imposter loss/win percentage it seems it is very dependent on the specific ability of the imposter to win or lose.

3/ Does completing more tasks increase your chances of getting murdered
To analyse the data more visually regarding the correlation between # of tasks completed and the likelihood of getting murdered,a bar graph is used which is also color coded.

From a range of 0 tasks to 10 it seems that normally up to completing 1-6 tasks you are not murdered, but after 6+ tasks the rate of dying significantly increases.

By trying to survive to the end game doing tasks throughout increases your chance of dying by alot especially as less and less crewmembers are alive by doing 6+ tasks its more likely for you to die by an imposter.

4/ How often are players able to correctly vote out imposters? 
To analyse the data more visually to see the number of ejections by team to their own crewmate or to an imposter a heatmap was used.


During these games there is alot of voting to weed out imposters many times teammembers are in disagreement to who is an imposter to be ejected. But overall it looks that 64% of the time the teammates are able to correctly vote out the imposter. We came to that parecentage by looking at the amount of time innocent crewmate were ejected (55) and the amount of time imposters were ejected (82) 55/82 = 0.64 x 100 = 64% which is a very good imposter detection/ejection rate.

Yes, 6 out of 10 times teammates correctly vote out the imposters.

5/ Does fixing sabotages increase your chances of dying?
To analyse the data more visually to see the correlation between fixing the sabotages and the rate of dying by an imposter a bar chart was used.

Looking at the bar chart it seems that NOT fixing the sabotages the rate of dying by an imposter was extremely high. Fixing 1+ sabotages the rate of dying was drastically less.

I will be able to conclude that fixing the sabotages you have a better chance of surviving that would be because when you are fixing the sabotages with you teammates you guys are able to deter the imposter from attempting to kill because if the imposter tried to the other teammate next to you would report the imposter just as you died. On the other hand if u stick to doing tasks and are seperated from your teammates fixing the sabotage then the imposter will have a easier chance of killing you.

## Conclusion
Limitations and future directions:     
Certain other stats like, when someone dies, what map they played on, and where they died and records of chat messages from players would have been incredibly useful.

Future: To get more data and record more types of info and do similar tests.

Things we did not predict:  
* We orginally thought more sabotage fixes would lead to more murder, but it was the opposite.

What did we learn:
*   By completing sabotages you are more likely to survive the duration of the game.
*   Try to do the long tasks in the beginning of the game then the short ones torwards the end to have a better surivival rate.

*   Ensure you have good teammates than can work together and be able to vote collectively to increase win rate.
*   While only voting is a good way to win the game, still focus on your tasks as it is better chance for the long run to secure the win.

## Acknowledgements
This project was submitted as the final course project for CSCI 2000U “Scientific 
Data Analysis” during Fall 2021. The authors certify that the work in this 
repository is original and that all appropriate resources are rightfully cited.

The dataset used for this report is "[Among Us Dataset](https://www.kaggle.com/ruchi798/among-us-dataset)" posted to Kaggle by Ruchi Bhatia. This dataset is in the public domain and is safe to use for data analysis projects such as this one.

## README
To properly run the included Jupyter notebook and recreate our results, download the repository and run 
the notebook in the same directory as the CSV files containing the original dataset. Run all cells 
in the order they appear in the notebook. Rerunning cells or running cells in the wrong order
may cause errors. If this happens, restarting the kernel will fix the issue.
