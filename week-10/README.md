## Week 10 Quiz Questions and Answers

In order to prepare your Week 10 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-10" in your fork of this repo. Then, after all edits have been made/committed, your Week 10 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-10 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 16, Problem 1]
- Question (tbishaw-stat6250): What is the difference between standard and nonstandard numeric data?    



[Course Textbook Chapter 16, Problem 5]
- Question (tbishaw-stat6250): How does SAS read a blank field? 
- Answer (tbishaw-stat6250): A blank filed is read as missing and does not cause other fileds to be read incorrectly.



[Course Textbook Chapter 16, Problem 7]
- Question (tbishaw-stat6250): What does a nonstandard data values require? 
- Answer (tbishaw-stat6250): Nonstandard data values require an input style that has more flexiblity than column input.  



[Course Textbook Chapter 16, Problem 8]
- Question (tbishaw-stat6250): How many input styles does SAS provide for reading data in fixed fileds? 



[Course Textbook Chapter 16, Problem 9]
- Question (tbishaw-stat6250): What is the function of a record format?
- Answer (tbishaw-stat6250): A record format specifies how records are organized in a file. The two most common are fixed-length records and variable-length records.



[Course Textbook Chapter 17, Problem 1]
- Question (tbishaw-stat6250): What are the three primary input sytles that SAS provides?
- Answer (tibishaw-stat6250): The three primary input styles are: column, formatted, and list input.



[Course Textbook Chapter 17, Problem 2]
- Question (tbishaw-stat6250): How is Free-format read in SAS? 
- Answer (tbishaw-stat6250): Free-format data can easily be read with list input because you do not need to specify column locations of the data.  



[Course Textbook Chapter 17, Problem 4]
- Question (tbishaw-stat6250): When can we use the DSD option in SAS?   



[Course Textbook Chapter 17, Problem 5]
- Question (tbishaw-stat6250): Which SAS statement do you use to specify the length of character values? 



[Course Textbook Chapter 17, Problem 7]
- Question (tbishaw-stat6250): What are the two format modifiers used by modified list input?
- Answer (tbishaw-stat6250): The ampersand (&) modifier enables you to read character and the colon (:) modifier enables you to read non standard data values.



[Course Textbook Chapter 17, Problem 8]
- Question (tbishaw-stat6250): What is the function of the DLM option?



[Course Textbook Chapter 17, Problem 10]
- Question (tbishaw-stat6250): What are the requirements we need to follow when using list input?
- Answer (tbishaw-stat6250): Fields must be separated by at least one blank or other delimiter, fields must be read in order, left to right, and use the LENGTH statement to avoid truncating character values that are longer than eight characters. 



[basic_recipe_to_load_remote_delimited_file Week 10 Recipe]
- Question (tbishaw-stat6250): Which SAS function do you use when importing a specific delimited file?
- Answer (tbishaw-stat6250): When importing a specific delimited file in SAS you use the Fileref function.



[adv_recipe_to_load_remote_delimited_file Week 10 Recipe]
- Question (tbishaw-stat6250): What is the procedure we need to follow when exporting to a delimited external data source?


