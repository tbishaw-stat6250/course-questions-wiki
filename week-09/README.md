## Week 9 Quiz Questions and Answers

In order to prepare your Week 9 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-9" in your fork of this repo. Then, after all edits have been made/committed, your Week 9 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-9 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 14, Problem 1]
- Question(dfei-stat6250): Can DO loops be used to combine DATA and PROC steps?
- Answer(dfei-stat6250): No, it can not.
- *Question* (aacharya4−stat6250):  What is the default value by which index variable is incremented in iterative DO statement in SAS?
- *Answer* (aacharya4−stat6250): The default value by which index variable is incremented in iterative DO statement in SAS is 1.
- *Question* (asharda-stat6250): Why do you need a DO loop?
- *Answer* (asharda-stat6250): You can execute SAS statements repeatedly by placing them in a DO loop. 
- *Question* (shatcher4-stat6250): What can DO loops be used for?
- *Answer* (shatcher4-stat6250): DO loops can execute any number of times in a single iteration of the DATA step, it can also generate data, conditionally execute statements, and read data.
- *Question* (ldai4-stat6250): What is DO loops?
- *Answer* (ldai4-stat6250): The DO loops are DATA step statement and cannot be used in conjunction with PROC steps.
- Question (tbishaw-stat6250): How can we execute a SAS statement repeatedly?     
- Answer (tbishaw-stat6250): We can execute a SAS statement repeatedly by placing them in a DO loop. Do loops can execute any number of times in a single iteration of the DATA step.  



[Course Textbook Chapter 14, Problem 2]
- Question(dfei-stat6250): How to determind the times DO loop execute?
- Answer(dfei-stat6250): "do month=1 to some value" is the factor to determind the times DO loop execute.
- *Question* (aacharya4−stat6250):  How can we change the value of incrementing or decrementing the index variable by 1 in iterative DO statement?
- *Answer* (aacharya4−stat6250): To change the incrementing or decrementing the index variable by 1 in iterative DO statement, we use the BY clause. For eg: do i = 1 to 5 by 0.5;
- *Question* (asharda-stat6250): How are number of iterations determined in a DO step?.
- *Answer* (asharda-stat6250): The number of iterations is determined by the DO statement's stop value.
- *Question* (shatcher4-stat6250): What is the purpose of the index variable in a DO loop?
- *Question* (ldai4-stat6250): Is the number of iterations determined by the DO statement's stop value?
- Question (tbishaw-stat6250): Which variables must be specified when creating a DO loop?



[Course Textbook Chapter 14, Problem 3]
- Question(dfei-stat6250): Does "do count = 1 to some value * percentage" correct?
- Answer(dfei-stat6250): No, it does not.
- *Question* (aacharya4−stat6250):  How can we terminate an iterative DO statement in SAS?
- *Answer* (aacharya4−stat6250): We can terminate an iterative DO statement in SAS by using the END statement.
- *Question* (asharda-stat6250): Using a DO loop how will you perform repetitive calculations starting at 1 and looping 25 times. 
- *Answer* (asharda-stat6250): do count=1 to 25;
- *Question* (shatcher4-stat6250): What are the different conditions that execute the DO loop?
- *Question* (ldai4-stat6250): Can the DO loop statement be used to calculate a balance with a constant interest?
- Question (tbishaw-stat6250): What happens when you place an explicit OUTPUT statement in a DATA step?
- Answer (tbishaw-stat6250): It overrides automatic output, causing SAS to add an observation to the data set only when the explicit OUTPUT statement is executed.



[Course Textbook Chapter 14, Problem 4]
- Question(dfei-stat6250): How many stored values happen if one DO loop execute?
- *Question* (aacharya4−stat6250):  How can we stop iterating a DO statement in SAS based on a condition?
- *Answer* (aacharya4−stat6250): To stop iterating a DO statement in SAS based on a condition; we need to use the WHILE or UNTIL clause.
- *Question* (asharda-stat6250): What is the use of TO clause in DO statement
- *Answer* (asharda-stat6250): The TO clause specifies the stop value. The stop value is the last index value that executes the DO loop. 
- *Question* (shatcher4-stat6250): When a DO loop is executed, what does the DATA step do?
- *Question* (ldai4-stat6250): Why do we need to specify an index variable when creating a DO loop with the iterative DO statement?
- *Answer* (ldai4-stat6250): The index variable stores the value of the current iteration of the DO loop.
- Question (tbishaw-stat6250): What is the difference between the DO UNTIL and DO WHILE statements? 



