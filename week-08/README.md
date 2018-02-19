## Week 8 Quiz Questions and Answers

In order to prepare your Week 8 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-8" in your fork of this repo. Then, after all edits have been made/committed, your Week 8 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-8 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 13, Problem 1]
- *Question* (aacharya4−stat6250): How can we specify a range of values as a function argument in SAS?
- *Answer* (aacharya4−stat6250): In order to specify a range of values as a function argument in SAS, we need to precede the list of variables with keyword 'OF'. Eg: sum(of va1-var10)



[Course Textbook Chapter 13, Problem 2]
- *Question* (aacharya4−stat6250): What function is used to convert numeric variable to character variable? 
- *Answer* (aacharya4−stat6250): In SAS, numeric variable is converted to numeric variable using PUT function. 



[Course Textbook Chapter 13, Problem 3]
- *Question* (aacharya4−stat6250): What is the use of format in PUT and INPUT function?
- *Answer* (aacharya4−stat6250): The use of format signifies what format type is to be used on the original variable type. For eg: In case of INPUT function to convert a character value to numeric, the format must be a character format.



[Course Textbook Chapter 13, Problem 4]
- *Question* (aacharya4−stat6250): What function is used to convert character variable to numeric variable? 
- *Answer* (aacharya4−stat6250): Character variable is converted to numeric variable using INPUT function.



[Course Textbook Chapter 13, Problem 5]
- *Question* (aacharya4−stat6250): What is the default value of the YEARCUTTOFF system option in SAS?
- *Answer* (aacharya4−stat6250): The default value of the YEARCUTTOFF system option in SAS is 1920.



[Course Textbook Chapter 13, Problem 6]
- *Question* (aacharya4−stat6250): What is the use of SCAN function in SAS?
- *Answer* (aacharya4−stat6250): The SCAN function returns the nth word from a character string.



[Course Textbook Chapter 13, Problem 7]
- *Question* (aacharya4−stat6250): What is the best option to extract a character value when its position is known in a character string?
- *Answer* (aacharya4−stat6250): SUBSTR is the best option to extract a character value when its position is known in a character string.



[Course Textbook Chapter 13, Problem 10]
- *Question* (aacharya4−stat6250): What is the use of INDEX function in SAS?
- *Answer* (aacharya4−stat6250): The INDEX function searches for the chaarcter expression in a character string and returns the position of string's first character in its first occurance.



[recipe_for_isolating_all_duplicates Week 8 Recipe]
- *Question* (aacharya4−stat6250): What is the difference of between using proc sort with dupout= option and using first and last variable in by-group processing in data step to remove duplicates in a datset?
- *Answer* (aacharya4−stat6250): In case of using proc sort with dupout= option a new dataset is created with dulpcate rows while using first and last variable in by-group processing outputs all duplicate rows to be isolated for comparison.



[recipe_for_drop_and_swap Week 8 Recipe]
- *Question* (aacharya4−stat6250): what is the default format that is used for in INPUT function with numerical variables having no digits after the decimal place?
- *Answer* (aacharya4−stat6250): "best12." is the default format that is used for in INPUT function with numerical variables having no digits after the decimal place.


