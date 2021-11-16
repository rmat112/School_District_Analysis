# School_District_Analysis
## Overview of the School District Analysis

The school board received evidence of academic dishonesty, specifically from reading and math grades for Thomas High School ninth graders. In order to uphold state-testing standards, they want to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Therefore in the PyCitySchools_Challenge notebook, the suspected math and reading scores were replaced with NaNs and then the school district analysis (from PyCitySchools) was repeated. Click here to access the PyCitySchools_Challenge notebook:


## Results

Due to the 9th grade math and reading scores being disregarded, these scores were replaced with NaNs in student_data as seen in the image below.

### Effect on District Summary:

When analyzing data prior to replacing NaNs (hereon referred to as 'pre') and after replacing NaNs (hereon refrerred to as 'post'), there is no change in columns of 'Total Schools','Total Students' and 'Total Budget'. However, there is a very minor change in '% Passing math', '% Passing reading', and '% Overall passing', as seen from the images below. 


### Effect on School Summary:

Math and reading scores of all 9th graders from Thomas High School were removed and replaced with NaNs.

### Thomas High School’s (THS) performance relative to the other schools:

Pre: THS was among the top 5 schools based on performance of all grades.
Post: By removing the scores of 9th graders and still counting 9th graders in student count, there was a huge impact and THS seemed to be one of the bottom 5 performers, dropping the overall passing % from 90.95% to 65.07%.
However, when the student count was adjusted to remove the 9th graders (taking only 10th, 11th, and 12th graders into account), THS was still among the top 5 performers with overall passing% @ 90.63% .
Images showing all 3 situations discussed here are attached below.

### Effects on the following:
1. Math and reading scores by grade
Math and reading scores for 9th graders in THS were replaced with NaN. There was no other change for any other school or grade. Pre and Post images attached below.
    
2. Scores by school spending
THS is in the $630-$644 range spending bin. There is no change in any other bin. Even in this bin the impact is so minor that it is not visible when scores are formatted to the nearest tenths. Pre and Post images attached below.
    
3. Scores by school size
THS is medium sized school. The difference in Pre and Post scores is in the hundreths place, which becomes insignificant when formatted to the nearest whole number. Pre and Post images attached below.
    
4. Scores by school type
THS is a charter school. The difference in Pre and Post scores is in the tenths place, which becomes insignificant when formatted to the nearest whole number. Pre and Post images attached below.

## Summary
* District Summary: minor change in '% Passing math', '% Passing reading', and '% Overall passing'
* Still a top performing school with minor difference (tenths place) in average math/reading scores and passing percentages. If the 9th graders of THS were completely dropped from the student count, then THS would be within bottom 5 schools.
* Math and reading scores for 9th graders in THS were replaced with NaN.
* Difference in scores by school spending, school size and school type is very minor (tenths or hundreths place) and is insignificant due to rounding.
