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
Q7: What will happen at line 14 and why?  If the code causes an error, explain why.  <br />
It prints: 150. finalPrice is defined inside the function using let, so it can be accessed at line 14. In other words, it is not out of scope. <br />

### Q8
Q8: What will this function return? Give a brief explanation why. If the code causes an error, explain why. <br />
It returns the variable discounted, which is a list of numbers storing discounted prices. Same as Q4.  <br />

### Q9
Q9: What will happen at line 11 and why?  If the code causes an error, explain why.  <br />
It results in error: Uncaught ReferenceError: i is not defined. <br />
Reason: Out of scope.i is defined using let keyword, so it can only be accessed within the for-loop block. Same as Q5.<br />

### Q10
Q10: What will happen at line 12 and why?  If the code causes an error, explain why.  <br />
It prints 3 since the length of prices is 3. <br />

### Q11
Q11: What will this function return? Give a brief explanation why. If the code causes an error, explain why. <br />
It returns the variable discounted, which is a list of numbers storing discounted prices. Same as Q4, Q8. Note that if a constant is an object or array, its items can be updated or removed. This is why the script works. <br />

### Q12
Given the above Object, write the notation for: <br />
A. Accessing the value of the name property in the student object<br />
Ans: student.name<br />
B. Accessing the value of the Grad Year property in the student object<br />
Ans: student['Grad Year']<br />
C. Calling the function for the greeting property in the student object<br />
Ans: student.greeting();<br />
D. Accessing the name property of the object in the Favorite Teacher property in student<br />
Ans: student['Favorite Teacher'].name<br />
E. Access index zero in the array of the courseLoad property of the student object<br />
Ans: student.courseLoad[0]<br />

### Q13
Arithmetic <br />
‘3’ + 2   32, 2 got concatenated to the string '3'<br />
‘3’ - 2 -> 1, '3' got mapped to 3<br />
3 + null -> 3, null got mapped to 0<br />
‘3’ + null -> 3null, null got concatenated to the string '3'<br />
true + 3 -> 4, true got mapped to 1<br />
false + null -> 0, both got mapped to 0<br />
'3' + undefined -> 3undefined, undefined got concatenated to the string '3'<br />
'3' - undefined -> NaN, result is not an number<br />

### Q14
Comparison<br />
‘2’ > 1 -> true, '2' got mapped to 2. <br />
‘2’ < ‘12’ -> false, when comparing two strings, "2" will be greater than "12", because (alphabetically) 1 is less than 2.<br />
2 == ‘2’ -> true, '2' got mapped to 2 <br />
2 === ‘2’ -> false, no type conversion is done in ===<br />
true == 2 -> false, true got mapped to 1<br />
true === Boolean(2) -> true, Boolean(2) got mapped to true<br />

### Q15
Explain the difference between the == and === operators. <br />
Ans: The strict equality operator (===) behaves identically to the abstract equality operator (==) except no type conversion is done, and the types must be the same to be considered equal. <br />

### Q16
See part2-question16.js located in the same folder. <br />

### Q17
If the function above is called with the following parameters modifyArray([1,2,3], doSomething), what will be the result? Briefly walk through how you arrived at that result.<br />
Ans: it will double each value in the input array, (in this case [1, 2, 3]) push them to a new array, and return that new array (in this case it returns [2, 4, 6]). <br />

### Q18
See part2-question18.js located in the same folder. <br />

### Q19
1<br />
4<br />
3<br />
2<br />

