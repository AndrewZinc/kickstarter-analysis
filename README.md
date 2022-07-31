# An Analysis of Kickstarter Data Using Excel

## Overview of Project
This project consisted of an analysis of Kickstarter data within an Excel Spreadsheet.  The spreadsheet contained an international collection of Kickstarter campaign data, with details such as:
* The fundraising goal, 
* Amount pledged, 
* Number of backers,
* Categorization of the campaign,
* The timing and duration of the campaign

Using this spreadsheet, an analysis was performed to discover the attributes of a successful Kickstarter campaign

### Purpose
This project was undertaken to provide insights to a Playwright who is interested in using data to build a successful Kickstarter campaign

## Analysis and Challenges
To prepare for the analysis, the contents of the spreadsheet were examined to identify the types of data and ensure they were all properly formatted. Additionally, conditional formatting was introduced to enable easier visual review of the spreadsheet contents regarding the outcome of the Kickstarter campaigns and the percent of funding received for each. ![Conditional Formatting](/Conditional_Formatting.png)

### Analysis of Outcomes Based on Launch Date
Preliminary review of the spreadsheet data suggested that Kickstarter campaigns were launched at different times all through the year.  A Pivot Table was constructed to determine if there was a best time of year to launch a Theatrical Kickstarter campaign. Using the Pivot Table data, a chart was added to visualize the data and its variation over time. ![Theater_Outcomes_vs_Launch Pivot Chart](/Theater_Outcomes_vs_Launch.png)
From this we can see that May is the best month to launch this type of Kickstarter, and December is the worst month.

### Analysis of Outcomes Based on Goals
Lastly, a chart was created to explore whether the size of the Kickstarter goal was a factor toward the success of a Theatrical Play campaign. ![Outcomes_vs_Goals Line Chart](/Outcomes_vs_Goals.png)

The chart was constructed using Excel COUNTIFS formulas for Successful, Failed, and Canceled Play Kickstarters that had goals in various ranges.  Interestingly, we see that there is a perfectly inverse relationship between the success or failure of the campaign, based on its goal.  Within this spreadsheet data set, there were no "Play" Kickstarters that were canceled.

### Challenges and Difficulties Encountered
#### Challenges
There were challenges with the data in the spreadsheet. The data associated with the dates for the start and end of the campaign were both included in Unix Epoch Time.  This data required conversion to make it human-readable.  This was accomplished using a formula '=(((J2/60)/60)/24)+DATE(1970,1,1)', which for example converted 1476094907 to 10/10/2016.
#### Difficulties
The only difficulty encountered was due to the size of the spreadsheet.  The volume of data made filtering and sorting data proceed very slowly on my computer.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
