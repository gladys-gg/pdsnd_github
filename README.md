>**Note**: Please **fork** the current Udacity repository so that you will have a **remote** repository in **your** Github account. Clone the remote repository to your local machine. Later, as a part of the project "Post your Work on Github", you will push your proposed changes to the remote repository in your Github account.

### Date created
December 5th 2021

### Project Title
Replace the Project Title

### Description
Udacity Bikeshare project

This Python script is written for Project 2  of Udacity's Data Science with Python Nanodegree and is used to explore data related to bike share systems for Chicago, New York City, and Washington. It imports data from csv files and compute descriptive statistics from the data. It also takes in users' raw input to create an interactive experience in the terminal to present these statistics.

The datasets used for this script contain bike share data for the first six months of 2017. Some data wrangling has been performed by Udacity's staff before being provided to the students of DAND. Under the permission of Udacity, I have uploaded a copy of the datasets here. The file sizes are too big to be uploaded on GitHub, so they were uploaded on Google Drive instead. After downloading the datasets, place them in the same folder with this Python script.

The data is provided by Motivate, which is a bike share system provider for many cities in the United States. The data files for all three cities contain the same six columns:

Start Time
End Time
Trip Duration (in seconds)
Start Station
End Station
User Type (Subscriber or Customer)
The Chicago and New York City files also contain the following two columns:

Gender
Birth Year

Questions explored
The script answers the following questions about the bike share data:

What is the most popular month for start time?
What is the most popular day of week (Monday, Tuesday, etc.) for start time?
What is the most popular hour of day for start time?
What is the total trip duration and average trip duration?
What is the most popular start station and most popular end station?
What is the most popular trip?
What are the counts of each user type?
What are the counts of gender?
What are the earliest (i.e. oldest person), most recent (i.e. youngest person), and most popular birth years?

### Files used
washington.read_csv
chicago.read_csv
new_york_city.read_csv
bikeshare_2.py

### Credits
https://stackoverflow.com/questions/21269399/datetime-dtypes-in-pandas-read-csv

https://stackoverflow.com/questions/17465045/can-pandas-automatically-recognize-dates

https://pandas.pydata.org/pandas-docs/stable/generated/pandas.read_csv.html

https://pandas.pydata.org/pandas-docs/stable/generated/pandas.Series.dt.html

https://pandas.pydata.org/pandas-docs/stable/generated/pandas.Series.dt.dayofweek.html

https://pandas.pydata.org/pandas-docs/stable/generated/pandas.set_option.html?ref=https://githubhelp.com
