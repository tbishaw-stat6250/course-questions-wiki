## Week 5 Quiz Questions and Answers

In order to prepare your Week 5 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-5" in your fork of this repo. Then, after all edits have been made/committed, your Week 5 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-5 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************

− Question (ljiang11-stat6250): Assign a libref, we use statement LIBNAME, what is the statement for assigning a filefre?
− Answer (ljiang11-stat6250): FILENAME.
- *Question* (jcanfield3-stat6250): Since we are defining filerefs, why is the command Filename instead of fileref?
- *Question* (akrishnamurthy-stat6250): How to associate a fileref to multiple external files? How to access specific files from a directory?
- *Answer* (akrishnamurthy-stat6250): The FILENAME can associate a fileref to a directory that contains multiple files. A specific file from the directory can then be referenced using the fileref followed by the individual filename in paranthesis.
- Question (who7-stat6250): What is the advantage of creating a dataset without giving it a temp name?
- Question (ttruong59-stat6250): What is a major difference between LIBNAME and FILENAME statement?
- Answer (ttruong59-stat6250): We can use a LIBNAME statement to reference a SAS library while a FILENAME statement is used to reference an external file that contains the data.
- Question (lceballos-stat6250): What is the difference between fileref and filename?
- Question (nshrivastava2-stat6250): Which statements are needed from a SAS data set to a raw data file as it used the INFILE and INPUT statements to create a SAS data set?
- Answer (nshrivastava2-stat6250): We use the FILE and PUT statements from a SAS dataset to to a raw data file. 
- *Question* (jbettonville-stat6250): How would one correctly write the path for a filename in a Unix/Linux/macOS environment?
- *Question* (shatcher4-stat6250): What is a raw data file?
- Question (tchan49-stat6250): When you use FILENAME statement to read an external file, do you need to assign a name to the file?
- Answer (tchan49-stat6250): Yes, the name associated to the file is called fileref. 
- Question(dfei-stat6250): What's the rule of SAS statement associates the fileref Crime with the raw data file?
- Answer(dfei-stat6250): It is filename crime 'c:\states\data\crime.dat'
- *Question* (aamiri2-stat6250): What are the steps in creating a raw data file? How can one identify a raw data file in a SAS statement?
- Question (aguenane−stat6250): To read a raw data file, what four instructions must the DATA step provide to SAS?
- Answer (aguenane-stat6250): The location or name of the external text file, the name for the new SAS data set, the reference that identifies the external file, and a description of the data values to be read. 
- *Question* (ldai4-stat6250): What is the difference for FILENAME and LIBNAME?
- *Answer* (ldai4-stat6250): FILENAME statement can be used to point to external raw file; LIBNAME is used to assign a libref.



[Course Textbook Chapter 5, Problem 2]
− Question (ljiang11-stat6250): Is fileref only active in the current session?
- *Question* (jcanfield3-stat6250): Can filrefs be removed without your permission?
- *Answer* (jcanfield3-stat6250): No since they can only be manually changed or when SAS is closed.
- *Question* (akrishnamurthy-stat6250): What is the scope of files referenced by FILENAME statement?
- Question (who7-stat6250): How can we ensure filerefs update when we move the file?
- Question (ttruong59-stat6250): What are fileref’s functions? And when are filerefs no longer effect in SAS session? 
- Answer (ttruong59-stat6250):  Filerefs perform the same function as librefs in where they temporarily point to a storage location for the data, but filerefs reference external data only. Filerefs are no longer in effect when users change, cancel them or SAS session was ended.
- Question (lceballos-stat6250): How can a filename be reassigned?
- Question (nshrivastava2-stat6250): What is the significant role of LIBNAME and FILENAME statements?
- Answer (nshrivastava2-stat6250): LIBNAME and FILENAME statements are global. Librefs and filerefs remain in effect until you change them, cancel them, or end your SAS session. 
- *Question* (jbettonville-stat6250): Do changes made to a file that is designated by a fileref change the raw file itself, or only the object that has been created from the file in the SAS session?
- *Question* (shatcher4-stat6250): What is a fileref that is assigned using a FILENAME statement?
- *Answer* (shatcher4-stat6250): A fileref is a name associated with an external file, that is 1 to 8 characters long that begins with a letter or underscore, and contains only letters, numerals, or underscores.
- Question (tchan49-stat6250): Would Filerefs remain in effect permanently?
- Question(dfei-stat6250): Does Filerefs remain in effect after you cancel them or end your SAS session? 
- Answer(dfei-stat6250): No, they will not in effect.
- *Question* (aamiri2-stat6250): What are the differences and similarities between Fileref and Libref?
- Question (aguenane−stat6250): What is the difference between the LIBNAME and FILENAME statements?
- Answer (aguenane-stat6250): LIBNAME references a SAS library while FILENAME references an external file.
- *Question* (ldai4-stat6250): What is fileref? Is the function of fileref same as libref’s?



