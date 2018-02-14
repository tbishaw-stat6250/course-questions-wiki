## Week 7 Quiz Questions and Answers

In order to prepare your Week 7 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-7" in your fork of this repo. Then, after all edits have been made/committed, your Week 7 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-7 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 10, Problem 2]
- *Question* (xyin6-stat6250): What is the difference for defining variable format between DATA step and PROC step?



[Course Textbook Chapter 10, Problem 6]
- *Question* (xyin6-stat6250): Is the character values in quotation marks always case sensitive?



[Course Textbook Chapter 10, Problem 7]
- *Question* (xyin6-stat6250): Is the order of If-statements matter in terms of defining variable length?
- *Answer* (xyin6-stat6250): Yes, SAS allocates as many bytes of storage space as there are characters in the first value that it encounters of the variable. So the length of following variables are restricted by first variable length.



[Course Textbook Chapter 10, Problem 8]
- *Question* (xyin6-stat6250): When we assign values to a variable, should we use quotation marks for both numeric value and character value?


[Course Textbook Chapter 10, Problem 9]
- *Question* (xyin6-stat6250): Where should we put the LENGTH statement to specify a length?
- *Answer* (xyin6-stat6250): It should appear before any other reference to the variable in teh DATA step, otherwise of the variable has been created by another statement, the LENGTH statement will not work.

[Course Textbook Chapter 10, Problem 10]
- *Question* (xyin6-stat6250): What is the difference between DROP= data set option and DROP statement?


[Course Textbook Chapter 11, Problem 1]
- *Question* (xyin6-stat6250): Which step will be excuted first? SET statement or DATA statement?


[Course Textbook Chapter 11, Problem 2]
- *Question* (xyin6-stat6250): Does the if-statement after SET statement overwrite the dataset created in DATA statement? (subseting a new dataset)


[Course Textbook Chapter 11, Problem 3]
- *Question* (xyin6-stat6250): How to append a variable into FIRST and LAST as shown in the book example? Is it automatically created by SAS?


[Course Textbook Chapter 11, Problem 8]
- *Question* (xyin6-stat6250): Is END= option always follow the SET statement?


[Course Textbook Chapter 11, Problem 9]
- *Question* (xyin6-stat6250): How does SAS set the value of each variable when SAS reads the raw data?
- *Answer* (xyin6-stat6250): SAS sets the value of each variable in the DATA step to missing at the beginning or each iteration.


[basic_recipe_for_combining_data_vertically Week 7 Recipe]
- *Question* (xyin6-stat6250): Why we have to include "do" statement in the body before referring to each data source?


[adv_recipe_for_combining_data_vertically Week 7 Recipe]
- *Question* (xyin6-stat6250): Is "Union all corr" a necessary statement for every PROC SQL step? 

