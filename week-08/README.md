## Week 8 Quiz Questions and Answers

In order to prepare your Week 8 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-8" in your fork of this repo. Then, after all edits have been made/committed, your Week 8 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-8 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 13, Problem 1]
- Question(tchan49-stat6250):Is mean(of var1 to var4) a vaild function to calculate the average of var1, var2, var3 and var4? 
- Answer(tchan49-stat6250):No, it should be mean(of var1-var4). 
- Question(pcheng14-stat6250):When specifying a variable list, do we have to be sure to precede the list with the word OF?
- Answer(pcheng14-stat6250):Yes, we do.
- Question(dfei-stat6250): What is coding format to calculates the average of the variables a, b, c?
- Answer(dfei-stat6250): It is mean(of a-b).
- Question (aguenane−stat6250): Do we really need to word OF inside the mean function?
- Answer (aguenane−stat6250): If you omit the word OF, the function argument might not be interpreted as expect
- *Question* (asharda-stat6250): What does a mean function do?
- *Answer* (asharda-stat6250): It calculates the mean of the variables that are listed as arguments.
- *Question* (aacharya4−stat6250): How can we specify a range of values as a function argument in SAS?
- *Answer* (aacharya4−stat6250): In order to specify a range of values as a function argument in SAS, we need to precede the list of variables with keyword 'OF'. Eg: sum(of va1-var10)
- *Question* (aamiri2-stat6250): When calculating averages of multiple variables, what happens to the function argument when you omit the word OF?
- *Answer* (aamiri2-stat6250): The word OF is used when specifying function arguments with a variable list or an array. If the word OF is omitted then the function will be interpreted as a subtraction formulation rather than an average of all variables. Consequently, this gives an incorrect output.
- Question (tbishaw-stat6250): What steps must be taken before using a SAS function?  
- Answer (tbishaw-stat6250): We must specify the function name followed by the function argument (enclosed in parentheses). 
- *Question* (cli19−stat6250): Can variables be used as a list in functions in a PROC SQL step?
- *Question* (jbettonville-stat6250): Do the variables included in the list that is created by the minus sign have to be in order within the data set? (i.e. if variables are arranged in a data set ordered as var3, var1, var2, var4, would the statement that generated the mean of all four variables be mean(of var3-var4)?)



[Course Textbook Chapter 13, Problem 2]
- Question(tchan49-stat6250):Under what situations, SAS automatically converts characters variables to numeric values? 
- Question(pcheng14-stat6250):When will SAS automatically converts the character values of PayRate to numeric values?
- Answer(pcheng14-stat6250):When this DATA step is executed.
- Question(dfei-stat6250): What will happen in SAS when a character variable calculate with a numeric one?
- Answer(dfei-stat6250): Sas will convert character to numeric to meet the calculation if possible.
- Question (aguenane-stat6250): What is the target variables?
- Answer (aguenane-stat6250): A target variable is the variable to whic the result of a function is assigned.
- *Question* (asharda-stat6250): What happens when data is automatically converted?
- *Answer* (asharda-stat6250): Whenever data is automatically converted ,a message is written to the SAS log stating that the conversion has occured.
- *Question* (aacharya4−stat6250): What function is used to convert numeric variable to character variable? 
- *Answer* (aacharya4−stat6250): In SAS, numeric variable is converted to numeric variable using PUT function. 
- *Question* (aamiri2-stat6250): What is the difference between the INPUT and PUT function? In which cases should this functions be used?
- *Answer* (aamiri2-stat6250): The INPUT function converts character data into numeric values whereas the PUT function works oppositely and converts numeric data values to character values. Usually these functions are used when one of the variables are needed for calculation.
- Question (tbishaw-stat6250): When can we specify a SAS function? What are the requirements? 
- Answer (tbishaw-stat6250): We can specify a SAS function anywhere that you would use a SAS expression, as long as the function is part of a SAS statement. 
- *Question* (cli19−stat6250): How does SAS convert character variables to numeric values so that a calculation can be completed?
- *Answer* (cli19−stat6250): A temporary numeric value for each character value is created to complete the calculation. However, the character values of the variable are not replaced.
- *Question* (jbettonville-stat6250): Is it possible to permanently convert a character value to a numeric value in the same step as completing a mathematical evaluation with the original character value?



