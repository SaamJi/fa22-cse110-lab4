## Part1 Answers 
This file stores answers to all questions in part1, lab4.  

### Q1 & Q2
Q1: What is printed by line 9? If the code returns an error, explain why. ^^^^^ <br />
Line 9 prints: values added:  20 <br />
<br />
Q2: What is printed by line 13? If the code returns an error, explain why. <br />
Line 13 prints: final result:  20 <br />


### Q3 & Q4
Q1: What is printed by line 9? If the code returns an error, explain why. ^^^^^ <br />
Line 9 prints: values added:  20 <br />
<br />
Q2: What is printed by line 13? If the code returns an error, explain why. <br />
Line 13 returns the following error: Uncaught ReferenceError: result is not defined
    at sumValues (part1-question3-4.js:13:35)
    at part1-question3-4.js:16:1 <br />
This is because line 13 tries to access variable result outside of its scope. Result is defined in line 5 in the if block <br />using let keyword. This means it can only be accessed with the if block, which ends at line 11. <br />


