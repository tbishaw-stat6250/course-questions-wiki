## Week 7 Quiz Questions and Answers

In order to prepare your Week 7 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-7" in your fork of this repo. Then, after all edits have been made/committed, your Week 7 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-7 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 10, Problem 2]
- Question (ldeng11−stat6250): What would happen if you have label and format statement in both DATA setp and Print procedure?
- Answer (ldeng11−stat6250): The label and format you assign in the print procedure will overwrite the ones in the DATA step.



[Course Textbook Chapter 10, Problem 6]
- Question (ldeng11−stat6250): What are thr rules when you have logical operand in the IF-THEN statement?



[Course Textbook Chapter 10, Problem 7]
- Question (ldeng11−stat6250): How many factors can affect the length of a new variable?
- Answer (ldeng11−stat6250): You could use LENGTH statement; assignment statement to define the length of a new variable; or it could be the length of the variable from the first reference in the DATA step.



[Course Textbook Chapter 10, Problem 8]
- Question (ldeng11−stat6250): What are the advantages using IF-ESLE statements than the multiple IF-THEN statement?



[Course Textbook Chapter 10, Problem 9]
- Question (ldeng11−stat6250): Where you should place the LENGTH statement if you want to use it in the DATA step?



[Course Textbook Chapter 10, Problem 10]
- Question (ldeng11−stat6250): What are the rules if you want to use KEEP, DROP statement?



[Course Textbook Chapter 11, Problem 1]
- Question (ldeng11−stat6250): What are the rules if you want to use KEEP, DROP option in the DATA step?



[Course Textbook Chapter 11, Problem 2]
- Question (ldeng11−stat6250): Can you drop the variable in the SET statement if you want to process this variable in the condition statements later?
 - Answer (ldeng11−stat6250): No. If you place the drop statement in the SET statement, you never read the drop variables from the original data set. You need to drop the variables in the DATA statement if you want to use the variables in the condition statementes later.



[Course Textbook Chapter 11, Problem 3]
- Question (ldeng11−stat6250): What are First., Last. variables stand for when you use BY-group process?



[Course Textbook Chapter 11, Problem 8]
- Question (ldeng11−stat6250): What you should do if you only want to select the last observation?



[Course Textbook Chapter 11, Problem 9]
- Question (ldeng11−stat6250): What happend during the data compilation phase?



[basic_recipe_for_combining_data_vertically Week 7 Recipe]
- Question (ldeng11−stat6250): How do you use in= option?



[adv_recipe_for_combining_data_vertically Week 7 Recipe]
- Question (ldeng11−stat6250): Can you write the equivalent DATA step code to repalce the PROC SQL code?


