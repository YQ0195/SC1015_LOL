# SC1015_Group9
SC1015 mini project
# Contributors
Chin Han Wen

Liew Kai Wei

Khoo Yong Quan
# About 
This is a mini project for SC1015. We decided to work with a [dataset of statistics from "League of Legends" game](https://www.kaggle.com/datasets/bobbyscience/league-of-legends-diamond-ranked-games-10-min?select=high_diamond_ranked_10min.csv)
# Problem definition
Our group decided to find out the factors that contribute to a victory in a League of Lengends ranked game.
We wanted to find out how significantly early-game leads would determine the outcome of a match and if it is justified to surrender early based on these leads.

We used Logistic Regression and Decision Tree models to find the relationship between the chosen factors and victory.

We compared both models to find out which model was able to predict better.
# Conclusion
Due to the high false negative rates for all factors, there is still a very good chance of winning despite being behind at the 10th minute mark, and that despite deficits in the early-game, they are still winnable if you play them out.
# What we learned from our project
- Fitting the Logistic Regression model and what it tells us
- Differences between Logistic Regression and Decision Tree models
- Possibility of stopping snowball leads in "League of Legends"
- Effectiveness of data visualization using strip plot in the case of mixed data- categorical and numerical 
# References
https://www.kaggle.com/datasets/bobbyscience/league-of-legends-diamond-ranked-games-10-min?select=high_diamond_ranked_10min.csv

https://mobalytics.gg/blog/lol-how-to-get-better-at-league-of-legends/

https://towardsdatascience.com/introduction-to-logistic-regression-66248243c148
