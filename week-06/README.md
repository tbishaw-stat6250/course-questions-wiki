## Week 6 Quiz Questions and Answers

In order to prepare your Week 6 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-6" in your fork of this repo. Then, after all edits have been made/committed, your Week 6 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-6 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 12, Problem 1]
- Question (ttruong59-stat6250): What happen if the data sets contain variables that have the same names in term of One-to-One Reading?
- Answer (ttruong59-stat6250): The value that are read from the last data set overwrite the values that were read from earlier data sets.



[Course Textbook Chapter 12, Problem 2]
- Question (ttruong59-stat6250): According to the textbook, the result is interleaving if you use a BY statement when users concatenate data sets. What if users do not include a BY statement? Is it still considered as interleaving?



[Course Textbook Chapter 12, Problem 3]
- Question (ttruong59-stat6250): What does concatenating datasets mean?
- Answer (ttruong59-stat6250): Concatenating datasets means stacking one dataset on top of the other. For example, given two datasets, records from the second dataset will be added to the end of the first one.



[Course Textbook Chapter 12, Problem 4]
- Question (ttruong59-stat6250): I see the correct answer from the textbook for problem 4 is “a” that means “missing" or the second observation in Sales.Rep does not contain a value for Sale, so a missing value appears for this variable. What about the first observation? Does a missing value appear for this variable as well?



[Course Textbook Chapter 12, Problem 5]
- Question (ttruong59-stat6250): What is a mechanism of SAS when users merge the datasets but have variables with the same name in more than one input dataset?
- Answer (ttruong59-stat6250): Values of the same name variable in the second dataset will overwrite the values of the first one.



[Course Textbook Chapter 12, Problem 7]
- Question (ttruong59-stat6250): What is a main reason users have to prevent the values of the variable from overwritten when merging two datasets that have a same-named variable?



[Course Textbook Chapter 12, Problem 9]
- Question (ttruong59-stat6250): How does the DATA step perform or process match-merges? What happen if observations do not match?



[basic_recipe_for_combining_data_horizontally Week 6 Recipe]
- Question (ttruong59-stat6250): When combining data horizontally by using a recipe per provided, is it possible to merge two columns with the same names but they have different variable attributes? 



[adv_recipe_for_combining_data_horizontally Week 6 Recipe]
- Question (ttruong59-stat6250): What is a disadvantage of using proc sql?
- Answer (ttruong59-stat6250):proc sql loads all the data into memory before joining so the process will take longer to create join datasets if the datasets are large but there is no issue as long as the data are small enough to fit in memory.


