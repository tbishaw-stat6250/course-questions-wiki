
## Week 3 Quiz Questions and Answers

In order to prepare your Week 3 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-3" in your fork of this repo. Then, after all edits have been made/committed, your Week 3 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-3 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 3, Problem 1]
Question (xyin6-stat6250): As the example shows, the statement can begin anywhere on a line, so what does "indent statements within a step" mean? 


[Course Textbook Chapter 3, Problem 2]
Question (xyin6-stat6250): How to recall the error statements if we are using the Program Editor window?
Answer (xyin6-stat6250): you can recall submitted statements by issuing the RECALL command or by selecting **Run→Recall Last Submit**, or we can just edit them in the code editing window.

[Course Textbook Chapter 3, Problem 3]
Question (xyin6-stat6250): Can we just simply add a quotation mark can solve the problem in the warning message?
Answer (xyin6-stat6250): No, it usually **DOES NOT** solve the problem, SAS still considers the quotation marks to be unbalanced. We have to cancel the statements then resubmitting.
 
[Course Textbook Chapter 3, Problem 4]
Question (xyin6-stat6250): Do syntax errors and data errors always appear in the Log window with explanation of the error?
Answer (xyin6-stat6250): Yes, problems with your statements or data might not be evident when you look at results in the Output window. Therefore, it is important to review the messages in the Log window each time you submit a SAS program.

[Course Textbook Chapter 3, Problem 5]
Question (xyin6-stat6250): If the Log window indicates the procedure was not found, will any output being produced still?


[Course Textbook Chapter 3, Problem 6]
Question (xyin6-stat6250): When I remove or replace the invalid option, will SAS run the whole program over again or just start from the error statement I corrected?


[Course Textbook Chapter 3, Problem 7]
Question (xyin6-stat6250): How to user Enhanced Editor for easier finding and checking syntax error?


[Course Textbook Chapter 3, Problem 10]
Question (xyin6-stat6250): If missing a RUN statement to end the DATA step, will the previous steps being executed? Or are these steps independent from each other?


[Course Textbook Chapter 4, Problem 1]
Question (xyin6-stat6250): Does ID statement and VAR statement share the same function in isting output?


[Course Textbook Chapter 4, Problem 3]
Question (xyin6-stat6250): Can I also use IN operator for selecting multiple numeric values? Is the quote sign required?


[Course Textbook Chapter 4, Problem 4]
Question (xyin6-stat6250): How can I sort on multiple variables in one statement?


[Course Textbook Chapter 4, Problem 7]
Question (xyin6-stat6250): If missing a BY statement in PROC SORT, will the data set still printed if followed by PROC PRINT?


[Course Textbook Chapter 4, Problem 9]
Question (xyin6-stat6250): Does parentheses help deciding the order of compound expressions being evaluated?


[Course Textbook Chapter 4, Problem 10]
Question (xyin6-stat6250): Is it mandatory to specify equal sign in the DATA= after PROC PRINT?


[recipe_to_check_for_duplicates Week 3 Recipe]
Question (xyin6-stat6250): If three variables (County_code, District_code and School_code) are followed by the By statement, will that three being sorted all together? (I thought only one variable can be sorted each time)


[recipe_for_sorting_data Week 3 Recipe]
Question (xyin6-stat6250): Does the character after out= option have specific requirements? Can it be anyname?


[recipe_for_printing_values Week 3 Recipe]
Question (xyin6-stat6250):Is the ID statement just for idetifying row labels for the variable?


