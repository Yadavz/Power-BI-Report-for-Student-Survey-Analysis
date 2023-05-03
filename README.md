# Power BI Report for Student Survey Analysis

## Project Overview

The objective of this project is to analyze the student survey data to extract meaningful insights by creating a Power BI report. The data set consists of information about the amount spent by students on different types of purchases like video games, indoor games, toys, books, and gadgets. The data set also includes the store setting column that explains the type of location in which the store is present. The report includes tabular visualization, matrix visualization, funnel chart, pie chart, scatter plot, sand dance plot, and Q&A feature of Power BI. 

## Report Details

1.	Tabular Visualization: The tabular visualization displays the total amount of purchase (TAP) based on ‘Store location’ and ‘Store setting’. The records are formatted based on the amount spent as follows: 

-	If 0<TAP<35000, then records should be in red colour
-	If 35000<=TAP<60000, then records should be in yellow colour
-	If TAP>=60000, then records should be in Blue colour

2.	Matrix Visualization: The matrix visualization displays the amount spent on outdoor sports across different ages and ‘Store setting’. The amount spent in total outdoor sports is colour-formatted.

3.	Funnel Chart: The funnel chart displays the total amount of purchase by ‘Store setting’. The data labels are shown as Percentage of First.

4.	Pie Chart: The pie chart displays the total amount of purchase by different ‘Store location’ for Suburban ‘Store setting’ only. The filter context is used to achieve this.

5.	Scatter Plot: The scatter plot displays the relationship between Video games purchase and Outdoor sports spent across different ages.

6.	Sand Dance Plot: The sand dance plot displays the relationship between Indoor sports and Video games spent across different age groups.

7.	Data Access Restriction: The data access is restricted for the given users in the User mapping table. For example, Mani deals with Rural area only, so she can view the data which belongs to Rural only, not urban and suburban data.

8.	Report Publishing and Dashboard Design: The report is published on Power BI cloud service, and a Master Dashboard is designed consisting of a funnel chart and scatter plots. The dashboard is scheduled for a refresh six times in every 4 hours for the Dashboard in a day.

9.	Q&A Feature of Power BI: The Q&A feature of Power BI is used to show the average age of students and a donut chart for the total amount of purchases by ‘Store location’.

## Conclusion

This Power BI report provides insights into the student survey data by using various visualization techniques. The report highlights the relationship between different types of purchases and the store settings. The report also provides data access restriction for different users and a Q&A feature to answer specific questions.

## Installation

7.	Clone or download the repository.
8.	Open the Power BI project file (.pbix) with Power BI Desktop.
9.	Make sure you have the necessary data sources and credentials to access them.


## Usage

9.	Open the Power BI project file (.pbix) with Power BI Desktop.
10.	Refresh the data sources if necessary.
11.	Use the slicers and filters to interact with the visualizations and explore the data.
12.	Export the visualizations to different formats if necessary.
