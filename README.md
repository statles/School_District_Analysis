# School_District_Analysis
Analysis of standardized test scores across one school district

## Overview of the school district analysis: 
The purpose of this analysis was to remove the scores of the ninth graders from Thomas High School due to allegations of academic integrity. The analysis of the school district test scores for math and reading were then rerun to account for this change in data. This change in the scores for Thomas High School Ninth graders lead to a change in district-wide math and reading scores.

## Results: 
Using bulleted lists and images of DataFrames as support, address the following questions.

- How is the district summary affected?
- Removing the Thomas High School ninth graders lead to 461 students being excluded from the school district summary. This had the effect of slightly decreasing the average math score. The percent of students who massed math, reading, and the overall passing percentage all drecreased by 0.1%.
- How is the school summary affected?
- The school summary is affected by greatly decreasing the percent passing for reading and math for Thomas High School. Passing math percentages dropped from 93% to 67%. Passing reading percentages dropped from 97% to 70%. The overall passing rate for Thomas High School dropped from 91% to 65%. However, when we replace the Thomas High School scores with the scores from only 10th through 12th grade, the passing percentages are only decreased by 0.1-0.3% for all scores.
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
- Origianally, Thomas High School was the top two school in terms of overall percentage of students who passed. With the ninth graders math and reading scores dropped, Thomas High School is now at the bottom of all schools in the district for percentage of students who passed reading. It puts Thomas High School near the bottom, but not in the bottom five, for percentage of students who passed math. The school still has a higher average math score (83.4) and a higher average reading score (83.9) than the bottom five schools. However, by replacing the Thomas High School data so that it only includes the 10th through 12th graders, Thomas High School's stading in the top five schools is not affected.
- How does replacing the ninth-grade scores affect the following:
- Math and reading scores by grade
- Now that the Thomas High School ninth graders' grades have been replaced with Nan, all data for reading scores and math scores for 9th grade for Thomas High School is now NaN as well. 10th through 12th grade scores for Thomas High School were not affected.
- Scores by school spending
- 
- Scores by school size
- Scores by school type

## Summary: 
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
