# School_District_Analysis
Module 4 including work with Anaconda, Jupyter Labs, Python
<!---There is a title, and there are multiple sections (2 pt).
<!---Each section has a heading and subheading (3 pt).
<!---Links to images are working, and code is formatted and displayed correctly (2 pt).
<!---Analysis (18 points)
<!---The written analysis has the following:--->

<!---Overview of the school district analysis:
The purpose of this analysis is well defined (3 pt).--->
## Overview
For this challenge, the task was to utilize Anaconda, Jupyter Labs Notebook, and Python to perform an analysis of two separate datasets consisting of:
- School data (16 rows)
- Student data (39,171 rows)

During coursework exercise, this data would be summarized into dataframes according to:
- passing reading, math, and overall scores (>= 70) in terms of count and percentage
- binned grouping analysis by school type, spending per student, and school size

During challenge portion of the exercise, it was given 9th grade scores for a specific school (Thomas High School) were altered.  To address, challenge was to remove 9th grade reading & math scores from the data for all schools, repeat analysis performed during coursework exercise, and compare difference in summary.

<!---Results:
There is a bulleted list that addresses how each of the seven school district metrics was affected by the changes in the data (10 pt).--->
## Results
Identification & highlight of differences as a result of setting Thomas High School 9th grade reading & math scores to "NaN".

For District Summary:
- Average Math Score reduced by 0.1
- % Passing Math reduced by 0.2%
- % Passing Reading reduced by 0.1%
- % Overall Passing reduced by 0.3%
![district_summary_df_comparison](/resources/district_summary_df_comparison.PNG)

For Per School Summary & Thomas High School specifically:
- Average Math Score change from 83.418 to 83.351
- Average Reading Score change from 83.849 to 83.896
- % Passing Math change from 93.272% to 93.186%
- % Passing Reading from 97.309% to 97.019%
- % Overall Passing from 90.948% to 90.630%
![per_school_summary_df_comparison](/resources/per_school_summary_df_comparison.PNG)

For Per School Ranking, Thomas High School experienced no change in ranking based on Overall Passing % despite the change in Overall Passing % due to removal of 9th grade scores.
![TOP_per_school_summary_df_comparison](/resources/TOP_per_school_summary_df_comparison.PNG)

![scores_by_grade_comparison](/resources/scores_by_grade_comparison.PNG)

![comparison_by_spending-size-type](/resources/comparison_by_spending-size-type.PNG)


<!---Summary:
There is a statement summarizing four major changes to the school district analysis after reading and math scores have been replaced (5 pt).--->
## Summary



