## Week 6 Quiz Questions and Answers

In order to prepare your Week 6 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-6" in your fork of this repo. Then, after all edits have been made/committed, your Week 6 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-6 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 12, Problem 1]
- Question (who7-stat6250): Is there a way to combine 2 datasets using if loop in the proc statement?



[Course Textbook Chapter 12, Problem 2]
- Question (who7-stat6250): Why would SAS use a formatting method to differentiate different combining method instead of using a command word?



[Course Textbook Chapter 12, Problem 3]
- Question (who7-stat6250): What happens when columsn from 2 datasets have the same column name but different properties?
- Answer (who7-stat6250): Depends on how you merge the datasets.  If you are just appending them, it would just add the 2nd dataset to the 1st dataset.



[Course Textbook Chapter 12, Problem 4]
- Question (who7-stat6250): Is there a way to combine datasets by adding columns instead of adding it by row?
- Answer (who7-stat6250): Yes, you can use the BY statement to merge 2 datasets by using common unique key to combine the datasets horizontally.



[Course Textbook Chapter 12, Problem 5]
- Question (who7-stat6250): If interleaving datasets will overwrite value that is the same, what happens if one is integer and one is decimal?



[Course Textbook Chapter 12, Problem 7]
- Question (who7-stat6250): What is the preferred method to avoid overwriting? using rename or some other way?



[Course Textbook Chapter 12, Problem 9]
- Question (who7-stat6250): Would there be other ways to combine data besides using merge method?
- Answer (who7-stat6250): Yes, you can merge datasets by useing proc sql.



[basic_recipe_for_combining_data_horizontally Week 6 Recipe]
- Question (who7-stat6250): Given using proc sql would use less code to achieve the same result, would proc sql be considered advanced SAS programming?



[adv_recipe_for_combining_data_horizontally Week 6 Recipe]
- Question (who7-stat6250): How would the use of inner join and outer join in sql language affect the way the datasets are combined in proc sql?


