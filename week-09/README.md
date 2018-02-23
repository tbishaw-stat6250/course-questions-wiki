## Week 9 Quiz Questions and Answers

In order to prepare your Week 9 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-9" in your fork of this repo. Then, after all edits have been made/committed, your Week 9 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-9 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 14, Problem 1]
- *Question* (asharda-stat6250): Why do you need a DO loop?
- *Answer* (asharda-stat6250): You can execute SAS statements repeatedly by placing them in a DO loop. DO loops can execute any
number of times in a single iteration of the DATA step.



[Course Textbook Chapter 14, Problem 2]
- *Question* (asharda-stat6250): How are number of iterations determined in a DO step?.
- *Answer* (asharda-stat6250): The number of iterations is determined by the DO statement's stop value.



[Course Textbook Chapter 14, Problem 3]
- *Question* (asharda-stat6250): Using a DO loop how will you perform repetitive calculations starting at 1 and looping 25 times. 
- *Answer* (asharda-stat6250): do count=1 to 25;



[Course Textbook Chapter 14, Problem 4]
- *Question* (asharda-stat6250): What is the use of TO clause in DO statement
- *Answer* (asharda-stat6250): The TO clause specifies the stop value. The stop value is the last index value that executes the DO loop. 



[Course Textbook Chapter 14, Problem 5]
- *Question* (asharda-stat6250): What is the use of OUTPUT statement ?
- *Answer* (asharda-stat6250): The OUTPUT statement overrides the automatic output at the end of the DATA step. 



[Course Textbook Chapter 14, Problem 6]
- *Question* (asharda-stat6250): What is the numbe rof observations based on ?
- *Answer* (asharda-stat6250): The number of observations is based on the number of times the OUTPUT statement executes.



[Course Textbook Chapter 14, Problem 7]
- *Question* (asharda-stat6250): Which statements do you use to loop  when number of iterations is fixed?.
- *Answer* (asharda-stat6250):  DO WHILE and DO UNTIL statement.



[Course Textbook Chapter 14, Problem 8]
- *Question* (asharda-stat6250): When is DO UNTIL condition evaluated?.
- *Answer* (asharda-stat6250):  The DO UNTIL condition is evaluated at the bottom of the loop, so the enclosed statements are always excecuted at least once.



[Course Textbook Chapter 14, Problem 9]
- *Question* (asharda-stat6250): When is DO WHILE loop evaluated?.
- *Answer* (asharda-stat6250): DO WHILE loop is evaluated at the top of the loop.



[Course Textbook Chapter 14, Problem 10]
- *Question* (asharda-stat6250): What is difference between DO UNTIL and DO WHILE statements?



[Course Textbook Chapter 15, Problem 1]
- *Question* (asharda-stat6250): What does an ARRAY statement do?.
- *Answer* (asharda-stat6250):  It merely defines an array.



[Course Textbook Chapter 15, Problem 2]
- *Question* (asharda-stat6250): What does the value in parentheses indicate?.
- *Answer* (asharda-stat6250):  The value in parentheses indicates the number of elements in the array.



[Course Textbook Chapter 15, Problem 3]
- *Question* (asharda-stat6250): Which variable represents the values of the array elements in the DO statement.
- *Answer* (asharda-stat6250):  Index variable represents the values of the array elements in the DO statement.



[Course Textbook Chapter 15, Problem 4]
- *Question* (asharda-stat6250): What does an index value represents .
- *Answer* (asharda-stat6250):  The index value represents the position of the array element.



[Course Textbook Chapter 15, Problem 5]
- *Question* (asharda-stat6250): How do you process all the elements in an array?
- *Answer* (asharda-stat6250):  To process all the elements in an array, you can either specify the array dimension or use the DIM function with the array name as the argument.



[Course Textbook Chapter 15, Problem 6]
- *Question* (asharda-stat6250): How do you process all the elements in an array?
- *Answer* (asharda-stat6250):  To process all the elements in an array, you can either specify the array dimension or use the DIM function with the array name as the argument.



[Course Textbook Chapter 15, Problem 7]
- *Question* (asharda-stat6250): Which  variables can be created by an ARRAY statement.
- *Answer* (asharda-stat6250):  Either numeric or character variables can be created by an ARRAY statement. 



[Course Textbook Chapter 15, Problem 8]
- *Question* (asharda-stat6250): How do you reference the elements of an array.



[Course Textbook Chapter 15, Problem 9]
- *Question* (asharda-stat6250): How do you create  create temporary array elements?



[recipe_to_create_unique_record_id Week 9 Recipe]
- *Question* (asharda-stat6250): What happens during compilation phase of data step?.



[recipe_to_disaggregate_counts_data Week 9 Recipe]
- *Question* (asharda-stat6250): What is the use of where not statement?.


