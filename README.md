
# Shark Attack Data Analysis Project
# Project Overview

This project analyzes the Shark Attack dataset to identify patterns in shark attacks based on country, activity, species,sex and type of attack

The main objective was to clean the dataset and draw insightfull hypotheses. 
# Data Cleaning Steps

The dataset contained inconsistent values and missing data. The following steps were performed:

- Removed unnecessary columns
- Checked null values using `isnull().sum()'
- Removed null rows using `dropna()'
- Removed Duplicates
- Standardized column names (lowercase,strip, removed spaces)
- Cleaned inconsistent country names by using regex.
- Cleaned Type of attacks by using replace
- Grouped similar activities (e.g., kite surfing, surf skiing → surfing)
- Cleaned and grouped different species of Shark.
- Cleaned and grouped 'Sex' using Mapping method
- Filled values using 'ffill' for sex 

# Exploratory Data Analysis

The following analysis was performed:

- Value counts of attacks by country
- Value counts by activity
- Value count of species
- Type of attack commonly observed
- Type of activity mostly responsibly for Shark attacks.
- Species frequency
- Attacks based on Gender 
- Attacks based on Age
- Visualized top activity in top 5 countries


# Key Insights

- USA recorded the highest number of shark attacks.
- Most of the attacks are unprovoked
- Surfing was the most common activity during attacks.
- For Bahamas Fishing was found to be the top activity during attack.
- Men are more prone to Shark attacks
- Almost all shark species attack during surfing activities. However bull sharks attack swimmers and the nurse shark species attack during fishing activities.
- 

# Technologies Used

- Python
- Pandas
- Regex library
- Google Colab
- Seaborn
- 
## Link
https://docs.google.com/presentation/d/1k34SLvGXxdjnmMW-m8MPkTKOWLGK3XvbxKFHbe8ijWI/edit?usp=sharing




