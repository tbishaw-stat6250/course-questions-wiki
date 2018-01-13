
## Week 2 Quiz Questions and Answers

In order to prepare your Week 2 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-2" in your fork of this repo. Then, after all edits have been made/committed, your Week 2 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-2 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 1, Problem 1]
- Question (lceballos-stat6250): How do we make the width lenght on the text window editor to 80 characters?
- Question (pcheng14−stat6250): What are the variables meaning?
- Answer (pcheng14−stat6250): There are the properties information includes the variable's name, type, length, format, informat, and label.
- Question (lsun20-stat6250): Does evey rows can only have one data in each variables?
- *Question* (aacharya4−stat6250): In SAS dataset, what does the rows and columns represent?
- *Answer* (aacharya4−stat6250): In SAS dataset, the number of rows represent the number of observations and the columns represent the variables.
- Question (ljiang11−stat6250): Why the values of Sex and Age are in the middle? Isn't character type data align to the left, and numeric data align to the right?
- *Question* (cnguyen77-stat6250): How to identify observations and variables in SAS data set?
- *Answer* (cnguyen77-stat6250): Observations in the data set correspond to rows or data lines. Variables in the data set correspond to columns. If a data value is unknown for a particular observation, a missing value is recorded in the SAS data set.
- Question (xyin6-stat6250): How many observations and variables can a data set contain? How to count observations/variables?
- Answer (xyin6-stat6250): As many as you can. Typically, rows are observations and colomns are variables.
- *Question* (jcanfield3-stat6250): Why does a period represent a blank numeric value?
- *Question* (aamiri2-stat6250): What are the differences between a variable and an observation?
- *Answer* (aamiri2-stat6250):  An observation are the rows in the data set that usually relates to a single object. A variable are the columns in the data set that describe a certain characteristic.
- Question (who7-stat6250): Would it be considered a variable if not data is stored in any of the variables? 
- Question(tchan49-stat6250): How do you call columns and rows in SAS data set?
- Answer(tchan49-stat6250): Columns are called variables and rows are called oberservations
- Question (ttruong59-stat6250): In SAS, what are observations and variables in the data set?
- Asnwer (ttruong59-stat6250): Observations, aka rows, in the data set are collections of data values that relate to a single project while variables, aka columns, are collection of values that describe a particular characteristics.
- Question (nshrivastava2-stat6250): What other information other than Observation and Variable output are present in Decsriptor portion.
- Answer(nshrivastava2-stat6250): The descriptor portion contains information about the attributes of each variable in the data set.The attribute information includes the variable's name, type, length, format, informat, and label
- *Question* (shatcher4-stat6250): How many observations can a SAS data set store?
- *Answer* (shatcher4-stat6250): Any number of observations.
- *Question* (akrishnamurthy-stat6250):What is an observation in SAS? Can a row with missing values be considered as an observation?
- *Question* (ldai4-stat6250): What is observations and variables in the data set?
- *Answer* (ldai4-stat6250): In the data set, rows are called observations, and columns are called variables.
- Question (ldeng11−stat6250): What are the observation and variable meaning in SAS?
- Answer (ldeng11−stat6250): In SAS data set, rows(observations) are the collections of data values typically relate to a single object. Columns(variables) are the collections of values describe a particular characteristics. 
- *Question* (jbettonville-stat6250): If a value is missing from a data set, how does this impact analysis processes that are run on the data set? Does a command fail due to a missing value, or does it disregard the record? Is there a way to specify how SAS should behave when values are missing?
- *Question* (cli19−stat6250): How can we view a summary or overview of a dataset that includes the number of observations or the number of variables? 
- *Answer* (cli19−stat6250): The PROC CONTENTS procedure in SAS can allow us a general overview of what we can expect to see in our dataset specified.
- Question (dfei−stat6250): What does observation mean in programming?



