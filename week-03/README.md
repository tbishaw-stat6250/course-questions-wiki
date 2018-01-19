
## Week 3 Quiz Questions and Answers

In order to prepare your Week 3 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-3" in your fork of this repo. Then, after all edits have been made/committed, your Week 3 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-3 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 3, Problem 1]
- *Question* (tbishawstat6250): Does SAS allow you to reopen a stored program to make edits on it for resubmission?
- *Answer* (tbishawstat6250): SAS software does allow you to reopen a stored program and made edits needed to submit it again. You can open a program using: file shortcuts, My Favorite Folders, the INCLUDE command, and the Open window. 



[Course Textbook Chapter 3, Problem 2]
- *Question* (tbishawstat6250): Is there a specific format to write a SAS statement or can you use any format and switch between different formats?
- *Answer* (tbishawstat6250): Although there are multiple formats in which you can write SAS statements in, a consistent layout enhances readability and helps you and others understand the program’s purpose. It is recommended to begin DATA and PROC steps in column one, indent statements within step, being RUN statements in column one, and include RUN statement after every DATA step or PROC step. 



[Course Textbook Chapter 3, Problem 3]
- *Question* (tbishawstat6250): What are the major capabilities of the Enhanced Editor in SAS software? 
 
 
 
[Course Textbook Chapter 3, Problem 4]
- *Question* (tbishawstat6250): Where can you find the line numbers and is it located in the same place for all operating environments? 
- *Answer* (tbishawstat6250): 



[Course Textbook Chapter 3, Problem 5] 
- *Question* (tbishawstat6250): What actions do the following Text Editor Line Commands execute: Cn, Dn, In, Mn, Rn, A, and B?
- *Answer* (tbishawstat6250): Cn: copies n lines (where n = a number up to 9999), Dn: deletes n lines, In: inserts n blank lines, Mn, moves n lines, Rn: repeats current line n times, A: after (used with C, I, and M), B: before (used with C, I, and M)



[Course Textbook Chapter 3, Problem 6]
- *Question* (tbishawstat6250): What are some of the most common errors in SAS? Where can you review the messages to check for errors each time you submit a SAS program?



[Course Textbook Chapter 3, Problem 7]
- *Question* (tbishawstat6250): If you are missing a quotation mark and you have an unbalanced quotation mark error, how do you resolve the Error?
- *Answer* (tbishawstat6250): 



[Course Textbook Chapter 3, Problem 10]
- *Question* (tbishawstat6250): What is the comment symbol in SAS? And does the SAS program execute or read the comments you make?



[Course Textbook Chapter 4, Problem 1]
- *Question* (tbishawstat6250): What is the first step in creating a Basic Report in SAS?
- *Answer* (tbishawstat6250): To create a simple list report, you first have to reference the library in which your SAS data set is stored. 



[Course Textbook Chapter 4, Problem 3]
- *Question* (tbishawstat6250): Can you specify the variables you want listed from a data set when creating a report? If so which SAS statement would you need to use to do so?



[Course Textbook Chapter 4, Problem 4]
- *Question* (tbishawstat6250): What is the functionality of the SORT procedure when creating a report?
- *Answer* (tbishawstat6250): The SORT procedure rearranges the observations in a SAS data set, creates a new SAS data set that contains the rearranged observations, replace the original SAS data set by default, and can sort multiple variables (ascending or descending order).



[Course Textbook Chapter 4, Problem 7]
- *Question* (tbishawstat6250): Which SAS statement do you use to produce column totals for numeric variables? And which SAS statement do you use for generating subtotals? 



[Course Textbook Chapter 4, Problem 9]
- *Question* (tbishawstat6250): What are the steps to generating a SAS LISTING output?
- *Answer* (tbishawstat6250): To generate SAS LISTING output, you must first select Tools and then you go to Options and under Options you select Preferences. In the Preference menu you will find the Results tab and the Creating Listing option. 



[Course Textbook Chapter 4, Problem 10]
- *Question* (tbishawstat6250): Which SAS statement do you use to label columns? And is it possible to use single or multiple label statements?



[recipe_to_check_for_duplicates Week 3 Recipe]
- *Question* (tbishawstat6250): What is the approach to checking for duplicate records in a data sets?
- *Answer* (tbishawstat6250): You have to attempt to sort the data set which simultaneously removing duplicate values but outputting the results of the de-duplication process to a null data set. By doing so you are able to find the number of duplicate records in the data log. It is extremely important to always check if our data contains duplicates. 



[recipe_for_sorting_data Week 3 Recipe]
- *Question* (tbishawstat6250): What is the procedure to sorting a report based on values of a variable and which SAS statement do we use to perform this action?
- *Answer* (tbishawstat6250): To sort a report based on values of a variable, we would use the PROC SORT statement to sort the data before using the PRINT procedure to create reports from the data. 



[recipe_for_printing_values Week 3 Recipe]
- *Question* (tbishawstat6250): What does the PROC PRINT statement display by default? And what are the observations displayed?
- *Answer* (tbishawstat6250): The PROC PRINT displays all observations and variable in a data set, a column for observation numbers on the far left, and variables in the order in which they occur in the data set. 


