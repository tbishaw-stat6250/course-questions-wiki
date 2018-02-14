## Week 7 Quiz Questions and Answers

In order to prepare your Week 7 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-7" in your fork of this repo. Then, after all edits have been made/committed, your Week 7 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-7 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 10, Problem 2]
- *Question* (akrishnamurthy-stat6250): Can multiple formats be assigned to same variable?



[Course Textbook Chapter 10, Problem 6]
- *Question* (akrishnamurthy-stat6250): Does the control break out of IF loop if condition is satisfied or all the IF statements are executed in order?



[Course Textbook Chapter 10, Problem 7]
- *Question* (akrishnamurthy-stat6250): Can the length of a variable be altered and reassigned after being referenced first in a DATA step?
- *Answer* (akrishnamurthy-stat6250): No, LENGTH statement will not change the size of a variable if it was created before in another statement. Hence best practice is to make sure that the LENGTH statement appears before any reference to the variable in DATA step.



[Course Textbook Chapter 10, Problem 8]
- *Question* (akrishnamurthy-stat6250): What is the best coding practice to evaluate mutually exclusive conditions?
- *Answer* (akrishnamurthy-stat6250): Using ELSE statements is a good practice for conditional processing and IF-THEN/ELSE should be constructed with conditions of decreasing probability.We can also use SELECT groups in DATA steps for mutually exclusive conditions and it is more efficient that multiple IF-THEN-ELSE statements.



[Course Textbook Chapter 10, Problem 9]
- *Question* (akrishnamurthy-stat6250): Is the length of a variable fixed or does it change with each reference ?



[Course Textbook Chapter 10, Problem 10]
- *Question* (akrishnamurthy-stat6250): What is the use of DROP or KEEP statements in DATA and PROC steps?



[Course Textbook Chapter 11, Problem 1]
- *Question* (akrishnamurthy-stat6250):How to retain only few variables from a dataset after processing? 



[Course Textbook Chapter 11, Problem 2]
- *Question* (akrishnamurthy-stat6250):Is it necessary to carry over all the variables that are being evaluated to output dataset? Can the variables being evaluated be dropped from output dataset?



[Course Textbook Chapter 11, Problem 3]
- *Question* (akrishnamurthy-stat6250): Should the dataset be sorted in any particular order before being processed by BY statements?



[Course Textbook Chapter 11, Problem 8]
- *Question* (akrishnamurthy-stat6250): What is the difference between END and POINT options?



[Course Textbook Chapter 11, Problem 9]
- *Question* (akrishnamurthy-stat6250): Will the observations be read into the program data vector after compilation ?
- *Answer* (akrishnamurthy-stat6250): At the end of compilation phase only the descriptor portion of new SAS dataset is created and observations are not read.



[basic_recipe_for_combining_data_vertically Week 7 Recipe]
- *Question* (akrishnamurthy-stat6250): Should two datasets be of same length and structure to be combined vertically ? How are differences handled if the file structure is different between the datasets?



[adv_recipe_for_combining_data_vertically Week 7 Recipe]
- *Question* (akrishnamurthy-stat6250): How to perform right outer join of two datasets using PROC SQL statement?


