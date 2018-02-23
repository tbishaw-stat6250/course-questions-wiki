## Week 9 Quiz Questions and Answers

In order to prepare your Week 9 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-9" in your fork of this repo. Then, after all edits have been made/committed, your Week 9 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-9 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 14, Problem 1]
- *Question* (aacharya4−stat6250):  What is the default value by which index variable is incremented in iterative DO statement in SAS?
- *Answer* (aacharya4−stat6250): The default value by which index variable is incremented in iterative DO statement in SAS is 1.



[Course Textbook Chapter 14, Problem 2]
- *Question* (aacharya4−stat6250):  How can we change the value of incrementing or decrementing the index variable by 1 in iterative DO statement?
- *Answer* (aacharya4−stat6250): To change the incrementing or decrementing the index variable by 1 in iterative DO statement, we use the BY clause. For eg: do i = 1 to 5 by 0.5;



[Course Textbook Chapter 14, Problem 3]
- *Question* (aacharya4−stat6250):  How can we terminate an iterative DO statement in SAS?
- *Answer* (aacharya4−stat6250): We can terminate an iterative DO statement in SAS by using the END statement.



[Course Textbook Chapter 14, Problem 4]
- *Question* (aacharya4−stat6250):  How can we stop iterating a DO statement in SAS based on a condition?
- *Answer* (aacharya4−stat6250): To stop iterating a DO statement in SAS based on a condition; we need to use the WHILE or UNTIL clause.



[Course Textbook Chapter 14, Problem 5]
- *Question* (aacharya4−stat6250):  What is the difference between using DO loop with UNTIL clause and DO loop with WHILE clause?
- *Answer* (aacharya4−stat6250): In case of DO loop with UNTIL clause, it executes at least one time because the condition is evaluated at the end of loop. In case of DO loop with WHILE clause, first the condition is evaluated before executing the statements within the loop.



[Course Textbook Chapter 14, Problem 6]
- *Question* (aacharya4−stat6250):  When does the execution of an iterative DO statement stop?
- *Answer* (aacharya4−stat6250): The execution of an iterative DO statement stops when the index variable's value exceeds the value of the stop variable, hence the execution of the DO loop stops.



[Course Textbook Chapter 14, Problem 7]
- *Question* (aacharya4−stat6250):  What is the case in case we use decrementing DO loops?
- *Answer* (aacharya4−stat6250): In case of decrementing DO loops, the BY clause has a negative value. Thus, the start value of the index variable should be greater than the stop value of the index variable.



[Course Textbook Chapter 14, Problem 8]
- *Question* (aacharya4−stat6250):  How can we generate observations with the DO loops for each iteration of the loop?
- *Answer* (aacharya4−stat6250): To generate observations for each iteration of the DO loop, we can use the OUTPUT statement.



[Course Textbook Chapter 14, Problem 9]
- *Question* (aacharya4−stat6250):  What are the possible types of start, stop and increment/decrement values for index variable in iterative DO statements?
- *Answer* (aacharya4−stat6250): The start, stop and increment/decrement values for index variable can be any number, numeric variable or SAS expression which evaluates to give a numeric value.



[Course Textbook Chapter 14, Problem 10]
- *Question* (aacharya4−stat6250):  How can we do nested DO loops in SAS?
- *Answer* (aacharya4−stat6250): Nested DO loops can be used in SAS where each DO loop has an unique index variable for each DO loop and each of the DO loops has its own terminating END statement.



[Course Textbook Chapter 15, Problem 1]
- *Question* (aacharya4−stat6250):  Is it possible to store both numeric and character variables in a single array in SAS?
- *Answer* (aacharya4−stat6250): No, a single array in SAS can store either numeric or character variables and not both.



[Course Textbook Chapter 15, Problem 2]
- *Question* (aacharya4−stat6250):  In the following syntax: (ARRAY array-name{dimension} {elements};), what does dimension mean?
- *Answer* (aacharya4−stat6250): The dimension in the given syntax indicates the length of the array or the number of elements in the array.



[Course Textbook Chapter 15, Problem 3]
- *Question* (aacharya4−stat6250):  What happens if we do not specify array elements in an ARRAY statement?
- *Answer* (aacharya4−stat6250):  If we do not specify array elements in an ARRAY statement, SAS automatically creates variable names by concatenating numbers 1,2,3,..upto the array dimension with the array name.



[Course Textbook Chapter 15, Problem 4]
- *Question* (aacharya4−stat6250):  When we use DO iterative statement with array in SAS, what does the index variable of the DO iterative statement indicate in regard to the array that it references?
- *Answer* (aacharya4−stat6250): The index variable of the DO iterative statement indicates the position of the array element of the array that it references.



[Course Textbook Chapter 15, Problem 5]
- *Question* (aacharya4−stat6250): What is the purpose of using the DIM function in SAS? 
- *Answer* (aacharya4−stat6250): We use the DIM function to process all the elements in an array in SAS.



[Course Textbook Chapter 15, Problem 6]
- *Question* (aacharya4−stat6250): How can we assign initial values in an ARRAY statement?
- *Answer* (aacharya4−stat6250): We can assign initial values in an ARRAY statement by placing the values within parenthesis, where each value is separated by a comma or blank. In case, of values for character variable in array, the values should be enclosed in quotation marks. 



[Course Textbook Chapter 15, Problem 7]
- *Question* (aacharya4−stat6250): How can we define multidimensional arrays in SAS?
- *Answer* (aacharya4−stat6250): In SAS, we can define a multidimensional array by specifying the number of elements in each dimension separated by comma. For example: array twoDim{2,4} a1-a8; means it is a 2D array with 2 rows and 4 columns.



[Course Textbook Chapter 15, Problem 8]
- *Question* (aacharya4−stat6250): How can we reference a multidimensional array in SAS?
- *Answer* (aacharya4−stat6250): We can reference a multidimensional array in SAS by suing nested DO loops.



[Course Textbook Chapter 15, Problem 9]
- *Question* (aacharya4−stat6250):  Can we use arrays to rotate datasets (changing variable to observation and vice versa) in SAS?
- *Answer* (aacharya4−stat6250): We can use arrays to rotate datasets (changing variable to observation and vice versa) in SAS.



[recipe_to_create_unique_record_id Week 9 Recipe]
- *Question* (aacharya4−stat6250): Why is the "z6." format used for conversion of automatic variable to character variable in the SAS recipe?
- *Answer* (aacharya4−stat6250): The "z6." format is used to make the converted character value to be exactly of 6 digits, which is one magnitude larger than the number of records of the dataset being used.



[recipe_to_disaggregate_counts_data Week 9 Recipe]
- *Question* (aacharya4−stat6250):  What is the purpose of using RETAIN statement in SAS?
- *Answer* (aacharya4−stat6250): In a DATA step, SAS sets the initial values of variables created by INPUT or assignment system as missing by default. The RETAIN statement overrides this default, so the value of the variable is retained when used with RETAIN statement.