[Course Textbook Chapter 14, Problem 5]
- Question(dfei-stat6250): Do I need OUTPUT statement in DO loop execute?
- *Question* (aacharya4−stat6250):  What is the difference between using DO loop with UNTIL clause and DO loop with WHILE clause?
- *Answer* (aacharya4−stat6250): In case of DO loop with UNTIL clause, it executes at least one time because the condition is evaluated at the end of loop. In case of DO loop with WHILE clause, first the condition is evaluated before executing the statements within the loop.
- *Question* (asharda-stat6250): What is the use of OUTPUT statement ?
- *Answer* (asharda-stat6250): The OUTPUT statement overrides the automatic output at the end of the DATA step. 
- *Question* (shatcher4-stat6250): Why does an OUTPUT statement need to be placed inside a DO loop?
- *Question* (ldai4-stat6250): Does the OUTPUT statement override the automatic output at the end of the dATA step?
- Question (tbishaw-stat6250): Is the WHILE expression evaluated before or after the execution of the DO loop?
- Answer (tbishaw-stat6250): The WHILE expression is evaluated before the execution of the DO loop. 



[Course Textbook Chapter 14, Problem 6]
- Question(dfei-stat6250): How to count observations in the data set contain?
- *Question* (aacharya4−stat6250):  When does the execution of an iterative DO statement stop?
- *Answer* (aacharya4−stat6250): The execution of an iterative DO statement stops when the index variable's value exceeds the value of the stop variable, hence the execution of the DO loop stops.
- *Question* (asharda-stat6250): What is the numbe rof observations based on ?
- *Answer* (asharda-stat6250): The number of observations is based on the number of times the OUTPUT statement executes.
- *Question* (shatcher4-stat6250): How do you specify how many times a DO loop executes with a variable list?
- *Question* (ldai4-stat6250): What determines the number of observations in DO loop statement?
- *Answer* (ldai4-stat6250): The number of observation is based on the number of times the OUTPUT statement executes.
- Question (tbishaw-stat6250): If the condition for the WHILE expression is initally false, does the DO loop execute?



[Course Textbook Chapter 14, Problem 7]
- Question(dfei-stat6250): What does nested DO loops mean?
- *Question* (aacharya4−stat6250):  What is the case in case we use decrementing DO loops?
- *Answer* (aacharya4−stat6250): In case of decrementing DO loops, the BY clause has a negative value. Thus, the start value of the index variable should be greater than the stop value of the index variable.
- *Question* (asharda-stat6250): Which statements do you use to loop  when number of iterations is fixed?.
- *Answer* (asharda-stat6250):  DO WHILE and DO UNTIL statement.
- *Question* (shatcher4-stat6250): What is the purpose of the DO WHILE and DO UNTIL statements?
- *Question* (ldai4-stat6250): What is the difference between DO WHILE statement and DO UNTIL statement?
- Question (tbishaw-stat6250): What does decrementing a DO loop accomplish? 



[Course Textbook Chapter 14, Problem 8]
- Question(dfei-stat6250): How to evaluate DO UNTIL statements?
- *Question* (aacharya4−stat6250):  How can we generate observations with the DO loops for each iteration of the loop?
- *Answer* (aacharya4−stat6250): To generate observations for each iteration of the DO loop, we can use the OUTPUT statement.
- *Question* (asharda-stat6250): When is DO UNTIL condition evaluated?.
- *Answer* (asharda-stat6250):  The DO UNTIL condition is evaluated at the bottom of the loop, so the enclosed statements are always excecuted at least once.
- *Question* (shatcher4-stat6250): During what part of the loop is the DO UNTIL statemnet evaluated, and what happens if the expression is evaluated as false?
- *Question* (ldai4-stat6250): In executing DO until statement, are the enclosed statement always executed at least once?
- Question (tbishaw-stat6250): What conditions must be met for a DO loop to run within a DO loop?
- Answer (tbishaw-stat6250): DO loops can run within DO loops, as long as you assign a unique index variable to each loop and terminate each DO loop with its own END statement.



