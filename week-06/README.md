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
- *Question* (sbagdi-stat6250): Which method of combining datasets diversifies or scatters the observations from two or more data sets, based on common variables? Which SAS statement is used to do so?
- Question(pcheng14-stat6250):Is the number of observations in the new data set is the number of observations in the highest original data set?
- Answer(pcheng14-stat6250):No, the correct is the number of observation in the smallest original data set.
- Question (tbishaw-stat6250): What are the two functions one-to-one mergin (or combining) allows you to do in SAS?     
- Answer (tbishaw-stat6250): In one-to-one merging you can read different data sets, or you can read the same data set more than once, as if you were reading from separate data sets.  
- Question (nshrivastava2-stat6250): How one-to-one reading data set works ?
- Answer(nshrivastava2-stat6250): The first SET statement reads the first observation from the first data set into the program data vector. Then The second SET statement reads the first observation from the second data set into the program data vector and SAS writes the contents of the program data vector to the new data set. The value from second data set overwrites the value from first data set.  
- Question (ttruong59-stat6250): What happen if the data sets contain variables that have the same names in term of One-to-One Reading?
- Answer (ttruong59-stat6250): The value that are read from the last data set overwrite the values that were read from earlier data sets.



[Course Textbook Chapter 12, Problem 2]
- *Question* (aacharya4−stat6250): What is meant by interleaving of two data sets and how is it accomplished in SAS?
- *Answer* (aacharya4−stat6250): Interleavinng of two or more data sets means taking observations from both datasets which have common observations. It is accomplished using BY statement.
- Question (dfei-stat6250): What is the most important points when programmer will combine two datasets together?
- *Question* (sbagdi-stat6250): What does match-making method of combining does? Which SAS statements are used for match-making?
- Question(pcheng14-stat6250):Waht will the new data set contain in the case of interleaving?
- Answer(pcheng14-stat6250):The new data set contains all the variables from all the input data sets, as well as the total number of records from all input data sets.
- Question (tbishaw-stat6250): What is the difference between appending and concatenating?   
- Question (nshrivastava2-stat6250):To append the observations from one data set to another data set,what are the two ways to do that?
- Answer(nshrivastava2-stat6250): Concatenating and appending are the two ways, by specifying the data set names in the SET statement and PROC APPEND procedure respectively.
- Question (ttruong59-stat6250): According to the textbook, the result is interleaving if you use a BY statement when users concatenate data sets. What if users do not include a BY statement? Is it still considered as interleaving?



[Course Textbook Chapter 12, Problem 3]
- *Question* (aacharya4−stat6250): What is the difference between using DATA CONCAT and PROC APPEND procedure to combine observations of two data sets?
- *Answer* (aacharya4−stat6250): In case of CONCAT procedure, a new dataset is created that contains observations from both data sets, while in APPEND procedure SAS does not create a new data set and appends the observations of one data set at the end of another(base) data set.
- Question (dfei-stat6250): What will happen after coding "set dataset name1 dataset name2"?
- Answer (dfei-stat6250): The two datasets will combine together and the dataset 2 will follow the dataset 1.
- *Question* (sbagdi-stat6250): In one-to-one merging method of combining, what is the number of observations in the new data set?
- *Answer* (sbagdi-stat6250): The new dataset in one-to-one merging method has the number of observations equivalent to the number of observations in the smallest original dataset. 
- Question(pcheng14-stat6250):Is it part of the variables from all the input data sets appear in the new data set is correct?
- Answer(pcheng14-stat6250):No, correct should be all of the variables from all the input data sets appear in the new data.
- Question (tbishaw-stat6250): How is interleaving peformed and what are the functions of interleaving?   
- Answer (tbishaw-stat6250): If you use a BY statement when you concatenate data sets, the result is interleaving. Interleaving intersperses observations from two or more data sets, based on one or more common variables.
- Question (nshrivastava2-stat6250): What is the requirement to append procedure?
- Answer(nshrivastava2-stat6250): Only two data sets can be used at a time in one step. The observations in the base data set are not read whereas the variable information in the descriptor portion of the base data set cannot change. The final data set is the original data set with appended observations and that no new data set was created.
- Question (ttruong59-stat6250): What does concatenating datasets mean?
- Answer (ttruong59-stat6250): Concatenating datasets means stacking one dataset on top of the other. For example, given two datasets, records from the second dataset will be added to the end of the first one.



