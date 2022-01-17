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

## School District Analysis Results

During the analysis, it was reported that there was academic dishonesty among the Thomas High School ninth graders. The following results show the city school district analysis with and without the ninth grade Thomas High School standardized testing scores:

### School District Summary

<div align="center">

|<img width="923" alt="School_District_Summary" src="https://user-images.githubusercontent.com/95327115/149689562-e0bc0daa-77df-4ccc-94bd-9b244ae126d6.png">|
|:--:|
|*Figure 1a: School District Summary*|

|<img width="930" alt="School_District_Summary_Revised" src="https://user-images.githubusercontent.com/95327115/149689624-d206e2dc-65a2-430b-939f-ca2f061330a3.png">|
|:--:|
|*Figure 1b: School District Summary (9th Grade Thomas High School Omitted)*|

</div>

  - The academic dishonesty did not affect the total number of students, total district budget, or average reading score.
  - The academic dishonesty appeared to increase the district average math score by 0.1, the percentage passing math by 0.2%, the percentage passing reading by 0.3%, and the overall passing percentage by 0.1%.

### School Summary

<div align="center">
  
|<img width="995" alt="School_Summary" src="https://user-images.githubusercontent.com/95327115/149690282-54e4dae8-34cd-4e28-804b-7a56e40129d5.png">|
|:--:|
|*Figure 2a: School Summary*|

|<img width="992" alt="School_Summary_Revised" src="https://user-images.githubusercontent.com/95327115/149690310-f59339cf-d71a-4798-ac8d-db06345f9606.png">|
|:--:|
|*Figure 2b: School Summary (9th Grade Thomas High School Omitted)*|

</div>
  
  - The academic dishonesty did not affect the results of the other fourteen high schools.
  - The academic dishonest appeared to increase Thomas High School average math score by 0.06, the average reading score by 0.05, the percentage passing math by 0.1%, the percentage passing reading by 0.3%, and the overall passing percentage by 0.3%.

### Top 5 and Bottom 5 Performing Schools

<div align="center">
  
|<img width="993" alt="Top_5_Schools" src="https://user-images.githubusercontent.com/95327115/149690375-006baba5-ad4a-49d7-8456-08ced9c238d7.png">|
|:--:|
|*Figure 3a: Top 5 Performing Schools*|
|<img width="992" alt="Top_5_Schools_Revised" src="https://user-images.githubusercontent.com/95327115/149690410-db737e46-0b37-4d96-bcbe-b4533178b33d.png">|
|*Figure 3b: Top 5 Performing Schools (9th Grade Thomas High School Omitted)*|

|<img width="996" alt="Bottom_5_Schools" src="https://user-images.githubusercontent.com/95327115/149690443-8530ea31-e29a-40eb-9363-b1e4a5d1592d.png">|
|:--:|
|*Figure 4a: Bottom 5 Performing Schools*|
|<img width="991" alt="Bottom_5_Schools_Revised" src="https://user-images.githubusercontent.com/95327115/149690473-617d0cfa-0dad-4d9e-9006-f588820dfe3d.png">|
|*Figure 4b: Bottom 5 Performing Schools (9th Grade Thomas High School Omitted)*|

</div>
  
  - The academic dishonesty did not affect the school's performance relative to other schools in the district.

### Math and Reading Scores by Grade

<div align="center">

|<img width="302" alt="Math_Scores_by_Grade" src="https://user-images.githubusercontent.com/95327115/149690507-7f344ac7-c5b4-4c6f-b13b-62f0a87d41ec.png">|<img width="298" alt="Math_Scores_by_Grade_Revised" src="https://user-images.githubusercontent.com/95327115/149690521-376b2763-a854-43b7-95df-18ab4540eec2.png">|
|:--:|:--:|
|*Figure 5a: Math Scores by Grade*|*Figure 5b: Math Scores by Grade <br /> (9th Grade Thomas High School Omitted)*|

|<img width="299" alt="Reading_Scores_by_Grade" src="https://user-images.githubusercontent.com/95327115/149691863-e90a0eba-3da1-4e69-a6b0-c299e58fc380.png">|<img width="298" alt="Reading_Scores_by_Grade_Revised" src="https://user-images.githubusercontent.com/95327115/149691962-d6a1e01b-1ea4-41b6-9485-b3c5db93857d.png">|
|:--:|:--:|
|*Figure 6a: Reading Scores by Grade*|*Figure 6b: Reading Scores by Grade <br /> (9th Grade Thomas High School Omitted)*|

</div>

  - The academic dishonesty did not affect the math and reading scores by grade. The ninth grade scores at Thomas High School have been omitted.

### Math and Reading Scores by School Spending

<div align="center">
  
|<img width="812" alt="Results_by_Spending" src="https://user-images.githubusercontent.com/95327115/149690552-b3c3a77e-6235-4efc-8fbf-2df52411147b.png">|
|:--:|
|*Figure 7a: Math and Reading Scores by School Spending*|

|<img width="814" alt="Results_by_Spending_Revised" src="https://user-images.githubusercontent.com/95327115/149690571-b9a559a8-881f-414b-945c-b0041b894810.png">|
|:--:|
|*Figure 7b: Math and Reading Scores by School Spending (9th Grade Thomas High School Omitted)*|

</div>

  - The academic dishonesty did not affect the math and reading scores relative to school spending.

### Math and Reading Scores by School Size

<div align="center">
  
|<img width="756" alt="Results_by_Size" src="https://user-images.githubusercontent.com/95327115/149690579-6325ad13-6d06-4721-ba80-e81afca12549.png">|
|:--:|
|*Figure 8a: Math and Reading Scores by School Size*|

|<img width="754" alt="Results_by_Size_Revised" src="https://user-images.githubusercontent.com/95327115/149690588-32f64b1a-82a2-42f1-8d39-b4830a2961da.png">|
|:--:|
|*Figure 8b: Math and Reading Scores by School Size (9th Grade Thomas High School Omitted)*|

</div>

  - The academic dishonesty did not affect the math and reading scores relative to school size.

### Math and Reading Scores by School Type

<div align="center">
  
|<img width="706" alt="Results_by_Type" src="https://user-images.githubusercontent.com/95327115/149690607-cb8b88eb-cc10-4182-89e3-bebceff50992.png">|
|:--:|
|*Figure 9a: Math and Reading Scores by School Type*|

|<img width="709" alt="Results_by_Type_Revised" src="https://user-images.githubusercontent.com/95327115/149690623-ceedc544-cf3d-4984-9dcc-de2aa9641030.png">|
|:--:|
|*Figure 9b: Math and Reading Scores by School Type (9th Grade Thomas High School Omitted)*|

</div>  
  
  - The academic dishonesty did not affect the math and reading scores relative to school type.

## School District Summary

Due to academic dishonesty, the ninth grade Thomas High School testing scores increased the math passing rate, reading passing rate, and the overall passing rate for the school and district. In all cases, the increase was within 1% of the original analysis. The school performance relative to the other schools was not affected by the omitted scores and neither were the standardized testing scores by grade, by school spending, school size, or school type.
