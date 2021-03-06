# Kickstarting with Excel

## Overview of Project

This project utilizes Microsoft Excel to determine success rate of various kickstarter fundraising campaigns in order to inform decisions for a new venture.

### Purpose

The purpose of this project is to identify how different fundraising campaigns performed based on their respective launch dates and funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

In order to analyze outcomes based on a play's launch date, the YEAR() function was used to extract the year from a given date column. This information along with outcomes, and date created data, was used to generate a pivot table. From this information, a line chart was created to show relationship between launch month and rate of success, failure and cancellation.![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/93743169/146620487-65111927-a111-48bc-84f6-5db1ef9a147f.png)


### Analysis of Outcomes Based on Goals

In order to analyze outcomes based on goals, the COUNTIFS() formulas were utilized to determine number of successful, number of failed, and number of canceled plays for various goal ranges starting from $1,000 to over $50,000. Another line chart was created to show the theater outcomes based on goal amounts.![Outcomes_vs_Goals](https://user-images.githubusercontent.com/93743169/146620506-33a01e6c-582c-408e-9912-65b0b163f30b.png)


### Challenges and Difficulties Encountered

One of the challenges encountered was to ensure formatting of the COUNTIFS() formula is correct. For example, ensuring the quotation marks are in the correct position. Another example is to ensure a '$' is present after the column letter in order for the column to become an absolute reference when the formula is copied to other cells.

## Results

Based on the data analysis, it can be deduced month of **May is the most successful month to launch a play in**, followed by June. **December is the least favorable month** to launch a play campaign.

The most successful outcomes for a play are when it's **goals are set between $1,000 and $4,999 (73%)**, followed by goal range of $35,000-$39,999 (67%), $40,000-$49,999 (67%), and less than $1,000 (67%). 

Some of the limitations of the data used for this analysis are missing data, limited time span in which data was collected (8 years), and global data. For example, a play that was successful in Great Britain may not be successful in the United States.

Although only 2 analyses were run, there are other variations that are possible. For example, a comparison can be run between a play's goal and pledged amount to determine success rate. Another analysis that could be run is to determine which subcategory has the most cancellations. Finally, a table and/or graph can be generated to determine which plays were the most successful to determine genres that can be utilized in future campaigns.

