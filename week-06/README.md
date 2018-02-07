## Week 6 Quiz Questions and Answers

In order to prepare your Week 6 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-6" in your fork of this repo. Then, after all edits have been made/committed, your Week 6 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-6 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 12, Problem 1]
- *Question* (jcanfield3-stat6250): Is it ever useful to replace previous variable contents in one-to-one matching?



[Course Textbook Chapter 12, Problem 2]
- *Question* (jcanfield3-stat6250): Do variables need to be pre-sorted for interleaving to work?



[Course Textbook Chapter 12, Problem 3]
- *Question* (jcanfield3-stat6250): How would the dataset in answer B) be formed, since there is no id to match them?



[Course Textbook Chapter 12, Problem 4]
- *Question* (jcanfield3-stat6250): In concatenating, do variables repeated throughout the datasets become merged or listed multiple times?
- *Answer* (jcanfield3-stat6250): They get listed multiple times.  They are treated as completely new observations rather than a continuation of a previous observation.



[Course Textbook Chapter 12, Problem 5]
- *Question* (jcanfield3-stat6250): How can you avoid overwriting variables?
- *Answer* (jcanfield3-stat6250): By concatenating, renaming variables, and not combining datasets with like named variables.



[Course Textbook Chapter 12, Problem 7]
- *Question* (jcanfield3-stat6250): What is the final results of the code? Do they get concatenated or merged horizontally?



[Course Textbook Chapter 12, Problem 9]
- *Question* (jcanfield3-stat6250): Which variables can be overwritten?
- *Answer* (jcanfield3-stat6250): Variables with matching id's and different contents when merging, or just different contents when one-to-one matching.



[basic_recipe_for_combining_data_horizontally Week 6 Recipe]
- *Question* (jcanfield3-stat6250): How does the Best12. format know how to decide between formats?


[adv_recipe_for_combining_data_horizontally Week 6 Recipe]
- *Question* (jcanfield3-stat6250): Why does the select function require commas to separate values rather than the usual space or semicolon?

