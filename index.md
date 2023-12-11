Hi! My name is Igor and welcome to my data analytics portfolio.
Below you will find projects that I have been working on recently. 

# **Project 1: Hyrox Results Dashboard**

## **Overview:**
Hyrox is a rapidly growing sport of fitness racing. Participants sign up for the events where they have to complete 8km of running and 8 stations (alternating 1km run with a station). 
For more information, I would recommend checking Hyrox's official website: [Hyrox](https://hyrox.com)

### **Motivation behind a project:**
The purpose of this project is to allow members from my local gym to view and compare their Hyrox results. My dashboard provides an interactive and comparative platform for members to view their race results, unlike the official website which does not allow to compare results and forces users to manually export data into Excel or a piece of paper to compare times.

### **Solution:**
I have decided to create and publish a Tableau dashboard to allow all gym members who competed in Hyrox events to track their progress, compare results between events, and generate insight for personal trainers to spot areas for improvements for future events. 

### **High-level summary of the project:**
1. Getting hold of the data. 
   - At first, I exported the data manually by creating an Excel template where I would paste the raw data from the website. 
   - Then I would process the data, and paste it into a table (works well for sourcing individual results).
2. Scraping the data off the Hyrox website. 
   - For larger data sets, I had to find a way to scrape the data off the official website, however, I was unable to write an entire Python script from scratch. 
   - After doing some research, I found a Python script on Kaggle that allows me to scrape the data off the Hyrox website for selected events.
3. Transforming/cleaning data.
   - Once data was exported, I had to clean and transform the data.
   - Filtering the results of the gym members and removing other participant results.
   - Transposing the data.
   - Formatting the data correctly.
4. Cleaned and transformed data was uploaded to Tableau.
5. Building a dashboard.  
   - Creating calculated fields in Tableau to display key metrics.
   - Creating a Tableau dashboard using table and column charts to compare time between runs and stations.
   - Adding filters to make the dashboard interactive.

**Tableau dashboard:**
![Alt text](https://github.com/Igor-Fij/Portfolio/blob/main/images/Tableau%20Hyrox%20Dashboard.JPG?raw=true)
[Click here to access the dashboard.](https://public.tableau.com/views/HyroxResultsDashboard/ParticipantDashboard3?:language=en-GB&publish=yes&:display_count=n&:origin=viz_share_link)


**PowerBI dashboard:**
![Alt text](https://github.com/Igor-Fij/Portfolio/blob/main/images/PowerBI%20Dashboard.JPG?raw=true)
(Since I do not have PowerBI Pro, I can't publish my dashboard.)

---

# **Project 2: Voice of the Customer Dashboard**

## **Overview:**
This project is an example of the dashboards I would create in my current role. I was responsible for designing and managing surveys, then collecting data submitted by customers, analysing customer feedback, and reporting on the Key Performance Indicators like NPS Score, Satisfaction Score, Courtesy Score, or Knowledge Score. 

**For this project, I have created a fake customer satisfaction data sample similar to the one I would use in my workplace.**

### **Motivation behind a project:**
The goal behind this project is to showcase how I have been using my data visualisation skills to build Tableau/PowerBI dashboards for business stakeholders. Allowing them to have easy access to real-time metrics regarding Customer Satisfaction and empowering them to use collected data and conduct data analysis on their own by using filters to identify areas for improvement. 

### **Solution:**
Exporting raw data stored in multiple data repositories like MySQL database, data warehouse, or survey tools like Hubspot/SurveyMonkey. Cleaning, processing, and loading data into data visualisation tools (Tableau or PowerBI) to create interactive dashboards for use by myself and internal stakeholders. 

### **High-level summary of the project:**
1. Getting hold of the data. 
   - Exporting the data from the data repository.
2. Cleaning, transforming, and analysing data.
   - Reviewing data and checking if any cleaning needs to be done.
   - Transforming data (if needed). For example, SurveyMonkey data would have to be transposed from storing each record as a row to columns to allow easy manipulation of the data in powerBI.
   - Categorising customer text feedback into categories or sub-categories. This part of the process has been done manually to truly understand customer pain points and create accurate themes for the feedback provided. You could also use Excel formulas, python script, or AI tools to help automate the process however each solution has its limitations.
3. Cleaned and transformed data was uploaded to PowerBI.
4. Building a dashboard.
   - Creating new measures to calculate key metrics like NPS Score, Satisfaction Score, and Ease Score by utilising DAX aggregation functions.
   - Adding clustered bar charts to highlight responses received per category.
   - Adding a gauge chart to show % of responses for each NPS category (Promoters, Passives, and Detractors).
   - Adding a treemap chart to highlight the volume of responses received for each category (Detractors and Passives only).
   - Formatting a dashboard by creating a simple-looking design.
5. Publishing a dashboard for stakeholders to view, use, and provide feedback (due to not having access to PowerBI Pro, I am unable to publish the dashboard below).

**PowerBI dashboard:**
![Alt text](https://github.com/Igor-Fij/Portfolio/blob/main/images/NPS%20Dashboard%20PowerBI.JPG)