[Course Textbook Chapter 13, Problem 3]
- Question(tchan49-stat6250):When you want to explicitly covert character to numeric, do you use PUT statement? 
- Answer(tchan49-stat6250):No, you would use INPUT(souce, informat)
- Question(pcheng14-stat6250):When should we use the INPUT function?
- Answer(pcheng14-stat6250):When we explicitly convert character values to numeric values.
- Question(dfei-stat6250): What is "put" statement mean in SAS programming? How does it work?
- Question (aguenane−stat6250): Which fuction should we use to convert character value to numeric value?
- Answer (aguenane−stat6250): we should use INPUT function.
- *Question* (asharda-stat6250): What is the use of  INPUT function?.
- *Answer* (asharda-stat6250): INPUT function is used to convert character data values to numeric values. 
- *Question* (aacharya4−stat6250): What is the use of format in PUT and INPUT function?
- *Answer* (aacharya4−stat6250): The use of format signifies what format type is to be used on the original variable type. For eg: In case of INPUT function to convert a character value to numeric, the format must be a character format.
- *Question* (aamiri2-stat6250): When converting character values to numeric values, how are commas and decimals differentiated in the INPUT function.
- Question (tbishaw-stat6250): When does Automatic character-to-numberic conversion occur?
- *Question* (cli19−stat6250): SAS generates a NOTE in the log when characters are converted to numeric values in order to complete calculations. Does SAS display a message in the log when character values are converted to numeric in an INPUT function?
- *Answer* (cli19−stat6250): No, no conversion messages appear in the SAS log when the INPUT function is used.
- *Question* (jbettonville-stat6250): When converting character values to numeric values with INPUT, what is the result if the character values contain numeric data that does not consistently conform to a standard informat?



[Course Textbook Chapter 13, Problem 4]
- Question(tchan49-stat6250):When you want to explicitly covert numeric to character, do you use INPUT statement? 
- Question(pcheng14-stat6250):When should we use the PUT function?
- Question(dfei-stat6250): What does SiteNum value mean?
- Answer(dfei-stat6250): It is a numeric character shows the location in computers.
- Question (aguenane−stat6250): What is the correct format for PUT function?
- *Question* (asharda-stat6250): Which function do you use to convert numeric values to character values?
- *Answer* (asharda-stat6250): PUT function is used to convert numeric values to character values. 
- *Question* (aacharya4−stat6250): What function is used to convert character variable to numeric variable? 
- *Answer* (aacharya4−stat6250): Character variable is converted to numeric variable using INPUT function.
- *Question* (aamiri2-stat6250): What are some typical errors that can occur with a PUT function?
- Question (tbishaw-stat6250): What function can we use to convert character data values to numeric values?
- *Question* (cli19−stat6250): How can you determine the format of variables?
- *Answer* (cli19−stat6250): One approach may involve using PROC CONTENTS to see the format of variables in a data set.
- *Question* (jbettonville-stat6250): Is it possible and/or useful to use regular expressions to do more complex conversions between formats?