[Course Textbook Chapter 5, Problem 6]
− Question (ljiang11-stat6250): Will the variable name take from input statement?
- *Question* (jcanfield3-stat6250): Could all three solutions potentially work?
- *Answer* (jcanfield3-stat6250): Yes, if you add labels to the variables to match the given output.
- *Question* (akrishnamurthy-stat6250): How should the character and numeric data fields from raw file be defined in SAS dataset?
- *Answer* (akrishnamurthy-stat6250): While specifying character fields, the variable name should be followed by '$' sign.
- Question (who7-stat6250): Is there a max width for the dataset we create?
- Question (ttruong59-stat6250): How to use INPUT statement correctly?
- Answer (ttruong59-stat6250): INPUT statement reads raw data in external files or data lines so users need to specify the variable name exactly as they appear in the dataset.
- Question (lceballos-stat6250): What does the dollar ("$") sign do in the function?
- Answer (lceballos-stat6250): When using variables with character names, use the dollar sign.
- Question (nshrivastava2-stat6250): When we don't need to specify the LIBNAME?
- Answer (nshrivastava2-stat6250): We do not need to use LIBNAME statement, if we store the data set in a temporary SAS data set or if SAS has automatically assigned the libref for the permanent library.
- *Question* (jbettonville-stat6250): In the example shown in this problem, why would we use a dollar sign after 'ID'? In this case, isn't ID a numeric variable, and therefore should not be cast as a character variable?
- *Answer* (jbettonville-stat6250): While it is not made explicit in the example, the ID fields are not sequential, nor are any values beyond the four shown included; if other ID values contained characters, it would be appropriate to cast the ID field as a character variable.
- *Question* (shatcher4-stat6250): What information is needed in the INPUT statement to read each wanted field of raw data into a SAS data set?
- Question (tchan49-stat6250):How can you assign a new column name to each column in a output table where the columns are imported from raw table? 
- Question(dfei-stat6250): Why SAS shows 1-----+-----10-------+---------20-------+--------30 these kind of format?
- *Question* (aamiri2-stat6250): When running an INPUT statement, when are dollar signs ($) used and when is it not needed?
- *Answer* (aamiri2-stat6250): The dollar sign ($) identifies the variable as a character in the columns. It is usually used for characters such as name or sex. It is not used for age because this is already a numeric value so there is no need for the dollar sign.
- Question (aguenane−stat6250): When using the INPUT statement to describe the fields of raw data to be read and placed into the SAS data set, what does the dollar sign ($) do?
- Answer (aguenane-stat6250): It identifies the variable type as character. 
- *Question* (ldai4-stat6250): How can we use INPUT statement?
- *Answer* (ldai4-stat6250): The INPUT statement creates a Variable using the name that we assign to each field. There, when we write an INPUT statement, we need to specify the variable names exactly as we want them to appear in the SAS dataset.



