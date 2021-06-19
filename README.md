# Excel-kickstarter-analysis
# Kickstarting with Excel

## Overview of Project

-Purpose

	The purpose of this analysis was to evaluate the outcomes for the theater category based on the date of the launch and the outcomes based on the goals set prior to the events. The collection data and outcomes were displayed through the use of pivot tables, filtering, different Excel functions and line graphs.


## Analysis and Challenges/ Challenges and Difficulties Encountered

 -Analysis of Outcomes Based on Launch Date

	For the outcomes of the theater category, I used a pivot table to extract the exact data I wanted to use. The outcomes were filtered to " successful, failed, canceled'" and the parent category was filtered to "theater". This gave me the number of outcomes based on the launch date for the theater category. I utilized the line graph to display the results that were found through the pivot table.I found this part of the analysis easy with no problems, however, I can see that people can have issues filtering and using the correct information for the rows and columns. 
  
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/85713532/122634853-b422d280-d0ae-11eb-84b1-e79e1432ce17.png)

-Analysis of Outcomes Based on Goals

	For the outcomes based on the goals set, I began a new sheet and I used the COUNTIFS function to pull the data that was necessary for this analysis. The different criteria for the COUNTIFS function was the different goal numbers, the different outcomes and the subcategory of plays. To calculate the total projects , I added all of the different outcomes that were collected. For the percentages, I divided the total projects from the successful, failed and canceled outcomes separately. Once that was completed, I used the number option on the Home tab to change the decimals to percentages. I then used the line graph to display the percentages of outcomes based on the goals. I found difficulty with the COUNTIFS function because the criteria function "successful " was not working and my result for the entire equation was 0. However, I removed a space from inside the quotation marks and it began to work miraculously.
  
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/85713532/122634855-b5ec9600-d0ae-11eb-9636-3396894534f3.png)
		
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

	One conclusion that we can draw from the outcomes based on the launch dates that the most success in revenue takes place during the warmer months of the year (May, June, July, August). Another conclusion that can be drawn from the outcomes based on the launch dates is that the percentage of successful shows to canceled/failed shows during the colder months are higher than the warmer months. The amount of cancellation in the month of January almost doubles any other month in the year. Based on this data, launch dates seem to be more successful if planned during the warmer months of the year.
	

- What can you conclude about the Outcomes based on Goals?

	A conclusion that we can draw from the outcomes based on goals data is that when the goals are set for less than five thousand dollars, the rate of percentage success is the highest and percentage failed is lowest. We can assume that this is where plays can have the most success when it comes to goals.
	

- What are some limitations of this dataset?

	One limitation I noticed is that many of the pledged numbers that are usually successful are slightly over the goal numbers. I believe that inflating pledged numbers could be an issue in this data collection because "successful" plays will promote future shows and even the casting for these plays. I believe this could be a limitation in this dataset.
	

- What are some other possible tables and/or graphs that we could create?

	For the outcomes based on the goals set, a stacked bar graph could be used to show the difference in percentages between success and failure.
  
![Outcomes_vs_Goals2](https://user-images.githubusercontent.com/85713532/122634887-dcaacc80-d0ae-11eb-85aa-e512f1b02f73.png)
