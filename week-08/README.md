## Week 8 Quiz Questions and Answers

In order to prepare your Week 8 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-8" in your fork of this repo. Then, after all edits have been made/committed, your Week 8 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-8 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 13, Problem 1]
- *Question* (cli19−stat6250): Can variables be used as a list in functions in a PROC SQL step?



[Course Textbook Chapter 13, Problem 2]
- *Question* (cli19−stat6250): How does SAS convert character variables to numeric values so that a calculation can be completed?
- *Answer* (cli19−stat6250): A temporary numeric value for each character value is created to complete the calculation. However, the character values of the variable are not replaced.



[Course Textbook Chapter 13, Problem 3]
- *Question* (cli19−stat6250): SAS generates a NOTE in the log when characters are converted to numeric values in order to complete calculations. Does SAS display a message in the log when character values are converted to numeric in an INPUT function?
- *Answer* (cli19−stat6250): No, no conversion messages appear in the SAS log when the INPUT function is used.



[Course Textbook Chapter 13, Problem 4]
- *Question* (cli19−stat6250): How can you determine the format of variables?
- *Answer* (cli19−stat6250): One approach may involve using PROC CONTENTS to see the format of variables in a data set.



[Course Textbook Chapter 13, Problem 5]
- *Question* (cli19−stat6250): What is the benefit to using the MDY(MM,DD,YYYY) to set the date rather than explicitly stating it with 'DDMONYYY'dt?



[Course Textbook Chapter 13, Problem 6]
- *Question* (cli19−stat6250): How does the SCAN function work if a string contains multiple commas, or delimiters?



[Course Textbook Chapter 13, Problem 7]
- *Question* (cli19−stat6250): The SUBSTR function counts the index from left to right. Is it possible to start the count from right to left to capture the last x values in a string?



[Course Textbook Chapter 13, Problem 10]
- *Question* (cli19−stat6250): What value does the INDEX function return if the sough after string is not found?
- *Answer* (cli19−stat6250): The INDEX function returns the position of the string's first character. If the string is not found it returns a value of 0.



[recipe_for_isolating_all_duplicates Week 8 Recipe]
- *Question* (cli19−stat6250): How does the dupout= option in PROC SORT process data differently than using FIRST. and LAST.?



[recipe_for_drop_and_swap Week 8 Recipe]
- *Question* (cli19−stat6250): What other options can be specified in the COMPRESS function to remove unwanted characters, numbers, etc. from values of a variable?


