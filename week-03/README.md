
## Week 3 Quiz Questions and Answers

In order to prepare your Week 3 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-3" in your fork of this repo. Then, after all edits have been made/committed, your Week 3 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-3 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 3, Problem 1]
- Question (ljiang11−stat6250): why the format is important?
- Answer (ljiang11−stat6250): Because SAS is free free format, keeping an organized format would be easier for developers to read.
- *Question* (jcanfield3-stat6250): What makes the Quit function different than the Run function?
- Question (lceballos-stat6250): Will a program run if the PROC or run are not in column one?
- Answer (lceballos-stat6250): It would run but it won't be easy to read which makes it difficult to understand the purpose of the program.
- Question (ldeng11−stat6250): What are the good practing rules/styles you should follow if you want to write an easy-to-read and easy-to-maintain code? 
- *Question* (akrishnamurthy-stat6250): Is there a coding structure to be followed for SAS program and What are the good SAS coding practices?
- *Question* (cnguyen77-stat6250): What is the good format to write SAS statements when writing and editing SAS programs?
- *Answer* (cnguyen77-stat6250): Although you can write SAS statements in almost any format, a consistent layout enhances readability and enables you to understand the program's purpose. It's a good idea to begin DATA and PROC steps in column one, to indent statements within a step, to begin RUN statements in column one, and to include a RUN statement after every DATA step or PROC step.
- *Question* (shatcher4-stat6250): Why should you write SAS statements in a consistent layout?
- *Question* (jbettonville-stat6250): The text mentions that it is a "good idea" to add a RUN statement after every DATA or PROC step; does this phrasing suggest that there are circumstances under which the absence of a RUN statement after a DATA or PROC step would not cause the program to fail?
- *Answer* (jbettonville-stat6250): If there is another PROC or DATA step after the PROC or DATA step that does not have a RUN statement, the second statement will execute. However, if there is no RUN statement at the end of the final PROC or DATA step, the final step will continue to run.
- *Question* (aamiri2-stat6250): What are the advantages of editing SAS programs in the Enhanced Editor?
- *Answer* (aamiri2-stat6250):The few advantages of using Enhanced Editor are, automatic indents of the next line when pressing ENTER, multiple views of a file, creating and formatting your own keywords, and much more!
- Question (nshrivastava2-stat6250): How SAS editor behaves with different elements of SAS program ? 
- Answer(nshrivastava2-stat6250): In SAS editors, all the different elements of a SAS program (e.g. keywords, comments, quoted strings, constants and variables) show up in a different color as you type them. This can be extremely valuable in catching missing semicolons (and also un-matched quotes) as you type your program, because the program will most likely not be colored properly if you have a missing semicolon.
- *Question* (cli19−stat6250): What is the downfall to writing SAS statements in inconsistent format?
- *Answer* (cli19−stat6250): Maintaining a consistent format when writing SAS statements makes your code more readable. This is especially important when sharing code with others or revisiting old code.
- Question(dfei-stat6250): As I write and edit SAS program, do I need begin RUN statement in column one?
- Answer(dfei-stat6250): Yes, I have to do so.
- Question(pcheng14-stat6250): While people write and edit SAS programs, why should we begin RUN statements in column one?
- *Question* (aacharya4−stat6250): Why should we follow proper indentation format while writing SAS program even if SAS is a free format language?
- *Answer* (aacharya4−stat6250): Inspite of SAS being a free format language, we should use proper indentation while writing SAS programs as it enhances the readablility of SAS code making it easier to understand the program better.
- Question(tchan49-stat6250): What can you do to make your SAS statement consistent and readable? 
- Answer(tchan49-stat6250): a)begin DATA and PROC steps in column one, b) indent statements within step, c) begin RUN statements in column one, d) include a RUN statement after every DATA step or PROC steps
- Question (lsun20-stat6250): Why the RUN statements can in the column one? Is there any example?
- *Question* (ldai4-stat6250): Why it is a good idea to begin DATA and PROC step in column?
- *Answer* (ldai4-stat6250): Because a consistent layout enhances readability and enables you to understand the program’s purpose.
- Question (xyin6-stat6250): As the example shows, the statement can begin anywhere on a line, so what does "indent statements within a step" mean? 
- *Question* (tbishawstat6250): Does SAS allow you to reopen a stored program to make edits on it for resubmission?
- *Answer* (tbishawstat6250): SAS software does allow you to reopen a stored program and made edits needed to submit it again. You can open a program using: file shortcuts, My Favorite Folders, the INCLUDE command, and the Open window. 
- Question (ttruong59-stat6250): Why is a consistent layout necessary and useful when writing SAS statements?
- Answer (ttruong59-stat6250): The reason is because it enhances readability and enable program’s purpose.
- *Question* (aguenane−stat6250): Why is it useful to write your SAS programs in a consistent layout?
- *Answer* (aguenane-stat6250): This is because a consistent layout enhances readability and helps you understand the program’s purpose.
- Question (who7−stat6250): Is the idea of putting DATA and PROC on column 1 more for style or for technical reason?




