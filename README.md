## School_District_Analysis

## Overview of the school district analysis:
The purpose of this project was to help Maria analyze the data of the high schools before and after possible academic dishonesty from one of the schools. The data for 9th Grade of Thomas High School is being scrutinized. We replaced the math and reading scores for Thomas High School with NaNs while leaving the rest of the data the same, analyzing the data before and after making the change.

* School and district summary
* Top 5 and bottom 5 performing schools, based on passing rate. 
* Average math and reading scores for each grade level from all schools.
* School performance based on budgets per student. 
* Scores by school spending per student, school size, and school type. 

# Resources:
* Data Source: schools_complete.csv, students_complete.csv
* Software: Python, Anaconda, Jupyter Notebook, Pandas

## Results:
* Maria was notified by the school board that the students_complte.csv file shows evidence of academic dishonesty in reading and math grades for Thomas High School ninth graders. The school board does not know the full extent, but they want to updhold state-testing standards and have asked us to work on the numbers for the ninth graders at Thomas High school.
* We replaced the math and readin scores while keeping all other data associated with the student group intact. 
* Math and reading scores were replaced with "NaN", for the student records. The "NaN" is a replacement for where there is no number value. 
* Output shows 

![Results](https://user-images.githubusercontent.com/106033535/178174545-ce925f93-e7b6-4bca-a35e-2d38a31e70cc.png)

# District Summary:

![District Summary](https://user-images.githubusercontent.com/106033535/178174581-f20ffa39-15ad-4434-88e5-b5bb993a8c72.png)

* The data is unnaffected in Total Schools, Total Students and Total Budget
* The data didn't changee the math and reading scores by grade. 

# School Summary:
* This output confirms the metrics for Thomas High School while calculating Per School Budget and Per Studen Budget:

![School Summary](https://user-images.githubusercontent.com/106033535/178174908-229d3016-cb02-4c6f-b119-56b6bca0629e.png)

* Average Math Score and Average Reading Score for Thomas High School dreastically changed after the data change. 

* Replacing 9th grade math and reading scores in Thomas High School affected their performance drastically. 
Ninth Grade Math Scores

<img width="302" alt="9th Grade Math Scores" src="https://user-images.githubusercontent.com/106033535/178175107-db86caa1-b1d9-4222-b669-5b8438293e20.png">

Ninth Grade Reading Scores

<img width="304" alt="9th Grade Reading Scores" src="https://user-images.githubusercontent.com/106033535/178175153-f9b4e736-6575-4575-b086-42b4697f9ccb.png">

Replacing the ninth grade scores affect math and reading scores by grade looking at average percentage. 

* Top 5 Schools

![Top 5 Schools](https://user-images.githubusercontent.com/106033535/178175300-731b1783-fb5b-470e-bc11-d5e43242bd8a.png)

* Bottom 5 Schools

![Bottom 5 Schools](https://user-images.githubusercontent.com/106033535/178175358-66fb4b90-62d1-4128-9f0f-da1e66f3568d.png)

* Scores by School Spending

![Spending Ranges](https://user-images.githubusercontent.com/106033535/178175450-9d777ed0-7a24-489f-8394-fe5a151c9421.png)
![School Spending Summary](https://user-images.githubusercontent.com/106033535/178175460-2c21bef2-dd22-4bc7-9677-6e9d1dca71a5.png)

* Scores by School Size

<img width="786" alt="Scores by school size" src="https://user-images.githubusercontent.com/106033535/178175502-b8ec901b-46c3-4903-b579-56cd6c15f272.png">

* Scores by School Type

![Scores by school type](https://user-images.githubusercontent.com/106033535/178175525-420657b0-4cb4-4a6a-899d-3e68829e80e8.png)


# Summary: 

* Using NaN for replaceing the ninth graders scores caused the overall passing percentages and average scores to drop. Average math scores, reading scores, and overall passing percentage decreased. 
* Thomas High school lost it's placement as a top five school in district. 
