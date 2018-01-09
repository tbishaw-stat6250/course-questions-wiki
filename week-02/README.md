## Week 2 Quiz Questions and Answers

In order to prepare your Week 2 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-2" in your fork of this repo. Then, after all edits have been made/committed, your Week 2 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-2 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 1, Problem 1]
- *Question* (ldai4-stat6250): What is observations and variables in the data set?
- *Answer* (ldai4-stat6250): In the data set, rows are called observations, and columns are called variables.

[Course Textbook Chapter 1, Problem 2]
- *Question* (ldai4-stat6250): what two steps can be in most SAS programs?
- *Answer*  (ldai4-stat6250): A SAS program can consist of a DATA step or a PROC step or any combination of DATA and PROC steps.


[Course Textbook Chapter 1, Problem 3]
- *Question* (ldai4-stat6250): Can a variable be either character or numeric? 


[Course Textbook Chapter 1, Problem 4]
- *Question* (ldai4-stat6250): what is variable’s type?
- *Answer*  (ldai4-stat6250): A variable’s type is either character or numeric. Character variable can contain any values; and numeric variables can contain only numeric values (the numerals 0-9,+,-., and E for scientific notation). A variable’s type also determines how missing values for a variable are displayed. For character variables,  a blank represents a missing value; and for numeric variables, a period represents a missing value.

[Course Textbook Chapter 1, Problem 5]
- *Question* (ldai4-stat6250): What is the rules of variable name in SAS?
- *Answer*  (ldai4-stat6250): Variable names follow the same rules, which can be 1 to 32 characters long, must begins with a letter(A-Z, either uppercase or lowercase) or an underscore, and can continue with any combination of numerals, letters, or underscores.


[Course Textbook Chapter 1, Problem 8]
- *Question* (ldai4-stat6250): What is the default length for the numeric variable?
- *Answer*  (ldai4-stat6250): The numeric variables have a default length of 8. Numeric values( no matter how many digits they contain) are stored in 8 bytes of storage unless you specify a different length.


[Course Textbook Chapter 2, Problem 3]
- *Question* (ldai4-stat6250): How four-digit years are handled?
- *Answer*  (ldai4-stat6250): The vale of the YEARCUTOFF=system option affects only two-digit year values. A date value that contains a four-digit year value will be interpreted correctly even if it does not fall within the 100-year span set by the YEARCUTOFF=system option.


[Course Textbook Chapter 2, Problem 7]
- *Question* (ldai4-stat6250): How can we reference SAS file in SAS libraries?




[Course Textbook Chapter 2, Problem 8]
- *Question* (ldai4-stat6250): what difference are two-digit year and four-digit year?



[Course Textbook Chapter 2, Problem 9]
- *Question* (ldai4-stat6250): what is LIBNAME statement?
- *Answer*  (ldai4-stat6250): The LIBNAME statement is global, which associates or disassociates a SAS library with a libref (a shortcut name), clears one or all librefs, lists the characteristics of a SAS library, concatenates SAS libraries, or concatenates SAS catalogs. 


[basic_recipe_for_loading_data_from_remote_Excel_file Week 2 Recipe]
- *Question* (ldai4-stat6250): Can the raw data's format be displayed in SAS library?


[bonus_advanced_recipe_for_loading_data_from_remote_Excel_file Week 2 Recipe]
- *Question* (ldai4-stat6250): For a specific SAS data set, can I use PROC DATASETS to display it? 