[Course Textbook Chapter 3, Problem 2]
- Question (ljiang11−stat6250): Why clear the log window?
- *Question* (jcanfield3-stat6250): Are there a set number of mispellings that SAS can still run through? (Like dat is treated as data)
- Question (lceballos-stat6250): What is the statement to clear the log?
- Answer (lceballos-stat6250): "dm log 'clear;"
- Question (ldeng11−stat6250): What are the steps to debug the code?
- Answer (ldeng11−stat6250): First, check the log window to see what is the error message, then go back to the code to see the specific line of code based on the error message, then make any change if neccessary, run the code again, then check the log window again.
- *Question* (akrishnamurthy-stat6250): What is the procedure for SAS code debugging and how to re-run corrected code?
- *Answer* (akrishnamurthy-stat6250): SAS log helps to debug a code and locate the lines causing errors. Code can then be corrected by recalling the code to Program Editor window. Before resubmitting the code, it is good practice to clear the log window so that the log from new run could be verified. Resubmit the code and repeat the process until code runs successfully.
- *Question* (cnguyen77-stat6250):What is the first step you should do when you want to modify the programs that contain errors?
- *Answer* (cnguyen77-stat6250):To modify programs that contain errors, if you use the Program Editor window, you usually need to recall the submitted statements from the recall buffer to the Program Editor window, where you can correct the problems. After correcting the errors, you can resubmit the revised program. However, before doing so, it's a good idea to clear the messages from the Log window so that you don't confuse the old error messages with the new messages. Remember to check the Log window again to verify that your program ran correctly.
- *Question* (shatcher4-stat6250): What is a simple error and how are they corrected?
- *Question* (jbettonville-stat6250): Why should we revise the program before clearing the log and resubmitting a program that had a spelling error?
- *Answer* (jbettonville-stat6250): The textbook does not specify, but I imagine it would be useful to still have access to the log from the failed program so that we can verify which parts of the program were incorrect.
- *Question* (aamiri2-stat6250): How many types of error messages are there in SAS program? Are the messages shown differently as compared to an OS, UNIX, or Windows operating system?
- Question (nshrivastava2-stat6250): What are the different colors log has, to show errors/ warnings/ Notes? 
- Answer(nshrivastava2-stat6250): Log has ERROR with Red, WARNING with Green, Notes with Blue.
- *Question* (cli19−stat6250): Why is it useful to clear the Log window prior to resubmitting a corrected program?
- Question(dfei-stat6250): How can I avoid spelling errors when I am writing SAS program?
- Question(pcheng14-stat6250): In order to avoid submitted a SAS program that contains spelling errors, we should be careful when we edit SAS programs.
- Answer(pcheng14-stat6250): Yes, we have to double check before we submit it.
- *Question* (aacharya4−stat6250): Why is it a good practice to clear the messages in the log window before resubmitting the program?
- *Answer* (aacharya4−stat6250): It is a good practice to clear the log window before resubmitting the program so as to avoid any confusion with the error messages of the earlier code.
- Question(tchan49-stat6250): Before resubmitting your updated SAS statement, which window should you double-check? 
- Question (lsun20-stat6250): which window will show your error specifically?
- Answer (lsun20-stat6250): the log window will display the messages about the error.
- *Question* (ldai4-stat6250): If I didn’t find the spelling errors, what would happen after running the program?
- Question (xyin6-stat6250): How to recall the error statements if we are using the Program Editor window?
- Answer (xyin6-stat6250): you can recall submitted statements by issuing the RECALL command or by selecting **Run→Recall Last Submit**, or we can just edit them in the code editing window.
- *Question* (tbishawstat6250): Is there a specific format to write a SAS statement or can you use any format and switch between different formats?
- *Answer* (tbishawstat6250): Although there are multiple formats in which you can write SAS statements in, a consistent layout enhances readability and helps you and others understand the program’s purpose. It is recommended to begin DATA and PROC steps in column one, indent statements within step, being RUN statements in column one, and include RUN statement after every DATA step or PROC step. 
- Question (ttruong59-stat6250): How do users clear the contain errors of Log window?
- Answer (ttruong59-stat6250): Users need to recall the submitted statements from the recall buffer to the Program Editor window to correct the problem. Once the errors were updated, users then need to resubmit the revised program.
- *Question* (aguenane−stat6250): What are two ways that you can clear the contents of the SAS programming windows?
- Question (who7−stat6250): Are there any third party SAS compiler that help you identify error when you are writing the code?




[Course Textbook Chapter 3, Problem 3]
- Question (ljiang11−stat6250): Why it shows "PROC PRINT running"?
- *Question* (jcanfield3-stat6250): Why does the program not recognize a ';' as the end of an unmatched quote?
- *Answer* (jcanfield3-stat6250): Because the ';' could be intended to be within a quotation, and thus not a suitable solution for all cases.
- Question (lceballos-stat6250): If a string contains quotation marks, how can we search for it in SAS with out without running into a syntax error?
- Question (ldeng11−stat6250): Does the sum function apply to the original dataset? Or it apply to the data after the selection statement?
- *Question* (akrishnamurthy-stat6250): How are missing quotation marks handled in SAS ? 
- *Question* (cnguyen77-stat6250): What would happen if you miss a quotation mark in the LABEL statement?
- *Question* (shatcher4-stat6250): How do you correct a "PROC PRINT running" message at the top of the active window?
- *Answer* (shatcher4-stat6250): Submit a RUN statement in order to complete the PROC statement.
- *Question* (jbettonville-stat6250): In longer programs that involve several SAS statements, is it difficult to detect the location of a syntax error? What about detecting errors in which the syntax is accurate but the command does not produce the desired result, and the resulting output causes an error to occur in a later statement?
- *Question* (aamiri2-stat6250): What is the result of running a PROC PRINT statement without a RUN statement? How can this be corrected?
- *Answer* (aamiri2-stat6250):A RUN statement usually indicates the end of the step. If RUN is omitted, then there will be a message at the top of the windows screen.  To correct this error you must submit a RUN statement to complete the PROC step.
- Question (nshrivastava2-stat6250): How many messages SAS logs contain? 
- Answer(nshrivastava2-stat6250): SAS Logs contain 3 types of messages: errors, warnings, and notes.
- *Question* (cli19−stat6250): What are some ways to avoid unbalanced quotation marks?
- *Answer* (cli19−stat6250): Paying attention to the color-coding of the text when programming in SAS is helpful. Text in quotation marks usually appear purple.
- Question(dfei-stat6250): Do I have to put semicolon at the end of each line?
- Answer(dfei-stat6250): Yes, I have to do so.
- Question(pcheng14-stat6250): What is the meaning of var resthr maxhr rechr date?
- *Question* (aacharya4−stat6250): What happens when missing quotation mark is encountered by the SAS program?
- Question(tchan49-stat6250): When you miss a quotation in a SAS statement, where can you find the error message? 
- Question (lsun20-stat6250): what is the maxmum length of a quoted string?
- *Question* (ldai4-stat6250): What is some common syntax errors?
- *Answer* (ldai4-stat6250): Common syntax errors include spelling mistakes, omitting semicolons, leaving quotation marks unbalanced, and specifying invalid options.
- Question (xyin6-stat6250): Can we just simply add a quotation mark can solve the problem in the warning message?
- Answer (xyin6-stat6250): No, it usually **DOES NOT** solve the problem, SAS still considers the quotation marks to be unbalanced. We have to cancel the statements then resubmitting.
- *Question* (tbishawstat6250): What are the major capabilities of the Enhanced Editor in SAS software? 
- Question (ttruong59-stat6250): How do users correct a "PROC PRINT running" message at the top of the active window?
- *Question* (aguenane−stat6250): What is the benefit of issuing the RECALL command or selected Run -> Recall Last Submit?
- *Answer* (aguenane-stat6250): This allows you to obtain the statements you just submitted. This allows you to edit your code easily when you run into syntax errors.
- Question (who7−stat6250): Do we always have to rename data set everytime we manipulate it? Can we overwrite existing data set?



