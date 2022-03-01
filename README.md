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

In additional to the original hypotheses of launch dates vs outcome and $ Goals vs outcome, we also examined a few other relationships.  Two particular relationships that are noteworthy to share here.

1. **Insights: Staff Pick vs Outcome**

When we looked whether a play being staff picked has an impact on the outcome, the chart below clearly points to a much higher chance of success if a show was picked by the staff.  Plays that were staff picked has a 90% success rate (notated by 'TRUE') vs a 63% sucess rate if a play was not staff picked (notated by 'FALSE').  Huge difference, right?

![Staff Picks vs Outcome](https://user-images.githubusercontent.com/100495799/156072780-7fc9f96a-7ef5-4207-a7c4-4aa805f25d13.png)

In addition, in the summary chart below, when a play is marked "staff pick", the average percentage of the fundraising changes from 86% & 88% overall average funding to 106%.  Having the "staff pick" increases both the fundraising outcomes significantly and the odds of success of a play.

_Staff Picks & Funding Outcomes_
<img width="234" alt="Screen Shot 2022-02-28 at 6 02 28 PM" src="https://user-images.githubusercontent.com/100495799/156073175-bed7d393-7ec3-40a5-a3d8-a6eeff4d58ad.png">

2. **Insights: Spotlight vs Outcome**

Even more surprisingly, of the plays selected for a **spotlight**, 100% of these plays were successful despite of the any seasonality that we've seen in the data earlier.

In terms of monetary impact of a spotlight, our data indicates that when a theater show (or play) is endorsed, it will on average an achieve 128% of its goal compared to 12% achievement for those not spotlighted.

<img width="388" alt="image" src="https://user-images.githubusercontent.com/100495799/156080486-664056a7-0404-45cb-8e50-20ab7b1f85ed.png">


Remember the **Theater Outcomes Based on Launch Date** analysis above? All of the successful theater shows were spotlighted.  None of the failed and canceled shows were spotlighted.



## Recommendations

The detailed analysis quite clearly tell us that if Louis wants to optimize for the most successful outcome for her future campaigns, the recommendations are as follows:

1. **Getting Spotlight:** Of the 839 theater shows spotlighted, 100% of this cohort had successful outcomes, regardless of launch date!  This means getting a spotlight endorsement will guarantee Louise success. It is also worth noting that all spotlighted fundraisings across _all categories_ have had successful launches. 

Conversely, of the 530 theater shows not spotlightted, 0% were successful; 
AND/OR (ideally both)

2. **Getting Staff Pick:** Of the 114 theater shows selected, 90% of the shows have successful outcomes compared to the 719 not picked by staff, which shows only 63% being successful outcomes.


3. Relative to the volume of plays launched each month, the data suggests _September, October, and December being the least optimal_ with % success rates being the lowest out of the twelve (12) months.  Louise should refrain from launching shows during these months until there are further data on the cause(s) for seasonality.  Success for other months are marginally different compared month to month.

![Theater Outcomes by Month](https://user-images.githubusercontent.com/100495799/155918391-790e70e1-c23e-4d3f-8e7f-9e7c58ccffda.png)




## Data Limitations & Challenges

- The data set spans from 2010-2017, however an overwhelming 96% of the data (1,312/1,369 data points) in the theater category represents fundraisings from 2014-to 2016.
- What causes seasonality in volume of launches month to month is inconclusive based on the data set.
- Lack of data on donors, which can help answer the questions like: Are there repeated donors?  If so, are there specific donors Louise should target who are particularly interested in supporting theaters and plays? Can we target the donors with the highest aggregate donations?
- The data set contains fundraising in multiple countries, although largely repensented by US data. We are operating under the assumption Louise understand overall success/fail rates is heavily indexed for _overall_ success of outcomes in all countries.
- Genre of the plays could be a factor in determining the success rate, though no data on genre is available in the data set.