[Course Textbook Chapter 13, Problem 5]
- Question(tchan49-stat6250):Do MDY function accept two-digit values for the year?
- Answer(tchan49-stat6250):Yes, but SAS interprets two-digit values according to the 100-year span that is set by the YEARCUTOFF=. 
- Question(pcheng14-stat6250):What is the meaning of MDY function?
- Question(dfei-stat6250): What is DMY statement when I want to know the day after 1000 days after special day?
- Question (aguenane−stat6250): how to write date in correct order in MDY function?
- *Question* (asharda-stat6250): What does a year function return?
- *Answer* (asharda-stat6250): A year function returns a four-digit numeric values that represents the year.
- *Question* (aacharya4−stat6250): What is the default value of the YEARCUTTOFF system option in SAS?
- *Answer* (aacharya4−stat6250): The default value of the YEARCUTTOFF system option in SAS is 1920.
- *Question* (aamiri2-stat6250): When using the MDY function, what is the general format for month, date, and year? What is a typical error that can occur with this function?
- *Answer* (aamiri2-stat6250): Normally, month is any number from 1-12, day is any number from 1-31, and year is four or two digits. An error that typically occurs is with the formatting the year. It is recommended to use four digits because this will minimize error. MDY function accepts two digit year values but it is based on the 100-year span from YEARCUTOFF=, so it is likely you will get an year that is not desired.
- Question (tbishaw-stat6250): What happens if you skip the INOUT function or the PUT function when converting data?
- Answer (tbishaw-stat6250): SAS will detect the mismatched variables and will try an automatic character-to-numeric or numeric-to-character conversion.
- *Question* (cli19−stat6250): What is the benefit to using the MDY(MM,DD,YYYY) to set the date rather than explicitly stating it with 'DDMONYYY'dt?
- *Question* (jbettonville-stat6250): Under what circumstances might we want to alter the YEARCUTOFF= value when starting a SAS session?



[Course Textbook Chapter 13, Problem 6]
- Question(tchan49-stat6250):When SCAN is used, do you hava to list the delimiters?
- Question(pcheng14-stat6250):When and why should we use the SCAN function?
- Question(dfei-stat6250): What is the difference between State=scan and State=substr statements?
- Question (aguenane−stat6250): When can we use the SCAN function?
- *Question* (asharda-stat6250): What is the use of SCAN function?
- *Question* (aacharya4−stat6250): What is the use of SCAN function in SAS?
- *Answer* (aacharya4−stat6250): The SCAN function returns the nth word from a character string.
- *Question* (aamiri2-stat6250): What function can be used to separate and store character values into a new variable?
- Question (tbishaw-stat6250): Can you display SAS date values in a variety of forms? and how can this be accomplished?
- Answer (tbishaw-stat6250): You can display SAS date values in a variety of forms by associating a SAS format with the values.
- *Question* (cli19−stat6250): How does the SCAN function work if a string contains multiple commas, or delimiters?
- *Question* (jbettonville-stat6250): When might the SUBSTR function be used instead of the SCAN function when parsing character values?
- *Answer* (jbettonville-stat6250): SUBSTR returns a value of a specified length at a specified position within a string. When a value within a data set is consistently structured, SUBSTR can be used to extract different parts of a specified variable.



[Course Textbook Chapter 13, Problem 7]
- Question(tchan49-stat6250):What happens if you omitt n in SUBSTR function?
- Answer(tchan49-stat6250):All remaining characters are inclued in the substring.
- Question(pcheng14-stat6250):What is the SUBSTR function?
- Question(dfei-stat6250): How to assign MDY character to a new variable?
- Question (aguenane-stat6250): What is the difference between SCAN and SUBSTR?
- *Question* (asharda-stat6250): What is the use of SUBSTR function?.
- *Question* (aacharya4−stat6250): What is the best option to extract a character value when its position is known in a character string?
- *Answer* (aacharya4−stat6250): SUBSTR is the best option to extract a character value when its position is known in a character string.
- *Question* (aamiri2-stat6250): What is the difference between SCAN, SUBSTR, and TRIM functions? Do these functions change the data permanently?
- Question (tbishaw-stat6250): Which SAS function do you use to return the integer portion of a numeric value?
- *Question* (cli19−stat6250): The SUBSTR function counts the index from left to right. Is it possible to start the count from right to left to capture the last x values in a string?
- *Question* (jbettonville-stat6250): What happens if the length of the output substring is not specified when using SUBSTR?
- *Answer* (jbettonville-stat6250): If the third argument is not included in the SUBSTR function, the resulting substring contains all characters from the original string starting from the specified index.