[Course Textbook Chapter 3, Problem 4]
- Question (ljiang11−stat6250): What would happen if it is a typo?
- Answer (ljiang11−stat6250): SAS will continue processing, and displays a warning in log window.
- *Question* (jcanfield3-stat6250): Why does SAS still process through some errors?
- Question (lceballos-stat6250): Are there any sort of error handling that can be done with SAS?
- Question (ldeng11−stat6250): What are the Log window and Output window using for?
- *Question* (akrishnamurthy-stat6250): Will a SAS program continue execution after encountering a step with syntax error? 
- *Question* (cnguyen77-stat6250): Will the SAS continue process the step if there is a syntax error in it?
- *Answer* (cnguyen77-stat6250): Syntax errors generally cause SAS to stop processing the step in which the error occurred. When a program that contains an error is submitted, messages regarding the problem also appear in the Log window. When a syntax error is detected, the Log window displays the word ERROR, identifies the possible location of the error, and gives an explanation of the error.
- *Question* (shatcher4-stat6250): What happens when a syntax error is detected and how is it corrected?
- *Question* (jbettonville-stat6250): Does SAS produce "warnings" instead of errors when a statement runs but produces a result that may not be what the author of the statement intended?
- *Question* (aamiri2-stat6250): What are some examples of syntax errors and what type of message will appear if it has been detected?
- Question (nshrivastava2-stat6250):How the missing RUN Statement interpret in SAS program?
- *Question* (cli19−stat6250): How can you determine the precise location of where the syntax error occurred?
- Question(dfei-stat6250): What does syntax error mean in computer programming?
- Answer(dfei-stat6250): In computer science, a syntax error is an error in the syntax of a sequence of characters or tokens that is intended to be written in a particular programming language.
- Question(pcheng14-stat6250): Can we detect the syntax error by ourselves?
- Answer(pcheng14-stat6250): Yes, it can be detected.
- *Question* (aacharya4−stat6250): What are the best possible ways to identify syntax errors in a SAS program?
- *Answer* (aacharya4−stat6250): Some of the ways to identify syntax errors in a SAS program are by using the SAS systems options in code window and DATA step debugger.
- Question(tchan49-stat6250): When you have a syntax error, can you check the error message at the Output window?
- Question (lsun20-stat6250): Which errors except Syntax error also will cause SAS to stop processing the step in which the error occurred?
- *Question* (ldai4-stat6250): Can a PROC SORT message appear at the top of the active window?
- Question (xyin6-stat6250): Do syntax errors and data errors always appear in the Log window with explanation of the error?
- Answer (xyin6-stat6250): Yes, problems with your statements or data might not be evident when you look at results in the Output window. Therefore, it is important to review the messages in the Log window each time you submit a SAS program.
- *Question* (tbishawstat6250): Where can you find the line numbers and is it located in the same place for all operating environments? 
- Question (ttruong59-stat6250): When a syntax error is detected, what is the best way to recognize and debug the error?
- *Question* (aguenane−stat6250): When debugging your programs, can you just look at the Output window?
- Question (who7−stat6250): Would there be an instance where program encounter a syntax error and continue running?



[Course Textbook Chapter 3, Problem 5]
- Question (ljiang11−stat6250): What are the rules of SAS usage?
- *Question* (jcanfield3-stat6250): Are there other syntax errors besides spelling errors?
- Question (lceballos-stat6250): What's the difference between syntax errors, data errors and logic errors?
- Question (ldeng11−stat6250): What are the common syntax errors?
- Answer (ldeng11−stat6250): Common syntax errors are misspelled keywords, omitting semicolons, quotation marks unbalanced, invalid options etc.
- *Question* (akrishnamurthy-stat6250): Are incompatible data values considered as syntax error in SAS ? 
- *Question* (cnguyen77-stat6250): What will happen if program statements do not conform to the rules of the SAS language?
- *Question* (shatcher4-stat6250): What is the difference between syntax errors and data errors?
- *Question* (jbettonville-stat6250): Is SAS backward compatible with programs written in previous versions of SAS? Will older SAS programs cause syntax errors when run in SAS 9.4?
- *Question* (aamiri2-stat6250): After correcting a syntax error, why is it important to clear the old messages from the Log window when resubmitting?
- Question (nshrivastava2-stat6250):How can SAS program interpret Error Messages ? 
- Answer(nshrivastava2-stat6250):SAS can detect several types of errors. The most common are 1) Syntax errors that occur when program statements do not conform to the rules of the SAS language. 2) Data errors that occur when some data values are not appropriate for the SAS statements that are specified in a program. 
- *Question* (cli19−stat6250): If it is not evident where errors were committed, how can you diagnose the problem?
- *Answer* (cli19−stat6250): The "Help" menu offers additional links and resources for online help.
- Question(dfei-stat6250):Will it happen some syntax errors when an invalid equation is entered into a calculator?
- Answer(dfei-stat6250): Yes, it will.
- Question(pcheng14-stat6250): How often syntax error occurs happened during per SAS programs?
- *Question* (aacharya4−stat6250): What are the different types of error that one can encounter in SAS programs?
- *Answer* (aacharya4−stat6250): The types of error encountered in a SAS program are : Syntax error, Data error, Semantic error, execution-time error.
- Question(tchan49-stat6250): Do you get syntax error when some data values are not appropriate for the SAS statement? 
- Question (lsun20-stat6250): How many tpye of error the SAS program has? Could you give at least 5 example?
- *Question* (ldai4-stat6250): How can a syntax error be modified in a submitted SAS program?
- Question (xyin6-stat6250): If the Log window indicates the procedure was not found, will any output being produced still?
- *Question* (tbishawstat6250): What actions do the following Text Editor Line Commands execute: Cn, Dn, In, Mn, Rn, A, and B?
- *Answer* (tbishawstat6250): Cn: copies n lines (where n = a number up to 9999), Dn: deletes n lines, In: inserts n blank lines, Mn, moves n lines, Rn: repeats current line n times, A: after (used with C, I, and M), B: before (used with C, I, and M)
- Question (ttruong59-stat6250): What is the main difference between syntax error and data error?
- Answer (ttruong59-stat6250): Syntax error occurs when program statements do not conform to the SAS rules while data error occurs when the values of data are not specifically specified.
- *Question* (aguenane−stat6250): What is the difference between a syntax error and a data error?
- *Answer* (aguenane-stat6250): A syntax error occurs when program statements do not conform to the rules of the SAS language while a data error occurs when some data values are not appropriate for the SAS statements that are specified in the program.
- Question (who7−stat6250): What is the main difference between syntax error and other error in SAS?



