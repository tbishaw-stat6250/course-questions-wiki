
## Week 3 Quiz Questions and Answers

In order to prepare your Week 3 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-3" in your fork of this repo. Then, after all edits have been made/committed, your Week 3 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-3 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************

[Course Textbook Chapter 3, Problem 1]
- *Question* (cnguyen77-stat6250): What is the good format to write SAS statements when writing and editing SAS programs?
- *Answer* (cnguyen77-stat6250): Although you can write SAS statements in almost any format, a consistent layout enhances readability and enables you to understand the program's purpose. It's a good idea to begin DATA and PROC steps in column one, to indent statements within a step, to begin RUN statements in column one, and to include a RUN statement after every DATA step or PROC step.


[Course Textbook Chapter 3, Problem 2]
- *Question* (cnguyen77-stat6250):What is the first step you should do when you want to modify the programs that contain errors?
- *Answer* (cnguyen77-stat6250):To modify programs that contain errors, if you use the Program Editor window, you usually need to recall the submitted statements from the recall buffer to the Program Editor window, where you can correct the problems. After correcting the errors, you can resubmit the revised program. However, before doing so, it's a good idea to clear the messages from the Log window so that you don't confuse the old error messages with the new messages. Remember to check the Log window again to verify that your program ran correctly.


[Course Textbook Chapter 3, Problem 3]
- *Question* (cnguyen77-stat6250): What would happen if you miss a quotation mark in the LABEL statement?


[Course Textbook Chapter 3, Problem 4]
- *Question* (cnguyen77-stat6250): Will the SAS continue process the step if there is a syntax error in it?
- *Answer* (cnguyen77-stat6250): Syntax errors generally cause SAS to stop processing the step in which the error occurred. When a program that contains an error is submitted, messages regarding the problem also appear in the Log window. When a syntax error is detected, the Log window displays the word ERROR, identifies the possible location of the error, and gives an explanation of the error.


[Course Textbook Chapter 3, Problem 5]
- *Question* (cnguyen77-stat6250): What will happen if program statements do not conform to the rules of the SAS language?


[Course Textbook Chapter 3, Problem 6]
- *Question* (cnguyen77-stat6250): What will happen if you specify an option that is not valid in a particular statement?
- *Answer* (cnguyen77-stat6250): When a SAS statement that contains an invalid option is submitted, a message appears in the Log window indicating that the option is not valid or not recognized.


[Course Textbook Chapter 3, Problem 7]
- *Question* (cnguyen77-stat6250): Will SAS produce a warning message or an syntax error when you misspell DATA step?
- *Answer* (cnguyen77-stat6250): SAS produces only a warning message, not an error.


[Course Textbook Chapter 3, Problem 10]
- *Question* (cnguyen77-stat6250): What will happen if you forget to end the DATA step with a RUN statement?


[Course Textbook Chapter 4, Problem 1]
- *Question* (cnguyen77-stat6250): How to specify the data set that you want to print?
- *Answer* (cnguyen77-stat6250): “PROC PRINT DATA=SAS-data-set;” where SAS-data-set is the name of the SAS data set to be printed.



[Course Textbook Chapter 4, Problem 3]
- *Question* (cnguyen77-stat6250): If you want to select observations based on several values, what kind of SAS statement you can use?
- *Answer* (cnguyen77-stat6250): In the WHERE statement, the IN operator enables you to select observations based on several values. You specify values in parentheses and separated by spaces or commas. Character values must be enclosed in quotation marks and must be in the same case as in the data set.


[Course Textbook Chapter 4, Problem 4]
- *Question* (cnguyen77-stat6250): Do you need to specify the data set in a PROC SORT step?
- *Answer* (cnguyen77-stat6250): In a PROC SORT step, you specify the DATA= option to specify the data set to sort. The OUT= option specifies an output data set. The required BY statement specifies the variable(s) to use in sorting the data.


[Course Textbook Chapter 4, Problem 7]
- *Question* (cnguyen77-stat6250): Is the BY statement required in PROC SORT step?


[Course Textbook Chapter 4, Problem 9]
- *Question* (cnguyen77-stat6250): How to ensure that the compound expression is evaluated correctly?


[Course Textbook Chapter 4, Problem 10]
- *Question* (cnguyen77-stat6250): What is the default function of PROC PRINT?


[recipe_to_check_for_duplicates Week 3 Recipe]
- *Question* (cnguyen77-stat6250): What is the approach to remove duplicate records in a SAS dataset?


[recipe_for_sorting_data Week 3 Recipe]
- *Question* (cnguyen77-stat6250): Do you need to specify the out=option when sorting data in SAS?


[recipe_for_printing_values Week 3 Recipe]
- *Question* (cnguyen77-stat6250): What will happen if the id statement are left out when printing data in SAS?
