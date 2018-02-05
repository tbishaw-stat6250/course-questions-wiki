In order to prepare your Week 6 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-6" in your fork of this repo. Then, after all edits have been made/committed, your Week 6 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-6 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 12, Problem 1]
- *Question* (ldai4-stat6250): How many methods can be used to combine observations from two or more data sets into a new data set?
- *Answer* (ldai4-stat6250): There are one-to one merging, concatenating, appending, interleaving, and match-merging.



[Course Textbook Chapter 12, Problem 2]
- *Question* (ldai4-stat6250): What is interleaving method for combining observations from two or more data sets?
- *Answer* (ldai4-stat6250): The interleaving method requires a list of data set names in the SET statement and one or more BY variables in BY statement. Notice that observations in each BY group are read sequentially, in the order in which that data sets and BY variable are listed. The new data set contains all the variable from all the input data sets.



[Course Textbook Chapter 12, Problem 3]
- *Question* (ldai4-stat6250): In the concatenating append method, does the append statement need to be used?



[Course Textbook Chapter 12, Problem 4]
- *Question* (ldai4-stat6250): Does the new data set contain all of the variables and observations from all of the input data sets when a program concatenates data sets?



[Course Textbook Chapter 12, Problem 5]
- *Question* (ldai4-stat6250): What happens if we merge the two data sets which have same name variables?



[Course Textbook Chapter 12, Problem 7]
- *Question* (ldai4-stat6250): How can we prevent the variables with same names from being overwritten during merging the two datasets?
- *Answer* (ldai4-stat6250): We can use RENAME=data set option in the MERGE statement to
prevent from be overwritten.



[Course Textbook Chapter 12, Problem 9]
- *Question* (ldai4-stat6250): During match-merging, can we select the observations that we need?



[basic_recipe_for_combining_data_horizontally Week 6 Recipe]
- *Question* (ldai4-stat6250): In using MERGE statement, how can we create the descending order?



[adv_recipe_for_combining_data_horizontally Week 6 Recipe]
- *Question* (ldai4-stat6250):  How can we select only observation that match for some specific input data sets in match-merging statement? For example, I want to select some observations which appear in both data files.