[Course Textbook Chapter 13, Problem 10]
- Question(tchan49-stat6250):What is the benefit of FIND statement over INDEX statement?
- Question(pcheng14-stat6250):Besides using the INDEX function in a subsetting IF statement, when can we use it?
- Question(dfei-stat6250): How to create a subset of the data in which the values of Finish contain the string? 
- Question (aguenane−stat6250): What is the default order when use INDEX function to search values?
- *Question* (asharda-stat6250): What happens when  SUBSTR function is placed on the right side of an assignment statement?.
- *Question* (aacharya4−stat6250): What is the use of INDEX function in SAS?
- *Answer* (aacharya4−stat6250): The INDEX function searches for the chaarcter expression in a character string and returns the position of string's first character in its first occurance.
- *Question* (aamiri2-stat6250): For what reasons are UPCASE and LOWCASE used in an INDEX function?
- Question (tbishaw-stat6250): When is it appropriate to nest functions?  
- Answer (tbishaw-stat6250): You can nest any functions as long as the function that is used as the argument meets the requirements for the argument
- *Question* (cli19−stat6250): What value does the INDEX function return if the sough after string is not found?
- *Answer* (cli19−stat6250): The INDEX function returns the position of the string's first character. If the string is not found it returns a value of 0.
- *Question* (jbettonville-stat6250): Can multiple INDEX statements be used with additional IF statements to create subsets based on multiple conditions at once?



[recipe_for_isolating_all_duplicates Week 8 Recipe]
- Question(tchan49-stat6250):Why is it important to isolat all deplicated keys? Is this step necessary? 
- Question(pcheng14-stat6250):Why should we sort the data with respect to the unique id schema?
- Question(dfei-stat6250): In the short video, the example show us "if...then..." statement, is "then" necessary or not?
- Question (aguenane−stat6250): Can we do the doublecate comparision without isolating the rows in a temperory dataset?
- *Question* (asharda-stat6250): What is the advantage of storing result in an auxiliary dataset?.
- *Question* (aacharya4−stat6250): What is the difference of between using proc sort with dupout= option and using first and last variable in by-group processing in data step to remove duplicates in a datset?
- *Answer* (aacharya4−stat6250): In case of using proc sort with dupout= option a new dataset is created with dulpcate rows while using first and last variable in by-group processing outputs all duplicate rows to be isolated for comparison.
- *Question* (aamiri2-stat6250): Is there an alternative approach to remove duplicate data and still do a comparison?
- Question (tbishaw-stat6250): What SAS functions can we use to isolate duplicates in a dataset? 
- *Question* (cli19−stat6250): How does the dupout= option in PROC SORT process data differently than using FIRST. and LAST.?
- *Question* (jbettonville-stat6250): How might we extract only records for which the target variable is not duplicated?
- *Answer* (jbettonville-stat6250): In the example provided in the recipe, the records containing unique values in the target variable could be selected by setting the contents of the IF statement to FIRST.School_Code * LAST.School_Code = 1, which would only return values for which the FIRST. and LAST. values for a given variable are both 1, which would indicate that the record in question represents the only instance of that value when sorted by the less deeply nested variables.



[recipe_for_drop_and_swap Week 8 Recipe]
- Question(tchan49-stat6250):What is the function kd? What does it do when extracting character variables? 
- Question(pcheng14-stat6250):What is the meaning of "business logic"?
- Question(dfei-stat6250): How many ways can we rename variables in SAS programming?
- Question (aguenane-stat6250): Why is it necessary to rename High_Grade?
- *Question* (asharda-stat6250): What is the advantage of using drop= dataset option?.
- *Question* (aacharya4−stat6250): what is the default format that is used for in INPUT function with numerical variables having no digits after the decimal place?
- *Answer* (aacharya4−stat6250): "best12." is the default format that is used for in INPUT function with numerical variables having no digits after the decimal place.
- *Question* (aamiri2-stat6250): When using the drop and swap technique, why is it useful to use high grade?
- Question (tbishaw-stat6250): Which SAS functions allows us to perform a character-to-numeric converstion?
- Answer (tbishaw-stat6250): We use the INPUT function to perform a character-to-numeric conversion, this technique is called swap and drop.
- *Question* (cli19−stat6250): What other options can be specified in the COMPRESS function to remove unwanted characters, numbers, etc. from values of a variable?
- *Question* (jbettonville-stat6250): When using the COMPRESS function, there does not appear to be an appreciable difference between writing the option characters as 'kd' or as 'dk'; what is reason for selecting the non-alphabetic order option in the recipe example? 