[Course Textbook Chapter 3, Problem 6]
- Question (ljiang11−stat6250): In what situation a "PROC running" message would occur?
- *Question* (jcanfield3-stat6250): Where can you find a list of possible options?
- *Answer* (jcanfield3-stat6250): You click Help -> SAS Help and Documentation.
- Question (lceballos-stat6250): If there are multiple syntax errors, does the log tell you all of them or the first one it finds?
- Question (ldeng11−stat6250): What would happen if you have an invalid option in your code?
- *Question* (akrishnamurthy-stat6250): How to correct a SAS program that failed with invalid option syntax error?
- *Question* (cnguyen77-stat6250): What will happen if you specify an option that is not valid in a particular statement?
- *Answer* (cnguyen77-stat6250): When a SAS statement that contains an invalid option is submitted, a message appears in the Log window indicating that the option is not valid or not recognized.
- *Question* (shatcher4-stat6250): How do you reslove an invalid option error?
- *Question* (jbettonville-stat6250): Besides adding KEYLABEL in a PROC command, what are some other examples of invalid options applied to SAS statements (especially ones that occur often in programs written by new SAS learners)?
- *Question* (aamiri2-stat6250): How can you resolve a problem with invalid option errors?
- Question (nshrivastava2-stat6250): What are the specification and classification of bugs discussed in SAS programing?
- Answer(nshrivastava2-stat6250): Bugs can be classified as 1) Syntax Error: missing semicolon, uninitialized variable and variable not found. 2) Data Error: Missing values were generated, numeric to character conversion, invalid data, character field is truncated.3)Logic Error:DATA step produces wrong results but no error message. 
- *Question* (cli19−stat6250): Why do some programming errors result in ERRORS while others in WARNINGS?
- Question(dfei-stat6250): How many types of invalid options in a SAS program?
- Question(pcheng14-stat6250): What is “DATA step running” meaning?
- Answer(pcheng14-stat6250): It same as “PROC running”.
- *Question* (aacharya4−stat6250): How does one avoid making "invalid option" error while writing SAS code?
- Question(tchan49-stat6250): When you have an invalid option in SAS program, is it a syntax error or data error? 
- Question (lsun20-stat6250): What is the reason may cause an invalid option in a SAS program?
- *Question* (ldai4-stat6250): Can a log message indicate spelling errors in addition to notifying the invalid option?
- Question (xyin6-stat6250): When I remove or replace the invalid option, will SAS run the whole program over again or just start from the error statement I corrected?
- *Question* (tbishawstat6250): What are some of the most common errors in SAS? Where can you review the messages to check for errors each time you submit a SAS program?
- Question (ttruong59-stat6250): How do users fix a debug error where a log message indicates an option is not valid or not recognized?
- Answer (ttruong59-stat6250): Users need to recall the program, remove or replace the invalid option, check the statement syntax and resubmit the statement.
- *Question* (aguenane−stat6250): How do you resolve an invalid option error?
- Question (who7−stat6250): Is there a better to keep track of different variables when writing code to avoid invalid option error?



[Course Textbook Chapter 3, Problem 7]
- Question (ljiang11−stat6250): What does set keyword do?
- *Question* (jcanfield3-stat6250): Why does proc print need the label option in order for the label to work?
- Question (lceballos-stat6250): Besides correcting dat with data, what else can SAS correct automatically?
- Question (ldeng11−stat6250): What would happen if you have syntax error in your code?
- *Question* (akrishnamurthy-stat6250): What kind of error is thrown for a misspelled keyword and how to correct the code for re-run?
- *Question* (cnguyen77-stat6250): Will SAS produce a warning message or an syntax error when you misspell DATA step?
- *Answer* (cnguyen77-stat6250): SAS produces only a warning message, not an error.
- *Question* (shatcher4-stat6250): Why is it important to review messages in the Log window after every submit?
- *Answer* (shatcher4-stat6250): Problems are not always evident while looking at the results in the output window.
- *Question* (jbettonville-stat6250): In the answer to this question it mentions that this is a common and interpretable error; does this mean that DAT will be interpreted as DATA in a SAS statement and run correctly?
- *Question* (aamiri2-stat6250): How common are syntax errors and what precautions can be taken to avoid such errors while using SAS program?
- Question (nshrivastava2-stat6250): What is the thumb rule for debugging? Why is so important to LISTEN TO THE SAS LOG? 
- *Question* (cli19−stat6250): What are other common syntax errors that SAS can successfully interpret and return warnings rather than erros?
- Question(dfei-stat6250): How to find a syntax error in a quick way?
- Question(pcheng14-stat6250): What is meaning of syntax error?
- *Question* (aacharya4−stat6250): What is the way to terminate a DATA step in a SAS program?
- *Answer* (aacharya4−stat6250): A DATA step in a SAS program can be terminated by using a RUN statement or by beginning another DATA step or a PROC step.
- Question(tchan49-stat6250): How can you correct the misspelling key work on a SAS statement? Do you need to re-type the entire statement? 
- Question (lsun20-stat6250): When the SAS produces only a warning message, not an error, will it influence the program running?
- *Question* (ldai4-stat6250): What statement indicates the beginning of a new step or the end of the current step?
- *Answer* (ldai4-stat6250): A DATA or PROC statement indicates the beginning of a new step; a RUN or QUIT statement indicates the end of the current step.
- Question (xyin6-stat6250): How to user Enhanced Editor for easier finding and checking syntax error?
- *Question* (tbishawstat6250): If you are missing a quotation mark and you have an unbalanced quotation mark error, how do you resolve the Error?
- Question (ttruong59-stat6250): Does SAS point out any misspelling error?
- *Question* (aguenane−stat6250): What type of errors are the following: omitting semicolons, leaving quotation marks unbalanced, specifying invalid options?
- Question (who7−stat6250): What would be the best way to avoid syntax error?



[Course Textbook Chapter 3, Problem 10]
- Question (ljiang11−stat6250): Will there be any message in log window?
- *Question* (jcanfield3-stat6250): Can you tell if a continuous "DATA step running" is due to a run missing or long compiling time, without looking at the code?
- Question (lceballos-stat6250): Why is the run statement necessary?
- Question (ldeng11−stat6250): What happen if you see the window display the message "DATA step running" for a long time?
- *Question* (akrishnamurthy-stat6250): Since SAS always executes a current step when it encounters the next PROC or DATA statement, why should a RUN statement be explicitly specified?
- *Answer* (akrishnamurthy-stat6250): Although RUN statements are not mandatory and are not considered as error,omitting RUN statements can sometimes produce unexpected results. Especially if the last step in program is not followed by RUN, the program will compile successfully but the last step will not be executed. 
- *Question* (cnguyen77-stat6250): What will happen if you forget to end the DATA step with a RUN statement?
- *Question* (shatcher4-stat6250): What are common syntax erorrs and their symptoms?
- *Question* (jbettonville-stat6250): Is there any circumstance under which it would be preferable for a RUN statement to not occur at the end of a PROC or DATA step?
- *Question* (aamiri2-stat6250): What is the purpose of DATA and RUN statements? What happens if a statement is missing one?
- Question (nshrivastava2-stat6250): How the "Unbalanced Quotation Marks" works in SAS programing? 
- Answer(nshrivastava2-stat6250):  When program has one for more unbalanced quotation marks, SAS is often unable to detect the end of the statement in which the error occurs. If unbalanced quotation marks appear in a program that contains TITLE or FOOTNOTE statements, there is sometimes a warning in the SAS log which indicates that a text string enclosed in quotation marks has become too long.
- *Question* (cli19−stat6250): How can you gauge program processing time?
- Question(dfei-stat6250): How can I fix “DATA step running” errors when programming?
- Question(pcheng14-stat6250): What kind of data values were not appropriate for the SAS statements?
- *Question* (aacharya4−stat6250): What happens when there are unbalanced Quotation marks in a DATA step of a SAS program? 
- *Answer* (aacharya4−stat6250): When there are unbalanced Quotation marks in a DATA step of a SAS program, the log window displays "DATA step running" message.
- Question(tchan49-stat6250): If you miss the RUN statement for a DATA step, what is going to display on the active window? 
- Answer(tchan49-stat6250): “DATA step running” for a long time. 
- Question (lsun20-stat6250): If you create a Endless Loop and run it, what will happen in SAS program?
- *Question* (ldai4-stat6250): Does each step need to RUN statement to end?
- Question (xyin6-stat6250): If missing a RUN statement to end the DATA step, will the previous steps being executed? Or are these steps independent from each other?
- *Question* (tbishawstat6250): What is the comment symbol in SAS? And does the SAS program execute or read the comments you make?
- Question (ttruong59-stat6250): Is each step compiled and executed independently?
- *Question* (aguenane−stat6250): Is it true that each step in a SAS program is compiled and executed independently from every other step.
- Question (who7−stat6250): Why wouldn't SAS automate the RUN; statement into the program?



