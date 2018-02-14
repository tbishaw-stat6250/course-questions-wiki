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
- *Question* (asharda-stat6250): Do labels and format affect how data is stored in data set?
- *Answer* (asharda-stat6250): Labels and Formats do not affect how data is stored in the data set, but only how it appears in output.
- *Question* (aacharya4−stat6250): What happens in case the format of a variable is provided in both DATA step and PROC step?
- *Answer* (aacharya4−stat6250): The temporary format of the variable assigned in PROC step overides the permanent formatting assigned to the variable in DATA step.
- Question (lceballos-stat6250): What does the format "comma10." do?
- Question (nshrivastava2-stat6250): What if you want to initialize Sum Varible to a different number, other than zero?
- Answer(nshrivastava2-stat6250): The RETAIN statement is used to assigns an initial value to a retained variable and prevents variables from being initialized each time the DATA step executes.



[Course Textbook Chapter 10, Problem 6]
- *Question* (aamiri2-stat6250): What is the general form of an IF-THEN statement and which comparison and logical operators can be used with this?
- Question (dfei-stat6250): Are IF-THEN statements in SAS same to IF-ELSE statements in Python?
- Answer (dfei-stat6250): Yes, both of them are conditional statements.
- Question(pcheng14-stat6250):Do we must enclose character values in quotation marks?
- Answer(pcheng14-stat6250):Yes, we do.
- Question (ldeng11−stat6250): What are thr rules when you have logical operand in the IF-THEN statement?
- *Question* (asharda-stat6250): What is the advantage of using ELSE statement with IF-THEN statement?.
- *Answer* (asharda-stat6250): Using ELSE statements with IF-THEN statements can save resources.
- *Question* (aacharya4−stat6250): What are the possible results that are possible from using IF-THEN statement in SAS?
- *Answer* (aacharya4−stat6250): IF-THEN statement in SAS produces a result that is either nonzero, zero, or missing. If result is nonzero,nonmissing value, then TRUE; if result is zerp, missing value, then FALSE.
- Question (lceballos-stat6250): If two IF commands are false what is the output?
- Question (nshrivastava2-stat6250):  How SAS processes the IF-THEN-ELSE statements, if the If expression-1 is true? 
- Answer(nshrivastava2-stat6250): If expression-1 is true, SAS executes statement-1 and does NOT check the remaining ELSE IF statements. SAS will then continue to process any additional code following the block of IF-THEN-ELSE statements.



[Course Textbook Chapter 10, Problem 7]
- *Question* (aamiri2-stat6250): Is it possible to specify and limit the length of a variable using the LENGTH statement in the DATA step?
- Question (dfei-stat6250): What is the command for showing the length of a new variable in SAS?
- Question(pcheng14-stat6250):Is the length of a variable determined by its second reference in the DATA step?
- Answer(pcheng14-stat6250):No, it should be by its first reference in the DATA step.
- Question (ldeng11−stat6250): How many factors can affect the length of a new variable?
- Answer (ldeng11−stat6250): You could use LENGTH statement; assignment statement to define the length of a new variable; or it could be the length of the variable from the first reference in the DATA step.
- *Question* (asharda-stat6250): How do you find length of new variable in SAS?.
- *Question* (aacharya4−stat6250): How is the length of a variable determined in SAS?
- *Answer* (aacharya4−stat6250): The length of a variable in SAS can be determined by VLENGTH or VARLEN function.
- Question (lceballos-stat6250): Do you need to specify the length if using SQL statements?
- Question (nshrivastava2-stat6250): What is the  expression to an accumulator variable?