[Course Textbook Chapter 5, Problem 7]
− Question (ljiang11-stat6250): Why Price has no dollar sign following? Do we not want it to be a character value?
- *Question* (jcanfield3-stat6250): Could you input different variables using overlapping columns?
- *Question* (akrishnamurthy-stat6250): Should all the colums from a raw file be read into SAS dataset ? Can the fields from raw file be read in any order ?
- Question (who7-stat6250): How can we format the numeric column to only have 2 decimal place?
- Question (ttruong59-stat6250): Why is a $ sign used in a INPUT statement?
- Answer (ttruong59-stat6250): Once we specify the variable name in a INPUT statement, $ sign is used to identify character variables. 
- Question (lceballos-stat6250): How can you combine different tables in SAS when the values are of the same domain?
- Question (nshrivastava2-stat6250): A raw data file is an external text file whose records contain data values that are organized in fields. Is The ruler is not part of the raw data file?
- Answer (nshrivastava2-stat6250): No, The ruler is not part of the raw data file. The file contains fixed fields; i.e values for each variable are in the same location in all records. 
- *Question* (jbettonville-stat6250): Can multiple variables contain the same column values in an input statement, or can each column only be used once?
- *Question* (shatcher4-stat6250): What can you do when using column input?
- *Answer* (shatcher4-stat6250): Read any or all fields from the raw data file, read the fields in any order, and specify only the starting column for values that occupy only one column.
- Question (tchan49-stat6250):How do you differentiate numeric and character variable when you input columns from raw dataset?
- Answer (tchan49-stat6250):Put a $ sign in front of the start column number if the variable is character. Nothing happens to the numeric variables. 
- Question(dfei-stat6250): Do I have to put some speical sign in "input" statement? 
- *Question* (aamiri2-stat6250): Does the ruler in a raw data file have a maximum limit? Is there another method to find out where individual fields begin and end?
- Question (aguenane−stat6250): If you wanted to name a new variable NewBalance, when do you need to specify it in the exact case you wanted stored and when can you specify the name in uppercase, lowercase, or mixed case?
- *Question* (ldai4-stat6250): Which variable need to add a $ before the name in using column input to read fields in any order?



[Course Textbook Chapter 5, Problem 8]
− Question (ljiang11-stat6250): What does 100 percent more mean?
− Answer (ljiang11-stat6250): 100% higher means double of the original.
- *Question* (jcanfield3-stat6250): If income isn't predefined, what is the resulting output of income=income*2?
- *Question* (akrishnamurthy-stat6250): How to redefine a variable with a new value using SAS expressions?
- Question (who7-stat6250): Can we use operator for character varailbe to add 2 words together?
- Question (ttruong59-stat6250): When does a user need to redefine the values of the variables? Is there any difference in term of redefining the values of the variable and creating a new variables?
- Question (lceballos-stat6250): Does the method income=income * 2 redifine every value of income?
- Answer (lceballos-stat6250): Yes, the values for income will all become 100% larger.
- Question (nshrivastava2-stat6250): What is the function of INFILE statement ?
- Answer (nshrivastava2-stat6250): Identify an external file and to verify the data, it is a good idea to use the OBS= option in the INFILE statement. Adding OBS=n to the INFILE statement enables you to process only records 1 through n, so you can verify that the correct fields are being read before reading the entire data file.
- *Question* (jbettonville-stat6250): Does SAS support iterative operators that are common in other programming languages? (i.e. ++ to increment a variable, -- to decrement)
- *Question* (shatcher4-stat6250): What happens when you use more than one arithmetic operator in an expression?
- Question (tchan49-stat6250):To create a new variable, is the re-defined name of the value on the left side of the equal sign or right side?
- Question(dfei-stat6250): Does to re-defines the values of the variable Income as 100 percent higher mean double the value?
- Answer(dfei-stat6250): Yes, it means 2 times the original variable.
- *Question* (aamiri2-stat6250): Can you use multiple arithmetic operators in an expression? If so, does order of operation automatically apply?
- *Answer* (aamiri2-stat6250): You can use many different arithmetic operations such as division, addition, subtraction, multiplication, and exponentiation. Negative prefixes have priority but then it goes by order of operations and parentheses can be used to control this better.
- Question (aguenane−stat6250): When you use more than one arithmetic operator in an expression, how do you control the order of operations?
- *Question* (ldai4-stat6250): How can we re-define the value of the variable?



