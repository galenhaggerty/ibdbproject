# IBDB Python and R Project
The files in this repository contain code for Data Analysis for R & Python created by Galen Haggerty. The code was created for a final project for a Data Analysis for R & Python (ECO 590) class at Pace University

### Code
The code in this repo webscrapes the IBDB 2018/2019 season page to pull a list of Broadway Show URLS

It then loops through the URLs to pull data from the "statistics table" on each page to get the Gross Revenue, Attendance, Capacity, and Average Gross Potential per week over the 2018/2019 season

It then averages the above variables for each show and creates a new column "Average Price" - dividing the Average Gross/ Average Attendance


### Files
Update your file path in the first section of code

Download the "bway_manual_data.csv" and save to your file path

Use the "bway_manual_data.csv" to add the titles and category (Original/Revival), you will use this to merge with the data pulled from the statistics table found on the show pages

View the "R--Final-Project.html" to review the regression results found in the R Markdown notebook "Galen Haggerty - Final Project (R) .Rmd"
