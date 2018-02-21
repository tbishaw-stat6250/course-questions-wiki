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
- Question(pcheng14-stat6250):When specifying a variable list, do we have to be sure to precede the list with the word OF?
- Answer(pcheng14-stat6250):Yes, we do.
- Question(dfei-stat6250): What is coding format to calculates the average of the variables a, b, c?
- Answer(dfei-stat6250): It is mean(of a-b).



[Course Textbook Chapter 13, Problem 2]
- Question(tchan49-stat6250):Under what situations, SAS automatically converts characters variables to numeric values? 
- Question(pcheng14-stat6250):When will SAS automatically converts the character values of PayRate to numeric values?
- Answer(pcheng14-stat6250):When this DATA step is executed.
- Question(dfei-stat6250): What will happen in SAS when a character variable calculate with a numeric one?
- Answer(dfei-stat6250): Sas will convert character to numeric to meet the calculation if possible.



[Course Textbook Chapter 13, Problem 3]
- Question(tchan49-stat6250):When you want to explicitly covert character to numeric, do you use PUT statement? 
- Answer(tchan49-stat6250):No, you would use INPUT(souce, informat)
- Question(pcheng14-stat6250):When should we use the INPUT function?
- Answer(pcheng14-stat6250):When we explicitly convert character values to numeric values.
- Question(dfei-stat6250): What is "put" statement mean in SAS programming? How does it work?



[Course Textbook Chapter 13, Problem 4]
- Question(tchan49-stat6250):When you want to explicitly covert numeric to character, do you use INPUT statement? 
- Question(pcheng14-stat6250):When should we use the PUT function?
- Question(dfei-stat6250): What does SiteNum value mean?
- Answer(dfei-stat6250): It is a numeric character shows the location in computers.



[Course Textbook Chapter 13, Problem 5]
- Question(tchan49-stat6250):Do MDY function accept two-digit values for the year?
- Answer(tchan49-stat6250):Yes, but SAS interprets two-digit values according to the 100-year span that is set by the YEARCUTOFF=. 
- Question(pcheng14-stat6250):What is the meaning of MDY function?
- Question(dfei-stat6250): What is DMY statement when I want to know the day after 1000 days after special day?



[Course Textbook Chapter 13, Problem 6]
- Question(tchan49-stat6250):When SCAN is used, do you hava to list the delimiters?
- Question(pcheng14-stat6250):When and why should we use the SCAN function?
- Question(dfei-stat6250): What is the difference between State=scan and State=substr statements?



[Course Textbook Chapter 13, Problem 7]
- Question(tchan49-stat6250):What happens if you omitt n in SUBSTR function?
- Answer(tchan49-stat6250):All remaining characters are inclued in the substring.
- Question(pcheng14-stat6250):What is the SUBSTR function?
- Question(dfei-stat6250): How to assign MDY character to a new variable?



[Course Textbook Chapter 13, Problem 10]
- Question(tchan49-stat6250):What is the benefit of FIND statement over INDEX statement?
- Question(pcheng14-stat6250):Besides using the INDEX function in a subsetting IF statement, when can we use it?
- Question(dfei-stat6250): How to create a subset of the data in which the values of Finish contain the string? 



[recipe_for_isolating_all_duplicates Week 8 Recipe]
- Question(tchan49-stat6250):Why is it important to isolat all deplicated keys? Is this step necessary? 
- Question(pcheng14-stat6250):Why should we sort the data with respect to the unique id schema?
- Question(dfei-stat6250): In the short video, the example show us "if...then..." statement, is "then" necessary or not?



[recipe_for_drop_and_swap Week 8 Recipe]
- Question(tchan49-stat6250):What is the function kd? What does it do when extracting character variables? 
- Question(pcheng14-stat6250):What is the meaning of "business logic"?
- Question(dfei-stat6250): How many ways can we rename variables in SAS programming?


