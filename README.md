### Date created
This project and README file was created on Jube 19'th 2020.

### Project Title
Explore-US-Bikeshare-Data

### Description
In this project, I will explore data related to bike share systems for three major cities in the United States—Chicago, New York City, and Washington. Using Python, I will write a code import the data and answer interesting questions about it by computing descriptive statistics

Using Python to explore data related to bikeshare systems for three major systems in the US. 
The data will need to be munged into shape before being analyzed using descriptive statistics before being visualised.

The purpose of this taask to to continue to become familliar with the data analysis process.

   1. This process will be done using any Python Editor.
   2. The code should run w/o errors.
   3. Appropriate use of
        data structures/types
        loops/conditional statements
        Packages
        functions
        coding practices (i.e. Docstrings, comments, variable names & general readability)
   4. Analysis
        Pose two questions about the data
        Inspect the structure of the original data (very important)
        Clean the data
        Answer questions about the data using descriptive statistics
        Visualize the data (instead of using plt use seaborn or ggplot)
        Perform additional exploratory analysis
        Consider where data analysis can be applied to other fields

## Datasets
The datasets used for this script contain bike share data for the first six months of 2017. Some data wrangling has been performed by Udacity's staff before being provided to the students of DAND. Under the permission of Udacity, I have uploaded a copy of the datasets [here](https://drive.google.com/open?id=16FfhNDfAh0DvTIRw9r0plmWZlHPEcBa4). The file sizes are too big to be uploaded on GitHub, so they were uploaded on Google Drive instead. After downloading the datasets, place them in the same folder with this Python script.

The data is provided by [Motivate](https://www.motivateco.com/), which is a bike share system provider for many cities in the United States. The data files for all three cities contain the same six columns:
* Start Time
* End Time
* Trip Duration (in seconds)
* Start Station
* End Station
* User Type (Subscriber or Customer)

The Chicago and New York City files also contain the following two columns:
* Gender
* Birth Year

### Files used
bikeshare.py

### Software Used
To complete this project, it wll require the following softwares:
   1. Python
   2. A text editor, like Sublime or Atom
   3. A terminal application

### The Datasets
The datasets provided by Motivate, a bike share system provider in the US, contains randomly selected data for the first six months of 2017 for all three cities. The data files for all three cities contain the same core six columns:

   1. Start Time
   2. End Time
   3. Trip Duration
   4. Start Station
   5. End Station
   6. User Type

The Chicago and New York City files also have the following two columns:

   1. Gender
   2. Birth Year

### Answering Questions
Through writing code for this project, I'm able to answer the following questions about the bike share data:

   1. What month occurs most often in the start time?
   2. What day of the week (Monday, Tuesday, etc.) occurs most often in the start time?
   3. What hour of the day occurs most often in the start time?
   4. What is the total trip duration and average trip duration?
   5. What is the most frequently used start station and most frequently used end station?
   6. What is the most common trip (i.e., the combination of start station and end station that occurs the most often)?
   7. What are the counts of each user type?
   8. What are the counts of gender?
   9. What is the earliest birth year (when the oldest person was born), most recent birth year, and most common birth year?

### The Interactive Experience
For a more interactive experience, I wrote a script that took raw input in the terminal to present the statistics.

## Questions explored
The script answers the following questions about the bike share data:
* What is the most popular month for start time?
* What is the most popular day of week (Monday, Tuesday, etc.) for start time?
* What is the most popular hour of day for start time?
* What is the total trip duration and average trip duration?
* What is the most popular start station and most popular end station?
* What is the most popular trip?
* What are the counts of each user type?
* What are the counts of gender?
* What are the earliest (i.e. oldest person), most recent (i.e. youngest person), and most popular birth years?

## Future scopes
In the future, more functions that compute statistics will be added to answer more questions about the data. The possibilities of improving the interactive experience (e.g turning this script into a web app) will also be explored.

## Resources referred to complete this project
Use parse_dates to recognize datetime columns:
* https://stackoverflow.com/questions/21269399/datetime-dtypes-in-pandas-read-csv
* https://stackoverflow.com/questions/17465045/can-pandas-automatically-recognize-dates
* https://pandas.pydata.org/pandas-docs/stable/generated/pandas.read_csv.html

Assess datetime series:
* https://pandas.pydata.org/pandas-docs/stable/generated/pandas.Series.dt.html
* https://stackoverflow.com/questions/29366572/pandas-how-to-filter-most-frequent-datetime-objects

Filter date:
* https://stackoverflow.com/questions/29370057/select-dataframe-rows-between-two-dates

Check validity of date:
* https://stackoverflow.com/questions/9987818/in-python-how-to-check-if-a-date-is-valid/9987935

Add a day to a date:
* http://www.pressthered.com/adding_dates_and_times_in_python/

Read day of week, month, hour etc.:
* https://pandas.pydata.org/pandas-docs/stable/generated/pandas.Series.dt.html
* https://pandas.pydata.org/pandas-docs/stable/generated/pandas.Series.dt.dayofweek.html

Convert seconds to hours, minutes and seconds:
* https://stackoverflow.com/questions/775049/how-to-convert-seconds-to-hours-minutes-and-seconds
* https://docs.python.org/3/library/functions.html#divmod

Convert pandas series or dataframes to string:
* https://pandas.pydata.org/pandas-docs/stable/generated/pandas.Series.to_string.html
* https://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.to_string.html

Concatenate strings of two columns:
* https://stackoverflow.com/questions/19377969/combine-two-columns-of-text-in-dataframe-in-pandas-python
* http://pandas.pydata.org/pandas-docs/stable/generated/pandas.Series.str.cat.html#pandas.Series.str.cat

Set column widths:
* https://pandas.pydata.org/pandas-docs/stable/options.html
* https://pandas.pydata.org/pandas-docs/stable/generated/pandas.set_option.html

Other pandas and numpy functions:
* Lessons in the Introduction to Data Analysis section of Udacity's Data Aanaly
