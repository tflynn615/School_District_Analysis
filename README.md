# School_District_Analysis

## Overview

The purpose of this project was to analyze the overall passing rate of students in Py City High Schools categorized by the type of school and their spending per student. 

## Results

After an initial analysis of the schools' passing rates, it was found that there was some cheating in the 9th grade class of Thomas High School throwing some of the data into question. As a result, all of their reading and math scores were removed from the data. This resulted in the following changes to the analysis: 

- After removing the 9th grade scores, Thomas High School still ranks as the second highest performing school in the district as their Overall Passing Percentage only lowered from 90.95 to 90.63 as a result of high passing scores in the upperclass grades. The lowest performing schools remain unchanged. Since the Overall Passing Percentage is calculated using the math and reading passing populations, this is a great metric to see how changes in both these areas reflect the end result. 
- When creating tables to compare average scores of both reading and math across the high schools, only the Thomas High School returns a NaN in the 9th grade column. Otherwise, it can be seen that the 10th, 11th, and 12th graders skew to the higher end of average scores in the mid 80's, while many other schools have average scores in the 70's or low 80's. These numbers correlate with the high number of students passing as seen in the above metric. 
- When we look at the spending bins for each school, Thomas falls into the mid-range spending per student in the $630 to $644 bin along with three other schools. The spending per student does not change here after removing the 9th grade scores because the student population was adjusted to remove them from the calculation and gives us the same ratio. 
- Looking at the average scores per spending range, we can see that removing the suspicious Thomas scores has not had a large effect on the calculations as the numbers differ by less than a percent (e.g. overall passing was 62.857% but changes to 62.778% after the adjustment). This difference is lost when the numbers are rounded to a whole number. 
- The next metric was to evaluate schools by size. Again the Medium sized schools see a small adjustment in their numbers as evidenced in the overall passing rate changing from 90.62% to 90.55% once the errant scores no longer contribute. 
- When evaluating the passing rates based on school type, District Schools' numbers remain unchanged while Charter Schools' overall rate falls from 90.43% to 90.39%. The change is negligible enough that the end result appears the same once the numbers are rounded to the nearest whole number. 


## Summary:

In summary, it is important to remove the suspicious scores to avoid any over reporting of the results of the school in order to have the most accurate picture of indicators for teaching success. However, the population of 9th graders at Thomas High was small enough that the changes to the analysis were negligible thus upholding the confidence in the results of this project assuming that students in higher grades of Thomas High School were not also party to scholastic dishonesty. 
