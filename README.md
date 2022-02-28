# kickstarter-analysis


### **Project Overview**

Louise’s recent play, Fever came close to its fundraising goal.  While almost successful, it fell short of the original raise goal of $2885.00 by a marginal gap of $40.00.  For this project, we’ll dive into fundraising data from 2010-2017 to help her understand how campaigns generally perform relative to their launch dates and funding goals, specifically focusing on theater category and then zooming in on plays subcatgory. In addition, we will help Louise uncover other trends that she can leverage to optimize for successful fundraisings in the future.


### **Analysis and Challenges:**

We will utilize Excel as the main tool to sensitize the raw data, add additional data reference points as well as adding visualizations such as charts, graphs, pivot tables to spot relevant trends.


As a pretext, “Theater” is a parent category which includes plays, musicals, and spaces subcategories -  and now keeping in mind that Louise’s Fever is a play as we will deep dive into “plays” specific analyses later.

**Insights: Theater Outcomes by Launch Date**
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/100495799/155916423-94f91ff4-d268-4a5d-a2b6-7a4c40297b75.png)

What does this line graph tell us?

1. **May** has the highest volume of overall launches and therefore the highest volume of successful launches. 
2. **December** has the lowest volume of theater launches.
3. Generally, the cancellation rates do not vary widely month to month.

**Insights: Play Outcomes based on $ Goals**
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/100495799/155916794-01f2d49d-9964-4c5a-a4fb-61817b691db2.png)

What does this line graph tell us?

1. This specific analysis zooms in on the “Play” subcategory - comparing play outcome vs goal via this line graph.
2. Regardless of the $ goal range (x-axis), 0% of plays get canceled, represented by the red data line at the bottom of the chart.
3. Overall, Louise has an average success rate of 53% across all goal ranges.
4. Fever’s play goal was in the “1000 to 4999” range, which has a 73% historical rate of success, though this particular play landed in the 27% failed category respectively.  We’ll dive into potentially what other factors could potentially change the outcome in the recommendation section below.

## Additional Analyses & Trends

## Recommendations

The detailed analysis quite clearly tell us that if Louis wants to optimize for the most successful outcome for her future campaigns, the recommendations are as follows:

1. **Getting Spotlight:** Of the 839 theater shows selected, 100% of the shows have successful outcomes, regardless of launch date!  This means getting a spotlight endorsement will guarantee her success. Interestingly, if we look at spotlights on all parent categories, the success rate decreases to 87%. The 100% success rate is applicable to theaters and plays specifically.  Louise should leverage this finding. AND/OR (ideally both)
 -- Of the total theater shows not spotlighted, 0% were successful (regardless of launch date); 


2. **Getting Staff Pick:** Of the 132 theater shows selected, 91% of the shows have successful outcomes compared to the 719 not picked by staff, only 58% were successful.

3. Relative to the volume of plays launched each month, the data suggests _September, October, and December being the least optimal_ with % success rates being the lowest out of the twelve (12) months.  Louise should refrain from launching shows during these months until there are further data on the cause(s) for seasonality.  Success for other months are marginally different compared month to month.

![Theater Outcomes by Month](https://user-images.githubusercontent.com/100495799/155918391-790e70e1-c23e-4d3f-8e7f-9e7c58ccffda.png)




## Data Limitations & Challenges

- The data set spans from 2010-2017, however an overwhelming 96% of the data (1,312/1,369 data points) in the theater category represents fundraisings from 2014-to 2016.
- What causes seasonality in volume of launches month to month is inconclusive based on the data set.
- Lack of data on donors, which can help answer the questions like: Are there repeated donors?  If so, are there specific donors Louise should target who are particularly interested in supporting theaters and plays? Can we target the donors with the highest aggregate donations?
- The data set contains fundraising in multiple countries, although largely repensented by US data. We are operating under the assumption Louise understand overall success/fail rates is heavily indexed for _overall_ success of outcomes in all countries.
- Genre of the plays could be a factor in determining the success rate, though no data on genre is available in the data set.

