## Week 6 Quiz Questions and Answers

In order to prepare your Week 6 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-6" in your fork of this repo. Then, after all edits have been made/committed, your Week 6 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-6 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 12, Problem 1]
- *Question*(kamirneni-stat6250): In one-to-one reading, what happens when data sets have the same variable names?
- *Answer*(kamirneni-stat6250): The values which are read from the last dataset overwrite the values from the earlier datasets.



[Course Textbook Chapter 12, Problem 2]
- *Question*(kamirneni-stat6250): In concatenation, what does SAS do when length of attributes is different in datasets?
- *Answer*(kamirneni-stat6250): In this case, SAS takes length from first data set that contains the variable.



[Course Textbook Chapter 12, Problem 3]
- *Question*(kamirneni-stat6250): In what situations is the FORCE option used in APPEND procedure and other what conditions?



[Course Textbook Chapter 12, Problem 4]
- *Question*(kamirneni-stat6250): Does any case of duplicity arise when interleaving data, if yes, how is it resolved?



[Course Textbook Chapter 12, Problem 5]
- *Question*(kamirneni-stat6250): In match-merging processing, what's the advantage of creating PDV to hold one observation at a time by SAS?



[Course Textbook Chapter 12, Problem 7]
- *Question*(kamirneni-stat6250): What is the process of referencing a variable in the original dataset? 



[Course Textbook Chapter 12, Problem 9]
- *Question*(kamirneni-stat6250): What is the function of FIRST and LAST in processing?



[basic_recipe_for_combining_data_horizontally Week 6 Recipe]
- *Question*(kamirneni-stat6250): What is the difference in working in DATA step of a RETAIN statement between single and multiple datasets?
- *Answer*(kamirneni-stat6250): The difference is that there are multiple origin points for values in mutliple datasets 
used to fill in the PDV for each row to be included in output.



[adv_recipe_for_combining_data_horizontally Week 6 Recipe]
- *Question*(kamirneni-stat6250): What is the data limit beyond which PROC SQL is no longer useful and conventional SAS methods are to be used?


