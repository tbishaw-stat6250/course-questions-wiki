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
- Question (dfei-stat6250): What will happen if two labels and two formats are assigned to the same variable?
- Question(pcheng14-stat6250):Is "temporary labels or formats that are assigned in a PROC step override temporary labels or formats that are assigned in a DATA step." correct?
- Answer(pcheng14-stat6250):No, correct is "Temporary labels or formats that are assigned in a PROC step override permanent labels or formats that are assigned in a DATA step."
- Question (ldeng11−stat6250): What would happen if you have label and format statement in both DATA setp and Print procedure?
- Answer (ldeng11−stat6250): The label and format you assign in the print procedure will overwrite the ones in the DATA step.



[Course Textbook Chapter 10, Problem 6]
- *Question* (aamiri2-stat6250): What is the general form of an IF-THEN statement and which comparison and logical operators can be used with this?
- Question (dfei-stat6250): Are IF-THEN statements in SAS same to IF-ELSE statements in Python?
- Answer (dfei-stat6250): Yes, both of them are conditional statements.
- Question(pcheng14-stat6250):Do we must enclose character values in quotation marks?
- Answer(pcheng14-stat6250):Yes, we do.
- Question (ldeng11−stat6250): What are thr rules when you have logical operand in the IF-THEN statement?



[Course Textbook Chapter 10, Problem 7]
- *Question* (aamiri2-stat6250): Is it possible to specify and limit the length of a variable using the LENGTH statement in the DATA step?
- Question (dfei-stat6250): What is the command for showing the length of a new variable in SAS?
- Question(pcheng14-stat6250):Is the length of a variable determined by its second reference in the DATA step?
- Answer(pcheng14-stat6250):No, it should be by its first reference in the DATA step.
- Question (ldeng11−stat6250): How many factors can affect the length of a new variable?
- Answer (ldeng11−stat6250): You could use LENGTH statement; assignment statement to define the length of a new variable; or it could be the length of the variable from the first reference in the DATA step.



[Course Textbook Chapter 10, Problem 8]
- *Question* (aamiri2-stat6250): What is the main difference between IF-THEN statements and DROP= KEEP= statements? 
- Question (dfei-stat6250): Can IF-THEN statements equal to IF-ELSE statements?
- Answer (dfei-stat6250): No, they can not.
- Question(pcheng14-stat6250):Can we write multiple ELSE statements to specify a series of mutually exclusive conditions?
- Question (ldeng11−stat6250): What are the advantages using IF-ESLE statements than the multiple IF-THEN statement?



[Course Textbook Chapter 10, Problem 9]
- *Question* (aamiri2-stat6250): What is the main purpose of using a LENGTH statement? What is the general form of it?
- *Answer* (aamiri2-stat6250): LENGTH statement is used to specify the number of bytes for TestLength before the first value is referenced in the DATA step. The general form is usually LENGTH variable(s) <$> length. The variable is the name to be assigned a length, $ is used if it is a character variable, and length is an integer that specifies the length.
- Question (dfei-stat6250): How to determind the length of the variable Type?
- Question(pcheng14-stat6250):How many types of the length of the variable we have?
- Question (ldeng11−stat6250): Where you should place the LENGTH statement if you want to use it in the DATA step?



[Course Textbook Chapter 10, Problem 10]
- *Question* (aamiri2-stat6250): What are the different type of errors that can happen? Are there any precautions that can be taken to avoid these errors?
- Question (dfei-stat6250): Do I have to put drop sumsec in the second choice of the question?
- Question(pcheng14-stat6250):When should we use DROP or KEEP statement in any DATA step?
- Question (ldeng11−stat6250): What are the rules if you want to use KEEP, DROP statement?



[Course Textbook Chapter 11, Problem 1]
- *Question* (aamiri2-stat6250): What are some statements to use while manipulating data using the DATA step?
- Question (dfei-stat6250): What is the squence when I put some variables appear in the new data set?
- Question(pcheng14-stat6250):Besides using the KEEP= option in the SET statement, have any others way can get same result?
- Question (ldeng11−stat6250): What are the rules if you want to use KEEP, DROP option in the DATA step?



[Course Textbook Chapter 11, Problem 2]
- *Question* (aamiri2-stat6250): What statement would be appropriate if I only wanted a certain variable with specific conditions and wanted to drop the rest of the data?
- Question (dfei-stat6250):  Is it possible to read data set Orders and creates the data set FastOrdr in one row command?
- Question(pcheng14-stat6250):When can we drop OrdrTime in the SET statement?
- Question (ldeng11−stat6250): Can you drop the variable in the SET statement if you want to process this variable in the condition statements later?
 - Answer (ldeng11−stat6250): No. If you place the drop statement in the SET statement, you never read the drop variables from the original data set. You need to drop the variables in the DATA statement if you want to use the variables in the condition statementes later.



[Course Textbook Chapter 11, Problem 3]
- *Question* (aamiri2-stat6250): What are the results of using the BY statement with the SET statement?
- *Answer* (aamiri2-stat6250):The data sets listed in the SET statements are sorted by the BY statement values. The DATA step then creates two temporary variables for every BY variable. They will be identified as FIRST.variable and LAST.variable with values of either 1 or 0.
- Question (dfei-stat6250): Can the data sets list in the SET statement be indexed or sorted by the values of the BY variable?
- Answer (dfei-stat6250): Yes, it can.
- Question(pcheng14-stat6250):When will the DATA step create the temporary variables FIRST. and LAST.?
- Question (ldeng11−stat6250): What are First., Last. variables stand for when you use BY-group process?



[Course Textbook Chapter 11, Problem 8]
- *Question* (aamiri2-stat6250): What is the difference between the two options, END= and POINT=. In which situations should these options be used?
- Question (dfei-stat6250): How to figure out whether my command is a a continuous loop or not?
- Question(pcheng14-stat6250):What kind of the program should use the END= option?
- Question (ldeng11−stat6250): What you should do if you only want to select the last observation?



[Course Textbook Chapter 11, Problem 9]
- *Question* (aamiri2-stat6250): What are some syntax errors that can occur in the second step of the compilation phase?
- Question (dfei-stat6250): What does compilation phase mean?
- Question(pcheng14-stat6250):What is the meaning of PDV?
- Question (ldeng11−stat6250): What happend during the data compilation phase?



[basic_recipe_for_combining_data_vertically Week 7 Recipe]
- *Question* (aamiri2-stat6250): While creating values for data source why is it assigned a character value at first?
- Question (dfei-stat6250): If two datasets with same column can not combine together successfully, what will the error messagers show?
- Question(pcheng14-stat6250):What is meaning of "business logic"?
- Question (ldeng11−stat6250): How do you use in= option?



[adv_recipe_for_combining_data_vertically Week 7 Recipe]
- *Question* (aamiri2-stat6250): While using PROC SQL, are datasets allowed to have duplicate rows? If so, how does this affect our data?
- Question (dfei-stat6250): In the second short video, the "select * " command seems like sql language, isn't it?
- Question(pcheng14-stat6250):Why many SAS programers rely on proc sql for the bulk of thier data manipulation tasks?
- Question (ldeng11−stat6250): Can you write the equivalent DATA step code to repalce the PROC SQL code?



