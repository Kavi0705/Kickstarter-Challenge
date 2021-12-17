# Kickstarting with Excel

## Overview of Project
This project utilizes Microsoft Excel to determine success rate of various kickstarter fundraising campaigns in order to inform decisions for a new venture.

### Purpose
The purpose of this project is to identify how different fundraising campaigns performed based on their respective launch dates and funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
In order to analyze outcomes based on a play's launch date, the YEAR() function was used to extract the year from a given date column. This information alson with outcomes, and date created data, a pivot table was generated. From this information, a line chart was created to show relationship between launch month and rate of sucess, failure and cancellation.(enter link to chart here)

### Analysis of Outcomes Based on Goals
In order to analyze outcomes based on goals, COUNTIFS() were utilized to determine number of successful, number of failed, and number of canceled plays for various goal ranges starting from $1,000 to over $50,000. Another line chart was created to show the theater outcomes based on goal amounts. (enter link to chart here)

### Challenges and Difficulties Encountered
One of the challenges encountered was to ensure formatting of the COUNTIFS() formula is correct. For example, ensuring the quotation marks are in the correct position. Another example is to ensure a '$' is present after the column letter in order for the column to become an absolute reference when the formula is copied to other cells.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
Based on the data analysis, it can be deduced month of May is the most successful month to lauch a play in, followed by June. December is the least favorable month to launch a play campaign.

- What can you conclude about the Outcomes based on Goals?
The most successful outcomes for a play are when it's goals are set between $1,000 and $4,999 (73%), follwed by goal range of $35,000-$39,999 (67%), $40,000-$49,999 (67%), and less than $1,000 (67%). 

- What are some limitations of this dataset?
Some of the limitations of the data used for this analysis is missing data, limited time span in which data was collected (8 years), and global data. For example, a play that was successful in Great Britain may not be successful in the United States.

- What are some other possible tables and/or graphs that we could create?
Although only 2 analyses were run, there are other variations that are possible. For example, a comparison can be run between a play's goal and pledged amount to determine success rate. Another analysis that could be run is to determine which subcategory has the most cancellations. Finally, a table and/or graph can be generated to determine which plays were the most successful to determine genres that can be utilized in future campaigns.

