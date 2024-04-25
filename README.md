#Screen Time Analysis
This R script analyzes screen time data and provides insights inot average screen time by day and frequently used apps.
#Features 
Imports data from excel. 
Calculates average screen time for each day.
Generates a bar chart of avaerage screen time by day. 
Groups data into weekdays and weekends.
Performs a t-test to compare screen time between weekdays and weekends. 
Calculates time spent on each app for each day. 
Creates a bar chart of frequently used apps with time spent,coloured by day.
#Dependencies
readxl library for reading Excel files
ggplot2 library for creating visualizations 
tidyverse library for data manipulation and analysis 
#Usage 
1. Install the required libraries: readxl, ggplot2, and tidyverse 
2. Replace the file path in read_excel() with the path to your own screen time data Excel file
3. Run the script to generate the analysis and visualizations 
#Output 
Bar chart of average screen time by day.
T-test results comparing screen time between weekdays and weekends. 
Bar chart of frequently used apps with time spent, coloured by day. 
This script provides a comprehensive analysis of screen time data allowing you to gain insights into my daily screen time habits and the apps I use most frequently.
