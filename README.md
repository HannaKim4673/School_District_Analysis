# School District Analysis

## Overview of Project

### Purpose
Jupyter notebook, pandas, python, and numpy were used to analyze student funding, school information, and students' standardized math and reading test scores for the state board of education. The main goal of this analysis was to find patterns and relationships amongst provided student funding, school, and students' test score information to help the state board of education make decisions, like how school budgets should be allocated. In the case of the challenge, the goal was to replace data that the state board of education discovered was altered (i.e., the math and reading test scores for Thomas High School 9th graders) with NaNs, run the analysis again, and see how the replacement of the altered data with NaNs affected the results of the analysis.

## Results

### How Removing Altered Data Affected Below School District Metrics
- **District Summary:** As visible in the two figures below, after the academically dishonest altered data for Thomas High School 9th graders was replaced with NaNs the average math score for the district decreased by 0.1 points, the percent of students passing math in the district decreased by 0.2 percent, the percent of students passing reading in the district decreased by 0.3 percent, and the percent of students passing both math and reading in the district decreased by 0.1 percent.
  - ![](https://github.com/HannaKim4673/School_District_Analysis/blob/main/Screenshots%20for%20readme/District%20Summary%20After%20Data%20Removal.png)
  - ![](https://github.com/HannaKim4673/School_District_Analysis/blob/main/Screenshots%20for%20readme/District%20Summary.png)
- **School Summary:** As visible in the yellow outlined rows in the figures 3 and 4 below, after the altered data for Thomas High School 9th graders was replaced with NaNs the average math score for Thomas High School students decreased by 0.067453 points, their average reading score increased by 0.047152 points, the percentage of Thomas High School students passing math decreased by 26.360856 percent, the percentage of Thomas High School students passing reading decreased by 27.64526 percent, and the percentage of Thomas High School students passing both math and reading decreased by 25.871559 percent.    
  - ![](https://github.com/HannaKim4673/School_District_Analysis/blob/main/Screenshots%20for%20readme/School%20Summary%20After%20Data%20Removal.png)
  - ![](https://github.com/HannaKim4673/School_District_Analysis/blob/main/Screenshots%20for%20readme/School%20Summary.png)
- **Thomas High School performance compared to other schools:** After the altered data for Thomas High School 9th graders was was replaced with NaNs, while the average reading and math scores and percentages for Thomas High School did change after the data value replacement, Thomas High School's standing and performance compared to the other schools in the district did not change at all. In fact, as visible in figures 5 and 6 below, Thomas High School remains the 2nd best school in the district even after the 9th graders' reading and math scores were replaced with NaNs.
  - ![](https://github.com/HannaKim4673/School_District_Analysis/blob/main/Screenshots%20for%20readme/Best%20Schools%20After%20Data%20Removal.png)
  - ![](https://github.com/HannaKim4673/School_District_Analysis/blob/main/Screenshots%20for%20readme/Best%20Schools.png)
- **Math and Reading Scores by Grade:** As visible in the yellow outlined rows in the figures 7 through 9 below, after the altered data for Thomas High School 9th graders was replaced with NaNs, the average math and reading scores for Thomas High School 9th graders became NaN.
  - ![](https://github.com/HannaKim4673/School_District_Analysis/blob/main/Screenshots%20for%20readme/Math%20by%20Grade%20After%20Data%20Removal.png) ![](https://github.com/HannaKim4673/School_District_Analysis/blob/main/Screenshots%20for%20readme/Math%20by%20Grade.png)
  - ![](https://github.com/HannaKim4673/School_District_Analysis/blob/main/Screenshots%20for%20readme/Reading%20by%20Grade%20After%20Data%20Removal.png) ![](https://github.com/HannaKim4673/School_District_Analysis/blob/main/Screenshots%20for%20readme/Reading%20by%20Grade.png)  
- **Scores by School Spending:** This metric was unaffected.
- **Scores by School Size:** This metric was unaffected.
- **Scores by School Type:** This metric was unaffected.

## Summary
As noted in the Results section, 4 major changes that occurred after the altered math and reading scores for Thomas High School 9th graders were replaced with NaNs were that the percentage of students in Thomas High School passing math, reading, and both subjects greatly decreased; the average math and reading scores for the entire district decreased a little; the average math score for 9th graders at Thomas High School changed to NaN; and the percentage of students passing both math and reading in the entire district dropped a little.
  
