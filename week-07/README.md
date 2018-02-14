## Week 7 Quiz Questions and Answers

In order to prepare your Week 7 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-7" in your fork of this repo. Then, after all edits have been made/committed, your Week 7 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-7 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 10, Problem 2]
- *Question* (ldai4-stat6250): Does the temporary labels or format that are assigned in a PROC step override permanent labels or formats that are assigned in DATA step?



[Course Textbook Chapter 10, Problem 6]
- *Question* (ldai4-stat6250): when can we use the IF-THEN statement?
- *Answer* (ldai4-stat6250):  when we need to perform an action conditionally, the IF-THEN statement should be used. The IF-then statement executes a SAS statement when the condition in the IF clause is true.



[Course Textbook Chapter 10, Problem 7]
- *Question* (ldai4-stat6250): What can the length of a new variable be determined by?
- *Answer* (ldai4-stat6250):  The length of a variable is determined by its first reference in the DATA step. When creating a new character variable, SAS allocates as many bytes of storage space as there are characters in the reference to that variable.



[Course Textbook Chapter 10, Problem 8]
- *Question* (ldai4-stat6250): Must the ELSE statement immediately follow the IF-THEN statement?



[Course Textbook Chapter 10, Problem 9]
- *Question* (ldai4-stat6250): Who can determine the length of a new variable?
- *Answer* (ldai4-stat6250):  The length of a new variable is determined by the first reference in the DATA step, not by data value.



[Course Textbook Chapter 10, Problem 10]
- *Question* (ldai4-stat6250): Can we use DROP and KEEP statement in the PROC steps?



[Course Textbook Chapter 11, Problem 1]
- *Question* (ldai4-stat6250): How is a new data set created from an existing SAS data set?



[Course Textbook Chapter 11, Problem 2]
- *Question* (ldai4-stat6250): If we need to reference a variable in the original data set, do we need to specify the variable in the DROP= option in the DATA statement?
- *Answer* (ldai4-stat6250): Yes, we should specify the variable in the DROP= or KEEP= option in the DATA statement. Otherwise, the statement that references the variable uses a missing value for the variable.



[Course Textbook Chapter 11, Problem 3]
- *Question* (ldai4-stat6250): Using the BY statement with the SET statement, does the DATA step automatically create two variables, FIRST. And LAST., for each variable in the BY statement?



[Course Textbook Chapter 11, Problem 8]
- *Question* (ldai4-stat6250): If we want to output only one observation, can we use the END= option in the SET statement?



[Course Textbook Chapter 11, Problem 9]
- *Question* (ldai4-stat6250): At the start of DATA step processing, why are there no observations?
- *Answer* (ldai4-stat6250):  At the bottom of the DATA step, the compilation phase is completed. There are no observations because the DATA step has not yet executed.



[basic_recipe_for_combining_data_vertically Week 7 Recipe]
- *Question* (ldai4-stat6250): If using the APPEND statement to combine two data sets to form a single dataset, do the two original datasets need to have same variables?



[adv_recipe_for_combining_data_vertically Week 7 Recipe]
- *Question* (ldai4-stat6250): When using INTERLV statement, does the new data set include all the variables and observations?


