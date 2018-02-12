## Week 7 Quiz Questions and Answers

In order to prepare your Week 7 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-7" in your fork of this repo. Then, after all edits have been made/committed, your Week 7 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-7 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 10, Problem 2]
- *Question* (cli19-stat6250): How can variable labels and formats be changed? 
- *Answer* (cli19-stat6250): Variable labels and formats can be temporarily changed in PROC steps or permanently changed in DATA steps.



[Course Textbook Chapter 10, Problem 6]
- *Question* (cli19-stat6250): When recoding variables using IF-THEN statements, would it be better to create a new variable rather than writing over an existing variable?



[Course Textbook Chapter 10, Problem 7]
- *Question* (cli19-stat6250): What happens if the length of proceeding observations is longer than the variable's first reference in the DATA step?
- *Answer* (cli19-stat6250): This results in WARNING outputs in the log and truncation of observations with that have longer length than what is defined for that variable.



[Course Textbook Chapter 10, Problem 8]
- *Question* (cli19-stat6250): How does writing separate IF statements differ from IF-ELSE statements for mutually exclusive conditions?
- *Answer* (cli19-stat6250): Utilizing IF-ELSE statements for mutually exclusive conditions can save computation time compared to separate IF statements. Rather than stepping through each IF statement is true or not, IF-ELSE tells SAS to stop and move to the next observation once it encounters a true statement.



[Course Textbook Chapter 10, Problem 9]
- *Question* (cli19-stat6250): Does the order of the length statement in a DATA step have any affect on the output data set?



[Course Textbook Chapter 10, Problem 10]
- *Question* (cli19-stat6250): How does syntax differ when dropping, keeping, or renaming variables in DATA steps versus PROC steps?



[Course Textbook Chapter 11, Problem 1]
- *Question* (cli19-stat6250): What is the purpose of specifying DROP or KEEP variables in the SET statement?



[Course Textbook Chapter 11, Problem 2]
- *Question* (cli19-stat6250): What does the program data vector (PDV) look like when statements in a DATA step reference variables that are not present in the data set?



[Course Textbook Chapter 11, Problem 3]
- *Question* (cli19-stat6250): What are other potential uses for FIRST. and LAST. statements?



[Course Textbook Chapter 11, Problem 8]
- *Question* (cli19-stat6250): How can LAST. be combined with other statements to get the last observation with respect to a specific variable?



[Course Textbook Chapter 11, Problem 9]
- *Question* (cli19-stat6250): Why are there no observations at the start of DATA step processing?



[basic_recipe_for_combining_data_vertically Week 7 Recipe]
- *Question* (cli19-stat6250): 



[adv_recipe_for_combining_data_vertically Week 7 Recipe]
- *Question* (cli19-stat6250): 


