## Week 6 Quiz Questions and Answers

In order to prepare your Week 6 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-6" in your fork of this repo. Then, after all edits have been made/committed, your Week 6 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-6 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 12, Problem 1]
- Question (nshrivastava2-stat6250): How one-to-one reading data set works ?
- Answer(nshrivastava2-stat6250): The first SET statement reads the first observation from the first data set into the program data vector. Then The second SET statement reads the first observation from the second data set into the program data vector and SAS writes the contents of the program data vector to the new data set. The value from second data set overwrites the value from first data set.  



[Course Textbook Chapter 12, Problem 2]
- Question (nshrivastava2-stat6250):To append the observations from one data set to another data set,what are the two ways to do that?
- Answer(nshrivastava2-stat6250): Concatenating and appending are the two ways, by specifying the data set names in the SET statement and PROC APPEND procedure respectively.



[Course Textbook Chapter 12, Problem 3]
- Question (nshrivastava2-stat6250): What is the requirement to append procedure?
- Answer(nshrivastava2-stat6250): Only two data sets can be used at a time in one step. The observations in the base data set are not read whereas the variable information in the descriptor portion of the base data set cannot change. The final data set is the original data set with appended observations and that no new data set was created.



[Course Textbook Chapter 12, Problem 4]
- Question (nshrivastava2-stat6250): What is the functionality of FORCE option in APPEND procedure ?



[Course Textbook Chapter 12, Problem 5]
- Question (nshrivastava2-stat6250): What is the difference between Interleaving and Conacatenate dataset?



[Course Textbook Chapter 12, Problem 7]
- Question (nshrivastava2-stat6250): How Interleaving Selects Data works?
- Answer(nshrivastava2-stat6250): When SAS interleaves data sets, observations in each BY group in each data set in the SET statement are read sequentially, in the order in which the data sets and BY variables are listed, until all observations have been processed. The new data set includes all the variables from all the input data sets, and it contains the total number of observations from all input data sets.



[Course Textbook Chapter 12, Problem 9]
- Question (nshrivastava2-stat6250): Explian the match merging processing?
- Answer(nshrivastava2-stat6250): When we submit a DATA step, it is processed in two phases: the compilation phase, in which SAS checks the syntax of the SAS statements and compiles them (translates them into machine code). During this phase, SAS also sets up descriptor information for the output data set and creates the program data vector (PDV), an area of memory where SAS holds one observation at a time. 



[basic_recipe_for_combining_data_horizontally Week 6 Recipe]
- Question (nshrivastava2-stat6250): In match merging, when we are trying to merge two files BY variables. In case of character variables, what happen when variables from one dataset has different case? 
- Answer(nshrivastava2-stat6250): The SAS match-merge is case sensitive. In such case an upper-case letter form one data set will not match with a lower-case of another dataset. However, when we receive data from different sources, the alphabet is not keyed uniformly in upper or lower case. 



[adv_recipe_for_combining_data_horizontally Week 6 Recipe]
- Question (nshrivastava2-stat6250): Comparing data step match-merges and proc sql joins, how they are different from each other?


