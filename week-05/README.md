## Week 5 Quiz Questions and Answers

In order to prepare your Week 5 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-5" in your fork of this repo. Then, after all edits have been made/committed, your Week 5 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-5 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 5, Problem 1]
- Question (ttruong59-stat6250): What is a major difference between LIBNAME and FILENAME statement?
- Answer (ttruong59-stat6250): We can use a LIBNAME statement to reference a SAS library while a FILENAME statement is used to reference an external file that contains the data.



[Course Textbook Chapter 5, Problem 2]
- Question (ttruong59-stat6250): What are fileref’s functions? And when are filerefs no longer effect in SAS session? 
- Answer (ttruong59-stat6250):  Filerefs perform the same function as librefs in where they temporarily point to a storage location for the data, but filerefs reference external data only. Filerefs are no longer in effect when users change, cancel them or SAS session was ended.



[Course Textbook Chapter 5, Problem 6]
- Question (ttruong59-stat6250): How to use INPUT statement correctly?
- Answer (ttruong59-stat6250): INPUT statement reads raw data in external files or data lines so users need to specify the variable name exactly as they appear in the dataset.



[Course Textbook Chapter 5, Problem 7]
- Question (ttruong59-stat6250): Why is a $ sign used in a INPUT statement?
- Answer (ttruong59-stat6250): Once we specify the variable name in a INPUT statement, $ sign is used to identify character variables. 



[Course Textbook Chapter 5, Problem 8]
- Question (ttruong59-stat6250): When does a user need to redefine the values of the variables? Is there any difference in term of redefining the values of the variable and creating a new variables?



[Course Textbook Chapter 6, Problem 1]
- Question (ttruong59-stat6250): What does SAS create during the compilation phase?
- Answer (ttruong59-stat6250): During the compilation phase SAS creates 3 items: input buffer, program data vector, and descriptor information.



[Course Textbook Chapter 6, Problem 2]
- Question (ttruong59-stat6250): What are the most common syntax errors users often encounter?
- Answer (ttruong59-stat6250): Syntax error can detect the following errors as invalid options or variables, missing or invalid punctuation, missing or misspelled keywords. However it can't verify the values of variables or its format.



[Course Textbook Chapter 6, Problem 3]
- Question (ttruong59-stat6250): Is it possible DATA step execute more than each record in the input file?



[Course Textbook Chapter 6, Problem 4]
- Question (ttruong59-stat6250): What are the missing values set to at the beginning of the execution phase?
- Answer (ttruong59-stat6250): Missing numeric values are set to periods, and missing character values are presented by blanks.



[Course Textbook Chapter 6, Problem 5]
- Question (ttruong59-stat6250): What is the value of _ERROR_ set to if there is more than one DATA error?
- Answer (ttruong59-stat6250): By default, the value of _ERROR_ is 0, and the value will be set to 1 when multiple errors occurred.



[Course Textbook Chapter 6, Problem 6]
- Question (ttruong59-stat6250): At the beginning of an iteration of the DATA step, why is the automatic variable _ERROR_ reset to 0 if necessary? What is a significant reason to reset it to 0 again?



[basic_recipe_for_creating_analytic_datasets Week 5 Recipe]
- Question (ttruong59-stat6250): Should users overwrite retain and keep statement to list more columns in the output when the statements were processed and executed or should users create a new statement for this purpose? Which method is more preferable?



[adv_recipe_for_creating_analytic_datasets Week 5 Recipe]
- Question (ttruong59-stat6250): What is a major difference of using retain/keep statement and proc sql statement? Which method is more preferable in term of using SAS?





