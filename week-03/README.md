
## Week 3 Quiz Questions and Answers

In order to prepare your Week 3 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-3" in your fork of this repo. Then, after all edits have been made/committed, your Week 3 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-3 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 3, Problem 1]
- *Question* (aacharya4−stat6250): Why should we follow proper indentation format while writing SAS program even if SAS is a free format language?
- *Answer* (aacharya4−stat6250): Inspite of SAS being a free format language, we should use proper indentation while writing SAS programs as it enhances the readablility of SAS code making it easier to understand the program better.


[Course Textbook Chapter 3, Problem 2]
- *Question* (aacharya4−stat6250): Why is it a good practice to clear the messages in the log window before resubmitting the program?
- *Answer* (aacharya4−stat6250): It is a good practice to clear the log window before resubmitting the program so as to avoid any confusion with the error messages of the earlier code.


[Course Textbook Chapter 3, Problem 3]
- *Question* (aacharya4−stat6250): What happens when missing quotation mark is encountered by the SAS program?


[Course Textbook Chapter 3, Problem 4]
- *Question* (aacharya4−stat6250): What are the best possible ways to identify syntax errors in a SAS program?
- *Answer* (aacharya4−stat6250): Some of the ways to identify syntax errors in a SAS program are by using the SAS systems options in code window and DATA step debugger.


[Course Textbook Chapter 3, Problem 5]
- *Question* (aacharya4−stat6250): What are the different types of error that one can encounter in SAS programs?
- *Answer* (aacharya4−stat6250): The types of error encountered in a SAS program are : Syntax error, Data error, Semantic error, execution-time error.


[Course Textbook Chapter 3, Problem 6] 
- *Question* (aacharya4−stat6250): How does one avoid making "invalid option" error while writing SAS code?


[Course Textbook Chapter 3, Problem 7]
- *Question* (aacharya4−stat6250): What is the way to terminate a DATA step in a SAS program?
- *Answer* (aacharya4−stat6250): A DATA step in a SAS program can be terminated by using a RUN statement or by beginning another DATA step or a PROC step.


[Course Textbook Chapter 3, Problem 10]
- *Question* (aacharya4−stat6250): What happens when there are unbalanced Quotation marks in a DATA step of a SAS program? 
- *Answer* (aacharya4−stat6250): When there are unbalanced Quotation marks in a DATA step of a SAS program, the log window displays "DATA step running" message.


[Course Textbook Chapter 4, Problem 1]
- *Question* (aacharya4−stat6250): What is the purpose of LABEL option in SAS?
- *Answer* (aacharya4−stat6250): The LABEL option in SAS is to replace the variable name in the dataset with the label specified.


[Course Textbook Chapter 4, Problem 3]
- *Question* (aacharya4−stat6250): Which operator in SAS is used to classify observations based on a range of values?
- *Answer* (aacharya4−stat6250): The "IN" operator in SAS is used to classify observations based on a range of values.


[Course Textbook Chapter 4, Problem 4]
- *Question* (aacharya4−stat6250): What happens if when use the PROC SORT step without using the OUT option on a SAS dataset? 
- *Answer* (aacharya4−stat6250): If when use the PROC SORT step without using the OUT option on a SAS dataset, the original dataset gets sorted.


[Course Textbook Chapter 4, Problem 7]
- *Question* (aacharya4−stat6250): What happens if we use the PROC SORT step without using the BY statement?
- *Answer* (aacharya4−stat6250): Without the BY statement, the PROC SORT step generates error.


[Course Textbook Chapter 4, Problem 9]
- *Question* (aacharya4−stat6250): What is the logical operator used to depict not equal to in SAS?
- *Answer* (aacharya4−stat6250): In SAS, "^=" logical operator is used to depict not equal. 


[Course Textbook Chapter 4, Problem 10]
- *Question* (aacharya4−stat6250): What option is used to remove the default column of observation numbers on far left in PROC PRINT output?
- *Answer* (aacharya4−stat6250): NOOBS option is used to remove the default column of observation numbers on far left in PROC PRINT output.


[recipe_to_check_for_duplicates Week 3 Recipe]
- *Question* (aacharya4−stat6250): What happens if the OUT option is not set to a NULL dataset while removing duplicate records from a SAS dataset?
- *Answer* (aacharya4−stat6250): If the OUT option is not set to a NULL dataset while removing duplicate records from a SAS dataset, it creates a deduplicated datset.


[recipe_for_sorting_data Week 3 Recipe]
- *Question* (aacharya4−stat6250): Do we need to specify "ascending" option in order to sort the data in ascending order in a PROC SORT step in SAS?
- *Answer* (aacharya4−stat6250): No. The PROC SORT step in SAS sorts the data in ascending order by default based on the given criteria.


[recipe_for_printing_values Week 3 Recipe]
- *Question* (aacharya4−stat6250): What is the use of "var" statement in a PROC PRINT step in SAS?
- *Answer* (aacharya4−stat6250): In SAS, "var" statement in a PROC PRINT step is used to specify the variables in the dataset which would be included in the output. Without the "var" statement all variables of the dataset would be part of the output.
