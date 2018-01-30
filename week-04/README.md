## Week 4 Quiz Questions and Answers

In order to prepare your Week 4 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-4" in your fork of this repo. Then, after all edits have been made/committed, your Week 4 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-4 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 7, Problem 3]
- Question(pcheng14-stat6250): When should we create a format with the VALUE statement?
- Answer(pcheng14-stat6250): Depends on the user, such as solving the mathematic problem.
- *Question* (cli19−stat6250): If a numeric variable ("JobTitle") is formatted to take on character values (i.e. 105='text processor'), does "JobTitle" remain a numeric variable after reformatting it (format JobTitle jobfmt.)?
- *Question* (aacharya4−stat6250): While specifying numeric values in VALUE statement, what are the rules that should be followed?
- *Answer* (aacharya4−stat6250): The numeric values should not end with '$' and they should be enclosed within quotation marks.
- *Question* (jbettonville-stat6250): If a dollar sign is placed in front of a format name, can a combination of character and number labels be used?
- *Answer* (jbettonville-stat6250): The values for a label can either be unique numerical values that are not surrounded by quotation marks, or unique combinations of characters surrounded by quotation marks, but not a combination of the two.
- Question (who7−stat6250): Could you write basic arithmetic function into the categorisation during FORMAT?



[Course Textbook Chapter 7, Problem 4]
- Question(pcheng14-stat6250): How many FORMAT procedures we always used it?
- *Question* (cli19−stat6250): In regards to processing speed and programming efficiency, is specifying the variable format better than  using IF-THEN logic to recode a variable?
- *Question* (aacharya4−stat6250): What are the rules to follow while defining one's own unique format with PROC FORMAT statement?
- *Answer* (aacharya4−stat6250): To define one own's unique format, it must begin with keyword value followed by the format name and ends with semicolon after all labels are defined.
- *Question* (jbettonville-stat6250): In a VALUE statement, could all of the labels be included on the same line, even though this would be a poor stylistic choice? Would the declaration function the same way?
- Question (who7−stat6250): Is there a limit on how many conditions we can set during FORMAT?



[Course Textbook Chapter 7, Problem 5]
- Question(pcheng14-stat6250): A range of numeric values, such as 50000-99999 is the ranges in the VALUE statement can be specify?
- *Question* (cli19−stat6250): What type of messages should we expect to see in the SAS log if the VALUE range includes a mistake?
- *Question* (aacharya4−stat6250): How to define a list of values (either numeric or character) in the VALUE statement?
- *Answer* (aacharya4−stat6250): A list containing either all numeric or character values can be used in the VALUE statement by seperating each value with commas.
- *Question* (jbettonville-stat6250): Can a combination of character and number labels within quotes be used in a VALUE statement? I.e. could 'A1' and 'A2' be used in a VALUE statement?
- Question (who7−stat6250): What can we do if we need to exceed the range in the VALUE statement?



[Course Textbook Chapter 7, Problem 6]
- Question(pcheng14-stat6250): What the lowest number of characters can be used in a label?
- Answer(pcheng14-stat6250): One
- *Question* (cli19−stat6250): Is it necessary to specify the maximum length of labels?
- *Question* (aacharya4−stat6250): What happens if the format name ends in a period when used in a VALUE statement?
- *Question* (jbettonville-stat6250): Does the 256 character limit for labels include the quotation marks that surround the content of the label?
- Question (who7−stat6250): Would it be wise to use FORMAT on a primary key?



[Course Textbook Chapter 7, Problem 7]
- Question(pcheng14-stat6250): What is the meaning of “OTHER” in keyword?
- *Question* (cli19−stat6250): The book provides an example for a numeric variable, but can "OTHER" also be applied to missing character values?
- *Question* (aacharya4−stat6250): What keywords can be used as a label to depict the lower and upper limits of a variable's value range in VALUE statement?
- *Answer* (aacharya4−stat6250): 'LOW' and 'HIGH' keywords can be used as a label to depict the lower and upper limits of a variable's value range in VALUE statement.
- *Question* (jbettonville-stat6250): In which other contexts might we use keywords LOW, HIGH, and OTHER?
- Question (who7−stat6250): Is there other keywords that can be used when we define our range?



