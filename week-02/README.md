
## Week 2 Quiz Questions and Answers

In order to prepare your Week 2 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-2" in your fork of this repo. Then, after all edits have been made/committed, your Week 2 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-2 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 1, Problem 1]
- *Question* (cli19−stat6250): How can we view a summary or overview of a dataset that includes the number of observations or the number of variables? 
- *Answer* (cli19−stat6250): The PROC CONTENTS procedure in SAS can allow us a general overview of what we can expect to see in our dataset specified.



[Course Textbook Chapter 1, Problem 2]
- *Question* (cli19−stat6250): Can procedures be combined to decrease the number of steps to be processed?



[Course Textbook Chapter 1, Problem 3]
- *Question* (cli19−stat6250): What happens when a variable that contains a mix of character/numeric observations is formatted as numeric?
- *Answer* (cli19−stat6250): The variable assumes null values for observations that are not completely numeric.



[Course Textbook Chapter 1, Problem 4]
- *Question* (cli19−stat6250): Why are missing values different for character (' ') and numeric (.) variables?



[Course Textbook Chapter 1, Problem 5]
- *Question* (cli19−stat6250): Are variable names case-sensitive?
- *Answer* (cli19−stat6250): No, SAS is not a case-sensitive program (e.g. variable Policy, POLICY, PolIcY, etc. are the same).



[Course Textbook Chapter 1, Problem 8]
- *Question* (cli19−stat6250): When is it appropriate to change variable length? Does SAS automatically adjust for where observations in a dataset have length greater than 8 bytes?



[Course Textbook Chapter 2, Problem 3]
- *Question* (cli19−stat6250): What are the benefits to specifying YEARCUTOFF?



[Course Textbook Chapter 2, Problem 7]
- *Question* (cli19−stat6250): Is it possible to reference multiple SAS data sets in a single data step? If so, how?



[Course Textbook Chapter 2, Problem 8]
- *Question* (cli19−stat6250): Does the YEARCUTOFF option have additional options to incease the time span to over 100 years?



[Course Textbook Chapter 2, Problem 9]
- *Question* (cli19−stat6250): How can we view the working directory or file path we would like our librefs to point to?



[basic_recipe_for_loading_data_from_remote_Excel_file Week 2 Recipe]
- *Question* (cli19−stat6250): How does SAS know how to format data imported from external files?



[bonus_advanced_recipe_for_loading_data_from_remote_Excel_file Week 2 Recipe]
- *Question* (cli19−stat6250): Why do only some macro functions in SAS require a "%" to invoke a function? And when do built-in SAS functions need to be invoked with %sysfunc()?


