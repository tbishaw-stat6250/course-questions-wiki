## Week 6 Quiz Questions and Answers

In order to prepare your Week 6 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-6" in your fork of this repo. Then, after all edits have been made/committed, your Week 6 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-6 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 12, Problem 1]
- *Question* (akrishnamurthy-stat6250): In case of one-to-one reading, what will be the total number of observations in final data set?



[Course Textbook Chapter 12, Problem 2]
- *Question* (akrishnamurthy-stat6250): How does interleaving select data?
- *Answer* (akrishnamurthy-stat6250): Interleaving requires a list of data set names in SET statement with corresponding BY statements.The observations in each BY group are read sequentially in the order listed. The new data set contains all the variables from all the input data sets as well as the total number of records from all the input data sets.



[Course Textbook Chapter 12, Problem 3]
- *Question* (akrishnamurthy-stat6250): What is the difference between APPEND procedure and concatenating datasets?
- *Answer* (akrishnamurthy-stat6250): PROC Append adds the observations of one dataset to the end of a master dataset.Where as,the DATA step creates a new dataset when concatenating.



[Course Textbook Chapter 12, Problem 4]
- *Question* (akrishnamurthy-stat6250): What is the difference between merging datasets and concatenating datasets?



[Course Textbook Chapter 12, Problem 5]
- *Question* (akrishnamurthy-stat6250): How are same named variables handled while merging datasets? Which value takes precedence if both the variables carry different values?
- *Answer* (akrishnamurthy-stat6250):The values of the same named variable in first dataset is overwritten by the value for the same-named variable in second dataset.



[Course Textbook Chapter 12, Problem 7]
- *Question* (akrishnamurthy-stat6250): How to prevent same-named variable from being overwritten ? Can both the same-named variables be retained in the output dataset?



[Course Textbook Chapter 12, Problem 9]
- *Question* (akrishnamurthy-stat6250):How are unmatched observations handled while merging two datasets?



[basic_recipe_for_combining_data_horizontally Week 6 Recipe]
- *Question* (akrishnamurthy-stat6250): Is it necessary for the datasets to be sorted before merging BY a common column?



[adv_recipe_for_combining_data_horizontally Week 6 Recipe]
- *Question* (akrishnamurthy-stat6250): What is the benefit of using PROC SQL over merge statement?


