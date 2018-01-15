
## Week 3 Quiz Questions and Answers

In order to prepare your Week 3 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-3" in your fork of this repo. Then, after all edits have been made/committed, your Week 3 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-3 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 3, Problem 1]
- Question (nshrivastava2-stat6250): How SAS editor behaves with different elements of SAS program ? 
- Answer(nshrivastava2-stat6250): In SAS editors, all the different elements of a SAS program (e.g. keywords, comments, quoted strings, constants and variables) show up in a different color as you type them. This can be extremely valuable in catching missing semicolons (and also un-matched quotes) as you type your program, because the program will most likely not be colored properly if you have a missing semicolon.



[Course Textbook Chapter 3, Problem 2]
- Question (nshrivastava2-stat6250): What are the different colors log has, to show errors/ warnings/ Notes? 
- Answer(nshrivastava2-stat6250): Log has ERROR with Red, WARNING with Green, Notes with Blue.


[Course Textbook Chapter 3, Problem 3]
- Question (nshrivastava2-stat6250): How many messages SAS logs contain? 
- Answer(nshrivastava2-stat6250): SAS Logs contain 3 types of messages: errors, warnings, and notes.

 
[Course Textbook Chapter 3, Problem 4]
- Question (nshrivastava2-stat6250):How the missing RUN Statement interpret in SAS program?


[Course Textbook Chapter 3, Problem 5]
- Question (nshrivastava2-stat6250):How can SAS program interpret Error Messages ? 
- Answer(nshrivastava2-stat6250):SAS can detect several types of errors. The most common are 1) Syntax errors that occur when program statements do not conform to the rules of the SAS language. 2) Data errors that occur when some data values are not appropriate for the SAS statements that are specified in a program. 



[Course Textbook Chapter 3, Problem 6]
- Question (nshrivastava2-stat6250): What are the specification and classification of bugs discussed in SAS programing?
- Answer(nshrivastava2-stat6250): Bugs can be classified as 1) Syntax Error: missing semicolon, uninitialized variable and variable not found. 2) Data Error: Missing values were generated, numeric to character conversion, invalid data, character field is truncated.3)Logic Error:DATA step produces wrong results but no error message. 



[Course Textbook Chapter 3, Problem 7]
- Question (nshrivastava2-stat6250): What is the thumb rule for debugging? Why is so important to LISTEN TO THE SAS LOG? 


[Course Textbook Chapter 3, Problem 10]
- Question (nshrivastava2-stat6250): How the "Unbalanced Quotation Marks" works in SAS programing? 
- Answer(nshrivastava2-stat6250):  When program has one for more unbalanced quotation marks, SAS is often unable to detect the end of the statement in which the error occurs. If unbalanced quotation marks appear in a program that contains TITLE or FOOTNOTE statements, there is sometimes a warning in the SAS log which indicates that a text string enclosed in quotation marks has become too long.



[Course Textbook Chapter 4, Problem 1]
- Question (nshrivastava2-stat6250): Where and how and can one produce column totals for numeric variables within your report?
- Answer(nshrivastava2-stat6250): Programmers have to program in PROC statement by using keyword "SUM" to column total for numeric variables. 



[Course Textbook Chapter 4, Problem 3]
- Question (nshrivastava2-stat6250): How one can remove the default Obs column that displays observation numbers?


[Course Textbook Chapter 4, Problem 4]
- Question (nshrivastava2-stat6250): What is the default sorting options?Can we specify more than one variables with different sort options?


[Course Textbook Chapter 4, Problem 7]
- Question (nshrivastava2-stat6250): If there are special character for instance German three letter-diacritic combinations (Ä/ä, Ö/ö, Ü/ü). Will the SORT function will take care of those and if yes,how?


[Course Textbook Chapter 4, Problem 9]
- Question (nshrivastava2-stat6250): By default, a PROC PRINT step lists all the observations in a data set. How can programmer can control observations to get printed ? 
- Answer(nshrivastava2-stat6250): Programmer can control observations to be printed by adding a WHERE statement to your PROC PRINT step.There can be only one WHERE statement in a step.



[Course Textbook Chapter 4, Problem 10]
- Question (nshrivastava2-stat6250): What technique is particularly useful when observations are too long to print on one line. 
- Answer(nshrivastava2-stat6250): One can say so by using the ID statement where ID variable(s), where variable(s) specifies one or more variables to print instead of the observation number at the beginning of each row of the report.



[recipe_to_check_for_duplicates Week 3 Recipe]
- Question (nshrivastava2-stat6250): What is the reason of duplicates? Is because of the variable supposed to be unique? How will the duplicate records remove?


[recipe_for_sorting_data Week 3 Recipe]
- Question (nshrivastava2-stat6250): Can we define SORT procedure and WHERE statement in one single PROC statement? If yes,Why/ if no, Whynot?
- Answer(nshrivastava2-stat6250): Yes, we can do that. This may improve the efficiency of SAS programs because SAS is not required to read all observations from the input data set. There are many different options that are available to the SORT procedure to use them to enhance the programs and improve efficiency. 



[recipe_for_printing_values Week 3 Recipe]
- Question (nshrivastava2-stat6250): How many TITLE and FOOTNOTE Statements specify in a program?
- Answer(nshrivastava2-stat6250):  To make the report more meaningful and self-explanatory, one can specify up to 10 titles with procedure output by using TITLE statements before the PROC step. Likewise, specify up to 10 footnotes by using FOOTNOTE statements before the PROC step. Be sure to match quotation marks that enclose the title or footnote text. 


