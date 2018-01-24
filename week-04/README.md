## Week 4 Quiz Questions and Answers

In order to prepare your Week 4 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-4" in your fork of this repo. Then, after all edits have been made/committed, your Week 4 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-4 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 7, Problem 3]
- *Question* (cnguyen77-stat6250): What are the rules to name a format with VALUE statement?


[Course Textbook Chapter 7, Problem 4]
- *Question* (cnguyen77-stat6250): Is it necessary to have a semicolon after the PROC FORMAT statement and VALUE statement?
- *Answer* (cnguyen77-stat6250): A semicolon is needed after the PROC FORMAT statement. The VALUE statement begins with the keyword VALUE and ends with a semicolon after all the labels have been defined.


[Course Textbook Chapter 7, Problem 5]
- *Question* (cnguyen77-stat6250): Can ranges in the VALUE statement specify a list of numeric and character values separated by commas?
- *Answer* (cnguyen77-stat6250): You can list values separated by commas, but the list must contain either all numeric values or all character values. Data set variables are either numeric or character.

[Course Textbook Chapter 7, Problem 6]
- *Question* (cnguyen77-stat6250): Is there any limitation for the number of characters of a label?
- *Answer* (cnguyen77-stat6250): When specifying a label, enclose it in quotation marks and limit the label to 256 characters.


[Course Textbook Chapter 7, Problem 7]
- *Question* (cnguyen77-stat6250): How to label missing numeric values as well as any values that are not specified in a range?
- *Answer* (cnguyen77-stat6250): The keyword OTHER can be used in the VALUE statement to label missing values as well as any values that are not specifically included in a range.


[Course Textbook Chapter 7, Problem 8]
- *Question* (cnguyen77-stat6250): Can FORMAT statement be used in a DATA step?
- *Answer* (cnguyen77-stat6250): Yes. By placing the FORMAT statement in a DATA step, you permanently associate the defined format with variables.


[Course Textbook Chapter 8, Problem 1]
- *Question* (cnguyen77-stat6250): What are included in the output of PROC MEANS?
- *Answer* (cnguyen77-stat6250): By default, the MEANS procedure produces the n, mean, minimum, maximum, and standard deviation.


[Course Textbook Chapter 8, Problem 2]
- *Question* (cnguyen77-stat6250): How to specify the variables that PROC MEANS analyzes?
- *Answer* (cnguyen77-stat6250): To specify the variables that PROC MEANS analyzes, add a VAR statement and list the variable names.


[Course Textbook Chapter 8, Problem 4]
- *Question* (cnguyen77-stat6250): What is the key difference between CLASS and BY processing?
- *Answer* (cnguyen77-stat6250): Unlike CLASS processing, BY group processing requires that your data already be indexed or sorted in the order of the BY variables. You might need to run the SORT procedure before using PROC MEANS with a BY group.


[Course Textbook Chapter 8, Problem 7]
- *Question* (cnguyen77-stat6250): Does PROC FREQ creates a table of frequencies and percentages for character variables or numeric variables?
- *Answer* (cnguyen77-stat6250): Both character and numeric variables. By default, PROC FREQ creates a table for all variables in a data set.


[Course Textbook Chapter 8, Problem 8]
- *Question* (cnguyen77-stat6250): When is the best case to use frequency distributions?
- *Answer* (cnguyen77-stat6250): Frequency distributions work best with categorical values.


[Course Textbook Chapter 8, Problem 10]
- *Question* (cnguyen77-stat6250): How to join the variables in crosstabulation tables?
- *Answer* (cnguyen77-stat6250): An asterisk is used to join the variables in crosstabulation tables.


[recipe_for_summarizing_quantitative_values Week 4 Recipe]
- *Question* (cnguyen77-stat6250): What are the two most basic statistical procs in SAS?
- *Answer* (cnguyen77-stat6250): Proc mean and proc means are the two most basic statistical procs in SAS.


[recipe_for_summarizing_qualitative_values Week 4 Recipe]
- *Question* (cnguyen77-stat6250): What is the nlevels used for in proc freq?


[recipe_for_temporarily_binning_values Week 4 Recipe]
- *Question* (cnguyen77-stat6250): How to group values in a SAS dataset without changing the underlying values in the dataset?
