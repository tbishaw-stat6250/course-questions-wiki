## Week 9 Quiz Questions and Answers

In order to prepare your Week 9 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-9" in your fork of this repo. Then, after all edits have been made/committed, your Week 9 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-9 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 14, Problem 1]
- *Question* (ldai4-stat6250): What is DO loops?
- *Answer* (ldai4-stat6250): The DO loops are DATA step statement and cannot be used in conjunction with PROC steps.



[Course Textbook Chapter 14, Problem 2]
- *Question* (ldai4-stat6250): Is the number of iterations determined by the DO statement's stop value?



[Course Textbook Chapter 14, Problem 3]
- *Question* (ldai4-stat6250): Can the DO loop statement be used to calculate a balance with a constant interest?



[Course Textbook Chapter 14, Problem 4]
- *Question* (ldai4-stat6250): Why do we need to specify an index variable when creating a DO loop with the iterative DO statement?
- *Answer* (ldai4-stat6250): The index variable stores the value of the current iteration of the DO loop.



[Course Textbook Chapter 14, Problem 5]
- *Question* (ldai4-stat6250): Does the OUTPUT statement override the automatic output at the end of the dATA step?



[Course Textbook Chapter 14, Problem 6]
- *Question* (ldai4-stat6250): What determines the number of observations in DO loop statement?
- *Answer* (ldai4-stat6250): The number of observation is based on the number of times the OUTPUT statement executes.



[Course Textbook Chapter 14, Problem 7]
- *Question* (ldai4-stat6250): What is the difference between DO WHILE statement and DO UNTIL statement?



[Course Textbook Chapter 14, Problem 8]
- *Question* (ldai4-stat6250): In executing DO until statement, are the enclosed statement always executed at least once?



[Course Textbook Chapter 14, Problem 9]
- *Question* (ldai4-stat6250): Why do we need to specify the condition in DO WHILE statement?



[Course Textbook Chapter 14, Problem 10]
- *Question* (ldai4-stat6250): If we want to the DO LOOP to stop executing some condition, should we use the WHILE statement?



[Course Textbook Chapter 15, Problem 1]
- *Question* (ldai4-stat6250): What is ARRAY statement?
- *Answer* (ldai4-stat6250): The ARRAY statement can be used to create variables, must contain either all numeric or all character elements, and must be used to define an array before the array name can be referenced.



[Course Textbook Chapter 15, Problem 2]
- *Question* (ldai4-stat6250): Does the value in parentheses indicate the number of elements in the array?



[Course Textbook Chapter 15, Problem 3]
- *Question* (ldai4-stat6250): How can we specify the index variable that represents the values of the array elements in the DO statement?
- *Answer* (ldai4-stat6250): We need to specify the start and stop position of the array elements. 



[Course Textbook Chapter 15, Problem 4]
- *Question* (ldai4-stat6250): What does the index value represent?



[Course Textbook Chapter 15, Problem 5]
- *Question* (ldai4-stat6250): How can we use the DIM function?



[Course Textbook Chapter 15, Problem 6]
- *Question* (ldai4-stat6250): Do we need to specify the array elements in the ARRAY statement?



[Course Textbook Chapter 15, Problem 7]
- *Question* (ldai4-stat6250): Can we give an array the same name as a variqable in the same DATA step?



[Course Textbook Chapter 15, Problem 8]
- *Question* (ldai4-stat6250): How temporary array element can be created?
- *Answer* (ldai4-stat6250): To create temporary array element, specify _TEMPORARY_ after the array name and dimension, specify an inital value for each element, separated by either blanks or commas, and enclose the values in parentheses.



[Course Textbook Chapter 15, Problem 9]
- *Question* (ldai4-stat6250): How do we specify the array reference in the nested DO loops?



[recipe_to_create_unique_record_id Week 9 Recipe]
- *Question* (ldai4-stat6250): How can I assign serial numbers to observations in a data set?



[recipe_to_disaggregate_counts_data Week 9 Recipe]
- *Question* (ldai4-stat6250): In using PROC mean statement, how can we calculate disaggregate statistics?


