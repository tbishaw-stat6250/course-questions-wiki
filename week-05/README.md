## Week 5 Quiz Questions and Answers

In order to prepare your Week 5 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-5" in your fork of this repo. Then, after all edits have been made/committed, your Week 5 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-5 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 5, Problem 1]
- *Question* (cli19?stat6250): What are the benefits to using a FILENAME statement over importing data to a SAS library?



[Course Textbook Chapter 5, Problem 2]
- *Question* (cli19?stat6250): What is the best practice for maintaining filerefs when programming?



[Course Textbook Chapter 5, Problem 6]
- *Question* (cli19?stat6250): What is the alternative to the INPUT statement in the case where a data set contains hundreds of variables and manually counting column location is not feasible?



[Course Textbook Chapter 5, Problem 7]
- *Question* (cli19?stat6250): What can we expect if we do not specify an INPUT statement variable type?
- *Answer* (cli19?stat6250): SAS will return numeric missing values for that unspecified field.



[Course Textbook Chapter 5, Problem 8]
- *Question* (cli19?stat6250): Is it considered "bad practice" to create a new variable using the same name as an existing variable?



[Course Textbook Chapter 6, Problem 1]
- *Question* (cli19?stat6250): What is the purpose in viewing the descriptor portion of the data set?
- *Answer* (cli19?stat6250): The descriptor portion contains information on the physical data set as well as information on individual variables. It can be used to get an overview of the output data set or even leveraged using PROC DATASETS to improve SAS code efficiency.



[Course Textbook Chapter 6, Problem 2]
- *Question* (cli19?stat6250): Are there other debugging features built into SAS?



[Course Textbook Chapter 6, Problem 3]
- *Question* (cli19?stat6250): How does the execution of the DATA step change when other statements are added?



[Course Textbook Chapter 6, Problem 4]
- *Question* (cli19?stat6250): Is it possible to change the default initializations from missing to a specified value?



[Course Textbook Chapter 6, Problem 5]
- *Question* (cli19?stat6250): When data errors are encountered, does SAS produce outputs?



[Course Textbook Chapter 6, Problem 6]
- *Question* (cli19?stat6250): Why does the program data vector get reset to missing with each iteration?



[basic_recipe_for_creating_analytic_datasets Week 5 Recipe]
- *Question* (cli19?stat6250): In what other ways can the RETAIN statement be used?
- *Answer* (cli19?stat6250): The RETAIN statement can be combined with other statements to compare values across observations, for example.



[adv_recipe_for_creating_analytic_datasets Week 5 Recipe]
- *Question* (cli19?stat6250): Aside from differences in number of lines of code or required disk space, how can one decide whether SAS procedures or PROC SQL is the better option?


