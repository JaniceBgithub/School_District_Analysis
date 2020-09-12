# School_District_Analysis: Module 4 Challenge

The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

# Results

The data analysis was run twice: the first time with all data included, the second time with Thomas' 9th grade students removed. 

## Overall district scores

The overall district scores changed slightly with the removal of 461 grade 9 Thomas High School students.  Most scores dropped by 0.1 to 0.3% with the exception of the reading score which stayed the same.  

All data: 

![district_WT](https://github.com/JaniceBgithub/School_District_Analysis/blob/master/Resources/district_WT.png)

With Thomas grade 9 removed: 

![district_NT](https://github.com/JaniceBgithub/School_District_Analysis/blob/master/Resources/district_NT.png)

## Top Schools in District

The order of the top schools in the district changed when the grade 9 Thomas High School Students were removed. 

Top Schools with Thomas grade 9 info  (90.9% overall passing rate):

![Top_schools_WT](https://github.com/JaniceBgithub/School_District_Analysis/blob/master/Resources/top_school_WT.png)

Top Schools with Thomas Grade 9 removed (90.6% overall passing rate): 

![Top_school_NT](https://github.com/JaniceBgithub/School_District_Analysis/blob/master/Resources/top_school_NT.png)

## Bottom Schools in District

There were no changes to the bottom schools in the district

![Bottom_schools](https://github.com/JaniceBgithub/School_District_Analysis/blob/master/Resources/bottom_school_NT.png)

## Math Scores with Thomas Grade 9 removed

The math scores by grade are:

![math_grade](https://github.com/JaniceBgithub/School_District_Analysis/blob/master/Resources/math_scores_grade_NT.png)

## Reading Scores with Thomas Grade 9 removed
![reading_grade](https://github.com/JaniceBgithub/School_District_Analysis/blob/master/Resources/reading_scores_grade_NT.png)

## Results by School 

With Thomas grade 9 data included:

![School_WT](https://github.com/JaniceBgithub/School_District_Analysis/blob/master/Resources/per_school_WT.png)

Without Thomas grade 9 data: 

![School_NT](https://github.com/JaniceBgithub/School_District_Analysis/blob/master/Resources/per_school_NT.png)


## Results by spending

Thomas high school is in the lowest spending bucket so removal of grade 9 information made some very small changes in this bucket.  No other buckets changed.

Spending with Thomas high school:

![spending_WT](https://github.com/JaniceBgithub/School_District_Analysis/blob/master/Resources/spending_summary_WT.png)

Spending without Thomas high school: 

![Spending_NT](https://github.com/JaniceBgithub/School_District_Analysis/blob/master/Resources/spending_summary_NT.png)