[Course Textbook Chapter 7, Problem 8]
- Question(pcheng14-stat6250): Why should we used FORMAT statement in either a DATA step or a PROC step?
- *Question* (cli19−stat6250): What are the pros and cons to a temporary association versus a permanent association between formats and variables?
- *Question* (aacharya4−stat6250): What can we make a apostrophe to appear in a label?
- *Answer* (aacharya4−stat6250): In order to make a make a apostrophe to appear in a label, we have to use two single quotation marks.
- *Question* (jbettonville-stat6250): If a format is permanently associated with a variable by using FORMAT in a DATA step, can another format be temporarily applied by using FORMAT to choose another format in a PROC step in reference to the same variable?
- Question (who7−stat6250): Can we save the temp FORMAT statement afterward?



[Course Textbook Chapter 8, Problem 1]
- Question(pcheng14-stat6250): When should we use the MEANS procedure in SAS?
- Answer(pcheng14-stat6250): When we solve the mathematic problems, we can use it.
- *Question* (cli19−stat6250): How does PROC MEANS deal with missing values?
- *Answer* (cli19−stat6250): Missing values are not included in the calculation (unless specified with "missing"), and sample size is (N) will show the total number of non-missing rows.
- *Question* (aacharya4−stat6250): Why is the purpose of using MAXDEC option in PROC MEANS statement?
- *Answer* (aacharya4−stat6250): By default, PROC MEANS statement displays the entire width of numeric variable. MAXDEC option in PROC MEANS statement is used to limit it to specified number of decimal places. 
- *Question* (jbettonville-stat6250): How could we create a procedure that invokes specific keywords used in the MEANS statement? I.e. Could a user create a single function that outputs only Median, Mode, and Standard Error when called, without needing to specify this collection of keywords more than once?
- *Answer* (jbettonville-stat6250): This could be accomplished with a macro declaration and call, such as:
```%LET mmse = median mode stderr;
proc means data=mydata &mmse.;
run;
```
- Question (who7−stat6250): What is the main difference between PROC MEAN and PROC SUMMARY?



[Course Textbook Chapter 8, Problem 2]
- Question(pcheng14-stat6250): What is the meaning of “Deplane” in SAS?
- *Question* (cli19−stat6250): If variables do not have the same prefixes, what are other ways to select a range of variables?
- *Answer* (cli19−stat6250): Another way to select a range of variables is by using the colon (:). For example, specifying "var m:" will include all variables that start with the letter "m".
- *Question* (aacharya4−stat6250): What is the purpose of using "var" statement in PROC MEANS? 
- *Answer* (aacharya4−stat6250): The purpose of using "var" in PROC MEANS statement is to specify the variables in the dataset for which PROC MEANS is applied.
- *Question* (jbettonville-stat6250): Would the statement "by boarded transfer deplane" create separate analyses breakdowns for each combination of unique values of variables Boarded, Transfer, and Deplane? Does SAS limit the number of breakdowns that can be created in a single PROC step?
- Question (who7−stat6250): What happens when you accidentally put a var that does not exist?



[Course Textbook Chapter 8, Problem 4]
- Question(pcheng14-stat6250): What is meaning of BY-group processing?
- *Question* (cli19−stat6250): By which variables should the data set be sorted prior to using the BY statement in PROC MEANS?
- *Question* (aacharya4−stat6250): What should be done before using the "BY" group processing?
- *Answer* (aacharya4−stat6250): "BY" group processing needs already indexed or sorted data, hence we need to run PROC SORT before using BY group processing.
- *Question* (jbettonville-stat6250): What happens if you attempt to use BY with data that has not already been sorted or indexed in the order of the BY variables?
- Question (who7−stat6250): When is the best scenario to use BY and when to use VAR?



[Course Textbook Chapter 8, Problem 7]
- Question(pcheng14-stat6250):Besides PROC FREQ, do we have other ways to create a table of frequencies and percentages?
- *Question* (cli19−stat6250): Does PROC FREQ also count the number and percent of missing values?
- *Answer* (cli19−stat6250): Under the "tables" statement, "missing" needs to be specified in order to include rows with missing values to the summary table. Otherwise, SAS excludes these by default and shows the total number missing at the bottom of the table.
- *Question* (aacharya4−stat6250): How is the purpose of using TABLES statement in PROC FREQ ?
- *Answer* (aacharya4−stat6250): The purpose of using TABLES statement in PROC FREQ is to determine the order in which the variables appear in the PROC FREQ report.
- *Question* (jbettonville-stat6250): Does PROC FREQ have any options that would cause character strings that are equal except for capitalization to be considered identical for purposes of counting? I.e. "Place" counted in the same group as "PLACE"?
- Question (who7−stat6250): Is there other keywords taht you can ues like in PROC MEAN?



