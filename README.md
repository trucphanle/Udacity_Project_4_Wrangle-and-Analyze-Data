# Udacity_Project_4_Wrangle-and-Analyze-Data

This is my repository for the project and files for the third project in the Udacity Data Analyst Nanodegree program.

## Project Overview
This data wrangling project involves datasets obtained from @WeRateDogs Twitter account and has three main stages:
1. Gathering data
2. Assessing data
3. Cleaning data

### Gathering
Data was gathered from 3 different sources:
- From WeRateDogs Twitter archive given by Udacity in csv format.
- Image prediction file downloaded programmatically using Requests library and the URL provided by Udacity in tsv format.
- Data retrieved by querying Twitter's APIs and using Tweepy library.

### Assessing
After gathering the data and storing them in DataFrames, the following step was assessing the data for quality and tidiness. Data were assessed programmatically and visually.

### Cleaning
It is the process of fixing and resolving issues identified in the Cleaning process. The (define, code, and test) steps were used in the cleaning process. First, copies of the DataFrames were created before cleaning. Then, the steps of cleaning were applied iteratively on all issues.

### Storing
The final DataFrame called 'twitter_arc_clean' contains 2356 rows and 17 columns with the correct data types. The dataset is then stored in a csv file called 'twitter_archive_master.csv'. At this point, the data was successfully wrangled and therefore ready for analysis and visualization.

### Analysis & Visualization
These steps are not part of data wrangling process. However, it cannot reflect correct and accurate insights without performing data wrangling first. Visualizations and insights are provided in `act_report.pdf`.
