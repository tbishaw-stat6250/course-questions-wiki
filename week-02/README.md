## Week 2 Quiz Questions and Answers

In order to prepare your Week 2 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-2" in your fork of this repo. Then, after all edits have been made/committed, your Week 2 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-2 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 1, Problem 1]
- *Question* (ldai4-stat6250): What is a SAS data set?
- *Answer* (ldai4-stat6250): A SAS data set is a data file that is formatted in a way that SAS can understand.


[Course Textbook Chapter 1, Problem 2]
- *Question* (ldai4-stat6250): what two steps can be in most SAS programs?
- *Answer*  (ldai4-stat6250): A SAS program can consist of a DATA step or a PROC step or any combination of DATA and PROC steps.


[Course Textbook Chapter 1, Problem 3]
- *Question* (ldai4-stat6250): What is the purposes of DATA steps and PROC steps?
- *Answer*  (ldai4-stat6250): DATA steps create and modify SAS data sets. You can use DATA steps to put your data into SAS data set, compute values, check for and correct errors, and produce new SAS data sets. PROC steps involve or call pre-written routines. You can use PROC steps to create a report that lists the data, produce descriptive statistics, create a summary report, and produce plots and charts.

[Course Textbook Chapter 1, Problem 4]
- *Question* (ldai4-stat6250): What is the rules of variable name in SAS?
- *Answer*  (ldai4-stat6250): Variable names follow the same rules, which can be 1 to 32 characters long, must begins with a letter(A-Z, either uppercase or lowercase) or an underscore, and can continue with any combination of numerals, letters, or underscores.


[Course Textbook Chapter 1, Problem 5]
- *Question* (ldai4-stat6250): What is the default length for the numeric variable?
- *Answer*  (ldai4-stat6250): The numeric variables have a default length of 8. Numeric values( no matter how many digits they contain) are stored in 8 bytes of storage unless you specify a different length.



[Course Textbook Chapter 1, Problem 8]
- *Question* (ldai4-stat6250): What is SAS library?
- *Answer*  (ldai4-stat6250): Every SAS file is stored in a SAS library, which is a collection of SAS files, such as SAS data sets and catalogs. In some operating environment, a SAS library is a physical collection of file. In others, the files are only logically related. In the Windows and UNIX environments, a SAS library is typically a group of SAS files in the same folder or directory.



[Course Textbook Chapter 2, Problem 3]
- *Question* (ldai4-stat6250): How can you create SAS output in HTML format on any SAS platform?
- *Answer*  (ldai4-stat6250): I can create HTML output using programming statements on any SAS platform.



[Course Textbook Chapter 2, Problem 7]
- *Question* (ldai4-stat6250): What is SAS engine?
- *Answer*  (ldai4-stat6250): A SAS engine is a set of internal instruction that SAS uses for writing to and reading from files in SAS library. Each engine specifies the file format for files that are stored in the library, which in turn enables SAS to access files with a particular format.



[Course Textbook Chapter 2, Problem 8]
- *Question* (ldai4-stat6250): How four-digit years are handled?
- *Answer*  (ldai4-stat6250): The vale of the YEARCUTOFF=system option affects only two-digit year values. A date value that contains a four-digit year value will be interpreted correctly even if it does not fall within the 100-year span set by the YEARCUTOFF=system option.



[Course Textbook Chapter 2, Problem 9]
- *Question* (ldai4-stat6250): When you specify an engine for a library, what should you do ?
- *Answer*  (ldai4-stat6250): when I specify an engine for a library, I always specify the file format for files that are stored in the library.


[basic_recipe_for_loading_data_from_remote_Excel_file Week 2 Recipe]



[bonus_advanced_recipe_for_loading_data_from_remote_Excel_file Week 2 Recipe]


