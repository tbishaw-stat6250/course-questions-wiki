## Week 5 Quiz Questions and Answers

In order to prepare your Week 5 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-5" in your fork of this repo. Then, after all edits have been made/committed, your Week 5 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-5 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 5, Problem 1]
- Question (nshrivastava2-stat6250): Which statements are needed from a SAS data set to a raw data file as it used the INFILE and INPUT statements to create a SAS data set?
- Answer (nshrivastava2-stat6250): We use the FILE and PUT statements from a SAS dataset to to a raw data file. 



[Course Textbook Chapter 5, Problem 2]
- Question (nshrivastava2-stat6250): What is the significant role of LIBNAME and FILENAME statements?
- Answer (nshrivastava2-stat6250): LIBNAME and FILENAME statements are global. Librefs and filerefs remain in effect until you change them, cancel them, or end your SAS session. 



[Course Textbook Chapter 5, Problem 6]
- Question (nshrivastava2-stat6250): When we don't need to specify the LIBNAME?
- Answer (nshrivastava2-stat6250): We do not need to use LIBNAME statement, if we store the data set in a temporary SAS data set or if SAS has automatically assigned the libref for the permanent library.



[Course Textbook Chapter 5, Problem 7]
- Question (nshrivastava2-stat6250): A raw data file is an external text file whose records contain data values that are organized in fields. Is The ruler is not part of the raw data file?
- Answer (nshrivastava2-stat6250): No, The ruler is not part of the raw data file. The file contains fixed fields; i.e values for each variable are in the same location in all records. 



[Course Textbook Chapter 5, Problem 8]
- Question (nshrivastava2-stat6250): What is the function of INFILE statement ?
- Answer (nshrivastava2-stat6250): Identify an external file and to verify the data, it is a good idea to use the OBS= option in the INFILE statement. Adding OBS=n to the INFILE statement enables you to process only records 1 through n, so you can verify that the correct fields are being read before reading the entire data file.



[Course Textbook Chapter 6, Problem 1]
- Question (nshrivastava2-stat6250): How can we use Null INPUT Statement? What it's fuctionality?



[Course Textbook Chapter 6, Problem 2]
- Question (nshrivastava2-stat6250): How SAS Processes the Programs?
- Answer (nshrivastava2-stat6250): You first compile the SAS source program and store the compiled code. Then SAS execute the compiled code, redirecting the input and output as necessary. SAS processes the DATA step through the compilation phase and then stores an intermediate code representation of the program and associated data tables in a SAS file.



[Course Textbook Chapter 6, Problem 3]
- Question (nshrivastava2-stat6250): What are the errors SAS diagnose during compilation phase?
- Answer (nshrivastava2-stat6250): During the compilation phase, SAS can interpret some syntax errors such as misspelled keywords and data set names,unbalanced quotation marks,invalid options. 



[Course Textbook Chapter 6, Problem 4]
- Question (nshrivastava2-stat6250): What are the errors SAS diagnose  in the Execution Phase?



[Course Textbook Chapter 6, Problem 5]
- Question (nshrivastava2-stat6250): What specify the keyword _NULL_ as the data set name to view compilation or execution errors without creating a data set?



[Course Textbook Chapter 6, Problem 6]
- Question (nshrivastava2-stat6250): Making, diagnosing, and resolving errors is part of the process of writing programs. What are the steps to ensure that save of time and hassel?
- Answer(nshrivastava2-stat6250): We need to make sure each SAS statement ends with a semicolon, filenames are spelled correctly, keywords are spelled correctly. 



[basic_recipe_for_creating_analytic_datasets Week 5 Recipe]
- Question (nshrivastava2-stat6250):What retain, keep and drop perform in SAS Progrmaing and What is Program Data Vector(PDV) for SAS dataset?
- Answer (nshrivastava2-stat6250): The RETAIN statement specifies variables whose values are not set to missing at the beginning of each iteration of the DATA step. The KEEP statement specifies variables that are to be included in any data set that is being created and DROP specifies the names of the variables to omit from the output data set. Program Data Vector(PDV)is an area of memory where SAS stores variable values and attributes. It is the PDV that stores an observation as it is being processed in the DATA step.



[adv_recipe_for_creating_analytic_datasets Week 5 Recipe]
- Question (nshrivastava2-stat6250): Can we create new varaibles using PROC SQL? If, yes please give brief explainations.
- Answer (nshrivastava2-stat6250):Variables can be dynamically created in PROC SQL. Dynamically created variables can be given a variable name, label, or neither. If a dynamically created variable is not given a name or a label, it will appear on the report as a column with no column heading.