[Course Textbook Chapter 14, Problem 9]
- Question(dfei-stat6250): What is the difference between do until and DO WHILE statement?
- *Question* (aacharya4−stat6250):  What are the possible types of start, stop and increment/decrement values for index variable in iterative DO statements?
- *Answer* (aacharya4−stat6250): The start, stop and increment/decrement values for index variable can be any number, numeric variable or SAS expression which evaluates to give a numeric value.
- *Question* (asharda-stat6250): When is DO WHILE loop evaluated?.
- *Answer* (asharda-stat6250): DO WHILE loop is evaluated at the top of the loop.
- *Question* (shatcher4-stat6250): During what part of the loop is the DO WHILE statemnet evaluated, and what happens if the expression is evaluated as true?
- *Question* (ldai4-stat6250): Why do we need to specify the condition in DO WHILE statement?
- Question (tbishaw-stat6250): What does the SET statement in a DO loop execute? 



[Course Textbook Chapter 14, Problem 10]
- Question(dfei-stat6250): What time does program stop generating observations?
- *Question* (aacharya4−stat6250):  How can we do nested DO loops in SAS?
- *Answer* (aacharya4−stat6250): Nested DO loops can be used in SAS where each DO loop has an unique index variable for each DO loop and each of the DO loops has its own terminating END statement.
- *Question* (asharda-stat6250): What is difference between DO UNTIL and DO WHILE statements?
- *Question* (shatcher4-stat6250): What occurs when you enclose a SET statement in a DO loop and what occurs when you add a POINT= option to that SET statement?
- *Question* (ldai4-stat6250): If we want to the DO LOOP to stop executing some condition, should we use the WHILE statement?
- Question (tbishaw-stat6250): How many values is the index variable always incremented by?



[Course Textbook Chapter 15, Problem 1]
- Question(dfei-stat6250): Can an ARRAY statement be used to create variables?
- *Question* (aacharya4−stat6250):  Is it possible to store both numeric and character variables in a single array in SAS?
- *Answer* (aacharya4−stat6250): No, a single array in SAS can store either numeric or character variables and not both.
- *Question* (asharda-stat6250): What does an ARRAY statement do?.
- *Answer* (asharda-stat6250):  It merely defines an array.
- *Question* (shatcher4-stat6250): What is a SAS array?
- *Question* (ldai4-stat6250): What is ARRAY statement?
- *Answer* (ldai4-stat6250): The ARRAY statement can be used to create variables, must contain either all numeric or all character elements, and must be used to define an array before the array name can be referenced.
- Question (tbishaw-stat6250): How can you process variables as a group?
- Answer (tbishaw-stat6250): You can process varaibles as a group by using array processing.



[Course Textbook Chapter 15, Problem 2]
- Question(dfei-stat6250): What does the braces of this ARRAY statement mean?
- *Question* (aacharya4−stat6250):  In the following syntax: (ARRAY array-name{dimension} {elements};), what does dimension mean?
- *Answer* (aacharya4−stat6250): The dimension in the given syntax indicates the length of the array or the number of elements in the array.
- *Question* (asharda-stat6250): What does the value in parentheses indicate?.
- *Answer* (asharda-stat6250):  The value in parentheses indicates the number of elements in the array.
- *Question* (shatcher4-stat6250): What is the purpose of the specification of the dimension of the array?
- *Question* (ldai4-stat6250): Does the value in parentheses indicate the number of elements in the array?
- Question (tbishaw-stat6250): What is an array? What are its functions?



