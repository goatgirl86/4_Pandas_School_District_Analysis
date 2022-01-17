# School_District_Analysis

## Project Overview

### Purpose
The purpose of this week’s assignment was to explore the capabilities Pandas by analyzing school district data.    

### Data Analyzed
The specific dataset analyzed included school performance data from fifteen different schools, including their school type, school size, school budget, average math and reading school, and overall passing grades. Throughout our weekly modules, we began analyzing the data for all schools.  For this challenge, we expanded our analysis by nullifying ‘bad data’ and rerunning our previous analyses.  

### Deliverables
The deliverables for this assignment were:
1)	Remove grade data for 9th graders at Thomas High School that had reportedly been “altered”.
2)	Recalculate our school district analysis with the corrected data.  

## Results 
- How is the district summary affected?
  -	After replacing 9th grade scores with NaN, outputs on the District Summary for “Average Math Score”, “Percent Passing Math”, “Percent Passing Reading”, and “Percent Overall Passing” decreased slightly (see Screenshot #1…original data on top, new/corrected data on bottom).
	 
-	How is the school summary affected?
  -	The only change in the in the School Summary was that Thomas High School’s values decreased slightly due to the fact that the 9th graders falsified ‘good’ grades were removed from the dataset (see Screenshot #2…original data on top, new/corrected data on bottom).
 
-	How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  -	Replacing the ninth graders’ scores does not affect Thomas High School’s overall performance relative to other schools.  Thomas remains #2 in the top five ranking schools (see Screenshot #3…original data on top, new/corrected data on bottom).
 
-	How does replacing the ninth-grade scores affect the following:
  -	Math and reading scores by grade: Math and reading scores for ninth grade at Thomas High School are now “NaN” (Screenshot #4 depicts math scores by grade). 
  - I also did an “extra analysis of 9th grade math/reading schools by school size, type, and spending” for comparison purposes. Values for “Medium” school size, “Charter” type of school, and Spending in the range of “$630-644” decreased (see Screenshot #5)
 
 -	Scores by school spending, size, and type: Depending on rounding and formatting, the scores for all three of these variables may or may not “change”.  If you do not round to one decimal, then you will see that the values do in fact differ.  However, when you round to one decimal point, the results show no difference.  This is because Thomas’ affect on the average is so minimal that the replacement of ninth grade test scores does not significantly  impact the overall result (Screenshots # 6 and 7 shows the slight variation between the second decimal places on the “$630-644” rows……original data on top, new/corrected data on bottom
 
 

## Summary
### 4 Changes after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs
1)	Outputs on the District Summary for “Average Math Score”, “Percent Passing Math”, “Percent Passing Reading”, and “Percent Overall Passing” decreased slightly.
2)	Grade Level data by School for math and reading show no values for Thomas High School’s 9th Grade
3)	If Thomas High School’s student count regarding “passing” grades is not corrected by only using a total student count of only grades 10-12, then Thomas High School’s grades are much lower. Screenshot # 8… top shot is % passing based on all Thomas students (9-12).  Bottom shot is % passing based on a student count of only 10th-12th graders.  
4)	When comparing 9th grade math/reading schools by school size, type, and spending values for “Medium” school size, “Charter” type of school, and Spending in the range of “$630-644” decreased (see Screenshot #5 above).



