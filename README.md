# School_District_Analysis
Performing analysis on School District data after replacing altered (incorrect) reading and math scores first

## Overview of the school district analysis 

Given two excel spreadsheet data (complete *school data* and complete *student data*; merged the two DataFrames), the goal was to generate a report (high-level snapshot) of the school district summary based on several key metrics: *Total number of students*, *Total number of schools*, *Total budget*, *Average math score*, *Average reading score*, *Percentage of students who passed math*, *Percentage of students who passed reading*, and *Overall passing percentage*. 

The purpose of this analysis was to replace the inaccurate data of (Thomas High School- 9th grade- Reading & Math scores), while keeping the rest of the original data intact. After cleaning up the data (now accurate), we repeated the same school district analysis: 1) *District Summary*, 2) *School Summary*, 3) *Top 5 High & Low Performing Schools*, 4) *Math & Reading Scores by Grade*, 5) *Scores by School Spending (per student)*, 6) *Scores by School Size*, and 7) *Scores by School Type*.


## Results 

### District Summary
* In terms of *Total Schools*, *Total Students*, & *Total Budget*, the number remained exactly the same. The *Average Math Score*, *Average Reading Score*, *% Passing Math*, *% Passing Reading*, and *% Overall Passing* are relatively similar in number (with only a decimal number or so off) compared to the first analysis and second analysis.

### School Summary
Below is a screenshot of the school summary data:

<img width="538" alt="School Summary (module challenge)" src="https://user-images.githubusercontent.com/107021231/177733746-26e79274-2a56-4ffa-808f-cee5d417e052.png">

* In terms of *School Type*, *Total Students*, & *Total School Budget	Per Student Budget*, the number remained exactly the same. As for the *Average Math Score*,	*Average Reading Score*,	*% Passing Math*,	*% Passing Reading*, and *% Overall Passing*, once again the numbers are relatively similar compared to the first and second analysis (with only a decimal number or so off). 


### Thomas High School's performance relative to other schools
* Overall, replacing the ninth graders' math and reading scores did not really affect Thomas High School's *Average Math Score*,	*Average Reading Score*,	*% Passing Math*,	*% Passing Reading*, and *% Overall Passing*. The numbers were not exactly the same on both analysis, but the numbers were relatively similar. On both analysis-- the *Average Math Score* and *Average Reading Score* were around 83; *% Passing Math* and *% Passing Reading* were around 93% & 97% (respectively); and *% Overall Passing* was around 90%.


### Math & Reading Scores by Grade
Below is a screenshot of the reading score by grade:

<img width="152" alt="Reading Score by Grade" src="https://user-images.githubusercontent.com/107021231/177739171-9e1b104b-8d91-4df5-8f8b-9e3dfe106805.png">

* There were no changes to math & reading scores by grade for all schools. The only difference is that the data under "9th Grade" for "Thomas High School" has "nan" instead of a number. 

### Scores by school spending
* According to the two analysis, there were no changes in terms of the scores by school spending.

### Scores by sample size
* According to the two analysis, there were no changes in terms of the scores by sample size. 

#### Scores by school type
* According to the two analysis, there were no changes in terms of the scores by school type as well. 

Overall, since removing the following (Thomas High School-9th grade-Reading & Math scores), is such a small portion of the entire large portion of school district data, most of the data (key metrics of the original analysis) were not drastically altered.


## Summary

### Four changes in the updated school district analysis 

After replacing the reading and math scores for the ninth graders at Thomas High Schoool with NaNs, the four major changes that occurred included mnostly data within the school, Thomas High School, itself. (which makes sense considering that the only data modified was the data at this school). The changes mostly occurred in the following metrics: *average math and reading score*, *% passing math*, and *% passing reading*, and *% overall passing
