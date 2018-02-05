## Week 6 Quiz Questions and Answers

In order to prepare your Week 6 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-6" in your fork of this repo. Then, after all edits have been made/committed, your Week 6 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-6 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 12, Problem 1]
- Question (aguenane−stat6250): What are the five methods of combining observations from two or more data sets into a new data set?
- Answer (aguenane-stat6250): They are one-to-one reading, concatenating, appending, interleaving, and match-merging.



[Course Textbook Chapter 12, Problem 2]
- Question (aguenane−stat6250): What is the difference between the interleaving and match-merging methods?



[Course Textbook Chapter 12, Problem 3]
- Question (aguenane−stat6250): What is the difference in the coding between one-to-one matching and concatenating?
- Answer (aguenane-stat6250): With one-to-one matching, you use individual SET statements per data set while with concatenating, you have multiple data sets in one SET statement separated by commas.



[Course Textbook Chapter 12, Problem 4]
- Question (aguenane−stat6250): When can you not concatenate multiple data sets?
- Answer (aguenane-stat6250): Any common variable must have the same type attribute.



[Course Textbook Chapter 12, Problem 5]
- Question (aguenane−stat6250): If you want to merge more than one variable in descending order, how do you code this?



[Course Textbook Chapter 12, Problem 7]
- Question (aguenane−stat6250): If you merge two data sets and two values for a variable are the same, the DATA step overwrites the values of the like-named variable in the first data set; is this overwrite permanent?



[Course Textbook Chapter 12, Problem 9]
- Question (aguenane−stat6250): When using a BY statement, can you specify any of the variables/more than one variable?



[basic_recipe_for_combining_data_horizontally Week 6 Recipe]
- Question (aguenane−stat6250): What is the goal of using a RETAIN statement when merging data sets?



[adv_recipe_for_combining_data_horizontally Week 6 Recipe]
- Question (aguenane−stat6250):What is the (PDV) MEANS ?



