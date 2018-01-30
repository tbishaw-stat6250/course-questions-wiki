## Week 5 Quiz Questions and Answers

In order to prepare your Week 5 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-5" in your fork of this repo. Then, after all edits have been made/committed, your Week 5 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-5 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 5, Problem 1]
- *Question* (jbettonville-stat6250): How would one correctly write the path for a filename in a Unix/Linux/macOS environment?



[Course Textbook Chapter 5, Problem 2]
- *Question* (jbettonville-stat6250): Do changes made to a file that is designated by a fileref change the raw file itself, or only the object that has been created from the file in the SAS session?



[Course Textbook Chapter 5, Problem 6]
- *Question* (jbettonville-stat6250): In the example shown in this problem, why would we use a dollar sign after 'ID'? In this case, isn't ID a numeric variable, and therefore should not be cast as a character variable?
- *Answer* (jbettonville-stat6250): While it is not made explicit in the example, the ID fields are not sequential, nor are any values beyond the four shown included; if other ID values contained characters, it would be appropriate to cast the ID field as a character variable.



[Course Textbook Chapter 5, Problem 7]
- *Question* (jbettonville-stat6250): Can multiple variables contain the same column values in an input statement, or can each column only be used once?



[Course Textbook Chapter 5, Problem 8]
- *Question* (jbettonville-stat6250): Does SAS support iterative operators that are common in other programming languages? (i.e. ++ to increment a variable, -- to decrement)



[Course Textbook Chapter 6, Problem 1]
- *Question* (jbettonville-stat6250): How can we access the data set descriptor to find out more information about what is created during the DATA step?
- *Answer* (jbettonville-stat6250): We can use a PROC CONTENTS statement to reference the data set descriptor. The following example of this can be found at http://support.sas.com/resources/papers/proceedings10/069-2010.pdf:
proc contents data=‟libref‟.dataset; run;



[Course Textbook Chapter 6, Problem 2]
- *Question* (jbettonville-stat6250): What procedures should be used to detect errors that are not syntax errors, so that the code will run but may not produce the desired result?



[Course Textbook Chapter 6, Problem 3]
- *Question* (jbettonville-stat6250): Under what circumstances might we want to execute the DATA step more or less than once per record in the input file?



[Course Textbook Chapter 6, Problem 4]
- *Question* (jbettonville-stat6250): When the DATA step encounters an error, does the \_ERROR\_ variable increment to keep a running total of the number of errors that are encountered while processing the data file, or does it reset after each iteration of the DATA step?



[Course Textbook Chapter 6, Problem 5]
- *Question* (jbettonville-stat6250): If the \_ERROR\_ variable resets after each iteration of the DATA step, what is the purpose of including it?
- *Answer* (jbettonville-stat6250): One example might be for the purpose of debugging SAS code with a PUT statement that outputs the record number given by \_N\_ along with the \_ERROR\_ variable so that it can be determined if SAS received an error on a given record.



[Course Textbook Chapter 6, Problem 6]
- *Question* (jbettonville-stat6250): What is the underlying mechanism by which SAS knows to stop executing the DATA step when it finishes operating on the last record in a file?



[basic_recipe_for_creating_analytic_datasets Week 5 Recipe]
- *Question* (jbettonville-stat6250): Under what circumstances might we want to have different values included in the KEEP and RETAIN statements in a DATA step?



[adv_recipe_for_creating_analytic_datasets Week 5 Recipe]
- *Question* (jbettonville-stat6250): Why does PROC SQL require a QUIT statement at the end instead of a RUN statement?


