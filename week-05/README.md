## Week 5 Quiz Questions and Answers

In order to prepare your Week 5 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-5" in your fork of this repo. Then, after all edits have been made/committed, your Week 5 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-5 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 5, Problem 1]
- *Question* (cli19-stat6250): What are the benefits to using a FILENAME statement over importing data to a SAS library?
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
- Question (aguenane-stat6250): To read a raw data file, what four instructions must the DATA step provide to SAS?
- Answer (aguenane-stat6250): The location or name of the external text file, the name for the new SAS data set, the reference that identifies the external file, and a description of the data values to be read. 
- *Question* (ldai4-stat6250): What is the difference for FILENAME and LIBNAME?
- *Answer* (ldai4-stat6250): FILENAME statement can be used to point to external raw file; LIBNAME is used to assign a libref.
- Question (ldeng11-stat6250): When you refrencing a raw data file, you use the absulut file path, what you need to do if the raw data file is not saved in your local machine?
- Question(pcheng14-stat6250):When should we use the fileref Crime with the raw data as our SAS statement?
- *Question*(kamirneni-stat6250): If one does not want to specify a file extension for referencing a file in an aggregate storage location, what is the alternative?
- *Answer*(kamirneni-stat6250): The alternative is to put the filename in quotation marks.
- Question (lsun20-stat6250): Why we need to use quotation mark in this statement?
- *Question* (xyin6-stat6250): What should be included in the DATA step in order to read the raw data file?
- Question (tbishaw-stat6250): What do we need to do before reading raw data from a file in the SAS software?
- Answer (tbishaw-stat6250): We might need to reference the SAS library in which we will be storing the data set. Then we can write a DATA step program to read the raw data file and create a SAS data set.
* Question (ljiang11-stat6250): Assign a libref, we use statement LIBNAME, what is the statement for assigning a filefre?
* Answer (ljiang11-stat6250): FILENAME.
- *Question* (aacharya4−stat6250): To read a external raw data file, what are the instructions that DATA step must provide?
- *Answer* (aacharya4−stat6250):Location of the external file, name of new SAS data set, reference to locate external file, description of data values.
- *Question* (cnguyen77-stat6250): Which SAS statement can be used to reference an external file?
- *Answer* (cnguyen77-stat6250): You assign a fileref by using a FILENAME statement in the same way that you assign a libref by using a LIBNAME statement.
- *Question* (sbagdi-stat6250): Where are the filerefs defined for a SAS session listed?
- *Question* (asharda-stat6250): How do you use a FILENAME statement?.
- *Answer* (asharda-stat6250): When reading raw data, you can use the FILENAME statement to point to the location of the external file  that contains the data. Just as you assign a libref by using  a LIBNAME statement, you assign a fileref by using a FILENAME statement.



[Course Textbook Chapter 5, Problem 2]
- *Question* (cli19-stat6250): What is the best practice for maintaining filerefs when programming?
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
- Question (aguenane-stat6250): What is the difference between the LIBNAME and FILENAME statements?
- Answer (aguenane-stat6250): LIBNAME references a SAS library while FILENAME references an external file.
- *Question* (ldai4-stat6250): What is fileref? Is the function of fileref same as libref’s?
- Question (ldeng11-stat6250): What do the LIBNAME and FILENAME statements are global mean?
- Answer (ldeng11-stat6250): It means once the program excuted these statements, they are remain effect until you change them, cancel them, or end your SAS session.
- Question(pcheng14-stat6250):Are FILENAME statements global?
- Answer(pcheng14-stat6250):Yes, they are.
- *Question*(kamirneni-stat6250): What is the naming convention when declaring a new variable?
- *Answer*(kamirneni-stat6250): One must specify the variable in the exact case to be stored. After that, one can specify it any case.
- Question (lsun20-stat6250): Is there any other statement like FILENAME statement are global?
- *Question* (xyin6-stat6250): When is necessary to use a LIBNAME statement?
- *Answer* (xyin6-stat6250): When we have to reference the permanent SAS library in which thedata set will be stored.
- Question (tbishaw-stat6250): What SAS command can we use to create a report after using the DATA step to read the raw data?
- Answer (tbishaw-stat6250): After using the DATA step to read the raw data, we can use the PROC PRINT step to produce a report that displays the data values that are in the new data set. 
* Question (ljiang11-stat6250): Is fileref only active in the current session?
- *Question* (aacharya4−stat6250): Are LIBNAME and FILNENAME statements global in SAS?
- *Answer* (aacharya4−stat6250): Yes, LIBNAME and FILNENAME statements are global in SAS.
- *Question* (cnguyen77-stat6250): When does fileref remain in effect?
- *Answer* (cnguyen77-stat6250): Like LIBNAME statements, FILENAME statements are global; they remain in effect until you change them, cancel them, or end your SAS session.
- *Question* (sbagdi-stat6250): How to view the details about a referenced file?
- *Question* (asharda-stat6250): Are LIBNAME and FILENAME statements global?
- *Answer* (asharda-stat6250): Yes,LIBNAME and FILENAME statements are global.



