# PyCitySchools Analysis

## Overview of project

### Purpose
The purpose of this analysis is to determine the performance of individual schools based on math and reading scores. Further, overall school performance will be analyzed based on the grade, school type, school size, and school spending. Additionally, the impact of the adjustment to the dataset due to the evidence for academic dishonesty in Thomas High School will be explored.  

## Results

- How is the district summary affected?
    - Adjusting for Thomas High School Grade 9 scores to NaN effectively adjusted 460 students out of 39,169 students. As this accounted for about 1.2% of students, it should not have a significant effect on the district in terms of score (which includes every grade). Looking at the changes, we see that the Average Math Score changed by 0.1, the Average Reading Score changed by nothing, The Passing Math changed by 0.2, the Passing Reading changed by 0.1, and the Overall Passing changed by 0.3. This is an expected result as changing the population of Grade 9s to NaN would automatically fail them and decrease the amount of students passing. 
