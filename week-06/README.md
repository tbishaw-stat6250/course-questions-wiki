## Week 6 Quiz Questions and Answers

In order to prepare your Week 6 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-6" in your fork of this repo. Then, after all edits have been made/committed, your Week 6 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-6 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 12, Problem 1]
- *Question* (sbagdi-stat6250): Which method of combining datasets diversifies or scatters the observations from two or more data sets, based on common variables? Which SAS statement is used to do so?



[Course Textbook Chapter 12, Problem 2]
- *Question* (sbagdi-stat6250): What does match-making method of combining does? Which SAS statements are used for match-making?



[Course Textbook Chapter 12, Problem 3]
- *Question* (sbagdi-stat6250): In one-to-one merging method of combining, what is the number of observations in the new data set?
- *Answer* (sbagdi-stat6250): The new dataset in one-to-one merging method has the number of observations equivalent to the number of observations in the smallest original dataset. 



[Course Textbook Chapter 12, Problem 4]
- *Question* (sbagdi-stat6250): What happens if the attributes of the datasets to be concatenated are different? 
- *Answer* (sbagdi-stat6250): If the attributes of the datasets to be concatenated are different, then SAS takes the attribute from the first dataset that contains the variable with that attribute. 



[Course Textbook Chapter 12, Problem 5]
- *Question* (sbagdi-stat6250): Which statement differentiates between concatenation and interleaving?
- *Answer* (sbagdi-stat6250): BY statement differentiates between concatenation and interleaving. 



[Course Textbook Chapter 12, Problem 7]
- *Question* (sbagdi-stat6250): Which option in the SAS prevents the variable values from being overwritten by values of another variable with the same name? In which programming step does over writing take place?
- *Answer* (sbagdi-stat6250): The RENAME option in SAS prevents overwriting of values of variable. This takes place in the DATA step of programming in SAS.



[Course Textbook Chapter 12, Problem 9]
- *Question* (sbagdi-stat6250): What does SAS does if the type of variable in the DATA= data set is different than in BASE= data set?
- *Answer* (sbagdi-stat6250): If the type of variable in the DATA= data set is different than in BASE= data set, SAS replaces all the values for the variable in the DATA= data set with missing values and keeps the variable type of the variable specified in the BASE= data set. 



[basic_recipe_for_combining_data_horizontally Week 6 Recipe]
- *Question* (sbagdi-stat6250): What is the difference between SET statement and MERGE statement used in the compile and execute steps of any SAS program? Can a SET statement be used to specify multiple input datasets? If so, then what difference does it create? 
- *Answer* (sbagdi-stat6250): The prime difference between SET and MERGE statements is that the former is used to specify single input data sets and the later is used to specify multiple input data sets. A SET statement can be used to specify multiple I/P datasets, but in which case the data sets will be merged vertically rather than horizontally. 



[adv_recipe_for_combining_data_horizontally Week 6 Recipe]
- *Question* (sbagdi-stat6250): What are the three JOIN conditions in PROC SQL? 