[Course Textbook Chapter 5, Problem 6]
- *Question* (cli19-stat6250): What is the alternative to the INPUT statement in the case where a data set contains hundreds of variables and manually counting column location is not feasible?
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
- Question (aguenane-stat6250): When using the INPUT statement to describe the fields of raw data to be read and placed into the SAS data set, what does the dollar sign ($) do?
- Answer (aguenane-stat6250): It identifies the variable type as character. 
- *Question* (ldai4-stat6250): How can we use INPUT statement?
- *Answer* (ldai4-stat6250): The INPUT statement creates a Variable using the name that we assign to each field. There, when we write an INPUT statement, we need to specify the variable names exactly as we want them to appear in the SAS dataset.
- Question (ldeng11-stat6250): What is $ mean in the INPUT statement?
- Answer (ldeng11-stat6250): The dollar sign ($) identify the variable type as character; if the variable is numeric, then you don't need to anything.
- Question(pcheng14-stat6250):Have any other program can create the PROC PRINT same output?
- *Question*(kamirneni-stat6250): What should be included in the INFILE statement to process records 1 through n?
- Question (lsun20-stat6250): What is the usage of the dollar sign($)?
- Answer (lsun20-stat6250): The dollar sign($) is used to identify the character variables.
- *Question* (xyin6-stat6250): What does the dollar sign "$" in INPUT statement stand for?
- *Answer* (xyin6-stat6250): The dollar sign identifies the variable type as character (if the variable is numeric, then nothing appears here).
- Question (tbishaw-stat6250): why would we need to use the LIBNAME statement as we are writing a program?
* Question (ljiang11-stat6250): Will the variable name take from input statement?
- *Question* (aacharya4−stat6250): What is the purpose of the INPUT statement in SAS?
- *Answer* (aacharya4−stat6250): The input statement creates variables in the SAS dataset as per the names, types and number of fields as mentioned in the INPUT statement.
- *Question* (cnguyen77-stat6250): What does the dollar sign ($) in INPUT statement mean?
- *Answer* (cnguyen77-stat6250): The dollar sign ($) identifies the variable type as character (if the variable is numeric, then nothing appears here).
- *Question* (sbagdi-stat6250):  Why a dollar ($) sign must be put in an INPUT statement?
- *Answer* (sbagdi-stat6250): A dollar sign identifies the variable type as a character.
- *Question* (asharda-stat6250):  What is the use of INPUT statement?
- *Answer* (asharda-stat6250): The INPUT statement creates a variable using the name that you assign to each field.



[Course Textbook Chapter 5, Problem 7]
- *Question* (cli19-stat6250): What can we expect if we do not specify an INPUT statement variable type?
- *Answer* (cli19-stat6250): SAS will return numeric missing values for that unspecified field.
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
- Question (ldeng11-stat6250): What you need to do if you want to read the raw data in your own order, not follow the order saved in the raw data file?
- Question(pcheng14-stat6250):In order to  correctly reads the fields, do we must specify the variable name, identify character variables with a $, and specify the correct starting and ending column for each field?
- Answer(pcheng14-stat6250):We do.
- *Question*(kamirneni-stat6250): Can date be assigned to variables, if yes, how?
- Question (lsun20-stat6250): Is there any order of input these column?
- Answer (lsun20-stat6250): We can use column input to read fields in any order.
- *Question* (xyin6-stat6250): When should we use INPUT statement?
- *Answer* (xyin6-stat6250): The INPUT statement describes the fields of raw data to be read and placed into the SAS data set.
- Question (tbishaw-stat6250): What is a fileref and what are the criterias for implementing for the fileref name? 
- Answer (tbishaw-stat6250): fileref is a name you assoiate wit han external file and the name must be 1 to 8 characters long. And the name has to also begin with a letter or underscore, and contain only letters, numerals, or underscores.
* Question (ljiang11-stat6250): Why Price has no dollar sign following? Do we not want it to be a character value?
- *Question* (aacharya4−stat6250): How can we distinguish between a character variable and numeric variable in INPUT statement?
- *Answer* (aacharya4−stat6250): The character variables are followed by a '$' in INPUT statements while numeric variables are not.
- *Question* (cnguyen77-stat6250): Is it necessary to read fields in an order when using column input?
- *Answer* (cnguyen77-stat6250): You can use column input to read fields in any order. You must specify the variable name, identify character variables with a $, and specify the correct starting and ending column for each field.
- *Question* (sbagdi-stat6250): What does startcol and endcol represent in an input statement?
- *Question* (asharda-stat6250): Is Column input appropriate in all situations?
- *Answer* (asharda−stat6250): Column input is appropriate only in some situations. When you use column input,your data must be standard character and numeric values, and these values must be in fixed fields.



