# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this project was to use the Kickstarter data to determine what would be the best course of action for Louise to take in order for her play Kickstarter to be successful. We did this by identifying what made a Kickstarter successful or a failure which could be used to help make decisions on timing and funding goals. 
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

![Outcomes_Based_On_Launch_Date](https://github.com/StevenKhan3/Kickstarter_Module_1_Challenge/blob/main/Resources/Theater_Outcomes_vs_Launch.png)
For the first visualization, we wanted to look at the status of theater Kickstarters over the course of a year to see if there was an optimal time to start the Kickstarter. We did this by creating a pivot table that filters only the theater data and making the X-axis the different months and quarters of the year. To get the data to go over the span of a year, we need to use the "YEAR()" function to isolate the years from the dates we had in our spreadsheet. When making the table I had a "Blank" category that keep showing up and was also being graphed but was fixed by filtering it out of the outcomes in the graph. Some other problems that could arise are not having pieces of data for certain months, or there is a disproportionate amount of data in certain months that can skew the data. 

### Analysis of Outcomes Based on Goals

![Outcomes_Based_on_Goals](https://github.com/StevenKhan3/Kickstarter_Module_1_Challenge/blob/main/Resources/Outcomes_vs_Goals.png)
For the second visualization, we looked at how the goals for the Kickstarted affected the outcome to find what would be the best range for Louise to set fund raising goals. We did this by first greating a set range of goals that were equally spaced so to put out outcome data into. We the used the "Countif()" funtion to find the data for the successful, failed, and canceled, plays within those ranges. We then found the total number of projects so that we can calculate the outcome percentages using the"Sum()" funtion. We then calculated the percentages by using a simple division funtion and graphed the results for each outcome to display the graph above. 

### Challenges and Difficulties Encountered
Some of the challenges faced when creating these data visualizations were making sure that the functions used, such as the "COUNTIFS()" function was pulling them from the correct rows and collecting all of the data needed but also only collecting data under the criteria that was given. At first, my graph had larger numbers than I had previously estimated and realized that I was pulling data from the entire sheet and not just from the play subcategory like what was intended. During the graphing of the outcomes based on goals, I also found it strange that I was getting 0 values for all of the canceled section which cause me to do some revision on the original Excel sheet to find that there were no canceled plays and that there wasn't an error with my functions. 
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
One conclusion that we can draw is that May has the greatest amount success with play Kickstaters making it an optimal time for Lousie to host her own. Another conclusion that can be draw is that October is the worse time to start a play Kickstarter as it has the highest amount of failed projects. So if Louise can't start her project in May, at the very least she knowns to stay away from an October launch. 
- What can you conclude about the Outcomes based on Goals?
The outcomes based on goals shows us that the best possibilty for success is for Lousie to set her goal somewhere between the 45,000 to 49,000 range as that has the highest amount of success.  
- What are some limitations of this dataset?
This data set has information for all kinds of Kickstarters in different parts of the world however, plays despite being a subcategory still is a broad term that encapsulates many different genres. We also could have more specific regional data because places like Broadway most likely have higher success rates with play Kickstarters versus somewhere like Silicon Valley which would bring more success to Kickstarter in tech. 
- What are some other possible tables and/or graphs that we could create?
You could create a table on how much people pledge to play Kickstarters and how many people pledge to see if you would need to appeal to a wider audience that will most likely donate less money but in higher quantities, or if you should be focusing on a smaller group of that would pay more like a team of investors.
