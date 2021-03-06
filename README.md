# School District Analysis
## Overview of Project
The education system and the value it can provide for students is crucial to their success.  Our job was to assist Maria, the Chief Data Scientist for the school district, by analyzing data from multiple sources indicating the performance of students and school budgets.  We will analyze both performance and budget by using student math and reading scores and student funding data to find trends.  This information is essential when making changes and decisions for the education system at a wide-level. 

We will improve our coding skills by importing the Pandas library within the Jupyter notebook.  Using Jupyter notebook and Pandas allows us to deeply analyze our data as specific as needed to indicate major trends.  As they were interested specifically in Thomas High School and whether their scores were altered, we will uncover how these altered scores affect the results of the entire analysis for the school district.

## Results
Deliverable 1 required us to replace all the altered 9th grade scores with NaN values so that it would not affect the entire school district analysis.  We were instructed to use the loc method in other to filter and replace the values to NaN. 

Once the altered values were replaced, I was able to compare the prior results without the replaced values and infer the percentage of change of the analysis before and after we updated our data. The difference between the intial analysis and the updated analysis of the district summary was minimal. The overall percent of students who passed only varied by 0.1%.  The average reading score and average math scores both decreased by percentages lying within 0.1-0.3%.  

In regards to the school summary, the data frame shows only Thomas High School was affected in the updated analysis.  The updated analysis shows that the percentage of Thomas High Students who passed math dropped from 93.272171% down to 66.911315% and the percentage who passed reading also dropped from 97.308869% to 69.663609%. Below you may view the updated analysis.

![alt text](https://github.com/nataliabench/School_District_Analysis/blob/85a8ab67084758700ce3e7d6452b52bed789fdca/Updated_School_Districts.png)

More specific changes we saw when we replaced the values was an overall decrease in math and reading scores.  Also, the percentage of overall students who passed decreased to 63% from the initial 79% within the $630-644 spending range. Another change we noticed in the updated analysis was a 6% decrease in the overall students passing within the medium size bracket. As for school types, the District Schools experienced a 20% decrease in overall students passing.

## Summary
In conclusion, four major changes are inferred from the data in the updated analysis after we replaced the 9th grader scores with NaNs.
1.  The spending ranges per student do not impact math and reading scores.
2.  The size of schools impact testing scores; we were able to correlate that as the school was larger, the lower the test scores and overall percentage of students passing.
3.  Charter Schools have a higher performance compared to District Schools.  Charter Schools had higher testing scores and percentage of overall students passing.
4.  NaN is an effective method compared to having to enter a value of zero to fix the inconsistencies.
