
## Week 3 Quiz Questions and Answers

In order to prepare your Week 3 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-3" in your fork of this repo. Then, after all edits have been made/committed, your Week 3 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-3 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 3, Problem 1]
- Question (ljiang11−stat6250): why the format is important?
- Answer (ljiang11−stat6250): Because SAS is free free format, keeping an organized format would be easier for developers to read.
- *Question* (jcanfield3-stat6250): What makes the Quit function different than the Run function?
- Question (lceballos-stat6250): Will a program run if the PROC or run are not in column one?
- Answer (lceballos-stat6250): It would run but it won't be easy to read which makes it difficult to understand the purpose of the program.
- Question (ldeng11−stat6250): What are the good practing rules/styles you should follow if you want to write an easy-to-read and easy-to-maintain code? 



[Course Textbook Chapter 3, Problem 2]
- Question (ljiang11−stat6250): Why clear the log window?
- *Question* (jcanfield3-stat6250): Are there a set number of mispellings that SAS can still run through? (Like dat is treated as data)
- Question (lceballos-stat6250): What is the statement to clear the log?
- Answer (lceballos-stat6250): "dm log 'clear;"
- Question (ldeng11−stat6250): What are the steps to debug the code?
- Answer (ldeng11−stat6250): First, check the log window to see what is the error message, then go back to the code to see the specific line of code based on the error message, then make any change if neccessary, run the code again, then check the log window again.



[Course Textbook Chapter 3, Problem 3]
- Question (ljiang11−stat6250): Why it shows "PROC PRINT running"?
- *Question* (jcanfield3-stat6250): Why does the program not recognize a ';' as the end of an unmatched quote?
- *Answer* (jcanfield3-stat6250): Because the ';' could be intended to be within a quotation, and thus not a suitable solution for all cases.
- Question (lceballos-stat6250): If a string contains quotation marks, how can we search for it in SAS with out without running into a syntax error?
- Question (ldeng11−stat6250): Does the sum function apply to the original dataset? Or it apply to the data after the selection statement?


 
[Course Textbook Chapter 3, Problem 4]
- Question (ljiang11−stat6250): What would happen if it is a typo?
- Answer (ljiang11−stat6250): SAS will continue processing, and displays a warning in log window.
- *Question* (jcanfield3-stat6250): Why does SAS still process through some errors?
- Question (lceballos-stat6250): Are there any sort of error handling that can be done with SAS?
- Question (ldeng11−stat6250): What are the Log window and Output window using for?



[Course Textbook Chapter 3, Problem 5]
- Question (ljiang11−stat6250): What are the rules of SAS usage?
- *Question* (jcanfield3-stat6250): Are there other syntax errors besides spelling errors?
- Question (lceballos-stat6250): What's the difference between syntax errors, data errors and logic errors?
- Question (ldeng11−stat6250): What are the common syntax errors?
- Answer (ldeng11−stat6250): Common syntax errors are misspelled keywords, omitting semicolons, quotation marks unbalanced, invalid options etc.



[Course Textbook Chapter 3, Problem 6]
- Question (ljiang11−stat6250): In what situation a "PROC running" message would occur?
- *Question* (jcanfield3-stat6250): Where can you find a list of possible options?
- *Answer* (jcanfield3-stat6250): You click Help -> SAS Help and Documentation.
- Question (lceballos-stat6250): If there are multiple syntax errors, does the log tell you all of them or the first one it finds?
- Question (ldeng11−stat6250): What would happen if you have an invalid option in your code?



[Course Textbook Chapter 3, Problem 7]
- Question (ljiang11−stat6250): What does set keyword do?
- *Question* (jcanfield3-stat6250): Why does proc print need the label option in order for the label to work?
- Question (lceballos-stat6250): Besides correcting dat with data, what else can SAS correct automatically?
- Question (ldeng11−stat6250): What would happen if you have syntax error in your code?



[Course Textbook Chapter 3, Problem 10]
- Question (ljiang11−stat6250): Will there be any message in log window?
- *Question* (jcanfield3-stat6250): Can you tell if a continuous "DATA step running" is due to a run missing or long compiling time, without looking at the code?
- Question (lceballos-stat6250): Why is the run statement necessary?
- Question (ldeng11−stat6250): What happen if you see the window display the message "DATA step running" for a long time?



