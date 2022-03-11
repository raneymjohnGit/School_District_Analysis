# School District Analysis
This is the repository to store the School District Analysis Challenge

## Project Overview
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you have replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

## Resources
- Data source : students_complete.csv
- Anaconda 4.11.0, Python 3.9, jupyter notebook

## Challenge Overview
Prerequisite:
1. Make a copy of your PyCitySchools.ipynb file and rename it PyCitySchools_Challenge_testing.ipynb
2. Download the PyCitySchools_Challenge_starter_code.ipynb file, copy the code, and paste it at the top of your PyCitySchools_Challenge_testing.ipynb file.
3. Install NumPy module from command line using following command
    -   pip install numpy


## Deliverable 1: Replace ninth-grade reading and math scores for Thomas High School with NaNs

Use the step-by-step instructions below to add code where indicated by the numbered comments in the starter code file.

Step 1: Use the code snippet provided in Step 1 to import the NumPy module.

Step 2: Use the code snippet provided in Step 2 for the Pandas loc method.
	   
Step 3: To select all the ninth-grade reading scores at Thomas High School, use the following steps to write code inside the brackets of the loc method

Step 4 Refactor the code from Step 2 to replace the math scores with NaNs.

Step 5: Check the student data to make sure the grades were replaced with NaNs.

Step 6: After you run Step 5 in your PyCitySchools_Challenge_testing.ipynb file, confirm that the DataFrame looks like the image below, where the ninth-grade reading and math scores from Thomas High School have been replaced with NaNs. Then, make a copy of the PyCitySchools_Challenge_testing.ipynb file and rename it PyCitySchools_Challenge.ipynb.

## Deliverable 2: Repeat the School District Analysis 

Repeat the school district analysis you did in this module, and recreate the following metrics:

-   The district summary
-   The school summary
-   The top 5 and bottom 5 performing schools, based on the overall passing rate
-   The average math score for each grade level from each school
-   The average reading score for each grade level from each school
-   The scores by school spending per student, by school size, and by school type

Use the instructions below to add code where indicated by the numbered-step comments in the starter code file to update the District Summary DataFrame.

Step 1: Using the loc method with logical and comparison operators, retrieve the student count for Thomas High School ninth graders in the school_data_complete_df DataFrame

Step 2: Subtract the number of students retrieved from Step 1 from the total student count to get the new total student count.
	   
Step 3: Calculate the math and reading passing percentages based on the new total student count.

Step 4: Calculate the overall passing percentage with the new total student count.

Step 5: Run the code from this module that creates and formats the School Summary DataFrame.

Step 6: Get the number of 10th-12th grade students from Thomas High School.

Step 7: Use the loc method to create a new DataFrame that has all the students passing math from Thomas High School.

Step 8: Use the loc method to create a new DataFrame that has all the students passing reading from Thomas High School.

Step 9: Use the loc method to create a new DataFrame that has all the students passing math and reading from Thomas High School.

Step 10: Calculate the percentage of 10th-12th grade students passing math from Thomas High School.

Step 11: Calculate the percentage of 10th-12th grade students passing reading from Thomas High School.

Step 12: Calculate the overall passing percentage of 10th-12th grade students from Thomas High School.

Step 13: Use the loc method to replace the % Passing Math score for Thomas High School with the new math passing percentage you calculated in Step 10.

Step 14: Use the loc method to replace the % Passing Reading score for Thomas High School with the new reading passing percentage you calculated in Step 11.

Step 15: Use the loc method to replace the % Overall Passing score for Thomas High School with the new overall passing percentage you calculated in Step 12.

Step 16: Next, complete the following steps for school district analysis using the remaining steps that are provided in the starter code.

    -   The top 5 and bottom 5 performing schools, based on the overall passing rate
    -   The average math score for each grade level from each school
    -   The average reading score for each grade level from each school
    -   The scores by school spending per student, by school size, and by school type

## School District Analysis Results

- Replaced ninth-grade reading and math scores for Thomas High School with NaNs:
![image_name](https://github.com/raneymjohnGit/stock-analysis/blob/main/Resources/VBA_Challenge_2017.png)


- Number of students after subtracting the number of students that are in ninth grade at Thomas High School from the total student count 
  38709

-   District Summary DataFrame with NaNs for math and reading for Thomas High School 9th Grades
    ![image_name](https://github.com/raneymjohnGit/stock-analysis/blob/main/Resources/VBA_Challenge_2017.png)
    
-   Per school summary with School Type,Total Students,Total School Budget,Per Student Budget,Average Math Score,Average Reading Score,% Passing Math,% Passing Reading,% Overall Passing
    ![image_name](https://github.com/raneymjohnGit/stock-analysis/blob/main/Resources/VBA_Challenge_2017.png)

-   Update Per school summary for Thomas High School 
    ![image_name](https://github.com/raneymjohnGit/stock-analysis/blob/main/Resources/VBA_Challenge_2017.png)

-   High Performing Schools
    ![image_name](https://github.com/raneymjohnGit/stock-analysis/blob/main/Resources/VBA_Challenge_2017.png)

-   Low Performing Schools
    ![image_name](https://github.com/raneymjohnGit/stock-analysis/blob/main/Resources/VBA_Challenge_2017.png)

-   Average Math Scores by School and Grade 
    ![image_name](https://github.com/raneymjohnGit/stock-analysis/blob/main/Resources/VBA_Challenge_2017.png)  

-   Average Reading Scores by School and Grade 
    ![image_name](https://github.com/raneymjohnGit/stock-analysis/blob/main/Resources/VBA_Challenge_2017.png) 

-   Scores summary based on spending bins
    ![image_name](https://github.com/raneymjohnGit/stock-analysis/blob/main/Resources/VBA_Challenge_2017.png) 

-   Scores summary based on size
    ![image_name](https://github.com/raneymjohnGit/stock-analysis/blob/main/Resources/VBA_Challenge_2017.png) 

-   Scores summary based on type
    ![image_name](https://github.com/raneymjohnGit/stock-analysis/blob/main/Resources/VBA_Challenge_2017.png)

-   How is the district summary affected?
    The  averages of math, passing score of math and reading, overall passing slightly decreased when we ignored the stutdent count from Thomas High school 9th Grades.

-   How is the school summary affected?
    The  averages of math, passing scores and passing percentage of math and reading, overall passing increased dramatically when we considered 10th -12th Grades only from Thomas
    High school .

-   How does replacing the ninth grader's math and reading scores affect Thomas High School's performance relative to the other schools?
    The replacing the ninth grader's math and reading scores dramatically improved the Thomas High School's performance

-   How does replacing the ninth-grade scores affect the following:
    
    -   Math and reading scores by grade
        It has no effect on other grades or 9th grade of schools other than Thomas High School
    
    -   Scores by school spending
        It has no effect
    
    -   Scores by school size
        It has no effect
    
    -   Scores by school type
        It has no effect

## School District Analysis Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
- Consider only 10th-12th grades from Thomas High School
- Average math and reading scores improved for Thomas High School
- % Passing math and reading improved for Thomas High School
- % Overall passing improved for Thomas High School