[Course Textbook Chapter 10, Problem 8]
- *Question* (aamiri2-stat6250): What is the main difference between IF-THEN statements and DROP= KEEP= statements? 
- Question (dfei-stat6250): Can IF-THEN statements equal to IF-ELSE statements?
- Answer (dfei-stat6250): No, they can not.
- Question(pcheng14-stat6250):Can we write multiple ELSE statements to specify a series of mutually exclusive conditions?
- Question (ldeng11−stat6250): What are the advantages using IF-ESLE statements than the multiple IF-THEN statement?
- *Question* (asharda-stat6250): Can you write multiple ELSE statements.
- *Answer* (asharda-stat6250): You can write multiple ELSE statements to specify a series of mutually exclusive conditions.
- *Question* (aacharya4−stat6250): In SAS, in what other ways one can perform the task of conditional processing as used in IF-THEN-ELSE statements?
- *Answer* (aacharya4−stat6250): In SAS, one can use the PROC FORMAT or SELECT statement in place of IF-THEN-ELSE statements for conditional processing.
- Question (lceballos-stat6250): Can you use CASE statements in SAS?
- Answer (lceballos-stat6250): Yes, you can use them in a PROC SQL step (e.g select Name, case when).
- Question (nshrivastava2-stat6250): How the assignment statements assign a missing value ?
- Answer(nshrivastava2-stat6250): If the expression produces a missing value, the sum statement ignores it. However, that assignment statements assign a missing value if the expression produces a missing value.



[Course Textbook Chapter 10, Problem 9]
- *Question* (aamiri2-stat6250): What is the main purpose of using a LENGTH statement? What is the general form of it?
- *Answer* (aamiri2-stat6250): LENGTH statement is used to specify the number of bytes for TestLength before the first value is referenced in the DATA step. The general form is usually LENGTH variable(s) <$> length. The variable is the name to be assigned a length, $ is used if it is a character variable, and length is an integer that specifies the length.
- Question (dfei-stat6250): How to determind the length of the variable Type?
- Question(pcheng14-stat6250):How many types of the length of the variable we have?
- Question (ldeng11−stat6250): Where you should place the LENGTH statement if you want to use it in the DATA step?
- *Question* (asharda-stat6250): What is the length of new variable determined by?
- *Answer* (asharda-stat6250): The length of a new variable is determined by the first reference in the DATA step.
- *Question* (aacharya4−stat6250): How is the use of LENGTH statement in SAS?
- *Answer* (aacharya4−stat6250): The LENGTH statement is used to set the length of a variable to a desired value. 
- Question (lceballos-stat6250): Where should the length statement go?
- Answer (lceballos-stat6250): Before the variable is ever mentioned in the data step.
- Question (nshrivastava2-stat6250): What if you want to initialize sum varible to a different number, other than zero?
- Answer(nshrivastava2-stat6250): The RETAIN statement is used to assigns an initial value to a retained variable and prevents variables from being initialized each time the DATA step executes.



[Course Textbook Chapter 10, Problem 10]
- *Question* (aamiri2-stat6250): What are the different type of errors that can happen? Are there any precautions that can be taken to avoid these errors?
- Question (dfei-stat6250): Do I have to put drop sumsec in the second choice of the question?
- Question(pcheng14-stat6250):When should we use DROP or KEEP statement in any DATA step?
- Question (ldeng11−stat6250): What are the rules if you want to use KEEP, DROP statement?
- *Question* (asharda-stat6250): Which statements can you use to select variables?.
- *Answer* (asharda-stat6250): You can use a DROP or KEEP statement in any DATA step. 
- *Question* (aacharya4−stat6250): How can a DROP statement be used in a PROC step?
- *Answer* (aacharya4−stat6250): If used in a PROC statement, the DROP dataset option should be used follwed by a dataset name. For eg: proc print data=salary(drop=employee address);
- Question (lceballos-stat6250): Can you use DROP or KEEP in a SQL step?
- Question (nshrivastava2-stat6250): What is the default number of bytes that SAS uses to store the values of any newly created numeric variables?



[Course Textbook Chapter 11, Problem 1]
- *Question* (aamiri2-stat6250): What are some statements to use while manipulating data using the DATA step?
- Question (dfei-stat6250): What is the squence when I put some variables appear in the new data set?
- Question(pcheng14-stat6250):Besides using the KEEP= option in the SET statement, have any others way can get same result?
- Question (ldeng11−stat6250): What are the rules if you want to use KEEP, DROP option in the DATA step?
- *Question* (asharda-stat6250): What is the significance of using KEEP=option in the SET statement?.
- *Question* (aacharya4−stat6250): What is the difference between KEEP data set option and KEEP statement in a DATA step?
- *Answer* (aacharya4−stat6250): In DATA step, the KEEP data set option is for both input and output data sets, while the KEEP sttement is only for output data sets.
- Question (lceballos-stat6250): Does the drop statement delete original data or does it just exclude it from the new dataset?
- Question (nshrivastava2-stat6250): Where to specify DROP= and KEEP= options ?
- Answer(nshrivastava2-stat6250): One can specify DROP= and KEEP= in either the DATA statement or the SET statement, depending on whether or not one want to process values of the variables in that DATA step. If one don't process certain variables and don't want them to appear in the new data set, then specify them in the DROP= option in the SET statement. And,  If one do need to process a variable in the original data set (in a subsetting IF statemente), one must specify the variable in the DROP= option in the DATA statement. Otherwise, the statement that is using the variable for processing causes an error.



