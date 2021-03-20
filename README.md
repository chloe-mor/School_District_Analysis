# School_District_Analysis

## Overview and Purpose
There is evidence of acadmeic dishonesty in our data set. The board requested we pull the suspicious data and re-run our analysis. Once we have a "cleaned up" analysis, we can present our findings to the board. We want to be prepared for any questions we may be asked, so in additional to re-running the analysis, we are going to compare the original results with the cleaned up results. This will tell us the extent to which the dishonest data impacted the overall analysis.

## Results
After replacing the ninth grade math and reading scores at Thomas High School with null or `NaN` we were able to re-run the analysis for the schools in the PyCity district. 

> *As a note, we had to replace the scores with `NaN` in order to perform the mathematical operations in our analysis. Had we used "None" or "0" in those entries, our averages would have come up in an error (in the case of "None") or they would have been skewed tremendously (in the case of "0"). The value `NaN` is read as a numeric value and a float integer.*
 
The comparison between the original analysis (containing dishonest data) and the cleaned up analysis (dishonest data replaced with `NaN`) is below.

 ### District Summary
**Original**
![district_summary_original](https://user-images.githubusercontent.com/79174885/111883834-16771480-8994-11eb-9162-b3c2fa516774.png)

**Clean**
![district_summary_clean](https://user-images.githubusercontent.com/79174885/111883880-5a6a1980-8994-11eb-80cc-e9a76dd71f4e.png)

Replacing the scores hardly had an effect on the overall district summary.

### School Summary
**Original**
![per_school_summary_original](https://user-images.githubusercontent.com/79174885/111879855-95f9e900-897e-11eb-9c87-46d1b71deafb.png)

**Clean**
![per_school_summary_clean](https://user-images.githubusercontent.com/79174885/111879860-98f4d980-897e-11eb-8b4e-709c7fe48006.png)

The per school summary data only changed for Thomas High School's data. No other school was impacted by replacing the scores. 

### Thomas High School vs. Others
When it comparing Thomas HS to the other schools in the city, the change in data has no impact on the school's ranking. After removing the ninth graders scores, Thomas HS is still ranked second in PyCity for percentage of students passing both math and reading.

### Scores by Grade
The average math and reading scores by grade for each school were not impacted after changing the ninth grade data for students at Thomas High School. This is because the values for all other grades at all other schools were not altered in the "cleaning up" process.

### Scores by School Spending
**Original**
![scores_by_spending_original](https://user-images.githubusercontent.com/79174885/111884057-715d3b80-8995-11eb-82bf-dbb28c4325c9.png)

**Clean**
![scores_by_spending_clean](https://user-images.githubusercontent.com/79174885/111884060-76ba8600-8995-11eb-911f-3837087b950f.png)

The average scores by school spending did not change after cleaning up the data.

### Scores by School Size
**Original**
![scores_by_size_original](https://user-images.githubusercontent.com/79174885/111884165-298ae400-8996-11eb-99c8-76ff3c95f9ee.png)

**Clean**


The average scores by school size did not change after cleaning up the data.

### Scores by School Type
**Original**
![scores_by_school_type_original](https://user-images.githubusercontent.com/79174885/111884173-3f000e00-8996-11eb-946a-4b511b0274bd.png)

**Clean**
![scores_by_school_type_clean](https://user-images.githubusercontent.com/79174885/111884181-46271c00-8996-11eb-8a94-dcf8ffe0fca8.png)

The average scores by school type did not change after cleaning up the data.

## Summary
The board might be interested to know about the 4 major changes we did find in the cleaned up school district analysis. 

