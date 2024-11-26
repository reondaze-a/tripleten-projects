# Integrated Project 1: Ice
[Project Notebook](https://github.com/reondaze-a/tripleten-projects/blob/main/project-5/integrated-project-1.ipynb)

In this project I'll be working with data from Ice, an online store that sells video games. User and expert reviews, genres, platforms (e.g. Xbox or PlayStation), and historical data on game sales are available from open sources.

# Goal
I'm tasked on creating an advertising campaign for the company. I'll need to identify patterns that determine whether a game succeeds or not. This will allow you to spot potential big winners and plan advertising campaigns. The data dates back to 2016. I'll be making a campaign as though I'm preparing for the year 2017.

## Hypotheses:
1. Average user ratings of the Xbox One and PC platforms are the same. 
2. Average user ratings for the Action and Sports genres are different.

# Data Description
- `Name`: name of the videogame
- `Platform`: platform of the game
- `Year_of_Release`: year the game was released
- `Genre`: the genre of the game 
- `NA_sales`: sales in North America in USD million.
- `EU_sales`: sales in Europe in USD million
- `JP_sales`: sales in Japan in USD million
- `Other_sales`: sales in other countries in USD million. 
- `Critic_Score`: scores from critics (maximum of 100) 
- `User_Score`: scores from users (maximum of 10) 
- `Rating`: Rating from (ESRB)

# Libraries
- Pandas
- Seaborn
- NumPy
- Scipy
  - Stats
- Matplotlib
  - Pyplot
