## Week 5 Quiz Questions and Answers

In order to prepare your Week 5 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-5" in your fork of this repo. Then, after all edits have been made/committed, your Week 5 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-5 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 5, Problem 1]
- Question (ldeng11−stat6250): When you refrencing a raw data file, you use the absulut file path, what you need to do if the raw data file is not saved in your local machine?



[Course Textbook Chapter 5, Problem 2]
- Question (ldeng11−stat6250): What do the LIBNAME and FILENAME statements are global mean?
- Answer (ldeng11−stat6250): It means once the program excuted these statements, they are remain effect until you change them, cancel them, or end your SAS session.


[Course Textbook Chapter 5, Problem 6]
- Question (ldeng11−stat6250): What is $ mean in the INPUT statement?
- Answer (ldeng11−stat6250): The dollar sign ($) identify the variable type as character; if the variable is numeric, then you don't need to anything.

[Course Textbook Chapter 5, Problem 7]
- Question (ldeng11−stat6250): What you need to do if you want to read the raw data in your own order, not follow the order saved in the raw data file?


[Course Textbook Chapter 5, Problem 8]
- Question (ldeng11−stat6250): How do you correctly use the operators in SAS expression?


[Course Textbook Chapter 6, Problem 1]
- Question (ldeng11−stat6250): What will happen during the compilation phase?


[Course Textbook Chapter 6, Problem 2]
- Question (ldeng11−stat6250): What are the syntax errors?


[Course Textbook Chapter 6, Problem 3]
- Question (ldeng11−stat6250): During the execution phase, how the DATA step works?


[Course Textbook Chapter 6, Problem 4]
- Question (ldeng11−stat6250): At the beginning of the execution phase, why the value of _N_ is 1, the value of _ERROR_ is 0, and what are the values of the remaining variables?
- Answer (ldeng11−stat6250): Because at the beginning of the execution phase, we are reading the first observation, and there is no error sofar, so the value of _N_ is 1, the value of _ERROR_ is 0, and the values of the remainning variables are setting to missing.

[Course Textbook Chapter 6, Problem 5]
- Question (ldeng11−stat6250): What is the value of _ERROR_ if you have three errors? 


[Course Textbook Chapter 6, Problem 6]
- Question (ldeng11−stat6250): What will happen during the DATA step?


[basic_recipe_for_creating_analytic_datasets Week 5 Recipe]
- Question (ldeng11−stat6250): What is the difference between retain and keep staments?


[adv_recipe_for_creating_analytic_datasets Week 5 Recipe]
- Question (ldeng11−stat6250): What are the advantages and the disadvantages when using PROC SQL?

