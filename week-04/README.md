## Week 4 Quiz Questions and Answers

In order to prepare your Week 4 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-4" in your fork of this repo. Then, after all edits have been made/committed, your Week 4 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-4 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 7, Problem 3]
- *Question* (jbettonville-stat6250): If a dollar sign is placed in front of a format name, can a combination of character and number labels be used?
- *Answer* (jbettonville-stat6250): The values for a label can either be unique numerical values that are not surrounded by quotation marks, or unique combinations of characters surrounded by quotation marks, but not a combination of the two.



[Course Textbook Chapter 7, Problem 4]
- *Question* (jbettonville-stat6250): In a VALUE statement, could all of the labels be included on the same line, even though this would be a poor stylistic choice? Would the declaration function the same way?



[Course Textbook Chapter 7, Problem 5]
- *Question* (jbettonville-stat6250): Can a combination of character and number labels within quotes be used in a VALUE statement? I.e. could 'A1' and 'A2' be used in a VALUE statement?



[Course Textbook Chapter 7, Problem 6]
- *Question* (jbettonville-stat6250): Does the 256 character limit for labels include the quotation marks that surround the content of the label?



[Course Textbook Chapter 7, Problem 7]
- *Question* (jbettonville-stat6250): In which other contexts might we use keywords LOW, HIGH, and OTHER?



[Course Textbook Chapter 7, Problem 8]
- *Question* (jbettonville-stat6250): If a format is permanently associated with a variable by using FORMAT in a DATA step, can another format be temporarily applied by using FORMAT to choose another format in a PROC step in reference to the same variable?



[Course Textbook Chapter 8, Problem 1]
- *Question* (jbettonville-stat6250): How could we create a procedure that invokes specific keywords used in the MEANS statement? I.e. Could a user create a single function that outputs only Median, Mode, and Standard Error when called, without needing to specify this collection of keywords more than once?
- *Answer* (jbettonville-stat6250): This could be accomplished with a macro declaration and call, such as:
%LET mmse = median mode stderr;
proc means data=mydata &mmse.;
run;



[Course Textbook Chapter 8, Problem 2]
- *Question* (jbettonville-stat6250): Would the statement "by boarded transfer deplane" create separate analyses breakdowns for each combination of unique values of variables Boarded, Transfer, and Deplane? Does SAS limit the number of breakdowns that can be created in a single PROC step?



[Course Textbook Chapter 8, Problem 4]
- *Question* (jbettonville-stat6250): What happens if you attempt to use BY with data that has not already been sorted or indexed in the order of the BY variables?



[Course Textbook Chapter 8, Problem 7]
- *Question* (jbettonville-stat6250): Does PROC FREQ have any options that would cause character strings that are equal except for capitalization to be considered identical for purposes of counting? I.e. "Place" counted in the same group as "PLACE"?



[Course Textbook Chapter 8, Problem 8]
- *Question* (jbettonville-stat6250): Under what, if any, circumstances might we want to use FREQ with continuous numerical data rather than categorical data?



[Course Textbook Chapter 8, Problem 10]
- *Question* (jbettonville-stat6250): Beyond the options shown in this chapter, what other options can be applied after a slash in a TABLES statement to alter the appearance of a table when using the FREQ procedure?



[recipe_for_summarizing_quantitative_values Week 4 Recipe]
- *Question* (jbettonville-stat6250): How might we use options with PROC MEANS to exclude variables with a number of observations beneath a certain threshold from the output?



[recipe_for_summarizing_qualitative_values Week 4 Recipe]
- *Question* (jbettonville-stat6250): How would the LABEL function be used in a FREQ procedure to alter the headers in the resulting output table?



[recipe_for_temporarily_binning_values Week 4 Recipe]
- *Question* (jbettonville-stat6250): Can implicit ranges with half-closed intervals be written with the inclusive term on the right-hand side, as in (.36-.67] instead of [.36-.67)?
- *Answer* (jbettonville-stat6250): Changing the format of a label in a VALUE statement from .36-<.67 to .36<-.67 does not cause an error to occur when the statement runs, so this construction appears to be syntactically valid.


