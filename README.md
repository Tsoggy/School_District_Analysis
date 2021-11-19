# School District Analysis

## Challenge 4: Python + Pandas

### Overview
##### Data
For this assignment, we are combining the data from two .csv data sources:
1. Student Data: this data includes student names, the school that they attend, their grade level, and test scores on the math and reading exam,
2. School Data: this data includes the school name, type of school (district or charter), and budget.

##### Purpose
Our challenge has two purposes:
1. The intent of our original analysis is to compare student performance between each school and include factors such as grade level, type of school, and spending per student,
2. The intent of our challenge analysis is to remove 9th grade math and reading exam scores, as they are corrupted. As such, our student performance determination from the original analysis is impacted.

##### Methods
To analyze our data, we:
  - Combine the data into a single dataset,
  - Clean the data,
  - Determine average math and reading exam scores by school,
  - Determine passing rate percentages at each school,
  - Determine the per capita spending by dividing each school's budget by the number of students,
  - Determine school achievement based on passing exam percentages, and compare achievement,
  - Remove the 9th grade reading and math grades and compare achievement with and without those grades.

### Results

##### Impacts of removing the 9th graders' math and reading scores
  - The district summary is not greatly impacted by removing the 9th graders' math and reading scores.

For this part of the Challenge, write a report that summarizes your updated analysis and compares it with the results from the module.

The analysis should contain the following:

Overview of the school district analysis: Explain the purpose of this analysis.

Results: Using bulleted lists and images of DataFrames as support, address the following questions.

How is the district summary affected?
How is the school summary affected?
How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade
Scores by school spending
Scores by school size
Scores by school type
Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.


Results:

There is a bulleted list that addresses how each of the seven school district metrics was affected by the changes in the data (10 pt).
Summary:

There is a statement summarizing four changes to the school district analysis after reading and math scores have been replaced (5 pt).
