## Week 5 Quiz Questions and Answers

In order to prepare your Week 5 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-5" in your fork of this repo. Then, after all edits have been made/committed, your Week 5 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-5 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 5, Problem 1]
- Question (aguenane−stat6250): To read a raw data file, what four instructions must the DATA step provide to SAS?
- Answer (aguenane-stat6250): The location or name of the external text file, the name for the new SAS data set, the reference that identifies the external file, and a description of the data values to be read. 



[Course Textbook Chapter 5, Problem 2]
- Question (aguenane−stat6250): What is the difference between the LIBNAME and FILENAME statements?
- Answer (aguenane-stat6250): LIBNAME references a SAS library while FILENAME references an external file.



[Course Textbook Chapter 5, Problem 6]
- Question (aguenane−stat6250): When using the INPUT statement to describe the fields of raw data to be read and placed into the SAS data set, what does the dollar sign ($) do?
- Answer (aguenane-stat6250): It identifies the variable type as character. 



[Course Textbook Chapter 5, Problem 7]
- Question (aguenane−stat6250): If you wanted to name a new variable NewBalance, when do you need to specify it in the exact case you wanted stored and when can you specify the name in uppercase, lowercase, or mixed case?



[Course Textbook Chapter 5, Problem 8]
- Question (aguenane−stat6250): When you use more than one arithmetic operator in an expression, how do you control the order of operations?



[Course Textbook Chapter 6, Problem 1]
- Question (aguenane−stat6250): What are the two automatic variables that can be used for processing contained in the program data vector?



[Course Textbook Chapter 6, Problem 2]
- Question (aguenane−stat6250): What happens when SAS finds a syntax error during the compilation phase?



[Course Textbook Chapter 6, Problem 3]
- Question (aguenane−stat6250): A raw data file with 20 records on the file executes how many times during the DATA step? 



[Course Textbook Chapter 6, Problem 4]
- Question (aguenane−stat6250): If I was missing the item name, what symbol would represent this missing value?



[Course Textbook Chapter 6, Problem 5]
- Question (aguenane−stat6250): Why does the value of the automatic variable _ERROR_ only go from 0 to 1?



[Course Textbook Chapter 6, Problem 6]
- Question (aguenane−stat6250): Why are the values of variables in the program data vector created in programming statements reset to missing at the end of the DATA step?



[basic_recipe_for_creating_analytic_datasets Week 5 Recipe]
- Question (aguenane−stat6250): Even though it looks redundant to have the same variables in both the RETAIN and KEEP statements, why is this necessary?



[adv_recipe_for_creating_analytic_datasets Week 5 Recipe]
- Question (aguenane−stat6250): Even though PROC SQL requires less code (since it uses the select clause to combine the functions of the RETAIN and KEEP statements), when are the times when you want to use PROC SQL and when are the times you would want to use the regular DATA step?




