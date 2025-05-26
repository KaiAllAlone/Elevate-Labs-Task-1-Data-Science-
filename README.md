# Elevate-Labs-Task-1-Data-Science-
Repo containing task 1 submission of Debanuj Roy in Data Science domain


This notebbok has performed pre-processing on the  Netflix Movies Dataset from Kaggle

Step 1:-Removed Duplicates

Step 2:-checked fro NaN values

Step 3:- Removed NaN by either replacing with 'Unknown' or the 'mode' of the column

Step 4:-Some columns had a sequence of names so we made that into a list of seperate names

Step 5:-We parsed the date column into datetime object

Step 6:- We created seperate columns for Seasons to store the no of seasons the show was running for and minutes to store the duration of the show in minutes.The two of them were mutually exclusive

Step 7:-Lastly for columns containing strings we trimmed them to remove any leadin gor trailing whitespace.
