## Week 7 Quiz Questions and Answers

In order to prepare your Week 7 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-7" in your fork of this repo. Then, after all edits have been made/committed, your Week 7 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-7 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 10, Problem 2]
- *Question* (jbettonville-stat6250): If two separate labels are to be used with equal frequency within a program, is there a way to specify multiple labels that can be applied, or does the full text of the secondary label need to be entered each time that label is needed?



[Course Textbook Chapter 10, Problem 6]
- *Question* (jbettonville-stat6250): How might we create a condition in which the case of the letters in the pattern to match is ignored?



[Course Textbook Chapter 10, Problem 7]
- *Question* (jbettonville-stat6250): Is it possible to change the length of a variable within a data set once it has been set in a DATA step?



[Course Textbook Chapter 10, Problem 8]
- *Question* (jbettonville-stat6250): What is the result if non-mutually exclusive conditions are included in an IF-ELSE statement?



[Course Textbook Chapter 10, Problem 9]
- *Question* (jbettonville-stat6250): In common SAS usage, is it preferred to implicitly define variable length within an IF statement, or to explicitly define it using a LENGTH statement before the IF statement?



[Course Textbook Chapter 10, Problem 10]
- *Question* (jbettonville-stat6250): In common SAS usage, is it preferred to use DROP statements within DATA steps to explicitly exclude certain variables, or to use KEEP to select specific variables to include?
- *Answer* (jbettonville-stat6250): It is preferred to use KEEP statements to explicitly include specific variables, as this makes the code somewhat "self-documenting" by showing what is included rather than what is excluded, and it also prevents unwanted columns from being included in case the input data changes. (n.b. Week 5 SAS recipes lines 89-93)



[Course Textbook Chapter 11, Problem 1]
- *Question* (jbettonville-stat6250): What is the difference between using DROP as an option on a DATA step and using DROP or KEEP as an option in a SET statement within a DATA step?
- *Answer* (jbettonville-stat6250): Using DROP or KEEP in the SET statement specifies what columns from the source data set are dropped or kept, at which point additional conditions may be applied to remove specific observations (i.e. an IF statement can be used following the SET statement to choose only rows that meet a specific condition). Using DROP as an option in the DATA step can be used to exclude columns that were included in the SET statement that may have been used when selecting which observations to select, but that are not desired in the final output data set.



[Course Textbook Chapter 11, Problem 2]
- *Question* (jbettonville-stat6250): Can the KEEP option be used as an option in the DATA step to explicitly choose the variables from the original data set to include in the output data set?



[Course Textbook Chapter 11, Problem 3]
- *Question* (jbettonville-stat6250): Can multiple observations in a data set take on a value of 1 in the FIRST. and/or LAST. variables when working with more than one BY variable?



[Course Textbook Chapter 11, Problem 8]
- *Question* (jbettonville-stat6250): Can (and should) the END= option be used to return the index of the final observation in a data set?



[Course Textbook Chapter 11, Problem 9]
- *Question* (jbettonville-stat6250): During the compilation phase, how does SAS determine the order of the variables added to the PDV based upon options in the DATA step, the SET statement, and any additional variables that are created within the statement?



[basic_recipe_for_combining_data_vertically Week 7 Recipe]
- *Question* (jbettonville-stat6250): Is it possible to resolve warnings about multiple lengths being specified for the same variable when multiple data sets are joined vertically?
- *Answer* (jbettonville-stat6250): The warnings about multiple lengths occur because the length of the initial observation for the affected variables in one data set are not the same length as they are in the second. In the example, the Academic_Year variable has length 19 in the first input data set and 60 in the second. It is possible to resolve this issue by specifying the length of this variable within the DATA step prior to the SET statement in which the input data sets are referenced, and choosing a value that is at least as long as the longest instance of this variable; by using the statement "length Academic_Year $ 60;", the warning for the Academic_Year variable will not be shown because the length has been declared to be equal to the longest version of this variable among the input data sets. However, while this resolves the warning for one variable, it may not be a scalable solution as it would require the length of all variables to be specified prior to the SET statement.



[adv_recipe_for_combining_data_vertically Week 7 Recipe]
- *Question* (jbettonville-stat6250): If not all columns between the two data sets were named identically, would UNION ALL CORR in lead to missing values in the resulting data set?


