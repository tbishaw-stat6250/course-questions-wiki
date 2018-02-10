## Week 6 Quiz Questions and Answers

In order to prepare your Week 6 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-6" in your fork of this repo. Then, after all edits have been made/committed, your Week 6 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-6 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 12, Problem 1]
- *Question* (aacharya4−stat6250): While combining two data sets in one-on-one reading using multiple SET statements, what happens when variable of same names occur?
- *Answer* (aacharya4−stat6250): In this case involving same variable names, the values that are read from the second data set replaces the values from the first data set.
- Question (dfei-stat6250): What is the code that can combine two datasets together?
- Answer (dfei-stat6250): "data new dataset name; old dataset name1; old dataset name2; run;"



[Course Textbook Chapter 12, Problem 2]
- *Question* (aacharya4−stat6250): What is meant by interleaving of two data sets and how is it accomplished in SAS?
- *Answer* (aacharya4−stat6250): Interleavinng of two or more data sets means taking observations from both datasets which have common observations. It is accomplished using BY statement.
- Question (dfei-stat6250): What is the most important points when programmer will combine two datasets together?



[Course Textbook Chapter 12, Problem 3]
- *Question* (aacharya4−stat6250): What is the difference between using DATA CONCAT and PROC APPEND procedure to combine observations of two data sets?
- *Answer* (aacharya4−stat6250): In case of CONCAT procedure, a new dataset is created that contains observations from both data sets, while in APPEND procedure SAS does not create a new data set and appends the observations of one data set at the end of another(base) data set.
- Question (dfei-stat6250): What will happen after coding "set dataset name1 dataset name2"?
- Answer (dfei-stat6250): The two datasets will combine together and the dataset 2 will follow the dataset 1.



[Course Textbook Chapter 12, Problem 4]
- *Question* (aacharya4−stat6250): How is the new data set that is created with CONCAT by combining two data sets?
- *Answer* (aacharya4−stat6250): The new data set created with CONCAT will have all variables of both data sets and it contains all observations from both data sets. The sequence of observations in the new data set is determined by the sequence in which the data sets are mentioned in the SET statement.
- Question (dfei-stat6250): How to get the values when there are different rows between 2 datasets?



[Course Textbook Chapter 12, Problem 5]
- *Question* (aacharya4−stat6250): What is match-merging and how is it accomplished in SAS?
- *Answer* (aacharya4−stat6250): Match-merging happens when we need to combine observations from two or more data sets based on values of BY variable. We can use MERGE statement to accomplish this in SAS.
- Question (dfei-stat6250): Will sas send error message that calucate two different types of values when combining two datasets?



[Course Textbook Chapter 12, Problem 7]
- *Question* (aacharya4−stat6250): How are missing values proceessed in case of match-merging of two or more data sets?
- *Answer* (aacharya4−stat6250): When there are missing values for observations based on BY variable, then they appear at the top of the top of the output data set in match-merging.
- Question (dfei-stat6250): How do you prevent the same variables names of values when merge two datasets?
- Answer (dfei-stat6250): Coding rename=(name1=name2) at the end of one of the dataset name.



[Course Textbook Chapter 12, Problem 9]
- *Question* (aacharya4−stat6250): How can we exclude unmatched observations in the output data set while match-merging two or more data sets?
- *Answer* (aacharya4−stat6250): To exclude unmatched observations in the output data set while match-merging, we need to use IN dataset option along with subsetting IF statement in DATA step.
- Question (dfei-stat6250): Why and How SAS merge some special numberical values?



[basic_recipe_for_combining_data_horizontally Week 6 Recipe]
- *Question* (aacharya4−stat6250): In match merging, what happens when both input data sets with no identical variable names have the same value of unique id?
- *Answer* (aacharya4−stat6250): In match merging, a single row with the unique id is created in the output data set that contains all the variables from both the input data sets.
- Question (dfei-stat6250): What are the most common merge datasets statements when programmer coding?



[adv_recipe_for_combining_data_horizontally Week 6 Recipe]
- *Question* (aacharya4−stat6250): What are some of the advantages of using PROC SQL for combining data sets?
- *Answer* (aacharya4−stat6250): Some of the advantages of using PROC SQL is less lines of code is required. Also, we do not need to use RENAME data set option to avoid overwriting if there are variables of same names in input data sets.
- Question (dfei-stat6250): Can I name same names of columns when I want to merge datasets?


