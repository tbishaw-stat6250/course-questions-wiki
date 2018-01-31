## Week 5 Quiz Questions and Answers

In order to prepare your Week 5 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-5" in your fork of this repo. Then, after all edits have been made/committed, your Week 5 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-5 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 5, Problem 1]
- *Question* (jcanfield3-stat6250): Since we are defining filerefs, why is the command Filename instead of fileref?
- *Question* (akrishnamurthy-stat6250): How to associate a fileref to multiple external files? How to access specific files from a directory?
- *Answer* (akrishnamurthy-stat6250): The FILENAME can associate a fileref to a directory that contains multiple files. A specific file from the directory can then be referenced using the fileref followed by the individual filename in paranthesis.
- Question (ttruong59-stat6250): What is a major difference between LIBNAME and FILENAME statement?
- Answer (ttruong59-stat6250): We can use a LIBNAME statement to reference a SAS library while a FILENAME statement is used to reference an external file that contains the data.



[Course Textbook Chapter 5, Problem 2]
- *Question* (jcanfield3-stat6250): Can filrefs be removed without your permission?
- *Answer* (jcanfield3-stat6250): No since they can only be manually changed or when SAS is closed.
- *Question* (akrishnamurthy-stat6250): What is the scope of files referenced by FILENAME statement?
- Question (ttruong59-stat6250): What are fileref’s functions? And when are filerefs no longer effect in SAS session? 
- Answer (ttruong59-stat6250):  Filerefs perform the same function as librefs in where they temporarily point to a storage location for the data, but filerefs reference external data only. Filerefs are no longer in effect when users change, cancel them or SAS session was ended.



[Course Textbook Chapter 5, Problem 6]
- *Question* (jcanfield3-stat6250): Could all three solutions potentially work?
- *Answer* (jcanfield3-stat6250): Yes, if you add labels to the variables to match the given output.
- *Question* (akrishnamurthy-stat6250): How should the character and numeric data fields from raw file be defined in SAS dataset?
- *Answer* (akrishnamurthy-stat6250): While specifying character fields, the variable name should be followed by '$' sign.
- Question (ttruong59-stat6250): How to use INPUT statement correctly?
- Answer (ttruong59-stat6250): INPUT statement reads raw data in external files or data lines so users need to specify the variable name exactly as they appear in the dataset.



[Course Textbook Chapter 5, Problem 7]
- *Question* (jcanfield3-stat6250): Could you input different variables using overlapping columns?
- *Question* (akrishnamurthy-stat6250): Should all the colums from a raw file be read into SAS dataset ? Can the fields from raw file be read in any order ?
- Question (ttruong59-stat6250): Why is a $ sign used in a INPUT statement?
- Answer (ttruong59-stat6250): Once we specify the variable name in a INPUT statement, $ sign is used to identify character variables. 



[Course Textbook Chapter 5, Problem 8]
- *Question* (jcanfield3-stat6250): If income isn't predefined, what is the resulting output of income=income*2?
- *Question* (akrishnamurthy-stat6250): How to redefine a variable with a new value using SAS expressions?
- Question (ttruong59-stat6250): When does a user need to redefine the values of the variables? Is there any difference in term of redefining the values of the variable and creating a new variables?



[Course Textbook Chapter 6, Problem 1]
- *Question* (jcanfield3-stat6250): Is there a way to print the values of _N_ and _Error_?
- *Question* (akrishnamurthy-stat6250): While subsetting data, are the observations filtered during compilation phase ?
- Question (ttruong59-stat6250): What does SAS create during the compilation phase?
- Answer (ttruong59-stat6250): During the compilation phase SAS creates 3 items: input buffer, program data vector, and descriptor information.



[Course Textbook Chapter 6, Problem 2]
- *Question* (jcanfield3-stat6250): Which syntax errors halt the execution of the compilation phase?
- *Question* (akrishnamurthy-stat6250): If SAS can interpret a syntax error, will the program DATA step still compile?
- *Answer* (akrishnamurthy-stat6250): If SAS can interpret a syntax error, then the DATA step compiles and executes. If SAS cannot interpret a syntax error, then the DATA step compiles but does not execute.
- Question (ttruong59-stat6250): What are the most common syntax errors users often encounter?
- Answer (ttruong59-stat6250): Syntax error can detect the following errors as invalid options or variables, missing or invalid punctuation, missing or misspelled keywords. However it can't verify the values of variables or its format.



[Course Textbook Chapter 6, Problem 3]
- *Question* (jcanfield3-stat6250): Is there a memory cap for the amount of records that can be inputed?
- *Question* (akrishnamurthy-stat6250): Will the DATA step execute for each observation?
- Question (ttruong59-stat6250): Is it possible DATA step execute more than each record in the input file?



[Course Textbook Chapter 6, Problem 4]
- *Question* (jcanfield3-stat6250): Can a missing value be considered undefined?
- *Question* (akrishnamurthy-stat6250): How does _N_ and _ERROR_ values loop for each record in the file?
- Question (ttruong59-stat6250): What are the missing values set to at the beginning of the execution phase?
- Answer (ttruong59-stat6250): Missing numeric values are set to periods, and missing character values are presented by blanks.



[Course Textbook Chapter 6, Problem 5]
- *Question* (jcanfield3-stat6250): Why can _Error_ only take values 0 or 1? Wouldn't knowing the amount of errors be more useful?
- *Question* (akrishnamurthy-stat6250): Is the program data vector values initialized before every record read or will the input data be stored as an array in the program data vector?
- Question (ttruong59-stat6250): What is the value of _ERROR_ set to if there is more than one DATA error?
- Answer (ttruong59-stat6250): By default, the value of _ERROR_ is 0, and the value will be set to 1 when multiple errors occurred.



[Course Textbook Chapter 6, Problem 6]
- *Question* (jcanfield3-stat6250): Is the descriptor portion also reset along with the values?
- *Question* (akrishnamurthy-stat6250): After the iterative read by DATA statement, what happens to the program data vector during and after execution phase?
- Question (ttruong59-stat6250): At the beginning of an iteration of the DATA step, why is the automatic variable _ERROR_ reset to 0 if necessary? What is a significant reason to reset it to 0 again?



[basic_recipe_for_creating_analytic_datasets Week 5 Recipe]
- *Question* (jcanfield3-stat6250): Does the order matter for the keep, retain, and set functions?
- *Question* (akrishnamurthy-stat6250): Why does SAS read a DATA step twice for compilation and execution?
- Question (ttruong59-stat6250): Should users overwrite retain and keep statement to list more columns in the output when the statements were processed and executed or should users create a new statement for this purpose? Which method is more preferable?



[adv_recipe_for_creating_analytic_datasets Week 5 Recipe]
- *Question* (jcanfield3-stat6250): What are some other uses of proc sql?
- *Answer* (jcanfield3-stat6250): Proq Sql can be used to "retrieve and manipulate data that is stored in tables or views; create tables, views, and indexes on columns in tables; create SAS macro variables that contain values from rows in a query's result; add or modify the data values in a table’s columns or insert and delete rows. You can also modify the table itself by adding, modifying, or dropping columns; and send DBMS-specific SQL statements to a database management system (DBMS) and retrieve DBMS data". 
- *Question* (akrishnamurthy-stat6250): What is the function of PROC SQL statement? Can larger datasets be processed with PROC SQL ?
- Question (ttruong59-stat6250): What is a major difference of using retain/keep statement and proc sql statement? Which method is more preferable in term of using SAS?



