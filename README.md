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
  - As demonstrated in the two tables above, adjusting the analysis by removing potentially invalid results, has altered the district results for Average test scores as well as for passing percentages.
## School Summary
- School Summary without adjusting for tampered grades
![SchoolAnalysisOriginal](https://github.com/conpm/School_District_Analysis/blob/main/Resources/SchoolAnalysisOriginal.PNG)
- School Summary with adjustments
![SchoolAnalysisAdjusted](https://github.com/conpm/School_District_Analysis/blob/main/Resources/SchoolAnalysisAdjusted.PNG)
  - From these two dataframes based on school, we can see that there is a minimal change in the data from Thomas High School where the tampered grades were from.  Aside from that, there is no changes in the other data within the dataframe.  The reason that the difference is so minor is because the 
- Additionally, since these dataframes are in decending order of Overall Passing percentage, we can also see that there is no change 
