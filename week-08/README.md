## Week 8 Quiz Questions and Answers

In order to prepare your Week 8 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-8" in your fork of this repo. Then, after all edits have been made/committed, your Week 8 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-8 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 13, Problem 1]
- *Question* (jcanfield3-stat6250): What is another way to calculate this mean?
- *Answer* (jcanfield3-stat6250): This can be done by writing 'mean(var1, var2, var3, var4);'.



[Course Textbook Chapter 13, Problem 2]
- *Question* (jcanfield3-stat6250): How does SAS identify variables that can be converted to numeric?



[Course Textbook Chapter 13, Problem 3]
- *Question* (jcanfield3-stat6250): Why do we need separate Put and Input functions rather than one that does both? 



[Course Textbook Chapter 13, Problem 4]
- *Question* (jcanfield3-stat6250): Is there ever a situation where a variable cannot be converted back to its original data type after transformation?  (Ex a numeric converted to char, that cannot be converted back to a numeric)



[Course Textbook Chapter 13, Problem 5]
- *Question* (jcanfield3-stat6250): Is the MDY function capable of handling 5 digit years?



[Course Textbook Chapter 13, Problem 6]
- *Question* (jcanfield3-stat6250): Why is option d not a valid answer?
- *Answer* (jcanfield3-stat6250): While option D does produce the correct value for this specific value, it does not provide the correct value for all values of this format. (Ex. Santa Barbara, CA would result in State = 'A,') 



[Course Textbook Chapter 13, Problem 7]
- *Question* (jcanfield3-stat6250): What happens when you do not specify the number of values to extract when using substr?



[Course Textbook Chapter 13, Problem 10]
- *Question* (jcanfield3-stat6250): How would I make sure the function finds the word 'walnut' instead of the string?



[recipe_for_isolating_all_duplicates Week 8 Recipe]
- *Question* (jcanfield3-stat6250): If the data is presorted is the 'by statement' needed when forming the dups dataset?



[recipe_for_drop_and_swap Week 8 Recipe]
- *Question* (jcanfield3-stat6250): What does the 'kd' option stand for?
- *Answer* (jcanfield3-stat6250): It is actually two options, k "keeps the characters in the list instead of removing them" and d "adds digits to the list of characters."