[Course Textbook Chapter 11, Problem 2]
- *Question* (aamiri2-stat6250): What statement would be appropriate if I only wanted a certain variable with specific conditions and wanted to drop the rest of the data?
- Question (dfei-stat6250):  Is it possible to read data set Orders and creates the data set FastOrdr in one row command?
- Question(pcheng14-stat6250):When can we drop OrdrTime in the SET statement?
- Question (ldeng11−stat6250): Can you drop the variable in the SET statement if you want to process this variable in the condition statements later?
 - Answer (ldeng11−stat6250): No. If you place the drop statement in the SET statement, you never read the drop variables from the original data set. You need to drop the variables in the DATA statement if you want to use the variables in the condition statementes later.
- *Question* (asharda-stat6250): How do you prevent variables from being written to the data set?
- *Answer* (asharda-stat6250): The DROP= data set option prevents variables from being written to the data set .
- *Question* (aacharya4−stat6250): What is the purpose of using DROP data set option in DATA step?
- *Answer* (aacharya4−stat6250): The purpose of using DROP data set option in DATA step is to prevent the mentioned variables in DROP data set option from being written to the data set.
- Question (lceballos-stat6250): Is "drop=ordrtime" necessary in this recipe?
- Question (nshrivastava2-stat6250): What is the POINT= Option  ?
- Answer(nshrivastava2-stat6250):  One can access observations directly, by going straight to an observation in a SAS data set without having to process each observation that precedes it. To access observations directly by their observation number, you use the POINT= option in the SET statement. 



[Course Textbook Chapter 11, Problem 3]
- *Question* (aamiri2-stat6250): What are the results of using the BY statement with the SET statement?
- *Answer* (aamiri2-stat6250):The data sets listed in the SET statements are sorted by the BY statement values. The DATA step then creates two temporary variables for every BY variable. They will be identified as FIRST.variable and LAST.variable with values of either 1 or 0.
- Question (dfei-stat6250): Can the data sets list in the SET statement be indexed or sorted by the values of the BY variable?
- Answer (dfei-stat6250): Yes, it can.
- Question(pcheng14-stat6250):When will the DATA step create the temporary variables FIRST. and LAST.?
- Question (ldeng11−stat6250): What are First., Last. variables stand for when you use BY-group process?
- *Question* (asharda-stat6250): What happens when you use BY statement with the SET statement?.
- *Question* (aacharya4−stat6250): What are the two variables created by DATA step when BY statement is used with SET statement?
- *Answer* (aacharya4−stat6250): The DATA step automatically creates a FIRST. and LAST. variable for each variable mentioned in BY statement to sidentify first and last observation of each BY group.
- Question (lceballos-stat6250): What are the FIRST. and LAST variables used for?
- Answer (lceballos-stat6250): To identify the first and last observation when sorting with a BY statement.
- Question (nshrivastava2-stat6250): What STOP statement does?
- Answer(nshrivastava2-stat6250): Use a STOP statement to prevent continuous looping. The STOP statement causes SAS to stop processing the current DATA step immediately and to resume processing statements after the end of the current DATA step. 



