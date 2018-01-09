
## Week 2 Quiz Questions and Answers

In order to prepare your Week 2 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-2" in your fork of this repo. Then, after all edits have been made/committed, your Week 2 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-2 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 1, Problem 1]
-*Question** (akrishnamurthy-stat6250):What is an observation in SAS? Can a row with missing values be considered as an observation?


[Course Textbook Chapter 1, Problem 2]
- *Question** (akrishnamurthy-stat6250):When will SAS execute a DATA, PROC or RUN statement?
- *Answer* (akrishnamurthy-stat6250):SAS executes the previous steps in the program when it encounters a DATA,PROC or RUN statements. RUN statements are not always required to specify execution step but using RUN statements makes the program and log more readable.


[Course Textbook Chapter 1, Problem 3]
- *Question* (akrishnamurthy-stat6250):Can special characters be assigned to numeric variables ?


[Course Textbook Chapter 1, Problem 4]
- *Question* (akrishnamurthy-stat6250):how are the missing values specified for character and numeric variables ?
- *Answer* (akrishnamurthy-stat6250):Missing values for character variables are assigned with spaces and numeric variables are assigned with period


[Course Textbook Chapter 1, Problem 5]
- *Question* (akrishnamurthy-stat6250):How should SAS variable name be defined?


[Course Textbook Chapter 1, Problem 8]
- *Question* (akrishnamurthy-stat6250):What is the length of a numeric variable with 10 digits?
- *Answer* (akrishnamurthy-stat6250):Irrespective of number of digits, numeric variables are always stored as floating point numbers in 8 bytes of storage unless a different length is specified.


[Course Textbook Chapter 2, Problem 3]
- *Question* (akrishnamurthy-stat6250):How to read from and write to files of different formats in SAS ?


[Course Textbook Chapter 2, Problem 7]
- *Question* (akrishnamurthy-stat6250):What is the function of YEARCUTOFF proc option?


[Course Textbook Chapter 2, Problem 8]
- *Question* (akrishnamurthy-stat6250):How to access files stored in SAS library ? Can the files be accessed across SAS sessions?


[Course Textbook Chapter 2, Problem 9]
- *Question* (akrishnamurthy-stat6250):What is the syntax of libname statement ? Should the engine and library be specified for all files to be accessed?


[basic_recipe_for_loading_data_from_remote_Excel_file Week 2 Recipe]
- *Question* (akrishnamurthy-stat6250):How to access a file from a remote server in SAS ? How to import raw data as a excel file in SAS ?


[bonus_advanced_recipe_for_loading_data_from_remote_Excel_file Week 2 Recipe]
- *Question* (akrishnamurthy-stat6250):How to define macros in SAS ? Should the macros be called with the same set of parameters defined in macro definition?

