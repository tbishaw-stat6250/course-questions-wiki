
## Week 3 Quiz Questions and Answers

In order to prepare your Week 3 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-3" in your fork of this repo. Then, after all edits have been made/committed, your Week 3 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-3 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 3, Problem 1]
- Question (ldeng11−stat6250): What are the good practing rules/styles you should follow if you want to write an easy-to-read and easy-to-maintain code? 



[Course Textbook Chapter 3, Problem 2]
- Question (ldeng11−stat6250): What are the steps to debug the code?
- Answer (ldeng11−stat6250): First, check the log window to see what is the error message, then go back to the code to see the specific line of code based on the error message, then make any change if neccessary, run the code again, then check the log window again.

[Course Textbook Chapter 3, Problem 3]
- Question (ldeng11−stat6250): Does the sum function apply to the original dataset? Or it apply to the data after the selection statement?

 
[Course Textbook Chapter 3, Problem 4]
- Question (ldeng11−stat6250): What are the Log window and Output window using for?


[Course Textbook Chapter 3, Problem 5]
- Question (ldeng11−stat6250): What are the common syntax errors?
- Answer (ldeng11−stat6250): Common syntax errors are misspelled keywords, omitting semicolons, quotation marks unbalanced, invalid options etc.

[Course Textbook Chapter 3, Problem 6]
- Question (ldeng11−stat6250): What would happen if you have an invalid option in your code?


[Course Textbook Chapter 3, Problem 7]
- Question (ldeng11−stat6250): What would happen if you have syntax error in your code?


[Course Textbook Chapter 3, Problem 10]
- Question (ldeng11−stat6250): What happen if you see the window display the message "DATA step running" for a long time?


[Course Textbook Chapter 4, Problem 1]
- Question (ldeng11−stat6250): What is the "noobs" option using for?


[Course Textbook Chapter 4, Problem 3]
- Question (ldeng11−stat6250): What is the "in" option using for?


[Course Textbook Chapter 4, Problem 4]
- Question (ldeng11−stat6250): Do you need to include a by statement when you sort the data?


[Course Textbook Chapter 4, Problem 7]
- Question (ldeng11−stat6250): What would happen if you sort the data but don't creat another data set to store the ordered data?
- Answer (ldeng11−stat6250): The original data set would be overwritten by the sorted data set, which is not the good practice because we like to keep the original data set for reference.

[Course Textbook Chapter 4, Problem 9]
- Question (ldeng11−stat6250): What is the running sequence when you have different logical operand in the same statement?


[Course Textbook Chapter 4, Problem 10]
- Question (ldeng11−stat6250): What does PROC PRINT display if you don't specific any options?


[recipe_to_check_for_duplicates Week 3 Recipe]
- Question (ldeng11−stat6250): The assumption for this recipe is the data set has one-to-one relationship between the unique id and the obervations (means one unique id can only have one observation). What if the unique id can have multiple observations, how do you check for duplicates? 


[recipe_for_sorting_data Week 3 Recipe]
- Question (ldeng11−stat6250): How the SAS would sort the data set if you specify multiple variables in the by statement?


[recipe_for_printing_values Week 3 Recipe]
- Question (ldeng11−stat6250): How can you print the only last several rows in the data set. For example, print the last 20 rows?

