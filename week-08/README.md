## Week 8 Quiz Questions and Answers

In order to prepare your Week 8 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-8" in your fork of this repo. Then, after all edits have been made/committed, your Week 8 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-8 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 13, Problem 1]
- *Question* (cnguyen77-stat6250): How to specify a variable list in MEAN function?
- *Answer* (cnguyen77-stat6250): When specifying a variable list, be sure to precede the list with the word OF. If you omit the word OF, the function argument might not be interpreted as expected.



[Course Textbook Chapter 13, Problem 2]
- *Question* (cnguyen77-stat6250): What happens when there is a multiplication of character variables and numeric variables in SAS?
- *Answer* (cnguyen77-stat6250): SAS automatically converts the character values to numeric values so that the calculation can occur. Whenever data is automatically converted, a message is written to the SAS log stating that the conversion has occurred.



[Course Textbook Chapter 13, Problem 3]
- *Question* (cnguyen77-stat6250): How to convert character values to numeric values?
- *Answer* (cnguyen77-stat6250): You explicitly convert character values to numeric values by using the INPUT function. Be sure to select an informat that can read the form of the values.



[Course Textbook Chapter 13, Problem 4]
- *Question* (cnguyen77-stat6250): How to convert numeric values to character values?
- *Answer* (cnguyen77-stat6250): You explicitly convert numeric values to character values by using the PUT function. Be sure to select a format that can read the form of the values.



[Course Textbook Chapter 13, Problem 5]
- *Question* (cnguyen77-stat6250): What does the YEAR function do?
- *Answer* (cnguyen77-stat6250): The YEAR function returns a four-digit numeric value that represents the year (for example, 2002).



[Course Textbook Chapter 13, Problem 6]
- *Question* (cnguyen77-stat6250): How to extract words from a character value?
- *Answer* (cnguyen77-stat6250): The SCAN function is used to extract words from a character value when you know the order of the words, when their position varies, and when the words are marked by some delimiter.



[Course Textbook Chapter 13, Problem 7]
- *Question* (cnguyen77-stat6250): When is the best to use SUBSTR function?
- *Answer* (cnguyen77-stat6250): The SUBSTR function is best used when you know the exact position of the substring to extract from the character value. You specify the position to start from and the number of characters to extract.



[Course Textbook Chapter 13, Problem 10]
- *Question* (cnguyen77-stat6250): 



[recipe_for_isolating_all_duplicates Week 8 Recipe]



[recipe_for_drop_and_swap Week 8 Recipe]
