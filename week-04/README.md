## Week 4 Quiz Questions and Answers

In order to prepare your Week 4 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-4" in your fork of this repo. Then, after all edits have been made/committed, your Week 4 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-4 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 7, Problem 3]
- Question (ttruong59-stat6250): What is a naming convention to name a character variable that is created with a VALUE statement?
- Answer (ttruong59-stat6250): The name of a format with a VALUE statement must begin with a dollar sign ($) if it applies to a character variable.



[Course Textbook Chapter 7, Problem 4]
- Question (ttruong59-stat6250): Is there any difference in formatting a numeric and character value of a VALUE statement?



[Course Textbook Chapter 7, Problem 5]
- Question (ttruong59-stat6250): Can ranges in VALUE statement specify a list of numeric and character values?
- Answer (ttruong59-stat6250): No. Either all numeric or all character values can specify.



[Course Textbook Chapter 7, Problem 6]
- Question (ttruong59-stat6250): How many characters can be used in label? What if the label exceeds character limits?
- Answer (ttruong59-stat6250): There are 256 characters can be used in label. In case the label exceeds 256 character limit, the system normally returns an error and notifies the user to rename. 



[Course Textbook Chapter 7, Problem 7]
- Question (ttruong59-stat6250): OTHER is a keyword to label any missing value that is not specified in a range. Is there any other keyword perform this function? 



[Course Textbook Chapter 7, Problem 8]
- Question (ttruong59-stat6250): Does FORMAT statement replace original data when we place it in a DATA step?



[Course Textbook Chapter 8, Problem 1]
- Question (ttruong59-stat6250): What are the default statistics produced by the MEANS procedure?
- Answer (ttruong59-stat6250): By default, MEANS procedure returns the n, mean, min, max, and standard deviation.



[Course Textbook Chapter 8, Problem 2]
- Question (ttruong59-stat6250): To limit a PROC MEANS analysis to variables, what can user do? 
- Answer (ttruong59-stat6250): User can add a VAR statement and list only the variable names they want to analyze.



[Course Textbook Chapter 8, Problem 4]
- Question (ttruong59-stat6250): Why does user need to run BY group processing statement?



[Course Textbook Chapter 8, Problem 7]
- Question (ttruong59-stat6250): What is a required statement to create a table of frequencies and percentages for all variables in a dataset?
- Answer (ttruong59-stat6250): The PROC FREQ is the required statement for the FREQ procedure.



[Course Textbook Chapter 8, Problem 8]
- Question (ttruong59-stat6250): Why does frequency distribution work best with categorical values only?



[Course Textbook Chapter 8, Problem 10]
- Question (ttruong59-stat6250): Is it possible to join 2 variables from 2 different datasets with PROC FREQ?



[recipe_for_summarizing_quantitative_values Week 4 Recipe]
- Question (ttruong59-stat6250): Both PROC MEANS and PROC FREQ are used to tell SAS which variables to summarize, but what are the major differences between of these 2 statements?



[recipe_for_summarizing_qualitative_values Week 4 Recipe]
- Question (ttruong59-stat6250): Does PROC FREQ have an option to calculate or compute the content (values) between two rows in the table? or should a user need to add another procedure to do so?



[recipe_for_temporarily_binning_values Week 4 Recipe]
- Question (ttruong59-stat6250): Temporarily binning values with a format is a two-step process, can a user make it permanently?



