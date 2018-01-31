## Week 5 Quiz Questions and Answers

In order to prepare your Week 5 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-5" in your fork of this repo. Then, after all edits have been made/committed, your Week 5 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-5 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 5, Problem 1]
− *Question* (xyin6-stat6250): What should be included in the DATA step in order to read the raw data file?


[Course Textbook Chapter 5, Problem 2]
− *Question* (xyin6-stat6250): When is necessary to use a LIBNAME statement?
− *Answer* (xyin6-stat6250): When we have to reference the permanent SAS library in which thedata set will be stored.


[Course Textbook Chapter 5, Problem 6]
− *Question* (xyin6-stat6250): What does the dollar sign "$" in INPUT statement stand for?
− *Answer* (xyin6-stat6250): The dollar sign identifies the variable type as character (if the variable is numeric, then nothing appears here).


[Course Textbook Chapter 5, Problem 7]
− *Question* (xyin6-stat6250): When should we use INPUT statement?
− *Answer* (xyin6-stat6250): The INPUT statement describes the fields of raw data to be read and placed into the SAS data set.


[Course Textbook Chapter 5, Problem 8]
− *Question* (xyin6-stat6250): What is the format of re-defining a variable? (numeric value)


[Course Textbook Chapter 6, Problem 1]
− *Question* (xyin6-stat6250): What is happening during the compilation phase?
− *Answer* (xyin6-stat6250): During the compilation phase, each statement is scanned for syntax
errors. Most syntax errors prevent further processing of the DATA step. When the compilation phase is complete, the descriptor portion of the new data set is created.


[Course Textbook Chapter 6, Problem 2]
− *Question* (xyin6-stat6250): What are typical types of syntax errors?


[Course Textbook Chapter 6, Problem 3]
− *Question* (xyin6-stat6250): Is the descriptor portion of the SAS data created after the program data vector being created or before?


[Course Textbook Chapter 6, Problem 4]
− *Question* (xyin6-stat6250): What statement is the next after defining the _N_ & _ERROR_ values?


[Course Textbook Chapter 6, Problem 5]
− *Question* (xyin6-stat6250): What is the value of variable _ERROR_ at the end of the DATA step?


[Course Textbook Chapter 6, Problem 6]
− *Question* (xyin6-stat6250): When reading variables from a SAS data set,does SAS sets the vaues to missing first?


[basic_recipe_for_creating_analytic_datasets Week 5 Recipe]
− *Question* (xyin6-stat6250): If the variable appears in retain, does it have to be in the keep statement?


[adv_recipe_for_creating_analytic_datasets Week 5 Recipe]
− *Question* (xyin6-stat6250): Other than "Select", what other command does PROC SQL have that is convenience for data manipulation steps?

