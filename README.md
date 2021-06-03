# Module 4 Challenge - School District Analysis

## Overview of Project

Maria is a Data Scientist for the City School District. She is responsible for analyzing various types of data and producing performance trends and patterns. This information enables to take decisions in school and district level regarding budgets and priorities.
The project is required to assist Maria in analyzing data - student, funding and standardized test scores, create the required dataframes/reports which showcase school and student performance and trends. The results would be used for making decisions in school budget and priority.


### Purpose

The purpose of this project is to analyze, filter the input data and create the required student, funding and grade data for Maria.
The student information has been provided in the comma separated value file: students_complete.csv
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. 
Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. 
We have to assist Maria to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once we have replaced the math and reading scores, Maria would like us to create the school district analysis using the revised data.
Finally we have to write up a report to describe how these changes affected the overall analysis.

The district analysis should contain the below information:

1. District level summary of all schools with the school count, total students, total budget, Average Math Score, Average Reading Score, % Passing Math, % Passing Reading, % Overall Passing
2. School level report with School Type, Total Students, Total School Budget, Per Student Budget, Average Math Score, Average Reading Score, % Passing Math, % Passing Reading, % Overall Passing
3. Math Grades for grades - 9th, 10th, 11th and 12th
4. Reading Grades for grades - 9th, 10th, 11th and 12th
5. Update the school level report with the field - Spending Ranges (Per Student) - which has the spending ranges per student for each school
6. Update the school level report with the field - School Size - which has the categories according to the number of students in the school
7. Create dataframe for Spending Summary
8. Create dataframe for School Size Summary
9. Create dataframe for School Size Summary



# School-District-Analysis Results

How is the district summary affected?
How is the school summary affected?
How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade
Scores by school spending
Scores by school size
Scores by school type

(1) How is the district summary affected?

Below is the district summary which has the Thomas High School ninth graders details:
![Screen Shot 2021-06-03 at 9.23.09 AM](https://i.imgur.com/fPXELe8.png)

Below is the district summary which does not have the Thomas High School ninth graders details:
![Screen Shot 2021-06-03 at 9.25.40 AM](https://i.imgur.com/XKrLc6v.png)

The % Passing Math, % Passing Reading, and % Overall Passing values have come slightly down once the Thomas High School ninth graders details have been removed

(2) How is the school summary affected?

 Below is the school summary which has the Thomas High School ninth graders details:
![Screen Shot 2021-06-03 at 9.33.19 AM](https://i.imgur.com/eARZHoZ.png)

Below is the school summary which does not have the Thomas High School ninth graders details:
![Screen Shot 2021-06-03 at 9.35.40 AM](https://i.imgur.com/Ibi1a8e.png)

The % Passing Math, % Passing Reading, and % Overall Passing values for Thomas High School have come down. This has come down as we are calculating the percentages for Thomas High School students, still considering the Grade 9 students in the total.

Once we calculate the Thomas High School details considering only students from Grades 10th-12th, below are the details:
![Screen Shot 2021-06-03 at 9.50.36 AM](https://i.imgur.com/j5Anr3P.png)

(3)  How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Replacing the ninth grader's math and reading scores puts Thomas High School in the high performing school group on the basis of % Overall Passing.

Below is the screen shot for the top five schools:

![Screen Shot 2021-06-03 at 9.53.46 AM](https://i.imgur.com/o6FvuKf.png)




(4) How does replacing the ninth-grade scores affect the following:

(a) Math and reading scores by grade

Math and reading scores by grade will not have 9th grade details for Thomas High School:

Math Score Screen shot:
![Screen Shot 2021-06-03 at 9.59.57 AM](https://i.imgur.com/3etk7uR.png)

Reading Score Screen shot:
![Screen Shot 2021-06-03 at 10.01.28 AM](https://i.imgur.com/uuCWdXH.png)

(b) Scores by school spending

The school spending before replacing:
![Screen Shot 2021-06-03 at 10.04.47 AM](https://i.imgur.com/Ej9YOe1.png)

The school spending after replacing:
![Screen Shot 2021-06-03 at 10.07.16 AM](https://i.imgur.com/jcIjuuA.png)

The Spending Ranges for Bailey High School has changed from $585-629 to $630-644
The Spending Ranges for Griffin High School has changed from $585-629 to $630-644

(c) Scores by school size

The school sizes do not see any size before and after replacing
![Screen Shot 2021-06-03 at 10.17.55 AM](https://i.imgur.com/dvfoOiy.png)


(d) Scores by school type
Scores by school type do not see any size before and after replacing
![Screen Shot 2021-06-03 at 10.19.19 AM](https://i.imgur.com/82cxzXE.png)


# School-District-Analysis Summary

Below are the changes changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs:

(a) District Summary:  The % Passing Math, % Passing Reading, and % Overall Passing values have come slightly down once the Thomas High School ninth graders details have been removed

(b) School Summary: The % Passing Math, % Passing Reading, and % Overall Passing values for Thomas High School have come down. However once they are recalculated considering only students from Grades 10th-12th, the percentages get updated, and puts Thomas High School in the high performing school group on the basis of % Overall Passing.

(c) Math and reading scores by grade: The 9th grades details are updated as NaN.

(d) Scores by School Spending: 
The Spending Ranges for Bailey High School has changed from bucket (585-629) to (630-649)
The Spending Ranges for Griffin High School has changed from bucket (585-629) to (630-649)