[Course Textbook Chapter 6, Problem 1]
− Question (ljiang11-stat6250): When is the first observation created?
- *Question* (jcanfield3-stat6250): Is there a way to print the values of _N_ and _Error_?
- *Question* (akrishnamurthy-stat6250): While subsetting data, are the observations filtered during compilation phase ?
- Question (who7-stat6250): How is compiling in sas different from other programming language?
- Question (ttruong59-stat6250): What does SAS create during the compilation phase?
- Answer (ttruong59-stat6250): During the compilation phase SAS creates 3 items: input buffer, program data vector, and descriptor information.
- Question (lceballos-stat6250): What are the automatic variables used for?
- Question (nshrivastava2-stat6250): How can we use Null INPUT Statement? What it's fuctionality?
- *Question* (jbettonville-stat6250): How can we access the data set descriptor to find out more information about what is created during the DATA step?
- *Answer* (jbettonville-stat6250): We can use a PROC CONTENTS statement to reference the data set descriptor. The following example of this can be found at http://support.sas.com/resources/papers/proceedings10/069-2010.pdf:
proc contents data=‟libref‟.dataset; run;
- *Question* (shatcher4-stat6250): What is the purpose of the compilation phase?
- *Answer* (shatcher4-stat6250): Each statement is scanned for syntax errors.
- Question (tchan49-stat6250):Would the descriptor portion of the new SAS data set be created after the compilation phase completes? 
- Answer (tchan49-stat6250):No, it will be created at the end of the compilation phase. 
- Question(dfei-stat6250): What does compilation phase mean in SAS?
- *Question* (aamiri2-stat6250): During the compilation phase, SAS scans statements in the DATA step for syntax errors, what are some of the errors that may occur?
- *Answer* (aamiri2-stat6250): Some of the syntax errors that occur during the compilation phase are misspelled keywords or missing keywords, invalid variable names, missing or invalid punctuation, and invalid options.
- Question (aguenane−stat6250): What are the two automatic variables that can be used for processing contained in the program data vector?
- *Question* (ldai4-stat6250): How is the program data vector created during the compilation phase?
- *Answer* (ldai4-stat6250): During the compilation, the program data vector includes the two automatic variables_N_and_ERROR_. The descriptor portion of the new SAS data set is created at the end of the compilation phase. Observations are not written until the execution phase.



[Course Textbook Chapter 6, Problem 2]
− Question (ljiang11-stat6250): Why SAS cannot detect incorrect format?
- *Question* (jcanfield3-stat6250): Which syntax errors halt the execution of the compilation phase?
- *Question* (akrishnamurthy-stat6250): If SAS can interpret a syntax error, will the program DATA step still compile?
- *Answer* (akrishnamurthy-stat6250): If SAS can interpret a syntax error, then the DATA step compiles and executes. If SAS cannot interpret a syntax error, then the DATA step compiles but does not execute.
- Question (who7-stat6250): What are the most common syntax error?
- Question (ttruong59-stat6250): What are the most common syntax errors users often encounter?
- Answer (ttruong59-stat6250): Syntax error can detect the following errors as invalid options or variables, missing or invalid punctuation, missing or misspelled keywords. However it can't verify the values of variables or its format.
- Question (lceballos-stat6250): If the compiler detects a syntax error does it stop or does it continue to the end?
- Question (nshrivastava2-stat6250): How SAS Processes the Programs?
- Answer (nshrivastava2-stat6250): You first compile the SAS source program and store the compiled code. Then SAS execute the compiled code, redirecting the input and output as necessary. SAS processes the DATA step through the compilation phase and then stores an intermediate code representation of the program and associated data tables in a SAS file.
- *Question* (jbettonville-stat6250): What procedures should be used to detect errors that are not syntax errors, so that the code will run but may not produce the desired result?
- *Question* (shatcher4-stat6250): How does the program data vector work?
- Question (tchan49-stat6250):Are incorrect values and formats considered as syntax errors? 
- Question(dfei-stat6250): How many syntax errors in SAS programming? 
- *Question* (aamiri2-stat6250): When a syntax error of invalid options occurs, what can be done to correct this error? What precautions can be made to avoid such errors beforehand?
- Question (aguenane−stat6250): What happens when SAS finds a syntax error during the compilation phase?
- *Question* (ldai4-stat6250): What is a syntax error in SAS?



