## Week 7 Quiz Questions and Answers

In order to prepare your Week 7 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-7" in your fork of this repo. Then, after all edits have been made/committed, your Week 7 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-7 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 10, Problem 2]
- Question (ttruong59-stat6250): Does the variable labeled and formatted in the PROC PRINT output affect how the data is stored in the dataset?
- Answer (ttruong59-stat6250): No, they do not. These labels and formats just appears in the output.



[Course Textbook Chapter 10, Problem 6]
- Question (ttruong59-stat6250): When using IF-THEN statement, are the character values case-sensitive?



[Course Textbook Chapter 10, Problem 7]
- Question (ttruong59-stat6250): How do users determine the length of a new variable once IF-THEN and ELSE statement were added to a DATA step?
- Answer (ttruong59-stat6250): Users can use a LENGTH statement to specify a length, the number of bytes, for TestLength before the first value is referenced elsewhere in the DATA step.



[Course Textbook Chapter 10, Problem 8]
- Question (ttruong59-stat6250): Are there any limits in term of using ELSE statement to specify a series of mutually exclusive conditions?



[Course Textbook Chapter 10, Problem 9]
- Question (ttruong59-stat6250): Should the LENGTH statement appear before or after the reference to the variable in the DATA step?
- Answer (ttruong59-stat6250): The LENGTH statement must appear before any other reference to the variable.



[Course Textbook Chapter 10, Problem 10]
- Question (ttruong59-stat6250): What is a major reason users cannot use DROP or KEEP statements in PROC steps?



[Course Textbook Chapter 11, Problem 1]
- Question (ttruong59-stat6250): Instead of using DROP= and KEEP= data set option in the DATA statements, why don't we use SELECT statements conditionally?



[Course Textbook Chapter 11, Problem 2]
- Question (ttruong59-stat6250): For this problem, the variables Age, Weight, and Group are specified using the KEEP= option in the SET statement. And after processing, Age and Group are dropped in the DATA statement. The question is what happens if we are going to change (KEEP=product units price ordrtime) to (DROP=product units price ordrtime) in the SET statement?



[Course Textbook Chapter 11, Problem 3]
- Question (ttruong59-stat6250): When using BY- group processing, the DATA steps create 2 temp variables for each BY variable: FIRST. variable and LAST.variable, and their values are either 1 or 0. Are these variables stored in the data set?



[Course Textbook Chapter 11, Problem 8]
- Question (ttruong59-stat6250): For this problem, what does “if last;" condition mean? And what does exactly “if last;" do in this program?



[Course Textbook Chapter 11, Problem 9]
- Question (ttruong59-stat6250): At the start of DATA step processing, are there any observations set during a compilation phase?
- Answer (ttruong59-stat6250): There are no observations set during a compilation phase since DATA step was not executed.



[basic_recipe_for_combining_data_vertically Week 7 Recipe]
- Question (ttruong59-stat6250): When combining 2 datasets vertically, what happens if one dataset mentioned in the DATA= option has more variables than the other?



[adv_recipe_for_combining_data_vertically Week 7 Recipe]
- Question (ttruong59-stat6250): Data exists in 2 datasets to be combined vertically, what happens if the variables have the same name but different types?


