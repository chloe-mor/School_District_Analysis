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
**Original**

![top_original](https://user-images.githubusercontent.com/79174885/111884457-2264d580-8998-11eb-83b2-85267f20fcc8.png)

**Clean**

![top_clean](https://user-images.githubusercontent.com/79174885/111884459-298be380-8998-11eb-97e1-8c3fb9c73393.png)

When it comparing Thomas HS to the other schools in the city, the change in data has no impact on the school's ranking. After removing the ninth graders scores, Thomas HS is still ranked second in PyCity for percentage of students passing both math and reading.

### Scores by Grade
**Original**

![math_original](https://user-images.githubusercontent.com/79174885/111884475-432d2b00-8998-11eb-9769-949965e66357.png)![reading_original](https://user-images.githubusercontent.com/79174885/111884480-488a7580-8998-11eb-8ec6-5ea4270154d0.png)

**Clean**

![math_clean](https://user-images.githubusercontent.com/79174885/111884482-4fb18380-8998-11eb-8726-b22c9b652855.png)![reading_clean](https://user-images.githubusercontent.com/79174885/111884489-53dda100-8998-11eb-890c-c8b8a1a32270.png)

The average math and reading scores by grade for each school only changed for ninth graders at Thomas High School. No other averages were impacted by the clean data.

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

![scores_by_size_clean](https://user-images.githubusercontent.com/79174885/111884299-217f7400-8997-11eb-9475-0cf5cf4bed3a.png)

The average scores by school size did not change after cleaning up the data.

### Scores by School Type
**Original**

![scores_by_school_type_original](https://user-images.githubusercontent.com/79174885/111884173-3f000e00-8996-11eb-946a-4b511b0274bd.png)

**Clean**

![scores_by_school_type_clean](https://user-images.githubusercontent.com/79174885/111884181-46271c00-8996-11eb-8a94-dcf8ffe0fca8.png)

The average scores by school type did not change after cleaning up the data.

## Summary
Overall, there weren't major differences between the original analysis and the cleaned up version. There were a few changes when we compared original analysis --> clean analysis for Thomas High School. The small differences are listed below.

**Average Math Score**: 83.418 --> 83.351

**Average Reading Score**: 83.849 --> 83.896

**% Passing Math**: 93.272 --> 93.186

**% Passing Reading**: 97.309 --> 97.019

**% Overall Passing**: 90.948 --> 90.630