[Course Textbook Chapter 1, Problem 2]
- Question (lceballos-stat6250): Since SAS runs a program everytime it reads PROC or DATA, is the run command necessary for running SAS programs?
- Question (pcheng14−stat6250): What is the lowest program steps are executed in the program when program is processed?
- Answer:one
- Question (lsun20-stat6250): Is there any other statements can make the SAS stop reading statement and executes the step in the program? 
- *Question* (aacharya4−stat6250): In SAS, what is meant by a program step?
- *Answer* (aacharya4−stat6250): In SAS, a program step is defined as the part that starts with SAS keyword DATA or PROC and ends with a ";". 
The step that starts with keyword DATA is called DATA step while the one beginning with keyword PROC is called PROC step.
- Question (ljiang11−stat6250): How many steps are in this program?
- Answer (ljiang11−stat6250): There are 3 steps, 1 data step and 2 proc steps.
- *Question* (cnguyen77-stat6250): What types of steps forms in SAS Programs?
- *Answer* (cnguyen77-stat6250): SAS programs consist of two types of steps: DATA steps and PROC (procedure) steps. These two steps, alone or combined, form most SAS programs.
- Question (xyin6-stat6250): How to find the point of program steps being executed in the program?
- Answer (xyin6-stat6250): "Run" and "Quit" statement mark step boundaries, at the step boundary, SAS executes any statements that have not previously being executed.
- *Question* (jcanfield3-stat6250): What does the infile command do?
- *Answer* (jcanfield3-stat6250): The infile command points to the location of the file to be used.
- *Question* (aamiri2-stat6250): In some SAS codes there are often words that are separated by a period also known as two-level names, what is the reason for doing this and is there an alternative method?
- Question (who7-stat6250): Would the command "run;" be counted as a program step?
- Answer (who7-stat6250): It would be counted as a program step as it is executing a line of code.
- Question(tchan49-stat6250):Is run statement required before you start a new step?
- Question (ttruong59-stat6250): What are the main differences between DATA steps and PROC steps in SAS?
- Asnwer (ttruong59-stat6250): DATA steps are used to create to create or modify SAS data sets, and can also be used to produce custom-designed reports. In contrast, PROC steps are used to invoke or call pre-written routines that enable us to analyze and process in a SAS data set, and can also be used to list, sort, and summarize data.
- Question (nshrivastava2-stat6250): How the program steps form in SAS?
- Answer(nshrivastava2-stat6250): A SAS program can consist of a DATA step, a PROC step, or any combination of DATA and PROC steps.DATA steps typically create or modify SAS data sets, but they can also be used to produce custom-designed reports. PROC steps are pre- written routines that enable you to analyze and process the data in a SAS data set and to present the data in the form of a report. PROC steps sometimes create new SAS data sets that contain the results of the procedure.
- *Question* (shatcher4-stat6250): What are the different statements that can be used in SAS?
- *Question* (akrishnamurthy-stat6250):When will SAS execute a DATA, PROC or RUN statement?
- *Answer* (akrishnamurthy-stat6250):SAS executes the previous steps in the program when it encounters a DATA,PROC or RUN statements. RUN statements are not always required to specify execution step but using RUN statements makes the program and log more readable.
- *Question* (ldai4-stat6250): what two steps can be in most SAS programs?
- *Answer*  (ldai4-stat6250): A SAS program can consist of a DATA step or a PROC step or any combination of DATA and PROC steps.
- Question (ldeng11−stat6250): What is DATA step? What is PROC step?
- *Question* (jbettonville-stat6250): Most programming languages have specific style standards when writing code that describe proper indentation, control structures, and use of whitespace; are there any common formatting conventions we should follow when creating SAS recipes?
- *Question* (cli19−stat6250): Can procedures be combined to decrease the number of steps to be processed?
- Question (dfei−stat6250): How to count program steps in SAS?



[Course Textbook Chapter 1, Problem 3]
- Question (lceballos-stat6250): For attributes with a data type, is it possible to change the variable data type after it was assigned?
- Answer (lceballos-stat6250): Yes, using an input function.
- Question (pcheng14−stat6250): What is the meaning of numberic for the type of variable?
- Answer (pcheng14−stat6250): It shows the number type as the variable.
- Question (lsun20-stat6250): How many type of variables in the SAS? and what are them?
- *Question* (aacharya4−stat6250): In SAS, what are the properties of character variable?
- *Answer* (aacharya4−stat6250): The properties of character variable in SAS are :
1. Character variables can be upto 32,767 bytes(the number of bytes used to store character variable)long.
2. Character variable can contain any value.
3. A blank (-) represents a missing value in character variable.
- Question (ljiang11−stat6250): Can digits also be character type of data?
- *Question* (cnguyen77-stat6250): What are the types of a variable in SAS?
- Question (xyin6-stat6250): How long can character variable be? Can character variables contain numbers?
- *Question* (jcanfield3-stat6250): Can a character value consisting of numbers be transformed into a numeric value?
- *Question* (aamiri2-stat6250): How common are missing data in a dataset? Does this affect the analysis, if so what can we do to improve our dataset?
- Question (who7-stat6250): Why would we use a numeric variable is char variable covers both numeric and characters?
- Question(tchan49-stat6250):What is the type of data that contains letters and numbers?
- Question (ttruong59-stat6250): Can a numeric variable contain letters and underscore?
- Asnwer (ttruong59-stat6250): No, only a character variable can.
- Question (nshrivastava2-stat6250): If the Value is missing from the dataset, How it interprets for character variables.
- Answer(nshrivastava2-stat6250): For character variables, a blank represents a missing value.
- *Question* (shatcher4-stat6250): What purpose does a variable type serve?
- *Question* (akrishnamurthy-stat6250):Can special characters be assigned to numeric variables ?
- *Question* (ldai4-stat6250): Can a variable be either character or numeric? 
- Question (ldeng11−stat6250): What are the types of variable?
- Answer (ldeng11−stat6250): There are two types of variable, numeric, and charactor
- *Question* (jbettonville-stat6250): When dealing with data from an outside source that contains numerical values in a predictable format that contain non-numerical values (i.e. 3456_1), how might one parse a value into two separate column values in a record (i.e. a record with 3456 in one column and 1 in another)?
- *Question* (cli19−stat6250): What happens when a variable that contains a mix of character/numeric observations is formatted as numeric?
- *Answer* (cli19−stat6250): The variable assumes null values for observations that are not completely numeric.
- Question (dfei−stat6250): How many types of variable in the data set?



