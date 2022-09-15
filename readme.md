 ## Overview
 A school district asked for a snapshot of several key metrics by each school campus and by the district level. The main analysis focused on the performance of math and reading scores disaggregated several ways in preparation for a board meeting. However, after the school board reviewed the data, it was determined that the data from Thomas High School's 9th grade class was suspect of cheating. The school board asked for the data to be removed and analyzed again for a comparison. 
* In this analysis there are challenging activities for a number of reasons. For one, these activities will require you to analyze thousands of records. Hacking through the data to look for obvious trends in Excel is just not a feasible option. The size of the data may seem daunting, but pandas will allow you to efficiently parse through it.

* The mean for the math_score drop down.
* In overall Mathew thomas of grade 10 of school Dixon High School scored lowest in reading_score.
* The calculation of sort_values using count and groupby was challenging for me.
## Summary
* Overall the conclusion is:
* Utilizing NaN is an effective way to capture inconsistencies in a dataset, without skewing the data by having to enter zeros in place of the inconsistency.
* School spending ranges per student do not impact math and reading scores.
* School size has an impact on testing scores. The larger the school size, the lower the test scores.
* Charter Schools performance is stronger than those of Public Schools, as they have higher testing scores.