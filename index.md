Hi! My name is Igor and welcome to my data analytics portfolio.
Below you will find projects that I have been working on recently. 

# Project 1: Hyrox Results Dashboard

## Overview:
Hyrox is a sport of fitness racing. Participants sign up for the events where they have to complete 8km of running split into 8x1km and 8 stations between them. For more information, I recommend checking Hyrox's official website: www.hyrox.com

### Motivation behind a project:
The purpose of this project is to allow members of my local gym community to view and compare their Hyrox results. The official website where participants can view the results is not the most user-friendly and does not allow you to compare results between events. The only available option is to manually export data into Excel or on paper and compare results.

### Solution:
As a result, I have decided to create and publish a Tableau dashboard to allow all gym members to track their progress, compare results between events, and help myself and other personal trainers to spot areas for improvements for future events.

### High-level summary of the project:
* First I had to get hold of the data. At first, I did it manually by creating an Excel template where I would paste the raw data, then process/clean the data, and paste it into a table (this works well for sourcing individual results).
* For larger data sets, I had to find a way to scrape the data off the website with my currently limited Python knowledge. 
* After doing some research, I found a Python script on Kaggle that allows me to scrape the data off for specific events.
* Once data was exported, I prepared the raw data in Excel to be loaded into Tableau.
* Next, I created calculated fields to display key metrics.
* Then, I created a Tableau dashboard using table and column charts to compare time between runs and stations.
* Lastly, filters were added to allow users to view their results.

Tableau dashboard:
![Alt text](https://github.com/Igor-Fij/Portfolio/blob/main/images/Tableau%20Hyrox%20Dashboard.JPG?raw=true)
[Click here to access dashboard.](https://public.tableau.com/views/HyroxResultsDashboard/ParticipantDashboard3?:language=en-GB&publish=yes&:display_count=n&:origin=viz_share_link)


PowerBI dashboard:
![Alt text](https://github.com/Igor-Fij/Portfolio/blob/main/images/PowerBI%20Dashboard.JPG?raw=true)