[Course Textbook Chapter 4, Problem 1]
- Question (ljiang11−stat6250): How many varaibles will be genereated from the code of choice d?
- Answer (ljiang11−stat6250): 5, first two cloumns are identical, both are date.
- *Question* (jcanfield3-stat6250): Is there a limit on the number of variables that can be used for an ID?
- Question (lceballos-stat6250): What does ID statement mean?
- Question (ldeng11−stat6250): What is the "noobs" option using for?
- *Question* (akrishnamurthy-stat6250): How to omit the observation number while creating a report?
- *Question* (cnguyen77-stat6250): How to specify the data set that you want to print?
- *Answer* (cnguyen77-stat6250): “PROC PRINT DATA=SAS-data-set;” where SAS-data-set is the name of the SAS data set to be printed.
- *Question* (shatcher4-stat6250): What is the purpose of the WHERE statement?
- *Question* (jbettonville-stat6250): What happens if you do not include NOOBS in the PROC statement and do not specify an ID for the output?
- *Question* (aamiri2-stat6250): What are some errors that can happen with a PROC PRINT statement?
- Question (nshrivastava2-stat6250): Where and how and can one produce column totals for numeric variables within your report?
- Answer(nshrivastava2-stat6250): Programmers have to program in PROC statement by using keyword "SUM" to column total for numeric variables. 
- *Question* (cli19−stat6250): Is there a limit to the restrictions you can add to the "where" clause?
- Question(dfei-stat6250): Are there any other codes similar to proc print? 
- Question(pcheng14-stat6250): How many steps creates the normal PROC PRINT output?
- *Question* (aacharya4−stat6250): What is the purpose of LABEL option in SAS?
- *Answer* (aacharya4−stat6250): The LABEL option in SAS is to replace the variable name in the dataset with the label specified.
- Question(tchan49-stat6250): How can you replace Obs column with other columns? 
- Answer(tchan49-stat6250): Use ID statement 
- Question (lsun20-stat6250): What is the ID statement means?
- Answer (lsun20-stat6250): the ID statement replaces the Obs column with the specified variable.
- *Question* (ldai4-stat6250): How can you use PROC PRINT step to create a basic report?
- *Answer* (ldai4-stat6250): To produce a simple list report, you first reference the library in which your SAS data set is stored. If you want, you can also set system options to control the appearance of your reports. Then you submit a basic PROC PRINT step.
- Question (xyin6-stat6250): Does ID statement and VAR statement share the same function in isting output?
- *Question* (tbishawstat6250): What is the first step in creating a Basic Report in SAS?
- *Answer* (tbishawstat6250): To create a simple list report, you first have to reference the library in which your SAS data set is stored. 
- Question (ttruong59-stat6250): How do users specify a dataset they wanted to print out?
- *Question (aguenane−stat6250): When producing a list report, if you don’t want to list all of the variables in the data set, can you choose indiv*idual variables to show?
- Question (who7−stat6250): one of the answer attempted to change the label name of a variable, can we display variable a as "A"?



[Course Textbook Chapter 4, Problem 3]
- Question (ljiang11−stat6250): Can I write where style in ('RANCH',"SPLIT",'TWOSTORY');?
- Answer (ljiang11−stat6250): As long as the single quotation mark and double quotation mark are not used on the same word, it will be fine.
- *Question* (jcanfield3-stat6250): Can you use more than one compound WHERE operator in a single statement?
- Question (lceballos-stat6250): Can you use the In operator to only include on item?
- Question (ldeng11−stat6250): What is the "in" option using for?
- *Question* (akrishnamurthy-stat6250): How to select observations from a file based on specific values for a variable?
- *Question* (cnguyen77-stat6250): If you want to select observations based on several values, what kind of SAS statement you can use?
- *Answer* (cnguyen77-stat6250): In the WHERE statement, the IN operator enables you to select observations based on several values. You specify values in parentheses and separated by spaces or commas. Character values must be enclosed in quotation marks and must be in the same case as in the data set.
- *Question* (shatcher4-stat6250): How do you specify a condition using the WHERE statement with character variables?
- *Question* (jbettonville-stat6250): Is there a way of specifying case insensitive values in a WHERE statement?
- *Question* (aamiri2-stat6250): What is the difference between CONTAINS and WHERE statements? In what situations would you apply these to?
- Question (nshrivastava2-stat6250): How one can remove the default Obs column that displays observation numbers?
- *Question* (cli19−stat6250): Is it necessary to include commas to delimit items listed in the "in" operator?
- *Answer* (cli19−stat6250): No, SAS can process this if the list is delimited by spaces.
- Question(dfei-stat6250): Are "in" and "=" same in SAS programming?
- Question(pcheng14-stat6250): What is the meaning of “TWOSTORY”?
- *Question* (aacharya4−stat6250): Which operator in SAS is used to classify observations based on a range of values?
- *Answer* (aacharya4−stat6250): The "IN" operator in SAS is used to classify observations based on a range of values.
- Question(tchan49-stat6250): When you test for multiple values of the same variable, besides using OR in a WHERE statement, what operator can you use? 
- Question (lsun20-stat6250): Can we use double quotation marks in this situation?
- *Question* (ldai4-stat6250): What step can be used to selected observations?
- Question (xyin6-stat6250): Can I also use IN operator for selecting multiple numeric values? Is the quote sign required?
- *Question* (tbishawstat6250): Can you specify the variables you want listed from a data set when creating a report? If so which SAS statement would you need to use to do so?
- Question (ttruong59-stat6250): Is WHERE the only statement used to set conditions? 
- *Question* (aguenane−stat6250): When specifying variables with WHERE expressions, what are the two things you must do?
- Question (who7−stat6250): Can i create AND condition within a OR condition?



