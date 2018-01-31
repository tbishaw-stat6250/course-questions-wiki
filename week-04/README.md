## Week 4 Quiz Questions and Answers

In order to prepare your Week 4 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-4" in your fork of this repo. Then, after all edits have been made/committed, your Week 4 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-4 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 7, Problem 3]
- Question (tbishawstat6250): What format is a PROC FORMAT stored in? And what happens if the SAS libary does not contain a fomrat catalog?   
- Answer (tbishawstat6250): Anytime a PROC FORMAT is uese to create a format, the format is stored in a format catlog. If the SAS libary does not already contain a fortmat catalog, SAS automatically creates one.  



[Course Textbook Chapter 7, Problem 4]
- Question (tbishawstat6250): How do you specify a non-inclusive range of numeric values to avoid overlapping?   



[Course Textbook Chapter 7, Problem 5]
- Question (tbishawstat6250): What order does SAS search for the fromat JOBFMT in the two libraries?   
- Answer (tbishawstat6250): SAS seraches for the temporary libary refrence by the libref Work and then the permanent libary refernced by the by the libref Library. 



[Course Textbook Chapter 7, Problem 6]
- Question (tbishawstat6250): Is there a difference between placing the FORMAT statement in either a DATA step or a PROC step?   
- Answer (tbishawstat6250): When placing the Format statement in a DATA step, you can permananetly associate a format with a variable. 



[Course Textbook Chapter 7, Problem 7]
- Question (tbishawstat6250): What are the key steps to remember when associating a format with a variable?  
- Answer (tbishawstat6250): You have to use the same format name in the FORMAT statement that you specified in the VALUE statement. And you have to place a period at the end of the format name when it is used in the FORMAT statement.  



[Course Textbook Chapter 7, Problem 8]
- Question (tbishawstat6250): Why is it necessary to add the key word FMTLIB to the PROC FORMAT statement when you're building a large catalog of permanent formats? 



[Course Textbook Chapter 8, Problem 1]
- Question (tbishawstat6250): What actions does the BESTw. format perform?    
- Answer (tbishawstat6250): The BESTw. format is the default format that SAS uses for writing numeric values. When there is no format specification, SAS chooses the format that provides the most informaiton about the value accorind to the avaible field width. 



[Course Textbook Chapter 8, Problem 2]
- Question (tbishawstat6250): What are CLASS variable used for? And are CLASS variables characters or numbers?  



[Course Textbook Chapter 8, Problem 4]
- Question (tbishawstat6250): What is the key difference between BY and CLASS variables?  



[Course Textbook Chapter 8, Problem 7]
- Question (tbishawstat6250): How can you create an output SAS data set?  
- Answer (tbishawstat6250): You can create an output SAS data set using the OUTPUT statemnt in PROC MEANS.  



[Course Textbook Chapter 8, Problem 8]
- Question (tbishawstat6250): What is the FREQ proceduce used for?   



[Course Textbook Chapter 8, Problem 10]
- Question (tbishawstat6250): When do you add the NOCUM option to your TABLES statement?  
- Answer (tbishawstat6250): Adding the NOCUM option to your TABLES statement suproessed the display of cumlative frequenceis and cumaltive percentages in one-way frequency tables and in list output.  



[recipe_for_summarizing_quantitative_values Week 4 Recipe]
- Question (tbishawstat6250): What are the two basic statstical PROCS in SAS?   
- Answer (tbishawstat6250): PORC MEANS along with PROC FREQ are the two basic stastical PROCS in SAS and they cover most cases for explanatory data analysis. 



[recipe_for_summarizing_qualitative_values Week 4 Recipe]
- Question (tbishawstat6250): How can you specify the variables to include in PROC MEANS output?
- Answer (tbishawstat6250): In order to specify the varibles to include in PROC MEANS output, you have to list them in a VAR statment. 



[recipe_for_temporarily_binning_values Week 4 Recipe]
- Question (tbishawstat6250): How do you supress table information?
- Answer (tbishawstat6250): You can supress the display of specific statistics by adding one or more options to the TABLES statement, such as: NOFREQ supresses cell frequencies, NOPRECENT supresses cell percentages, NOROW supresses row percentages, and NOCOL supresses column percentages. 



