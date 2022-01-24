# School District Analysis

## Overview of the school district analysis
The main purpose of the School District Analysis is to help Maria to exclude the information from the 9th grade of Thomas High School from the School Analysis, as they suspected these data has been altered. 

In order to help Maria, we have rewrited the code and replaced the grades from Thomas 9th grade for Math and Readng to NaNs.

## Results

- How is the district summary affected?
The district summary is a collection of data from all schools. The result had a mnimal affectby the changes in the Thomas High School 9th grade.
![district_comparison](/Resources/district_comparison.png)

- How is the school summary affected?
The School summary was mininally afected by the changes in the Thomas High School 9th. 
![school_summary_comparison](/Resources/school_summary_comparison.png)

- How does replacing the ninth graders’ math and reading scores   affect Thomas High School’s performance relative to the other schools?
The replacing didn't change the position of Thomas High School in the Overall performace 
![top5_school_overall](/Resources/top5_school_overall.png)

- How does replacing the ninth-grade scores affect the following:
 - Math and reading scores by grade
 For Thmas, 9th grade, the math and reading scores are NaN, as below:
 ![math_score](/Resources/math_score.png)
 ![reading_score](/Resources/reading_score.png)


 - Scores by school spending
 This summary hasn't been affected by the Thomas High School changes.(left-with Thomas 9th / right-whithot Thomas 9th)
![spending_summary](/Resources/spending_summary.png)

 - Scores by school size
 This summary hasn't been affected by the Thomas High School changes.(left-with Thomas 9th / right-whithot Thomas 9th)
 ![schoolsize_summary](/Resources/schoolsize_summary.png)

 - Scores by school type
 This summary hasn't been affected by the Thomas High School changes.(left-with Thomas 9th / right-whithot Thomas 9th)
 ![schooltype_summary](/Resources/schooltype_summary.png)


## Summary

There are some changes in the School Disctrict Analysis after the replacement of Math and Reading grades to NaNs for Thomas High School. 
One of them is the % Passing Reading rank falls from 93.27 (1st) before the replacement to 93.018 (3rd) without the 9th grade scores.
Also, Thomas High School remains Top 2 of schools when ranked by Overall Passing Percentage, however the % Overall Passing felt from 90.948 to 90.630. It may not seem like much, but it does put Thomas High School closer to the 3rd and 4th ranked schools.