[Course Textbook Chapter 5, Problem 8]
- *Question* (cli19-stat6250): Is it considered "bad practice" to create a new variable using the same name as an existing variable?
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
- Question (ldeng11-stat6250): How do you correctly use the operators in SAS expression?
- Question(pcheng14-stat6250):When shoudl we re-defines the values?
- Answer(pcheng14-stat6250):Depends on quesion or situation, if the question need to re-defines values.
- *Question*(kamirneni-stat6250): Does subsetting DATA create a new file with the conditional data or make changes to the original file?
- Question (lsun20-stat6250): Does the new variable Income need a new name, such as Income_1, which is different from the original one?
- *Question* (xyin6-stat6250): What is the format of re-defining a variable? (numeric value)
- Question (tbishaw-stat6250): When do you use a subsetting IF statment? 
* Question (ljiang11-stat6250): What does 100 percent more mean?
* Answer (ljiang11-stat6250): 100% higher means double of the original.
- *Question* (aacharya4−stat6250): What is used as an assignment operator in SAS?
- *Answer* (aacharya4−stat6250): The '=' is used as an assignment operator in SAS.
- *Question* (cnguyen77-stat6250): How to re-define the values of a variable in an assignment statement?
- *Answer* (cnguyen77-stat6250): To re-define the values of a variable in an assignment statement, you specify the variable name on the left side of the equal sign and an appropriate expression including the variable name on the right side of the equal sign.
- *Question* (sbagdi-stat6250): What should be the range of length of variable names in SAS?
- *Question* (asharda-stat6250): How do you re-define the values of the variable in an assignment statement?
- *Answer* (asharda−stat6250): To re-define values of the variable in an assignment statement, one must specify the variable name on the left side of the equal sign and an appropriate expression including the variable name on the right side of the equal sign.



[Course Textbook Chapter 6, Problem 1]
- *Question* (cli19-stat6250): What is the purpose in viewing the descriptor portion of the data set?
- *Answer* (cli19-stat6250): The descriptor portion contains information on the physical data set as well as information on individual variables. It can be used to get an overview of the output data set or even leveraged using PROC DATASETS to improve SAS code efficiency.
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
- Question (ldeng11-stat6250): What will happen during the compilation phase?
- Question(pcheng14-stat6250):Why "the program data vector" is created during the compilation phase?
- *Question*(kamirneni-stat6250): Why is raw data considered for creating a input buffer, and not SAS data at all?
- Question (lsun20-stat6250): What is the data set descriptor include?
- Answer (lsun20-stat6250): The description includes the name of the data set, the number of observations and variables and the names and attributes of the variables.
- *Question* (xyin6-stat6250): What is happening during the compilation phase?
- *Answer* (xyin6-stat6250): During the compilation phase, each statement is scanned for syntax
errors. Most syntax errors prevent further processing of the DATA step. When the compilation phase is complete, the descriptor portion of the new data set is created.
- Question (tbishaw-stat6250): How is a SAS DATA step processed? 
- Answer (tbishaw-stat6250): A SAS DATA step is processed in two phases: Compilation Phase and Execution Phase.
* Question (ljiang11-stat6250): When is the first observation created?
- *Question* (aacharya4−stat6250): What are the automatic variables of Program Data Vector (PDV)?
- *Question* (cnguyen77-stat6250): When is the descriptor of the new SAS data set created?
- *Answer* (cnguyen77-stat6250): The descriptor portion of the new SAS data set is created at the end of the compilation phase. The descriptor portion includes the name of the data set, the number of observations and variables, and the names and attributes of the variables. Observations are not written until the execution phase.
- *Question* (sbagdi-stat6250): Why is an input buffer created? Which DATA step phase is it created in?
- *Question* (asharda-stat6250): What is created at the beginning of compilation phase?
- *Answer* (asharda-stat6250): At the beginning of the compilation phase, the input buffer (an area of memory) is created to hold a record from the external file.



