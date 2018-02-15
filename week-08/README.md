## Week 8 Quiz Questions and Answers

In order to prepare your Week 8 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-8" in your fork of this repo. Then, after all edits have been made/committed, your Week 8 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-8 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 13, Problem 1]
- Question(tchan49-stat6250):Is mean(of var1 to var4) a vaild function to calculate the average of var1, var2, var3 and var4? 
- Answer(tchan49-stat6250):No, it should be mean(of var1-var4). 



[Course Textbook Chapter 13, Problem 2]
- Question(tchan49-stat6250):Under what situations, SAS automatically converts characters variables to numeric values? 



[Course Textbook Chapter 13, Problem 3]
- Question(tchan49-stat6250):When you want to explicitly covert character to numeric, do you use PUT statement? 
- Answer(tchan49-stat6250):No, you would use INPUT(souce, informat)



[Course Textbook Chapter 13, Problem 4]
- Question(tchan49-stat6250):When you want to explicitly covert numeric to character, do you use INPUT statement? 



[Course Textbook Chapter 13, Problem 5]
- Question(tchan49-stat6250):Do MDY function accept two-digit values for the year?
- Answer(tchan49-stat6250):Yes, but SAS interprets two-digit values according to the 100-year span that is set by the YEARCUTOFF=. 


[Course Textbook Chapter 13, Problem 6]
- Question(tchan49-stat6250):When SCAN is used, do you hava to list the delimiters?



[Course Textbook Chapter 13, Problem 7]
- Question(tchan49-stat6250):What happens if you omitt n in SUBSTR function?
- Answer(tchan49-stat6250):All remaining characters are inclued in the substring.



[Course Textbook Chapter 13, Problem 10]
- Question(tchan49-stat6250):What is the benefit of FIND statement over INDEX statement?



[recipe_for_isolating_all_duplicates Week 8 Recipe]
- Question(tchan49-stat6250):Why is it important to isolat all deplicated keys? Is this step necessary? 



[recipe_for_drop_and_swap Week 8 Recipe]
- Question(tchan49-stat6250):What is the function kd? What does it do when extracting character variables? 


