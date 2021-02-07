# IPL-Data-Analysis-using-Python-EDA


# Welcome to Data Analysis in Python
In this tutorial, We will see how to get started with Data Analysis in Python. The Python packages that we use in this notebook are:

numpy
pandas
matplotlib
seaborn
The dataset that we use in this notebook is IPL (Indian Premier League) Dataset



# Loading the Libraries
Pandas is used for Data Processing and is also the most popular library in python used for data analysis.

# Getting Basic Details of Data
The shape gives the number of rows and columns in the data. Here, 637 rows and 17 columns are present.





# Observations:
The following inferences can be made from the describe() method:
The .csv file has data of IPL matches starting from the season 2008 to 2019.
The biggest margin of victory for the team batting first(win_by_runs) is 146 runs.
The biggest victory of the team batting second(win_by_wickets) is by 10 wickets.
75% of the victorious teams that bat first won by a margin of 19 runs.
75% of the victorious teams that bat second won by a margin of 6 wickets.
There were 756 IPL matches hosted from 2008 to 2019.



The dataset has 18 columns. Let’s get acquainted with the columns.
id: The IPL match id.
season: The IPL season
city: The city where the IPL match was held.
date: The date on which the match was held.
team1: One of the teams of the IPL match
team2: The other team of the IPL match
toss_winner: The team that won the toss
toss_decision: The decision taken by the team that won the toss to ‘bat’ or ‘field’
result: The result(‘normal’, ‘tie’, ‘no result’) of the match.
dl_applied: (1 or 0)indicates whether the Duckworth-Lewis rule was applied or not.
winner: The winner of the match.
win_by_runs: Provides the runs by which the team batting first won
win_by_runs: Provides the number of wickets by which the team batting second won.
player_of_match: The outstanding player of the match.
venue: The venue where the match was hosted.
umpire1: One of the two on-field umpires who officiate the match.
umpire2: One of the two on-field umpires who officiate the match.
umpire3: The off-field umpire who officiates the match
A mere glance of the DataFrame through its columns indicates the presence of NaN values in the ‘umpire3’ column. Let’s see the count of NaN values in the column.



# Exploratory Analysis and Visualization
Now that our data set has been cleaned up, it’s time to do the in-depth analysis and visualization.
Let’s begin by importingmatplotlib.pyplot and seaborn.


The team with the most number of wins per season.
Each IPL season has a fair share of excitement and adulation. No team other than Chennai Super Kings(in 2010 and 2011) was able to win the IPL trophy in succession. That is a testimony to the unpredictability of IPL.
Let’s analyze the team with the most wins in each season.

Observations:
Mumbai Indians has secured the most wins in four seasons(2010, 2013, 2017, and 2019).
The venue that hosted the maximum number of matches


