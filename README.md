# School_District_Analysis

## Project Overview
A school board has given the following tasks to complete the analysis of student data in the PyCities School District across all students in grade levels 9 through 12 and all schools. The validity of a subset of the data was determined to be in question and a separate analysis requested with the potentially erroneous subset of data removed. Once complete for both the results are to be reviewed for differences.

1. Calculate the overall number of students who passed math
2. Calculate the overall number of students who passed reading
3. Calculate the overall number of students who passed both math and reading
4. Calculate the overall budget of the school district
5. Calculate the number of students who passed math at each school
6. Calculate the number of students who passed reading at each school
7. Calculate the number of students who passed both math and reading at each school
8. Calculate a per student budget amount for each school
9. Determine the top 5 high and low performing schools by % Overall Passing
10. Calculate average math scores by grade per school
11. Calculate average reading scores by grade per school
12. Calculate average math and reading scores, % passing math and reading, % overall passing by spending range per student (<$584, $585-629, $630-644, $645-675)
13. Calculate average math and reading scores, % passing math and reading, % overall passing by school size (<1000, 1000-2000, 2000-5000)
14. Calculate the average math and reading scores, % passing math and reading, % overall passing by school type (Charter, District)

## Resources
- Data Sources: students_complete.csv, schools_complete.csv
- Software: Python 3.7, Anaconda 4.10.1, Jupyter Notebook 6.3.0

## Results
Two different analysis were conducted via the same methodology utilizing the original and a modified dataset removing the 9th grade scores from Thomas High School.

The initial analysis utilizing the original dataset show:
  - District summary results are:
    - Total Schools: 15
    - Total Students: 39,170
    - Total Budget: $24,649,428.00
    - Avg Math Score: 79.0%
    - Avg Reading Score: 81.9%
    - % Passing Math: 75%
    - % Passing Reading 86%
    - % Overall Passing: 65%
  - The per school summary results are: [Per School Summary Results](Resources/school_summary.PNG)
  - High and low performing schools are:
    - [Top 5 High Performing Schools by % Overall Passing](Resources/high_performing.PNG)
    - [Top 5 Low Performing Schools by % Overall Passing](Resources/low_performing.PNG)
  - Math and reading scores by grade per school are:
    - [Math Scores by Grade Per School](Resources/math.PNG)
    - [Reading Scores by Grade Per School](Resources/reading.PNG)
  - Scores by school spending are: [Scores by School Spending](Resources/scores_by_school_spending.PNG)
  - Scores by school size are: [Scores by School Size](Resources/scores_by_school_size.PNG)
  - Scores by school type are: [Scores by School Type](Resources/scores_by_school_type.PNG)


The secondary analysis with the 9th grade data from Thomas High School removed show:
  - District summary results are:
    - Total Schools: 15
    - Total Students: 38,709
    - Total Budget: $24,649,428.00
    - Average Math Score: 78.9%
    - Average Reading Score: 81.9%
    - % Passing Math: 74.8%
    - % Passing Reading: 85.7%
    - % Overall Passing: 64.9%
  - The per school summary results are: [Per School Summary Results](Resources/updated_school_summary.PNG)
  - High and low performing schools are:
    - [Top 5 High Performing Schools by % Overall Passing](Resources/updated_high_performing.PNG)
    - [Top 5 Low Performing Schools by % Overall Passing](Resources/updated_low_performing.PNG)
  - Math and reading scores by grade per school are:
    - [Math Scores by Grade Per School](Resources/updated_math.PNG)
    - [Reading Scores by Grade Per School](Resources/updated_reading.PNG)
  - Scores by school spending are: [Scores by School Spending](Resources/updated_scores_by_school_spending.PNG)
  - Scores by school size are: [Scores by School Size](Resources/updated_scores_by_school_size.PNG)
  - Scores by school type are: [Scores by School Type](Resources/updated_scores_by_school_type.PNG)

Removing Thomas High School 9th grade data resulted in the following District changes relative to the original results:
  - Total Students: Reduced from 39,170 to 38,709
  - Total Budget: Remained the same at $24,649,428.00
  - Average Math Score: Reduced from 79.0% to 78.9%
  - Average Reading Score: Remained the same at 81.9%
  - % Passing Math: Reduced from 75% to 74.8%
  - % Passing Reading: Reduced from 86% to 85.7%
  - % Overall Passing: Reduced from 65% to 64.9%
   
Removing the 9th grade Thomas High School data resulted in no change to the following:
  - No change to top 5 high performing or top 5 low performing
  - No change to scores by school spending
  - No change to scores by school size
  - No change to scores by school type

## Summary

Comparing the two datasets results in a reduction in 4 scored values:
- Average Math Score was reduced by 0.1%
- % Passing Math was reduced by 0.2%
- % Passing Reading was reduced by 0.3%
- % Overall Passing was reduced by 0.1%
