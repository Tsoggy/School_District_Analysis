# School District Analysis
## Challenge 4: Python + Pandas
### Overview
#### Data
For this assignment, we are combining the data from two .csv data sources:
1. Student Data: this data includes student names, the school that they attend, their grade level, and test scores on the math and reading exam,
2. School Data: this data includes the school name, type of school (district or charter), and budget.

#### Purpose
Our challenge has two purposes:
1. The intent of our original analysis is to compare student performance between each school and include factors such as grade level, type of school, and spending per student,
2. The intent of our challenge analysis is to remove 9th grade math and reading exam scores, as they are corrupted. As such, our student performance determination from the original analysis is impacted and we would like to be able to display how this impact changes our analysis.

#### Methods
To analyze our data, we:
  - Combine the data into a single dataset,
  - Clean the data,
  - Determine average math and reading exam scores by school,
  - Determine passing rate percentages at each school,
  - Determine the per capita spending by dividing each school's budget by the number of students,
  - Determine school achievement based on passing exam percentages, and compare achievement,
  - Remove the 9th grade reading and math grades and compare achievement with and without those grades.

### Results
#### Impacts of removing the 9th graders' math and reading scores
  - The district summary is impacted after the ninth graders' math and reading scores are removed. Once both sets of data are formatted, the results are identical, with the same amount of students in the district, the same total budget, the same average scores and passing percentages, as you can see here:

![District_Summary](Resources/District_Summary.png)
  - The school summary is very slightly impacted. When including the original ninth graders' scores, Thomas High School's average grades and percentage passing was greater by hundreds of a percent. Below, please find Thomas High School's performance with the ninth graders' scores:

![Original Ninth](Resources/Original_School_Summary.png)
Below are the updated scores for Thomas High School when the ninth graders' scores are removed:
![Updated Ninth](Resources/Updated_9th.png)
  - Replacing the ninth graders' math and reading scores doesn't affect Thomas High School's performance relative to the other schools.
  - Replacing the ninth graders' scores does not greatly affect math and reading scored by grade.
  - Replacing the ninth graders' scores does not greatly affect scores by school spending.
  - Replacing the ninth graders' scores does not greatly affect scores by school size.
  - Replacing the ninth graders' scores does not greatly affect scores by school type.

#### Four changes
When we originally replace our reading and math scores for the ninth graders at Thomas High School with NaNs, we see a remarkable difference in performance for Thomas High School. The reason for this is due to the fact that we are still calibrating the percentage of exam achievement based on the original number of students at Thomas High School, which DOES include the ninth graders. This brings all percentages down, as the ninth graders' scores count as "zero" when calibrating averages and passing performance.

The four changes that we see when the ninth graders' scores are replaced with NaNs are:
1.
2.
3.
4.

