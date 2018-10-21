# GoT-Analysis
Analysis of Game of Thrones dataset. Made for Udacity Nano Degree.

One of the assignments in the course is to conduct a deeper analysis of a dataset, and then present this analysis for others to see. A couple of suggestions for datasets were presented, but after browsing Kaggle, the game of thrones dataset ( https://www.kaggle.com/mylesoneill/game-of-thrones/version/1 ) caught my eye.

I read all of the books of the series, and watched all of the episodes of the HBO show, so it is safe to say I am invested in the Universe. Therefore i thought it would be interesting to use my newly aquired Data Science abilities to dig into the Game of Thrones Data.

This analysis answers the following questions:
* Did winter help the Starks to win their battles?
* Characteristics of deaths?
* What is the distribution of characters lifespan in term of chapters?

The analysis concludes that
* Winter did **not** help the Starks win any wars
* Males had an unproportional tendency of dying, compared to the general gender distribution in the universe
* Most character die very few chapters after their introduction.

A blogpost showing the visuals of these conclusions can be found at https://medium.com/@jhhcons/game-of-thrones-aeeddfa14562

For this project, the pandas, numpy and seaborn packages were used.

The following files are present in this project:
* GoT Analysis.ipynb - The Jupiter Notebook containing the analysis
* README.md - This Readme
* battles.csv - Battle data
* character-deaths.csv - Character death specific information
* character-predictions.csv - Base information about the differnet characters in the Universe, along with a prediction of likelyhood of death.
