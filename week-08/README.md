## Week 8 Quiz Questions and Answers

In order to prepare your Week 8 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-8" in your fork of this repo. Then, after all edits have been made/committed, your Week 8 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-8 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 13, Problem 1]
- Question (nshrivastava2-stat6250): What is the difference between INPUT and PUT functions?
- Answer(nshrivastava2-stat6250):  The form of the INPUT function is very similar to the form of the PUT function (which performs numeric-to-character conversions). However, the INPUT function requires an informat, whereas the PUT function requires a format. 



[Course Textbook Chapter 13, Problem 2]
- Question (nshrivastava2-stat6250): What happens if you skip the INPUT function or the PUT function when converting data? 



[Course Textbook Chapter 13, Problem 3]
- Question (nshrivastava2-stat6250): Does SAS performs automatic conversion of character values to numeric values or vice versa?
- Answer(nshrivastava2-stat6250): Yes, whenever SAS performs automatic data conversion, a message is written to the SAS log stating that the conversion has occurred. 



[Course Textbook Chapter 13, Problem 4]
- Question (nshrivastava2-stat6250): In what conditions/cases, does SAS convert a character data type to a numeric data type, and vice-versa, automatically?
- Answer(nshrivastava2-stat6250): SAS's automatic conversion occurs in the following situations:Assign the character variable to a previously defined numeric variable.2) use it in a math calculation.3) compare it to a numeric operation (IF, not WHERE, more in a second on this). 4) use it in a function that requires numeric arguments.



[Course Textbook Chapter 13, Problem 5]
- Question (nshrivastava2-stat6250): While converting data with restriction for WHERE expressions, will SAS performs automatic conversion?
- Answer(nshrivastava2-stat6250): The WHERE statement does not perform automatic conversions in comparisons. Mismatch of character and numeric variables and values prevents the program from processing the WHERE statements. Automatic conversion is not performed. Instead, the program stops, and error messages are written to the SAS log. 



[Course Textbook Chapter 13, Problem 6]
- Question (nshrivastava2-stat6250): What is the overview of INTCK function ?
- Answer(nshrivastava2-stat6250): The INTCK function returns the number of time intervals that occur in a given time span. It counts intervals from fixed interval beginnings, not in multiples of an interval unit from the from value. Partial intervals are not counted. 



[Course Textbook Chapter 13, Problem 7]
- Question (nshrivastava2-stat6250): How INTNX function works?
- Answer(nshrivastava2-stat6250): The INTNX function is similar to the INTCK function. The INTNX function applies multiples of a given interval to a date, time, or datetime value and returns the resulting value. You can use the INTNX function to identify past or future days, weeks, months, and so on. 



[Course Textbook Chapter 13, Problem 10]
- Question (nshrivastava2-stat6250): SCAN function, specifying the variable length and SUBSTR function is similar to the SCAN function but how they are different from each other? 
- Answer(nshrivastava2-stat6250): SCAN extracts words within a value that is marked by delimiters and SUBSTR extracts a portion of a value by starting at a specified location.



[recipe_for_isolating_all_duplicates Week 8 Recipe]
- Question (nshrivastava2-stat6250): NODUP option in sort procedure, will it works for composite key? 
- Answer(nshrivastava2-stat6250): You use the NODUP option on PROC SORT to remove records where every variable in this record matches every variable in the last observation. SAS only looks at one previous observation when comparing variables and deciding what records to remove. 



[recipe_for_drop_and_swap Week 8 Recipe]
- Question (nshrivastava2-stat6250): How can compress function be use to unrevel strings?
- Answer(nshrivastava2-stat6250): The COMPRESS function is a routine available in the DATA step that allows you to remove unwanted characters. It facilitates the squeezing of information out of the data.


