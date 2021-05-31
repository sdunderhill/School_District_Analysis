# School_District_Analysis
PyCity with Pandas and Jupyter

## Overview

In the module we analyzed the data from each school. We looked at reading and math test scores from each grade level at each school. After we had looked at all the data it was realized that the 9th grade scores at Thomas High School were altered. Knowing that information, that data had to be recallibrated with that in mind. I had to set the Thomas High School 9th grade test scores to null and refactor the code to give scores based on that adjusted data.

## Results

* **Total School Budget** - was unaffected. Every schools budget stayed the same.
* **Per Student Budget** - unaffected. The per student budget for each school stayed the same.
* **Average Math Score** - the only affected school was Thomas High School. With removing the 9th grade scores their average math score decreased by 0.05% but that didn't change their placement as 2nd in the Overall Percent passing.
* **Average Reading Score** - again, only Thomas High School was affected with a 0.05% drop in their average reading score. That didn't change their placement either.
* **Percent Passing Math** - Thomas High School's percent passing math dropped 0.1%. Their placement in the top schools was unaffected.
* **Percent Passing Reading** - Thomas High School's percent passing math dropped 0.3%. Their placement in the top schools was unaffected.
* **Percent Overall Passing** - Thomas High School's percent overall passing dropped by 0.3%. Their placement in the top schools was unaffected.

## Summary

Thomas High School's data did lower after removing the 9th grade scores. The scores that were affected are: Average Math Score, Average Reading Score, Percent Passing Math, Percent passing Reading, and the overall percent passing. However, it didn't produce a significant change. The district summary's and order by percent overall passing were unaffected by the drops.
