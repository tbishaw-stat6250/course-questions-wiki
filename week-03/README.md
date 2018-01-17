
## Week 3 Quiz Questions and Answers

In order to prepare your Week 3 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-3" in your fork of this repo. Then, after all edits have been made/committed, your Week 3 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-3 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 3, Problem 1]
- *Question* (akrishnamurthy-stat6250): Is there a coding structure to be followed for SAS program and What are the good SAS coding practices?


[Course Textbook Chapter 3, Problem 2]
- *Question* (akrishnamurthy-stat6250): What is the procedure for SAS code debugging and how to re-run corrected code?
- *Answer* (akrishnamurthy-stat6250): SAS log helps to debug a code and locate the lines causing errors. Code can then be corrected by recalling the code to Program Editor window. Before resubmitting the code, it is good practice to clear the log window so that the log from new run could be verified. Resubmit the code and repeat the process until code runs successfully.


[Course Textbook Chapter 3, Problem 3]
- *Question* (akrishnamurthy-stat6250): How are missing quotation marks handled in SAS ? 

 
[Course Textbook Chapter 3, Problem 4]
- *Question* (akrishnamurthy-stat6250): Will a SAS program continue execution after encountering a step with syntax error? 


[Course Textbook Chapter 3, Problem 5]
- *Question* (akrishnamurthy-stat6250): Are incompatible data values considered as syntax error in SAS ? 


[Course Textbook Chapter 3, Problem 6]
- *Question* (akrishnamurthy-stat6250): How to correct a SAS program that failed with invalid option syntax error?


[Course Textbook Chapter 3, Problem 7]
- *Question* (akrishnamurthy-stat6250): What kind of error is thrown for a misspelled keyword and how to correct the code for re-run?


[Course Textbook Chapter 3, Problem 10]
- *Question* (akrishnamurthy-stat6250): Since SAS always executes a current step when it encounters the next PROC or DATA statement, why should a RUN statement be explicitly specified?
- *Answer* (akrishnamurthy-stat6250): Although RUN statements are not mandatory and are not considered as error,omitting RUN statements can sometimes produce unexpected results. Especially if the last step in program is not followed by RUN, the program will compile successfully but the last step will not be executed. 


[Course Textbook Chapter 4, Problem 1]
- *Question* (akrishnamurthy-stat6250): How to omit the observation number while creating a report?


[Course Textbook Chapter 4, Problem 3]
- *Question* (akrishnamurthy-stat6250): How to select observations from a file based on specific values for a variable?


[Course Textbook Chapter 4, Problem 4]
- *Question* (akrishnamurthy-stat6250): How to sort a file temporarily for the current SAS session ?


[Course Textbook Chapter 4, Problem 7]
- *Question* (akrishnamurthy-stat6250): Is sort statement mandatory before printing a dataset in SAS ?


[Course Textbook Chapter 4, Problem 9]
- *Question* (akrishnamurthy-stat6250): How are compound expressions evaluated in SAS ?


[Course Textbook Chapter 4, Problem 10]
- *Question* (akrishnamurthy-stat6250): What is the syntax of PRINT procedure and how can the output be customized to filter columns or rows?


[recipe_to_check_for_duplicates Week 3 Recipe]
- *Question* (akrishnamurthy-stat6250): How to retrieve the duplicate observations from a dataset?
- *Answer* (akrishnamurthy-stat6250): The statement 'nodupkey' in sort procedure is used to eliminate the duplicate observations from a dataset based on th key columns specified. The eliminated records could be directed either to a Null output or another permanent dataset using the 'dupout' statement


[recipe_for_sorting_data Week 3 Recipe]
- *Question* (akrishnamurthy-stat6250): How are duplicate values for key column handled while sorting the dataset ?


[recipe_for_printing_values Week 3 Recipe]
- *Question* (akrishnamurthy-stat6250): What is the need for an 'id' statement in PRINT procedure ?

