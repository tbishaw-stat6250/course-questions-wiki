## Week 4 Quiz Questions and Answers

In order to prepare your Week 4 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-4" in your fork of this repo. Then, after all edits have been made/committed, your Week 4 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-4 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 7, Problem 3]
Question (asharda-stat6250):What are the different options that can be given to PROC format?
Answer(asharda-stat6250): There are 2 options that can be included with PROC format and they are  
(i)LIBRARY=lbref specifies the libref for a SAS data library to contain a permanent catalog of user-defined formats
(ii)FMTLIB displays a list of all the formats in your catalog, along with descriptions of their values.



[Course Textbook Chapter 7, Problem 4]
Question (asharda-stat6250): What is the beginning and ending of a VALUE statement?
Answer(asharda-stat6250):The VALUE statement begins with the keyword VALUE and ends with a semicolon after all the labels have been defined.



[Course Textbook Chapter 7, Problem 5]
Question (asharda-stat6250): Can a list contain a combination of character and numeric values?.
Answer(asharda-stat6250):A list cannot contain combination of character and numeric values.



[Course Textbook Chapter 7, Problem 6]
Question (asharda-stat6250): What is the maximum number of characters that can be used in a label?.
Answer(asharda-stat6250):256 is the maximum number of characters that can be used in a label.



[Course Textbook Chapter 7, Problem 7]
Question (asharda-stat6250): What is the use of OTHER in a value statement.



[Course Textbook Chapter 7, Problem 8]
Question (asharda-stat6250): Can you place FORMAT statement in either DATA or PROC step?
Answer(asharda-stat6250):Yes ,you can place FORMAT statement in either DATA or PROC step.



[Course Textbook Chapter 8, Problem 1]
Question (asharda-stat6250): When should you use MEANS procedure
Answer(asharda-stat6250):You should use MEANS procedure to calculate statistics such as the mean, sum, minimum, and maximum.



[Course Textbook Chapter 8, Problem 2]
Question (asharda-stat6250): How to specify variales that PROC MEANS analyzes



[Course Textbook Chapter 8, Problem 4]
Question (asharda-stat6250): What is the difference between CLASS and BY processing
Answer(asharda-stat6250):Unlike CLASS processing, BY group processing requires that your data already be indexed or sorted in the order of the BY variables. You might need to run the SORT procedure before using PROC MEANS with a BY group. 



[Course Textbook Chapter 8, Problem 7]
Question (asharda-stat6250): Are there other ways to create a table of frequencies and percentages besides PROC FREQ?



[Course Textbook Chapter 8, Problem 8]
Question (asharda-stat6250): How do you specify variables in PROC FREQ?.



[Course Textbook Chapter 8, Problem 10]
Question (asharda-stat6250): When do you specify NOFREQ option?.



[recipe_for_summarizing_quantitative_values Week 4 Recipe]
Question (asharda-stat6250): Why to use "class" and "var" in PROC MEANS statement?.



[recipe_for_summarizing_qualitative_values Week 4 Recipe]
Question (asharda-stat6250): How is a list used in cross- tabulation?.
Answer(asharda-stat6250):list can be used in a cross-tabulation to stack output.



[recipe_for_temporarily_binning_values Week 4 Recipe]
Question (asharda-stat6250): Can PROC FORMAT statement be used to bin numerical variables into categories
Answer(asharda-stat6250):Yes, a PROC FORMAT statement be used to bin numerical variables into categories.