[Course Textbook Chapter 15, Problem 3]
- Question(dfei-stat6250): How to select an iterative DO statement to process all elements?
- *Question* (aacharya4−stat6250):  What happens if we do not specify array elements in an ARRAY statement?
- *Answer* (aacharya4−stat6250):  If we do not specify array elements in an ARRAY statement, SAS automatically creates variable names by concatenating numbers 1,2,3,..upto the array dimension with the array name.
- *Question* (asharda-stat6250): Which variable represents the values of the array elements in the DO statement.
- *Answer* (asharda-stat6250):  Index variable represents the values of the array elements in the DO statement.
- *Question* (shatcher4-stat6250): When are arrays used with a DO loop?
- *Answer* (shatcher4-stat6250): Arrays are generally used with DO loops to process multiple variables and to perform repetitive calculations.
- *Question* (ldai4-stat6250): How can we specify the index variable that represents the values of the array elements in the DO statement?
- *Answer* (ldai4-stat6250): We need to specify the start and stop position of the array elements. 
- Question (tbishaw-stat6250): What are the functions of a a DIM function? 
- Answer (tbishaw-stat6250): You can use the DIM function to specify the TO clause of the iterative DO statement.



[Course Textbook Chapter 15, Problem 4]
- Question(dfei-stat6250): How to know the value of the index variable?
- *Question* (aacharya4−stat6250):  When we use DO iterative statement with array in SAS, what does the index variable of the DO iterative statement indicate in regard to the array that it references?
- *Answer* (aacharya4−stat6250): The index variable of the DO iterative statement indicates the position of the array element of the array that it references.
- *Question* (asharda-stat6250): What does an index value represents .
- *Answer* (asharda-stat6250):  The index value represents the position of the array element.
- *Question* (shatcher4-stat6250): How do you specify the elements of an array?
- *Question* (ldai4-stat6250): What does the index value represent?
- Question (tbishaw-stat6250): What length are all character variables that are created with an ARRAY statement assigned by default?  



[Course Textbook Chapter 15, Problem 5]
- Question(dfei-stat6250): What does the "*" mean in "do i=1 to dim(*)" statement?
- *Question* (aacharya4−stat6250): What is the purpose of using the DIM function in SAS? 
- *Answer* (aacharya4−stat6250): We use the DIM function to process all the elements in an array in SAS.
- *Question* (asharda-stat6250): How do you process all the elements in an array?
- *Answer* (asharda-stat6250):  To process all the elements in an array, you can either specify the array dimension or use the DIM function with the array name as the argument.
- *Question* (shatcher4-stat6250): What is the purpose of the i in the DO loop of an array?
- *Question* (ldai4-stat6250): How can we use the DIM function?
- Question (tbishaw-stat6250): How can we assign initial values to character varaibles?  



[Course Textbook Chapter 15, Problem 6]
- Question(dfei-stat6250): By default, are all character variables assigned a length of eight?
- *Question* (aacharya4−stat6250): How can we assign initial values in an ARRAY statement?
- *Answer* (aacharya4−stat6250): We can assign initial values in an ARRAY statement by placing the values within parenthesis, where each value is separated by a comma or blank. In case, of values for character variable in array, the values should be enclosed in quotation marks. 
- *Question* (asharda-stat6250): How do you process all the elements in an array?
- *Answer* (asharda-stat6250):  To process all the elements in an array, you can either specify the array dimension or use the DIM function with the array name as the argument.
- *Question* (shatcher4-stat6250):  If exisiting variables within an array are not referenced, why does SAS automatically create new variables and assigns them default names?
- *Question* (ldai4-stat6250): Do we need to specify the array elements in the ARRAY statement?
- Question (tbishaw-stat6250): How can we define a multidimensional arrays? 