[Course Textbook Chapter 8, Problem 8]
- Question(pcheng14-stat6250): When should we use the frequency distributions in SAS?
- *Question* (cli19−stat6250): Aside from PROC FREQ or PROC MEANS, what would be an alternative way for examining the distribution for numeric values?
- *Question* (aacharya4−stat6250): Why frequency distributions do not work well with continous and unique values?
- *Question* (jbettonville-stat6250): Under what, if any, circumstances might we want to use FREQ with continuous numerical data rather than categorical data?
- Question (who7−stat6250): Can we combine certain variables to count together in PROC FREQUENCY?



[Course Textbook Chapter 8, Problem 10]
- Question(pcheng14-stat6250): Is PROC FREQ the best step to create or produce the table in Figure 8.28 in textbook?
- *Question* (cli19−stat6250): Can the order of the levels in categorical values we see in the table be manipulated?
- *Question* (aacharya4−stat6250): What is the purpose of using NOFREQ option in PROC FREQ statement?
- *Answer* (aacharya4−stat6250): The purpose of using NOFREQ option in PROC FREQ statement is to suppress the cell frequencies.
- *Question* (jbettonville-stat6250): Beyond the options shown in this chapter, what other options can be applied after a slash in a TABLES statement to alter the appearance of a table when using the FREQ procedure?
- Question (who7−stat6250): Can we use SAS to create a table similar to OLAP cube?



[recipe_for_summarizing_quantitative_values Week 4 Recipe]
- Question(pcheng14-stat6250): When should we use “Output Delivery System” in SAS?
- *Question* (cli19−stat6250): Is it possible to subset data in PROC MEANS (i.e. summarizing for x number of observations)?
- *Question* (aacharya4−stat6250): What is the purpose of using "class" statement in PROC MEANS? 
- *Answer* (aacharya4−stat6250): The purpose of using "class" statement in PROC MEANS is to group the PROC MEANS output by the values of variables mentioned in the class statement.
- *Question* (jbettonville-stat6250): How might we use options with PROC MEANS to exclude variables with a number of observations beneath a certain threshold from the output?
- Question (who7−stat6250): Which are the most often uses PROC statement in statistical anlysis?
- Answer (who7−stat6250): PROC MEAN and PROC FREQUENCY are some of the most often use PROC statments.



[recipe_for_summarizing_qualitative_values Week 4 Recipe]
- Question(pcheng14-stat6250): Have any better way can we summarize the qualitative data in SAS?
- *Question* (cli19−stat6250): Is there a limit on how many levels per variable can be cross-tabulated?
- *Question* (aacharya4−stat6250): How to create two way table using TABLES statement in PROC FREQ?
- *Answer* (aacharya4−stat6250): In PROC FREQ, the TABLES statement contains the keyword "tables" followed by the two variable names joined by asterisk(*). The first varible represents the rows while the second variable represents the columns in PROC FREQ output table.
- *Question* (jbettonville-stat6250): How would the LABEL function be used in a FREQ procedure to alter the headers in the resulting output table?
- Question (who7−stat6250): What are the ways to summarize your data set?
- Answer (who7−stat6250): You can create two-way tables or one-way tables or even present your data as a list.



[recipe_for_temporarily_binning_values Week 4 Recipe]
- Question(pcheng14-stat6250): When should we have to temporarily binning values in SAS?
- *Question* (cli19−stat6250): Does the order of the statements within PROC FREQ matter? That is, can the "format" statement precede the "table" statement?
- *Question* (aacharya4−stat6250): How can we permanently associate a format with a variable?
- *Answer* (aacharya4−stat6250): A varible can be permanently associated with a format if the format is defined in the data step.
- *Question* (jbettonville-stat6250): Can implicit ranges with half-closed intervals be written with the inclusive term on the right-hand side, as in (.36-.67] instead of [.36-.67)?
- *Answer* (jbettonville-stat6250): Changing the format of a label in a VALUE statement from .36-<.67 to .36<-.67 does not cause an error to occur when the statement runs, so this construction appears to be syntactically valid.
- Question (who7−stat6250): how can we avoid edge cases when binning values?
- Answer (who7−stat6250): We can use the keywords low or high to avoid edge cases when binning values.



