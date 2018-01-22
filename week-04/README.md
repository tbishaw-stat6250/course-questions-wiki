## Week 4 Quiz Questions and Answers

In order to prepare your Week 4 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-4" in your fork of this repo. Then, after all edits have been made/committed, your Week 4 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-4 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 7, Problem 3]
- *Question* (aamiri2-stat6250): While creating a format with a VALUE statement, why is it important to have the correct format in the beginning and ending statements?



[Course Textbook Chapter 7, Problem 4]
- *Question* (aamiri2-stat6250): How will we be able to use the values assigned to each variable during the analysis? Are values easier to use as compared to the actual variable name?



[Course Textbook Chapter 7, Problem 5]
- *Question* (aamiri2-stat6250): Are there any differences in formatting a range VALUE statement between numeric and character values? 



 [Course Textbook Chapter 7, Problem 6]
- *Question* (aamiri2-stat6250): What is the result of going over the character limit in a label?



[Course Textbook Chapter 7, Problem 7]
- *Question* (aamiri2-stat6250): The textbook mentions you can use the keyword OTHER to label a missing value, are there any other keywords that can have the same function?



 [Course Textbook Chapter 7, Problem 8]
- *Question* (aamiri2-stat6250): What happens when you place FORMAT in a PROC step? What is the difference between the DATA step?



 [Course Textbook Chapter 8, Problem 1]
- *Question* (aamiri2-stat6250): Can you obtain specific descriptive statistics of certain variables in a dataset?



[Course Textbook Chapter 8, Problem 2]
- *Question* (aamiri2-stat6250): Is there a way to limit the descriptive statistics so we can only have the minimum and maximum?
- *Answer* (aamiri2-stat6250): To specify a statistic you can use a PROC MEANS statement and use the specific keywords like MINIMUM and MAXIMUM to get the descriptive statistics of only that.



 [Course Textbook Chapter 8, Problem 4]
- *Question* (aamiri2-stat6250): What is the difference between BY and CLASS?
- *Answer* (aamiri2-stat6250): BY processing differs from CLASS because it requires your data to be sorted in the order of the BY variable, unlike CLASS which processes differently. They also both have different layouts of group results.



[Course Textbook Chapter 8, Problem 7]
- *Question* (aamiri2-stat6250): In which situation would we create a table of frequencies? What can we learn about our dataset with this information?



[Course Textbook Chapter 8, Problem 8]
- *Question* (aamiri2-stat6250): Why do frequency distributions work best with variables that contain categorical values?



[Course Textbook Chapter 8, Problem 10]
- *Question* (aamiri2-stat6250): What is the benefit of creating a two-way frequency table as compared to a one-way frequency table?



[recipe_for_summarizing_quantitative_values Week 4 Recipe]
- *Question* (aamiri2-stat6250): What is the difference between PROC MEANS and PROC FREQ? What is the default format of PROC FREQ?



[recipe_for_summarizing_qualitative_values Week 4 Recipe]
- *Question* (aamiri2-stat6250): What does cross tabulation mean and what are the benefits of using it?
- *Answer* (aamiri2-stat6250): Cross tabulation is one of the tools used to analyze the categorical data between one or more variables. This provides a way to analyze and compare the results for one or more variable with the results of another. It helps you understand the relationships within the data.



[recipe_for_temporarily_binning_values Week 4 Recipe]
- *Question* (aamiri2-stat6250): When are appropriate scenarios when we would need to roll-up/bin values?