[Course Textbook Chapter 6, Problem 2]
- *Question* (cli19-stat6250): Are there other debugging features built into SAS?
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
- Question (ldeng11-stat6250): What are the syntax errors?
- Question(pcheng14-stat6250):Besdies verify the values of variables or the correctness of formats, what else errors Syntax checking can't detect?
- *Question*(kamirneni-stat6250): What is a program data vector?
- *Answer*(kamirneni-stat6250): It is the area of memory where SAS holds one observation at a time.
- Question (lsun20-stat6250): Why the invalid option or variable name should be considered as a syntax error? 
- *Question* (xyin6-stat6250): What are typical types of syntax errors?
- Question (tbishaw-stat6250): What is stored in the program data vector afeter the input buffer is created?
* Question (ljiang11-stat6250): Why SAS cannot detect incorrect format?
- *Question* (aacharya4−stat6250): What constitutes syntax errors that are checked during compilation phase?
- *Answer* (aacharya4−stat6250): Synatax error include invalid variable names/options, missing or invalid punctuation, missing or misspelled words.
- *Question* (cnguyen77-stat6250): What are the common errors that a syntax checking can identify?
- *Answer* (cnguyen77-stat6250): Syntax checking can detect many common errors including invalid options or variable names, missing or invalid punctuation, missing or misspelled keywords. However, it cannot verify the values of variables or the correctness of formats.
- *Question* (sbagdi-stat6250): What are different syntax errors that can be identified by syntax checking?
- *Question* (asharda-stat6250): What does SYNTAX errors include?



[Course Textbook Chapter 6, Problem 3]
- *Question* (cli19-stat6250): How does the execution of the DATA step change when other statements are added?
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
- Question (ldeng11-stat6250): During the execution phase, how the DATA step works?
- Question(pcheng14-stat6250):Why DATA step executes only once for each record in the input file?
- *Question*(kamirneni-stat6250): After the end of DATA step, why variable values in the program data vector are re-set to missing?
- Question (lsun20-stat6250): When the DATA step will executes?
- *Question* (xyin6-stat6250): Is the descriptor portion of the SAS data created after the program data vector being created or before?
- Question (tbishaw-stat6250): What are some examples of some syntax errors?
- Answer (tbishaw-stat6250): Missing or misspelled keywords, invalid variable names, missing or invalid punctuation, and invalid options.
* Question (ljiang11-stat6250): How the the DATA step execute?
* Answer (ljiang11-stat6250): It executes one record and iterate back to excute the second one.
- *Question* (aacharya4−stat6250): What is the difference when DATA step reads data raw data as compared to reading from a SAS dataset?
- *Answer* (aacharya4−stat6250): When DATA step reads data raw data, SAS reads each record of the data in an input buffer as compared to SAS dataset, in that case SAS reads directly into Program Data Vector.
- *Question* (cnguyen77-stat6250): When are records in the input raw data file written to the new data set as observations?
- *Answer* (cnguyen77-stat6250): During execution, each record in the input raw data file is read into the input buffer, copied to the program data vector, and then written to the new data set as an observation. The DATA step executes once for each record in the input file, unless otherwise directed by additional statements.
- *Question* (sbagdi-stat6250): What are the two important phases of a DATA step?
- *Question* (asharda-stat6250): Are variables that are created with an assignment statement in the DATA step , also added to the program data vector?
- *Answer* (asharda-stat6250): Yes,Any variables that are created with an assignment statement in the DATA step are also added to the program data vector.



