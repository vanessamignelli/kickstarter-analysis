# Campaigne Fundraising Analysis

## Overview of Project

### The purpose of this project is to examine how different campaigns perform with relation to their launch dates and funding goals, and identify any trends that may be present within the data.

## Analysis and Challenges

### The first analysis was constructed based on theater outcomes by launch date. To do this, data was gathered and displayed to show the month of the year in which the campaign was launched, and the number of corresponding successes, failures and cancels for each month. This data was consolidated in a pivot table, and filtered to show only the theatre category. It has the additional functionality to filter by year to further breakdown the launch date vs. outcomes analysis. The graph above provides a visualization for the analysis, and trends for successes, failures and cancels can be identified on a monthly basis. 

### The second analysis was constructed based on outcomes by goals. To do this, data was gathered and displayed to show the monetary goal established prior to the launch of the campaign, and the corresponding number of sucesses, failures and cancels based on these initial goals. To appropriately sort this information, the 'COUNTIF' function was used in excel to specify the outcome, goal range and the play subcategory. From there, the percentage of each outcomes by monetary goal could be examined. The graph above provides a visual representation of the findings. 

### Possible challenges that could be considered when putting together this analysis is the ability to properly formulate a 'COUNTIF' statement in excel. Because there are various columns in the dataset, and criteria that must be met to sort the data into their appropriate categories, it is crucial to ensure the formula is correct to decipher accurate results for this analysis.

## Results

- With relation to the outcomes based on launch data, it can be concluded that theatre campaigns that are launched in May and June see the greatest number of successes. However, this can also potentially be attributed to the increase in overall campaigns that are launched within these months, as the percentage of successes is approximately 61%. Additionally, the data reveals that regardless of when a campaign is launched, the number of cancellations remains relatively consistent month over month. This could suggest that cancellations are not impacted by launch date.

- With relation to the outcomes based on goals, it can be concluded that the most successful play campaigns have a goal of anywhere from less than $1000 - $4999. Additionally, the largest portion of play campaignes have a goal of $1000-$4999 and few have a goal over $9999. The percentage of play campaigns that fail are generally greater than 50% once a goal outcome is set to $5000 or higher. 

- Some limitations with regards to the data can include the limited geographical data. The data only provides information with relation to the country, but does not examine province or city, meaning the outcome results might potentially be influenced by the population in certain rural or city areas. Additionally, some information in the dataset like 'spotlight' and staff pick' do not contain any clear descriptors of what the data contained in these columns is referring to, making it difficult to use this information in the analysis. Finally, the goal pledge amounts are listed in different currencies, making it hard to draw accurate assumptions based on these metrics as they are not measured using the same scale. 

- To further the findings of this analysis, graphs examing the outcomes by parent category could be generated, examine the outcomes based on month per year, to see if there are any yearly outliers skewing the data, and the average donation against the number of backers. 
