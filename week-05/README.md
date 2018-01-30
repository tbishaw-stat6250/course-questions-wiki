## Week 5 Quiz Questions and Answers

In order to prepare your Week 5 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-5" in your fork of this repo. Then, after all edits have been made/committed, your Week 5 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-5 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 5, Problem 1]
- Question (tchan49-stat6250): When you use FILENAME statement to read an external file, do you need to assign a name to the file?
- Answer (tchan49-stat6250): Yes, the name associated to the file is called fileref. 



[Course Textbook Chapter 5, Problem 2]
- Question (tchan49-stat6250): Would Filerefs remain in effect permanently?



[Course Textbook Chapter 5, Problem 6]
- Question (tchan49-stat6250):How can you assign a new column name to each column in a output table where the columns are imported from raw table? 



[Course Textbook Chapter 5, Problem 7]
- Question (tchan49-stat6250):How do you differentiate numeric and character variable when you input columns from raw dataset?
- Answer (tchan49-stat6250):Put a $ sign in front of the start column number if the variable is character. Nothing happens to the numeric variables. 



[Course Textbook Chapter 5, Problem 8]
- Question (tchan49-stat6250):To create a new variable, is the re-defined name of the value on the left side of the equal sign or right side?



[Course Textbook Chapter 6, Problem 1]
- Question (tchan49-stat6250):Would the descriptor portion of the new SAS data set be created after the compilation phase completes? 
- Answer (tchan49-stat6250):No, it will be created at the end of the compilation phase. 



[Course Textbook Chapter 6, Problem 2]
- Question (tchan49-stat6250):Are incorrect values and formats considered as syntax errors? 



[Course Textbook Chapter 6, Problem 3]
- Question (tchan49-stat6250):Can the DATA step excutes each record in the input file more than once? 
- Answer (tchan49-stat6250):



[Course Textbook Chapter 6, Problem 4]
- Question (tchan49-stat6250):How do you know if there are any missing numeric and character values on Program Data Vector?  
- Answer (tchan49-stat6250):Missing numeric values are represented by periods and missing character values are represented by blanks. 



[Course Textbook Chapter 6, Problem 5]
- Question (tchan49-stat6250):When would the value of the sutomatic variable _ERROR_ larger than one? 



[Course Textbook Chapter 6, Problem 6]
- Question (tchan49-stat6250):When would the values of variables created in programming statements re-set to missing in program data vector? 



[basic_recipe_for_creating_analytic_datasets Week 5 Recipe]
- Question (tchan49-stat6250):Should you create a new name for the new dataset you create that obtains rows and columns from another dataset? 
- Answer (tchan49-stat6250):Yes, it is very important to name the new dataset to something unique and different from the dataset you obstain rows and colums from. 
This way, when you call out the dataset, it won't cause any confusions. 



[adv_recipe_for_creating_analytic_datasets Week 5 Recipe]
- Question (tchan49-stat6250):When you finish the PROC SQL step, do you end it with RUN statement?
- Answer (tchan49-stat6250):
