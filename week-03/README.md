
## Week 3 Quiz Questions and Answers

In order to prepare your Week 3 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-3" in your fork of this repo. Then, after all edits have been made/committed, your Week 3 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-3 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 3, Problem 1]
- *Question* (sbagdi-stat6250): Can I create my own keywords?
- *Answer* (sbagdi-stat6250): Yes, creating and formatting keywords for a SAS program is possible using the enhanced editer in SAS. 



[Course Textbook Chapter 3, Problem 2]
- *Question* (sbagdi-stat6250): What is the non-compulsory, but an essential good practice before resubmitting a revised SAS program?


[Course Textbook Chapter 3, Problem 3]
- *Question* (sbagdi-stat6250): After creating the abbreviations, what steps are to be performed to finally display the full length of the abbreviated text?
- *Answer* (sbagdi-stat6250): Steps to display the full length abbreviated text-
a) Type the abbreviation.
b) if that abbreviation is recognized, a tooltip displays the expanded text; Press Tab Key or Enter to accept the abbreviation. 

 
[Course Textbook Chapter 3, Problem 4]
- *Question* (sbagdi-stat6250): What are the different types of syntax errors?


[Course Textbook Chapter 3, Problem 5]
- *Question* (sbagdi-stat6250): How to locate a statement that lacks a semi-colon in an error message?


[Course Textbook Chapter 3, Problem 6]
- *Question* (sbagdi-stat6250): Why doesn’t simply adding a quotation mark (in missing quotation mark errors) and resubmitting a program resolves the problem? 


[Course Textbook Chapter 3, Problem 7]
- *Question* (sbagdi-stat6250): What are the essential steps to resolve the issue of invalid option?


[Course Textbook Chapter 3, Problem 10]
- *Question* (sbagdi-stat6250): Which syntax error, other than the ‘missing run statement’, results in error message- ‘DATA Step running’ at the top of active window?




[Course Textbook Chapter 4, Problem 1]
- *Question* (sbagdi-stat6250): Which option is used to remove the default observation column (column that displays observation numbers)? Where do the programmer specifies that option in his program?


[Course Textbook Chapter 4, Problem 3]
- *Question* (sbagdi-stat6250): Why are logical operators used in any SAS programs? Also, Which operator can be used as an alternative to ‘OR’ operator? 
- *Answer* (sbagdi-stat6250): The logical operators link sequence of expressions into compound expressions. Two types are: ‘AND’ (&) and ‘OR’ (|). Operator ‘IN’ can be used in place of ‘OR’ operator. 



[Course Textbook Chapter 4, Problem 4]
- *Question* (sbagdi-stat6250): What happens if a programmer doesn’t use OUT= option in a PROC SORT step? 


[Course Textbook Chapter 4, Problem 7]
- *Question* (sbagdi-stat6250): What does the DESCENDING option does? And to which statement should it be added?
- *Answer* (sbagdi-stat6250): The DESCENDING option sorts observations in ascending order of second variable (the one programmer specifies in VAR statement) within descending order of the first variable. And it should be added to the BY statement.

[Course Textbook Chapter 4, Problem 9]
- *Question* (sbagdi-stat6250): Which operator is used to select observations that include a specified string?
- *Answer* (sbagdi-stat6250):The contains operator is used to select observations including a specified string- CONTAINS ‘xyz’ OR ? ‘xyz.



[Course Textbook Chapter 4, Problem 10]
- *Question* (sbagdi-stat6250): How many ‘WHERE’ statements can there be in any PROC PRINT step?


[recipe_to_check_for_duplicates Week 3 Recipe]
- *Question* (sbagdi-stat6250): What happens if the OUT= option is set to anything other than the null value? Specify the statement used to sort the duplicate records.


[recipe_for_sorting_data Week 3 Recipe]
- *Question* (sbagdi-stat6250): In which order is a data stored by default in a data set? Does a programmer need to specify the order type in a default order state? 
- *Answer* (sbagdi-stat6250): By default, the data in a data set is stored in ascending order. And, there’s no need to write ‘ascending’ before the variable name.



[recipe_for_printing_values Week 3 Recipe]
- *Question* (sbagdi-stat6250): What does a (OBS= ) statement does in PROC PRINT?

