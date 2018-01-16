
## Week 3 Quiz Questions and Answers

In order to prepare your Week 3 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-3" in your fork of this repo. Then, after all edits have been made/committed, your Week 3 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-3 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 3, Problem 1]
- *Question* (jbettonville-stat6250): The text mentions that it is a "good idea" to add a RUN statement after every DATA or PROC step; does this phrasing suggest that there are circumstances under which the absence of a RUN statement after a DATA or PROC step would not cause the program to fail?
- *Answer* (jbettonville-stat6250): If there is another PROC or DATA step after the PROC or DATA step that does not have a RUN statement, the second statement will execute. However, if there is no RUN statement at the end of the final PROC or DATA step, the final step will continue to run.



[Course Textbook Chapter 3, Problem 2]
- *Question* (jbettonville-stat6250): Why should we revise the program before clearing the log and resubmitting a program that had a spelling error?
- *Answer* (jbettonville-stat6250): The textbook does not specify, but I imagine it would be useful to still have access to the log from the failed program so that we can verify which parts of the program were incorrect.



[Course Textbook Chapter 3, Problem 3]
- *Question* (jbettonville-stat6250): In longer programs that involve several SAS statements, is it difficult to detect the location of a syntax error? What about detecting errors in which the syntax is accurate but the command does not produce the desired result, and the resulting output causes an error to occur in a later statement?



[Course Textbook Chapter 3, Problem 4]
- *Question* (jbettonville-stat6250): Does SAS produce "warnings" instead of errors when a statement runs but produces a result that may not be what the author of the statement intended?



[Course Textbook Chapter 3, Problem 5]
- *Question* (jbettonville-stat6250): Is SAS backward compatible with programs written in previous versions of SAS? Will older SAS programs cause syntax errors when run in SAS 9.4?



[Course Textbook Chapter 3, Problem 6]
- *Question* (jbettonville-stat6250): Besides adding KEYLABEL in a PROC command, what are some other examples of invalid options applied to SAS statements (especially ones that occur often in programs written by new SAS learners)?



[Course Textbook Chapter 3, Problem 7]
- *Question* (jbettonville-stat6250): In the answer to this question it mentions that this is a common and interpretable error; does this mean that DAT will be interpreted as DATA in a SAS statement and run correctly?



[Course Textbook Chapter 3, Problem 10]
- *Question* (jbettonville-stat6250): Is there any circumstance under which it would be preferable for a RUN statement to not occur at the end of a PROC or DATA step?



[Course Textbook Chapter 4, Problem 1]
- *Question* (jbettonville-stat6250): What happens if you do not include NOOBS in the PROC statement and do not specify an ID for the output?



[Course Textbook Chapter 4, Problem 3]
- *Question* (jbettonville-stat6250): Is there a way of specifying case insensitive values in a WHERE statement?



[Course Textbook Chapter 4, Problem 4]
- *Question* (jbettonville-stat6250): When sorting by a variable, how do we specify the direction (ascending or descending) of the sort order?



[Course Textbook Chapter 4, Problem 7]
- *Question* (jbettonville-stat6250): Assuming that the BY statement is included in PROC SORT, if an OUT option is not specified, does PROC SORT sort the data in place? (i.e. is the data altered if an OUT option is not specified?)



[Course Textbook Chapter 4, Problem 9]
- *Question* (jbettonville-stat6250): What is the functional difference between "eq" and =, or "le" and <=? Can they be used interchangeably?
- *Answer* (jbettonville-stat6250): According to the textbook page 124-125, comparison operators such as these can be used interchangeably in WHERE statements.



[Course Textbook Chapter 4, Problem 10]
- *Question* (jbettonville-stat6250): In data sets with a large number of columns, are there any shortcuts for displaying several columns without specifying the name of each variable? Is it possible to select ranges of columns to display?



[recipe_to_check_for_duplicates Week 3 Recipe]
- *Question* (jbettonville-stat6250):



[recipe_for_sorting_data Week 3 Recipe]
- *Question* (jbettonville-stat6250):



[recipe_for_printing_values Week 3 Recipe]
- *Question* (jbettonville-stat6250):
