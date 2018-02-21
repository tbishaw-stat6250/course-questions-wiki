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
- *Question* (cli19-stat6250): How can variable labels and formats be changed? 
- *Answer* (cli19-stat6250): Variable labels and formats can be temporarily changed in PROC steps or permanently changed in DATA steps.
- Question (tbishaw-stat6250): What is the function of a RETAIN statement?  
- Answer (tbishaw-stat6250): A RETAIN statement, assigns an intial value to a retained variable and prevents variables from being initialized each time the DATA step executes.
- Question (tchan49-stat6250):Is the label statement in DATA step permanent or temporary? 
- Answer (tchan49-stat6250): The label statement in DATA Step is permanent that would be overwritten by the label statement in PORC print that is temporary. 
- *Question* (jbettonville-stat6250): If two separate labels are to be used with equal frequency within a program, is there a way to specify multiple labels that can be applied, or does the full text of the secondary label need to be entered each time that label is needed?
- Question (aguenane−stat6250): What is the difference between COMMA6 and COMMA10?
- *Question* (shatcher4-stat6250): Why do character values need to be specified in the same case in which they appear in the data set and enclosed in quotation marks?
- *Question* (who7-stat6250): Is there a way to override the LABEL made in DATA step?
- *Answer* (who7-stat6250): Yes, you can override existing labels made in the DATA Step by creating another label in the PROC step.
- *Question* (jcanfield3-stat6250): Why is the label option needed?
- *Answer* (jcanfield3-stat6250): Without it the data does not know to output the new label within the proc statememt.
- Question (ttruong59-stat6250): Does the variable labeled and formatted in the PROC PRINT output affect how the data is stored in the dataset?
- Answer (ttruong59-stat6250): No, they do not. These labels and formats just appears in the output.
- Question (ljiang11−stat6250): Why the label is not "Amount of Loan"?
- Answer (ljiang11−stat6250): The LABEL statement in PROC PRINT overrides the previous LABEL.
- *Question* (akrishnamurthy-stat6250): Can multiple formats be assigned to same variable?
- *Question* (cnguyen77-stat6250): How does the label and format in PROC PRINT affect the label and format in DATA step?
- *Answer* (cnguyen77-stat6250): Temporary labels or formats that are assigned in a PROC step override permanent labels or formats that are assigned in a DATA step.
- *Question* (ldai4-stat6250): Does the temporary labels or format that are assigned in a PROC step override permanent labels or formats that are assigned in DATA step?
- *Question* (xyin6-stat6250): What is the difference for defining variable format between DATA step and PROC step?
- Question (lsun20-stat6250): What is the usage of the "infile creddata"?
- *Question*(kamirneni-stat6250): What is the advantage of RETAIN statement used in initializing SUM variables? 
- *Answer*(kamirneni-stat6250): The RETAIN statements assigns an initial value to the retained variable and prevents variables from being initialized each time the DATA step executes.
- *Question* (sbagdi-stat6250): What does a RETAIN statement does?



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
- *Question* (cli19-stat6250): When recoding variables using IF-THEN statements, would it be better to create a new variable rather than writing over an existing variable?
- Question (tbishaw-stat6250): What are some of the comparision operators we can use when writing an IF-THEN statements?
- Answer (tbishaw-stat6250): Comparision operators: =oreq (equal to), ^=orne (not equal to), >orgt (greater than), <orlt (less than), >=orge (greater than or equal to), <=orle (less than or equal to), and in (equal to one of a list)
- Question (tchan49-stat6250):Can IF-THEN statement be still excuted if character values are in the different case from in which they appear in original dataset? 
- Answer (tchan49-stat6250):No, it cannot. 
- *Question* (jbettonville-stat6250): How might we create a condition in which the case of the letters in the pattern to match is ignored?
- Question (aguenane−stat6250): For Chapter 10 Quiz, problem 6, if both if statements were false, what would be the values of the variables Count and Control?
- Answer (aguenane-stat6250): The value of Count would be 12 and the value of Control would be Go.
- *Question* (shatcher4-stat6250): How would you perfom an action conditionally in SAS?
- *Answer* (shatcher4-stat6250): Use an IF-THEN statement, which will execute a SAS statement when the condition in the IF clause is true
- *Question* (who7-stat6250): Can i create an extra condition within a condition? E.g. If a and (b or c) Then.
- *Question* (jcanfield3-stat6250): Why does capitalization matter for character values?
- Question (ttruong59-stat6250): When using IF-THEN statement, are the character values case-sensitive?
- Question (ljiang11−stat6250): Will the first IF THEN statement execuate before second IF THEN statement?
- *Question* (akrishnamurthy-stat6250): Does the control break out of IF loop if condition is satisfied or all the IF statements are executed in order?
- *Question* (cnguyen77-stat6250): When does the IF-THEN statement executes a SAS statement?
- *Answer* (cnguyen77-stat6250): The IF-THEN statement executes a SAS statement when the condition in the IF clause is true.
- *Question* (ldai4-stat6250): when can we use the IF-THEN statement?
- *Answer* (ldai4-stat6250):  when we need to perform an action conditionally, the IF-THEN statement should be used. The IF-then statement executes a SAS statement when the condition in the IF clause is true.
- *Question* (xyin6-stat6250): Is the character values in quotation marks always case sensitive?
- Question (lsun20-stat6250): Does capitalization influence the character values everytime in SAS?
- *Question*(kamirneni-stat6250): What functions do we use to read and process variables that we do not want in the dataset?
- *Question* (sbagdi-stat6250): Why should only one condition in a series of conditions should be true in case of using OR operator?



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
- *Question* (cli19-stat6250): What happens if the length of proceeding observations is longer than the variable's first reference in the DATA step?
- *Answer* (cli19-stat6250): This results in WARNING outputs in the log and truncation of observations with that have longer length than what is defined for that variable.
- Question (tbishaw-stat6250): What statement can you add t oassign a value to TestLength when the condition in you IF-THEN statment is false? 
- Question (tchan49-stat6250):If the length of the variable's first reference in DATA step is 6, what is the length of the new variable? 
- *Question* (jbettonville-stat6250): Is it possible to change the length of a variable within a data set once it has been set in a DATA step?
- Question (aguenane−stat6250): What does it mean when a value is truncated?
- Answer (aguenane-stat6250): It means if the value is longer than the assigned length, the value is shortened to the assigned length. 
- *Question* (shatcher4-stat6250): What does the LENGTH statement do?
- *Question* (who7-stat6250): in what situation would we need to get the length of a variable?
- *Answer* (who7-stat6250): You might need to find the length of a variable when there is a limit of length or certain condition where length is required.
- *Question* (jcanfield3-stat6250): Are there any other ways to determine/change variable length?
- Question (ttruong59-stat6250): How do users determine the length of a new variable once IF-THEN and ELSE statement were added to a DATA step?
- Answer (ttruong59-stat6250): Users can use a LENGTH statement to specify a length, the number of bytes, for TestLength before the first value is referenced elsewhere in the DATA step.
- Question (ljiang11−stat6250): What is the maximum length for a new variable?
- *Question* (akrishnamurthy-stat6250): Can the length of a variable be altered and reassigned after being referenced first in a DATA step?
- *Answer* (akrishnamurthy-stat6250): No, LENGTH statement will not change the size of a variable if it was created before in another statement. Hence best practice is to make sure that the LENGTH statement appears before any reference to the variable in DATA step.
- *Question* (cnguyen77-stat6250): How to determine the length of a new variable?
- *Answer* (cnguyen77-stat6250): The length of a variable is determined by its first reference in the DATA step. When creating a new character variable, SAS allocates as many bytes of storage space as there are characters in the reference to that variable. The first reference to a new variable can also be made with a LENGTH statement or an assignment statement.
- *Question* (ldai4-stat6250): What can the length of a new variable be determined by?
- *Answer* (ldai4-stat6250):  The length of a variable is determined by its first reference in the DATA step. When creating a new character variable, SAS allocates as many bytes of storage space as there are characters in the reference to that variable.
- *Question* (xyin6-stat6250): Is the order of If-statements matter in terms of defining variable length?
- *Answer* (xyin6-stat6250): Yes, SAS allocates as many bytes of storage space as there are characters in the first value that it encounters of the variable. So the length of following variables are restricted by first variable length.
- Question (lsun20-stat6250): How the assignment statement determine the length of a new variable?
- *Question*(kamirneni-stat6250): Do the temporary labels and formats assigned during PROC step override the ones in DATA step if assigned?
- *Question* (sbagdi-stat6250): Which is the longest value and how many characters does it have?



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
- *Question* (cli19-stat6250): How does writing separate IF statements differ from IF-ELSE statements for mutually exclusive conditions?
- *Answer* (cli19-stat6250): Utilizing IF-ELSE statements for mutually exclusive conditions can save computation time compared to separate IF statements. Rather than stepping through each IF statement is true or not, IF-ELSE tells SAS to stop and move to the next observation once it encounters a true statement.
- Question (tbishaw-stat6250): When do you want to use an IF-THEN statment with a DELETE statement in SAS? 
- Question (tchan49-stat6250):Would ELSE statement execute if the previous IF-THEN/ELSE is true? 
- Answer (tchan49-stat6250):ELSE statement excutes only if the previous IF-THEN/ELSE is false. 
- *Question* (jbettonville-stat6250): What is the result if non-mutually exclusive conditions are included in an IF-ELSE statement?
- Question (aguenane−stat6250): Why is it more efficient to construct IF-THEN/ELSE statements with conditions of decreasing probability?
- *Question* (shatcher4-stat6250): How can using an ELSE statement with an IF-THEN statemnet save resources?
- *Question* (who7-stat6250): Would we use While loop in SAS?
- *Question* (jcanfield3-stat6250): Why do b, c, and d fail to emulate the desired code?
- *Answer* (jcanfield3-stat6250): Option b rewrites type='Fixed' to type='Unknown', because code="1" isn't excluded.  Option C renames all code ^= 1 to '2' and type to 'variable'; the second else command is also invalidated.  In option D, when Code=1 and Type=Fixed then they are rewritten as Code=2 and Type=Variable, else type='Unknown'.
- Question (ttruong59-stat6250): Are there any limits in term of using ELSE statement to specify a series of mutually exclusive conditions?
- Question (ljiang11−stat6250): What would happen when code is neither 1 or 2?
- *Question* (akrishnamurthy-stat6250): What is the best coding practice to evaluate mutually exclusive conditions?
- *Answer* (akrishnamurthy-stat6250): Using ELSE statements is a good practice for conditional processing and IF-THEN/ELSE should be constructed with conditions of decreasing probability.We can also use SELECT groups in DATA steps for mutually exclusive conditions and it is more efficient that multiple IF-THEN-ELSE statements.
- *Question* (cnguyen77-stat6250): What is the function of ELSE statement?
- *Answer* (cnguyen77-stat6250): You can write multiple ELSE statements to specify a series of mutually exclusive conditions. The ELSE statement must immediately follow the IF-THEN statement in your program. An ELSE statement executes only if the previous IF-THEN/ELSE statement is false.
- *Question* (ldai4-stat6250): Must the ELSE statement immediately follow the IF-THEN statement?
- *Question* (xyin6-stat6250): When we assign values to a variable, should we use quotation marks for both numeric value and character value?
- Question (lsun20-stat6250): How the ELSE statement works?
- Answer (lsun20-stat6250): The ELSE statement works when the previous IF-THEN/ELSE statement is false.
- *Question*(kamirneni-stat6250): Does WHEN statement identify both TRUE and FALSE statements?
- *Question* (sbagdi-stat6250): Why can a numeric value stand alone in a condition?



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
- *Question* (cli19-stat6250): Does the order of the length statement in a DATA step have any affect on the output data set?
- Question (tbishaw-stat6250): What is the key difference between the DROP and KEEP statments? 
- Answer (tbishaw-stat6250): The KEEP and DROP statments are similar, except that the KEEP statement specifies a list of variables to write to output data sets.
- Question (tchan49-stat6250):Where shoud LENGTH statement be placed in DATA step? Before or all the reference to variables in DATA step? 
- *Question* (jbettonville-stat6250): In common SAS usage, is it preferred to implicitly define variable length within an IF statement, or to explicitly define it using a LENGTH statement before the IF statement?
- Question (aguenane−stat6250): Can you specify a new LENGTH of a variable after the first value for the variable is referenced?
- *Question* (shatcher4-stat6250): Why does the LENGTH step need to appear before any other reference to the variable in the DATA step?
- *Question* (who7-stat6250): What would happen if variable length exceed what we set in the DATA Step?
- *Question* (jcanfield3-stat6250): Why does capitalization not matter when referencing variables?
- Question (ttruong59-stat6250): Should the LENGTH statement appear before or after the reference to the variable in the DATA step?
- Answer (ttruong59-stat6250): The LENGTH statement must appear before any other reference to the variable.
- Question (ljiang11−stat6250): If put LENGTH TYPE $10 as the first reference, would the length be 10?
- *Question* (akrishnamurthy-stat6250): Is the length of a variable fixed or does it change with each reference ?
- *Question* (cnguyen77-stat6250): Where should the LENGTH statement be placed in DATA step?
- *Answer* (cnguyen77-stat6250): Make sure the LENGTH statement appears before any other reference to the variable in the DATA step. If the variable has been created by another statement, then a later use of the LENGTH statement will not change its length.
- *Question* (ldai4-stat6250): Who can determine the length of a new variable?
- *Answer* (ldai4-stat6250):  The length of a new variable is determined by the first reference in the DATA step, not by data value.
- *Question* (xyin6-stat6250): Where should we put the LENGTH statement to specify a length?
- *Answer* (xyin6-stat6250): It should appear before any other reference to the variable in teh DATA step, otherwise of the variable has been created by another statement, the LENGTH statement will not work.
- Question (lsun20-stat6250): Why the length of the variable Type is not 10 with the Length statement?
- Answer (lsun20-stat6250): Because the LENGTH statement is in the wrong place, it should before any other reference to the variable in the DATA step.
- *Question*(kamirneni-stat6250): When does SAS issue an error in the SELECT-WHEN statement?
- *Question* (sbagdi-stat6250): Why should a LENGTH statement appear before any other reference to the varaible in a DATA step?



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
- *Question* (cli19-stat6250): How does syntax differ when dropping, keeping, or renaming variables in DATA steps versus PROC steps?
- Question (tbishaw-stat6250): Is there an alternative to IF-THEN/ELSE statement? If so what is it?
- Answer (tbishaw-stat6250): As an alternative to IF-THEN/ELSE statmenent you can use SELECT groups in DATA steps to perform conditional processing. 
- Question (tchan49-stat6250):Can KEEP or DROP statement be written in PORC statement? 
- *Question* (jbettonville-stat6250): In common SAS usage, is it preferred to use DROP statements within DATA steps to explicitly exclude certain variables, or to use KEEP to select specific variables to include?
- *Answer* (jbettonville-stat6250): It is preferred to use KEEP statements to explicitly include specific variables, as this makes the code somewhat "self-documenting" by showing what is included rather than what is excluded, and it also prevents unwanted columns from being included in case the input data changes. (n.b. Week 5 SAS recipes lines 89-93)
- Question (aguenane−stat6250): Do you have to provide a label and format for a variable?
- *Question* (shatcher4-stat6250): What does the DROP= statement do?
- *Question* (who7-stat6250): How can we achieve the DROP function in PROC step?
- *Question* (jcanfield3-stat6250): Why does an error occur when you use a drop or keep statement in a proc step?
- Question (ttruong59-stat6250): What is a major reason users cannot use DROP or KEEP statements in PROC steps?
- Question (ljiang11−stat6250): Can KEEP or DROP statements be in PROC step?
- Answer (ljiang11−stat6250): No, however DROP= and KEEP= can be put in PROC step as a data set option following a data set name.
- *Question* (akrishnamurthy-stat6250): What is the use of DROP or KEEP statements in DATA and PROC steps?
- *Question* (cnguyen77-stat6250): Can DROP or KEEP statements be used in PROC steps?
- *Question* (ldai4-stat6250): Can we use DROP and KEEP statement in the PROC steps?
- *Question* (xyin6-stat6250): What is the difference between DROP= data set option and DROP statement?
- Question (lsun20-stat6250): If we put the DROP statement after the data= option, it will still an error?
- *Question*(kamirneni-stat6250): Are there any limitations in using SELECT groups? 
- *Question* (sbagdi-stat6250): What causes the statements that refrence variables to use missing values for the variables?
- *Answer* (sbagdi-stat6250)- To reference a variable in the original dataset, we should do that in DROP= and KEEP= option, failing to do this, causes the use of missing values for variables.



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
- *Question* (cli19-stat6250): What is the purpose of specifying DROP or KEEP variables in the SET statement?
- Question (tbishaw-stat6250): What are the steps you need to perform before you create the data set? 
- Answer (tbishaw-stat6250): To create the data set, you must first reference the library in which your data is stored and then you wirte a DATA step to read your data and create a new data set; you must assign a libref to the SAS library that will store the data set.
- Question (tchan49-stat6250):What is the difference between having DROP/KEEP option in SET statement or DATA step? 
- *Question* (jbettonville-stat6250): What is the difference between using DROP as an option on a DATA step and using DROP or KEEP as an option in a SET statement within a DATA step?
- *Answer* (jbettonville-stat6250): Using DROP or KEEP in the SET statement specifies what columns from the source data set are dropped or kept, at which point additional conditions may be applied to remove specific observations (i.e. an IF statement can be used following the SET statement to choose only rows that meet a specific condition). Using DROP as an option in the DATA step can be used to exclude columns that were included in the SET statement that may have been used when selecting which observations to select, but that are not desired in the final output data set.
- Question (aguenane−stat6250): What is the difference between using DROP= and KEEP= statements in the DATA step vs the SET step?
- *Question* (shatcher4-stat6250): Where is the data set that will be read specified after a DATA step is written to name the SAS data set to be created?
- *Question* (who7-stat6250): If we DROP variable in the DATA step, can we recall those varaibles if we use another DATA Step?
- *Question* (jcanfield3-stat6250): Is the if statement processed before or after the drop= option?
- Question (ttruong59-stat6250): Instead of using DROP= and KEEP= data set option in the DATA statements, why don't we use SELECT statements conditionally?
- Question (ljiang11−stat6250): What is used to separate variables after DROP=
- Answer (ljiang11−stat6250): Use space, not comma.
- *Question* (akrishnamurthy-stat6250):How to retain only few variables from a dataset after processing? 
- *Question* (cnguyen77-stat6250): Where to Specify the DROP= and KEEP= Data Set Options?
- *Answer* (cnguyen77-stat6250): You can specify DROP= and KEEP= in either the DATA statement or the SET statement, depending on whether you want to drop variables onto output or input.
- *Question* (ldai4-stat6250): How is a new data set created from an existing SAS data set?
- *Question* (xyin6-stat6250): Which step will be excuted first? SET statement or DATA statement?
- Question (lsun20-stat6250): What the difference about the DROP/KEEP= option in DATA and SET statement?
- *Question*(kamirneni-stat6250): What is the difference in procedure of referencing a variable from original dataset? 
- *Answer*(kamirneni-stat6250): Use DROP/KEEP in SET statement to not reference variables and not let them appear in new dataset. If one needs to reference a variable in the original dataset, use DROP/KEEP statement in DATA statement.
- *Question* (sbagdi-stat6250)- How to create a new dataset from an existing one?



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
- *Question* (cli19-stat6250): What does the program data vector (PDV) look like when statements in a DATA step reference variables that are not present in the data set?
- Question (tbishaw-stat6250): What is the function the SET statment performs? 
- Answer (tbishaw-stat6250): After you write a DATA step to name the SAS data set to be created, you use the SET statement to specify the data set that will be read. 
- Question (tchan49-stat6250):Can you drop a variable in DATA step that isn't kept in SET statement? 
- *Question* (jbettonville-stat6250): Can the KEEP option be used as an option in the DATA step to explicitly choose the variables from the original data set to include in the output data set?
- Question (aguenane−stat6250): What does “july” mean when referencing the data set Orders with this statement: july.orders?
- *Question* (shatcher4-stat6250): What are the different ways to manipulate data using the DATA step?
- *Question* (who7-stat6250): Why would we drop varialbe when we create new dataset?
- *Answer* (who7-stat6250): Sometimes it is present a more clear cut dataset taht shows only varaibles that is needed.
- *Question* (jcanfield3-stat6250): What is wrong with option B?
- *Answer* (jcanfield3-stat6250): Not only is ordrtime never read, thus invalidating the if statement, but also we are creating the orders dataset rather than reading it.
- Question (ttruong59-stat6250): For this problem, the variables Age, Weight, and Group are specified using the KEEP= option in the SET statement. And after processing, Age and Group are dropped in the DATA statement. The question is what happens if we are going to change (KEEP=product units price ordrtime) to (DROP=product units price ordrtime) in the SET statement?
- Question (ljiang11−stat6250): What are the variables left?
- Answer (ljiang11−stat6250): product, units, price.
- *Question* (akrishnamurthy-stat6250):Is it necessary to carry over all the variables that are being evaluated to output dataset? Can the variables being evaluated be dropped from output dataset?
- *Question* (cnguyen77-stat6250): What is the function of DROP= data set option?
- *Answer* (cnguyen77-stat6250): The DROP= data set option prevents variables from being written to the data set.
- *Question* (ldai4-stat6250): If we need to reference a variable in the original data set, do we need to specify the variable in the DROP= option in the DATA statement?
- *Answer* (ldai4-stat6250): Yes, we should specify the variable in the DROP= or KEEP= option in the DATA statement. Otherwise, the statement that references the variable uses a missing value for the variable.
- *Question* (xyin6-stat6250): Does the if-statement after SET statement overwrite the dataset created in DATA statement? (subseting a new dataset)
- Question (lsun20-stat6250): Why we don't need the THEN statement after IF statement?
- *Question*(kamirneni-stat6250): What is a minor difference between STOP and DATA step in looping with POINT function?
- *Question* (sbagdi-stat6250)- How is KEEP dataset option different rom KEEp statement in a DATA step?



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
- *Question* (cli19-stat6250): What are other potential use cases for FIRST. and LAST. statements?
- *Answer* (cli19-stat6250): One use case is FIRST. and LAST. can be used to compare observations to see if there are any duplicate rows.
- Question (tbishaw-stat6250): Which statement do you use if you never refernce certain varaibles and you do not want them to appear in the new data set? 
- Question (tchan49-stat6250):Are First. and LAST. temporary variables? 
- *Question* (jbettonville-stat6250): Can multiple observations in a data set take on a value of 1 in the FIRST. and/or LAST. variables when working with more than one BY variable?
- Question (aguenane−stat6250): What are the values in FIRST.variable and LAST.variable?
- Answer (aguenane-stat6250): Their values are either 1 for the first and last observations respectively or 0 for any other observation.
- *Question* (shatcher4-stat6250): What happens when you use the BY statement with the SET statement?
- *Question* (who7-stat6250): What are some other interesting ways to use the FRIST and LAST variables?
- *Question* (jcanfield3-stat6250): Is there a way to output the first. and last. variables?
- Question (ttruong59-stat6250): When using BY- group processing, the DATA steps create 2 temp variables for each BY variable: FIRST. variable and LAST.variable, and their values are either 1 or 0. Are these variables stored in the data set?
- Question (ljiang11−stat6250): Is FIRST. and LAST. sorted?
- *Question* (akrishnamurthy-stat6250): Should the dataset be sorted in any particular order before being processed by BY statements?
- *Question* (cnguyen77-stat6250): When using the BY statement with the SET statement, are the temporary variables FIRST. and LAST. stored in the data set?
- *Question* (ldai4-stat6250): Using the BY statement with the SET statement, does the DATA step automatically create two variables, FIRST. And LAST., for each variable in the BY statement?
- *Question* (xyin6-stat6250): How to append a variable into FIRST and LAST as shown in the book example? Is it automatically created by SAS?
- Question (lsun20-stat6250): Where the FIRST and LAST are stored when you use BY-group processing?
- Answer (lsun20-stat6250): The DATA step creates the temporary variables FIRST and LAST.
- *Question*(kamirneni-stat6250): What is the difference in DATA step processing for existing dataset and raw data?
- *Question* (sbagdi-stat6250)- WHat does POINT= option does?
- *Answer* (sbagdi-stat6250)- To access observations directly by their observation number, POINT= option is used in SET statement.



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
- *Question* (cli19-stat6250): How can LAST. be combined with other statements to get the last observation with respect to a specific variable?
- Question (tbishaw-stat6250): What are the two temporary varaibles the DATA step creates for each BY variable? 
- Answer (tbishaw-stat6250): One is named FIRST.variable, is the name of the BY variable, and the second is named LAST.variable. These two variables identify the first and last observation in each BY group. 
- Question (tchan49-stat6250):When you only want to select only the last observation of the dataset, do you put end=last at the end of SET statement ot DATA step? 
- Answer (tchan49-stat6250): At the end of SET statement and also finish it with "if last;" at the end of data step before run statement. 
- *Question* (jbettonville-stat6250): Can (and should) the END= option be used to return the index of the final observation in a data set?
- Question (aguenane−stat6250): Is “LAST” a SAS defined statement or is it a variable?
- *Question* (shatcher4-stat6250): How do you create a temporary numeric variable whose value is used to detect the last observation?
- *Answer* (shatcher4-stat6250): Use the END= option in the SET statement.
- *Question* (who7-stat6250): How can we achieve the function of end=last function for the first entry?
- *Question* (jcanfield3-stat6250): Can you use an end=last option to make the last observation from each "by or class" variable have last=1? 
- Question (ttruong59-stat6250): For this problem, what does “if last;" condition mean? And what does exactly “if last;" do in this program?
- Question (ljiang11−stat6250): What does END= do?
- *Question* (akrishnamurthy-stat6250): What is the difference between END and POINT options?
- *Question* (cnguyen77-stat6250): What is the function of END=option on SET statement?
- *Question* (ldai4-stat6250): If we want to output only one observation, can we use the END= option in the SET statement?
- *Question* (xyin6-stat6250): Is END= option always follow the SET statement?
- Question (lsun20-stat6250): What the means of "IF last"? How does it works?
- *Question*(kamirneni-stat6250): What does SAS do differently for raw data compared to existing dataset in DATA step?
- *Question* (sbagdi-stat6250)- How is data set process different in raw dataset and exisitng dataset?



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
- *Question* (cli19-stat6250): Why are there no observations at the start of DATA step processing?
- Question (tbishaw-stat6250): How can you prevent continuous looping when using direct access to read data?  
- Answer (tbishaw-stat6250): You add a STOP statement to the DATA step to prevent continuous looping. 
- Question (tchan49-stat6250):When the descriptor portion of the new SAS dataset id created, has the DATA step executed yet?
- *Question* (jbettonville-stat6250): During the compilation phase, how does SAS determine the order of the variables added to the PDV based upon options in the DATA step, the SET statement, and any additional variables that are created within the statement?
- Question (aguenane−stat6250): If variables are created in the DATA step, what happens to them during the compilation phase?
- *Question* (shatcher4-stat6250): What happens during the compilation phase of DATA steps that use a SET statement?
- *Question* (who7-stat6250): With the way SAS runs the compilation phase, does it means all data manipulation process should be done in the DATA step?
- *Question* (jcanfield3-stat6250): Is there a way to print how the PDV works in an output?
- Question (ttruong59-stat6250): At the start of DATA step processing, are there any observations set during a compilation phase?
- Answer (ttruong59-stat6250): There are no observations set during a compilation phase since DATA step was not executed.
- Question (ljiang11−stat6250): What is PDV?
- Answer (ljiang11−stat6250): Program Data Vector.
- *Question* (akrishnamurthy-stat6250): Will the observations be read into the program data vector after compilation ?
- *Answer* (akrishnamurthy-stat6250): At the end of compilation phase only the descriptor portion of new SAS dataset is created and observations are not read.
- *Question* (cnguyen77-stat6250): Is there any observations at the start of DATA step processing?
- *Question* (ldai4-stat6250): At the start of DATA step processing, why are there no observations?
- *Answer* (ldai4-stat6250):  At the bottom of the DATA step, the compilation phase is completed. There are no observations because the DATA step has not yet executed.
- *Question* (xyin6-stat6250): How does SAS set the value of each variable when SAS reads the raw data?
- *Answer* (xyin6-stat6250): SAS sets the value of each variable in the DATA step to missing at the beginning or each iteration.
- Question (lsun20-stat6250): When the observation will be created?
- *Question*(kamirneni-stat6250):How does the DATA step execute the dataset?
- *Question* (sbagdi-stat6250)- What happens when we use multiple BY statements?



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
- *Question* (cli19-stat6250): Should length be defined outside the do loop rather than inside?
- Question (tbishaw-stat6250): How is the LEGNGTH statement used in SAS? 
- Answer (tbishaw-stat6250): The LENGTH statemnt is used in the dATA step to specify a variable's length. If the varaible is character, the length applies to the PDV and the output data set. If the variable is numeric, the length applies only to the output data set.   
- Question (tchan49-stat6250): What is the benefit having in= dataset option? 
- *Question* (jbettonville-stat6250): Is it possible to resolve warnings about multiple lengths being specified for the same variable when multiple data sets are joined vertically?
- *Answer* (jbettonville-stat6250): The warnings about multiple lengths occur because the length of the initial observation for the affected variables in one data set are not the same length as they are in the second. In the example, the Academic_Year variable has length 19 in the first input data set and 60 in the second. It is possible to resolve this issue by specifying the length of this variable within the DATA step prior to the SET statement in which the input data sets are referenced, and choosing a value that is at least as long as the longest instance of this variable; by using the statement "length Academic_Year $ 60;", the warning for the Academic_Year variable will not be shown because the length has been declared to be equal to the longest version of this variable among the input data sets. However, while this resolves the warning for one variable, it may not be a scalable solution as it would require the length of all variables to be specified prior to the SET statement.
- Question (aguenane−stat6250): What is the function of the SAS statement DO? 
- *Question* (shatcher4-stat6250): What is "business logic" and how is it performed?
- *Question* (who7-stat6250): How do the do end condition differs from the if then condition?
- *Question* (jcanfield3-stat6250): Can I format the id variable before its assigned a value?
- Question (ttruong59-stat6250): When combining 2 datasets vertically, what happens if one dataset mentioned in the DATA= option has more variables than the other?
- Question (ljiang11−stat6250): What does IN= do? Is it indexing?
- *Question* (akrishnamurthy-stat6250): Should two datasets be of same length and structure to be combined vertically ? How are differences handled if the file structure is different between the datasets?
- *Question* (cnguyen77-stat6250): How to create indicator variables?
- *Question* (ldai4-stat6250): If using the APPEND statement to combine two data sets to form a single dataset, do the two original datasets need to have same variables?
- *Question* (xyin6-stat6250): Why we have to include "do" statement in the body before referring to each data source?
- Question (lsun20-stat6250): Can we remove the first END statement after the ELSE statement?
- *Question*(kamirneni-stat6250): How are defensive programming practices defined?
- *Question* (sbagdi-stat6250)- What's defensive programming practice?



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
- *Question* (cli19-stat6250): What happens if variables are of different type when combining data vertically using a UNION ALL CORR statement in a PROC SQL step?
- Question (tbishaw-stat6250): How are a group of statments executed as a unit in DATA steps? 
- Question (tchan49-stat6250): Can "UNION all corr" make sure that all columns with corresponding name are matched up even in different positions? 
- *Question* (jbettonville-stat6250): If not all columns between the two data sets were named identically, would UNION ALL CORR in lead to missing values in the resulting data set?
- Question (aguenane-stat6250): What does the AS keyword do in a PROC SQL SELECT statement?
- *Question* (shatcher4-stat6250): How is an asterisk used as shorthand?
- *Answer* (shatcher4-stat6250): It is used to include all columns from the source dataset name that is listed in the corresponding from clause
- *Question* (who7-stat6250): It seems for one proc sql seems to involve more code to do merge than normal SAS code, would it be considered a better way to merge dataset?
- *Question* (jcanfield3-stat6250): Why is proc sql not taught at a beginner level if its so much more efficient?
- Question (ttruong59-stat6250): Data exists in 2 datasets to be combined vertically, what happens if the variables have the same name but different types?
- Question (ljiang11−stat6250): What does UNION in PROC SQL do?
- *Question* (akrishnamurthy-stat6250): How to perform right outer join of two datasets using PROC SQL statement?
- *Question* (cnguyen77-stat6250): Other than the creation of indicator variables, what is the alternative method being used to combine data vertically?
- *Question* (ldai4-stat6250): When using INTERLV statement, does the new data set include all the variables and observations?
- *Question* (xyin6-stat6250): Is "Union all corr" a necessary statement for every PROC SQL step? 
- Question (lsun20-stat6250): What is the usage of the " * " in the SELECT statement?
- *Question*(kamirneni-stat6250): What are the trade-offs for combining datasets using SQL in SAS? 
- *Answer*(kamirneni-stat6250): It loads all data into memory before performing set theory operations, RAM has limitations and takes longer time to create datasets comparatively.  
- *Question* (sbagdi-stat6250)- What is the difference between oprators UNION, INTERSECT and EXCEPT?
- *Answer* (sbagdi-stat6250)- The three operatos are different from each other in terms of the set-theoretic rules they implement, yet their mechanics is similar.


