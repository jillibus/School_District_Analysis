## School District Analysis
 
## Overview
Maria, the Chief Data Scientist of the City's School District, has tasked me to analyize data on the School District in the area high schools for their Standardized Testing, in these categories:
1.  Overall District Summary
  * Total Number of Schools
  * Total Number of Students
  * Total District Budget
  * Average Math Scores
  * Average Reading Scores
  * % Students Passing Math
  * % Students Passing Reading
  * % Students Passing Math & Reading
2. The second set of analysis, I will perform, on this data, is a breakdown of each of these categories:
  * Per School
  * Per Size ( Small, Medium, Large )
  * Per Budget ( broken down per student )
  * Per Type ( Charter or District )
  * Per Avg Math Scores
  * Per Avg Reading Scores
  * Show you the top 5 schools by their Avg Math and Reading Scores
  * Show you the bottom 5 schools by their Avg Math and Reading Scores
  * Show you the Avg Math and Avg Reading by School, by Grade

## Resources
* Data Source: schools_complete.csv, students_complete.csv
* Software: Python 3.7.10, Jupyter Notebook 6.3.0 

## Results
First I will address, is the issue of Thomas High School's 9th Grade test scores.  All of my analysis has been done with Thomas High School's 9th grade's standardized test scores marked as NaN, in the charts you will see below.  In all mathmatical equations it is treated as zero.

First, obviously making all of the math and reading scores of entire grade of a medium sized school, will definitely make an impact. The School District isn't that small so the impact overall wasn't felt by the other schools.  With standard formatting and rounding rules, you would have to look a bit closer to see the difference, but it is there.  I will break it down in the individual areas.

![District Summary]('resources/f_district_summary.png')
### How is the district summary affected by the change in data? 
_Answer:_ Removing the scores for the 9th grade reading and math, overall the District Summary faired very well, again with rounding to the tenth place you will hardly notice the change.  The first 4 areas wouldn't change, and the % Overall Passing was affected 1%.
* Average Math went down 0.07%
* Average Reading went down 0.03%
* % Passing Math went down 0.29%
* % Passing Reading went down 0.17%
* % Overall Passing went down 1.32%

![School Summary]('resources/f_per_school_summary.png')
### How is the school summary affected by this change?
* Average Math went down 0.07%
* Average Reading went down 0.03%
* % Passing Math went down 0.29%
* % Passing Reading went down 0.17%
* % Overall Passing went down 1.32%

![School Summary]('resources/f_spending_summary.png')
#### Difference in School Summary by Spending
* Average Math went down 0.02%
* Average Reading went up 0.01%
* % Passing Math went down 0.03%
* % Passing Reading went down 0.09%
* % Overall Passing went down 0.13%

![School Summary]('resources/f_size_summary.png')
#### Difference in School Summary by Size (Small, Medium, Large)
* Average Math went down 0.02%
* Average Reading went up 0.01%
* % Passing Math went up 0.02%
* % Passing Reading went down 0.06%
* % Overall Passing went down 0.07%

![School Summary]('resources/f_type_summary.png')
#### Difference in School Summary by Type (Charter and District)
* Average Math went down 0.01%
* Average Reading went up 0.01%
* % Passing Math went down 0.01%
* % Passing Reading went up 0.04%
* % Overall Passing went down 0.08%