[Course Textbook Chapter 6, Problem 3]
− Question (ljiang11-stat6250): How the the DATA step execute?
− Answer (ljiang11-stat6250): It executes one record and iterate back to excute the second one.
- *Question* (jcanfield3-stat6250): Is there a memory cap for the amount of records that can be inputed?
- *Question* (akrishnamurthy-stat6250): Will the DATA step execute for each observation?
- Question (who7-stat6250): Are there other ways to create dataset with using the data statement?
- Answer (who7-stat6250): Yes, you can use proc sql to create table as well.
- Question (ttruong59-stat6250): Is it possible DATA step execute more than each record in the input file?
- Question (lceballos-stat6250): Does SAS support recursion functions?
- Question (nshrivastava2-stat6250): What are the errors SAS diagnose during compilation phase?
- Answer (nshrivastava2-stat6250): During the compilation phase, SAS can interpret some syntax errors such as misspelled keywords and data set names,unbalanced quotation marks,invalid options. 
- *Question* (jbettonville-stat6250): Under what circumstances might we want to execute the DATA step more or less than once per record in the input file?
- *Question* (shatcher4-stat6250): What happens during the execution phase?
- Question (tchan49-stat6250):Can the DATA step excutes each record in the input file more than once? 
- Answer (tchan49-stat6250):
- Question(dfei-stat6250): What is the original way to DATA step executes?
- *Question* (aamiri2-stat6250): After the Data step is compiled, what are the next steps during the execution phase?
- Question (aguenane−stat6250): A raw data file with 20 records on the file executes how many times during the DATA step? 
- *Question* (ldai4-stat6250): How does the DATA step work?



[Course Textbook Chapter 6, Problem 4]
- *Question* (jcanfield3-stat6250): Can a missing value be considered undefined?
- *Question* (akrishnamurthy-stat6250): How does _N_ and _ERROR_ values loop for each record in the file?
- Question (who7-stat6250): Why is the value o f_N_ set to 1 during the execution phase?
- Question (ttruong59-stat6250): What are the missing values set to at the beginning of the execution phase?
- Answer (ttruong59-stat6250): Missing numeric values are set to periods, and missing character values are presented by blanks.
- Question (lceballos-stat6250): What is the purpose of the _N_ variable?
- Answer (lceballos-stat6250): Everytime the data step is ran, the _N_ variable increases by 1.
- Question (nshrivastava2-stat6250): What are the errors SAS diagnose  in the Execution Phase?
- *Question* (jbettonville-stat6250): When the DATA step encounters an error, does the \_ERROR\_ variable increment to keep a running total of the number of errors that are encountered while processing the data file, or does it reset after each iteration of the DATA step?
- *Question* (shatcher4-stat6250): In the execution phase, what are missing numeric values and missing character values represented by?
- Question (tchan49-stat6250):How do you know if there are any missing numeric and character values on Program Data Vector?  
- Answer (tchan49-stat6250):Missing numeric values are represented by periods and missing character values are represented by blanks. 
- Question(dfei-stat6250): In SAS programming, what's the advanages to define the value of _N_ is 1 and the value of_ERROR_ is  0? 
- *Question* (aamiri2-stat6250): If _ERROR_ is 1 at the beginning of the execution phase, will it tell is exactly the source of the error?
- Question (aguenane−stat6250): If I was missing the item name, what symbol would represent this missing value?
- *Question* (ldai4-stat6250): How does the DATA step execute the missing variables?
- *Answer* (ldai4-stat6250): Missing numeric values are represented by periods, and missing character values are represented by blanks.
− Question (ljiang11-stat6250): Why at the beginning of the execution phase, the variables that aren't executed are set to missing?


