## Week 8 Quiz Questions and Answers

In order to prepare your Week 8 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-8" in your fork of this repo. Then, after all edits have been made/committed, your Week 8 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-8 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 13, Problem 1]
- *Question* (xyin6-stat6250): Where should we put the word "of" if we want mean value of x1,x2,x4, excluding x3?



[Course Textbook Chapter 13, Problem 2]
- *Question* (xyin6-stat6250): Is there any restrictions in the automatic character-to-numeric conversion?
- *Answer* (xyin6-stat6250): It will produce a numeric missing value from any character value that does not conform to standard numeric notation (digits with an optional decimal point, leading sign or scientific notation).



[Course Textbook Chapter 13, Problem 3]
- *Question* (xyin6-stat6250): When choosing the numeric informat in the INPUT function, do we refer to the longest character value?



[Course Textbook Chapter 13, Problem 4]
- *Question* (xyin6-stat6250): What happens if we use the PUT function to create a variable that has not been previously identifies?
- *Answer* (xyin6-stat6250): It will create a character variable whose length is equal to the format width.



[Course Textbook Chapter 13, Problem 5]
- *Question* (xyin6-stat6250): What does the format "date9." represent in the date conversion process?



[Course Textbook Chapter 13, Problem 6]
- *Question* (xyin6-stat6250): What is the most significant difference between SCAN and SUBSTR function?
- *Answer* (xyin6-stat6250): The SUBSTR function is best used when you know the exact position of the string that you want to extract from the character value. By contrast, the SCAN function is best used when you know the order of the words in the character value; the starting position of the words varies and the words are marked by some delimiter.



[Course Textbook Chapter 13, Problem 7]
- *Question* (xyin6-stat6250): In the SUBSTR function, if position =2 and n is omitted, what will happen to the character value?
- *Answer* (xyin6-stat6250): All the remaining characters starting from position 2 will be included in the substring.



[Course Textbook Chapter 13, Problem 10]
- *Question* (xyin6-stat6250): When should we put quotation marks inside the INTNX function?



[recipe_for_isolating_all_duplicates Week 8 Recipe]
- *Question* (xyin6-stat6250): Still confused why both first.school_code and last.school_code equals 1 represents there's no duplicates?



[recipe_for_drop_and_swap Week 8 Recipe]
- *Question* (xyin6-stat6250): What does best12. represent? Is it a default formatting way?


