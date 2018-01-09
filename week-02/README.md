
## Week 2 Quiz Questions and Answers

In order to prepare your Week 2 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-2" in your fork of this repo. Then, after all edits have been made/committed, your Week 2 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-2 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 1, Problem 1]
- *Question* (jbettonville-stat6250): If a value is missing from a data set, how does this impact analysis processes that are run on the data set? Does a command fail due to a missing value, or does it disregard the record? Is there a way to specify how SAS should behave when values are missing?


[Course Textbook Chapter 1, Problem 2]
- *Question* (jbettonville-stat6250): Most programming languages have specific style standards when writing code that describe proper indentation, control structures, and use of whitespace; are there any common formatting conventions we should follow when creating SAS recipes?


[Course Textbook Chapter 1, Problem 3]
- *Question* (jbettonville-stat6250): When dealing with data from an outside source that contains numerical values in a predictable format that contain non-numerical values (i.e. 3456_1), how might one parse a value into two separate column values in a record (i.e. a record with 3456 in one column and 1 in another)?


[Course Textbook Chapter 1, Problem 4]
- *Question* (jbettonville-stat6250): Since numerical values are always represented by floating point numbers in SAS, is there any danger of strange behavior when running calculations (i.e. 1.1 + 1.1 + 1.1 + 4 = 7.300000000000001 instead of 7.3)? If so, is there any method of accounting for this issue?


[Course Textbook Chapter 1, Problem 5]
- *Question* (jbettonville-stat6250): Is there a preferred naming convention for SAS variables that conforms to the limitations on the names of variables? (i.e. Is there a preference between ListOfObjects, list_of_objects, listOfObjects, or another format?)
- *Answer* (jbettonville-stat6250): A reading at the SAS Community website (http://www.sascommunity.org/wiki/Style_guide_for_writing_and_polishing_programs) has suggestions for formatting conventions, such as generally using lowercase (with a few exceptions). However, the style guide contradicts the way the macro name and the instances of *proc* are formatted in this week's SAS recipes, so it is possible that these suggestions are somewhat flexible.


[Course Textbook Chapter 1, Problem 8]
- *Question* (jbettonville-stat6250): What would happen if you were to specify a length for a numerical variable, and then were to encounter an observation that contained a value that is too large to be represented within the specified length?
- *Answer* (jbettonville-stat6250): This may result in a loss of precision without any warning being given, according to the following article which describes what happens in this situation: http://www.pauldickman.com/teaching/sas/length.php


[Course Textbook Chapter 2, Problem 3]
- *Question* (jbettonville-stat6250): In several instances within SAS, it appears that the default format for writing dates is *DATE9.* (e.g. 08JAN2018); is there an historical reason behind the prevalence of this date format in SAS instead of format that could be more easily sorted, such as YYYYMMDD (e.g. 20180108)?


[Course Textbook Chapter 2, Problem 7]
- *Question* (jbettonville-stat6250): What is the reasoning behind limiting the length of a libref to only eight characters?


[Course Textbook Chapter 2, Problem 8]
- *Question* (jbettonville-stat6250): As we approach the year 2020, has there been any discussion within the SAS community about when it would be appropriate to update the default YEARCUTOFF= option from 1920 to another year?


[Course Textbook Chapter 2, Problem 9]
- *Question* (jbettonville-stat6250): In some programming environments, it is possible to save the current session or workspace, including all variables and structures that are currently in use, so that work can be resumed at a later time and/or in another location with the same conditions; is there a way to do this within SAS, and if so, can it be automated?


[basic_recipe_for_loading_data_from_remote_Excel_file Week 2 Recipe]
- *Question* (jbettonville-stat6250): In other languages, certain functions can only be called after a specific library has been loaded. It appears that SAS can natively handle http requests and parsing Excel files, but are there other file formats or methods of reading in data sets that require additional preparation within SAS first?
- *Answer* (jbettonville-stat6250): Regarding SAS's ability to read other file formats, this is discussed in the SAS Certification Prep Guide in chapter 2; page 50 has a listing of the various file formats that are supported by engines within SAS.

[bonus_advanced_recipe_for_loading_data_from_remote_Excel_file Week 2 Recipe]
- *Question* (jbettonville-stat6250): Can macros be saved into external packages that can then be loaded and called without including the original SAS recipe in the text of the workspace?
