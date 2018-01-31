## Week 5 Quiz Questions and Answers

In order to prepare your Week 5 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-5" in your fork of this repo. Then, after all edits have been made/committed, your Week 5 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-5 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 5, Problem 1]
- Question (who7-stat6250): What is the advantage of creating a dataset without giving it a temp name?



[Course Textbook Chapter 5, Problem 2]
- Question (who7-stat6250): How can we ensure filerefs update when we move the file?



[Course Textbook Chapter 5, Problem 6]
- Question (who7-stat6250): Is there a max width for the dataset we create?



[Course Textbook Chapter 5, Problem 7]
- Question (who7-stat6250): How can we format the numeric column to only have 2 decimal place?



[Course Textbook Chapter 5, Problem 8]
- Question (who7-stat6250): Can we use operator for character varailbe to add 2 words together?



[Course Textbook Chapter 6, Problem 1]
- Question (who7-stat6250): How is compiling in sas different from other programming language?



[Course Textbook Chapter 6, Problem 2]
- Question (who7-stat6250): What are the most common syntax error?



[Course Textbook Chapter 6, Problem 3]
- Question (who7-stat6250): Are there other ways to create dataset with using the data statement?
- Answer (who7-stat6250): Yes, you can use proc sql to create table as well.



[Course Textbook Chapter 6, Problem 4]
- Question (who7-stat6250): Why is the value o f_N_ set to 1 during the execution phase?



[Course Textbook Chapter 6, Problem 5]
- Question (who7-stat6250): Would a syntax error be counted in the _ERROR_ value?



[Course Textbook Chapter 6, Problem 6]
- Question (who7-stat6250): What are the main limiatations when creating the descriptor portion of the dataset?



[basic_recipe_for_creating_analytic_datasets Week 5 Recipe]
- Question (who7-stat6250): If the number of columns that needed to be removed is larger than the number of columns needed to keep, is it still best practice to use the KEEP statement instead of DROP statement?
- Answer (who7-stat6250): There are 2 views regarding this.  First, it may be wise to use DROP instead of KEEP as it will uses less lines of code.  Second, you may still want to use KEEP as it is a more clear way of showing which columns are actually using.



[adv_recipe_for_creating_analytic_datasets Week 5 Recipe]
- Question (who7-stat6250): Are the command under PROC SQL the same as SQL itself?
- Answer (who7-stat6250): Yes, the commands are the same.