[Course Textbook Chapter 11, Problem 8]
- *Question* (aamiri2-stat6250): What is the difference between the two options, END= and POINT=. In which situations should these options be used?
- Question (dfei-stat6250): How to figure out whether my command is a a continuous loop or not?
- Question(pcheng14-stat6250):What kind of the program should use the END= option?
- Question (ldeng11−stat6250): What you should do if you only want to select the last observation?
- *Question* (asharda-stat6250): When do you use END=option?.
- *Question* (aacharya4−stat6250): What is the use of END data set option in SAS?
- *Answer* (aacharya4−stat6250): The END data set option is to signify a temporary variable that contains the end-of-file marker.
- Question (lceballos-stat6250): What is the purpose of the statement "if last;"?
- Question (nshrivastava2-stat6250): Can we specify END= with POINT= ?
- Answer(nshrivastava2-stat6250):  No, Do not specify END= with POINT= because POINT= reads only a specific observation, so the last observation in the data set is not encountered. 



[Course Textbook Chapter 11, Problem 9]
- *Question* (aamiri2-stat6250): What are some syntax errors that can occur in the second step of the compilation phase?
- Question (dfei-stat6250): What does compilation phase mean?
- Question(pcheng14-stat6250):What is the meaning of PDV?
- Question (ldeng11−stat6250): What happend during the data compilation phase?
- *Question* (asharda-stat6250): What is the general form basic DATA step for reading a single data set?
- *Question* (aacharya4−stat6250): What is Program Data Vector (PDV)?
- *Answer* (aacharya4−stat6250): PDV is a logiacal memory area created during the compilation of a DATA step process. SAS reads one observation at a time to PDV to make the SAS dataset.
- Question (lceballos-stat6250): What is the program data vector (PDV)?
- Question (nshrivastava2-stat6250): If there is no end-of-file condition, while direct access to read the data, so how can your program prevent a continuous loop?
- Answer(nshrivastava2-stat6250): To avoid a continuous loop while direct access, either include a STOP statement or use programming logic that checks for an invalid value of the POINT= variable. 



[basic_recipe_for_combining_data_vertically Week 7 Recipe]
- *Question* (aamiri2-stat6250): While creating values for data source why is it assigned a character value at first?
- Question (dfei-stat6250): If two datasets with same column can not combine together successfully, what will the error messagers show?
- Question(pcheng14-stat6250):What is meaning of "business logic"?
- Question (ldeng11−stat6250): How do you use in= option?
- *Question* (asharda-stat6250): What is a defensive programming practice?
- *Question* (aacharya4−stat6250): What is the purpose of using IN data set option in SAS?
- *Answer* (aacharya4−stat6250): The IN data set option names the indicator variable that determines whether the input data set is part of the current observation. The value of the indicator variable is 1, if input data set contributes to current  observation. Otherwise, the value of indicator variable is 0.
- Question (lceballos-stat6250): What does the IN statement used for in this recipe?
- Question (nshrivastava2-stat6250): How END and DO statement works?
- Answer(nshrivastava2-stat6250): The DO statement specifies that the statements following the DO statement be executed as a group until a matching END statement appears. DO statements often appear in IF-THEN/ELSE statements, where they designate groups of statements to be performed when the IF condition is true or false.



[adv_recipe_for_combining_data_vertically Week 7 Recipe]
- *Question* (aamiri2-stat6250): While using PROC SQL, are datasets allowed to have duplicate rows? If so, how does this affect our data?
- Question (dfei-stat6250): In the second short video, the "select * " command seems like sql language, isn't it?
- Question(pcheng14-stat6250):Why many SAS programers rely on proc sql for the bulk of thier data manipulation tasks?
- Question (ldeng11−stat6250): Can you write the equivalent DATA step code to repalce the PROC SQL code?
- *Question* (asharda-stat6250): Does using "union" allow datasets to contain duplicates?
- *Question* (aacharya4−stat6250): What is the change needed in the code of this recipe to select the rows that are common in both the datasets?
- *Answer* (aacharya4−stat6250): In oreder to select the rows that are common in both the datasets, "union" in the code should be replaced by "intersect".
- Question (lceballos-stat6250): How does the statement "union all corr" work?
- Question (nshrivastava2-stat6250): How three set operators UNION, INTERSECT, and EXCEPT are different from each other?
- Answer(nshrivastava2-stat6250): The three set operators are differ in nature from each other in terms of the set-theoretic rules they implement, but resemble one another in terms of their mechanics. UNION, INTERSECT, and EXCEPT do not have simple DATA step counterparts,though some emulation can be programmed.



