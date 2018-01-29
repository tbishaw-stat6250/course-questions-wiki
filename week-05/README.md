## Week 5 Quiz Questions and Answers

In order to prepare your Week 5 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-5" in your fork of this repo. Then, after all edits have been made/committed, your Week 5 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-5 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 5, Problem 1]
- *Question* (aamiri2-stat6250): What are the steps in creating a raw data file? How can one identify a raw data file in a SAS statement?



[Course Textbook Chapter 5, Problem 2]
- *Question* (aamiri2-stat6250): What are the differences and similarities between Fileref and Libref?



[Course Textbook Chapter 5, Problem 6]
- *Question* (aamiri2-stat6250): When running an INPUT statement, when are dollar signs ($) used and when is it not needed?
- *Answer* (aamiri2-stat6250): The dollar sign ($) identifies the variable as a character in the columns. It is usually used for characters such as name or sex. It is not used for age because this is already a numeric value so there is no need for the dollar sign.



[Course Textbook Chapter 5, Problem 7]
- *Question* (aamiri2-stat6250): Does the ruler in a raw data file have a maximum limit? Is there another method to find out where individual fields begin and end?



[Course Textbook Chapter 5, Problem 8]
- *Question* (aamiri2-stat6250): Can you use multiple arithmetic operators in an expression? If so, does order of operation automatically apply?
- *Answer* (aamiri2-stat6250): You can use many different arithmetic operations such as division, addition, subtraction, multiplication, and exponentiation. Negative prefixes have priority but then it goes by order of operations and parentheses can be used to control this better.



[Course Textbook Chapter 6, Problem 1]
- *Question* (aamiri2-stat6250): During the compilation phase, SAS scans statements in the DATA step for syntax errors, what are some of the errors that may occur?
- *Answer* (aamiri2-stat6250): Some of the syntax errors that occur during the compilation phase are misspelled keywords or missing keywords, invalid variable names, missing or invalid punctuation, and invalid options.



[Course Textbook Chapter 6, Problem 2]
- *Question* (aamiri2-stat6250): When a syntax error of invalid options occurs, what can be done to correct this error? What precautions can be made to avoid such errors beforehand?



[Course Textbook Chapter 6, Problem 3]
- *Question* (aamiri2-stat6250): After the Data step is compiled, what are the next steps during the execution phase?



[Course Textbook Chapter 6, Problem 4]
- *Question* (aamiri2-stat6250): If _ERROR_ is 1 at the beginning of the execution phase, will it tell is exactly the source of the error?



[Course Textbook Chapter 6, Problem 5]
- *Question* (aamiri2-stat6250): What is the value of the automatic variable _ ERROR_ when there is more than one error? 



[Course Textbook Chapter 6, Problem 6]
- *Question* (aamiri2-stat6250): What happens to the data during the beginning iteration DATA step? What information can be obtain during this step?



[basic_recipe_for_creating_analytic_datasets Week 5 Recipe]
- *Question* (aamiri2-stat6250): What are the differences between RETAIN and KEEP statements?



[adv_recipe_for_creating_analytic_datasets Week 5 Recipe]
- *Question* (aamiri2-stat6250): How can we load our data using PROC SQL?


