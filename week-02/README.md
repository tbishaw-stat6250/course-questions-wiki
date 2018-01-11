
## Week 2 Quiz Questions and Answers

In order to prepare your Week 2 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-2" in your fork of this repo. Then, after all edits have been made/committed, your Week 2 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-2 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************

[Course Textbook Chapter 1, Problem 1]
- *Question* (aacharya4−stat6250): In SAS dataset, what does the rows and columns represent?
- *Answer* (aacharya4−stat6250): In SAS dataset, the number of rows represent the number of observations and the columns represent the variables.


[Course Textbook Chapter 1, Problem 2]
- *Question* (aacharya4−stat6250): In SAS, what is meant by a program step?
- *Answer* (aacharya4−stat6250): In SAS, a program step is defined as the part that starts with SAS keyword DATA or PROC and ends with a ";". 
The step that starts with keyword DATA is called DATA step while the one beginning with keyword PROC is called PROC step.


[Course Textbook Chapter 1, Problem 3]
- *Question* (aacharya4−stat6250): In SAS, what are the properties of character variable?
- *Answer* (aacharya4−stat6250): The properties of character variable in SAS are :
1. Character variables can be upto 32,767 bytes(the number of bytes used to store character variable)long.
2. Character variable can contain any value.
3. A blank (-) represents a missing value in character variable.

[Course Textbook Chapter 1, Problem 4]
- *Question* (aacharya4−stat6250): In SAS, how is missing value represented by numeric variable?
- *Answer* (aacharya4−stat6250): In SAS, a dot (.) represents a missing value in numeric variable.


[Course Textbook Chapter 1, Problem 5]
- *Question* (aacharya4−stat6250): If SAS, what is the criteria for a valid variable name?
- *Answer* (aacharya4−stat6250): In SAS, for a variable name to valid, the following rules should be followed:
1. The length of the variable name should not exceed 32 characters.
2. Variable name has to start with A-Z(both upper and lower cases permitted) or an Underscore followed by any combination of letters, numbers or Underscore.

[Course Textbook Chapter 1, Problem 8]
- *Question* (aacharya4−stat6250): In SAS, what are the properties of numeric variable?
- *Answer* (aacharya4−stat6250): The properties of numeric variable in SAS are :
1. Numeric variables can be upto 8 bytes(the number of bytes used to store character variable)long.
2. Numeric variable can contain only numeric value (0 to 9,+,-,., E for scientific notation).
3. A dot (.) represents a missing value in numeric variable.

[Course Textbook Chapter 2, Problem 3]
- *Question* (aacharya4−stat6250): What is the default value of YEARCUTOFF option in SAS?
- *Answer* (aacharya4−stat6250): In SAS, the default value of YEARCUTOFF option is 1920.


[Course Textbook Chapter 2, Problem 7]
- *Question* (aacharya4−stat6250): What is the explanation of the SAS code given below :
![code_2](https://user-images.githubusercontent.com/35093776/34758544-cc757cb8-f58b-11e7-8c0f-dcd0b9d8a643.png)

- *Answer* (aacharya4−stat6250): The first line of the code creates a new permanent SAS library called "sales". 
The LIBNAME statement defines libref sales and gives SAS the physical location of the SAS library "sales".
The second line of the code creates a new dataset called "totalsales". This dataset is permanently stored in the SAS library "sales".


[Course Textbook Chapter 2, Problem 8]
- *Question* (aacharya4−stat6250): What is the purpose of YEARCUTOFF option in programming statements in SAS?
- *Answer* (aacharya4−stat6250): In SAS programming, when we use two-digit year values, the YEARCUTOFF option gives the 100 year span for interpreting the two-digit year values.



[Course Textbook Chapter 2, Problem 9]
- *Question* (aacharya4−stat6250): What happens after deletion of a libref of a library in SAS?
- *Answer* (aacharya4−stat6250): Afrer deletion of a libref of a library, SAS will not be able to access the contents of the library, although the contents of the library are permanently stored in the operating system.


[basic_recipe_for_loading_data_from_remote_Excel_file Week 2 Recipe]
- *Question* (aacharya4−stat6250): What is the code to adjust the size of editor window in SAS?


[bonus_advanced_recipe_for_loading_data_from_remote_Excel_file Week 2 Recipe]
- *Question* (aacharya4−stat6250): What does the following " %<variable_name>." mean in SAS?
- *Answer* (aacharya4−stat6250): In SAS, we reference a variable in this way. It starts with the delimiter (%) and ends with the delimiter (.). variable_name signifies the name of the variable that is referenced.

