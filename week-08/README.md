## Week 8 Quiz Questions and Answers

In order to prepare your Week 8 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-8" in your fork of this repo. Then, after all edits have been made/committed, your Week 8 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-8 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 13, Problem 1]
- Question (ttruong59-stat6250): When specifying a variable list for mean function, preceding the list with the word OF is required as mean(of var1-var) for example? What happens if users omit the word OF?
- Answer (ttruong59-stat6250): If users omit the word OF, the function returns var1-var4, not the average of the variable var1, var2, var3, var4.



[Course Textbook Chapter 13, Problem 2]
- Question (ttruong59-stat6250): Under what step that SAS will auto convert the character values to numeric values so that the calculation can occur?
- Answer (ttruong59-stat6250): When the DATA step is executed, SAS will convert the character values to numeric values so that the calculation can occur.



[Course Textbook Chapter 13, Problem 3]
- Question (ttruong59-stat6250): What is a major difference of using INPUT and PUT function when creating the variable?
- Answer (ttruong59-stat6250): INPUT function used to convert character values to numeric values while PUT function used to convert numeric values to character values.



[Course Textbook Chapter 13, Problem 4]
- Question (ttruong59-stat6250): What happens if we use the PUT function to create a variable that has not been previously identified?
- Answer (ttruong59-stat6250): It will create a character variable whose length is equal to the format width.



[Course Textbook Chapter 13, Problem 5]
- Question (ttruong59-stat6250): Is it possible to reset the YEARCUTOFF= system option, instead of using 1920 as a default? 



[Course Textbook Chapter 13, Problem 6]
- Question (ttruong59-stat6250): What is a major difference between SCAN and SUBSTR function?
- Answer (ttruong59-stat6250): SCAN function is used to return a specified word from a character value while SUBSTR function is used to extract a substring or to replace character values.



[Course Textbook Chapter 13, Problem 7]
- Question (ttruong59-stat6250): How to distinguish a SUBSTR function which is used to extract a substring or is used to replace character values?
- Answer (ttruong59-stat6250): The best way to recognize its use is to look at the side of the statement. The function is used to extract a substring if the SUBSTR function is on the right side. And the function is used to replace the contents of the character variable if the SUBSTR function is on the left side.



[Course Textbook Chapter 13, Problem 10]
- Question (ttruong59-stat6250): Is INDEX function case-sensitive so the character string we search for must be specified exactly as it is recorded in the dataset? If so, is there any alternative function to search for but it is not case-sensitive?
- Answer (ttruong59-stat6250): Yes, INDEX function is case-sensitive. we can use FIND function which is similar to INDEX to complete the search.



[recipe_for_isolating_all_duplicates Week 8 Recipe]
- Question (ttruong59-stat6250): What happens if first.School_Code*last.School_Code will equal 1?



[recipe_for_drop_and_swap Week 8 Recipe]
- Question (ttruong59-stat6250): What is a main purpose of using the ‘kd’ option and the format best12. for this recipe?
- Answer (ttruong59-stat6250): The 'kd' option is used to remove all other characters and keep digits only. And best12. is used to set the default format for numerical variables having no value after the decimal point.


