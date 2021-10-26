
# Kickstarting with Excel

## Overview of Project

Louise wants to start crowd campaign 'Fever' and before  jumping into her first fund raising campaign, She need help to organize, Sort and Analyze crowd funding data to determine whether there are specific factors to make project campaign successful. We are making data more readable and searchable to retrive the data we needed for our analysis.

### Purpose

Report data in order to justify the concluision that theatre catagory has the most successful outcome. The purpose of this analysis is to get additional visualization of data to see outcomes of all the categories by creating summary tables, charts and graphs. 
(many organizations spend months looking through past projects in an attempt to discover some trick for finding success.)

## Analysis and Challenges
    Here is the Organized data with some needed columns Using functions and Sorting. 
    
   <img width="1399" alt="Screen Shot 2021-10-25 at 9 36 17 PM" src="https://user-images.githubusercontent.com/92277581/138799913-be1859d2-5fa6-4d30-857b-dbecda42dd54.png">

    
  

### Analysis of Outcomes Based on Launch Date
    Based on Launchdate, Theatre catagory has most successful outcomes.
1. Rename the StarterBook.xlsx file you have been working with in this module: Kickstarter_Challenge.xlsx.
2. Create a folder called “resources” to hold the PNGs of the two charts you will create.
3. In the Kickstarter_Challenge.xlsx workbook, create a new column labeled "Years."
4. In the "Years" column, use the YEAR() function to extract the year from the “Date Created Conversion” column. 
5. Create a pivot table from the KickStarter worksheet, and place the pivot table in a new sheet.
6. Label the sheet "Theater Outcomes by Launch Date."
7. Filter the pivot table based on "Parent Category" and "Years."
8. Place the appropriate pivot table fields in the columns, rows, and values.
9. Filter the column labels to show only "successful," "failed," and "canceled."
10. Here is the pivot table:
  
    <img width="435" alt="Screen Shot 2021-10-25 at 9 49 32 PM" src="https://user-images.githubusercontent.com/92277581/138800679-bd092cf4-2a47-4455-ad2a-6e5d865e6ab0.png">

   
11. Create a line chart from the pivot table to visualize the relationship between outcomes and launch month.
12. Add a title to the line chart, and save it as Theater_Outcomes_vs_Launch.png to the resources folder.

   
    Here is the line chart for the Theatre outcomes based on Launch date: 
    
    <img width="679" alt="Screen Shot 2021-10-25 at 9 28 29 PM" src="https://user-images.githubusercontent.com/92277581/138800743-099dd076-5318-4189-8938-0d6e8f3ab849.png">

    
    

### Analysis of Outcomes Based on Goals

1. In the KickStarter sheet, create a new sheet and label it "Outcomes Based on Goals."
2. In the new sheet, create the following columns to hold the data:
    Goal
    Number Successful
    Number Failed
    Number Canceled
    Total Projects
    Percentage Successful
    Percentage Failed
    Percentage Canceled
3. In the “Goal” column, create the following dollar-amount ranges so projects can be grouped based on their goal amount.

<img width="167" alt="Screen Shot 2021-10-25 at 9 55 27 PM" src="https://user-images.githubusercontent.com/92277581/138801213-dd3ac2f2-78f5-432b-b564-2b850e22a0be.png">


4. Use COUNTIFS() functions to populate the "Number Successful," "Number Failed," and "Number Canceled" columns by filtering on the Kickstarter "outcome" column, on the "goal" amount column using the ranges created in Step 3, and on the "Subcategory" column using "plays" as the criteria.
5. Use the SUM() function to populate the "Total Projects" column with the number of successful, failed, and canceled projects for each row.
6. Calculate the percentage of successful, failed, and canceled projects for each row.
7. Create a line chart titled "Outcomes Based on Goal" to visualize the relationship between the goal-amount ranges on the x-axis and the percentage of successful, failed, or canceled projects on the y-axis.
8. Confirm that your line chart looks like the following, and save it as Outcomes_vs_Goals.png to the resources folder.


<img width="1209" alt="Screen Shot 2021-10-25 at 9 58 01 PM" src="https://user-images.githubusercontent.com/92277581/138801426-87b615ab-3966-4200-8bcb-d914637a544f.png">




### Challenges and Difficulties Encountered



## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
    1. Theatre catagory has most successful outcomes than other catagories.
    2. Month of May and June has more successful outcomes. 
- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
