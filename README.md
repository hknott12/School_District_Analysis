# School District Analysis
Analyzing a school district's data
## Overview of the Project
The goal of this project was to analyze the school district's data regarding test scores, school size, school type, and school budget. The analysis was done on all the data for the school district, but then was repeated to exclude the test scores of 9th graders from Thomas High School because of a cheating issue. The files used for the analysis are listed below.  
Jupyter Notebook Code and Output: ![code](PyCitySchools_Challenge.ipynb)  
Original Datasets: ![data1](Resources/schools_complete.csv)  
![data2](Resources/students_complete.csv)  
## Results
After repeating the district analysis and excluding the 9th grade test scores from Thomas High School, the original results were impacted. Details of the impacts are listed here. 
### District Summary
The original district summary is very slightly eafected by the score removal from Thomas High School. The average math score, percent of students passing math, and percent of students passing both reading and math are all slightly lower.  
  * Original District Summary:  
  ![original](Images/district_summary_original.png)  
  
  * Modified District Summary:
  ![modified](Images/district_summary_modified.png)
  
### School Summary  
The individual school summaries are the same for every school except Thomas High School. The math and reading scores are slightly lower after the removal of the ninth grade scores, and the percentage of students passing is slightly lower.   
  * Original District Summary:  
  ![orignal_summary](Images/school_summary_original.png)  

  * Modified District Summary:  
  ![modified_summary](Images/school_summary_modified.png)

### Thomas High School Ranking  
Because the change in scores for Thomas High School is so small, it retains its spot as number 2 in the ranking of the top five schools based on test score performance, though with a slightly larger margin compared to the top school. 
  * Original Top Five Ranking:  
  ![original_top](Images/top_schools_original.png)   

  * Modified Top Five Ranking:  
  ![modified_top](Images/top_schools_modified.png)  
  
### Math and Reading Scores by Grade  
The math and reading scores by grade were the same for all schools and grades, except the Thomas High School ninth graders. Instead of average reading and math scores, Thomas High School ninth graders have null values in those columns.  
  * Original Math Scores:  
  ![original_scores](Images/math_grade_original.png)  
  * Original Reading Scores:  
  ![original scores](Images/reading_grade_original.png)  

  * Modified Math Scores:  
  ![modified scores](Images/math_grade_modified.png)  
  * Modified Reading Scores:  
  ![modified_scores](Images/reading_grade_modified.png)  

### Scores by School Spending   
The scores by school spending were unchanged with the modification of the ninth grade scores. This is likely because the changes in average test scores were very small for Thomas High School. The number of ninth graders at Thomas High School is relatively small compared to the student population as a whole, so the averages were not greatly impacted. If the formatting were altered to show more decimal places, the changes might be more noticable.  
  * Original Scores by School Spending:  
  ![original_spending](Images/spending_original.png)  
  * Modified Scores by School Spending:  
  ![modified_spending](Images/spending_modifed.png)  

### Scores by School Size  
The scores by school size were also unchanged, likely for the same reasons as the scores by school spending.  
  * Original Scores by School Size:  
  ![original_size](Images/size_summary_original.png)  
  * Modified Scores by School Size:  
  ![modified_size](Images/size_summary_modified.png)  

### Scores by School Type  
The scores by school type were also unchanged.  
  * Original Scores by School Type:  
  ![original_type](Images/type_summary_original.png)  
  * Modified Scores by School Type:  
  ![modified_type](Images/type_summary_modifed.png)  


## Summary
In summary, the main four changes to the school district analysis are: 
* The school district summary is slightly different, with lower reading and math score averages and a lower percentage of students passing reading and math. 
* The average scores for Thomas High School are slightly lower, as are its percentage of students passing reading and math. 
* The average scores by grade level have no value for Thomas High School ninth graders for math and reading. 
* Thomas High School is the same ranking as before modifying the values, but with a slightly larger margin. 

