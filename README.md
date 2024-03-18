# Data Cleaning & Visualisation - Bike Sales
This small project is an exercise in data cleaning and visualisation posted to GitHub on 18th March 2024.
The project begins with a comprehensive dataset of information on customers of an online business that sells bikes.
Information on customers includes headings such as marital status, gender, income, whether the customers have children, occupation, whether the customers own homes, the amount of cars customers own, commute distance to work, their region, their age, and whether they actually purchased a bike.
## Data Cleaning
26 duplicates were identified and removed using Excel's "remove duplicates" feature.
Marital status and gender were displayed as single letters. This is inconsiderate if you expect any other professional to handle your data, so using the replace function in Excel these were changed to include a full description on marital status and gender.
An age bracket was introduced. For visualisation purposes, it is often easier to read when ages are grouped in a way that makes sense to a marketing team such as "adolescent" or "middle aged". This was accomplished using nested "if" statements in a seperate column.
## Data Visualisation - Creating Pivot Tables
Four seperate pivot tables were created.
The first showed the average income of customers that purchased bikes seperated by gender.
The second showed the counts of purchases made by customers that fell into categories of different commute distances from work.
The third showed the counts of purchases made by customers that fell into categories of the different age brackets created during data cleaning.
The fourth showed the counts of purchases made by customers by their age to investigate if the inclusion of an age bracket was necessary. It proved to be easier to comprehend the graph that seperated age into brackets.
## Data Visualisation - Creating a Dashboard
Using the graphs generated from the pivot tables, a dashboard was constructed.
The first three graphs were included in the dashboard display and were linked with three different slicers.
The first slicer controlled customer marital status. A user of the dashboard can select "Married" or "Single" and the graphs would automatically update to show data only corresponding to the group selected.
The second slicer controlled customer region. A user of the dashboard can select "Europe", "North America", or "Pacific" and the graphs would automatically update to show data only corresponding to the group selected.
The third slicer controlled customer education. A user of the dashboard can select "Partial High School", "High School", "Partial College", "Bachelors", or "Graduate Degree" and the graphs would automatically update to show data only corresponding to the group selected.
