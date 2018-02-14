## Week 7 Quiz Questions and Answers

In order to prepare your Week 7 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-7" in your fork of this repo. Then, after all edits have been made/committed, your Week 7 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-7 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 10, Problem 2]
- Question (tchan49-stat6250):Is the label statement in DATA step permanent or temporary? 
- Answer (tchan49-stat6250): The label statement in DATA Step is permanent that would be overwritten by the label statement in PORC print that is temporary. 



[Course Textbook Chapter 10, Problem 6]
- Question (tchan49-stat6250):Can IF-THEN statement be still excuted if character values are in the different case from in which they appear in original dataset? 
- Answer (tchan49-stat6250):No, it cannot. 



[Course Textbook Chapter 10, Problem 7]
- Question (tchan49-stat6250):If the length of the variable's first reference in DATA step is 6, what is the length of the new variable? 



[Course Textbook Chapter 10, Problem 8]
- Question (tchan49-stat6250):Would ELSE statement execute if the previous IF-THEN/ELSE is true? 
- Answer (tchan49-stat6250):ELSE statement excutes only if the previous IF-THEN/ELSE is false. 



[Course Textbook Chapter 10, Problem 9]
- Question (tchan49-stat6250):Where shoud LENGTH statement be placed in DATA step? Before or all the reference to variables in DATA step? 



[Course Textbook Chapter 10, Problem 10]
- Question (tchan49-stat6250):Can KEEP or DROP statement be written in PORC statement? 




[Course Textbook Chapter 11, Problem 1]
- Question (tchan49-stat6250):What is the difference between having DROP/KEEP option in SET statement or DATA step? 



[Course Textbook Chapter 11, Problem 2]
- Question (tchan49-stat6250):Can you drop a variable in DATA step that isn't kept in SET statement? 



[Course Textbook Chapter 11, Problem 3]
- Question (tchan49-stat6250):Are First. and LAST. temporary variables? 



[Course Textbook Chapter 11, Problem 8]
- Question (tchan49-stat6250):When you only want to select only the last observation of the dataset, do you put end=last at the end of SET statement ot DATA step? 
- Answer (tchan49-stat6250): At the end of SET statement and also finish it with "if last;" at the end of data step before run statement. 



[Course Textbook Chapter 11, Problem 9]
- Question (tchan49-stat6250):When the descriptor portion of the new SAS dataset id created, has the DATA step executed yet?



[basic_recipe_for_combining_data_vertically Week 7 Recipe]
- Question (tchan49-stat6250): What is the benefit having in= dataset option? 



[adv_recipe_for_combining_data_vertically Week 7 Recipe]
- Question (tchan49-stat6250): Can "UNION all corr" make sure that all columns with corresponding name are matched up even in different positions? 


