## Week 8 Quiz Questions and Answers

In order to prepare your Week 8 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-8" in your fork of this repo. Then, after all edits have been made/committed, your Week 8 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-8 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 13, Problem 1]
- *Question* (ldai4-stat6250): Are function mean(var1,var2,var3, var4) and mean(of var1-var4) same?
- *Answer* (ldai4-stat6250): Yes. they are same. But the work OF can not be omitted.



[Course Textbook Chapter 13, Problem 2]
- *Question* (ldai4-stat6250): What happens when DATA step, Salary=PayRate*hours, is executed?
- *Answer* (ldai4-stat6250): SAS automatically converts the character values of PayRate to numeric values so that the calculation can occur. A message is showed in the SAS log.



[Course Textbook Chapter 13, Problem 3]
- *Question* (ldai4-stat6250): SAS can automatically convert character values to numeric values, but why is INPUT function usually used?



[Course Textbook Chapter 13, Problem 4]
- *Question* (ldai4-stat6250): What is the difference between INPUT function and PUT function?



[Course Textbook Chapter 13, Problem 5]
- *Question* (ldai4-stat6250): Does the MDY function accept two-digit value for the year?
- *Answer* (ldai4-stat6250): Yes, SAS accepts two-digit year. But SAS interprets two_digit values according to the 100-year span that is set by the YEARCUTOFF=system option.



[Course Textbook Chapter 13, Problem 6]
- *Question* (ldai4-stat6250): How does the SCAN function work?
- *Answer* (ldai4-stat6250): The SCAN function is used to extract words from a character value when you know the order of the words, when their position varies, and when the words are marked by some delimiter.



[Course Textbook Chapter 13, Problem 7]
- *Question* (ldai4-stat6250): If we know the exact position of the substring to extract from the character value, what function is best used?



[Course Textbook Chapter 13, Problem 10]
- *Question* (ldai4-stat6250): Must the INDEX function be used in a subsetting IF statement?



[recipe_for_isolating_all_duplicates Week 8 Recipe]
- *Question* (ldai4-stat6250): How can we remove the duplicates in new data set?



[recipe_for_drop_and_swap Week 8 Recipe]
- *Question* (ldai4-stat6250): When match-merging, if we use DROP= data set option, do the dropped variables still exist in the original data set?


