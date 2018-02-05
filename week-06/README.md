## Week 6 Quiz Questions and Answers

In order to prepare your Week 6 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-6" in your fork of this repo. Then, after all edits have been made/committed, your Week 6 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-6 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 12, Problem 1]
- *Question* (aamiri2-stat6250): Is it possible to combine two datasets with the goal of merging variables to match ID or observation numbers?
- *Answer* (aamiri2-stat6250):This is possible, there are many situations where there are multiple variables associated with one ID. Foremost, it is important that any dataset you want to combine should both have matching ID's. You can then combine the first dataset with the second dataset where you will have one ID column and various variables that were in both datasets.



[Course Textbook Chapter 12, Problem 2]
- *Question* (aamiri2-stat6250): What are the differences between one-to-one merging, concatenating, and appending when combining datasets?
- *Answer* (aamiri2-stat6250): The method of one-to-one merging creates observations that contain all of the variable from each dataset and combines the observations based on their position in each data set. The method of concatenating appends the observations from one dataset to another. The method of appending adds the observations in the second dataset to the end of the original dataset.



[Course Textbook Chapter 12, Problem 3]
- *Question* (aamiri2-stat6250): When combining a dataset using DATA CONCAT and all variables and observations are combined, what happens if there is missing data?



[Course Textbook Chapter 12, Problem 4]
- *Question* (aamiri2-stat6250): What is the difference between PROC APPEND and DATA CONCAT when combining datasets?



[Course Textbook Chapter 12, Problem 5]
- *Question* (aamiri2-stat6250): When combining a dataset, can you combine data based on a variable instead of an observation or ID number? 



[Course Textbook Chapter 12, Problem 7]
- *Question* (aamiri2-stat6250): What can be done to prevent a variable from being overwritten when merging two datasets?
- *Answer* (aamiri2-stat6250): To prevent overwriting, you can rename variables by using the RENAME= option in the MERGE statement. Then the old variable and new variable name must be stated to ensure your data does not get overwritten.



[Course Textbook Chapter 12, Problem 9]
- *Question* (aamiri2-stat6250): How can you exclude unmatched observation data when combining  a dataset? Does this cause any discrepancies in the final combined dataset?



[basic_recipe_for_combining_data_horizontally Week 6 Recipe]
- *Question* (aamiri2-stat6250): Does MERGE statements and BY statements need to be used conjointly? 



[adv_recipe_for_combining_data_horizontally Week 6 Recipe]
- *Question* (aamiri2-stat6250): What is the benefit of using PROC SQL when combining datasets? Where can we learn more about PROC SQL for self-study?


