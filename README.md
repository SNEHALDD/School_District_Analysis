# School_District_Analysis
# School_District_Analysis

#Overview of the school district analysis: Explain the purpose of this analysis.
In School District Analysis, students_complete.csv file showed evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered.I am supposed to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Also, describe how these changes affected the overall analysis after replacing the math and reading score of Thomas High School with NaN.


#Results: Using bulleted lists and images of DataFrames as support, address the following questions.

##How is the district summary affected?
Total student count will not have Thomas High School's 9th grade students in it. The final calculation should contain passing math and passing reading percentages, and the overall passing percentage with the recalculated total student count. It will affect the total performance of Thomas High School since we can not consider marks of 9th grade and replacing them with NaN.

Image of District Analysis = <img width="979" alt="District_Summary" src="https://user-images.githubusercontent.com/106944351/177866589-3d29277e-9442-492e-9540-4cec063a8e0d.png">

##How is the school summary affected?
Drop function will drop NaNs that means math and reading scores of Thomas High School will not be considered. It will affect the performance of overall Thomas High School.
Since Budget did not change even after dropping 9th grade students of Thomas High School, so every remaining student will have more budget.

Image of School Analysis = 


##How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
The overall performance gets better since they are dealing with less number of students now. 


##How does replacing the ninth-grade scores affect the following:
###Math and reading scores by grade 
Replacing 9th grade scores will not affect other grade's math and reading scores. It will only affect overall Thomas High School performance

###Scores by school spending
It will affect budget per student. Per student budget will increase since we are dropping 9th grade students.

###Scores by school size
% passing Math, % passing reading, % overall passing will increase as we are considering 10th, 11th and 12 grade math and reading scores.

###Scores by school type
Dropping 9th grade scores from Thomas High School will no affect scores by school type

#Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
1)Total student count varies
2)Total percentage varies
3)budget per student varies
4)count of total number of students passed math and reading from Thomas School changes
