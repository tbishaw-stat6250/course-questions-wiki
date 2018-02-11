## Week 7 Quiz Questions and Answers

In order to prepare your Week 7 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-7" in your fork of this repo. Then, after all edits have been made/committed, your Week 7 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-7 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 10, Problem 2]
- *Question* (aacharya4−stat6250): What happens in case the format of a variable is provided in both DATA step and PROC step?
- *Answer* (aacharya4−stat6250): The temporary format of the variable assigned in PROC step overides the permanent formatting assigned to the variable in DATA step.



[Course Textbook Chapter 10, Problem 6]
- *Question* (aacharya4−stat6250): What are the possible results that are possible from using IF-THEN statement in SAS?
- *Answer* (aacharya4−stat6250): IF-THEN statement in SAS produces a result that is either nonzero, zero, or missing. If result is nonzero,nonmissing value, then TRUE; if result is zerp, missing value, then FALSE.



[Course Textbook Chapter 10, Problem 7]
- *Question* (aacharya4−stat6250): How is the length of a variable determined in SAS?
- *Answer* (aacharya4−stat6250): The length of a variable in SAS can be determined by VLENGTH or VARLEN function.



[Course Textbook Chapter 10, Problem 8]
- *Question* (aacharya4−stat6250): In SAS, in what other ways one can perform the task of conditional processing as used in IF-THEN-ELSE statements?
- *Answer* (aacharya4−stat6250): In SAS, one can use the PROC FORMAT or SELECT statement in place of IF-THEN-ELSE statements for conditional processing.



[Course Textbook Chapter 10, Problem 9]
- *Question* (aacharya4−stat6250): How is the use of LENGTH statement in SAS?
- *Answer* (aacharya4−stat6250): The LENGTH statement is used to set the length of a variable to a desired value. 



[Course Textbook Chapter 10, Problem 10]
- *Question* (aacharya4−stat6250): How can a DROP statement be used in a PROC step?
- *Answer* (aacharya4−stat6250): If used in a PROC statement, the DROP dataset option should be used follwed by a dataset name. For eg: proc print data=salary(drop=employee address);



[Course Textbook Chapter 11, Problem 1]
- *Question* (aacharya4−stat6250): What is the difference between KEEP data set option and KEEP statement in a DATA step?
- *Answer* (aacharya4−stat6250): In DATA step, the KEEP data set option is for both input and output data sets, while the KEEP sttement is only for output data sets.



[Course Textbook Chapter 11, Problem 2]
- *Question* (aacharya4−stat6250): What is the purpose of using DROP data set option in DATA step?
- *Answer* (aacharya4−stat6250): The purpose of using DROP data set option in DATA step is to prevent the mentioned variables in DROP data set option from being written to the data set.



[Course Textbook Chapter 11, Problem 3]
- *Question* (aacharya4−stat6250): What are the two variables created by DATA step when BY statement is used with SET statement?
- *Answer* (aacharya4−stat6250): The DATA step automatically creates a FIRST. and LAST. variable for each variable mentioned in BY statement to sidentify first and last observation of each BY group.



[Course Textbook Chapter 11, Problem 8]
- *Question* (aacharya4−stat6250): What is the use of END data set option in SAS?
- *Answer* (aacharya4−stat6250): The END data set option is to signify a temporary variable that contains the end-of-file marker.



[Course Textbook Chapter 11, Problem 9]
- *Question* (aacharya4−stat6250): What is Program Data Vector (PDV)?
- *Answer* (aacharya4−stat6250): PDV is a logiacal memory area created during the compilation of a DATA step process. SAS reads one observation at a time to PDV to make the SAS dataset.



[basic_recipe_for_combining_data_vertically Week 7 Recipe]
- *Question* (aacharya4−stat6250): What is the purpose of using IN data set option in SAS?
- *Answer* (aacharya4−stat6250): The IN data set option names the indicator variable that determines whether the input data set is part of the current observation. The value of the indicator variable is 1, if input data set contributes to current  observation. Otherwise, the value of indicator variable is 0.



[adv_recipe_for_combining_data_vertically Week 7 Recipe]
- *Question* (aacharya4−stat6250): What is the change needed in the code of this recipe to select the rows that are common in both the datasets?
- *Answer* (aacharya4−stat6250): In oreder to select the rows that are common in both the datasets, "union" in the code should be replaced by "intersect".


