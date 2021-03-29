# School_District_Analysis
## 1. Overview of the school district analysis
The school district analysis looks at students' grades across various schools for maths and reading with students in grades 9 to 12. After the initial analysis, the school board notified that there was some evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. To incorporate this information while maintaining state-testing standards, the scores for math and reading were replaced with NaNs and the remaining data was kept intact.The school district analysis was repeated and this writeup describes how these changes affected the overall analysis.

## 2.	Results
The following changes in the analysis were observed:

* District summary 
The overall percentages are very close to original. The revised analysis has the same number of total students since there data was kept with the original and only their scores were replaced. These can be seen in the following two images:
https://github.com/madihajaved/School_District_Analysis/blob/main/Resources/disctrict_summary_original.png
https://github.com/madihajaved/School_District_Analysis/blob/main/Resources/disctrict_summary_revised.png

* School summary 
The summary scores for Thomas High School have changed. While the total number of students is 1635, only scores of 1174 students is being counted given that the scores of ninth graders were replaced. This has changed the passing percentages as well with the revised percentages of maths, reading and overall being 93%, 97% and 90%. 

* Relative performance of Thomas High School 
In terms of ranking, Thomas High School is still second in place with the second highest overall percentage. However, the stats have changed slightly from a previous 90.95% overall passing score to 90.63%. The unformatted numbers can be seen in this image:

https://github.com/madihajaved/School_District_Analysis/blob/main/Resources/top%20five%20schools%20-%20revised.png

* Impact of replacing ninth-grades scores
  * Math and reading scores by grade: Except for Thomas High School nine-graders whose scores now show NaN, everything else is same.    
  * Scores by school spending: Thomas High School has a per capita budget of $638. Thus, for the third spending bin of $630 to $644 the average math and reading scores change. However, once the scores are formatted and rounded off, the change is so small that the overall numbers look the same. For instance, before replacing the scores with NaN, the overall passing in the third spending bin was 62.86% which got reduced to 62.78% but both these figures rounded off to 63% in the final output. 
  * Scores by school size: Thomas High School is a medium sized school with 1635 students overall. Again the change is so small that it is lost in the final output. However, the revised analysis shows that overall passing of students in medium sized school changed from 90.62% to 90.56% while other two categories remained unchanged. 
  * Scores by school type: Thomas High School is a Charter school and overall passing score for Charter schools fell from 90.43% to 90.39%.    

## 3.	Summary
To summarize, the following were the major changes:
* 451 scores were excluded from overall analysis
* Total students whose scores were counted declined to 38709 from 39160
* Maths and reading passing percentage for Thomas High School changed 
* Overall passing percentage for Thomas High school was also changed 

