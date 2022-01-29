# PyCitySchools Analysis

## Overview of project

### Purpose
The purpose of this analysis is to determine the performance of individual schools based on math and reading scores. Further, overall school performance will be analyzed based on the grade, school type, school size, and school spending. Additionally, the impact of the adjustment to the dataset due to the evidence for academic dishonesty in Thomas High School will be explored.  

## Results

- How is the district summary affected?
    - Adjusting for Thomas High School Grade 9 scores to NaN effectively adjusted 460 students out of 39,169 students. As this accounted for about 1.2% of students, it should not have a significant effect on the district in terms of score (which includes every grade). Looking at the changes, we see that the Average Math Score changed by 0.1, the Average Reading Score changed by nothing, The Passing Math changed by 0.2, the Passing Reading changed by 0.1, and the Overall Passing changed by 0.3. This is an expected result as changing the population of Grade 9s to NaN would automatically fail them and decrease the amount of students passing. 
- How is the school summary affected? 
    - Under School Summary, Thomas High School’s % Passing for Math, Reading, and Overall have been significantly decreased by around 26%. This is an expected result as 460 out of 1635 (28%) students are now automatically failing. Looking into the average scores, they have not changed much, with reading actually increasing by a little bit. 
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools? 
    - The removal of Grade 9 Scores in Thomas High School significantly affected Thomas High School’s passing performance. However this is due to the automatic failures of all of their Grade 9 Students. If we were to exclude these grade 9 from the school’s performance and only look at Thomas High School’s performance from grade 10 to 12, then their overall ranking compare to other schools is still rank 2. This may be an indication that Thomas High School either may not have been dishonest with their grade 9s (if the grade 9 adheres to the overall performance of their grade 10s – 12s), or Thomas High School is dishonest for every grade. 
- How does replacing the ninth-grade scores affect the following:
    - Math and reading scores by grade
        - There is no record for grade 9 Thomas High School.
    - Scores by school spending
        - Since Thomas High School is categorized under range 630-644, we can see that after removing data, the passing rate is slightly decreased compared to original table. The reason of this minor change is because we had removed the grade 9 Thomas High School population and the grade 10 to 12 performance was still similar to what was there before. 
    - Scores by school size
        - Applying the same logic to school size, the number is slightly lower than the original dataset after removing grade 9 Thomas High School. 
    - Scores by school type
        - Similar to school size and school spending, the number is slightly lower than the original dataset after removing grade 9 Thomas High School.
## Summary
After reading and math scores for the ninth grade Thomas High School students were replaced with NaNs, four major changes occurred.
1) 
