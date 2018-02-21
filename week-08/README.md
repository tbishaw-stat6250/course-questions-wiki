## Week 8 Quiz Questions and Answers

In order to prepare your Week 8 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-8" in your fork of this repo. Then, after all edits have been made/committed, your Week 8 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-8 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 13, Problem 1]
- *Question* (who7-stat6250): How can we show results in table format after using SAS function?



[Course Textbook Chapter 13, Problem 2]
- *Question* (who7-stat6250): Will SAS convert charactor value to numeric value?
- *Answer* (who7-stat6250): Yes, you can use the Put() function to achieve that. 



[Course Textbook Chapter 13, Problem 3]
- *Question* (who7-stat6250): What is the methodology use when determinging which function to use, put() or input()?
- *Answer* (who7-stat6250): We can first ask if the final varaible a character or number, then determine if the source variable is a character or a number.  Finally, if source varaible is a character, is the final varaible a character or a number.  This would help determine wether to use put() or input().



[Course Textbook Chapter 13, Problem 4]
- *Question* (who7-stat6250): In what other instances where we will use "||" in sas?



[Course Textbook Chapter 13, Problem 5]
- *Question* (who7-stat6250): How do we figure out when systemcutoff date is?



[Course Textbook Chapter 13, Problem 6]
- *Question* (who7-stat6250): Is there a methodology to when to use scan or substr function?
- *Answer* (who7-stat6250): Scan will select a portion of the original string where substr can take out a part of it.  So if the word is seperated by spaces, scan would be great while if it isn't, then substr.



[Course Textbook Chapter 13, Problem 7]
- *Question* (who7-stat6250): Is there a limit on how long a substring can be?



[Course Textbook Chapter 13, Problem 10]
- *Question* (who7-stat6250): Can we update exisitng dataset by using SAS function to rewrite the dataset?



[recipe_for_isolating_all_duplicates Week 8 Recipe]
- *Question* (who7-stat6250): What is the main advantage by using the first and last variable to remove duplicates verse using the proc sort method shown in Week 3?



[recipe_for_drop_and_swap Week 8 Recipe]
- *Question* (who7-stat6250): What other scenerio would we prefer to sort the data by coverting them to character first?


