## Week 8 Quiz Questions and Answers

In order to prepare your Week 8 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-8" in your fork of this repo. Then, after all edits have been made/committed, your Week 8 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-8 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 13, Problem 1]
- *Question* (jbettonville-stat6250): Do the variables included in the list that is created by the minus sign have to be in order within the data set? (i.e. if variables are arranged in a data set ordered as var3, var1, var2, var4, would the statement that generated the mean of all four variables be mean(of var3-var4)?)



[Course Textbook Chapter 13, Problem 2]
- *Question* (jbettonville-stat6250): Is it possible to permanently convert a character value to a numeric value in the same step as completing a mathematical evaluation with the original character value?



[Course Textbook Chapter 13, Problem 3]
- *Question* (jbettonville-stat6250): When converting character values to numeric values with INPUT, what is the result if the character values contain numeric data that does not consistently conform to a standard informat?



[Course Textbook Chapter 13, Problem 4]
- *Question* (jbettonville-stat6250): Is it possible and/or useful to use regular expressions to do more complex conversions between formats?



[Course Textbook Chapter 13, Problem 5]
- *Question* (jbettonville-stat6250): Under what circumstances might we want to alter the YEARCUTOFF= value when starting a SAS session?



[Course Textbook Chapter 13, Problem 6]
- *Question* (jbettonville-stat6250): When might the SUBSTR function be used instead of the SCAN function when parsing character values?
- *Answer* (jbettonville-stat6250): SUBSTR returns a value of a specified length at a specified position within a string. When a value within a data set is consistently structured, SUBSTR can be used to extract different parts of a specified variable.



[Course Textbook Chapter 13, Problem 7]
- *Question* (jbettonville-stat6250): What happens if the length of the output substring is not specified when using SUBSTR?
- *Answer* (jbettonville-stat6250): If the third argument is not included in the SUBSTR function, the resulting substring contains all characters from the original string starting from the specified index.



[Course Textbook Chapter 13, Problem 10]
- *Question* (jbettonville-stat6250): Can multiple INDEX statements be used with additional IF statements to create subsets based on multiple conditions at once?



[recipe_for_isolating_all_duplicates Week 8 Recipe]
- *Question* (jbettonville-stat6250): How might we extract only records for which the target variable is not duplicated?
- *Answer* (jbettonville-stat6250): In the example provided in the recipe, the records containing unique values in the target variable could be selected by setting the contents of the IF statement to FIRST.School_Code * LAST.School_Code = 1, which would only return values for which the FIRST. and LAST. values for a given variable are both 1, which would indicate that the record in question represents the only instance of that value when sorted by the less deeply nested variables.



[recipe_for_drop_and_swap Week 8 Recipe]
- *Question* (jbettonville-stat6250): When using the COMPRESS function, there does not appear to be an appreciable difference between writing the option characters as 'kd' or as 'dk'; what is reason for selecting the non-alphabetic order option in the recipe example? 
