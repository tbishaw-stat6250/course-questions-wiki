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
- *Question*(kamirneni-stat6250): In one-to-one reading, what happens when data sets have the same variable names?
- *Answer*(kamirneni-stat6250): The values which are read from the last dataset overwrite the values from the earlier datasets.
- *Question* (aamiri2-stat6250): Is it possible to combine two datasets with the goal of merging variables to match ID or observation numbers?
- *Answer* (aamiri2-stat6250):This is possible, there are many situations where there are multiple variables associated with one ID. Foremost, it is important that any dataset you want to combine should both have matching ID's. You can then combine the first dataset with the second dataset where you will have one ID column and various variables that were in both datasets.
- *Question* (shatcher4-stat6250): What are the different methods of merging?
- *Answer* (shatcher4-stat6250): The methods of merging are one-to-one reading, concatenating, appending, interleaving, and match-merging
- Question (aguenane−stat6250): What are the five methods of combining observations from two or more data sets into a new data set?
- Answer (aguenane-stat6250): They are one-to-one reading, concatenating, appending, interleaving, and match-merging.
- Question(tchan49-stat6250):In one-to-one reading, is the number of observations in the new dataset the the number of observations in the largerst or smallest orginal dataset?
- Answer(tchan49-stat6250):The smallest orginal datset. 
- *Question* (cli19−stat6250): In one-to-one reading, why does the final data set take on the number or rows from the smaller data set being combined?
- *Answer* (cli19−stat6250): Since SAS processes data row by row, the DATA step processing stops when the smaller data set reaches an end-of-file.
- *Question* (jbettonville-stat6250): Can more than two SET statements be used in a single DATA step to combine records from more than two data sets?
- *Answer* (jbettonville-stat6250): Yes, multiple data sets can be combined at once.
- Question (ldeng11−stat6250): What would happen if the two datasets have different number of observations, and have contain the variables have the same name when you use one-to-one reading?
- Answer (ldeng11−stat6250): The new data set will have all the values from the samllest data set; and the value of the variable will be the last read data set.
- *Question* (jcanfield3-stat6250): Is it ever useful to replace previous variable contents in one-to-one matching?
- *Question* (cnguyen77-stat6250): In one-to-one merging, how is the number of observations of the new data set defined?
- *Answer* (cnguyen77-stat6250): In one-to-one merging, the number of observations in the new data set is the number of observations in the smallest original data set.
- Question (lsun20-stat6250): Why the column VarX in the Brother.Three table will be 2 and 4 after combine?
- Question (lceballos-stat6250): How can we combine columns instead of rows?
- *Question* (akrishnamurthy-stat6250): In case of one-to-one reading, what will be the total number of observations in final data set?
- *Question* (xyin6-stat6250): How to determine the order of variable/observation for the new combined dataset?
- *Answer* (xyin6-stat6250): Observations are combined based on their relative position in each data set. That is, the first observation in one data set is joined with the first observation in the other, and so as the variable order.
- Question (who7-stat6250): Is there a way to combine 2 datasets using if loop in the proc statement?
- Question (ljiang11−stat6250): Would the second SET statement rewrite the first SET statement?
- Answer (ljiang11−stat6250): Yes.
- *Question* (ldai4-stat6250): How many methods can be used to combine observations from two or more data sets into a new data set?
- *Answer* (ldai4-stat6250): There are one-to one merging, concatenating, appending, interleaving, and match-merging.



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
- *Question*(kamirneni-stat6250): In concatenation, what does SAS do when length of attributes is different in datasets?
- *Answer*(kamirneni-stat6250): In this case, SAS takes length from first data set that contains the variable.
- *Question* (aamiri2-stat6250): What are the differences between one-to-one merging, concatenating, and appending when combining datasets?
- *Answer* (aamiri2-stat6250): The method of one-to-one merging creates observations that contain all of the variable from each dataset and combines the observations based on their position in each data set. The method of concatenating appends the observations from one dataset to another. The method of appending adds the observations in the second dataset to the end of the original dataset.
- *Question* (shatcher4-stat6250): What happens when a program concatenates data sets?
- Question (aguenane−stat6250): What is the difference between the interleaving and match-merging methods?
- Question(tchan49-stat6250):In interleaving reading, what happen if the variable for BY statement is character variable?
- *Question* (cli19−stat6250): Why isn't it necessary to first sort data prior to concatenating data sets?
- *Answer* (cli19−stat6250): SAS checks sequentially if key indicators match in a MERGE statement to combine rows, so sorting the data prior to a merge is required. For concatenating data sets, sorting isn't necessary since SAS essentially stacks the listed data sets and doesn't need to pair data sets by key indicators.
- *Question* (jbettonville-stat6250): When using BY to interleave multiple data sets, can we apply the DESCENDING keyword to change the order in which the resulting data set is sorted?
- Question (ldeng11−stat6250): How many onbervations will the end data set have after the interleaving process?
- Answer (ldeng11−stat6250): The new data set have all the variables from all the input data sets, and the total number of observations are the sum of the input data sets.
- *Question* (jcanfield3-stat6250): Do variables need to be pre-sorted for interleaving to work?
- *Question* (cnguyen77-stat6250): What statements are required in Interleaving method?
- *Answer* (cnguyen77-stat6250): A list of data set names in the SET statement and one or more BY variables in the BY statement.
- Question (lsun20-stat6250): What is the usage of the BY statement?
- Answer (lsun20-stat6250): To notice that observation in each BY group are read sequentially, in the order that the BY variable list.
- Question (lceballos-stat6250): What's the difference between the set function and the merge function when combining two datasets?
- *Question* (akrishnamurthy-stat6250): How does interleaving select data?
- *Answer* (akrishnamurthy-stat6250): Interleaving requires a list of data set names in SET statement with corresponding BY statements.The observations in each BY group are read sequentially in the order listed. The new data set contains all the variables from all the input data sets as well as the total number of records from all the input data sets.
- *Question* (xyin6-stat6250): Does SAS automatically sort the variable after "BY"? Or what sequence does it follow?
- Question (who7-stat6250): Why would SAS use a formatting method to differentiate different combining method instead of using a command word?
- Question (ljiang11−stat6250): By putting BY statement here, data will read as the BY variable's order instead of SET data order?
- *Question* (ldai4-stat6250): What is interleaving method for combining observations from two or more data sets?
- *Answer* (ldai4-stat6250): The interleaving method requires a list of data set names in the SET statement and one or more BY variables in BY statement. Notice that observations in each BY group are read sequentially, in the order in which that data sets and BY variable are listed. The new data set contains all the variable from all the input data sets.



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
- *Question*(kamirneni-stat6250): In what situations is the FORCE option used in APPEND procedure and other what conditions?
- *Question* (aamiri2-stat6250): When combining a dataset using DATA CONCAT and all variables and observations are combined, what happens if there is missing data?
- *Question* (shatcher4-stat6250): How do you concatenate data sets?
- *Answer* (shatcher4-stat6250): You must use the SET statement to append the observations from one data set to another data set by specifying a list of data set names in the statement.
- Question (aguenane−stat6250): What is the difference in the coding between one-to-one matching and concatenating?
- Answer (aguenane-stat6250): With one-to-one matching, you use individual SET statements per data set while with concatenating, you have multiple data sets in one SET statement separated by commas.
- Question(tchan49-stat6250):In concatenating reading, if two dataset have different types attributes, how would two datasets be combined?
- *Question* (cli19−stat6250): Is it possible to concatenate data sets and keep common variables only?
- *Question* (jbettonville-stat6250): Can data be sorted in the same step as it is concatenated (perhaps by using a BY statement), or does sorting require a separate step?
- Question (ldeng11−stat6250): How concatenating the data set process work?
- *Question* (jcanfield3-stat6250): How would the dataset in answer B) be formed, since there is no id to match them?
- *Question* (cnguyen77-stat6250): What happens when combining two SAS data sets by using concaternating method?
- *Answer* (cnguyen77-stat6250): Concatenating appends the observations from one data set to another data set. The new data set contains all of the variables and observations from all of the input data sets.
- Question (lsun20-stat6250): What will happen if the two table have one or more same column?
- Question (lceballos-stat6250): How can you concatenate column by groups?
- *Question* (akrishnamurthy-stat6250): What is the difference between APPEND procedure and concatenating datasets?
- *Answer* (akrishnamurthy-stat6250): PROC Append adds the observations of one dataset to the end of a master dataset.Where as,the DATA step creates a new dataset when concatenating.
- *Question* (xyin6-stat6250): If the length of attributes in two datasets are different, how does the concatenated dataset select the length?
- *Answer* (xyin6-stat6250): SAS takes the length from the first data set that contains the variable. The same is true for the label, format, and informat attributes.
- Question (who7-stat6250): What happens when columsn from 2 datasets have the same column name but different properties?
- Answer (who7-stat6250): Depends on how you merge the datasets.  If you are just appending them, it would just add the 2nd dataset to the 1st dataset.
- Question (ljiang11−stat6250): Why is there missing values?
- Answer (ljiang11−stat6250): Because there are no common columns, SAS will generate missing values for the new variables merged into the dataset.
- *Question* (ldai4-stat6250): In the concatenating append method, does the append statement need to be used?



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
- *Question*(kamirneni-stat6250): Does any case of duplicity arise when interleaving data, if yes, how is it resolved?
- *Question* (aamiri2-stat6250): What is the difference between PROC APPEND and DATA CONCAT when combining datasets?
- *Question* (shatcher4-stat6250): When concatenating data sets, what would cause an error message?
- Question (aguenane−stat6250): When can you not concatenate multiple data sets?
- Answer (aguenane-stat6250): Any common variable must have the same type attribute.
- Question(tchan49-stat6250):In concatenating reading, what would happen if two dataset have different lengths of observations? 
- *Question* (cli19−stat6250): How does SAS determine the length of different variables when concatenating data sets?
- *Answer* (cli19−stat6250): SAS takes the attribute from the first data set that contains the variable with that attribute. If the greatest length of varaibles is known, it's best to state it (using length or format) to avoid truncation.
- *Question* (jbettonville-stat6250): Is it possible to exclude specific variables while concatenating two or more data sets?
- Question (ldeng11−stat6250): What would happen if all the input data sets have the same variable name when you using the concatenating process?
- *Question* (jcanfield3-stat6250): In concatenating, do variables repeated throughout the datasets become merged or listed multiple times?
- *Answer* (jcanfield3-stat6250): They get listed multiple times.  They are treated as completely new observations rather than a continuation of a previous observation.
- *Question* (cnguyen77-stat6250): How does concatenating select data?
- *Answer* (cnguyen77-stat6250): When a program concatenates data sets, all of the observations are read from the first data set listed in the SET statement. Then all of the observations are read from the second data set listed, and so on, until all of the listed data sets have been read. The concatenated data sets are read sequentially, in the order in which they are listed in the SET statement.
- Question (lsun20-stat6250): How to concatenate the tables when they have different type of variable in SAS? 
- Question (lceballos-stat6250): How does SAS read the datasets when combining them?
- Answer (lceballos-stat6250): The concatenated data sets are read sequentially.
- *Question* (akrishnamurthy-stat6250): What is the difference between merging datasets and concatenating datasets?
- *Question* (xyin6-stat6250): If two data sets do not have common variables, can they still be concatenated?
- Question (who7-stat6250): Is there a way to combine datasets by adding columns instead of adding it by row?
- Answer (who7-stat6250): Yes, you can use the BY statement to merge 2 datasets by using common unique key to combine the datasets horizontally.
- Question (ljiang11−stat6250): What does concatenate mean?
- Answer (ljiang11−stat6250): It means to combine two datasets vertically.
- *Question* (ldai4-stat6250): Does the new data set contain all of the variables and observations from all of the input data sets when a program concatenates data sets?



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
- *Question*(kamirneni-stat6250): In match-merging processing, what's the advantage of creating PDV to hold one observation at a time by SAS?
- *Question* (aamiri2-stat6250): When combining a dataset, can you combine data based on a variable instead of an observation or ID number? 
- *Question* (shatcher4-stat6250): How are unmatched observations and missing values handled during the match-merge process?
- Question (aguenane−stat6250): If you want to merge more than one variable in descending order, how do you code this?
- Question(tchan49-stat6250):If two dataset have the same name in a variable, would the second dataset overwrite the value in the first dataset? 
- Answer(tchan49-stat6250):Yes, the second dataset would overwrite the value. 
- *Question* (cli19−stat6250): When merging two data sets by a key indicator, why do common variables from the second data set supercede the values from the first?
- *Question* (jbettonville-stat6250): In the example provided in this problem, how would we keep Age variables from both data sets when merging on the SSN variable?
- *Answer* (jbettonville-stat6250): In the MERGE statement, after the name of the data set containing the variable for which the name should be change, add a RENAME= option, as in (rename=(Age=LowerAge)) to change the Age variable in the second data set to a variable called LowerAge in the resulting output data set.
- Question (ldeng11−stat6250): What would happen if the input data sets have the same viariable names other than the match merge column?
- Answer (ldeng11−stat6250): The value from the later data set would overwrite the value of the forward data set in the same viariable column.
- *Question* (jcanfield3-stat6250): How can you avoid overwriting variables?
- *Answer* (jcanfield3-stat6250): By concatenating, renaming variables, and not combining datasets with like named variables.
- *Question* (cnguyen77-stat6250): What happens if you merge two data sets that have variables with the same name?
- *Answer* (cnguyen77-stat6250): If you have variables with the same name in more than one input data set, values of the same-named variable in the first data set in which it appears are overwritten by values of the same-named variable in subsequent data sets.
- Question (lsun20-stat6250): Which statement can make the same-named variable keep original when you merge the two data sets?
- Question (lceballos-stat6250): How do we chose which dataset overwrites the other?
- Answer (lceballos-stat6250): List the data set that you want to keep first, datasets after that with same-named variables will be overwritten.
- *Question* (akrishnamurthy-stat6250): How are same named variables handled while merging datasets? Which value takes precedence if both the variables carry different values?
- *Answer* (akrishnamurthy-stat6250):The values of the same named variable in first dataset is overwritten by the value for the same-named variable in second dataset.
- *Question* (xyin6-stat6250): What will happen to the output if input data set doesn't have any observations for a particular value of the by-variable?
- *Answer* (xyin6-stat6250): The observation in the output data set contains missing values for the variables that are unique to that input data set
- Question (who7-stat6250): If interleaving datasets will overwrite value that is the same, what happens if one is integer and one is decimal?
- Question (ljiang11−stat6250): Why the value of age in the 2nd dataset overwrite that from the 1st dataset?
- Answer (ljiang11−stat6250): The order of the datasets after MERGE statement determines the subsequent dataset can overwrite the 1st dataset.
- *Question* (ldai4-stat6250): What happens if we merge the two data sets which have same name variables?



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
- *Question*(kamirneni-stat6250): What is the process of referencing a variable in the original dataset? 
- *Question* (aamiri2-stat6250): What can be done to prevent a variable from being overwritten when merging two datasets?
- *Answer* (aamiri2-stat6250): To prevent overwriting, you can rename variables by using the RENAME= option in the MERGE statement. Then the old variable and new variable name must be stated to ensure your data does not get overwritten.
- *Question* (shatcher4-stat6250): What happens when you have same-named variables in more than one input data set?
- Question (aguenane−stat6250): If you merge two data sets and two values for a variable are the same, the DATA step overwrites the values of the like-named variable in the first data set; is this overwrite permanent?
- Question(tchan49-stat6250):If you want to prevent the variable being overwritten by the second dataset, do you rename the variable name of the first dataset or second dataset? 
- *Question* (cli19−stat6250): When merging data sets, is there an expedient way to automatically rename variables with the same name to keep variables from both data sets?
- *Question* (jbettonville-stat6250): Can data combinations such as the examples listed in this chapter also be completed using PROC SQL statements?
- Question (ldeng11−stat6250): If the input data sets have the same column, what you need to do to prevent the data be over write when you use the match merge process?
- *Question* (jcanfield3-stat6250): What is the final results of the code? Do they get concatenated or merged horizontally?
- *Question* (cnguyen77-stat6250): Can you keep the values of same-named variables from being overwritten when you merge the two data sets?
- *Answer* (cnguyen77-stat6250): To prevent overwriting, rename variables by using the RENAME= data set option in the MERGE statement.
- Question (lsun20-stat6250): Why we need to use RENAME=data set option in the MERGE statement?
- Answer (lsun20-stat6250): RENAME= data set option can help us to prevent overwriting when we merge the two data set.
- Question (lceballos-stat6250): Can you use the IN statement for several variables at a time?
- *Question* (akrishnamurthy-stat6250): How to prevent same-named variable from being overwritten ? Can both the same-named variables be retained in the output dataset?
- *Question* (xyin6-stat6250): If we rename the variable in the output, does the original dataset keep the former name or it will also be changed?
- Question (who7-stat6250): What is the preferred method to avoid overwriting? using rename or some other way?
- Question (ljiang11−stat6250): What does RENAME= do?
- *Question* (ldai4-stat6250): How can we prevent the variables with same names from being overwritten during merging the two datasets?
- *Answer* (ldai4-stat6250): We can use RENAME=data set option in the MERGE statement to prevent from be overwritten.



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
- *Question*(kamirneni-stat6250): What is the function of FIRST and LAST in processing?
- *Question* (aamiri2-stat6250): How can you exclude unmatched observation data when combining  a dataset? Does this cause any discrepancies in the final combined dataset?
- *Question* (shatcher4-stat6250): What does the IN= data set option do in excluding unmatched observations?
- *Answer* (shatcher4-stat6250): It creates and names a variable that indicates whether the data set contributed data to the current observations.
- Question (aguenane−stat6250): When using a BY statement, can you specify any of the variables/more than one variable?
- Question(tchan49-stat6250):When the dataset are merged, will the new dataset drop the rows that have any missing value?
- Answer(tchan49-stat6250):No, the new dataset will keep the all the rows even there are missing values. 
- *Question* (cli19−stat6250): What are other methods to keep all observations from data sets being merged by a key indicator?
- *Answer* (cli19−stat6250): This can also be accomplished by using a FULL JOIN in a PROC SQL step.
- *Question* (jbettonville-stat6250): If the Name variables were not the same for each ID variable in these data sets, which value of Name would the resulting data set take for each ID?
- *Answer* (jbettonville-stat6250): If the ID variable for both data sets matched but the Name variable in each data set was different for that ID number, the resulting data set would take on the Name variable of the second data set containing the given ID, because the PDV would take the second Name variable and overwrite the first Name variable before adding the new record to the output data set.
- Question (ldeng11−stat6250): How the match merge process handle the unmatched observations?
- *Question* (jcanfield3-stat6250): Which variables can be overwritten?
- *Answer* (jcanfield3-stat6250): Variables with matching id's and different contents when merging, or just different contents when one-to-one matching.
- *Question* (cnguyen77-stat6250): How does match-merging select data?
- Question (lsun20-stat6250): What will happen if there are some missing value in these table after merging?
- Answer (lsun20-stat6250): All the observations will be keep after merging except the same-name observation, and will leave blank speace in the missing value.
- Question (lceballos-stat6250): How do you merge using an ID?
- Answer (lceballos-stat6250): Using the BY statement.
- *Question* (akrishnamurthy-stat6250):How are unmatched observations handled while merging two datasets?
- *Question* (xyin6-stat6250): Is it necessary to specify descending order in both DATA and PROC step?
- Question (who7-stat6250): Would there be other ways to combine data besides using merge method?
- Answer (who7-stat6250): Yes, you can merge datasets by useing proc sql.
- Question (ljiang11−stat6250): What happens to the observations with same ID?
- *Question* (ldai4-stat6250): During match-merging, can we select the observations that we need?



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
- *Question*(kamirneni-stat6250): What is the difference in working in DATA step of a RETAIN statement between single and multiple datasets?
- *Answer*(kamirneni-stat6250): The difference is that there are multiple origin points for values in mutliple datasets 
used to fill in the PDV for each row to be included in output.
- *Question* (aamiri2-stat6250): Does MERGE statements and BY statements need to be used conjointly? 
- *Question* (shatcher4-stat6250): In match-merging why is a merge and by statement required?
- Question (aguenane−stat6250): What is the goal of using a RETAIN statement when merging data sets?
- Question(tchan49-stat6250):What is the difference of the code between concatenating and interleaving? 
- Answer(tchan49-stat6250):There BY statement in interleaving reading. 
- *Question* (cli19−stat6250): From which data set being merged are labels kept when it comes to common variables?
- *Question* (jbettonville-stat6250): Do KEEP statements have to list variables in the same order as RETAIN statements?
- Question (ldeng11−stat6250): What does the rename statement do?
- *Question* (jcanfield3-stat6250): How does the Best12. format know how to decide between formats?
- *Question* (cnguyen77-stat6250): What are the functions of the merge and by statements in match-merging method?
- *Answer* (cnguyen77-stat6250): The merge statement is used to name two input datasets, and the by statement is used to name the unique id column(s), which specify how rows are to be matched up when combining the datasets.
- Question (lsun20-stat6250): What is the usage of best12? Why we need the format best12 in this place?
- Question (lceballos-stat6250): Performance wise, is the PROC SQL method more effient?
- *Question* (akrishnamurthy-stat6250): Is it necessary for the datasets to be sorted before merging BY a common column?
- *Question* (xyin6-stat6250): IS it possible to put more than one variable after BY statement?
- Question (who7-stat6250): Given using proc sql would use less code to achieve the same result, would proc sql be considered advanced SAS programming?
- Question (ljiang11−stat6250): When combining columns from two datasets, why do we want to convert the varaibles from text to numeric?
- *Question* (ldai4-stat6250): In using MERGE statement, how can we create the descending order?



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
- *Question*(kamirneni-stat6250): What is the data limit beyond which PROC SQL is no longer useful and conventional SAS methods are to be used?
- *Question* (aamiri2-stat6250): What is the benefit of using PROC SQL when combining datasets? Where can we learn more about PROC SQL for self-study?
- *Question* (shatcher4-stat6250): What are the tradeoffs in combining datasets using proc sql?
- Question (aguenane−stat6250):What is the (PDV) MEANS ?
- Question(tchan49-stat6250): What are the advantages of using Proc SQL to create a merged table for two datasets?
- *Question* (cli19−stat6250): How do DATA steps and PROC SQL compare computationally? Is one more intensive than the other?
- *Question* (jbettonville-stat6250): When using PROC SQL to match-merge data sets, do the data sets first need to be sorted by the variables on which they are to be merged, as they do when performing a match-merge with a DATA step?
- Question (ldeng11−stat6250): What is full join mean in SAS PROC SQL procedure? What are the differneces between PROC SQL and SQL language when joining the data? 
- *Question* (jcanfield3-stat6250): Why does the select function require commas to separate values rather than the usual space or semicolon?
- *Question* (cnguyen77-stat6250): What is the approach to merge multiple datasets with respect to a condition for matching up rows without using data steps?
- Question (lsun20-stat6250): What is the means of the dash between the two input statements in the example?
- Question (lceballos-stat6250): How does the "AS" Statement make the code easier to read or work with?
- *Question* (akrishnamurthy-stat6250): What is the benefit of using PROC SQL over merge statement?
- *Question* (xyin6-stat6250): How to specify join condition instead of full join?
- Question (who7-stat6250): How would the use of inner join and outer join in sql language affect the way the datasets are combined in proc sql?
- Question (ljiang11−stat6250): Why would renaming data name in PROC SQL can minimize the amount of missing data?
- *Question* (ldai4-stat6250):  How can we select only observation that match for some specific input data sets in match-merging statement? For example, I want to select some observations which appear in both data files.