[Course Textbook Chapter 1, Problem 4]
- Question (lceballos-stat6250): What if you input data that is the wrong variable data type? 
- Question (pcheng14−stat6250): What is the meaning of character for the type of the variable?
- Answer (pcheng14−stat6250): It shows the word type as the variable.
- Question (lsun20-stat6250): If the missing value is showing like a blank, does the answer still be numeric?
- *Question* (aacharya4−stat6250): In SAS, how is missing value represented by numeric variable?
- *Answer* (aacharya4−stat6250): In SAS, a dot (.) represents a missing value in numeric variable.
- Question (ljiang11−stat6250): How to omit the dot when there is missing data?
- Answer (ljiang11−stat6250): One can set data option to display "missing".
- *Question* (cnguyen77-stat6250): How missing values for numeric variable are displayed by SAS?
- *Answer* (cnguyen77-stat6250): For numeric variables, a period represents a missing value.
- Question (xyin6-stat6250): How to represent missing value in character and numeric variable type?
- Answer (xyin6-stat6250): A blank represents missing value in character variable, and a period represents missing value in numeric variable.
- *Question* (jcanfield3-stat6250): Are blank values just ignored in analysis, or do they contribute some value?
- *Question* (aamiri2-stat6250): What is the importance of understanding the attributes of the variables you use in your data?
- *Answer* (aamiri2-stat6250): It is very important to understand your data type for many reasons. One of the main reasons are converging data sets that contain the same-named variables in which the variable type must be the same. For example, you cannot combine a character and number variable because they are different.
- Question (who7-stat6250): What are the other types of data in SAS?
- Question(tchan49-stat6250):Can numeric variable be character variable?
- Question (ttruong59-stat6250): Assuming a missing value is indicated by a blank rather than a period, is the variable still considered as a numberic variable?
- Question (nshrivastava2-stat6250): What type of Varaible which is right justifies?
- *Question* (shatcher4-stat6250): Why is a blank representative of a missing value for character variables, while a period is representative of a missing value for numeric variables?
- *Question* (akrishnamurthy-stat6250):how are the missing values specified for character and numeric variables ?
- *Answer* (akrishnamurthy-stat6250):Missing values for character variables are assigned with spaces and numeric variables are assigned with period
- *Question* (ldai4-stat6250): what is variable’s type?
- *Answer*  (ldai4-stat6250): A variable’s type is either character or numeric. Character variable can contain any values; and numeric variables can contain only numeric values (the numerals 0-9,+,-., and E for scientific notation). A variable’s type also determines how missing values for a variable are displayed. For character variables,  a blank represents a missing value; and for numeric variables, a period represents a missing value.
- Question (ldeng11−stat6250): How a variable will display if it is a missing value> 
- *Question* (jbettonville-stat6250): Since numerical values are always represented by floating point numbers in SAS, is there any danger of strange behavior when running calculations (i.e. 1.1 + 1.1 + 1.1 + 4 = 7.300000000000001 instead of 7.3)? If so, is there any method of accounting for this issue?
- *Question* (cli19−stat6250): Why are missing values different for character (' ') and numeric (.) variables?
- Question (dfei−stat6250): what does numberic character mean?
- Answer (dfei−stat6250): A numeric character reference (NCR) is a common markup construct used in SGML and SGML-derived markup languages such as HTML and XML. It consists of a short sequence of characters that, in turn, represents a single character.



