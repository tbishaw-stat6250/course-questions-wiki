## Week 5 Quiz Questions and Answers

In order to prepare your Week 5 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-5" in your fork of this repo. Then, after all edits have been made/committed, your Week 5 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-5 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 5, Problem 1]
- *Question* (cnguyen77-stat6250): Which SAS statement can be used to reference an external file?
- *Answer* (cnguyen77-stat6250): You assign a fileref by using a FILENAME statement in the same way that you assign a libref by using a LIBNAME statement.


[Course Textbook Chapter 5, Problem 2]
- *Question* (cnguyen77-stat6250): When does fileref remain in effect?
- *Answer* (cnguyen77-stat6250): Like LIBNAME statements, FILENAME statements are global; they remain in effect until you change them, cancel them, or end your SAS session.


[Course Textbook Chapter 5, Problem 6]
- *Question* (cnguyen77-stat6250): What does the dollar sign ($) in INPUT statement mean?
- *Answer* (cnguyen77-stat6250): The dollar sign ($) identifies the variable type as character (if the variable is numeric, then nothing appears here).


[Course Textbook Chapter 5, Problem 7]
- *Question* (cnguyen77-stat6250): Is it necessary to read fields in an order when using column input?
- *Answer* (cnguyen77-stat6250): You can use column input to read fields in any order. You must specify the variable name, identify character variables with a $, and specify the correct starting and ending column for each field.


[Course Textbook Chapter 5, Problem 8]
- *Question* (cnguyen77-stat6250): How to re-define the values of a variable in an assignment statement?
- *Answer* (cnguyen77-stat6250): To re-define the values of a variable in an assignment statement, you specify the variable name on the left side of the equal sign and an appropriate expression including the variable name on the right side of the equal sign.


[Course Textbook Chapter 6, Problem 1]
- *Question* (cnguyen77-stat6250): When is the descriptor of the new SAS data set created?
- *Answer* (cnguyen77-stat6250): The descriptor portion of the new SAS data set is created at the end of the compilation phase. The descriptor portion includes the name of the data set, the number of observations and variables, and the names and attributes of the variables. Observations are not written until the execution phase.


[Course Textbook Chapter 6, Problem 2]
- *Question* (cnguyen77-stat6250): What are the common errors that a syntax checking can identify?
- *Answer* (cnguyen77-stat6250): Syntax checking can detect many common errors including invalid options or variable names, missing or invalid punctuation, missing or misspelled keywords. However, it cannot verify the values of variables or the correctness of formats.


[Course Textbook Chapter 6, Problem 3]
- *Question* (cnguyen77-stat6250): When are records in the input raw data file written to the new data set as observations?
- *Answer* (cnguyen77-stat6250): During execution, each record in the input raw data file is read into the input buffer, copied to the program data vector, and then written to the new data set as an observation. The DATA step executes once for each record in the input file, unless otherwise directed by additional statements.


[Course Textbook Chapter 6, Problem 4]
- *Question* (cnguyen77-stat6250): What are the values of the remaining variables set to at the beginning of the execution phase?
- *Answer* (cnguyen77-stat6250): The remaining variables are initialized to missing. Missing numeric values are represented by periods, and missing character values are represented by blanks.


[Course Textbook Chapter 6, Problem 5]
- *Question* (cnguyen77-stat6250): What is the value of the automatic variable_ERROR_ when multiple errors occur?
- *Answer* (cnguyen77-stat6250): The default value of _ERROR_ is 0, which means there is no data error. When an error occurs, whether one error or multiple errors, the value is set to 1.


[Course Textbook Chapter 6, Problem 6]
- *Question* (cnguyen77-stat6250): What happens at the beginning of an iteration of the DATA step?


[basic_recipe_for_creating_analytic_datasets Week 5 Recipe]
- *Question* (cnguyen77-stat6250): What is the difference between retain and keep statements?


[adv_recipe_for_creating_analytic_datasets Week 5 Recipe]
- *Question* (cnguyen77-stat6250): What are the pros of using Proc sql in SAS?
