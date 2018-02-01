## Week 5 Quiz Questions and Answers

In order to prepare your Week 5 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-5" in your fork of this repo. Then, after all edits have been made/committed, your Week 5 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-5 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 5, Problem 1]
- *Question* (aacharya4−stat6250): To read a external raw data file, what are the instructions that DATA step must provide?
- *Answer* (aacharya4−stat6250):Location of the external file, name of new SAS data set, reference to locate external file, description of data values.



[Course Textbook Chapter 5, Problem 2]
- *Question* (aacharya4−stat6250): Are LIBNAME and FILNENAME statements global in SAS?
- *Answer* (aacharya4−stat6250): Yes, LIBNAME and FILNENAME statements are global in SAS.



[Course Textbook Chapter 5, Problem 6]
- *Question* (aacharya4−stat6250): What is the purpose of the INPUT statement in SAS?
- *Answer* (aacharya4−stat6250): The input statement creates variables in the SAS dataset as per the names, types and number of fields as mentioned in the INPUT statement.



[Course Textbook Chapter 5, Problem 7]
- *Question* (aacharya4−stat6250): How can we distinguish between a character variable and numeric variable in INPUT statement?
- *Answer* (aacharya4−stat6250): The character variables are followed by a '$' in INPUT statements while numeric variables are not.



[Course Textbook Chapter 5, Problem 8]
- *Question* (aacharya4−stat6250): What is used as an assignment operator in SAS?
- *Answer* (aacharya4−stat6250): The '=' is used as an assignment operator in SAS.



[Course Textbook Chapter 6, Problem 1]
- *Question* (aacharya4−stat6250): What are the automatic variables of Program Data Vector (PDV)?



[Course Textbook Chapter 6, Problem 2]
- *Question* (aacharya4−stat6250): What constitutes syntax errors that are checked during compilation phase?
- *Answer* (aacharya4−stat6250): Synatax error include invalid variable names/options, missing or invalid punctuation, missing or misspelled words.



[Course Textbook Chapter 6, Problem 3]
- *Question* (aacharya4−stat6250): What is the difference when DATA step reads data raw data as compared to reading from a SAS dataset?
- *Answer* (aacharya4−stat6250): When DATA step reads data raw data, SAS reads each record of the data in an input buffer as compared to SAS dataset, in that case SAS reads directly into Program Data Vector.



[Course Textbook Chapter 6, Problem 4]
- *Question* (aacharya4−stat6250): What happens to the automatic variable 'N' of program data vector with each iteration of the DATA step?
- *Answer* (aacharya4−stat6250): With each iteration of the DATA step, the automatic variable 'N' is increamented by 1.



[Course Textbook Chapter 6, Problem 5]
- *Question* (aacharya4−stat6250): What is the default value of automatic variable 'ERROR' of Program Data Vector(PDV)? 
- *Answer* (aacharya4−stat6250): The default value of 'ERROR' variable of PDV is 0. This indicates no error, which changes to 1 in case error occurs in data execution.



[Course Textbook Chapter 6, Problem 6]
- *Question* (aacharya4−stat6250): When is descriptor information created during compilation phase of SAS program?



[basic_recipe_for_creating_analytic_datasets Week 5 Recipe]
- *Question* (aacharya4−stat6250): What is the purpose of keeping the same set of columns in the retain and keep statement?
 


[adv_recipe_for_creating_analytic_datasets Week 5 Recipe]
- *Question* (aacharya4−stat6250): What is the difference between loading data using PROC SQL statement instead of using DATA step using RETAIN and KEEP statements?
- *Answer* (aacharya4−stat6250): When PROC SQL statement is used to load data, it loads all records of a dataset into the memory from the memory at one go. In case of DATA step, records are loaded into the memory one by one from disk.


