## Week 5 Quiz Questions and Answers

In order to prepare your Week 5 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-5" in your fork of this repo. Then, after all edits have been made/committed, your Week 5 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-5 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 5, Problem 1]
- *Question* (akrishnamurthy-stat6250): How to associate a fileref to multiple external files? How to access specific files from a directory?
- *Answer* (akrishnamurthy-stat6250): The FILENAME can associate a fileref to a directory that contains multiple files. A specific file from the directory can then be referenced using the fileref followed by the individual filename in paranthesis.



[Course Textbook Chapter 5, Problem 2]
- *Question* (akrishnamurthy-stat6250): What is the scope of files referenced by FILENAME statement?



[Course Textbook Chapter 5, Problem 6]
- *Question* (akrishnamurthy-stat6250): How should the character and numeric data fields from raw file be defined in SAS dataset?
- *Answer* (akrishnamurthy-stat6250): While specifying character fields, the variable name should be followed by '$' sign.



[Course Textbook Chapter 5, Problem 7]
- *Question* (akrishnamurthy-stat6250): Should all the colums from a raw file be read into SAS dataset ? Can the fields from raw file be read in any order ?



[Course Textbook Chapter 5, Problem 8]
- *Question* (akrishnamurthy-stat6250): How to redefine a variable with a new value using SAS expressions?



[Course Textbook Chapter 6, Problem 1]
- *Question* (akrishnamurthy-stat6250): While subsetting data, are the observations filtered during compilation phase ?



[Course Textbook Chapter 6, Problem 2]
- *Question* (akrishnamurthy-stat6250): If SAS can interpret a syntax error, will the program DATA step still compile?
- *Answer* (akrishnamurthy-stat6250): If SAS can interpret a syntax error, then the DATA step compiles and executes. If SAS cannot interpret a syntax error, then the DATA step compiles but does not execute.



[Course Textbook Chapter 6, Problem 3]
- *Question* (akrishnamurthy-stat6250): Will the DATA step execute for each observation?



[Course Textbook Chapter 6, Problem 4]
- *Question* (akrishnamurthy-stat6250): How does _N_ and _ERROR_ values loop for each record in the file?



[Course Textbook Chapter 6, Problem 5]
- *Question* (akrishnamurthy-stat6250): Is the program data vector values initialized before every record read or will the input data be stored as an array in the program data vector?



[Course Textbook Chapter 6, Problem 6]
- *Question* (akrishnamurthy-stat6250): After the iterative read by DATA statement, what happens to the program data vector during and after execution phase?



[basic_recipe_for_creating_analytic_datasets Week 5 Recipe]
- *Question* (akrishnamurthy-stat6250): Why does SAS read a DATA step twice for compilation and execution?



[adv_recipe_for_creating_analytic_datasets Week 5 Recipe]
- *Question* (akrishnamurthy-stat6250): What is the function of PROC SQL statement? Can larger datasets be processed with PROC SQL ?


