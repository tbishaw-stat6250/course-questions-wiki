
## Week 2 Quiz Questions and Answers

In order to prepare your Week 2 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-2" in your fork of this repo. Then, after all edits have been made/committed, your Week 2 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-2 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 1, Problem 1]
- Question (nshrivastava2-stat6250): What other information other than Observation and Variable output are present in Decsriptor portion.
- Answer(nshrivastava2-stat6250): The descriptor portion contains information about the attributes of each variable in the data set.The attribute information includes the variable's name, type, length, format, informat, and label



[Course Textbook Chapter 1, Problem 2]
- Question (nshrivastava2-stat6250): How the program steps form in SAS?
- Answer(nshrivastava2-stat6250): A SAS program can consist of a DATA step, a PROC step, or any combination of DATA and PROC steps.DATA steps typically create or modify SAS data sets, but they can also be used to produce custom-designed reports. PROC steps are pre- written routines that enable you to analyze and process the data in a SAS data set and to present the data in the form of a report. PROC steps sometimes create new SAS data sets that contain the results of the procedure.



[Course Textbook Chapter 1, Problem 3]
- Question (nshrivastava2-stat6250): If the Value is missing from the dataset, How it interprets for character variables.
- Answer(nshrivastava2-stat6250): For character variables, a blank represents a missing value.



[Course Textbook Chapter 1, Problem 4]
- Question (nshrivastava2-stat6250): What type of Varaible which is right justifies?


[Course Textbook Chapter 1, Problem 5]
- Question (nshrivastava2-stat6250): What is the naming convention for varibale name?


[Course Textbook Chapter 1, Problem 8]
- Question (nshrivastava2-stat6250):What is the storage bytes in character variables?
- Answer(nshrivastava2-stat6250): A variable's length (the number of bytes used to store it) is related to its type. Character variables can be up to 32,767 bytes long. In the example below, Name has a length of 20 characters and uses 20 bytes of storage.  



[Course Textbook Chapter 2, Problem 3]
- Question (nshrivastava2-stat6250):How SAS Files Are Stored ?
- Answer(nshrivastava2-stat6250): Every SAS file is stored in a SAS library, which is a collection of SAS files. A SAS data library is the highest level of organization for information within SAS.


[Course Textbook Chapter 2, Problem 7]
- Question (nshrivastava2-stat6250): How the Leap years works in all SAS version?
- Answer(nshrivastava2-stat6250): Leap years, century, and fourth-century adjustments are made automatically.Leap seconds are ignored, and SAS does not adjust for daylight saving time.



[Course Textbook Chapter 2, Problem 8]
- Question (nshrivastava2-stat6250): What is the general format of  LIBNAME statement ?


[Course Textbook Chapter 2, Problem 9]
- Question (nshrivastava2-stat6250): What is the naming convesntion of Library Name?


[basic_recipe_for_loading_data_from_remote_Excel_file Week 2 Recipe]
- Question (nshrivastava2-stat6250): How to import file from FTP or FTPs ? Does SAS has an ability to do that?
- Answer(nshrivastava2-stat6250): Yes, SAS has an ability to do the same. We need specify the link to the FTP with directory, user, Host, Passwd in order to link to the FTP. 



[bonus_advanced_recipe_for_loading_data_from_remote_Excel_file Week 2 Recipe]
- Question (nshrivastava2-stat6250):Why we use SAS Macro? How Macro is differ from the standard SAS code.
- Answer(nshrivastava2-stat6250):Though macro code takes longer to write and debug than standard SAS code but if write similar code over and over again, then macros may
make your job easier. This piece of solution I found from the web. PFD file of "SAS Macro Programming for Beginners".





