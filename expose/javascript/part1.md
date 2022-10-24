## Part1 Answers 
This file stores answers to all questions in part1, lab4.  

### Q1 & Q2
Q1: What is printed by line 9? If the code returns an error, explain why. ^^^^^ <br />
Line 9 prints: values added:  20 <br />
<br />
Q2: What is printed by line 13? If the code returns an error, explain why. <br />
Line 13 prints: final result:  20 <br />


### Q3 & Q4
Q3: What is printed by line 9? If the code returns an error, explain why. ^^^^^ <br />
Line 9 prints: values added:  20 <br />
<br />
Q4: What is printed by line 13? If the code returns an error, explain why. <br />
Line 13 returns the following error: Uncaught ReferenceError: result is not defined <br />
    at sumValues (part1-question3-4.js:13:35) <br />
    at part1-question3-4.js:16:1 <br />
Reason: line 13 tries to access variable result outside of its scope. <br /> Result is defined in line 5 in the if block using let keyword. This means it can only be accessed with the if block, which ends at line 11. <br />

### Q5 & Q6
Q5: What is printed by line 9? If the code returns an error, explain why. ^^^^^ <br />
Line 9 returns error: Uncaught TypeError: Assignment to constant variable. <br />
Reason: Line 5 defines variable result using the const keyword, this means the value of result cannot be changed. However Line 7 tries to change its value. 
<br />
Q6: What is printed by line 13? If the code returns an error, explain why. <br />
Line 13 is not executed because of error at Line 7. <br />



