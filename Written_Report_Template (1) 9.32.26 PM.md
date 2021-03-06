# Kickstarting with Excel

## Overview of Project

This project contains a Kickstarter Challenge data that highlights the more specific data based on distinct categories like theatre, goals and dates.

### Purpose

The purpose of this kickstarter Challenge is to show insights to Louise of how the project can show particular results of successful campaigns by using various tools and filters. In addition to this, how the manager can execute it to make better report for future successful campaigns.

## Analysis and Challenges

Two type of Analysis is created under Theatre Outcomes by Launch Date and second is Outcome based on Goals.

### Analysis of Outcomes Based on Launch Date

The main key in this analysis is the 'Parent Category' which is created by filtering the one category  from kickstarter data into two parts and named as parent and sub category. This is necessary to get better and firm results. For this Challenge it was asked to filter the parent category 'theatre' based on months for each campaign. To complete this, pivot table was created by selecting all data and filter parent category and years to months. the table shows that under Theatre category the number of successful campaign is 839 which is highest among all. To visualize this a line chart with marks created that shows in month May and Jun is the highest peak to 111 and 100.


### Analysis of Outcomes Based on Goals

This analysis has major role play by subcategory 'plays' and 'goals' ranges. The ranges was given in deliverable section. The focus is to analyze the number and percentage of successful, failed and cancelled campaigns based on goal ranges. For this, I used Countifs and sum formula in excel and derived total outcomes to get the percentage results. In the chart display, the only the percentage of successful and failed outcome is displayed by using subcategory of 'plays'. This also shows that percentage of cancelled under plays was 0 in all ranges resulting 0 display as compare the other two. The outcome of successful lies in 40000 TO 45999 IS 100% where as for failed lies in 45000 to 49999.

### Challenges and Difficulties Encountered

The most challenging part in using formula of coutifs as the data is quite big and numeric value are always changing if you are using filter in column of goals, pledged or outcomes. So, it is very necessary that you column and rows have same and correlate data to original sheet and no filters have been used while using counties formula, else the number and outcome of chart will be different. It is best to use fresh sheet and not the sheet that we were changing and practicing excel formulas.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

The two outcomes are as follows:
1- May and June are the best time to start campaign for Theatre as if we total of those two months it will be 211 which gives 25.1% of outcome as compare to other outcome total 319 which results only 23.3%.
2- October to December are the least favourable months for theatre based campaigns as it results only
 156 which is 18.6% of successful campaign and other has 20.3% in total.

- What can you conclude about the Outcomes based on Goals?

The number of successful outcome based on goals lies in range under $5000 which is 75.81% as compare to the 100%v result I received in range $45000 to $49999 but only has 2 successful campaigns.

- What are some limitations of this dataset?

The conclusion we get from outcome of goals is there a filter that we used only plays from sub category which resulted very less in total as compare to other sub categories. Some of the ranges did not have even 1 dollar amount under this category which makes us wonder if the date reflect is skewed or not.
Another is the comparison of the goals range under same category can provide all the information for kickstarter in future or just to pick another in order to raise money.

- What are some other possible tables and/or graphs that we could create?

If we can create the outcomes based on pledge and can use more than one category like television to analyze the information that can use to kickstart the campaign more successful in future.
