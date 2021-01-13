# School_District_Analysis
## Overview: The purpose of this analysis is to create an analysis for Thomas Highschool Reading and Math grades where 9th graders are excluded. This primarily has to do with the fact that there is a problem 9th grade scores and the school board would like to maintain its high standards by only including grades they are sure about. In this case, grades 10 through 12. 
## Deliverable 1: Replacing the scores with NaNs. AS you can see in the picture in the link below, the 9th grade scores for reading and math have been replaced with NaNs. When recalculating the statistics, 9th graders will be excluded. 

https://github.com/cwbyrd/School_District_Analysis/blob/main/Analysis/Del%201%20with%20Nan%20in%209th%20graders.PNG

## Deliverable 2: In deliverable 2, we essentially replace the analysis we did in our modules where we exclude 9th graders. 
### Results
1. How is the district summary affected? District Summary did not have a larger impact. It looks as though removing 9th graders from consideration slightly increased the overall passing percentages for reading, math and overall. This may be because 9th graders at Thomas needed to acclimate to High School and had not gotten their sea legs yet. However, we can make no real conclusions because the purpose for excluding 9th graders is that the accuracy was in question. 
   a. The Average Math Score drops slightly. 
   b. Average Reading Score stayed the same. 
   c. The % Passing Math increases by a point. 
   d. The % Passing Reading increases by a point.
   e. The % Overall Passing increases by a little less than a point. 

2. How is the school summary affected? Thomas highschool was the only school that was impacted, which makes sense, as we changed 9th graders from THS. 
3. How does replacing the ninth graders's math and reading scores affect Thomas High School's (THS) performance relative to the other schools? Did not really change its position within the school district. 
4. How does replacing the ninth-grade scores affect the following? 
   a. Math and reading scores by grade : Since only Thomas High School was impacted, it will only impact 9th grade and only by a little. 
   b. Scores by school spending: There was no change in school spending when replacing THS 9th grade scores with NaN. 
   c. Scores by school size: Median scores did not really change that much when excluding 9th grade at Thomas.
   d. Scores by school type: No real changes for charter schools (which THS is).  

## Summary - 4 major changes occuring once the 9th graders received all NaNs for their grades.    
With respect to changes that occurred once 9th graders received all NaNs is the following: 
1. THS overall performance with the district is did not change. 
2. Spending per school did not have an impact on schools. 
3. Average scores for the district from a % passing perspective increased a little bit (by 1% or less) 
4. The school summary did not change except for THS. 
