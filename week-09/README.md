## Week 9 Quiz Questions and Answers

In order to prepare your Week 9 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-9" in your fork of this repo. Then, after all edits have been made/committed, your Week 9 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-9 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 14, Problem 1]
- Question (tbishaw-stat6250): How can we execute a SAS statement repeatedly?     
- Answer (tbishaw-stat6250): We can execute a SAS statement repeatedly by placing them in a DO loop. Do loops can execute any number of times in a single iteration of the DATA step.  



[Course Textbook Chapter 14, Problem 2]
- Question (tbishaw-stat6250): Which variables must be specified when creating a DO loop?



[Course Textbook Chapter 14, Problem 3]
- Question (tbishaw-stat6250): What happens when you place an explicit OUTPUT statement in a DATA step?
- Answer (tbishaw-stat6250): It overrides automatic output, causing SAS to add an observation to the data set only when the explicit OUTPUT statement is executed.



[Course Textbook Chapter 14, Problem 4]
- Question (tbishaw-stat6250): What is the difference between the DO UNTIL and DO WHILE statements? 



[Course Textbook Chapter 14, Problem 5]
- Question (tbishaw-stat6250): Is the WHILE expression evaluated before or after the execution of the DO loop?
- Answer (tbishaw-stat6250): The WHILE expression is evaluated before the execution of the DO loop. 



[Course Textbook Chapter 14, Problem 6]
- Question (tbishaw-stat6250): If the condition for the WHILE expression is initally false, does the DO loop execute?



[Course Textbook Chapter 14, Problem 7]
- Question (tbishaw-stat6250): What does decrementing a DO loop accomplish? 



[Course Textbook Chapter 14, Problem 8]
- Question (tbishaw-stat6250): What conditions must be met for a DO loop to run within a DO loop?
- Answer (tbishaw-stat6250): DO loops can run within DO loops, as long as you assign a unique index variable to each loop and terminate each DO loop with its own END statement.



[Course Textbook Chapter 14, Problem 9]
- Question (tbishaw-stat6250): What does the SET statement in a DO loop execute? 



[Course Textbook Chapter 14, Problem 10]
- Question (tbishaw-stat6250): How many values is the index variable always incremented by?



[Course Textbook Chapter 15, Problem 1]
- Question (tbishaw-stat6250): How can you process variables as a group?
- Answer (tbishaw-stat6250): You can process varaibles as a group by using array processing.



[Course Textbook Chapter 15, Problem 2]
- Question (tbishaw-stat6250): What is an array? What are its functions?



[Course Textbook Chapter 15, Problem 3]
- Question (tbishaw-stat6250): What are the functions of a a DIM function? 
- Answer (tbishaw-stat6250): You can use the DIM function to specify the TO clause of the iterative DO statement.



[Course Textbook Chapter 15, Problem 4]
- Question (tbishaw-stat6250): What length are all character variables that are created with an ARRAY statement assigned by default?  



[Course Textbook Chapter 15, Problem 5]
- Question (tbishaw-stat6250): How can we assign initial values to character varaibles?  



[Course Textbook Chapter 15, Problem 6]
- Question (tbishaw-stat6250): How can we define a multidimensional arrays? 



[Course Textbook Chapter 15, Problem 7]
- Question (tbishaw-stat6250): What does rotating a data set accomplish?
- Answer (tbishaw-stat6250): Rotating a data set changes variables to observations or observations to variables. 



[Course Textbook Chapter 15, Problem 8]
- Question (tbishaw-stat6250): Can we give an array the same name as a variable in the same DATA step? 



[Course Textbook Chapter 15, Problem 9]
- Question (tbishaw-stat6250): How can we indicate the dimension of a one-dimensional array?
- Answer (tbishaw-stat6250): You can indicate the dimension of a one-dimensional array with an asterik as long as you specify the elements of the array.



[recipe_to_create_unique_record_id Week 9 Recipe]
- Question (tbishaw-stat6250): How can we adda new ID column in SAS? 



[recipe_to_disaggregate_counts_data Week 9 Recipe]
- Question (tbishaw-stat6250): Which SAS function do we use to execute disaggreagation? And what does Disaggreagation accomplish?  


