# School_District_Analysis

## Overview of School District Analysis

In this project, I have been tasked with analyzing the standardized math and reading test scores for high school students in a city school district. I collaborated with the city school district data scientist to analyze, report, and present performance trends at the school and district level. The data scientist has given me the following tasks to complete the school district analysis of the recent standardized testing:

1. Provide a district summary breakdown including the total schools, total students, total budget, average math score, average reading score, percentage passing math, percentage passing reading, and the overall passing percentage.
2. Provide a school summary breakdown with the same metrics as the district summary plus the school budget per capita.
3. Determine the highest and lowest performing schools based on the overall passing percentage.
4. Provide a breakdown of the average math and reading scores by grade for each school.
5. Determine average math and reading scores and passing percentages based on school budget.
6. Determine average math and reading scores and passing percentages based on school size.
7. Determine average math and reading scores and passing percentages based on school type.

The city school district has provided school data and student testing data in CSV files. The schools file contains each school ID, name, type, size and budget. The student file contains each student ID, name, gender, grade, school, reading score and math score. I used Jupyter Notebook in a Python3 environment and imported the pandas and numpy modules to pull information, create data frames, and perform operations. During the analysis I manipulated the data through merging datasets, removing unreliable student scores, and grouping the complete dataset as necessary. The full set of resources and the school district results are shown below.

## Resources
- Data Source: schools_complete.csv, students_complete.csv
- Software: Python 3.8.9, Jupyter Notebook

## School District Results

During the analysis, it was reported that there was academic dishonesty among the Thomas High School ninth graders. The following results show the city school district analysis with and without the ninth grade Thomas High School standardized testing scores:

- School District Summary

[images]

  - The academic dishonesty did not affect the total number of students, total district budget, or average reading score.
  - The academic dishonesty appeared to increase the district average math score by 0.1, the percentage passing math by 0.2%, the percentage passing reading by 0.3%, and the overall passing percentage by 0.1%.

- School Summary

[images]

  - The academic dishonesty did not affect the results of the other fourteen high schools.
  - The academic dishonest appeared to increase Thomas High School average math score by 0.06, the average reading score by 0.05, the percentage passing math by 0.1%, the percentage passing reading by 0.3%, and the overall passing percentage by 0.3%.

- Top 5 and Bottom 5 Performing Schools

[images]

  - The academic dishonesty did not affect the school's performance relative to other schools in the district.

- Math and Reading Scores by Grade

[images]

  - The academic dishonesty did not affect the math and reading scores by grade. The ninth grade scores at Thomas High School have been omitted.

- Math and Reading Scores by School Spending

[images]

  - The academic dishonesty did not affect the math and reading scores relative to school spending.

- Math and Reading Scores by School Size

[images]

  - The academic dishonesty did not affect the math and reading scores relative to school size.

- Math and Reading Scores by School Type

[images]

  - The academic dishonesty did not affect the math and reading scores relative to school type.

## School District Summary

Due to academic dishonesty, the ninth grade Thomas High School testing scores increased the math passing rate, reading passing rate, and the overall passing rate for the school and district. In all cases, the increase was within 1% of the original analysis. The school performance relative to the other schools was not affected by the omitted scores and neither were the standardized testing scores by grade, by school spending, school size, or school type.
