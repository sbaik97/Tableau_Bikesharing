
# Tableau_Bikesharing

Creating Tableau Dashboards and stories about NYC Citi Bike in order to make a solid business proposal of a bike-sharing program in Des Moines city, Iowa.

## Tableau Public Website
[Tableau_Public_Sungil Baik](https://public.tableau.com/profile/sungil.baik#!/vizhome/NYC_Citibike_Challenge_16084077890610/Story1?publish=yes)


## Background

As the new lead analyst for the [New York Citi Bike](https://en.wikipedia.org/wiki/Citi_Bike) Program, you are now responsible for overseeing the largest bike sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicize and improve the city program.
Herein, we'll work with data visualization software called Tableau to present a business proposal for a bike-sharing company. First, we'll learn how to import, style, and portray data accurately. Then, we'll create worksheets, dashboards, and stories to visualize key data from a New York Citi Bike dataset.

## Objective and Goal

 - Import data into Tableau.
 - Create and style worksheets, dashboards, and stories in Tableau.
 - Use Tableau worksheets to display data in a professional way.
 - Portray data accurately using Tableau dashboards.

## Software/Tools
* Tableau, VS Code, Jupyter Notebook, Pandas, Github
* The data is provided [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage.


## Tasks

**Using Tableau we visualize in many aspect.**
 * Determine the Number of Trips
 * Find the Proportion of Short Term Customers to Annual Subscribers
 * Find the Peak Riding Hours in August
 * Find Top Starting and End Locations
 * Find the Number of Rides by Gender
 * Find the Average Trip Duration by Age
 * Determine the Bikes Due for Repair
 * Determine Bike Utilization
 * Few tasks are summurized in the following dashboard.

![City Bike Dashboard](/Practice/2019_citybike.jpg)

## Challenge

From the analysis, we’ll use Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, you’ll create a set of visualizations to: (1) Show the length of time that bikes are checked out for all riders and genders (2) Show the number of bike trips for all riders and genders for each hour
of each day of the week, (3) Show the number of bike trips for each type of user and gender for each day of the week, (4) Finally, you’ll add these new visualizations to the two you created in this module for your final presentation and analysis to pitch to investors.


* Change Trip Duration to a Datetime Format
Using Python and Pandas functions, you’ll convert the "tripduration" column from an integer to a datetime datatype to get the time in hours, minutes, and seconds (00:00:00). After you convert the "tripduration" column to a datetime dataytpe, you’ll export the DataFrame as a CSV file.

![NYC_Citibike_Datetime Format Chage by Python](/NYC_Citibike_Challenge.ipynb)

* Create Visualizations for the Trip Analysis
(1) Create the Checkout Times for Users Visualization
![City Bike worksheet1](/Image/Slide2.PNG)

(2) Create the Checkout Times by Gender Visualization
![City Bike worksheet2](Image/Slide3.PNG)

(3) Create the Trips by Weekday for Each Hour Visualization
![City Bike worksheet2](Image/Slide4.PNG)

(4) Create the Trips by Gender (Weekday per Hour) Visualization
![City Bike worksheet2](Image/Slide5.PNG)

(5) Create the User Trips by Gender by Weekday Visualization
![City Bike worksheet2](Image/Slide6.PNG)




* Lastly, Create a Story and Report for the Final Presentation.

* For this part of the Challenge, you’ll create a story in Tableau and write a report that describes the key outcomes of the NYC Citibike analysis you
did in the module and in Deliverable 2. This stroy is published in the Tableau Public link:

[Tableau_Public](https://public.tableau.com/profile/sungil.baik#!/vizhome/NYC_Citibike_Challenge_16084077890610/Story1?publish=yes)


## Considerations

Remember, the people reading your analysis will NOT be data analysts. Your audience will be city officials, public administrators, and heads of New York City departments. Your data and analysis needs to be presented in a way that is focused concise, easy-to-understand, and visually compelling. Your visualizations should be colorful enough to be included in press releases, and your analysis should be thoughtful enough for dictating programmatic changes. 



