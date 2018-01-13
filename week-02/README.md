
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



[Course Textbook Chapter 1, Problem 2]
- Question (lceballos-stat6250): Since SAS runs a program everytime it reads PROC or DATA, is the run command necessary for running SAS programs?
- Question (pcheng14−stat6250): What is the lowest program steps are executed in the program when program is processed?
- Answer:one
- Question (lsun20-stat6250): Is there any other statements can make the SAS stop reading statement and executes the step in the program? 



[Course Textbook Chapter 1, Problem 3]
- Question (lceballos-stat6250): For attributes with a data type, is it possible to change the variable data type after it was assigned?
- Answer (lceballos-stat6250): Yes, using an input function.
- Question (pcheng14−stat6250): What is the meaning of numberic for the type of variable?
- Answer (pcheng14−stat6250): It shows the number type as the variable.
- Question (lsun20-stat6250): How many type of variables in the SAS? and what are them?



[Course Textbook Chapter 1, Problem 4]
- Question (lceballos-stat6250): What if you input data that is the wrong variable data type? 
- Question (pcheng14−stat6250): What is the meaning of character for the type of the variable?
- Answer (pcheng14−stat6250): It shows the word type as the variable.
- Question (lsun20-stat6250): If the missing value is showing like a blank, does the answer still be numeric?



[Course Textbook Chapter 1, Problem 5]
- Question (lceballos-stat6250): Why can't variables start with a number?
- Question (pcheng14−stat6250): Is the following the variable is invalid?   "$_Willie_$"
- Answer (pcheng14−stat6250) : Yes, the variable is invaild.
- Question (lsun20-stat6250): Is there any specific rule in SAS about making name?
- Answer (lsun20-stat6250):yes, there are some rule which is show in the website (https://v8doc.sas.com/sashtml/lgref/z1031056.htm) in making name in SAS.



[Course Textbook Chapter 1, Problem 8]
- Question (lceballos-stat6250): What is the maximum lenght for a floating number in SAS?
- Question (pcheng14−stat6250): What is the meaning of the the numeric variable Balance?
- Question (lsun20-stat6250): Does the numeric variable which are stored in 8 bytes have a range? if yes, what is it?
- Answer (lsun20-stat6250): It depends on different variable type. (e.g. the range of the Long integer is -2,147,483,647 to 2,147,483,647)



[Course Textbook Chapter 2, Problem 3]
- Question (lceballos-stat6250): Does YEARCUTOFF=2000 pick 1918 or 2018 if the date is 1/9/18?
- Question (pcheng14−stat6250): When shoud I use data values in SAS programming?
- Question (lsun20-stat6250): How the "YEARCUTOFF=option" works in SAS?
- Answer (lsun20-stat6250): The YEARCUTOFF= option specifies which 100-year span is used to interpret two-digit year values.



[Course Textbook Chapter 2, Problem 7]
- Question (lceballos-stat6250): Can you revert back to a previous version of a temporary library?
- Question (pcheng14−stat6250): What is the most common SAS data set shoud I use for?
- Question (lsun20-stat6250): Do we need to coding the SAS library which we need in the program at the first line in the program?
- Answer (lsun20-stat6250): It's better to put the library code at the first of the entire program. Actually, this code just need to be code before you use it.



[Course Textbook Chapter 2, Problem 8]
- Question (lceballos-stat6250): Can SAS use a date range that is more than 100 years old if you're using YEARCUTOFF?
- uestion (pcheng14−stat6250): What is the meaning of YEARCUTOFF?
- Question (lsun20-stat6250): Is there any other code have the same effect as the "YEARCUTOFF"?



[Course Textbook Chapter 2, Problem 9]
- Question (lceballos-stat6250): If your SAS or computer crashes, is there a way to recover a LIBNAME?
- Question (pcheng14−stat6250): When should I use special SAS windows?
- Question (lsun20-stat6250): Is it possible to direct the Library to WORK Data library, using LIBNAME statement (e.g. Libname save SAS.WORK;)?



[basic_recipe_for_loading_data_from_remote_Excel_file Week 2 Recipe]
- Question (lceballos-stat6250): "Is the filename tempfile clear;" required for the program to run correctly?
- Answer (lceballos-stat6250): No, the program will run without it. Clearing up the tempfile allots more space.
- Question (pcheng14−stat6250): May I edit the Excel file which import form the remote Excel file?
- Question (lsun20-stat6250): Can SAS load data from other sotfware except EXCEL? If can, is there any different in coding to do it?



[bonus_advanced_recipe_for_loading_data_from_remote_Excel_file Week 2 Recipe]
- Question (lceballos-stat6250): When using a macro, what do the names in paranthesis mean?
- Answer (lceballos-stat6250): The names in the parenthesis will define the variables that will be uses later when you call the macro. You input what they are when you use the macro.
- Question (pcheng14−stat6250): Except I get the http or http// address can import and remote the Excel file, any way I can load the data from remote Excel file?
- Question (lsun20-stat6250): what are the disadvantages of using a macro?


