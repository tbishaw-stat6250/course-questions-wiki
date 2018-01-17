
## Week 3 Quiz Questions and Answers

In order to prepare your Week 3 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-3" in your fork of this repo. Then, after all edits have been made/committed, your Week 3 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-3 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 3, Problem 1]
- Question (ljiang11−stat6250): why the format is important?
- Answer (ljiang11−stat6250): Because SAS is free free format, keeping an organized format would be easier for developers to read.
- *Question* (jcanfield3-stat6250): What makes the Quit function different than the Run function?



[Course Textbook Chapter 3, Problem 2]
- Question (ljiang11−stat6250): Why clear the log window?
- *Question* (jcanfield3-stat6250): Are there a set number of mispellings that SAS can still run through? (Like dat is treated as data)



[Course Textbook Chapter 3, Problem 3]
- Question (ljiang11−stat6250): Why it shows "PROC PRINT running"?
- *Question* (jcanfield3-stat6250): Why does the program not recognize a ';' as the end of an unmatched quote?
- *Answer* (jcanfield3-stat6250): Because the ';' could be intended to be within a quotation, and thus not a suitable solution for all cases.


 
[Course Textbook Chapter 3, Problem 4]
- Question (ljiang11−stat6250): What would happen if it is a typo?
- Answer (ljiang11−stat6250): SAS will continue processing, and displays a warning in log window.
- *Question* (jcanfield3-stat6250): Why does SAS still process through some errors?



[Course Textbook Chapter 3, Problem 5]
- Question (ljiang11−stat6250): What are the rules of SAS usage?
- *Question* (jcanfield3-stat6250): Are there other syntax errors besides spelling errors?



[Course Textbook Chapter 3, Problem 6]
- Question (ljiang11−stat6250): In what situation a "PROC running" message would occur?
- *Question* (jcanfield3-stat6250): Where can you find a list of possible options?
- *Answer* (jcanfield3-stat6250): You click Help -> SAS Help and Documentation.



[Course Textbook Chapter 3, Problem 7]
- Question (ljiang11−stat6250): What does set keyword do?
- *Question* (jcanfield3-stat6250): Why does proc print need the label option in order for the label to work?



[Course Textbook Chapter 3, Problem 10]
- Question (ljiang11−stat6250): Will there be any message in log window?
- *Question* (jcanfield3-stat6250): Can you tell if a continuous "DATA step running" is due to a run missing or long compiling time, without looking at the code?



[Course Textbook Chapter 4, Problem 1]
- Question (ljiang11−stat6250): How many varaibles will be genereated from the code of choice d?
- Answer (ljiang11−stat6250): 5, first two cloumns are identical, both are date.
- *Question* (jcanfield3-stat6250): Is there a limit on the number of variables that can be used for an ID?



[Course Textbook Chapter 4, Problem 3]
- Question (ljiang11−stat6250): Can I write where style in ('RANCH',"SPLIT",'TWOSTORY');?
- Answer (ljiang11−stat6250): As long as the single quotation mark and double quotation mark are not used on the same word, it will be fine.
- *Question* (jcanfield3-stat6250): Can you use more than one compound WHERE operator in a single statement?



[Course Textbook Chapter 4, Problem 4]
- Question (ljiang11−stat6250): Is a comma needed before out?
- Answer (ljiang11−stat6250): No.
- *Question* (jcanfield3-stat6250): Do I need to specify work, when naming an output file?



[Course Textbook Chapter 4, Problem 7]
- Question (ljiang11−stat6250): Is it a syntax error that by statement is missing in PROC SORT step?
- *Question* (jcanfield3-stat6250): In the book solution is the second run statement missing a semicolon?
- *Answer* (jcanfield3-stat6250): Yes it is, the book has a typo, since the semicolon is there in the chapter quiz originally.



[Course Textbook Chapter 4, Problem 9]
- Question (ljiang11−stat6250): In what situation, a parenthesis is necessary?
- *Question* (jcanfield3-stat6250): What's the point of having multiple ways of saying the same operator in SAS (like le vs <=)?



[Course Textbook Chapter 4, Problem 10]
- Question (ljiang11−stat6250): How can we remove first column?
- Answer (ljiang11−stat6250): By adding option noobs;
- *Question* (jcanfield3-stat6250): What happens when you try to proc print and empty data set?



[recipe_to_check_for_duplicates Week 3 Recipe]
- Question (ljiang11−stat6250): what is the mechanism of keyword "nodupkey"?
- *Question* (jcanfield3-stat6250): When can isolating duplicate rows be useful?



[recipe_for_sorting_data Week 3 Recipe]
- Question (ljiang11−stat6250): Why the out= is necessary?
- Answer (ljiang11−stat6250): Because otherwise the original data will be overwritten.
- *Question* (jcanfield3-stat6250): Are "stable" datasets unpreffered?



[recipe_for_printing_values Week 3 Recipe]
- Question (ljiang11−stat6250): How to show the last 20 observations?
- *Question* (jcanfield3-stat6250): Is the obs= only capable of showing the first 'x' rows?  What if I didn't want the first row?


