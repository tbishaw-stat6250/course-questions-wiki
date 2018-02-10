## Week 6 Quiz Questions and Answers

In order to prepare your Week 6 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-6" in your fork of this repo. Then, after all edits have been made/committed, your Week 6 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-6 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 12, Problem 1]- Question (ljiang11−stat6250): Would the second SET statement rewrite the first SET statement?
- Answer (ljiang11−stat6250): Yes.



[Course Textbook Chapter 12, Problem 2]
- Question (ljiang11−stat6250): By putting BY statement here, data will read as the BY variable's order instead of SET data order?



[Course Textbook Chapter 12, Problem 3]
- Question (ljiang11−stat6250): Why is there missing values?
- Answer (ljiang11−stat6250): Because there are no common columns, SAS will generate missing values for the new variables merged into the dataset.



[Course Textbook Chapter 12, Problem 4]
- Question (ljiang11−stat6250): What does concatenate mean?
- Answer (ljiang11−stat6250): It means to combine two datasets vertically.



[Course Textbook Chapter 12, Problem 5]
- Question (ljiang11−stat6250): Why the value of age in the 2nd dataset overwrite that from the 1st dataset?
- Answer (ljiang11−stat6250): The order of the datasets after MERGE statement determines the subsequent dataset can overwrite the 1st dataset.



[Course Textbook Chapter 12, Problem 7]
- Question (ljiang11−stat6250): What does RENAME= do?



[Course Textbook Chapter 12, Problem 9]
- Question (ljiang11−stat6250): What happens to the observations with same ID?



[basic_recipe_for_combining_data_horizontally Week 6 Recipe]
- Question (ljiang11−stat6250): When combining columns from two datasets, why do we want to convert the varaibles from text to numeric?



[adv_recipe_for_combining_data_horizontally Week 6 Recipe]
- Question (ljiang11−stat6250): Why would renaming data name in PROC SQL can minimize the amount of missing data?





