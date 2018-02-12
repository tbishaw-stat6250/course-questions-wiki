## Week 7 Quiz Questions and Answers

In order to prepare your Week 7 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-7" in your fork of this repo. Then, after all edits have been made/committed, your Week 7 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-7 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 10, Problem 2]
- Question (nshrivastava2-stat6250): What if you want to initialize Sum Varible to a different number, other than zero?
- Answer(nshrivastava2-stat6250): The RETAIN statement is used to assigns an initial value to a retained variable and prevents variables from being initialized each time the DATA step executes.



[Course Textbook Chapter 10, Problem 6]
- Question (nshrivastava2-stat6250):  How SAS processes the IF-THEN-ELSE statements, if the If expression-1 is true? 
- Answer(nshrivastava2-stat6250): If expression-1 is true, SAS executes statement-1 and does NOT check the remaining ELSE IF statements. SAS will then continue to process any additional code following the block of IF-THEN-ELSE statements.



[Course Textbook Chapter 10, Problem 7]
- Question (nshrivastava2-stat6250): What is the  expression to an accumulator variable?



[Course Textbook Chapter 10, Problem 8]
- Question (nshrivastava2-stat6250): How the assignment statements assign a missing value ?
- Answer(nshrivastava2-stat6250): If the expression produces a missing value, the sum statement ignores it. However, that assignment statements assign a missing value if the expression produces a missing value.



[Course Textbook Chapter 10, Problem 9]
- Question (nshrivastava2-stat6250): What if you want to initialize sum varible to a different number, other than zero?
- Answer(nshrivastava2-stat6250): The RETAIN statement is used to assigns an initial value to a retained variable and prevents variables from being initialized each time the DATA step executes.



[Course Textbook Chapter 10, Problem 10]
- Question (nshrivastava2-stat6250): What is the default number of bytes that SAS uses to store the values of any newly created numeric variables?



[Course Textbook Chapter 11, Problem 1]
- Question (nshrivastava2-stat6250): Where to specify DROP= and KEEP= options ?
- Answer(nshrivastava2-stat6250): One can specify DROP= and KEEP= in either the DATA statement or the SET statement, depending on whether or not one want to process values of the variables in that DATA step. If one don't process certain variables and don't want them to appear in the new data set, then specify them in the DROP= option in the SET statement. And,  If one do need to process a variable in the original data set (in a subsetting IF statemente), one must specify the variable in the DROP= option in the DATA statement. Otherwise, the statement that is using the variable for processing causes an error.



[Course Textbook Chapter 11, Problem 2]
- Question (nshrivastava2-stat6250): What is the POINT= Option  ?
- Answer(nshrivastava2-stat6250):  One can access observations directly, by going straight to an observation in a SAS data set without having to process each observation that precedes it. To access observations directly by their observation number, you use the POINT= option in the SET statement. 



[Course Textbook Chapter 11, Problem 3]
- Question (nshrivastava2-stat6250): What STOP statement does?
- Answer(nshrivastava2-stat6250): Use a STOP statement to prevent continuous looping. The STOP statement causes SAS to stop processing the current DATA step immediately and to resume processing statements after the end of the current DATA step. 



[Course Textbook Chapter 11, Problem 8]
- Question (nshrivastava2-stat6250): Can we specify END= with POINT= ?
- Answer(nshrivastava2-stat6250):  No, Do not specify END= with POINT= because POINT= reads only a specific observation, so the last observation in the data set is not encountered. 



[Course Textbook Chapter 11, Problem 9]
- Question (nshrivastava2-stat6250): If there is no end-of-file condition, while direct access to read the data, so how can your program prevent a continuous loop?
- Answer(nshrivastava2-stat6250): To avoid a continuous loop while direct access, either include a STOP statement or use programming logic that checks for an invalid value of the POINT= variable. 



[basic_recipe_for_combining_data_vertically Week 7 Recipe]
- Question (nshrivastava2-stat6250): How END and DO statement works?
- Answer(nshrivastava2-stat6250): The DO statement specifies that the statements following the DO statement be executed as a group until a matching END statement appears. DO statements often appear in IF-THEN/ELSE statements, where they designate groups of statements to be performed when the IF condition is true or false.



[adv_recipe_for_combining_data_vertically Week 7 Recipe]
- Question (nshrivastava2-stat6250): How three set operators UNION, INTERSECT, and EXCEPT are different from each other?
- Answer(nshrivastava2-stat6250): The three set operators are differ in nature from each other in terms of the set-theoretic rules they implement, but resemble one another in terms of their mechanics. UNION, INTERSECT, and EXCEPT do not have simple DATA step counterparts,though some emulation can be programmed.


