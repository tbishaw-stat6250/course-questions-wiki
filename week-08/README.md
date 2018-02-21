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
- Question (nshrivastava2-stat6250): What is the difference between INPUT and PUT functions?
- Answer(nshrivastava2-stat6250):  The form of the INPUT function is very similar to the form of the PUT function (which performs numeric-to-character conversions). However, the INPUT function requires an informat, whereas the PUT function requires a format. 
- *Question* (shatcher4-stat6250): What are the SAS functions that compute sample statistics?
- *Answer* (shatcher4-stat6250): SUM, MEAN, MIN, MAX, VAR, STD
- *Question* (cnguyen77-stat6250): How to specify a variable list in MEAN function?
- *Answer* (cnguyen77-stat6250): When specifying a variable list, be sure to precede the list with the word OF. If you omit the word OF, the function argument might not be interpreted as expected.
- *Question* (ldai4-stat6250): Are function mean(var1,var2,var3, var4) and mean(of var1-var4) same?
- *Answer* (ldai4-stat6250): Yes. they are same. But the work OF can not be omitted.
- *Question* (xyin6-stat6250): Where should we put the word "of" if we want mean value of x1,x2,x4, excluding x3?
- *Question* (jcanfield3-stat6250): What is another way to calculate this mean?
- *Answer* (jcanfield3-stat6250): This can be done by writing 'mean(var1, var2, var3, var4);'.
- Question (ttruong59-stat6250): When specifying a variable list for mean function, preceding the list with the word OF is required as mean(of var1-var) for example? What happens if users omit the word OF?
- Answer (ttruong59-stat6250): If users omit the word OF, the function returns var1-var4, not the average of the variable var1, var2, var3, var4.
- Question (ldeng11−stat6250): How many ways you can write for caculating the average of the variable var1, var2, var3, and var4?
- *Question* (who7-stat6250): How can we show results in table format after using SAS function?
- Question (ljiang11−stat6250): What does mean(var1-var4) output?
- Question (lsun20-stat6250): Can we use median(of var1, var4) function to calculate the median number of these variables?
- *Question* (akrishnamurthy-stat6250): How to specify a range of variables as function argument ?
- *Answer* (akrishnamurthy-stat6250): Variable list can be used to specify the range of variables for a function argument. The list should be preceded by the keyword OF followed by the starting and ending variables.
- Question (lceballos-stat6250): Can you use multiple ranges for the mean function.
- *Question* (sbagdi-stat6250): Why should we specify the word OF before a list or array when specifying function arguments?
- *Question*(kamirneni-stat6250): Can the arguments of mean function be imported by some other way apart from a variable list?
- *Answer*(kamirneni-stat6250): Yes, the variables can be referenced by an array.



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
- Question (nshrivastava2-stat6250): What happens if you skip the INPUT function or the PUT function when converting data? 
- *Question* (shatcher4-stat6250): How do you convert a character variable from character to numeric?
- *Question* (cnguyen77-stat6250): What happens when there is a multiplication of character variables and numeric variables in SAS?
- *Answer* (cnguyen77-stat6250): SAS automatically converts the character values to numeric values so that the calculation can occur. Whenever data is automatically converted, a message is written to the SAS log stating that the conversion has occurred.
- *Question* (ldai4-stat6250): What happens when DATA step, Salary=PayRate*hours, is executed?
- *Answer* (ldai4-stat6250): SAS automatically converts the character values of PayRate to numeric values so that the calculation can occur. A message is showed in the SAS log.
- *Question* (xyin6-stat6250): Is there any restrictions in the automatic character-to-numeric conversion?
- *Answer* (xyin6-stat6250): It will produce a numeric missing value from any character value that does not conform to standard numeric notation (digits with an optional decimal point, leading sign or scientific notation).
- *Question* (jcanfield3-stat6250): How does SAS identify variables that can be converted to numeric?
- Question (ttruong59-stat6250): Under what step that SAS will auto convert the character values to numeric values so that the calculation can occur?
- Answer (ttruong59-stat6250): When the DATA step is executed, SAS will convert the character values to numeric values so that the calculation can occur.
- Question (ldeng11−stat6250): What would happen if you use mathmatic operators connect numeric values with character values?
- Answer (ldeng11−stat6250): If you omit the INPUT or PUT function to convert the variables, and if the variables can automatic finish the conversion, the SAS will automatically convert the values, and write the message in the log to tell you the conversion has occurred. But if the variables can not automatic finish the conversion, the SAS would stop excute and have error message.
- *Question* (who7-stat6250): Will SAS convert charactor value to numeric value?
- *Answer* (who7-stat6250): Yes, you can use the Put() function to achieve that. 
- Question (ljiang11−stat6250): Will a message be written to SAS log everytime an automatic convertion occur?
- Answer (ljiang11−stat6250): Yes.
- Question (lsun20-stat6250): Why the SAS will convert the character variable to numeric values in this situation?
- Answer (lsun20-stat6250): The SAS automatically converts the character values of PayRate to numeric values when the DATA step was executed.
- *Question* (akrishnamurthy-stat6250): Why does SAS handle data conversion for mismatch data type calculation instead of raising an exception?
- Question (lceballos-stat6250): What if a payrate includes non-numeric values?
- *Question* (sbagdi-stat6250): How to convert a variable from character to numeric?
- *Question*(kamirneni-stat6250): Under what circumstances, does SAS convert character into numeric value?



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
- Question (nshrivastava2-stat6250): Does SAS performs automatic conversion of character values to numeric values or vice versa?
- Answer(nshrivastava2-stat6250): Yes, whenever SAS performs automatic data conversion, a message is written to the SAS log stating that the conversion has occurred. 
- *Question* (shatcher4-stat6250): When does automatic character to numeric conversion occur?
- *Question* (cnguyen77-stat6250): How to convert character values to numeric values?
- *Answer* (cnguyen77-stat6250): You explicitly convert character values to numeric values by using the INPUT function. Be sure to select an informat that can read the form of the values.
- *Question* (ldai4-stat6250): SAS can automatically convert character values to numeric values, but why is INPUT function usually used?
- *Question* (xyin6-stat6250): When choosing the numeric informat in the INPUT function, do we refer to the longest character value?
- *Question* (jcanfield3-stat6250): Why do we need separate Put and Input functions rather than one that does both? 
- Question (ttruong59-stat6250): What is a major difference of using INPUT and PUT function when creating the variable?
- Answer (ttruong59-stat6250): INPUT function used to convert character values to numeric values while PUT function used to convert numeric values to character values.
- Question (ldeng11−stat6250): When there is specific format in the variable like $ or the comma, what you should do to finish the explicit conversion?
- *Question* (who7-stat6250): What is the methodology use when determinging which function to use, put() or input()?
- *Answer* (who7-stat6250): We can first ask if the final varaible a character or number, then determine if the source variable is a character or a number.  Finally, if source varaible is a character, is the final varaible a character or a number.  This would help determine wether to use put() or input().
- Question (ljiang11−stat6250): What does INPUT do?
- Question (lsun20-stat6250): Why it is comma7. in this statement that the target 123,456 is 6 number?
- *Question* (akrishnamurthy-stat6250): What is the difference between PUT function and INPUT function?
- *Answer* (akrishnamurthy-stat6250): PUT function is for converting numeric to character datatypes and INPUT function converts character values to numeric.
- Question (lceballos-stat6250): Why is it always best to include INPUT and PUT functions in your programs?
- Answer (lceballos-stat6250): To avoid data type mismatches and circumvent automatic conversion.
- *Question* (sbagdi-stat6250): How are functions INPUT and PUT different from each other?
- *Question*(kamirneni-stat6250): When converting data, what is the result if one forgets to skip the INPUT function?
- *Answer*(kamirneni-stat6250): SAS detects the mismatched variables and tries an automatic character to numeric conversion or vice versa. This process is not always successful. It is recommended to include INPUT and PUT function.



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
- Question (nshrivastava2-stat6250): In what conditions/cases, does SAS convert a character data type to a numeric data type, and vice-versa, automatically?
- Answer(nshrivastava2-stat6250): SAS's automatic conversion occurs in the following situations: Assign the character variable to a previously defined numeric variable.2) use it in a math calculation.3) compare it to a numeric operation. 4) use it in a function that requires numeric arguments.
- *Question* (shatcher4-stat6250): How do you explicitly convert numeric data values to character values?
- *Question* (cnguyen77-stat6250): How to convert numeric values to character values?
- *Answer* (cnguyen77-stat6250): You explicitly convert numeric values to character values by using the PUT function. Be sure to select a format that can read the form of the values.
- *Question* (ldai4-stat6250): What is the difference between INPUT function and PUT function?
- *Question* (xyin6-stat6250): What happens if we use the PUT function to create a variable that has not been previously identifies?
- *Answer* (xyin6-stat6250): It will create a character variable whose length is equal to the format width.
- *Question* (jcanfield3-stat6250): Is there ever a situation where a variable cannot be converted back to its original data type after transformation?  (Ex a numeric converted to char, that cannot be converted back to a numeric)
- Question (ttruong59-stat6250): What happens if we use the PUT function to create a variable that has not been previously identified?
- Answer (ttruong59-stat6250): It will create a character variable whose length is equal to the format width.
- Question (ldeng11−stat6250): What is the concatenation operator doing here?
- *Question* (who7-stat6250): In what other instances where we will use "||" in sas?
- Question (ljiang11−stat6250): What does PUT do?
- Question (lsun20-stat6250): How the SAS convert numeric values to character values?
- Answer (lsun20-stat6250): We can convert numeric values to character values by using the PUT function and select the readable form of the values.
- *Question* (akrishnamurthy-stat6250): What is the syntax of PUT function ? How does SAS handle the PUT function, if input format is different from format specified in PUT function ?
- Question (lceballos-stat6250): How do you convert numbers to characters?
- Answer (lceballos-stat6250): Using the PUT(source,format) statement
- *Question* (sbagdi-stat6250): How to convert data values from numeric to character values?
- *Question*(kamirneni-stat6250): What happens if one creates a variable in the PUT function?
- *Answer*(kamirneni-stat6250): It creates a character variable whose length is equal to the format width.



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
- Question (nshrivastava2-stat6250): While converting data with restriction for WHERE expressions, will SAS perform automatic conversion?
- Answer(nshrivastava2-stat6250): The WHERE statement does not perform automatic conversions in comparisons. Mismatch of character and numeric variables and values prevents the program from processing the WHERE statements. Automatic conversion is not performed. Instead, the program stops, and error messages are written to the SAS log. 
- *Question* (shatcher4-stat6250): How does SAS store date values, time values, and datetime values?
- *Answer* (shatcher4-stat6250): A date value is stored as the number of days from January 1, 1960, to a given date. A time value is stored as the number of seconds since midnight. A datetime value is stored as the number of seconds between midnight on January 1, 1960, and a given date and time.
- *Question* (cnguyen77-stat6250): What does the YEAR function do?
- *Answer* (cnguyen77-stat6250): The YEAR function returns a four-digit numeric value that represents the year (for example, 2002).
- *Question* (ldai4-stat6250): Does the MDY function accept two-digit value for the year?
- *Answer* (ldai4-stat6250): Yes, SAS accepts two-digit year. But SAS interprets two_digit values according to the 100-year span that is set by the YEARCUTOFF=system option.
- *Question* (xyin6-stat6250): What does the format "date9." represent in the date conversion process?
- *Question* (jcanfield3-stat6250): Is the MDY function capable of handling 5 digit years?
- Question (ttruong59-stat6250): Is it possible to reset the YEARCUTOFF= system option, instead of using 1920 as a default? 
- Question (ldeng11−stat6250): Is YEARCUTOFF option affect the date value when you use four digit to indicate the year?
- Answer (ldeng11−stat6250): No. The YEARCUTOFF option is only working when you use two digit to indicate the year.
- *Question* (who7-stat6250): How do we figure out when systemcutoff date is?
- Question (ljiang11−stat6250): Why MDY(1, 3, 20) won't work?
- Answer (ljiang11−stat6250): Because the YEARCUTOFF= system option is set to 1920, so 20 will be mistaken to 1920.
- Question (lsun20-stat6250): Can we use 20 instead of 1920 in this situation if without the YEARCUTOFF= system option is set to 1920?
- *Question* (akrishnamurthy-stat6250): What is the use of YEARCUTOFF= option?
- *Answer* (akrishnamurthy-stat6250): The YEARCUTOFF option specifies which 100 year span is used to interpret two-digit year values. The default value of YEARCUTOFF= is 1920 which can also be overriden. 
- Question (lceballos-stat6250): How is Datetime stored in SAS?
- Answer (lceballos-stat6250): Is stored as the number of seconds between midnight on January 1, 1960, and a given date and time.
- *Question* (sbagdi-stat6250): What does SCAN function does in SAS?
- *Answer* (sbagdi-stat6250): To return the nth word in a character string, we make use of SCAN function.
- *Question*(kamirneni-stat6250): How is the MDY function efficient?



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
- Question (nshrivastava2-stat6250): What is the overview of INTCK function?
- Answer(nshrivastava2-stat6250): The INTCK function returns the number of time intervals that occur in a given time span. It counts intervals from fixed interval beginnings, not in multiples of an interval unit from the from value. Partial intervals are not counted. 
- *Question* (shatcher4-stat6250): What is the purpose of the SCAN function?
- *Question* (cnguyen77-stat6250): How to extract words from a character value?
- *Answer* (cnguyen77-stat6250): The SCAN function is used to extract words from a character value when you know the order of the words, when their position varies, and when the words are marked by some delimiter.
- *Question* (ldai4-stat6250): How does the SCAN function work?
- *Answer* (ldai4-stat6250): The SCAN function is used to extract words from a character value when you know the order of the words, when their position varies, and when the words are marked by some delimiter.
- *Question* (xyin6-stat6250): What is the most significant difference between SCAN and SUBSTR function?
- *Answer* (xyin6-stat6250): The SUBSTR function is best used when you know the exact position of the string that you want to extract from the character value. By contrast, the SCAN function is best used when you know the order of the words in the character value; the starting position of the words varies and the words are marked by some delimiter.
- *Question* (jcanfield3-stat6250): Why is option d not a valid answer?
- *Answer* (jcanfield3-stat6250): While option D does produce the correct value for this specific value, it does not provide the correct value for all values of this format. (Ex. Santa Barbara, CA would result in State = 'A,') 
- Question (ttruong59-stat6250): What is a major difference between SCAN and SUBSTR function?
- Answer (ttruong59-stat6250): SCAN function is used to return a specified word from a character value while SUBSTR function is used to extract a substring or to replace character values.
- Question (ldeng11−stat6250): How do you substring the specific charators?
- *Question* (who7-stat6250): Is there a methodology to when to use scan or substr function?
- *Answer* (who7-stat6250): Scan will select a portion of the original string where substr can take out a part of it.  So if the word is seperated by spaces, scan would be great while if it isn't, then substr.
- Question (ljiang11−stat6250): Why we want to use SCAN instead of SUBSTR?
- Answer (ljiang11−stat6250): The SCAN function is used to extract words from a character value when you know the order of the words.
- Question (lsun20-stat6250): What is the differnent between the scan function and substr function?
- *Question* (akrishnamurthy-stat6250): What is the use of SCAN function in SAS?
- Question (lceballos-stat6250): Can you specify the delimiter when using a SCAN function?
- *Question* (sbagdi-stat6250): What is INTCK function used for?
- *Answer* (sbagdi-stat6250): The INTCK function returns the number of time intervals in a time span. It counts intervals from fixed intervals beginnings, not in multiples of interval unit. 
- *Question*(kamirneni-stat6250): What are the specifications of INTNX function?



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
- Question (nshrivastava2-stat6250): How INTNX function works?
- Answer(nshrivastava2-stat6250): The INTNX function is similar to the INTCK function. The INTNX function applies multiples of a given interval to a date, time, or datetime value and returns the resulting value. You can use the INTNX function to identify past or future days, weeks, months, and so on. 
- *Question* (shatcher4-stat6250): What are the differences between SUBSTR and SCAN?
- *Question* (cnguyen77-stat6250): When is the best to use SUBSTR function?
- *Answer* (cnguyen77-stat6250): The SUBSTR function is best used when you know the exact position of the substring to extract from the character value. You specify the position to start from and the number of characters to extract.
- *Question* (ldai4-stat6250): If we know the exact position of the substring to extract from the character value, what function is best used?
- *Question* (xyin6-stat6250): In the SUBSTR function, if position =2 and n is omitted, what will happen to the character value?
- *Answer* (xyin6-stat6250): All the remaining characters starting from position 2 will be included in the substring.
- *Question* (jcanfield3-stat6250): What happens when you do not specify the number of values to extract when using substr?
- Question (ttruong59-stat6250): How to distinguish a SUBSTR function which is used to extract a substring or is used to replace character values?
- Answer (ttruong59-stat6250): The best way to recognize its use is to look at the side of the statement. The function is used to extract a substring if the SUBSTR function is on the right side. And the function is used to replace the contents of the character variable if the SUBSTR function is on the left side.
- Question (ldeng11−stat6250): How do you extract specific charators from the input?
- *Question* (who7-stat6250): Is there a limit on how long a substring can be?
- Question (ljiang11−stat6250): Why do we want to use SUBSTR, not SCAN?
- Answer (ljiang11−stat6250): The SUBSTR function is best used when you know the exact position of the substring to extract from the character value.
- Question (lsun20-stat6250): Is there any influence about the capitailize of the idcode?
- *Question* (akrishnamurthy-stat6250):What is the difference between SCAN and SUBSTR functions?
- Question (lceballos-stat6250): How can we extract the month and year but not the day?
- *Question* (sbagdi-stat6250): How are SCAN and SUBSTR different from each other?
- *Question*(kamirneni-stat6250): What is the maximum number of delimiters that can be used in a SCAN function?



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
- Question (nshrivastava2-stat6250): SCAN function, specifying the variable length and SUBSTR function is similar to the SCAN function but how they are different from each other? 
- Answer(nshrivastava2-stat6250): SCAN extracts words within a value that is marked by delimiters and SUBSTR extracts a portion of a value by starting at a specified location.
- *Question* (shatcher4-stat6250): How does the INDEX function work?
- *Answer* (shatcher4-stat6250): The INDEX function searches a character value for a specified string by searching values from left to right, looking for the first occurance of the string. It will then return the position of the string's first character; however, if the string is not found, it will return a value of 0.
- *Question* (cnguyen77-stat6250): When is the INDEX function being used?
- *Question* (ldai4-stat6250): Must the INDEX function be used in a subsetting IF statement?
- *Question* (xyin6-stat6250): When should we put quotation marks inside the INTNX function?
- *Question* (jcanfield3-stat6250): How would I make sure the function finds the word 'walnut' instead of the string?
- Question (ttruong59-stat6250): Is INDEX function case-sensitive so the character string we search for must be specified exactly as it is recorded in the dataset? If so, is there any alternative function to search for but it is not case-sensitive?
- Answer (ttruong59-stat6250): Yes, INDEX function is case-sensitive. we can use FIND function which is similar to INDEX to complete the search.
- Question (ldeng11−stat6250): What is lowcase function doing here?
- Answer (ldeng11−stat6250): It transform all the charators in the input to their lower cases.
- *Question* (who7-stat6250): Can we update exisitng dataset by using SAS function to rewrite the dataset?
- Question (ljiang11−stat6250): What does INDEX function do?
- Question (lsun20-stat6250): What is the usage of >0 in the IF statement?
- Answer (lsun20-stat6250): It shows the only those observations in which function locates the string and returns a value greater than 0 are written to the data set.
- *Question* (akrishnamurthy-stat6250): What is the difference between FIND and INDEX functions in SAS ?
- Question (lceballos-stat6250): What's the difference between INDEX and FIND?
- *Question* (sbagdi-stat6250): What is INTNX function? 
- *Question*(kamirneni-stat6250): What is the criteria of using the pre-defined functions in nested functions?



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
- Question (nshrivastava2-stat6250): NODUPKEY and DUPOUT= option in sort procedure, how its helpful in getting rid of duplicate records? 
- Answer(nshrivastava2-stat6250): The new DUPOUT option on the SORT statement provides this without adding program steps. if input data set is not expected to contain duplicates, PROC SORT with NODUPKEY and DUPOUT provides protection against bad duplicate data without adding much overhead when there are no duplicates. Use of NODUP option on PROC SORT to remove records where every variable in this record matches every variable in the last observation. SAS only looks at one previous observation when comparing variables and deciding what records to remove. 
- *Question* (shatcher4-stat6250): What is the purpose of by-group processing?
- *Question* (cnguyen77-stat6250): How to isolate duplicate values of records of a SAS data set?
- *Question* (ldai4-stat6250): How can we remove the duplicates in new data set?
- *Question* (xyin6-stat6250): Still confused why both first.school_code and last.school_code equals 1 represents there's no duplicates?
- *Question* (jcanfield3-stat6250): If the data is presorted is the 'by statement' needed when forming the dups dataset?
- Question (ttruong59-stat6250): What happens if first.School_Code*last.School_Code will equal 1?
- Question (ldeng11−stat6250): Can you use PROC SQL to write the code doing the same thing?
- *Question* (who7-stat6250): What is the main advantage by using the first and last variable to remove duplicates verse using the proc sort method shown in Week 3?
- Question (ljiang11−stat6250): What does FIRST. and LAST. do?
- Question (lsun20-stat6250): Where the output of this statement will be  in this example?
- *Question* (akrishnamurthy-stat6250): What are the ways of eliminating duplicates from a dataset in SAS ?
- Question (lceballos-stat6250): What is the function of first.School_Code*last.School_Code = 0?
- *Question* (sbagdi-stat6250):  What are FIRST. and LAST. variables in by-group processing?
- *Question*(kamirneni-stat6250): How is isolating the duplicates more efficient from PROC SORT function?



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
- Question (nshrivastava2-stat6250): How can compress function be use to unravel strings?
- Answer(nshrivastava2-stat6250): The COMPRESS function is a routine available in the DATA step that allows you to remove unwanted characters. It facilitates the squeezing of information out of the data.
- *Question* (shatcher4-stat6250): What does the 'kd' option do?
- *Question* (cnguyen77-stat6250): What is the function of "call missing (variable)"?
- *Question* (ldai4-stat6250): When match-merging, if we use DROP= data set option, do the dropped variables still exist in the original data set?
- *Question* (xyin6-stat6250): What does best12. represent? Is it a default formatting way?
- *Question* (jcanfield3-stat6250): What does the 'kd' option stand for?
- *Answer* (jcanfield3-stat6250): It is actually two options, k "keeps the characters in the list instead of removing them" and d "adds digits to the list of characters."
- Question (ttruong59-stat6250): What is a main purpose of using the ‘kd’ option and the format best12. for this recipe?
- Answer (ttruong59-stat6250): The 'kd' option is used to remove all other characters and keep digits only. And best12. is used to set the default format for numerical variables having no value after the decimal point.
- Question (ldeng11−stat6250): What is "call missing (High_Grade)" doing here?
- *Question* (who7-stat6250): What other scenerio would we prefer to sort the data by coverting them to character first?
- Question (ljiang11−stat6250): What does CALL statement do? Do we include CALL MISSING to make sure High_Grade is numeric, otherwise make it missing value?
- Question (lsun20-stat6250): Why we need the end function between the then statement and else statement?
- *Question* (akrishnamurthy-stat6250): How to rename a dataset variable only for the duration of a DATA step?
- Question (lceballos-stat6250): Can we use this if the dataset has special characters?
- *Question* (sbagdi-stat6250): What does the ‘kd’ option in compress function do?
- *Answer* (sbagdi-stat6250): The ‘kd’ option keeps just the digits and remove all the characters from the values of variables.
- *Question*(kamirneni-stat6250): What are the implications of removing all characters from values of a variable?


