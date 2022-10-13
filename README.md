# Kickstarting with Excel

## Overview of Project

### The purpose of [this project](https://github.com/Ctblossey/Kickstarter-analysis) is to lay out different aspects of the Kickstarter challenge such as name, blurb, goal, pledge, etc. From here, we have a concrete way of keeping track of progress and making predictions. It is important to have a clean layout of all the data in order to make assumptions about which ones are successful and which are not. We have 4113 projects across several different categories and subcategories.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
     
- ### Based on the [data](https://github.com/Ctblossey/Kickstarter-analysis/blob/main/Kickstarter_Challenge.xlsx.zip) we have, we are able to take a deep dive into the outcomes we have based on Launch Date. The analysis is comprised of a distribution of outcome types corresponding to their Launch Date months, specifically for the theater parent category. In addition to the breakdown of results, our visualizations provide the ability to filter on both parent category and years. Having this ability provides an extra level of detail, as we can compare results across different criteria.
    
- ![](https://github.com/Ctblossey/Kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)
    
- [Theater Outcomes vs Launch Date](https://github.com/Ctblossey/Kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals

- ### One of the main areas of focus for these [Kickstarters](https://github.com/Ctblossey/Kickstarter-analysis/blob/main/Kickstarter_Challenge.xlsx.zip) were the goals for each individual one. With the analysis of outcomes based on goals, we were able to breakdown certain subcategories based on different goal ranges. For our analysis, we chose to take a look at plays, where we were able to have many takeaways. In doing so, we were able to draw out more realistic points of success, failure, and cancelations.

- ![](https://github.com/Ctblossey/Kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)
    
- [Outcomes vs Goals](https://github.com/Ctblossey/Kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

- ### Although we did not encounter any significant difficulties during our analysis, it is important to acknowledge where fault may occur. Two possible difficulties are yearly differences for launch date outcomes and scope for outcomes based on goals. For the launch date outcomes, there is a chance that certain years weigh heavily on the monthly distribution. To combat this, we added a year filter to double check any meaningful statistical differences. For the outcomes based on goals, it is possibly that our scope is too narrow only being in regard to plays. One way to combat this would be by creating a subcategory key that we could filter on instead of using hard code. 

## Results

- ### Two main conclusions in regard to theater outcomes are that canceled outcomes hold little impact on the results and that successes consistently have more outcomes than failures throughout the year overall.

- ### One conclusion about outcomes based on goals is that the majority of projects have a goal of less than 10,000; where successes outweigh failures overall.

- ### There are several limitations to this data set. One of which being that the goals and pledges can differ in currency. Without creating a central value, there could be statistical error. Another limitation, yet similar, is the difference between countries. It would be important to look at the differences based on all similarities instead of just the main ones like date, goal, and category.

- ### Other visualizations could bring in important context for the data. One of which, like mentioned in the limitations, would be a graph to show the distribution of kickstarters across different countries based on similar criteria, like the goal. Another visualization would be a chart to show the total projects in regard to outcomes based on goals. The largest difference occurs in the 45,000-49,999 range, however, there is only one total project. Finally, an additional table that would help would be a currency conversion table. It is important to show each currency's goals in relation to other currencies.