[Course Textbook Chapter 6, Problem 4]
- *Question* (cli19-stat6250): Is it possible to change the default initializations from missing to a specified value?
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
- Question (ldeng11-stat6250): At the beginning of the execution phase, why the value of _N_ is 1, the value of _ERROR_ is 0, and what are the values of the remaining variables?
- Answer (ldeng11-stat6250): Because at the beginning of the execution phase, we are reading the first observation, and there is no error sofar, so the value of _N_ is 1, the value of _ERROR_ is 0, and the values of the remainning variables are setting to missing.
- Question(pcheng14-stat6250):Why missing numeric values are represented by periods, and missing character values are represented by blanks?
- *Question*(kamirneni-stat6250): Why are there exceptions for SAS to set value of variable missing in DATA statement at beginning of each cycle of execution? What happens if the exceptions are ignored?
- Question (lsun20-stat6250): Why the answer is "missing"?
- *Question* (xyin6-stat6250): What statement is the next after defining the _N_ & _ERROR_ values?
- Question (tbishaw-stat6250): What are included in the descriptor portion of the SAS data set?
* Question (ljiang11-stat6250): Why at the beginning of the execution phase, the variables that aren't executed are set to missing?
- *Question* (aacharya4−stat6250): What happens to the automatic variable 'N' of program data vector with each iteration of the DATA step?
- *Answer* (aacharya4−stat6250): With each iteration of the DATA step, the automatic variable 'N' is increamented by 1.
- *Question* (cnguyen77-stat6250): What are the values of the remaining variables set to at the beginning of the execution phase?
- *Answer* (cnguyen77-stat6250): The remaining variables are initialized to missing. Missing numeric values are represented by periods, and missing character values are represented by blanks.
- *Question* (sbagdi-stat6250): How many times does a DATA step executes for each record in an input file? Can that be manages by the programmer?
- *Answer* (sbagdi-stat6250): The DATA step executes once for each record in the input file. This execution can be managed by the programmer; directions can be given to do so.
- *Question* (asharda-stat6250): What is the value of ERROR at the beginning of the execution phase?
- *Answer* (asharda-stat6250): Because there are no data errors, the value of ERROR is 0



[Course Textbook Chapter 6, Problem 5]
- *Question* (cli19-stat6250): When data errors are encountered, does SAS produce outputs?
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
- Question (ldeng11-stat6250): What is the value of _ERROR_ if you have three errors? 
- Question(pcheng14-stat6250):How many times errors can be happened during running a program? 
- *Question*(kamirneni-stat6250): How do PROC FREQ and PROC MEANS filter invalid data?
- Question (lsun20-stat6250): Is the value of the automatic variable_ERROR_ calculate by times?
- *Question* (xyin6-stat6250): What is the value of variable _ERROR_ at the end of the DATA step?
- Question (tbishaw-stat6250): How many times does the dATA step execute for each record in the input file? What are the exceptions?
- Answer (tbishaw-stat6250): The DATA step executes once for each record in the inut file, unless otherwise directed by an additional statements.
* Question (ljiang11-stat6250): How does the automatic variable _ERROR_ work?
* Answer (ljiang11-stat6250): It will display 1 when there are 1 or more errors.
- *Question* (aacharya4−stat6250): What is the default value of automatic variable 'ERROR' of Program Data Vector(PDV)? 
- *Answer* (aacharya4−stat6250): The default value of 'ERROR' variable of PDV is 0. This indicates no error, which changes to 1 in case error occurs in data execution.
- *Question* (cnguyen77-stat6250): What is the value of the automatic variable_ERROR_ when multiple errors occur?
- *Answer* (cnguyen77-stat6250): The default value of _ERROR_ is 0, which means there is no data error. When an error occurs, whether one error or multiple errors, the value is set to 1.
- *Question* (sbagdi-stat6250): What type of an error is ‘incorrectly identifying a variable’s type’?
- *Answer* (sbagdi-stat6250): Incorrectly identifying a variable type is an execution-time error.
- *Question* (asharda-stat6250): What is the value of ERROR for multiple errors?
- *Answer* (asharda-stat6250): Whether one error or multiple errors, the value of ERROR is set to 1.



[Course Textbook Chapter 6, Problem 6]
- *Question* (cli19-stat6250): Why does the program data vector get reset to missing with each iteration?
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
- Question (ldeng11-stat6250): What will happen during the DATA step?
- Question(pcheng14-stat6250):Why the automatic variable _ERROR_ is reset to 0 if necessary?
- *Question*(kamirneni-stat6250): Is it efficient to delete observations which have invalid data instead of correcting them?
- Question (lsun20-stat6250): What is descriptor portion of the data set?
- *Question* (xyin6-stat6250): When reading variables from a SAS data set,does SAS sets the vaues to missing first?
- Question (tbishaw-stat6250): How can you detect common errors and save development time? 
- Answer (tbishaw-stat6250): You can use the OBS= option in the INFILE statement to limit the number o observations that are read or created during the DATA step. 
* Question (ljiang11-stat6250): Why is the values in PDV reset to missing?
- *Question* (aacharya4−stat6250): When is descriptor information created during compilation phase of SAS program?
- *Question* (cnguyen77-stat6250): What happens at the beginning of an iteration of the DATA step?
- *Question* (sbagdi-stat6250): What happens at the beginning of the iteration of a DATA step?
- *Question* (asharda-stat6250): What happens at the end of DATA step?



