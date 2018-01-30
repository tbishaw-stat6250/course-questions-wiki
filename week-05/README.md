## Week 5 Quiz Questions and Answers

In order to prepare your Week 5 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-5" in your fork of this repo. Then, after all edits have been made/committed, your Week 5 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-5 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************
[Course Textbook Chapter 5, Problem 1]

- *Question* (ldai4-stat6250): What is the difference for FILENAME and LIBNAME?
- *Answer* (ldai4-stat6250): FILENAME statement can be used to point to external raw file; LIBNAME is used to assign a libref.

[Course Textbook Chapter 5, Problem 2]

- *Question* (ldai4-stat6250): What is fileref? Is the function of fileref same as libref’s?

[Course Textbook Chapter 5, Problem 6]

- *Question* (ldai4-stat6250): How can we use INPUT statement?
- *Answer* (ldai4-stat6250): The INPUT statement creates a Variable using the name that we assign to each field. There, when we write an INPUT statement, we need to specify the variable names exactly as we want them to appear in the SAS dataset.

[Course Textbook Chapter 5, Problem 7]

- *Question* (ldai4-stat6250): Which variable need to add a $ before the name in using column input to read fields in any order?

[Course Textbook Chapter 5, Problem 8]

- *Question* (ldai4-stat6250): How can we re-define the value of the variable?

[Course Textbook Chapter 6, Problem 1]

- *Question* (ldai4-stat6250): How is the program data vector created during the compilation phase?
- *Answer* (ldai4-stat6250): During the compilation, the program data vector includes the two automatic variables_N_and_ERROR_. The descriptor portion of the new SAS data set is created at the end of the compilation phase. Observations are not written until the execution phase.

[Course Textbook Chapter 6, Problem 2]

- *Question* (ldai4-stat6250): What is a syntax error in SAS?

[Course Textbook Chapter 6, Problem 3]

- *Question* (ldai4-stat6250): How does the DATA step work?

[Course Textbook Chapter 6, Problem 4]

- *Question* (ldai4-stat6250): How does the DATA step execute the missing variables?
- *Answer* (ldai4-stat6250): Missing numeric values are represented by periods, and missing character values are represented by blanks.

[Course Textbook Chapter 6, Problem 5]

- *Question* (ldai4-stat6250): In program data vector, what does error 1 represent?
- *Answer* (ldai4-stat6250): Error signals are caused by the data during execution. The default value is 0, which means there is no error. When one or more errors occur, the value is set to 1.

[Course Textbook Chapter 6, Problem 6]

- *Question* (ldai4-stat6250): What action occurs at the end of the DATA step?

[basic_recipe_for_creating_analytic_datasets Week 5 Recipe]

- *Question* (ldai4-stat6250): How can we read a remote excel file in the SAS?

[adv_recipe_for_creating_analytic_datasets Week 5 Recipe]

- *Question* (ldai4-stat6250): How can we recover the right format of date for downloaded Excel file in SAS? 