[Course Textbook Chapter 6, Problem 5]
− Question (ljiang11-stat6250): How does the automatic variable _ERROR_ work?
− Answer (ljiang11-stat6250): It will display 1 when there are 1 or more errors.
- *Question* (jcanfield3-stat6250): Why can _Error_ only take values 0 or 1? Wouldn't knowing the amount of errors be more useful?
- *Question* (akrishnamurthy-stat6250): Is the program data vector values initialized before every record read or will the input data be stored as an array in the program data vector?
- Question (who7-stat6250): Would a syntax error be counted in the _ERROR_ value?
- Question (ttruong59-stat6250): What is the value of _ERROR_ set to if there is more than one DATA error?
- Answer (ttruong59-stat6250): By default, the value of _ERROR_ is 0, and the value will be set to 1 when multiple errors occurred.
- Question (lceballos-stat6250): What are the two values that _ERROR_ can be?
- Answer (lceballos-stat6250): If there is no error: 0. If there are any errors: 1.
- Question (nshrivastava2-stat6250): What specify the keyword _NULL_ as the data set name to view compilation or execution errors without creating a data set?
- *Question* (jbettonville-stat6250): If the \_ERROR\_ variable resets after each iteration of the DATA step, what is the purpose of including it?
- *Answer* (jbettonville-stat6250): One example might be for the purpose of debugging SAS code with a PUT statement that outputs the record number given by \_N\_ along with the \_ERROR\_ variable so that it can be determined if SAS received an error on a given record.
- *Question* (shatcher4-stat6250): Why would the automatic variable _ERROR_ reset to zero?
- Question (tchan49-stat6250):When would the value of the sutomatic variable _ERROR_ larger than one? 
- Question(dfei-stat6250): How to know What is the value of the automatic variable _ERROR_?
- *Question* (aamiri2-stat6250): What is the value of the automatic variable _ ERROR_ when there is more than one error? 
- Question (aguenane−stat6250): Why does the value of the automatic variable _ERROR_ only go from 0 to 1?
- *Question* (ldai4-stat6250): In program data vector, what does error 1 represent?
- *Answer* (ldai4-stat6250): Error signals are caused by the data during execution. The default value is 0, which means there is no error. When one or more errors occur, the value is set to 1.



[Course Textbook Chapter 6, Problem 6]
- *Question* (jcanfield3-stat6250): Is the descriptor portion also reset along with the values?
- *Question* (akrishnamurthy-stat6250): After the iterative read by DATA statement, what happens to the program data vector during and after execution phase?
- Question (who7-stat6250): What are the main limiatations when creating the descriptor portion of the dataset?
- Question (ttruong59-stat6250): At the beginning of an iteration of the DATA step, why is the automatic variable _ERROR_ reset to 0 if necessary? What is a significant reason to reset it to 0 again?
- Question (lceballos-stat6250): What is the descriptor portion of the data?
- Question (nshrivastava2-stat6250): Making, diagnosing, and resolving errors is part of the process of writing programs. What are the steps to ensure that save of time and hassel?
- Answer(nshrivastava2-stat6250): We need to make sure each SAS statement ends with a semicolon, filenames are spelled correctly, keywords are spelled correctly. 
- *Question* (jbettonville-stat6250): What is the underlying mechanism by which SAS knows to stop executing the DATA step when it finishes operating on the last record in a file?
- *Question* (shatcher4-stat6250): Why does the DATA step work like a loop?
- Question (tchan49-stat6250):When would the values of variables created in programming statements re-set to missing in program data vector? 
- Question(dfei-stat6250): The rule of iteration in SAS the same as in other computer languages?  
- *Question* (aamiri2-stat6250): What happens to the data during the beginning iteration DATA step? What information can be obtain during this step?
- Question (aguenane−stat6250): Why are the values of variables in the program data vector created in programming statements reset to missing at the end of the DATA step?
- *Question* (ldai4-stat6250): What action occurs at the end of the DATA step?
− Question (ljiang11-stat6250): Why is the values in PDV reset to missing?




