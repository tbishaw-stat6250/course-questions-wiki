## Week 7 Quiz Questions and Answers

In order to prepare your Week 7 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-7" in your fork of this repo. Then, after all edits have been made/committed, your Week 7 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-7 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 10, Problem 2]
- *Question* (jcanfield3-stat6250): Why is the label option needed?
- *Answer* (jcanfield3-stat6250): Without it the data does not know to output the new label within the proc statememt.



[Course Textbook Chapter 10, Problem 6]
- *Question* (jcanfield3-stat6250): Why does capitalization matter for character values?



[Course Textbook Chapter 10, Problem 7]
- *Question* (jcanfield3-stat6250): Are there any other ways to determine/change variable length?



[Course Textbook Chapter 10, Problem 8]
- *Question* (jcanfield3-stat6250): Why do b, c, and d fail to emulate the desired code?
- *Answer* (jcanfield3-stat6250): Option b rewrites type='Fixed' to type='Unknown', because code="1" isn't excluded.  Option C renames all code ^= 1 to '2' and type to 'variable'; the second else command is also invalidated.  In option D, when Code=1 and Type=Fixed then they are rewritten as Code=2 and Type=Variable, else type='Unknown'.



[Course Textbook Chapter 10, Problem 9]
- *Question* (jcanfield3-stat6250): Why does capitalization not matter when referencing variables?



[Course Textbook Chapter 10, Problem 10]
- *Question* (jcanfield3-stat6250): Why does an error occur when you use a drop or keep statement in a proc step?



[Course Textbook Chapter 11, Problem 1]
- *Question* (jcanfield3-stat6250): Is the if statement processed before or after the drop= option?



[Course Textbook Chapter 11, Problem 2]
- *Question* (jcanfield3-stat6250): What is wrong with option B?
- *Answer* (jcanfield3-stat6250): Not only is ordrtime never read, thus invalidating the if statement, but also we are creating the orders dataset rather than reading it.



[Course Textbook Chapter 11, Problem 3]
- *Question* (jcanfield3-stat6250): Is there a way to output the first. and last. variables?



[Course Textbook Chapter 11, Problem 8]
- *Question* (jcanfield3-stat6250): Can you use an end=last option to make the last observation from each "by or class" variable have last=1? 



[Course Textbook Chapter 11, Problem 9]
- *Question* (jcanfield3-stat6250): Is there a way to print how the PDV works in an output?



[basic_recipe_for_combining_data_vertically Week 7 Recipe]
- *Question* (jcanfield3-stat6250): Can I format the id variable before its assigned a value?



[adv_recipe_for_combining_data_vertically Week 7 Recipe]
- *Question* (jcanfield3-stat6250): Why is proc sql not taught at a beginner level if its so much more efficient?


