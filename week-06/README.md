## Week 6 Quiz Questions and Answers

In order to prepare your Week 6 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-6" in your fork of this repo. Then, after all edits have been made/committed, your Week 6 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-6 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 12, Problem 1]
- *Question* (jbettonville-stat6250): Can more than two SET statements be used in a single DATA step to combine records from more than two data sets?
- *Answer* (jbettonville-stat6250): Yes, multiple data sets can be combined at once.



[Course Textbook Chapter 12, Problem 2]
- *Question* (jbettonville-stat6250): When using BY to interleave multiple data sets, can we apply the DESCENDING keyword to change the order in which the resulting data set is sorted?



[Course Textbook Chapter 12, Problem 3]
- *Question* (jbettonville-stat6250): Can data be sorted in the same step as it is concatenated (perhaps by using a BY statement), or does sorting require a separate step?



[Course Textbook Chapter 12, Problem 4]
- *Question* (jbettonville-stat6250): Is it possible to exclude specific variables while concatenating two or more data sets?



[Course Textbook Chapter 12, Problem 5]
- *Question* (jbettonville-stat6250): In the example provided in this problem, how would we keep Age variables from both data sets when merging on the SSN variable?
- *Answer* (jbettonville-stat6250): In the MERGE statement, after the name of the data set containing the variable for which the name should be change, add a RENAME= option, as in (rename=(Age=LowerAge)) to change the Age variable in the second data set to a variable called LowerAge in the resulting output data set.



[Course Textbook Chapter 12, Problem 7]
- *Question* (jbettonville-stat6250): Can data combinations such as the examples listed in this chapter also be completed using PROC SQL statements?



[Course Textbook Chapter 12, Problem 9]
- *Question* (jbettonville-stat6250): If the Name variables were not the same for each ID variable in these data sets, which value of Name would the resulting data set take for each ID?
- *Answer* (jbettonville-stat6250): If the ID variable for both data sets matched but the Name variable in each data set was different for that ID number, the resulting data set would take on the Name variable of the second data set containing the given ID, because the PDV would take the second Name variable and overwrite the first Name variable before adding the new record to the output data set.



[basic_recipe_for_combining_data_horizontally Week 6 Recipe]
- *Question* (jbettonville-stat6250): Do KEEP statements have to list variables in the same order as RETAIN statements?



[adv_recipe_for_combining_data_horizontally Week 6 Recipe]
- *Question* (jbettonville-stat6250): When using PROC SQL to match-merge data sets, do the data sets first need to be sorted by the variables on which they are to be merged, as they do when performing a match-merge with a DATA step?
