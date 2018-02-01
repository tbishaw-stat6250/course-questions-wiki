## Week 5 Quiz Questions and Answers

In order to prepare your Week 5 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-5" in your fork of this repo. Then, after all edits have been made/committed, your Week 5 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-5 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 5, Problem 1]
- Question (tbishaw-stat6250): What do we need to do before reading raw data from a file in the SAS software?
- Answer (tbishaw-stat6250): We might need to reference the SAS library in which we will be storing the data set. Then we can write a DATA step program to read the raw data file and create a SAS data set.



[Course Textbook Chapter 5, Problem 2]
- Question (tbishaw-stat6250): What SAS command can we use to create a report after using the DATA step to read the raw data?
- Answer (tbishaw-stat6250): After using the DATA step to read the raw data, we can use the PROC PRINT step to produce a report that displays the data values that are in the new data set. 



[Course Textbook Chapter 5, Problem 6]
- Question (tbishaw-stat6250): why would we need to use the LIBNAME statement as we are writing a program?



[Course Textbook Chapter 5, Problem 7]
- Question (tbishaw-stat6250): What is a fileref and what are the criterias for implementing for the fileref name? 
- Answer (tbishaw-stat6250): fileref is a name you assoiate wit han external file and the name must be 1 to 8 characters long. And the name has to also begin with a letter or underscore, and contain only letters, numerals, or underscores.



[Course Textbook Chapter 5, Problem 8]
- Question (tbishaw-stat6250): When do you use a subsetting IF statment? 



[Course Textbook Chapter 6, Problem 1]
- Question (tbishaw-stat6250): How is a SAS DATA step processed? 
- Answer (tbishaw-stat6250): A SAS DATA step is processed in two phases: Compilation Phase and Execution Phase.



[Course Textbook Chapter 6, Problem 2]
- Question (tbishaw-stat6250): What is stored in the program data vector afeter the input buffer is created?



[Course Textbook Chapter 6, Problem 3]
- Question (tbishaw-stat6250): What are some examples of some syntax errors?
- Answer (tbishaw-stat6250): Missing or misspelled keywords, invalid variable names, missing or invalid punctuation, and invalid options.



[Course Textbook Chapter 6, Problem 4]
- Question (tbishaw-stat6250): What are included in the descriptor portion of the SAS data set?



[Course Textbook Chapter 6, Problem 5]
- Question (tbishaw-stat6250): How many times does the dATA step execute for each record in the input file? What are the exceptions?
- Answer (tbishaw-stat6250): The DATA step executes once for each record in the inut file, unless otherwise directed by an additional statements.



[Course Textbook Chapter 6, Problem 6]
- Question (tbishaw-stat6250): How can you detect common errors and save development time? 
- Answer (tbishaw-stat6250): You can use the OBS= option in the INFILE statement to limit the number o observations that are read or created during the DATA step. 



[basic_recipe_for_creating_analytic_datasets Week 5 Recipe]
- Question (tbishaw-stat6250): Is there a way to tell SAS which rows and columns to include in a newly created data set? If so how?



[adv_recipe_for_creating_analytic_datasets Week 5 Recipe]
- Question (tbishaw-stat6250): What is the Program Data Vector (PDV) and how is it used in SAS?   
- Answer (tbishaw-stat6250): PDV is one of the most complex parts of using SAS and takes a lot of practice. PDV is one of the main features of SAS, and it allows SAS to read datasets one record at a time. 