[Course Textbook Chapter 4, Problem 4]
- Question (ljiang11−stat6250): Is a comma needed before out?
- Answer (ljiang11−stat6250): No.
- *Question* (jcanfield3-stat6250): Do I need to specify work, when naming an output file?
- Question (lceballos-stat6250): How do you sort by descending order?
- Answer (lceballos-stat6250): With the Descending Key option (eg "by y descending x;". 
- Question (ldeng11−stat6250): Do you need to include a by statement when you sort the data?
- *Question* (akrishnamurthy-stat6250): How to sort a file temporarily for the current SAS session ?
- *Question* (cnguyen77-stat6250): Do you need to specify the data set in a PROC SORT step?
- *Answer* (cnguyen77-stat6250): In a PROC SORT step, you specify the DATA= option to specify the data set to sort. The OUT= option specifies an output data set. The required BY statement specifies the variable(s) to use in sorting the data.
- *Question* (shatcher4-stat6250): What does the SORT procedure do?
- *Question* (jbettonville-stat6250): When sorting by a variable, how do we specify the direction (ascending or descending) of the sort order?
- *Answer* (jbettonville-stat6250): By default, variables are sorted in ascending order. The option DESCENDING can be applied following BY but immediately before a variable if that variable should instead be sorted in descending order.
- *Question* (aamiri2-stat6250): What are the steps in sorting you data permanently and temporarily? 
- Question (nshrivastava2-stat6250): What is the default sorting options?Can we specify more than one variables with different sort options?
- *Question* (cli19−stat6250): What is the default sort order? 
- *Answer* (cli19−stat6250): Unless specified, SAS sorts data in ascending order by the variable(s) called.
- Question(dfei-stat6250): How can I create a temp dataset in SAS programming?
- Question(pcheng14-stat6250): When should we sort data and create a temporary data?
- *Question* (aacharya4−stat6250): What happens if when use the PROC SORT step without using the OUT option on a SAS dataset? 
- *Answer* (aacharya4−stat6250): If when use the PROC SORT step without using the OUT option on a SAS dataset, the original dataset gets sorted.
- Question(tchan49-stat6250): Do you create a temporary dataset before identifying the datatset that you want to read or after? 
- Question (lsun20-stat6250): What will happen if we code without By statement in this case?
- Answer (lsun20-stat6250): The BY statement is required in PROC SORT, without it, the PROC SORT step fails.
- *Question* (ldai4-stat6250): what is the SORT procedure by using PROC SORT?
- Question (xyin6-stat6250): How can I sort on multiple variables in one statement?
- *Question* (tbishawstat6250): What is the functionality of the SORT procedure when creating a report?
- *Answer* (tbishawstat6250): The SORT procedure rearranges the observations in a SAS data set, creates a new SAS data set that contains the rearranged observations, replace the original SAS data set by default, and can sort multiple variables (ascending or descending order).
- Question (ttruong59-stat6250): How do users sort data and create a temporary data set to store sorted data?
- *Question* (aguenane−stat6250): What is the general form of a simple PROC SORT step?
- Question (who7−stat6250): What is the difference between sorting data set to name and a.name?



[Course Textbook Chapter 4, Problem 7]
- Question (ljiang11−stat6250): Is it a syntax error that by statement is missing in PROC SORT step?
- *Question* (jcanfield3-stat6250): In the book solution is the second run statement missing a semicolon?
- *Answer* (jcanfield3-stat6250): Yes it is, the book has a typo, since the semicolon is there in the chapter quiz originally.
- Question (lceballos-stat6250): What is the syntax when using the by procedure?
- Question (ldeng11−stat6250): What would happen if you sort the data but don't creat another data set to store the ordered data?
- Answer (ldeng11−stat6250): The original data set would be overwritten by the sorted data set, which is not the good practice because we like to keep the original data set for reference.
- *Question* (akrishnamurthy-stat6250): Is sort statement mandatory before printing a dataset in SAS ?
- *Question* (cnguyen77-stat6250): Is the BY statement required in PROC SORT step?
- *Question* (shatcher4-stat6250): Why do you need to use PROC SORT before PRINT?
- *Question* (jbettonville-stat6250): Assuming that the BY statement is included in PROC SORT, if an OUT option is not specified, does PROC SORT sort the data in place? (i.e. is the data altered if an OUT option is not specified?)
- *Question* (aamiri2-stat6250): If the wrong value is accidentally typed on column totals, how can this be corrected?
- Question (nshrivastava2-stat6250): If there are special character for instance German three letter-diacritic combinations (Ä/ä, Ö/ö, Ü/ü). Will the SORT function will take care of those and if yes,how?
- *Question* (cli19−stat6250): Why does SAS continue to run a program even after if has encountered an error?
- Question(dfei-stat6250): Do I have to put "run" at the end of each "PROC PRINT"?
- Question(pcheng14-stat6250): How could we know whether the PROC SORT step permanently sorts the input data set or not?
- *Question* (aacharya4−stat6250): What happens if we use the PROC SORT step without using the BY statement?
- *Answer* (aacharya4−stat6250): Without the BY statement, the PROC SORT step generates error.
- Question(tchan49-stat6250): Is BY statement required when you try to sort a dataset? 
- Question (lsun20-stat6250): Why the PROC PRINT step will still runs successfully?
- *Question* (ldai4-stat6250): How can we produce column totals for numeric variables?
- Question (xyin6-stat6250): If missing a BY statement in PROC SORT, will the data set still printed if followed by PROC PRINT?
- *Question* (tbishawstat6250): Which SAS statement do you use to produce column totals for numeric variables? And which SAS statement do you use for generating subtotals? 
- Question (ttruong59-stat6250): Why do users need to run PROC SORT and PROC PRINT statement?
- *Question* (aguenane−stat6250): Does the PROC SORT step permanently sort the input data set?
- Question (who7−stat6250): Can SAS combine 2 data sets and sort it and print certain variables from the 2 data set like in SQL?



[Course Textbook Chapter 4, Problem 9]
- Question (ljiang11−stat6250): In what situation, a parenthesis is necessary?
- *Question* (jcanfield3-stat6250): What's the point of having multiple ways of saying the same operator in SAS (like le vs <=)?
- Question (lceballos-stat6250): What is the difference between the eq function and "="?
- Question (ldeng11−stat6250): What is the running sequence when you have different logical operand in the same statement?
- *Question* (akrishnamurthy-stat6250): How are compound expressions evaluated in SAS ?
- *Question* (cnguyen77-stat6250): How to ensure that the compound expression is evaluated correctly?
- *Question* (shatcher4-stat6250): What are the comparison operators that can be used in a WHERE statement?
- *Question* (jbettonville-stat6250): What is the functional difference between "eq" and =, or "le" and <=? Can they be used interchangeably?
- *Answer* (jbettonville-stat6250): According to the textbook page 124-125, comparison operators such as these can be used interchangeably in WHERE statements.
- *Question* (aamiri2-stat6250): What are two main rules you must follow to specifying a condition when selecting the value of a character variable?
- *Answer* (aamiri2-stat6250): You must enclose the value in quotation marks and write the value with lowercase, uppercase, or mixed case letters exactly as it appears in the dataset.
- Question (nshrivastava2-stat6250): By default, a PROC PRINT step lists all the observations in a data set. How can programmer can control observations to get printed ? 
- Answer(nshrivastava2-stat6250): Programmer can control observations to be printed by adding a WHERE statement to your PROC PRINT step.There can be only one WHERE statement in a step.
- *Question* (cli19−stat6250): What is the most efficient way to add a lengthy list of character values into a conditional statement?
- Question(dfei-stat6250): Can I program "less" code instead of code "<" sign code in SAS?
- Question(pcheng14-stat6250): How should we selects colume in which the amount is greater than or equal to $10000 and the account is 1-9527 or the rate equals 0.98?
- *Question* (aacharya4−stat6250): What is the logical operator used to depict not equal to in SAS?
- *Answer* (aacharya4−stat6250): In SAS, "^=" logical operator is used to depict not equal. 
- Question(tchan49-stat6250): What is the difference between AND and OR operator? How are they used differently when testing variables from the same attribute or different attributes? 
- Question (lsun20-stat6250): Can we seprate the one statement to two statements which have the same effect?
- *Question* (ldai4-stat6250): Can SUM statement appear after the BY statement?
- Question (xyin6-stat6250): Does parentheses help deciding the order of compound expressions being evaluated?
- *Question* (tbishawstat6250): What are the steps to generating a SAS LISTING output?
- *Answer* (tbishawstat6250): To generate SAS LISTING output, you must first select Tools and then you go to Options and under Options you select Preferences. In the Preference menu you will find the Results tab and the Creating Listing option. 
- Question (ttruong59-stat6250): What are the comparison operators used in WHERE statement?
- *Question* (aguenane−stat6250): Can you use quotation marks when specifying certain character strings, or must you use apostrophes?
- Question (who7−stat6250): Can we create new abbreviation in SAS?



[Course Textbook Chapter 4, Problem 10]
- Question (ljiang11−stat6250): How can we remove first column?
- Answer (ljiang11−stat6250): By adding option noobs;
- *Question* (jcanfield3-stat6250): What happens when you try to proc print and empty data set?
- Question (lceballos-stat6250): What does "noob" mean in a PROC step?
- Question (ldeng11−stat6250): What does PROC PRINT display if you don't specific any options?
- *Question* (akrishnamurthy-stat6250): What is the syntax of PRINT procedure and how can the output be customized to filter columns or rows?
- *Question* (cnguyen77-stat6250): What is the default function of PROC PRINT?
- *Question* (shatcher4-stat6250): What is the default of PROC PRINT?
- *Answer* (shatcher4-stat6250): It lists the observations in the order they appear in the data set
- *Question* (jbettonville-stat6250): In data sets with a large number of columns, are there any shortcuts for displaying several columns without specifying the name of each variable? Is it possible to select ranges of columns to display?
- *Question* (aamiri2-stat6250): Why is it important to use PROC SORT first then PROC PRINT when creating reports?
- Question (nshrivastava2-stat6250): What technique is particularly useful when observations are too long to print on one line. 
- Answer(nshrivastava2-stat6250): One can say so by using the ID statement where ID variable(s), where variable(s) specifies one or more variables to print instead of the observation number at the beginning of each row of the report.
- *Question* (cli19−stat6250): Is there a limit to report size in SAS?
- Question(dfei-stat6250): The result of "PROC PRINT" store in RAM in computer, isn't it?
- Question(pcheng14-stat6250): Besides PROC PRINT displays all observations and variables in the data set, what kind fo the way I can get the same outcome?
- *Question* (aacharya4−stat6250): What option is used to remove the default column of observation numbers on far left in PROC PRINT output?
- *Answer* (aacharya4−stat6250): NOOBS option is used to remove the default column of observation numbers on far left in PROC PRINT output.
- Question(tchan49-stat6250): To avoid printing out columns that you do not want, what statement do you need to use?
- Question (lsun20-stat6250): What the common usage of the PROC PRINT statement?
- *Question* (ldai4-stat6250): What would happen if you submit a DATA step without a RUN statement?
- *Answer* (ldai4-stat6250): The active window displays the message “DATA step running” for a long time.
- Question (xyin6-stat6250): Is it mandatory to specify equal sign in the DATA= after PROC PRINT?
- *Question* (tbishawstat6250): Which SAS statement do you use to label columns? And is it possible to use single or multiple label statements?
- Question (ttruong59-stat6250): What does PROC PRINT display by default?
- *Question* (aguenane−stat6250): What does the Obs column represent and how do you remove the Obs column in your program?
- Question (who7−stat6250): Can we write a statement that only print the first row of data?
- Answer (who7−stat6250): Yes, you can limit the number of data shown by using (obs=1).



[recipe_to_check_for_duplicates Week 3 Recipe]
- Question (ljiang11−stat6250): what is the mechanism of keyword "nodupkey"?
- *Question* (jcanfield3-stat6250): When can isolating duplicate rows be useful?
- Question (lceballos-stat6250): When using multiple files, what precautions can we take to not have duplicate records
- Question (ldeng11−stat6250): The assumption for this recipe is the data set has one-to-one relationship between the unique id and the obervations (means one unique id can only have one observation). What if the unique id can have multiple observations, how do you check for duplicates? 
- *Question* (akrishnamurthy-stat6250): How to retrieve the duplicate observations from a dataset?
- *Answer* (akrishnamurthy-stat6250): The statement 'nodupkey' in sort procedure is used to eliminate the duplicate observations from a dataset based on th key columns specified. The eliminated records could be directed either to a Null output or another permanent dataset using the 'dupout' statement
- *Question* (cnguyen77-stat6250): What is the approach to remove duplicate records in a SAS dataset?
- *Question* (shatcher4-stat6250): How does nodupkey work?
- *Question* (jbettonville-stat6250): In the context of this recipe, what is the difference between OUT and DUPOUT?
- *Answer* (jbettonville-stat6250): OUT specifies the data set to which the sorted version of the original data set with the duplicates removed; DUPOUT specifies the data set that stores all the duplicate records that were removed.
- *Question* (aamiri2-stat6250): How can we minimize our chances of having duplicate files in a dataset so we can avoid running additional steps to remove it?
- Question (nshrivastava2-stat6250): What is the reason of duplicates? Is because of the variable supposed to be unique? How will the duplicate records remove?
- *Question* (cli19−stat6250): If you are expecting multiple rows per unique identifier, how can you remove duplicate rows from a data set? 
- Question(dfei-stat6250): How many ways can I use to duplicate codes in SAS?
- Question(pcheng14-stat6250): Is this method the best way for isolating duplicate rows than the dupout statement?
- *Question* (aacharya4−stat6250): What happens if the OUT option is not set to a NULL dataset while removing duplicate records from a SAS dataset?
- *Answer* (aacharya4−stat6250): If the OUT option is not set to a NULL dataset while removing duplicate records from a SAS dataset, it creates a deduplicated datset.
- Question(tchan49-stat6250): Why is it important to check duplicate records for unique IDs especially the dataset is obtained from external source?
- Question (lsun20-stat6250): What will be the influence if we use a dataset with some duplicated records?
- *Question* (ldai4-stat6250): How can we remove the duplicate variables from SAS data set?
- Question (xyin6-stat6250): If three variables (County_code, District_code and School_code) are followed by the By statement, will that three being sorted all together? (I thought only one variable can be sorted each time)
- *Question* (tbishawstat6250): What is the approach to checking for duplicate records in a data sets?
- *Answer* (tbishawstat6250): You have to attempt to sort the data set which simultaneously removing duplicate values but outputting the results of the de-duplication process to a null data set. By doing so you are able to find the number of duplicate records in the data log. It is extremely important to always check if our data contains duplicates. 
- Question (ttruong59-stat6250): What is a significant reason to remove duplicates rows in a data set?
- *Question* (aguenane−stat6250): What is the purpose of removing duplicate rows in a SAS data set?
- Question (who7−stat6250): Would there be a situation where looking for duplicate data is not recommended?
- Answer (who7−stat6250): There might be a scenario when duplicate data is common and by removing duplicate data you will be removing valuable data.



[recipe_for_sorting_data Week 3 Recipe]
- Question (ljiang11−stat6250): Why the out= is necessary?
- Answer (ljiang11−stat6250): Because otherwise the original data will be overwritten.
- *Question* (jcanfield3-stat6250): Are "stable" datasets unpreffered?
- Question (lceballos-stat6250): Why would we ever sort the data if there could be information lost by sorting it?
- Question (ldeng11−stat6250): How the SAS would sort the data set if you specify multiple variables in the by statement?
- *Question* (akrishnamurthy-stat6250): How are duplicate values for key column handled while sorting the dataset ?
- *Question* (cnguyen77-stat6250): Do you need to specify the out=option when sorting data in SAS?
- *Question* (shatcher4-stat6250): Why is the out= option optional in the case of sorting data?
- *Question* (jbettonville-stat6250): How sensitive is SAS to memory usage, and under what circumstances might we be concerned about creating a sorted duplicate of a large data set?
- *Question* (aamiri2-stat6250): What would be our results if we sort before removing duplicate files?
- Question (nshrivastava2-stat6250): Can we define SORT procedure and WHERE statement in one single PROC statement? If yes,Why/ if no, Whynot?
- Answer(nshrivastava2-stat6250): Yes, we can do that. This may improve the efficiency of SAS programs because SAS is not required to read all observations from the input data set. There are many different options that are available to the SORT procedure to use them to enhance the programs and improve efficiency. 
- *Question* (cli19−stat6250): To sort a data set in descending order by all variables listed, can we simply put paratheses around the specified variables?
- Question(dfei-stat6250): What will happen when there are same data in dataset when decending or ascending sort of data in SAS?
- Question(pcheng14-stat6250): esides the method, have any other better recipe for sorting data?
- *Question* (aacharya4−stat6250): Do we need to specify "ascending" option in order to sort the data in ascending order in a PROC SORT step in SAS?
- *Answer* (aacharya4−stat6250): No. The PROC SORT step in SAS sorts the data in ascending order by default based on the given criteria.
- Question(tchan49-stat6250): How can you sort the data in ascending order by multiple columns? 
- Question (lsun20-stat6250): Can we make the dataset to sort by the first colum in ascending order and the remaining other columns in descending order?
- *Question* (ldai4-stat6250): Does the new data set created by using PROC SORT replace original data? Does the original data disappear from SAS library?
- Question (xyin6-stat6250): Does the character after out= option have specific requirements? Can it be anyname?
- *Question* (tbishawstat6250): What is the procedure to sorting a report based on values of a variable and which SAS statement do we use to perform this action?
- *Answer* (tbishawstat6250): To sort a report based on values of a variable, we would use the PROC SORT statement to sort the data before using the PRINT procedure to create reports from the data. 
- Question (ttruong59-stat6250): Is it required to specify the out=option when sorting data in SAS?
- *Question* (aguenane−stat6250): When sorting data, why should you add the “out=” command?
- Question (who7−stat6250): How can we best sort data when we want to keep the order of data?
- Answer (who7−stat6250): We can create a temp data set to store the sort data so you can keep the correct order of the data in the original data set.



[recipe_for_printing_values Week 3 Recipe]
- Question (ljiang11−stat6250): How to show the last 20 observations?
- *Question* (jcanfield3-stat6250): Is the obs= only capable of showing the first 'x' rows?  What if I didn't want the first row?
- Question (lceballos-stat6250): Is it possible to export the manipulated data to an excel file?
- Question (ldeng11−stat6250): How can you print the only last several rows in the data set. For example, print the last 20 rows?
- *Question* (akrishnamurthy-stat6250): What is the need for an 'id' statement in PRINT procedure ?
- *Question* (cnguyen77-stat6250): What will happen if the id statement are left out when printing data in SAS?
- *Question* (shatcher4-stat6250): What is the purpose of limiting the number of observations (rows) printed?
- *Question* (jbettonville-stat6250): What advanced techniques can be applied to further format the HTML output? Can we apply different colors, typefaces, sizes, borders, etc.?
- *Question* (aamiri2-stat6250): Can you make any changes to files while using EXPLORE?
- Question (nshrivastava2-stat6250): How many TITLE and FOOTNOTE Statements specify in a program?
- Answer(nshrivastava2-stat6250):  To make the report more meaningful and self-explanatory, one can specify up to 10 titles with procedure output by using TITLE statements before the PROC step. Likewise, specify up to 10 footnotes by using FOOTNOTE statements before the PROC step. Be sure to match quotation marks that enclose the title or footnote text. 
- *Question* (cli19−stat6250): Rather than viewing data sets in SAS, is it possible to export them to Excel or other tools?
- Question(dfei-stat6250): What is the most convenient way to print values in SAS? 
- Question(pcheng14-stat6250): When should we use this technique or recipe for printing the value?
- *Question* (aacharya4−stat6250): What is the use of "var" statement in a PROC PRINT step in SAS?
- *Answer* (aacharya4−stat6250): In SAS, "var" statement in a PROC PRINT step is used to specify the variables in the dataset which would be included in the output. Without the "var" statement all variables of the dataset would be part of the output.
- Question(tchan49-stat6250): How can you print last 30 Obs of the dataset? 
- Question (lsun20-stat6250): What will happen in the example if the PORC PRINT statement without the "(obs=20)"?
- *Question* (ldai4-stat6250): How the report can be shown the title and footnote?
- *Answer* (ldai4-stat6250): Use TITLE and FOOTNOTE statement.
- Question (xyin6-stat6250):Is the ID statement just for idetifying row labels for the variable?
- *Question* (tbishawstat6250): What does the PROC PRINT statement display by default? And what are the observations displayed?
- *Answer* (tbishawstat6250): The PROC PRINT displays all observations and variable in a data set, a column for observation numbers on the far left, and variables in the order in which they occur in the data set. 
- Question (ttruong59-stat6250): Why do users have to limit rows when printing out?
- *Question* (aguenane−stat6250): How do you specify which rows will be used when using a PROC PRINT command?
- Question (who7−stat6250): By the video, it seems it is easy for SAS to change to Excel mode. What are the advantage of using SAS over Excel?