[basic_recipe_for_creating_analytic_datasets Week 5 Recipe]
− Question (ljiang11-stat6250): Does the values in retain statement need to be exact the same as the values in keep statements?
- *Question* (jcanfield3-stat6250): Does the order matter for the keep, retain, and set functions?
- *Question* (akrishnamurthy-stat6250): Why does SAS read a DATA step twice for compilation and execution?
- Question (who7-stat6250): If the number of columns that needed to be removed is larger than the number of columns needed to keep, is it still best practice to use the KEEP statement instead of DROP statement?
- Answer (who7-stat6250): There are 2 views regarding this.  First, it may be wise to use DROP instead of KEEP as it will uses less lines of code.  Second, you may still want to use KEEP as it is a more clear way of showing which columns are actually using.
- Question (ttruong59-stat6250): Should users overwrite retain and keep statement to list more columns in the output when the statements were processed and executed or should users create a new statement for this purpose? Which method is more preferable?
- Question (lceballos-stat6250): Are both week 5 recipees equivalient?
- Question (nshrivastava2-stat6250):What retain, keep and drop perform in SAS Progrmaing and What is Program Data Vector(PDV) for SAS dataset?
- Answer (nshrivastava2-stat6250): The RETAIN statement specifies variables whose values are not set to missing at the beginning of each iteration of the DATA step. The KEEP statement specifies variables that are to be included in any data set that is being created and DROP specifies the names of the variables to omit from the output data set. Program Data Vector(PDV)is an area of memory where SAS stores variable values and attributes. It is the PDV that stores an observation as it is being processed in the DATA step.
- *Question* (jbettonville-stat6250): Under what circumstances might we want to have different values included in the KEEP and RETAIN statements in a DATA step?
- *Question* (shatcher4-stat6250): Why is important to have retain and keep statements?
- Question (tchan49-stat6250):Should you create a new name for the new dataset you create that obtains rows and columns from another dataset? 
- Answer (tchan49-stat6250):Yes, it is very important to name the new dataset to something unique and different from the dataset you obstain rows and colums from. 
This way, when you call out the dataset, it won't cause any confusions. 
- Question(dfei-stat6250): Why PDF is one of the most difficult parts in SAS?
- *Question* (aamiri2-stat6250): What are the differences between RETAIN and KEEP statements?
- Question (aguenane−stat6250): Even though it looks redundant to have the same variables in both the RETAIN and KEEP statements, why is this necessary?
- *Question* (ldai4-stat6250): How can we read a remote excel file in the SAS?

− Question (ljiang11-stat6250): Why SAS reading data by each record imply it can deal with big data? Can it store arbitrarily large amount of data?


[adv_recipe_for_creating_analytic_datasets Week 5 Recipe]
− Question (ljiang11-stat6250): Does PROC SQL's SELECT has the similar function as RETAIN and KEEP statements in DATA STEP? 
- *Question* (jcanfield3-stat6250): What are some other uses of proc sql?
- *Answer* (jcanfield3-stat6250): Proq Sql can be used to "retrieve and manipulate data that is stored in tables or views; create tables, views, and indexes on columns in tables; create SAS macro variables that contain values from rows in a query's result; add or modify the data values in a table’s columns or insert and delete rows. You can also modify the table itself by adding, modifying, or dropping columns; and send DBMS-specific SQL statements to a database management system (DBMS) and retrieve DBMS data". 
- *Question* (akrishnamurthy-stat6250): What is the function of PROC SQL statement? Can larger datasets be processed with PROC SQL ?
- Question (who7-stat6250): Are the command under PROC SQL the same as SQL itself?
- Answer (who7-stat6250): Yes, the commands are the same.
- Question (ttruong59-stat6250): What is a major difference of using retain/keep statement and proc sql statement? Which method is more preferable in term of using SAS?
- Question (lceballos-stat6250): What are some disadvantages of using PROC SQL?
- Question (nshrivastava2-stat6250): Can we create new varaibles using PROC SQL? If, yes please give brief explainations.
- Answer (nshrivastava2-stat6250):Variables can be dynamically created in PROC SQL. Dynamically created variables can be given a variable name, label, or neither. If a dynamically created variable is not given a name or a label, it will appear on the report as a column with no column heading.
- *Question* (jbettonville-stat6250): Why does PROC SQL require a QUIT statement at the end instead of a RUN statement?
- *Question* (shatcher4-stat6250): What is the purpose of proc sql?
- Question (tchan49-stat6250):When you finish the PROC SQL step, do you end it with RUN statement?
- Question(dfei-stat6250): How many types of task can data steps accomplish?
- *Question* (aamiri2-stat6250): How can we load our data using PROC SQL?
- Question (aguenane−stat6250): Even though PROC SQL requires less code (since it uses the select clause to combine the functions of the RETAIN and KEEP statements), when are the times when you want to use PROC SQL and when are the times you would want to use the regular DATA step?
- *Question* (ldai4-stat6250): How can we recover the right format of date for downloaded Excel file in SAS? 




