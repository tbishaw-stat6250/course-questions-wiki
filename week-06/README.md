## Week 6 Quiz Questions and Answers

In order to prepare your Week 6 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-6" in your fork of this repo. Then, after all edits have been made/committed, your Week 6 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-6 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 12, Problem 1]
- *Question* (cli19−stat6250): In one-to-one reading, why does the final data set take on the number or rows from the smaller data set being combined?
- *Answer* (cli19−stat6250): Since SAS processes data row by row, the DATA step processing stops when the smaller data set reaches an end-of-file.



[Course Textbook Chapter 12, Problem 2]
- *Question* (cli19−stat6250): Why isn't it necessary to first sort data prior to concatenating data sets?
- *Answer* (cli19−stat6250): SAS checks sequentially if key indicators match in a MERGE statement to combine rows, so sorting the data prior to a merge is required. For concatenating data sets, sorting isn't necessary since SAS essentially stacks the listed data sets and doesn't need to pair data sets by key indicators.



[Course Textbook Chapter 12, Problem 3]
- *Question* (cli19−stat6250): Is it possible to concatenate data sets and keep common variables only?



[Course Textbook Chapter 12, Problem 4]
- *Question* (cli19−stat6250): How does SAS determine the length of different variables when concatenating data sets?
- *Answer* (cli19−stat6250): SAS takes the attribute from the first data set that contains the variable with that attribute. If the greatest length of varaibles is known, it's best to state it (using length or format) to avoid truncation.



[Course Textbook Chapter 12, Problem 5]
- *Question* (cli19−stat6250): When merging two data sets by a key indicator, why do common variables from the second data set supercede the values from the first?



[Course Textbook Chapter 12, Problem 7]
- *Question* (cli19−stat6250): When merging data sets, is there an expedient way to automatically rename variables with the same name to keep variables from both data sets?



[Course Textbook Chapter 12, Problem 9]
- *Question* (cli19−stat6250): What are other methods to keep all observations from data sets being merged by a key indicator?
- *Answer* (cli19−stat6250): This can also be accomplished by using a FULL JOIN in a PROC SQL step.



[basic_recipe_for_combining_data_horizontally Week 6 Recipe]
- *Question* (cli19−stat6250): From which data set being merged are labels kept when it comes to common variables?



[adv_recipe_for_combining_data_horizontally Week 6 Recipe]
- *Question* (cli19−stat6250): How do DATA steps and PROC SQL compare computationally? Is one more intensive than the other?


