# Py City Schools Analysis

## Overview of Project

Maria, the chief data scientist for the school district, and I worked together to conduct an analysis of the recent high school standardized math and reading testing.  

The purpose of the project was to analyze test performance and consider various factors that could potentially impact performance.  Our analysis includes reporting at the district level, school level, and grade level within each school.  Additionally, we analyzed various factors to help understand the impact upon test performance.  These factors were per student spending, school size, and school type.  This data can provide greater insight to the board of education as they make decisions for the future.

After our initial round of analysis, abnormalities were found in the scores for 9th graders at Thomas High School.  As a result, all scores for those 421 students were removed.  (These students comprise 25.7% of Thomas’s population, and 1.1% of all high schoolers in the district.)  A second round of analysis was preformed and changes in the analysis will be discussed further below.

## Results

### District-level results

- A total of 39,170 district students completed the standardized across the 15 high schools.  The two tables below show the results of the original (top) and updated (bottom) analysis.  

- The average math score dropped 0.1 to 78.9 after the suspect scores were removed.  All other values remained consistent.  
(The top table below shows the initial data.  The second table reflects the updates after removing Thomas High School 9th grade values.)
![District_summary_original](https://user-images.githubusercontent.com/82730954/119282806-a2a9f000-bc00-11eb-9ce2-20bbe5d5f6f6.PNG)
![District_summary_updated](https://user-images.githubusercontent.com/82730954/119282810-a76ea400-bc00-11eb-8716-4a3e88ba0df0.PNG)

### School-level results
 
- The tables below reflect the school-level results.  

- As the data reflect, there are dramatic differences between the performance levels at various schools.  These will be discussed later in this analysis.

- Also shown below are the revised numbers for Thomas High School once the values were removed.  There were slight differences in the average scores and the percent of students passing after removal of these values.

- Since the only values removed for the second analysis were from Thomas High School, data for all other schools remain the same.
![Per_school_summary_original](https://user-images.githubusercontent.com/82730954/119282837-b6555680-bc00-11eb-975f-3e3b617e823d.PNG)

- Update for Thomas High School after removing 9th grade values.
![Per_school_summary_updated](https://user-images.githubusercontent.com/82730954/119282845-bc4b3780-bc00-11eb-8b73-a8ddbb151a78.PNG)

### Top schools

- Cabrera High School had the highest overall passing percentage.  

- Thomas High School remained the second highest school based on overall passing rate.  However, the gap between Thomas and Griffin High School was greatly narrowed after the revised analysis was performed.  

- The tables below provide all values for the top five schools.  (The top chart is the original analysis and the bottom chart reflect the revised analysis.)
![Top_Five_Schools_Original](https://user-images.githubusercontent.com/82730954/119282885-d9800600-bc00-11eb-8a7a-95e2d32e1bde.PNG)
![Top_Five_Schools_Updated](https://user-images.githubusercontent.com/82730954/119282888-dbe26000-bc00-11eb-807e-df019a93d3d1.PNG)

### Math scores by grade

- Besides the obvious missing value for 9th graders at Thomas, there were no other changes to the performance by school and grade level.  The top table below reflect the original analysis followed by the Thomas data after the revision.  (Note: nan = not a number, meaning no numerial data to report on)

![Math_scores_by_grade_original](https://user-images.githubusercontent.com/82730954/119282900-eb61a900-bc00-11eb-8fd2-e0087cbe3522.PNG)

![Math_scores_by_grade_updated](https://user-images.githubusercontent.com/82730954/119282903-eef53000-bc00-11eb-8e9a-a7e4ea014d8f.PNG)

### Reading scores by grade

- Again, the only change was for Thomas High School.  The top table below reflect the original analysis followed by the Thomas data after the revision.  
![Reading_scores_by_grade_original](https://user-images.githubusercontent.com/82730954/119282914-fc121f00-bc00-11eb-81f2-5d089e9bb511.PNG)

![Reading_scores_by_grade_updated](https://user-images.githubusercontent.com/82730954/119282923-003e3c80-bc01-11eb-838c-0014ca53e788.PNG)

### Performance by school spending

- To better understand school performance, the schools were grouped into categories based upon the per student spending.  

- It was surprising to this analyst that the data reveal schools who spend less per student had significantly better performance.  It is suggested that various factors be considered to help explain this difference.  Based upon this investigation, there may be solutions to increase performance and save money.

- The revised analysis did not impact these findings.  (Thomas is in the $630-$644 category.)
![Scores_by_student_spending_original](https://user-images.githubusercontent.com/82730954/119282942-0df3c200-bc01-11eb-95b9-58ef74153dd1.PNG)

### Performance by school size

- Schools were grouped according to the number of students in each school.  

- Overall, the small and medium schools performed significantly better than the large schools.

- There were no differences in the numbers after removing the scores from Thomas (a medium sized high school).
![Scores_by_school_size_original](https://user-images.githubusercontent.com/82730954/119282960-1ba94780-bc01-11eb-8f59-8818ef05357a.PNG)

### Performance by school type

- Schools were also categorized by type to compare performance.  The data reflect that charter schools significantly outperformed district schools.

- Again, there were no changes after removing the Thomas scores.  Thomas is a charter school.
![Scores_by_school_type_original](https://user-images.githubusercontent.com/82730954/119282975-2663dc80-bc01-11eb-8907-330558085523.PNG)

## Summary

After removing the suspect scores for Thomas High School’s 9th graders, most of the data remained consistent from the earlier analysis.  There were minor changes based upon the secondary analysis.

- District wide, the average math score dropped from 79.0 to 78.9.

- Thomas’s average reading score improved from 83.8 to 83.9.

- The percent of Thomas’s students passing reading dropped from 97.3% to 97.0%.

- The percent of Thomas’s students passing overall, dropped from 90.9% to 90.6%.

- One note is that the current analysis of schools by spending, size, and type look at an average of the schools within each category.  Another way to look at the data would be to look at the averages for all students making up each of those categories.  Because the current analysis is averaging averages, it gives larger weight to smaller schools within each category and smaller weight to larger schools.  Looking at the underlying students in each category might provide additional insight that could be helpful to meet the board’s goals.








