
## Week 2 Quiz Questions and Answers

In order to prepare your Week 2 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-2" in your fork of this repo. Then, after all edits have been made/committed, your Week 2 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-2 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************
[Course Textbook Chapter 1, Problem 1]
- *Question* (tbishaw-stat6250): Is the result of processing programs in SAS the same across all SAS programs?
- *Answer* (tbishaw-stat6250): The result of processing might vary across different SAS programs. For example, some SAS programs open interactive window so you can directly modify data, such as the REPORT window. 


[Course Textbook Chapter 1, Problem 2]
- *Question* (tbishaw-stat6250): Are there specific rules we need to follow in the file name poertion of a SAS data set name?
- *Answer* (tbishaw-stat6250): There are specific rules that apply in a SAS data set names and variable names. These rules include: can be between 1 to 32 characters long, it must begin with a letter (uppercase or lowercase) or an underscore(_) sign, and the following sequence can continue with any combination of numbers, letters, or underscores.  


[Course Textbook Chapter 1, Problem 3]
- *Question* (tbishaw-stat6250): How does a format (variable attributes) affect the way data values are written? And do SAS software’s offer variety of formats? If so what are those formats?

[Course Textbook Chapter 1, Problem 4]
- *Question* (tbishaw-stat6250): How are steps executed in SAS tracked and logged? And is the result of processing the same across different SAS programs?
- *Answer* (tbishaw-stat6250): Each time a step is executed, SAS generates a log to keep track of the processing activities and the result of the processing. And the result of processing varies across different SAS programs. While some SAS programs open an interactive window that creates output in the form of report other programs perform tasks such as sorting, which have no visible results other than messages in the log. 


[Course Textbook Chapter 1, Problem 5]
- *Question* (tbishaw-stat6250): What is a major difference between referencing a temporary SAS file versus referencing a permanent SAS file?


[Course Textbook Chapter 1, Problem 8]
- *Question* (tbishaw-stat6250): What is the difference between the two parts a SAS data set, a descriptor portion and the data portion?


[Course Textbook Chapter 2, Problem 3]
- *Question* (tbishaw-stat6250): When setting up a SAS session, what is the first step in the process? Are there other ways to assign library names?


[Course Textbook Chapter 2, Problem 7]
- *Question* (tbishaw-stat6250): If you are using other operating systems other than windows do you expect the platform-specific names and locations to be the same?
- *Answer* (tbishaw-stat6250): If you are running SAS within other operating systems other than windows the platform-specific names and locations will look different. Otherwise, SAS programming code will be the same across operating systems and environments. 


[Course Textbook Chapter 2, Problem 8]
- *Question* (tbishaw-stat6250): When you end your SAS session or delete a libref, will you have another way of accessing the files in the library?


[Course Textbook Chapter 2, Problem 9]
- *Question* (tbishaw-stat6250): What are the capabilities of a PROC DATASETS in terms of what tasks it allows users to perform?


[basic_recipe_for_loading_data_from_remote_Excel_file Week 2 Recipe]
- *Question* (tbishaw-stat6250): Is the recipe code capable of reading through the data across all the excel sheets or do we need to specify which ones to look at?


[bonus_advanced_recipe_for_loading_data_from_remote_Excel_file Week 2 Recipe]
- *Question* (tbishaw-stat6250): How is a macro variable used? And is there a limit to how many time we can refer to a macro variable in a SAS program?



