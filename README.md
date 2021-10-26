# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this analysis is to provide Louise with data insights and visualizations from other campaign outcomes based on launch dates and funding goals to compare against her own campaign.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
![Theater_Outcomes_vs_Launch.png](https://github.com/mjkleineck/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
![Outcomes_vs_Goals.png](https://github.com/mjkleineck/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
The largest challenge was encountered when aggregating and organizing the underlying data table for the graph displaying outcomes based on goals. Errors in the table were first discovered upon double checking the formulas for determining the count of the number of failed campaigns by goal amount. Upon triple checking, it was realized that the data across all subcategories was being displayed, not "plays" only. The formulas were updated to reflect only the "plays" subcategory. Facing these difficulties taught a valuable lesson: to slow down, be more methodical and thorough when creating data tables and graphs from raw data.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
Based on the difference between the volume of successful campaigns and failed campaigns by month, campaigns that begin in May are most likely to be successful, followed by June, then July. Campaigns that begin in December are most likely to fail.

- What can you conclude about the Outcomes based on Goals?
Campaigns that have goals less than $5,000 are more likely to be successful than campaigns with goals of $5,000 or more. Even though campaigns with goals from $35,000 to $45,000 had a success rate of 67%, the sample size is much smaller. Thus, a campaign goal that large is not recommended.

- What are some limitations of this dataset?
The dataset skews towards campaigns with goals of $10,000 or less so the data around larger campaign goals is less reliable. Theater outcomes by launch date is inclusive of all subcategories in the "theater" parent category. This provides directional insight and may not be an accurate representation since theater spaces is included. Another unknown variable is how the campaigns were marketed. It's likely that the campaigns would have all been marketed differently which could impact the campaigns' results.

- What are some other possible tables and/or graphs that we could create?
We have data for campaign launch dates and completion dates. It would be interesting to see how long it took to meet campaign goals by goal amount, and break that down by category and subcategory. With this insight, Louise could benckmark her campaign against others and make a decision to market her campaign more if she's falling short of the benchmark.