[Course Textbook Chapter 1, Problem 5]
- Question (lceballos-stat6250): Why can't variables start with a number?
- Question (pcheng14−stat6250): Is the following the variable is invalid?   "$_Willie_$"
- Answer (pcheng14−stat6250) : Yes, the variable is invaild.
- Question (lsun20-stat6250): Is there any specific rule in SAS about making name?
- Answer (lsun20-stat6250):yes, there are some rule which is show in the website (https://v8doc.sas.com/sashtml/lgref/z1031056.htm) in making name in SAS.
- *Question* (aacharya4−stat6250): If SAS, what is the criteria for a valid variable name?
- *Answer* (aacharya4−stat6250): In SAS, for a variable name to valid, the following rules should be followed:
1. The length of the variable name should not exceed 32 characters.
2. Variable name has to start with A-Z(both upper and lower cases permitted) or an Underscore followed by any combination of letters, numbers or Underscore.
- Question (ljiang11−stat6250): What are the rules of naming a variable?
- *Question* (cnguyen77-stat6250): What are the rules to set a variable name?
- Question (xyin6-stat6250): What are the constrains to make a valid variable name?
- *Question* (jcanfield3-stat6250): Out of all the symbols, why is only the underscore allowed in a variable name?
- *Question* (aamiri2-stat6250): What are some of the data rules associated with SAS variable names?
- *Answer* (aamiri2-stat6250): A few of the rules for SAS variable names are that is can only be 1 to 32 characters long. It must begin with a letter between A-Z or an underscore and can continue afterwards with any combination of letters, numbers, or underscores.
- Question (who7-stat6250): Why is underscore the only special character that can be used as a part of a variable name?
- Answer (who7-stat6250): Cannot be 100% sure of all special character, but coding don't usually start with a special character because most speial character usually refers to a specific function/syntax within the code. As a result, to avoid confusion, they made it a rule to not make variable name with special character.
- Question(tchan49-stat6250):Can variable names contain only numbers? 
- Answer(tchan49-stat6250):No, it has to begin with a letter or underscore.
- Question (ttruong59-stat6250): Are variable names case-sensitive? And what are their naming convention?
- Asnwer (ttruong59-stat6250): No, variable name are not case-sensitive. For example, variable STAT6250 and Stat6250 are considered the same. Variable must follow the naming convention as follows: (1) can't exceed 32 characters long, (2) must begin with a letter or an underscore, and (3) can continue with any combination of numbers, letters, and underscores. 
- Question (nshrivastava2-stat6250): What is the naming convention for varibale name?
- *Question* (shatcher4-stat6250):What is the difference between a character and numeric variable type?
- *Answer* (shatcher4-stat6250): A character variable can contain any value, while a numeric variable can contain only numeric values.
- *Question* (akrishnamurthy-stat6250):How should SAS variable name be defined?
- *Question* (ldai4-stat6250): What is the rules of variable name in SAS?
- *Answer*  (ldai4-stat6250): Variable names follow the same rules, which can be 1 to 32 characters long, must begins with a letter(A-Z, either uppercase or lowercase) or an underscore, and can continue with any combination of numerals, letters, or underscores.
- Question (ldeng11−stat6250): What is the naming rule for the variable in SAS?
- *Question* (jbettonville-stat6250): Is there a preferred naming convention for SAS variables that conforms to the limitations on the names of variables? (i.e. Is there a preference between ListOfObjects, list_of_objects, listOfObjects, or another format?)
- *Answer* (jbettonville-stat6250): A reading at the SAS Community website (http://www.sascommunity.org/wiki/Style_guide_for_writing_and_polishing_programs) has suggestions for formatting conventions, such as generally using lowercase (with a few exceptions). However, the style guide contradicts the way the macro name and the instances of *proc* are formatted in this week's SAS recipes, so it is possible that these suggestions are somewhat flexible.
- *Question* (cli19−stat6250): Are variable names case-sensitive?
- *Answer* (cli19−stat6250): No, SAS is not a case-sensitive program (e.g. variable Policy, POLICY, PolIcY, etc. are the same).
- Question (dfei−stat6250): what are the variable name rules?
- Answer (dfei−stat6250): Variable name rules are as follows: SAS variable names can be up to 32 characters in length. The first character must begin with an English letter or an underscore. Subsequent characters can be English letters, numeric digits, or underscores.
  


[Course Textbook Chapter 1, Problem 8]
- Question (lceballos-stat6250): What is the maximum lenght for a floating number in SAS?
- Question (pcheng14−stat6250): What is the meaning of the the numeric variable Balance?
- Question (lsun20-stat6250): Does the numeric variable which are stored in 8 bytes have a range? if yes, what is it?
- Answer (lsun20-stat6250): It depends on different variable type. (e.g. the range of the Long integer is -2,147,483,647 to 2,147,483,647)
- *Question* (aacharya4−stat6250): In SAS, what are the properties of numeric variable?
- *Answer* (aacharya4−stat6250): The properties of numeric variable in SAS are :
1. Numeric variables can be upto 8 bytes(the number of bytes used to store character variable)long.
2. Numeric variable can contain only numeric value (0 to 9,+,-,., E for scientific notation).
3. A dot (.) represents a missing value in numeric variable.
- Question (ljiang11−stat6250): How many digits can numeric variable display?
- Answer (ljiang11−stat6250): 16 to 17 digits.
- *Question* (cnguyen77-stat6250): What is the default length of numeric variables in SAS programs?
- Question (xyin6-stat6250): What is the default length for the numeric variable?
- *Question* (jcanfield3-stat6250): Do character variables have a default length?
- *Question* (aamiri2-stat6250): How can you format the maximum width of a number to have a width of 3 including 2 decimals places for the variable Balance?
- Question (who7-stat6250): What are the maximum length in a numeric variable?
- Answer (who7-stat6250): The usual length of a numeric variables is 3-8.
- Question(tchan49-stat6250):What is the default length for numeric values? 
- Question (ttruong59-stat6250): What is the default length for the numberic variable? What format do we need to specify a width of 8 and 4 decimal places.
- Asnwer (ttruong59-stat6250): The default length for the numeric variable is 8 bytes unless a different length is specified. To specify a width of and 4 decimal places, the format is COMMA8.4
- Question (nshrivastava2-stat6250):What is the storage bytes in character variables?
- Answer(nshrivastava2-stat6250): A variable's length (the number of bytes used to store it) is related to its type. Character variables can be up to 32,767 bytes long. In the example below, Name has a length of 20 characters and uses 20 bytes of storage.  
- *Question* (shatcher4-stat6250): Why are numeric values stored as floating-point numbers?
- *Question* (akrishnamurthy-stat6250):What is the length of a numeric variable with 10 digits?
- *Answer* (akrishnamurthy-stat6250):Irrespective of number of digits, numeric variables are always stored as floating point numbers in 8 bytes of storage unless a different length is specified.
- *Question* (ldai4-stat6250): What is the default length for the numeric variable?
- *Answer*  (ldai4-stat6250): The numeric variables have a default length of 8. Numeric values( no matter how many digits they contain) are stored in 8 bytes of storage unless you specify a different length.
- Question (ldeng11−stat6250): What is the defaul length for the numeric variable?
- *Question* (jbettonville-stat6250): What would happen if you were to specify a length for a numerical variable, and then were to encounter an observation that contained a value that is too large to be represented within the specified length?
- *Answer* (jbettonville-stat6250): This may result in a loss of precision without any warning being given, according to the following article which describes what happens in this situation: http://www.pauldickman.com/teaching/sas/length.php
- *Question* (cli19−stat6250): When is it appropriate to change variable length? Does SAS automatically adjust for where observations in a dataset have length greater than 8 bytes?
- Question (dfei−stat6250): In SAS, what is the default length of a numeric variable?
- Answer (dfei−stat6250): In SAS, the default length of a numeric variable is 8 bytes.



[Course Textbook Chapter 2, Problem 3]
- Question (lceballos-stat6250): Does YEARCUTOFF=2000 pick 1918 or 2018 if the date is 1/9/18?
- Question (pcheng14−stat6250): When shoud I use data values in SAS programming?
- Question (lsun20-stat6250): How the "YEARCUTOFF=option" works in SAS?
- Answer (lsun20-stat6250): The YEARCUTOFF= option specifies which 100-year span is used to interpret two-digit year values.
- *Question* (aacharya4−stat6250): What is the default value of YEARCUTOFF option in SAS?
- *Answer* (aacharya4−stat6250): In SAS, the default value of YEARCUTOFF option is 1920.
- Question (ljiang11−stat6250): Why is YEARCUTOFF= option necessary?
- *Question* (cnguyen77-stat6250): How does the YEARCUTOFF= Option Work?
- *Answer* (cnguyen77-stat6250): When a two-digit year value is read, SAS interprets it based on a 100-year span which starts with the YEARCUTOFF= value. The default value of YEARCUTOFF= is 1920. However, you can override the default and change the value of YEARCUTOFF= to the first year of another 100-year span.
- Question (xyin6-stat6250): Does YEARCUTOFF= option also works on 4-digits year values?
- Answer (xyin6-stat6250): No, YEARCUTOFF= option works only on 2-digits year values. As long as you specify an informat with the correct field width for reading the entire date value, the YEARCUTOFF= option doesn't affect date values that have four-digit years.
- *Question* (jcanfield3-stat6250): Is the YEARCUTOFF= option necessary, if your year has four digits?
- *Answer* (jcanfield3-stat6250): No it is not, as it only applies to situations where the year has 2 digits, and thus used to identify which 100 year range the data is coming from.
- *Question* (aamiri2-stat6250): What is the correct method of using the YEARCUTOFF= option with the date of 02march1955? What would be it’s time span given that date?
- Question (who7-stat6250): Instead of a cutoff date, can it be a range?
- Question(tchan49-stat6250): Do you have to specify YEARCUTOFF= option for 4-digit years of the date values? 
- Answer(tchan49-stat6250):No, when the years of date values are 4-digit, the YEARCUTOFF= value can be any value. So YEARCUTOFF= is not needed. 
- Question (ttruong59-stat6250): Are there any differences in term of handling two-digit year and 4-digit year in SAS? If so, what are they?
- Question (nshrivastava2-stat6250):How SAS Files Are Stored ?
- Answer(nshrivastava2-stat6250): Every SAS file is stored in a SAS library, which is a collection of SAS files. A SAS data library is the highest level of organization for information within SAS.
- *Question* (shatcher4-stat6250): Why is the default value of YEARCUTOFF= 1920?
- *Question* (akrishnamurthy-stat6250):How to read from and write to files of different formats in SAS ?
- *Question* (ldai4-stat6250): How four-digit years are handled?
- *Answer*  (ldai4-stat6250): The vale of the YEARCUTOFF=system option affects only two-digit year values. A date value that contains a four-digit year value will be interpreted correctly even if it does not fall within the 100-year span set by the YEARCUTOFF=system option.
- Question (ldeng11−stat6250): How the SAS save date values?
- *Question* (jbettonville-stat6250): In several instances within SAS, it appears that the default format for writing dates is *DATE9.* (e.g. 08JAN2018); is there an historical reason behind the prevalence of this date format in SAS instead of format that could be more easily sorted, such as YYYYMMDD (e.g. 20180108)?
- *Question* (cli19−stat6250): What are the benefits to specifying YEARCUTOFF?
- Question (dfei−stat6250): How to setup data value appropriately?



[Course Textbook Chapter 2, Problem 7]
- Question (lceballos-stat6250): Can you revert back to a previous version of a temporary library?
- Question (pcheng14−stat6250): What is the most common SAS data set shoud I use for?
- Question (lsun20-stat6250): Do we need to coding the SAS library which we need in the program at the first line in the program?
- Answer (lsun20-stat6250): It's better to put the library code at the first of the entire program. Actually, this code just need to be code before you use it.
- *Question* (aacharya4−stat6250): What is the explanation of the SAS code given below :
![code_2](https://user-images.githubusercontent.com/35093776/34758544-cc757cb8-f58b-11e7-8c0f-dcd0b9d8a643.png)
- *Answer* (aacharya4−stat6250): The first line of the code creates a new permanent SAS library called "sales". 
The LIBNAME statement defines libref sales and gives SAS the physical location of the SAS library "sales".
The second line of the code creates a new dataset called "totalsales". This dataset is permanently stored in the SAS library "sales".
- Question (ljiang11−stat6250): What is aproc in choice C? Is that a typo?
- *Question* (cnguyen77-stat6250): What are the attributes of assigning a libref name?
- Question (xyin6-stat6250): What are the specification for the LIBNAME statement for files in other formats?
- Answer (xyin6-stat6250): libref is 1 to 8 characters long, begins with a letter or underscore, and contains only letters, numbers. or underscores.
- *Question* (jcanfield3-stat6250): Can a file be referenced within a proc statement?
- *Question* (aamiri2-stat6250): What is the purpose of referencing a SAS file if it is already in the library?
- Question (who7-stat6250): Can we change the name of data set in the code?
- Question(tchan49-stat6250):To define libraries, what function statement do you need to use? AND what are the requirements for setting up a Librefs?
- Answer(tchan49-stat6250):LIBNAME libref 'SAS-data-library';. 1-8 characters long, begin with letter or underscore, contain only letters numbers and underscores 
- Question (ttruong59-stat6250): Why does the length of a libref only allow 8 characters?
- Question (nshrivastava2-stat6250): How the Leap years works in all SAS version?
- Answer(nshrivastava2-stat6250): Leap years, century, and fourth-century adjustments are made automatically.Leap seconds are ignored, and SAS does not adjust for daylight saving time.
- *Question* (shatcher4-stat6250): How would you go about referencing a permanent SAS file?
- *Question* (akrishnamurthy-stat6250):What is the function of YEARCUTOFF proc option?
- *Question* (ldai4-stat6250): How can we reference SAS file in SAS libraries?
- Question (ldeng11−stat6250): How many ways you can reference a SAS data set?
- *Question* (jbettonville-stat6250): What is the reasoning behind limiting the length of a libref to only eight characters?
- *Question* (cli19−stat6250): Is it possible to reference multiple SAS data sets in a single data step? If so, how?
- Question (dfei−stat6250): How to store dataset into SAS libraries?



[Course Textbook Chapter 2, Problem 8]
- Question (lceballos-stat6250): Can SAS use a date range that is more than 100 years old if you're using YEARCUTOFF?
- uestion (pcheng14−stat6250): What is the meaning of YEARCUTOFF?
- Question (lsun20-stat6250): Is there any other code have the same effect as the "YEARCUTOFF"?
- *Question* (aacharya4−stat6250): What is the purpose of YEARCUTOFF option in programming statements in SAS?
- *Answer* (aacharya4−stat6250): In SAS programming, when we use two-digit year values, the YEARCUTOFF option gives the 100 year span for interpreting the two-digit year values.
- Question (ljiang11−stat6250): Is YEARCUTOFF= in global environment?
- *Question* (cnguyen77-stat6250): What is the default value of YEARCUTOFF= Option?
- Question (xyin6-stat6250): What is the default value of YEARCUTOFF= option and what's its range?
- *Question* (jcanfield3-stat6250): Why is 1582 A.D. the earliest that the YEARCUTOFF= option can take?
- *Question* (aamiri2-stat6250): What is the reason for using YEARCUTOFF= option and what are the benefits?
- *Answer* (aamiri2-stat6250): This option helps specify which 100-year span is used to interpret two-digit year values. This usually needs to be specified such as YEARCUTOFF=1940 so the 100 year span dates would be 1940 – 2039
- Question (who7-stat6250): Is there a way to expand the range of time period for more than 100 years?
- Question(tchan49-stat6250):When you set up a YEARCUTOFF= and count a time span(100years), does the year you intend to start count as the first year of the span? 
- Question (ttruong59-stat6250): Why is the default value of YEARCUTOFF= 1920? Is there any benefit of using 1920, instead of using different year as a default value? If so, what is it?
- Question (nshrivastava2-stat6250): What is the general format of  LIBNAME statement ?
- *Question* (shatcher4-stat6250): Why are two-digit year values treated differently than a four-digit year value in the YEARCUTOFF option?
- *Question* (akrishnamurthy-stat6250):How to access files stored in SAS library ? Can the files be accessed across SAS sessions?
- *Question* (ldai4-stat6250): what difference are two-digit year and four-digit year?
- Question (ldeng11−stat6250): What is the YEARCUTOFF option using to?
- *Question* (jbettonville-stat6250): As we approach the year 2020, has there been any discussion within the SAS community about when it would be appropriate to update the default YEARCUTOFF= option from 1920 to another year?
- *Question* (cli19−stat6250): Does the YEARCUTOFF option have additional options to incease the time span to over 100 years?
- Question (dfei−stat6250): How to interpret two-digit year values?



[Course Textbook Chapter 2, Problem 9]
- Question (lceballos-stat6250): If your SAS or computer crashes, is there a way to recover a LIBNAME?
- Question (pcheng14−stat6250): When should I use special SAS windows?
- Question (lsun20-stat6250): Is it possible to direct the Library to WORK Data library, using LIBNAME statement (e.g. Libname save SAS.WORK;)?
- *Question* (aacharya4−stat6250): What happens after deletion of a libref of a library in SAS?
- *Answer* (aacharya4−stat6250): Afrer deletion of a libref of a library, SAS will not be able to access the contents of the library, although the contents of the library are permanently stored in the operating system.
- Question (ljiang11−stat6250): How to delete/change a libref?
- Answer (ljiang11−stat6250): One can assign a different path to the same libref to change it. And can use libref clear
command to delete the libref.
- *Question* (cnguyen77-stat6250): Can librefs last from one SAS session to another?
- Question (xyin6-stat6250): Is LIBNAME statement required each time for every SAS session?
- *Question* (jcanfield3-stat6250): Why do librefs get deleted at the end of a SAS session? 
- *Question* (aamiri2-stat6250): The textbook explains that once you end your SAS session then SAS no longer has access to the assigned libref files in the library. Is there any other way of accessing the contents of the libref file again?
- Question (who7-stat6250): Is there any restriction to LIBNAME like variable names?
- Question(tchan49-stat6250):When does librefs stop remaining effect in the current SAS session? 
- Question (ttruong59-stat6250): What is a significant reason that LIBNAME statement can only assign the libref for the current SAS session only?
- Question (nshrivastava2-stat6250): What is the naming convesntion of Library Name?
- *Question* (shatcher4-stat6250): What is the purpose of the LIBNAME statement?
- *Answer* (shatcher4-stat6250): LIBNAME is a global statement that is used to define libraries with any SAS program.
- *Question* (akrishnamurthy-stat6250):What is the syntax of libname statement ? Should the engine and library be specified for all files to be accessed?
- *Question* (ldai4-stat6250): what is LIBNAME statement?
- *Answer*  (ldai4-stat6250): The LIBNAME statement is global, which associates or disassociates a SAS library with a libref (a shortcut name), clears one or all librefs, lists the characteristics of a SAS library, concatenates SAS libraries, or concatenates SAS catalogs. 
- Question (ldeng11−stat6250): What happen to the SAS library if you delete a libref in your SAS code?
- Answer (ldeng11−stat6250): You will lost the access to the files in the library, but the contents of the library are still exist in your operation sysetm.
- *Question* (jbettonville-stat6250): In some programming environments, it is possible to save the current session or workspace, including all variables and structures that are currently in use, so that work can be resumed at a later time and/or in another location with the same conditions; is there a way to do this within SAS, and if so, can it be automated?
- *Question* (cli19−stat6250): How can we view the working directory or file path we would like our librefs to point to?
- Question (dfei−stat6250): Can librefs last from more than one SAS session to another?



[basic_recipe_for_loading_data_from_remote_Excel_file Week 2 Recipe]
- Question (lceballos-stat6250): "Is the filename tempfile clear;" required for the program to run correctly?
- Answer (lceballos-stat6250): No, the program will run without it. Clearing up the tempfile allots more space.
- Question (pcheng14−stat6250): May I edit the Excel file which import form the remote Excel file?
- Question (lsun20-stat6250): Can SAS load data from other sotfware except EXCEL? If can, is there any different in coding to do it?
- *Question* (aacharya4−stat6250): What is the code to adjust the size of editor window in SAS?
- Question (ljiang11−stat6250): How to set the 80-character banner with SAS studio? And how to set code tab and log tab side by side?
- *Question* (cnguyen77-stat6250): What is the syntax to create a file name in SAS?
- Question (xyin6-stat6250): Is there a size limit for loading data from remote Excel file in a temporary location? (As many of the Excel files are very large)
- *Question* (jcanfield3-stat6250): Why can't the dataset be directly transformed into a SAS dataset within the proc http step?
- *Question* (aamiri2-stat6250): How can we transform an Excel file into a URL using Github? How long does this process take?
- Question (who7-stat6250): When loading data from remote excel file, can we manually assign and rename the library folder that the file will be stored at?
- Question(tchan49-stat6250):What is the purpose of the REPLACE option? Do you have to have that statment when you import dataset? 
- Question (ttruong59-stat6250): Is there a way to revise codes to support some other data formats? 
- Question (nshrivastava2-stat6250): How to import file from FTP or FTPs ? Does SAS has an ability to do that?
- Answer(nshrivastava2-stat6250): Yes, SAS has an ability to do the same. We need specify the link to the FTP with directory, user, Host, Passwd in order to link to the FTP. 
- *Question* (shatcher4-stat6250): What are the benefits of loading Excel data sets to a web server, such as GitHub, first? 
- *Question* (akrishnamurthy-stat6250):How to access a file from a remote server in SAS ? How to import raw data as a excel file in SAS ?
- *Question* (ldai4-stat6250): Can the raw data's format be displayed in SAS library?
- Question (ldeng11−stat6250): Can the recipe code read the excel sheet from other sheets other than sheet 1 (the left most sheet)?
- Answer (ldeng11−stat6250): Yes, you need to add the sheet statement option.
- *Question* (jbettonville-stat6250): In other languages, certain functions can only be called after a specific library has been loaded. It appears that SAS can natively handle http requests and parsing Excel files, but are there other file formats or methods of reading in data sets that require additional preparation within SAS first?
- *Answer* (jbettonville-stat6250): Regarding SAS's ability to read other file formats, this is discussed in the SAS Certification Prep Guide in chapter 2; page 50 has a listing of the various file formats that are supported by engines within SAS.
- *Question* (cli19−stat6250): How does SAS know how to format data imported from external files?
- Question (dfei−stat6250): What will happen if I forget to clear tempfile? Will it disappear after I restart my computer?



[bonus_advanced_recipe_for_loading_data_from_remote_Excel_file Week 2 Recipe]
- Question (lceballos-stat6250): When using a macro, what do the names in paranthesis mean?
- Answer (lceballos-stat6250): The names in the parenthesis will define the variables that will be uses later when you call the macro. You input what they are when you use the macro.
- Question (pcheng14−stat6250): Except I get the http or http// address can import and remote the Excel file, any way I can load the data from remote Excel file?
- Question (lsun20-stat6250): what are the disadvantages of using a macro?
- *Question* (aacharya4−stat6250): What does the following " %<variable_name>." mean in SAS?
- *Answer* (aacharya4−stat6250): In SAS, we reference a variable in this way. It starts with the delimiter (%) and ends with the delimiter (.). variable_name signifies the name of the variable that is referenced.
- Question (ljiang11−stat6250): Are we supposed to learn Macro in this class? It looks intimidating at the beginning since I don't have too much background of SAS.
- *Question* (cnguyen77-stat6250): What does SAS interpret character “&” and “%”?
- Question (xyin6-stat6250): Why we have to put "%" percent sign before the if/then/else statement? 
- *Question* (jcanfield3-stat6250): What are macros useful for?
- *Answer* (jcanfield3-stat6250): Macros are useful to simplify code, condensing repeated lines into the one macro execution.
- *Question* (aamiri2-stat6250):  Which character is used for the Macro command? How many different Macro commands are there?
- Question (who7-stat6250): Can we consider the macro command similar to a function in Python?
- Question(tchan49-stat6250):What is the symbol macro? What is the purpose to create a macro?
- Question (ttruong59-stat6250): Why do we use macro variable in SAS?
- Question (nshrivastava2-stat6250):Why we use SAS Macro? How Macro is differ from the standard SAS code.
- Answer(nshrivastava2-stat6250):Though macro code takes longer to write and debug than standard SAS code but if write similar code over and over again, then macros may make your job easier. This piece of solution I found from the web. PFD file of "SAS Macro Programming for Beginners".
- *Question* (shatcher4-stat6250): What is the purpose of a macro variable?
- *Question* (akrishnamurthy-stat6250):How to define macros in SAS ? Should the macros be called with the same set of parameters defined in macro definition?
- *Question* (ldai4-stat6250): For a specific SAS data set, can I use PROC DATASETS to display it? 
- Question (ldeng11−stat6250): How to revise the code to support other data formats?
- *Question* (jbettonville-stat6250): Can macros be saved into external packages that can then be loaded and called without including the original SAS recipe in the text of the workspace?
- *Question* (cli19−stat6250): Why do only some macro functions in SAS require a "%" to invoke a function? And when do built-in SAS functions need to be invoked with %sysfunc()?
- Question (dfei−stat6250): There are two characters,"ampersand","percent" signs introducing in the video, anyother common characters should I know in SAS?


