# School_District_Analysis: Module 4 Challenge

The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked me to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. A variety of metrics were re-run and compared against the original data to determine the effect that removing the Grade 9 Thomas High School students had. 

# Results

The data analysis was run twice: the first time with all data included, the second time with Thomas' 9th grade students removed. 

## Overall district metrics

The overall district scores changed slightly with the removal of 461 grade 9 Thomas High School students.  The seven major metric changes are: 
 - The grade 9 Thomas students were rmeoved from the analysis thus dropping the student count.  In reality, these students are still registered at Thomas!
 - School budgets stayed the same
 - Math score dropped 0.1% when Thomas grade 9 students were removed
 - Reading score stayed the same with Thomas grade 9 were removed
 - % passing math dropped from 75.0 to 74.8% when Thomas grade 9 was removed
 - % passing reading dropped 0.1% when Thomas grade 9 was removed
 - The overall passing rate dropped from 65.2% to 64.8% when Thomas grade 9 was removed


All data: 

![district_WT](https://github.com/JaniceBgithub/School_District_Analysis/blob/master/Resources/district_WT.png)

With Thomas grade 9 removed: 

![district_NT](https://github.com/JaniceBgithub/School_District_Analysis/blob/master/Resources/district_NT.png)

## Top Schools in district

The order of the top schools in the district changed when the grade 9 Thomas High School Students were removed. 

Top Schools with Thomas grade 9 info  (90.9% overall passing rate):

![Top_schools_WT](https://github.com/JaniceBgithub/School_District_Analysis/blob/master/Resources/top_school_WT.png)

Top Schools with Thomas Grade 9 removed (90.6% overall passing rate): 

![Top_school_NT](https://github.com/JaniceBgithub/School_District_Analysis/blob/master/Resources/top_school_NT.png)

## Bottom Schools in district

There were no changes to the bottom schools in the district

![Bottom_schools](https://github.com/JaniceBgithub/School_District_Analysis/blob/master/Resources/bottom_school_NT.png)

## Math Scores with Thomas Grade 9 removed

The math scores by grade are:

![math_grade](https://github.com/JaniceBgithub/School_District_Analysis/blob/master/Resources/math_scores_grade_NT.png)

## Reading Scores with Thomas Grade 9 removed
![reading_grade](https://github.com/JaniceBgithub/School_District_Analysis/blob/master/Resources/reading_scores_grade_NT.png)

## Results by school 

With Thomas grade 9 data included:

![School_WT](https://github.com/JaniceBgithub/School_District_Analysis/blob/master/Resources/per_school_WT.png)

Without Thomas grade 9 data: 

![School_NT](https://github.com/JaniceBgithub/School_District_Analysis/blob/master/Resources/per_school_NT.png)


## Results by spending

The results by spending did not noticeably change with removal of Thomas grade 9 students:

![spending_WT](https://github.com/JaniceBgithub/School_District_Analysis/blob/master/Resources/spending_summary_WT.png)

## Results by school size

The results by school size did not change with removal of Thomas Grade 9 students

![size](https://github.com/JaniceBgithub/School_District_Analysis/blob/master/Resources/school_size_NT.png)

## Results by school type

The results by school type changed slightly for the charter school (of which Thomas is a part of)

With Thomas grade 9:

![type_WT](https://github.com/JaniceBgithub/School_District_Analysis/blob/master/Resources/school_type_WT.png)

Without Thomas grade 9:

![Type_NT](https://github.com/JaniceBgithub/School_District_Analysis/blob/master/Resources/school_type_NT.png)


# Summary

The four main things that changed when Thomas High School Grade 9 was removed include: 
 1. Math score dropped 0.1% when Thomas grade 9 students were removed
 2. % passing math dropped from 75.0 to 74.8% when Thomas grade 9 was removed
 3. % passing reading dropped 0.1% when Thomas grade 9 was removed
 4. The overall passing rate dropped from 65.2% to 64.8% when Thomas grade 9 was removed