[Course Textbook Chapter 4, Problem 1]
- Question (ljiang11−stat6250): How many varaibles will be genereated from the code of choice d?
- Answer (ljiang11−stat6250): 5, first two cloumns are identical, both are date.
- *Question* (jcanfield3-stat6250): Is there a limit on the number of variables that can be used for an ID?
- Question (lceballos-stat6250): What does ID statement mean?
- Question (ldeng11−stat6250): What is the "noobs" option using for?



[Course Textbook Chapter 4, Problem 3]
- Question (ljiang11−stat6250): Can I write where style in ('RANCH',"SPLIT",'TWOSTORY');?
- Answer (ljiang11−stat6250): As long as the single quotation mark and double quotation mark are not used on the same word, it will be fine.
- *Question* (jcanfield3-stat6250): Can you use more than one compound WHERE operator in a single statement?
- Question (lceballos-stat6250): Can you use the In operator to only include on item?
- Question (ldeng11−stat6250): What is the "in" option using for?



[Course Textbook Chapter 4, Problem 4]
- Question (ljiang11−stat6250): Is a comma needed before out?
- Answer (ljiang11−stat6250): No.
- *Question* (jcanfield3-stat6250): Do I need to specify work, when naming an output file?
- Question (lceballos-stat6250): How do you sort by descending order?
- Answer (lceballos-stat6250): With the Descending Key option (eg "by y descending x;". 
- Question (ldeng11−stat6250): Do you need to include a by statement when you sort the data?



[Course Textbook Chapter 4, Problem 7]
- Question (ljiang11−stat6250): Is it a syntax error that by statement is missing in PROC SORT step?
- *Question* (jcanfield3-stat6250): In the book solution is the second run statement missing a semicolon?
- *Answer* (jcanfield3-stat6250): Yes it is, the book has a typo, since the semicolon is there in the chapter quiz originally.
- Question (lceballos-stat6250): What is the syntax when using the by procedure?
- Question (ldeng11−stat6250): What would happen if you sort the data but don't creat another data set to store the ordered data?
- Answer (ldeng11−stat6250): The original data set would be overwritten by the sorted data set, which is not the good practice because we like to keep the original data set for reference.



[Course Textbook Chapter 4, Problem 9]
- Question (ljiang11−stat6250): In what situation, a parenthesis is necessary?
- *Question* (jcanfield3-stat6250): What's the point of having multiple ways of saying the same operator in SAS (like le vs <=)?
- Question (lceballos-stat6250): What is the difference between the eq function and "="?
- Question (ldeng11−stat6250): What is the running sequence when you have different logical operand in the same statement?



[Course Textbook Chapter 4, Problem 10]
- Question (ljiang11−stat6250): How can we remove first column?
- Answer (ljiang11−stat6250): By adding option noobs;
- *Question* (jcanfield3-stat6250): What happens when you try to proc print and empty data set?
- Question (lceballos-stat6250): What does "noob" mean in a PROC step?
- Question (ldeng11−stat6250): What does PROC PRINT display if you don't specific any options?



[recipe_to_check_for_duplicates Week 3 Recipe]
- Question (ljiang11−stat6250): what is the mechanism of keyword "nodupkey"?
- *Question* (jcanfield3-stat6250): When can isolating duplicate rows be useful?
- Question (lceballos-stat6250): When using multiple files, what precautions can we take to not have duplicate records
- Question (ldeng11−stat6250): The assumption for this recipe is the data set has one-to-one relationship between the unique id and the obervations (means one unique id can only have one observation). What if the unique id can have multiple observations, how do you check for duplicates? 



[recipe_for_sorting_data Week 3 Recipe]
- Question (ljiang11−stat6250): Why the out= is necessary?
- Answer (ljiang11−stat6250): Because otherwise the original data will be overwritten.
- *Question* (jcanfield3-stat6250): Are "stable" datasets unpreffered?
- Question (lceballos-stat6250): Why would we ever sort the data if there could be information lost by sorting it?
- Question (ldeng11−stat6250): How the SAS would sort the data set if you specify multiple variables in the by statement?



[recipe_for_printing_values Week 3 Recipe]
- Question (ljiang11−stat6250): How to show the last 20 observations?
- *Question* (jcanfield3-stat6250): Is the obs= only capable of showing the first 'x' rows?  What if I didn't want the first row?
- Question (lceballos-stat6250): Is it possible to export the manipulated data to an excel file?
- Question (ldeng11−stat6250): How can you print the only last several rows in the data set. For example, print the last 20 rows?


