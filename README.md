# Predicting NBA Game Outcomes using ML
This project aims to develop a sophisticated machine learning model to predict the outcomes of NBA games. By leveraging comprehensive historical data on team and player statistics spanning 10 NBA seasons from 2013-2014 to 2022-2023, the project seeks to uncover hidden patterns and trends that can inform more accurate game outcome predictions.
The key aspects of this project include:
* Introducing player-impact scores for the top 5 performers of each team and a bench impact score to capture individual contributions and team depth.
* Employing advanced feature selection techniques, such as ANOVA F-value feature selection and correlation analysis, to identify the most relevant and non-redundant features.
* Utilizing a Random Forest classifier to handle a large number of features, capture non-linear relationships, and provide robust predictions.
* Evaluating the model's performance using time-series cross-validation and appropriate metrics like accuracy and precision.

By incorporating novel features, domain knowledge, and advanced machine learning techniques, this project aims to improve upon existing NBA game outcome prediction models and contribute to a better understanding of the factors influencing game results.

Link to Dataset: https://www.kaggle.com/datasets/lukedip/nba-boxscore-dataset

## Setup Instructions
1. Open the file in jupyter notebook
2. Ensure dataset is in the same folder as file
3. If you would like to run the whole notebook, Click Restart Kernal and Run All (Will take about 10 minutes). (NOTE: Hyperparameter Tuning is commented out. This section of the code is very computationally expensive and took about 40 minutes to run on my personal device with 16 cores. If you would like to run it, just uncomment it and run it.)

* I left the python notebook in a state that is pretty clean and displays the major results in the bottom sections.
