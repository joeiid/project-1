# ![](https://ga-dash.s3.amazonaws.com/production/assets/lo8go-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Standardized Test Analysis

### Problem Statement

---

This project will examine the relationships between ACT and SAT participation in states and regions. Within the last couple of years levels of participation in multiple states have changed with varying legislative desicions. This project will explore trends in SAT and ACT in 2019 and seeks to identify states that have low SAT participation. This will help identify where the College Board can concentrate in raising participation rates for the SAT.


### Data

---

In this project I chose to use 5 diffrent datasets to show the correlation and define the problem stated above. All of these datasets were data from 2019 for the SAT and ACT.

The SAT dataset has 51 rows that represents all 50 states and 5 columns. The 5 columns identify the states, participation rates that shows the total participation of each state, a total score for the Evidence-Base Reading and Writing section and Math section, and the overall score of all sections summed together.

The ACT dataset has 51 rows that represents all 50 states and 3 columns. The 3 columns identify the states, participation rates that shows the total participation of each state, a composite score.

The ACT_Region data set has 51 rows and 2 columns. The rows show all the states and the 2 columns show the participation rates and the region that each states is in(Northeast, Midwest, South, West).

The SAT_Region data set has 51 rows and 2 columns. The rows show all the states and the 2 columns show the participation rates and the region that each states is in(Northeast, Midwest, South, West).


#### Datasets Used:

* [`sat_2019.csv`](./data/sat_2019.csv): 2019 SAT Scores by State ([source](https://blog.prepscholar.com/average-sat-scores-by-state-most-recent))
* [`act_2019.csv`](./data/act_2019.csv): 2019 ACT Scores by State ([source](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows))

#### Data Dictionary 

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**state**|*obj*|2019 ACT/SAT|States in the United States.| 
|**participation_sat**|*float*|2019 SAT|2019 SAT participation rates through all 50 states in the United States.|
|**participation_act**|*float*|2019 ACT|2019 ACT participation rates through all 50 states in the United States.| 
|**composite_score_sat**|*float*|2019 SAT|2019 SAT scores through all 50 states in the United States.| 
|**composite_score_sat**|*float*|2019 ACT|2019 ACT scores through all the 50 states in the United States.| 
|**region**|*obj*|2019 ACT|States seperated by regions.| 


### Analysis

---

There was strong participation in certain states in regard with the region they were in. States that had high participation rates in SAT would have low participation rates in ACT, and high ACT participation rates ment that state would have a low SAT participation rates. 

When the states were divided into regions, the regions was taked from the U.S. Census 
Bureau (https://www2.census.gov/geo/pdfs/maps-data/maps/reference/us_regdiv.pdf), we were able to see that for the SAT the Northeast had a much higher participation greater than 80%, west and south slightly greater than 40%, and the midwest, less than 30%. When we looked at the ACT divided into regions we saw ACT participations high in Midwest with about 70% participation, the south and west over 60% participation, and the less than 20%.

It was difficult to get the most accurate analysis with the data we had because their was many factors that came into play. This did not consider if there was certain cities with higher SAT or ACT within the states and instead took the overall comparison per state. It also does not consider that many states are not requiring the SAT or ACT for entrance into Universities and Colleges.

### Conclusion

---

Overall, we were able to identify a clear trend with participation in states favoriting SAT and other favorting ACT. In every graph we plotted, it seemed that states tend to support one test over the other with no even participation. 
The relationship with the regions was the same as the states, favorting one over the other.
My recommendation for the College Board for increasing SAT participation would be to focus on states and regions with high participation rates in ACT and low participation rates with SAT. These would be states located in the Midwest, South, and West. By focusing in those areas we would be able to prioritize funds into states that could use the increase in participation.