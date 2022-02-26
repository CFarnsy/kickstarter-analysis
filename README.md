‘Kickstarter Campaign Analysis:

# Kickstarter Campaign Analysis

## This is an analysis of Kickstarter campaigns and their successes or failures with respect to their fundraising goals and launch dates.  
###The fundraising goal for Louise’s play was close to being reached within a short timeframe.  Louise is wondering how the other Kickstarter campaigns fared.  The purpose of this analysis is to review the Kickstarter campaigns based on their launch dates and funding goals

## Analysis

### The analysis of the campaigns based on launch dates was completed by reviewing information on whether the theater campaign was successful, failed, or cancelled.  The other piece of information used in the analysis was the month the campaign was launched. The DATE conversion functionality was used to convert the launch dates into one that could be easily understood just by looking at it.  Then the YEAR functionality was used to extract the launch year from the launch date.  Next a pivot table was used to compile the necessary data by populating the outcomes in the columns and the converted launch date in rows.  The campaign ID was used to count the number of successful, failed, and cancelled campaigns.  The parent category was used as a filter to limit the data to just theater campaigns.  The following chart is the result of the analysis:

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/99366022/155856382-819d13d1-1a58-4df3-ba78-f31d01be88c5.png)

### The analysis of the campaigns based on the outcomes of the goals was completed by reviewing information on the number and percent of successful, failed, or cancelled plays in twelve different ranges of monetary values.  The COUNTIFs function was used to count the number of campaigns that were successful in each of the twelve monetary ranges.  This step was repeated for the failed and cancelled plays.  The number of plays for each monetary range were totaled using the SUM function.  Then the percentage of successful, failed, and cancelled plays in each of the twelve monetary ranges were calculated by dividing the number of total plays by the number of plays in each of the outcomes.  The following chart is the result of the analysis:
 
 ![Outcomes_vs_Goals](https://user-images.githubusercontent.com/99366022/155856388-435e88cb-c2a2-460d-aa82-98d47a54352a.png)

## Challenges and Difficulties

###One challenge that could occur is when the launch date is being converted.  If the wrong formula is used, then the date could be inaccurate resulting in the results being skewed.  The other area to keep an eye on are the filters that are applied either in the primary data and in the pivot table.  A wrong filter in either area could result in inaccurate results.

###Another challenge that could occur when using the COUNTIFS functionality is double counting the information if the criteria isn’t entered correctly.  This functionality uses multiple criteria to identify and determine if the information should be included in the calculation.  If any of the criteria is wrong, it could result in the information being double-counted or left out altogether which in turn could result in an incorrect analysis. Make sure you review the results to verify the information makes sense.  If it doesn’t then investigate until the error is identified and corrected. 

## Results

###The first conclusion from the analysis of the outcomes of the theater campaigns based on the launch date found that overall, there were more successful campaigns than failed and cancelled campaigns.  The second conclusion is that the most successful launch months for theater campaigns are May and June.  

###The analysis of the outcomes of the theater plays based on the goals found that plays with a fundraising goal of less than five thousand are about three times more successful than failed.  Campaigns with a goal between five thousand and twenty-five thousand have a fifty-fifty chance of succeeding or failing.  However, campaigns with a goal of twenty-five thousand or more have a significantly higher chance of failing than succeeding except goals between thirty-five and forty-five thousand.  Campaigns with a goal between thirty-five and forty-five thousand, has a chance of succeeding two times more than failing.  It is also interesting to note there were no campaigns at any funding level that were cancelled, each campaign either succeeded or failed.  

###One of the limitations of this dataset is that we don’t what method was used to fundraise.  The method used to fundraise could be a significantly contributing factor on whether the campaign was successful or not.  Another limitation of the data set is details about the backers.  This also could be a significant contributing factor for a successful campaign, especially if a backer is well known and well connected. 

###Another graph that could have been created to help with the analysis is a year over year comparison of campaigns based on launch dates.  This data would have shown there was an explosive growth in theater campaigns overall in 2014 as well as a higher number of successful campaigns.

###A table calculating the mean, median, standard deviation, upper and lower quartile, and the IQR of the fundraising goals might have also been beneficial in analyzing the data more thoroughly.
