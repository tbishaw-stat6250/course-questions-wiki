## Week 6 Quiz Questions and Answers

In order to prepare your Week 6 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-6" in your fork of this repo. Then, after all edits have been made/committed, your Week 6 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-6 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 12, Problem 1]
- *Question* (cnguyen77-stat6250): In one-to-one merging, how is the number of observations of the new data set defined?
- *Answer* (cnguyen77-stat6250): In one-to-one merging, the number of observations in the new data set is the number of observations in the smallest original data set.



[Course Textbook Chapter 12, Problem 2]
- *Question* (cnguyen77-stat6250): What statements are required in Interleaving method?
- *Answer* (cnguyen77-stat6250): A list of data set names in the SET statement and one or more BY variables in the BY statement.



[Course Textbook Chapter 12, Problem 3]
- *Question* (cnguyen77-stat6250): What happens when combining two SAS data sets by using concaternating method?
- *Answer* (cnguyen77-stat6250): Concatenating appends the observations from one data set to another data set. The new data set contains all of the variables and observations from all of the input data sets.



[Course Textbook Chapter 12, Problem 4]
- *Question* (cnguyen77-stat6250): How does concatenating select data?
- *Answer* (cnguyen77-stat6250): When a program concatenates data sets, all of the observations are read from the first data set listed in the SET statement. Then all of the observations are read from the second data set listed, and so on, until all of the listed data sets have been read. The concatenated data sets are read sequentially, in the order in which they are listed in the SET statement.



[Course Textbook Chapter 12, Problem 5]
- *Question* (cnguyen77-stat6250): What happens if you merge two data sets that have variables with the same name?
- *Answer* (cnguyen77-stat6250): If you have variables with the same name in more than one input data set, values of the same-named variable in the first data set in which it appears are overwritten by values of the same-named variable in subsequent data sets.



[Course Textbook Chapter 12, Problem 7]
- *Question* (cnguyen77-stat6250): Can you keep the values of same-named variables from being overwritten when you merge the two data sets?
- *Answer* (cnguyen77-stat6250): To prevent overwriting, rename variables by using the RENAME= data set option in the MERGE statement.



[Course Textbook Chapter 12, Problem 9]
- *Question* (cnguyen77-stat6250): How does match-merging select data?



[basic_recipe_for_combining_data_horizontally Week 6 Recipe]
- *Question* (cnguyen77-stat6250): What are the functions of the merge and by statements in match-merging method?
- *Answer* (cnguyen77-stat6250): The merge statement is used to name two input datasets, and the by statement is used to name the unique id column(s), which specify how rows are to be matched up when combining the datasets.



[adv_recipe_for_combining_data_horizontally Week 6 Recipe]
- *Question* (cnguyen77-stat6250): What is the approach to merge multiple datasets with respect to a condition for matching up rows without using data steps?
