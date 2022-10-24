## Part2 Answers 
This file stores answers to all questions in part2, lab4.  

### Q1 
Q1: What will happen at line 12 and why? If the code causes an error, explain why. <br />
Line 12 prints: (i = ) 3. Reason: i increments from 0 to 3, which is the length of prices input.  <br />

### Q2
Q2: What will happen at line 13 and why? If the code causes an error, explain why. <br />
Line 12 prints: NaN. Reason: NaN stands for not a number. Type of discountedPrices is object, not number. So printing it results in NaN.  <br />

### Q3
Q3: What will happen at line 14 and why? If the code causes an error, explain why. <br />
Line 12 prints: NaN.  Reason: NaN stands for not a number. Type of finalPrice is object, not number. So printing it results in NaN.  <br />

### Q4
Q4: What will this function return? Give a brief explanation why. If the code causes an error, explain why. <br />
It returns the variable discounted, which is a list of numbers storing discounted prices.  <br />

### Q5
Q5: What will happen at line 12 and why?  If the code causes an error, explain why.  <br />
It results in error: Uncaught ReferenceError: i is not defined. <br />
Reason: Out of scope.i is defined using let keyword, so it can only be accessed within the for-loop block.<br />

### Q6
Q6: What will happen at line 13 and why?  If the code causes an error, explain why.  <br />
It results in error: Uncaught ReferenceError: discountedPrice is not defined. <br />
Reason: Out of scope. discountedPrice is defined using let keyword, so it can only be accessed within the for-loop block.<br />

### Q7
Q6: What will happen at line 14 and why?  If the code causes an error, explain why.  <br />
It prints: 150. finalPrice is defined inside the function using let, so it can be accessed at line 14. In other words, it is not out of scope. <br />

