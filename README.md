# School_District_Analysis

## Project Overview
A school board has given the following tasks to complete the analysis of student data in the PyCities School District across all students in grade levels 9 through 12 and all schools. The validity of a subset of the data was determined to be in question and a separate analysis requested along with a comparison of the original results relative to updated results with the potentially erroneous subset of data removed.

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
    - [Math Scores by Grade Per School](Resources/math_scores.PNG)
    - [Reading Scores by School Per School](Resources/reading_scores.PNG)
  - Scores by school spending are: [Scores by School Spending](Resources/scores_school_spending.PNG)
  - Scores by school size are: [Scores by School Size](Resources/scores_school_size.PNG)
  - Scores by school type are: [Scores by School Type](Resources/scores_school_type.PNG)


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
    - [Math Scores by Grade Per School](Resources/updated_math_scores.PNG)
    - [Reading Scores by School Per School](Resources/updated_reading_scores.PNG)
  - Scores by school spending are: [Scores by School Spending](Resources/updated_scores_school_spending.PNG)
  - Scores by school size are: [Scores by School Size](Resources/updated_scores_school_size.PNG)
  - Scores by school type are: [Scores by School Type](Resources/updated_scores_school_type.PNG)

## Summary
