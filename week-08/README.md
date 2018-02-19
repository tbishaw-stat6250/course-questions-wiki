## Week 8 Quiz Questions and Answers

In order to prepare your Week 8 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-8" in your fork of this repo. Then, after all edits have been made/committed, your Week 8 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-8 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 13, Problem 1]
- *Question* (aamiri2-stat6250): When calculating averages of multiple variables, what happens to the function argument when you omit the word OF?
- *Answer* (aamiri2-stat6250): The word OF is used when specifying function arguments with a variable list or an array. If the word OF is omitted then the function will be interpreted as a subtraction formulation rather than an average of all variables. Consequently, this gives an incorrect output.



[Course Textbook Chapter 13, Problem 2]
- *Question* (aamiri2-stat6250): What is the difference between the INPUT and PUT function? In which cases should this functions be used?
- *Answer* (aamiri2-stat6250): The INPUT function converts character data into numeric values whereas the PUT function works oppositely and converts numeric data values to character values. Usually these functions are used when one of the variables are needed for calculation.



[Course Textbook Chapter 13, Problem 3]
- *Question* (aamiri2-stat6250): When converting character values to numeric values, how are commas and decimals differentiated in the INPUT function.



[Course Textbook Chapter 13, Problem 4]
- *Question* (aamiri2-stat6250): What are some typical errors that can occur with a PUT function?



[Course Textbook Chapter 13, Problem 5]
- *Question* (aamiri2-stat6250): When using the MDY function, what is the general format for month, date, and year? What is a typical error that can occur with this function?
- *Answer* (aamiri2-stat6250): Normally, month is any number from 1-12, day is any number from 1-31, and year is four or two digits. An error that typically occurs is with the formatting the year. It is recommended to use four digits because this will minimize error. MDY function accepts two digit year values but it is based on the 100-year span from YEARCUTOFF=, so it is likely you will get an year that is not desired.



[Course Textbook Chapter 13, Problem 6]
- *Question* (aamiri2-stat6250): What function can be used to separate and store character values into a new variable?



[Course Textbook Chapter 13, Problem 7]
- *Question* (aamiri2-stat6250): What is the difference between SCAN, SUBSTR, and TRIM functions? Do these functions change the data permanently?



[Course Textbook Chapter 13, Problem 10]
- *Question* (aamiri2-stat6250): For what reasons are UPCASE and LOWCASE used in an INDEX function?



[recipe_for_isolating_all_duplicates Week 8 Recipe]
- *Question* (aamiri2-stat6250): Is there an alternative approach to remove duplicate data and still do a comparison?



[recipe_for_drop_and_swap Week 8 Recipe]
- *Question* (aamiri2-stat6250): When using the drop and swap technique, why is it useful to use high grade?


