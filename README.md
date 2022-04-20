# School_District_Analysis
---
# Overview of the School District Analysis
The purpose of this analysis was to show the performance of schools and their students within a school district based on several criteria.  The criteria which were analyzed to compare the schools were; school type, number of students, total school budget, budget per student, average math and reading scores, and percentages of passing students in math, reading and both.  This data is then used to calculate performance for the District as a whole, which is then broken down further into an analysis of each school's performance, and then that is broken down into an analysis of each grade's performance within each school.  After the initial analysis of the data, it was determined that there may have been tampering with the grades of the 9th grade students at one of the schools.  Therefore the analysis was performed again in order to exclude grades which may have been tampered with.  Subsequently, the final results were adjusted to account for the exclusion of those grades.
## Results
### District Summary
- District Summary without adjusting for tampered grades
![DistrictAnalysisOriginal](https://github.com/conpm/School_District_Analysis/blob/main/Resources/DistrictAnalysisOriginal.PNG)
- District Summary with adjustments
![DistrictAnalysisAdjusted](https://github.com/conpm/School_District_Analysis/blob/main/Resources/DistrictAnalysisAdjusted.PNG)
- As demonstrated in the two tables above, adjusting the analysis by removing potentially invalid results, has slightly altered the district results for Average test scores as well as for passing percentages.
### School Summary
- School Summary without adjusting for tampered grades
![SchoolAnalysisOriginal](https://github.com/conpm/School_District_Analysis/blob/main/Resources/SchoolAnalysisOriginal.PNG)
- School Summary with adjustments
![SchoolAnalysisAdjusted](https://github.com/conpm/School_District_Analysis/blob/main/Resources/SchoolAnalysisAdjusted.PNG)
- From these two dataframes based on school, we can see that there is a minor change in the data from Thomas High School where the tampered grades were from.  Aside from that, there is no changes in the other data within the dataframe.  This change represents the difference between the Thomas High School's performance, with and without the 9th grade scores.  If the 9th grade scores, which were adjusted to NaN values, were included in the adjusted calculations, it would greatly skew the data from Thomas High School because those grades would be calculated as zeros.
- Additionally, since these dataframes are in decending order of Overall Passing percentage, we can also see that there is no change in the rankings of the schools from the adjustment.
- In further analysis, the adjustment had negligible differences from the unadjusted data in the following categories.
  - Scores by school spending: spending group "$631-645"
  - Scores by school size: size group "Medium"
  - Scores by school type: school type "Charter"
- In the breakdown of Math and Reading scores by grade, all of the data other than the Math and Reading scores for 9th graders at Thomas High School was uneffected.  The scores for 9th graders at Thomas High School show as NaN values representing that the scores for that group were not calculated due to their potential illegitimacy.
## Summary
By adjusting potentially tampered data from the school district analysis we have seen several changes in the results.  The most significant change is that the passing percentages have gotten slightly lower in all categories for the district summary, as well as for the school summary of Thomas High School.  This shows that the potentially tampered grades from the 9th graders at Thomas High School had a higher average score than the grades from Thomas High School students in grades 10-12 whose grades were not tampered with.  Another easily noticable change in the the school district analysis is that in the summary of math and reading scores by grade, the Thomas High School 9th grade scores now show as NaN.  The last few changes to the school district analysis are much less noticable due to their changes being at a level of precision which was not shown in the final formatted summaries of; scores by school spending, scores by school size, and scores by school type.  In these categories there were very minor changes to the passing percentages for the spending group of "$631-645", the size group of "Medium", and the school type of "Charter".  Since in the summary of these categories, we are only looking at passing percentages to the precision of whole numbers, these changes are negligible to the school district analysis. 
