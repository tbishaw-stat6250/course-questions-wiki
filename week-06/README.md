## Week 6 Quiz Questions and Answers

In order to prepare your Week 6 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-6" in your fork of this repo. Then, after all edits have been made/committed, your Week 6 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-6 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 12, Problem 1]
- *Question* (xyin6-stat6250): How to determine the order of variable/observation for the new combined dataset?
- *Answer* (xyin6-stat6250): Observations are combined based on their relative position in each data set. That is,
the first observation in one data set is joined with the first observation in the other, and so as the variable order.



[Course Textbook Chapter 12, Problem 2]
- *Question* (xyin6-stat6250): Does SAS automatically sort the variable after "BY"? Or what sequence does it follow?



[Course Textbook Chapter 12, Problem 3]
- *Question* (xyin6-stat6250): If the length of attributes in two datasets are different, how does the concatenated dataset select the length?
- *Answer* (xyin6-stat6250): SAS takes the length from the first data set that contains the variable. The same is true for the label, format, and informat attributes.



[Course Textbook Chapter 12, Problem 4]
- *Question* (xyin6-stat6250): If two data sets do not have common variables, can they still be concatenated?



[Course Textbook Chapter 12, Problem 5]
- *Question* (xyin6-stat6250): What will happen to the output if input data set doesn't have any observations for a particular value of the by-variable?
- *Answer* (xyin6-stat6250): The observation in the output data set contains missing values for the variables that are unique to that input data set



[Course Textbook Chapter 12, Problem 7]
- *Question* (xyin6-stat6250): If we rename the variable in the output, does the original dataset keep the former name or it will also be changed?



[Course Textbook Chapter 12, Problem 9]
- *Question* (xyin6-stat6250): Is it necessary to specify descending order in both DATA and PROC step?



[basic_recipe_for_combining_data_horizontally Week 6 Recipe]
- *Question* (xyin6-stat6250): IS it possible to put more than one variable after BY statement?



[adv_recipe_for_combining_data_horizontally Week 6 Recipe]
- *Question* (xyin6-stat6250): How to specify join condition instead of full join?


