## Week 7 Quiz Questions and Answers

In order to prepare your Week 7 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-7" in your fork of this repo. Then, after all edits have been made/committed, your Week 7 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-7 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 10, Problem 2]
- *Question* (cnguyen77-stat6250): How does the label and format in PROC PRINT affect the label and format in DATA step?
- *Answer* (cnguyen77-stat6250): Temporary labels or formats that are assigned in a PROC step override permanent labels or formats that are assigned in a DATA step.




[Course Textbook Chapter 10, Problem 6]
- *Question* (cnguyen77-stat6250): When does the IF-THEN statement executes a SAS statement?
- *Answer* (cnguyen77-stat6250): The IF-THEN statement executes a SAS statement when the condition in the IF clause is true.



[Course Textbook Chapter 10, Problem 7]
- *Question* (cnguyen77-stat6250): How to determine the length of a new variable?
- *Answer* (cnguyen77-stat6250): The length of a variable is determined by its first reference in the DATA step. When creating a new character variable, SAS allocates as many bytes of storage space as there are characters in the reference to that variable. The first reference to a new variable can also be made with a LENGTH statement or an assignment statement.




[Course Textbook Chapter 10, Problem 8]
- *Question* (cnguyen77-stat6250): What is the function of ELSE statement?
- *Answer* (cnguyen77-stat6250): You can write multiple ELSE statements to specify a series of mutually exclusive conditions. The ELSE statement must immediately follow the IF-THEN statement in your program. An ELSE statement executes only if the previous IF-THEN/ELSE statement is false.



[Course Textbook Chapter 10, Problem 9]
- *Question* (cnguyen77-stat6250): Where should the LENGTH statement be placed in DATA step?
- *Answer* (cnguyen77-stat6250): Make sure the LENGTH statement appears before any other reference to the variable in the DATA step. If the variable has been created by another statement, then a later use of the LENGTH statement will not change its length.



[Course Textbook Chapter 10, Problem 10]
- *Question* (cnguyen77-stat6250): Can DROP or KEEP statements be used in PROC steps?



[Course Textbook Chapter 11, Problem 1]
- *Question* (cnguyen77-stat6250): Where to Specify the DROP= and KEEP= Data Set Options?
- *Answer* (cnguyen77-stat6250): You can specify DROP= and KEEP= in either the DATA statement or the SET statement, depending on whether you want to drop variables onto output or input.



[Course Textbook Chapter 11, Problem 2]
- *Question* (cnguyen77-stat6250): What is the function of DROP= data set option?
- *Answer* (cnguyen77-stat6250): The DROP= data set option prevents variables from being written to the data set.



[Course Textbook Chapter 11, Problem 3]
- *Question* (cnguyen77-stat6250): When using the BY statement with the SET statement, are the temporary variables FIRST. and LAST. stored in the data set?



[Course Textbook Chapter 11, Problem 8]
- *Question* (cnguyen77-stat6250): What is the function of END=option on SET statement?



[Course Textbook Chapter 11, Problem 9]
- *Question* (cnguyen77-stat6250): Is there any observations at the start of DATA step processing?



[basic_recipe_for_combining_data_vertically Week 7 Recipe]
- *Question* (cnguyen77-stat6250): How to create indicator variables?



[adv_recipe_for_combining_data_vertically Week 7 Recipe]
- *Question* (cnguyen77-stat6250): Other than the creation of indicator variables, what is the alternative method being used to combine data vertically?
