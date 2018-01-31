## Week 4 Quiz Questions and Answers

In order to prepare your Week 4 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-4" in your fork of this repo. Then, after all edits have been made/committed, your Week 4 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-4 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 7, Problem 3]
− *Question* (xyin6-stat6250): When should we use VALUE statement?
- *Answer* (xyin6-stat6250): To define a format for displaying one or more values for a specific output.



[Course Textbook Chapter 7, Problem 4]
− *Question* (xyin6-stat6250): What will happen if I just format part of a variable's values, not all of them?
- *Answer* (xyin6-stat6250): Those that are not listed in the VALUE statement are printed as they appear in the SAS dataset, (in the original format of characters/numbers)



[Course Textbook Chapter 7, Problem 5]
− *Question* (xyin6-stat6250): When I use LOW and HIGH keywords to specify the lower and upper limits, how to deal with missing value?
- *Answer* (xyin6-stat6250): The keyword OTHER can be used to lable missing values, and we can label it 'unknown'.



[Course Textbook Chapter 7, Problem 6]
− *Question* (xyin6-stat6250): WHen to use two single quotation marks in the label?



[Course Textbook Chapter 7, Problem 7]
− *Question* (xyin6-stat6250): How to difine several formats in one proc format statement?



[Course Textbook Chapter 7, Problem 8]
− *Question* (xyin6-stat6250): Do we have to reference the location of the format cataloh each time in the DATA pr PROC step?



[Course Textbook Chapter 8, Problem 1]
− *Question* (xyin6-stat6250): How to specify output statistics, only include one or two statistics?
- *Answer* (xyin6-stat6250): use the sub-statement statistic-keywords to specify the statistics to compute.



[Course Textbook Chapter 8, Problem 2]
− *Question* (xyin6-stat6250): What if we want to add a number range of variables?



[Course Textbook Chapter 8, Problem 4]
− *Question* (xyin6-stat6250): Is OUT= option necessary in sorting data sets when we try to enable group processing?



[Course Textbook Chapter 8, Problem 7]
− *Question* (xyin6-stat6250): How many columns are there in the one-way table produced by PROC FREQ by default?



[Course Textbook Chapter 8, Problem 8]
− *Question* (xyin6-stat6250): What kind of variable is unsuitable for PROC FREQ processing and why?



[Course Textbook Chapter 8, Problem 10]
− *Question* (xyin6-stat6250): What is NOFREQ, NOROW, and NOCO options?



[recipe_for_summarizing_quantitative_values Week 4 Recipe]
− *Question* (xyin6-stat6250): Should we use keyword "other" to define missing values or just define a specific name as the video shown?



[recipe_for_summarizing_qualitative_values Week 4 Recipe]
− *Question* (xyin6-stat6250): How is MISSING NOFREQ, NOROW NOCO option different from directly apply them after "/"?



[recipe_for_temporarily_binning_values Week 4 Recipe]
− *Question* (xyin6-stat6250): How to permanently associate a format with a variable in the DATA step?


