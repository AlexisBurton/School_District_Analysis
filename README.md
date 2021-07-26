# School District Analysis
## Objective
The purpose of this analysis is to evaluate the performance of schools in the district. We  want to see not only how the students are doing in reading and math, but also if there is any correlation between student scores and school characteristics (i.e. school type, school size, per capita spend rate).

Additionally, after being notified of possible academic dishonesty in an isolated group, we ran parallel analysis to see how the removal of tainted data affected the overall results.

## Results
Overall, the tainted data seems to have had little effect over the results. The changes are summarized below. 
- District Summary<p> 
	The tainted data represented roughly 1% of the total data, so it is little surprise that its removal produced negligible change. Four of the five reporting points did not have enough of a change to be reflected in reporting format, and the one that did change, Average Math Score, only dropped by one tenth of a point. [Original District Analysis  /](Screenshots/Original_District_Analysis.png)      [  Modified District Analysis](Screenshots/Modified_District_Analysis.png)
- School Summary<p>
This is the subcategory where the data removal was most likely to have an effect, given that it accounted for roughly a quarter of the school data. However, we once again see very little movement, with the only reportable change being the Average Reading Score increasing by one tenth of a point.
   [Original Thomas High Summary  /](Screenshots/Original_THS_School_Analysis.png)      [  Modified Thomas High Summary](Screenshots/Modified_THS_School_Analysis.png)
- Relative Performance<p>
The small changes in scores did not affect the overall school ranking. Thomas High remains the 2nd best performing school in the district. 
- Null Replacement
	- Math and Reading Scores by Grade<p>
		Since the tainted data was limited to a single grade in a single school, the only only change seen was that no data provided for 9th grade at Thomas High. 
	- Scores by School Spending<p>
		There was no reportable change in scores by school spending when using the modified data.<p>[Original Scores by School Spending   /](Screenshots/Original_Scores_By_Spending.png)  [  Modified Scores by School Spending](Screenshots/Modified_Scores_By_Spending.png)
	- Scores by School Size<p>
		There was no reportable change in scores by school size when using the modified data.
	- Scores by School Type<p>
		There was no reportable change in scores by school type.
## Summary
