## Week 6 Quiz Questions and Answers

In order to prepare your Week 6 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-6" in your fork of this repo. Then, after all edits have been made/committed, your Week 6 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-6 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 12, Problem 1]
- Question (tbishaw-stat6250): What are the two functions one-to-one mergin (or combining) allows you to do in SAS?     
- Answer (tbishaw-stat6250): In one-to-one merging you can read different data sets, or you can read the same data set more than once, as if you were reading from separate data sets.  



[Course Textbook Chapter 12, Problem 2]
- Question (tbishaw-stat6250): What is the difference between appending and concatenating?   



[Course Textbook Chapter 12, Problem 3]
- Question (tbishaw-stat6250): How is interleaving peformed and what are the functions of interleaving?   
- Answer (tbishaw-stat6250): If you use a BY statement when you concatenate data sets, the result is interleaving. Interleaving intersperses observations from two or more data sets, based on one or more common variables.



[Course Textbook Chapter 12, Problem 4]
- Question (tbishaw-stat6250): How does Match-Merging Select Data?   



[Course Textbook Chapter 12, Problem 5]
- Question (tbishaw-stat6250): What is the code format to renaming a variable in SAS?   
- Answer (tbishaw-stat6250): RENAME=(old-variable-name=new-variable-name)



[Course Textbook Chapter 12, Problem 7]
- Question (tbishaw-stat6250): Why is it important that you reference a variable in the original data set (in a subsetting IF statement, for example) using the DROP= option in the DATA statement?
- Answer (tbishaw-stat6250): If you do not reference the variable then you may get unexpected results and your variable will be uninitialized. 



[Course Textbook Chapter 12, Problem 9]
- Question (tbishaw-stat6250): Where do observations that have missing values for the BY variable appear?   
- Answer (tbishaw-stat6250): Observations that have missing values for the BY variable appear at the top of the output data set.



[basic_recipe_for_combining_data_horizontally Week 6 Recipe]
- Question (tbishaw-stat6250): When building an analytic file, what statement can be use to specify column order in the output data set?      
- Answer (tbishaw-stat6250): You use a RETAIN statement to specify column order in the output data set. 



[adv_recipe_for_combining_data_horizontally Week 6 Recipe]
- Question (tbishaw-stat6250): What is the Program Data Vecor (PDV)?  


