
## Week 2 Quiz Questions and Answers

In order to prepare your Week 2 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-2" in your fork of this repo. Then, after all edits have been made/committed, your Week 2 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-2 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 1, Problem 1]
- Question (ttruong59-stat6250): In SAS, what are observations and variables in the data set?
- Asnwer (ttruong59-stat6250): Observations, aka rows, in the data set are collections of data values that relate to a single project while variables, aka columns, are collection of values that describe a particular characteristics.


[Course Textbook Chapter 1, Problem 2]
- Question (ttruong59-stat6250): What are the main differences between DATA steps and PROC steps in SAS?
- Asnwer (ttruong59-stat6250): DATA steps are used to create to create or modify SAS data sets, and can also be used to produce custom-designed reports. In contrast, PROC steps are used to invoke or call pre-written routines that enable us to analyze and process in a SAS data set, and can also be used to list, sort, and summarize data.


[Course Textbook Chapter 1, Problem 3]
- Question (ttruong59-stat6250): Can a numeric variable contain letters and underscore?
- Asnwer (ttruong59-stat6250): No, only a character variable can.

[Course Textbook Chapter 1, Problem 4]
- Question (ttruong59-stat6250): Assuming a missing value is indicated by a blank rather than a period, is the variable still considered as a numberic variable?


[Course Textbook Chapter 1, Problem 5]
- Question (ttruong59-stat6250): Are variable names case-sensitive? And what are their naming convention?
- Asnwer (ttruong59-stat6250): No, variable name are not case-sensitive. For example, variable STAT6250 and Stat6250 are considered the same. Variable must follow the naming convention as follows: (1) can't exceed 32 characters long, (2) must begin with a letter or an underscore, and (3) can continue with any combination of numbers, letters, and underscores. 


[Course Textbook Chapter 1, Problem 8]
- Question (ttruong59-stat6250): What is the default length for the numberic variable? What format do we need to specify a width of 8 and 4 decimal places.
- Asnwer (ttruong59-stat6250): The default length for the numeric variable is 8 bytes unless a different length is specified. To specify a width of and 4 decimal places, the format is COMMA8.4


[Course Textbook Chapter 2, Problem 3]
- Question (ttruong59-stat6250): Are there any differences in term of handling two-digit year and 4-digit year in SAS? If so, what are they?


[Course Textbook Chapter 2, Problem 7]
- Question (ttruong59-stat6250): Why does the length of a libref only allow 8 characters?


[Course Textbook Chapter 2, Problem 8]
- Question (ttruong59-stat6250): Why is the default value of YEARCUTOFF= 1920? Is there any benefit of using 1920, instead of using different year as a default value? If so, what is it?


[Course Textbook Chapter 2, Problem 9]
- Question (ttruong59-stat6250): What is a significant reason that LIBNAME statement can only assign the libref for the current SAS session only?


[basic_recipe_for_loading_data_from_remote_Excel_file Week 2 Recipe]
- Question (ttruong59-stat6250): Is there a way to revise codes to support some other data formats? 


[bonus_advanced_recipe_for_loading_data_from_remote_Excel_file Week 2 Recipe]
- Question (ttruong59-stat6250): Why do we use macro variable in SAS?