[Course Textbook Chapter 12, Problem 4]
- *Question* (aacharya4−stat6250): How is the new data set that is created with CONCAT by combining two data sets?
- *Answer* (aacharya4−stat6250): The new data set created with CONCAT will have all variables of both data sets and it contains all observations from both data sets. The sequence of observations in the new data set is determined by the sequence in which the data sets are mentioned in the SET statement.
- Question (dfei-stat6250): How to get the values when there are different rows between 2 datasets?
- *Question* (sbagdi-stat6250): What happens if the attributes of the datasets to be concatenated are different? 
- *Answer* (sbagdi-stat6250): If the attributes of the datasets to be concatenated are different, then SAS takes the attribute from the first dataset that contains the variable with that attribute. 
- Question(pcheng14-stat6250):Why the concatenated data sets are read sequentially?
- Question (tbishaw-stat6250): How does Match-Merging Select Data?   
- Question (nshrivastava2-stat6250): What is the functionality of FORCE option in APPEND procedure ?
- Question (ttruong59-stat6250): I see the correct answer from the textbook for problem 4 is “a” that means “missing" or the second observation in Sales.Rep does not contain a value for Sale, so a missing value appears for this variable. What about the first observation? Does a missing value appear for this variable as well?



[Course Textbook Chapter 12, Problem 5]
- *Question* (aacharya4−stat6250): What is match-merging and how is it accomplished in SAS?
- *Answer* (aacharya4−stat6250): Match-merging happens when we need to combine observations from two or more data sets based on values of BY variable. We can use MERGE statement to accomplish this in SAS.
- Question (dfei-stat6250): Will sas send error message that calucate two different types of values when combining two datasets?
- *Question* (sbagdi-stat6250): Which statement differentiates between concatenation and interleaving?
- *Answer* (sbagdi-stat6250): BY statement differentiates between concatenation and interleaving. 
- Question(pcheng14-stat6250):When shoudl we merge the data sets?
- Question (tbishaw-stat6250): What is the code format to renaming a variable in SAS?   
- Answer (tbishaw-stat6250): RENAME=(old-variable-name=new-variable-name)
- Question (nshrivastava2-stat6250): What is the difference between Interleaving and Conacatenate dataset?
- Question (ttruong59-stat6250): What is a mechanism of SAS when users merge the datasets but have variables with the same name in more than one input dataset?
- Answer (ttruong59-stat6250): Values of the same name variable in the second dataset will overwrite the values of the first one.



[Course Textbook Chapter 12, Problem 7]
- *Question* (aacharya4−stat6250): How are missing values proceessed in case of match-merging of two or more data sets?
- *Answer* (aacharya4−stat6250): When there are missing values for observations based on BY variable, then they appear at the top of the top of the output data set in match-merging.
- Question (dfei-stat6250): How do you prevent the same variables names of values when merge two datasets?
- Answer (dfei-stat6250): Coding rename=(name1=name2) at the end of one of the dataset name.
- *Question* (sbagdi-stat6250): Which option in the SAS prevents the variable values from being overwritten by values of another variable with the same name? In which programming step does over writing take place?
- *Answer* (sbagdi-stat6250): The RENAME option in SAS prevents overwriting of values of variable. This takes place in the DATA step of programming in SAS.
- Question(pcheng14-stat6250):Is there any others solutions way could prevent the values of the variable being overwritten when we merge the two data sets
- Question (tbishaw-stat6250): Why is it important that you reference a variable in the original data set (in a subsetting IF statement, for example) using the DROP= option in the DATA statement?
- Answer (tbishaw-stat6250): If you do not reference the variable then you may get unexpected results and your variable will be uninitialized. 
- Question (nshrivastava2-stat6250): How Interleaving Selects Data works?
- Answer(nshrivastava2-stat6250): When SAS interleaves data sets, observations in each BY group in each data set in the SET statement are read sequentially, in the order in which the data sets and BY variables are listed, until all observations have been processed. The new data set includes all the variables from all the input data sets, and it contains the total number of observations from all input data sets.
- Question (ttruong59-stat6250): What is a main reason users have to prevent the values of the variable from overwritten when merging two datasets that have a same-named variable?



