
## Week 2 Quiz Questions and Answers

In order to prepare your Week 2 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-2" in your fork of this repo. Then, after all edits have been made/committed, your Week 2 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-2 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 1, Problem 1]
- Question (xyin6-stat6250): How many observations and variables can a data set contain? How to count observations/variables?
- Answer (xyin6-stat6250): As many as you can. Typically, rows are observations and colomns are variables.

[Course Textbook Chapter 1, Problem 2]
- Question (xyin6-stat6250): How to find the point of program steps being executed in the program?
- Answer (xyin6-stat6250): "Run" and "Quit" statement mark step boundaries, at the step boundary, SAS executes any statements that have not previously being executed.

[Course Textbook Chapter 1, Problem 3]
- Question (xyin6-stat6250): How long can character variable be? Can character variables contain numbers?


[Course Textbook Chapter 1, Problem 4]
- Question (xyin6-stat6250): How to represent missing value in character and numeric variable type?
- Answer (xyin6-stat6250): A blank represents missing value in character variable, and a period represents missing value in numeric variable.

[Course Textbook Chapter 1, Problem 5]
- Question (xyin6-stat6250): What are the constrains to make a valid variable name?


[Course Textbook Chapter 1, Problem 8]
- Question (xyin6-stat6250): What is the default length for the numeric variable?


[Course Textbook Chapter 2, Problem 3]
- Question (xyin6-stat6250): Does YEARCUTOFF= option also works on 4-digits year values?
- Answer (xyin6-stat6250): No, YEARCUTOFF= option works only on 2-digits year values. As long as you specify an informat with the correct field width for reading the entire date value, the YEARCUTOFF= option doesn't affect date values that have four-digit years.

[Course Textbook Chapter 2, Problem 7]
- Question (xyin6-stat6250): What are the specification for the LIBNAME statement for files in other formats?
- Answer (xyin6-stat6250): libref is 1 to 8 characters long, begins with a letter or underscore, and contains only letters, numbers. or underscores.

[Course Textbook Chapter 2, Problem 8]
- Question (xyin6-stat6250): What is the default value of YEARCUTOFF= option and what's its range?


[Course Textbook Chapter 2, Problem 9]
- Question (xyin6-stat6250): Is LIBNAME statement required each time for every SAS session?


[basic_recipe_for_loading_data_from_remote_Excel_file Week 2 Recipe]
- Question (xyin6-stat6250): Is there a size limit for loading data from remote Excel file in a temporary location? (As many of the Excel files are very large)


[bonus_advanced_recipe_for_loading_data_from_remote_Excel_file Week 2 Recipe]
- Question (xyin6-stat6250): Why we have to put "%" percent sign before the if/then/else statement? 