[basic_recipe_for_creating_analytic_datasets Week 5 Recipe]
- *Question* (cli19-stat6250): In what other ways can the RETAIN statement be used?
- *Answer* (cli19-stat6250): The RETAIN statement can be combined with other statements to compare values across observations, for example.
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
- Question (ldeng11-stat6250): What is the difference between retain and keep staments?
- Question(pcheng14-stat6250):Is any other way can tell SAS which rows and columns to include in a newly created dataset?
- *Question*(kamirneni-stat6250): Which is more efficient in loading data from disk, PDV in SAS or R/SQL, considering time and size of data?
- Question (lsun20-stat6250): Is there any limit number of column from the data set?
- *Question* (xyin6-stat6250): If the variable appears in retain, does it have to be in the keep statement?
- Question (tbishaw-stat6250): Is there a way to tell SAS which rows and columns to include in a newly created data set? If so how?
* Question (ljiang11-stat6250): Why SAS reading data by each record imply it can deal with big data? Can it store arbitrarily large amount of data?
* Question (ljiang11-stat6250): Does the values in retain statement need to be exact the same as the values in keep statements?
- *Question* (aacharya4−stat6250): What is the purpose of keeping the same set of columns in the retain and keep statement?
- *Question* (cnguyen77-stat6250): What is the difference between retain and keep statements?
- *Question* (sbagdi-stat6250): Why is it important to explicitly list output columns? Which statement, if not the Keep statement, can be used to list columns to keep in output?
- *Answer* (sbagdi-stat6250): It is considered best practice to explicitly list output column, so that the code is more self-documenting. The drop statement can also be used to list the columns to keep in output.
- *Question* (asharda-stat6250): In addition to variable names what does a PDV also keep track of?



[adv_recipe_for_creating_analytic_datasets Week 5 Recipe]
- *Question* (cli19-stat6250): Aside from differences in number of lines of code or required disk space, how can one decide whether SAS procedures or PROC SQL is the better option?
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
- Question (aguenane-stat6250): Even though PROC SQL requires less code (since it uses the select clause to combine the functions of the RETAIN and KEEP statements), when are the times when you want to use PROC SQL and when are the times you would want to use the regular DATA step?
- *Question* (ldai4-stat6250): How can we recover the right format of date for downloaded Excel file in SAS? 
- Question (ldeng11-stat6250): What are the advantages and the disadvantages when using PROC SQL?
- Question(pcheng14-stat6250):Why many SAS programmers rely on proc sql for the bulk of their data manipulation tasks?
- *Question*(kamirneni-stat6250): What is the advantage of using PROC SQL over the conventional retain and keep method?
- *Answer*(kamirneni-stat6250): it can also be used as a substitute for proc means, proc freq, and many other proc statements with the right syntax to make the code and dataset result more efficient.
- Question (lsun20-stat6250): Is there any limitation of the column name? Such as can not end as a number?
- *Question* (xyin6-stat6250): Other than "Select", what other command does PROC SQL have that is convenience for data manipulation steps?
- Question (tbishaw-stat6250): What is the Program Data Vector (PDV) and how is it used in SAS?   
- Answer (tbishaw-stat6250): PDV is one of the most complex parts of using SAS and takes a lot of practice. PDV is one of the main features of SAS, and it allows SAS to read datasets one record at a time. 
- *Question* (ldai4-stat6250): How can we recover the right format of date for downloaded Excel file in SAS?
* Question (ljiang11-stat6250): Does PROC SQL's SELECT has the similar function as RETAIN and KEEP statements in DATA STEP?
- *Question* (aacharya4−stat6250): What is the difference between loading data using PROC SQL statement instead of using DATA step using RETAIN and KEEP statements?
- *Answer* (aacharya4−stat6250): When PROC SQL statement is used to load data, it loads all records of a dataset into the memory from the memory at one go. In case of DATA step, records are loaded into the memory one by one from disk.
- *Question* (cnguyen77-stat6250): What are the pros of using Proc sql in SAS?
- *Question* (sbagdi-stat6250): What is the limitation of PROC SQL over the Retain and Keep statements in SAS?
- *Question* (asharda-stat6250): What is one of the drawback of using proc sql?



