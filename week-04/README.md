## Week 4 Quiz Questions and Answers

In order to prepare your Week 4 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-4" in your fork of this repo. Then, after all edits have been made/committed, your Week 4 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-4 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 7, Problem 3]
- *Question* (aacharya4−stat6250): While specifying numeric values in VALUE statement, what are the rules that should be followed?
- *Answer* (aacharya4−stat6250): The numeric values should not end with '$' and they should be enclosed within quotation marks.



[Course Textbook Chapter 7, Problem 4]
- *Question* (aacharya4−stat6250): What are the rules to follow while defining one's own unique format with PROC FORMAT statement?
- *Answer* (aacharya4−stat6250): To define one own's unique format, it must begin with keyword value followed by the format name and ends with semicolon after all labels are defined.



[Course Textbook Chapter 7, Problem 5]
- *Question* (aacharya4−stat6250): How to define a list of values (either numeric or character) in the VALUE statement?
- *Answer* (aacharya4−stat6250): A list containing either all numeric or character values can be used in the VALUE statement by seperating each value with commas.



[Course Textbook Chapter 7, Problem 6]
- *Question* (aacharya4−stat6250): What happens if the format name ends in a period when used in a VALUE statement?



[Course Textbook Chapter 7, Problem 7]
- *Question* (aacharya4−stat6250): What keywords can be used as a label to depict the lower and upper limits of a variable's value range in VALUE statement?
- *Answer* (aacharya4−stat6250): 'LOW' and 'HIGH' keywords can be used as a label to depict the lower and upper limits of a variable's value range in VALUE statement.



[Course Textbook Chapter 7, Problem 8]
- *Question* (aacharya4−stat6250): What can we make a apostrophe to appear in a label?
- *Answer* (aacharya4−stat6250): In order to make a make a apostrophe to appear in a label, we have to use two single quotation marks.



[Course Textbook Chapter 8, Problem 1]
- *Question* (aacharya4−stat6250): Why is the purpose of using MAXDEC option in PROC MEANS statement?
- *Answer* (aacharya4−stat6250): By default, PROC MEANS statement displays the entire width of numeric variable. MAXDEC option in PROC MEANS statement is used to limit it to specified number of decimal places. 



[Course Textbook Chapter 8, Problem 2]
- *Question* (aacharya4−stat6250): What is the purpose of using "var" statement in PROC MEANS? 
- *Answer* (aacharya4−stat6250): The purpose of using "var" in PROC MEANS statement is to specify the variables in the dataset for which PROC MEANS is applied.



[Course Textbook Chapter 8, Problem 4]
- *Question* (aacharya4−stat6250): What should be done before using the "BY" group processing?
- *Answer* (aacharya4−stat6250): "BY" group processing needs already indexed or sorted data, hence we need to run PROC SORT before using BY group processing.



[Course Textbook Chapter 8, Problem 7]
- *Question* (aacharya4−stat6250): How is the purpose of using TABLES statement in PROC FREQ ?
- *Answer* (aacharya4−stat6250): The purpose of using TABLES statement in PROC FREQ is to determine the order in which the variables appear in the PROC FREQ report.



[Course Textbook Chapter 8, Problem 8]
- *Question* (aacharya4−stat6250): Why frequency distributions do not work well with continous and unique values?



[Course Textbook Chapter 8, Problem 10]
- *Question* (aacharya4−stat6250): What is the purpose of using NOFREQ option in PROC FREQ statement?
- *Answer* (aacharya4−stat6250): The purpose of using NOFREQ option in PROC FREQ statement is to suppress the cell frequencies.



[recipe_for_summarizing_quantitative_values Week 4 Recipe]
- *Question* (aacharya4−stat6250): What is the purpose of using "class" statement in PROC MEANS? 
- *Answer* (aacharya4−stat6250): The purpose of using "class" statement in PROC MEANS is to group the PROC MEANS output by the values of variables mentioned in the class statement.



[recipe_for_summarizing_qualitative_values Week 4 Recipe]
- *Question* (aacharya4−stat6250): How to create two way table using TABLES statement in PROC FREQ?
- *Answer* (aacharya4−stat6250): In PROC FREQ, the TABLES statement contains the keyword "tables" followed by the two variable names joined by asterisk(*). The first varible represents the rows while the second variable represents the columns in PROC FREQ output table.



[recipe_for_temporarily_binning_values Week 4 Recipe]
- *Question* (aacharya4−stat6250): How can we permanently associate a format with a variable?
- *Answer* (aacharya4−stat6250): A varible can be permanently associated with a format if the format is defined in the data step.


