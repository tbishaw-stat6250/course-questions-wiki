## Week 7 Quiz Questions and Answers

In order to prepare your Week 7 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-7" in your fork of this repo. Then, after all edits have been made/committed, your Week 7 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-7 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 10, Problem 2]
- *Question* (aamiri2-stat6250): How can you add the results of an expression to an accumulator variable?
- *Answer* (aamiri2-stat6250): To do this you must use a sum statement in your DATA step which generally is just variable + expression. Variable is the name of the accumulator variable and is numeric whereas the expression is any valid SAS expression. 



[Course Textbook Chapter 10, Problem 6]
- *Question* (aamiri2-stat6250): What is the general form of an IF-THEN statement and which comparison and logical operators can be used with this?



[Course Textbook Chapter 10, Problem 7]
- *Question* (aamiri2-stat6250): Is it possible to specify and limit the length of a variable using the LENGTH statement in the DATA step?



[Course Textbook Chapter 10, Problem 8]
- *Question* (aamiri2-stat6250): What is the main difference between IF-THEN statements and DROP= KEEP= statements? 



[Course Textbook Chapter 10, Problem 9]
- *Question* (aamiri2-stat6250): What is the main purpose of using a LENGTH statement? What is the general form of it?
- *Answer* (aamiri2-stat6250): LENGTH statement is used to specify the number of bytes for TestLength before the first value is referenced in the DATA step. The general form is usually LENGTH variable(s) <$> length. The variable is the name to be assigned a length, $ is used if it is a character variable, and length is an integer that specifies the length.



[Course Textbook Chapter 10, Problem 10]
- *Question* (aamiri2-stat6250): What are the different type of errors that can happen? Are there any precautions that can be taken to avoid these errors?



[Course Textbook Chapter 11, Problem 1]
- *Question* (aamiri2-stat6250): What are some statements to use while manipulating data using the DATA step?



[Course Textbook Chapter 11, Problem 2]
- *Question* (aamiri2-stat6250): What statement would be appropriate if I only wanted a certain variable with specific conditions and wanted to drop the rest of the data?



[Course Textbook Chapter 11, Problem 3]
- *Question* (aamiri2-stat6250): What are the results of using the BY statement with the SET statement?
- *Answer* (aamiri2-stat6250):The data sets listed in the SET statements are sorted by the BY statement values. The DATA step then creates two temporary variables for every BY variable. They will be identified as FIRST.variable and LAST.variable with values of either 1 or 0.



[Course Textbook Chapter 11, Problem 8]
- *Question* (aamiri2-stat6250): What is the difference between the two options, END= and POINT=. In which situations should these options be used?



[Course Textbook Chapter 11, Problem 9]
- *Question* (aamiri2-stat6250): What are some syntax errors that can occur in the second step of the compilation phase?



[basic_recipe_for_combining_data_vertically Week 7 Recipe]
- *Question* (aamiri2-stat6250): While creating values for data source why is it assigned a character value at first?



[adv_recipe_for_combining_data_vertically Week 7 Recipe]
- *Question* (aamiri2-stat6250): While using PROC SQL, are datasets allowed to have duplicate rows? If so, how does this affect our data?