[Course Textbook Chapter 12, Problem 9]
- *Question* (aacharya4−stat6250): How can we exclude unmatched observations in the output data set while match-merging two or more data sets?
- *Answer* (aacharya4−stat6250): To exclude unmatched observations in the output data set while match-merging, we need to use IN dataset option along with subsetting IF statement in DATA step.
- Question (dfei-stat6250): Why and How SAS merge some special numberical values?
- *Question* (sbagdi-stat6250): What does SAS does if the type of variable in the DATA= data set is different than in BASE= data set?
- *Answer* (sbagdi-stat6250): If the type of variable in the DATA= data set is different than in BASE= data set, SAS replaces all the values for the variable in the DATA= data set with missing values and keeps the variable type of the variable specified in the BASE= data set. 
- Question(pcheng14-stat6250):What is the smallest observations amount the new data set contain?
- Question (tbishaw-stat6250): Where do observations that have missing values for the BY variable appear?   
- Answer (tbishaw-stat6250): Observations that have missing values for the BY variable appear at the top of the output data set.
- Question (nshrivastava2-stat6250): Explian the match merging processing?
- Answer(nshrivastava2-stat6250): When we submit a DATA step, it is processed in two phases: the compilation phase, in which SAS checks the syntax of the SAS statements and compiles them (translates them into machine code). During this phase, SAS also sets up descriptor information for the output data set and creates the program data vector (PDV), an area of memory where SAS holds one observation at a time. 
- Question (ttruong59-stat6250): How does the DATA step perform or process match-merges? What happen if observations do not match?



[basic_recipe_for_combining_data_horizontally Week 6 Recipe]
- *Question* (aacharya4−stat6250): In match merging, what happens when both input data sets with no identical variable names have the same value of unique id?
- *Answer* (aacharya4−stat6250): In match merging, a single row with the unique id is created in the output data set that contains all the variables from both the input data sets.
- Question (dfei-stat6250): What are the most common merge datasets statements when programmer coding?
- *Question* (sbagdi-stat6250): What is the difference between SET statement and MERGE statement used in the compile and execute steps of any SAS program? Can a SET statement be used to specify multiple input datasets? If so, then what difference does it create? 
- *Answer* (sbagdi-stat6250): The prime difference between SET and MERGE statements is that the former is used to specify single input data sets and the later is used to specify multiple input data sets. A SET statement can be used to specify multiple I/P datasets, but in which case the data sets will be merged vertically rather than horizontally. 
- Question(pcheng14-stat6250):Why retain statemnet is used to specify columen order in he output dataset?
- Question (tbishaw-stat6250): When building an analytic file, what statement can be use to specify column order in the output data set?      
- Answer (tbishaw-stat6250): You use a RETAIN statement to specify column order in the output data set. 
- Question (nshrivastava2-stat6250): In match merging, when we are trying to merge two files BY variables. In case of character variables, what happen when variables from one dataset has different case? 
- Answer(nshrivastava2-stat6250): The SAS match-merge is case sensitive. In such case an upper-case letter form one data set will not match with a lower-case of another dataset. However, when we receive data from different sources, the alphabet is not keyed uniformly in upper or lower case. 
- Question (ttruong59-stat6250): When combining data horizontally by using a recipe per provided, is it possible to merge two columns with the same names but they have different variable attributes? 



[adv_recipe_for_combining_data_horizontally Week 6 Recipe]
- *Question* (aacharya4−stat6250): What are some of the advantages of using PROC SQL for combining data sets?
- *Answer* (aacharya4−stat6250): Some of the advantages of using PROC SQL is less lines of code is required. Also, we do not need to use RENAME data set option to avoid overwriting if there are variables of same names in input data sets.
- Question (dfei-stat6250): Can I name same names of columns when I want to merge datasets?
- *Question* (sbagdi-stat6250): What are the three JOIN conditions in PROC SQL? 
- Question(pcheng14-stat6250):Besides using proc sql with a from clause combining the datasteps with a join operation specifying the condition for matching up rows. Is there any other ways can get same result? 
- Question (tbishaw-stat6250): What is the Program Data Vecor (PDV)?  
- Question (nshrivastava2-stat6250): Comparing data step match-merges and proc sql joins, how they are different from each other?
- Question (ttruong59-stat6250): What is a disadvantage of using proc sql?
- Answer (ttruong59-stat6250):proc sql loads all the data into memory before joining so the process will take longer to create join datasets if the datasets are large but there is no issue as long as the data are small enough to fit in memory.



