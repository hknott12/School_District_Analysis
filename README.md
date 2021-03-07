# School District Analysis
Analyzing a school district's data
## Overview of the Project
The goal of this project was to analyze the school district's data regarding test scores, school size, school type, and school budget. The analysis was done on all the data for the school district, but then was repeated to exclude the test scores of 9th graders from Thomas High School because of a cheating issue.
## Results
After repeating the district analysis and excluding the 9th grade test scores from Thomas High School, the original results were impacted. Details of the impacts are listed here. 
* District Summary
The original district summary is very slightly eafected by the score removal from Thomas High School. The average math score, percent of students passing math, and percent of students passing both reading and math are all slightly lower.  
Original District Summary:  
![original](Images/district_summary_original.png)  
  
Modified District Summary:
![modified](Images/district_summary_modified.png)
  
* School Summary. 
The individual school summaries are the same for every school except Thomas High School. The math and reading scores are slightly lower after the removal of the ninth grade scores, and the percentage of students passing is slightly lower.   
Original District Summary:  
![orignal_summary](Images/school_summary_original.png)  

Modified District Summary:  
![modified_summary](Images/school_summary_modified.png)

* Thomas High School Ranking
Because the change in scores for Thomas High School is so small, it retains its spot as number 2 in the ranking of the top five schools based on test score performance.  
Original Top Five Ranking:
![original_top](Images/top_schools_original.png). 

Modified Top Five Ranking:
![modified_top](Images/top_schools_modified.png)
  
* Math and reading scores by grade
The math and reading scores by grade were the same for all schools and grades, except the Thomas High School ninth graders. Instead of average reading and math scores, Thomas High School ninth graders have null values in those columns. 
Original Math and Reading Scores:  
![original_scores](Images/math_grade_original)  
![original scores](Images/reading_grade_original) 

Modified Math and Reading Scores:  
![modified scores](Images/math_grade_modifed)  
![modified_scores](Images/reading_grade_modified)  

* Scores by school spending
The scores by school spending were unchanged with the modification of the ninth grade scores. This is likely because the changes in average test scores was so small for Thomas High School.  
Original Scores by School Spending:  
![original_spending](Images/spending_original.png)  
Modified Scores by School Spending:  
![modified_spending](Images/spending_modified.png)  

* Scores by school size  
The scores by school size were also unchanged, likely for the same reasons as the scores by school spending.  
Original Scores by School Size:  
![original_size](Images/size_summary_original.png)  
Modified Scores by School Size:  
![modifed_size](Images/size_summary_modified.png)  

* Scores by school type
The scores by school type were also unchanged.  
Original Scores by School Type:  
![original_type](Images/type_summary_original.png)  
Modified Scores by School Type:  
![modified_type](Images/type_summary_modified.png)


## Summary
There is a statement summarizing four major changes to the school district analysis after reading and math scores have been replaced (5 pt).
In summary, the main four changes to the school district analysis are: 
* The school district summary is slightly different, with lower reading and math score averages and a lower percentage of students passing reading and math. 
* The average scores for Thomas High School are slightly lower, as are its percentage of students passing reading and math. 
* The average scores by grade level have no value for Thomas High School ninth graders for math and reading. 
* Thomas High School is the same ranking as before modifying the values, but with a slightly lower margin. 

