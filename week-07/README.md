## Week 7 Quiz Questions and Answers

In order to prepare your Week 7 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-7" in your fork of this repo. Then, after all edits have been made/committed, your Week 7 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-7 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 10, Problem 2]
- Question (tbishaw-stat6250): What is the function of a RETAIN statement?  
- Answer (tbishaw-stat6250): A RETAIN statement, assigns an intial value to a retained variable and prevents variables from being initialized each time the DATA step executes.



[Course Textbook Chapter 10, Problem 6]
- Question (tbishaw-stat6250): What are some of the comparision operators we can use when writing an IF-THEN statements?
- Answer (tbishaw-stat6250): Comparision operators: =oreq (equal to), ^=orne (not equal to), >orgt (greater than), <orlt (less than), >=orge (greater than or equal to), <=orle (less than or equal to), and in (equal to one of a list)



[Course Textbook Chapter 10, Problem 7]
- Question (tbishaw-stat6250): What statement can you add t oassign a value to TestLength when the condition in you IF-THEN statment is false? 



[Course Textbook Chapter 10, Problem 8]
- Question (tbishaw-stat6250): When do you want to use an IF-THEN statment with a DELETE statement in SAS? 



[Course Textbook Chapter 10, Problem 9]
- Question (tbishaw-stat6250): What is the key difference between the DROP and KEEP statments? 
- Answer (tbishaw-stat6250): The KEEP and DROP statments are similar, except that the KEEP statement specifies a list of variables to write to output data sets.



[Course Textbook Chapter 10, Problem 10]
- Question (tbishaw-stat6250): Is there an alternative to IF-THEN/ELSE statement? If so what is it?
- Answer (tbishaw-stat6250): As an alternative to IF-THEN/ELSE statmenent you can use SELECT groups in DATA steps to perform conditional processing. 



[Course Textbook Chapter 11, Problem 1]
- Question (tbishaw-stat6250): What are the steps you need to perform before you create the data set? 
- Answer (tbishaw-stat6250): To create the data set, you must first reference the library in which your data is stored and then you wirte a DATA step to read your data and create a new data set; you must assign a libref to the SAS library that will store the data set.



[Course Textbook Chapter 11, Problem 2]
- Question (tbishaw-stat6250): What is the function the SET statment performs? 
- Answer (tbishaw-stat6250): After you write a DATA step to name the SAS data set to be created, you use the SET statement to specify the data set that will be read. 



[Course Textbook Chapter 11, Problem 3]
- Question (tbishaw-stat6250): Which statement do you use if you never refernce certain varaibles and you do not want them to appear in the new data set? 



[Course Textbook Chapter 11, Problem 8]
- Question (tbishaw-stat6250): What are the two temporary varaibles the DATA step creates for each BY variable? 
- Answer (tbishaw-stat6250): One is named FIRST.variable, is the name of the BY variable, and the second is named LAST.variable. These two variables identify the first and last observation in each BY group. 



[Course Textbook Chapter 11, Problem 9]
- Question (tbishaw-stat6250): How can you prevent continuous looping when using direct access to read data?  
- Answer (tbishaw-stat6250): You add a STOP statement to the DATA step to prevent continuous looping. 



[basic_recipe_for_combining_data_vertically Week 7 Recipe]
- Question (tbishaw-stat6250): How is the LEGNGTH statement used in SAS? 
- Answer (tbishaw-stat6250): The LENGTH statemnt is used in the dATA step to specify a variable's length. If the varaible is character, the length applies to the PDV and the output data set. If the variable is numeric, the length applies only to the output data set.   



[adv_recipe_for_combining_data_vertically Week 7 Recipe]
- Question (tbishaw-stat6250): How are a group of statments executed as a unit in DATA steps? 


