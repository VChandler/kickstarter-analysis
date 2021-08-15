# Kickstarting with Excel

## Overview of Project
This project is to show how different Kickstarter campaigns fared in relation to their launch dates and funding goals.

### Purpose
Create recommendations for future kickstarter theater campaigns.

## Analysis and Challenges
The analysis was conducted based on Kickstarter data available from 2009 to 2017.  A total of 4,114 projects were available, though
analysis focused on a subset of projects related to theater and plays, as outlined below.  The data was readily available and no
additional data sources were necessary.

### Analysis of Outcomes Based on Launch Date
In examining data for the parent category "theater," a total of 1,369 projects were identified for further analysis.  Of these projects,
there is a clear trend for successful projects to be launched in the May-July timeframe.![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/88070999/129493332-2a5b83c8-5c32-46db-ae72-b75a4585315e.png)
 

### Analysis of Outcomes Based on Goals
A total of 1,046 projects were identified with a "plays" subcategory.  As with the launch data analysis, these spanned 2010 to 2017 projects.  Of these, the vast majority had goals under $10,000.  As anticipated,lower goal amounts were more likely to be successful, as larger projects are much more difficult to push over the finish line.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/88070999/129493336-3a231421-a93f-4b04-bfec-4c4d7ba7c17d.png)

### Challenges and Difficulties Encountered
Within the "Outcomes Based on Launch Date," data spanned from projects in 2010 to 2017.  While there were no difficulties with the
analysis, there are some limitations to the granularity of datapoints available, as explained further below.

## Results

### Conclusions for Outcomes based on Launch Date
One conclusion is that theater projects launched from May to July seem to have a higher chance of success than other times of the year.
There are more projects during that timeframe, but also a higher percentage of those are successful.  For failed projects, there
appears to be a spike in October, both at an overall level and a percent of all projects.  Finally, overall projects drop fairly
dramatically from November to January.  Though this can be a benefit with fewer projects vying for funding, overall success rate is
relatively low, making a new project launch during that timeframe not ideal.

### Conclusions for Outcomes based on Goals
Projects under $10k and $35k-$45k are the most successful as a percent of projects.  However, the percent of projects can be
deceiving since there are only nine total projects in the $35k-$45k range.  Further, projects vying for $50k or more in goals will
likely end poorly- with 88% of those result in a failure.  Projects under $5000 have the highest overall chance of success.

### Limitations
This dataset has some limitations as to what we can examine. We are unable to see a number of other dimensions that may
impact how we would like to analyze the data- for example, we are unable to see the genre of plays, more exact location data for the
plays (such as regional data), how the projects were marketed both within Kickstarter and externally, etc.  It would also be helpful to
know details about views vs. donors, incentives offered, and many other aspects of the campaigns that could potentially impact the data we
see.

### Additional Work
The relevant theater data used in the analysis spans 2010 to 2017.  Additional analysis/graphs would be needed to see if there are any
year over year trends- especially to compare data from recent years to those that are much older.  There may be some underlying macro 
trends that are hidden in a monthly analysis.

Additionally, further refinement of the data may be necessary to filter out projects involving theater spaces, if it is not relevant
to future project ideas. These data points may skew data and cloud recommendations.