[Course Textbook Chapter 15, Problem 7]
- Question(dfei-stat6250): Why does array "wt{*} weight1-weight10" mean?
- *Question* (aacharya4−stat6250): How can we define multidimensional arrays in SAS?
- *Answer* (aacharya4−stat6250): In SAS, we can define a multidimensional array by specifying the number of elements in each dimension separated by comma. For example: array twoDim{2,4} a1-a8; means it is a 2D array with 2 rows and 4 columns.
- *Question* (asharda-stat6250): Which  variables can be created by an ARRAY statement.
- *Answer* (asharda-stat6250):  Either numeric or character variables can be created by an ARRAY statement. 
- *Question* (shatcher4-stat6250): How do you create an array of character variables?
- *Question* (ldai4-stat6250): Can we give an array the same name as a variqable in the same DATA step?
- Question (tbishaw-stat6250): What does rotating a data set accomplish?
- Answer (tbishaw-stat6250): Rotating a data set changes variables to observations or observations to variables. 



[Course Textbook Chapter 15, Problem 8]
- Question(dfei-stat6250): What is the format to create temporary array elements?
- *Question* (aacharya4−stat6250): How can we reference a multidimensional array in SAS?
- *Answer* (aacharya4−stat6250): We can reference a multidimensional array in SAS by suing nested DO loops.
- *Question* (asharda-stat6250): How do you reference the elements of an array.
- *Question* (shatcher4-stat6250): What is the purpose of temporary array elements?
- *Answer* (shatcher4-stat6250): Temporary array elements are useful when the array is needed for calculations, since these temporary arrays can improve performance time.
- *Question* (ldai4-stat6250): How temporary array element can be created?
- *Answer* (ldai4-stat6250): To create temporary array element, specify _TEMPORARY_ after the array name and dimension, specify an inital value for each element, separated by either blanks or commas, and enclose the values in parentheses.
- Question (tbishaw-stat6250): Can we give an array the same name as a variable in the same DATA step? 



[Course Textbook Chapter 15, Problem 9]
- Question(dfei-stat6250): What does array reference mean?
- *Question* (aacharya4−stat6250):  Can we use arrays to rotate datasets (changing variable to observation and vice versa) in SAS?
- *Answer* (aacharya4−stat6250): We can use arrays to rotate datasets (changing variable to observation and vice versa) in SAS.
- *Question* (asharda-stat6250): How do you create  create temporary array elements?
- *Question* (shatcher4-stat6250): How do assign inital values in an ARRAY statement?What is the purpose of temporary array elements 
- *Question* (ldai4-stat6250): How do we specify the array reference in the nested DO loops?
- Question (tbishaw-stat6250): How can we indicate the dimension of a one-dimensional array?
- Answer (tbishaw-stat6250): You can indicate the dimension of a one-dimensional array with an asterik as long as you specify the elements of the array.



[recipe_to_create_unique_record_id Week 9 Recipe]
- Question(dfei-stat6250): "_N_ is converted to a character value, meaning it's left-padded with zeros." Why not with ones?
- *Question* (aacharya4−stat6250): Why is the "z6." format used for conversion of automatic variable to character variable in the SAS recipe?
- *Answer* (aacharya4−stat6250): The "z6." format is used to make the converted character value to be exactly of 6 digits, which is one magnitude larger than the number of records of the dataset being used.
- *Question* (asharda-stat6250): What happens during compilation phase of data step?.
- *Question* (shatcher4-stat6250): What is the purpose of the double-pipe operator?
- *Question* (ldai4-stat6250): How can I assign serial numbers to observations in a data set?
- Question (tbishaw-stat6250): How can we adda new ID column in SAS? 



[recipe_to_disaggregate_counts_data Week 9 Recipe]
- Question(dfei-stat6250): How many ways to add an unique ID to each row in dataset?
- *Question* (aacharya4−stat6250):  What is the purpose of using RETAIN statement in SAS?
- *Answer* (aacharya4−stat6250): In a DATA step, SAS sets the initial values of variables created by INPUT or assignment system as missing by default. The RETAIN statement overrides this default, so the value of the variable is retained when used with RETAIN statement.
- *Question* (asharda-stat6250): What is the use of where not statement?.
- *Question* (shatcher4-stat6250): Why would you use a retain attribute in a DO loop?
- *Question* (ldai4-stat6250): In using PROC mean statement, how can we calculate disaggregate statistics?
- Question (tbishaw-stat6250): Which SAS function do we use to execute disaggreagation? And what does Disaggreagation accomplish?  


