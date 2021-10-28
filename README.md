
# Kickstarting with Excel

## Overview of Project

Louise wants to start her first ever crowdfunging campaign 'Fever' and before  jumping into her first fund raising campaign, She need help to organize, sort and analyze crowd funding data to determine whether there are specific factors to make project campaign successful. Here, making data more readable and searchable to retrive the data we needed for our analysis.

### Purpose

Report data in order to justify the concluision that theatre catagory has the most successful outcome. The purpose of this analysis is to get additional visualization of data to see outcomes of all the categories by creating summary tables, charts and graphs using various country data. 
(many organizations spend months looking through past projects in an attempt to discover some trick for finding success.)

## Analysis and Challenges
    
 As per my analysis, Theatre catagory has most successful outcomes than other catagories and the least successful was food category. Also, Month of May-July has more successful outcomes and then it s†arted falling down.
    
    
   I have started analysis with the help of Excel functions. Here is the Organized data with some needed columns Using functions and Sorting. I have organized data using filters and formating, also used Freeze function for some clumn and raws for this Analysis using the dataset given:
    
   <img width="1399" alt="Screen Shot 2021-10-25 at 9 36 17 PM" src="https://user-images.githubusercontent.com/92277581/138799913-be1859d2-5fa6-4d30-857b-dbecda42dd54.png">

    
  

### Analysis of Outcomes Based on Launch Date
    
   This campaign had many different projects but Based on Launchdate, Theatre catagory has the most successful outcomes.
    
 I have started with creating column for "Years" using year() function to extract the year from the “Date Created Conversion” column. Then, created Pivot table with adding columns, raws and values based on "Parent Category" and "Years". Next, filtered the column labels to show only "successful" "failed" and "canceled".


 Here is the Pivot table for all the Parent categories outcomes by launch date:
 
<img width="435" alt="Screen Shot 2021-10-25 at 9 49 32 PM" src="https://user-images.githubusercontent.com/92277581/139285247-c001dcd8-28fa-450a-b1b7-1f4d1de7178d.png">

Here is the pivot table for only Theater category outcomes by launch date:
  
   <img width="444" alt="Screen Shot 2021-10-28 at 9 58 54 AM" src="https://user-images.githubusercontent.com/92277581/139282725-6f2585b2-e024-4a15-9f8f-f56d5a812235.png">

   
Next, Created a line chart from the pivot table to visualize the relationship between outcomes and launch month.
   
Here is the line chart for the Theatre outcomes based on Launch date: 
    
  <img width="679" alt="Screen Shot 2021-10-25 at 9 28 29 PM" src="https://user-images.githubusercontent.com/92277581/138800743-099dd076-5318-4189-8938-0d6e8f3ab849.png">

    
    

### Analysis of Outcomes Based on Goals
   Based on Goals, Less Amounts of Goals has more successful outcomes. 
   
 1. In the new sheet, created the following columns to hold the data:
    Goal
    Number Successful
    Number Failed
    Number Canceled
    Total Projects
    Percentage Successful
    Percentage Failed
    Percentage Canceled
2.  In the “Goal” column, create the following dollar-amount ranges so projects can be grouped based on their goal amount.

<img width="167" alt="Screen Shot 2021-10-25 at 9 55 27 PM" src="https://user-images.githubusercontent.com/92277581/138801213-dd3ac2f2-78f5-432b-b564-2b850e22a0be.png">


3. Here, Using COUNTIFS() functions to populate the "Number Successful," "Number Failed," and "Number Canceled" columns by filtering on the Kickstarter "outcome" column, on the "goal" amount column using the ranges created in Step 2, and on the "Subcategory" column using "plays" as the criteria. Also, Used the SUM() function to populate the "Total Projects" column with the numbers and then calculate percentages. 

Here is "Outcomes Based on Goal" to visualize the relationship between the goal-amount ranges on the x-axis and the percentage of successful, failed, or canceled projects on the y-axis.


<img width="1209" alt="Screen Shot 2021-10-25 at 9 58 01 PM" src="https://user-images.githubusercontent.com/92277581/138801426-87b615ab-3966-4200-8bcb-d914637a544f.png">



### Challenges and Difficulties Encountered

   While using COUNTIFS(), I was getting wrong data(After using any functions, I always double check through filtering data and count raws, whether my results comes same or different) It took my more time to reach to the concluision that, "I had missed some information". But Learned many new things, While analyzing these whole data.
   
   (For Louise, There are no visible and evident or reasons why only some subcategories are popular. I think that should be challenging for her because her estimation was $12,000 for her Play.)
   
## Results

   The most successful category were in Months of May-July and there there are 525 successful theatre Kickstarters in USA. Also, there are only a total of 604 Kickstarter campaigns for plays in Great Britain with the most successfull catagory is in "Theatre" only.
    

- What are two conclusions you can draw about the Outcomes based on Launch Date?
    1. As per my analysis, Theatre catagory has most successful outcomes than other catagories and the least successful was food category.
    2. Month of May-June has more successful outcomes and then it started falling down. 
    
- What can you conclude about the Outcomes based on Goals?

    If we filter for only the United States campaigns, we will find that there were 525 successful theater Kickstarters.

- What are some limitations of this dataset?
   
    I think, in this dataset, there are no defined numbers to check how many people where working on a particular project and might be it contributes to the success or failure of the event.
        

- What are some other possible tables and/or graphs that we could create?

    We can create Box Plots for Outliers,Sub category Outcomes,Find values of mean-median-mode- IQR of goal through Descriptive statistics etc.
    Here, I have added some more tables and graphs:


<img width="714" alt="Screen Shot 2021-10-27 at 9 47 27 AM" src="https://user-images.githubusercontent.com/92277581/139090845-12def7df-946d-4ca8-80a6-b3b204a35739.png">

<img width="1218" alt="Screen Shot 2021-10-27 at 9 48 36 AM" src="https://user-images.githubusercontent.com/92277581/139091022-62900748-c3cc-491d-a5cf-003d01af6cab.png">
<img width="276" alt="Screen Shot 2021-10-27 at 9 49 08 AM" src="https://user-images.githubusercontent.com/92277581/139091078-df912260-eff3-4435-a1b7-8a6ca028ad31.png">
<img width="1086" alt="Screen Shot 2021-10-27 at 9 32 40 AM" src="https://user-images.githubusercontent.com/92277581/139091146-b1b97ad5-9501-484e-ad93-76065d716199.png">





<img width="770" alt="Screen Shot 2021-10-27 at 9 33 16 AM" src="https://user-images.githubusercontent.com/92277581/139091112-5dc41813-3bbf-49f9-b4e2-2c55b4a6bfd0.png">



