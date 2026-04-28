Question 1 

Line 12 prints 3. The loop runs through the three elements in the prices array, so after the final iteration the value of i becomes 3. 
This does not cause an error because i was declared with var, which is function-scoped, and thus is still accessible outside of the for loop.

Quesiton 2

Line 13 prints 150. The variable 'discounted rice' is declared using var, which is function-scoped, so it remains accessible outside the loop. 
After the loop finishes, it retains the value from the final iteration, so that value is printed.

Question 3

Line 14 prints 150. The variable 'final price' is declared using var , which is function-scoped, so it remains accessible outside the loop. 
During each iteration, 'final price' is updated, and after the loop finishes, it holds the value from the final iteration, so that value is printed.

Question 4

The function returns [50, 100, 150]. The loop goes through each element in the prices array and applies the discount by multiplying each value by (1 - 0.5). 
Each result is rounded and added to the discounted array. Since var is function-scoped, the final array of discounted prices is returned.

Question 5

Line 12 causes a ERROR. The variable i is declared using let inside the for loop, which makes it block-scoped. Thus i only exists within the loop and is not accessible outside of it. 
Therefore, trying to call i at line 12 results in an error.

Question 6

Line 13 causes a ERROR. The variable discountedPrice is declared using let inside the for loop, which makes it block-scoped. Thus discountedPrice only exists within the loop and is not accessible outside of it. Therefore, trying to log discountedPrice at line 13 results in an error.

Question 7 

Line 14 prints 150. The variable finalPrice is declared outside the loop using let, so it is accessible after the loop finishes. 
During each iteration, finalPrice is updated, and after the loop ends, it holds the value from the final iteration, so that value is printed.

Question 8

The function returns [50, 100, 150]. The loop goes through each element in the prices array and applies the discount by multiplying each value by (1 - 0.5). 
Each result is rounded and added to the discounted array and the final array of discounted prices is returned. All variables are declared and called correctly.

Question 9 

Line 11 causes a ERROR. The variable i is declared using let inside the for loop, which makes it block-scoped. 
This means i only exists within the loop and is not accessible outside of it. Therefore, trying to call i at line 11 results in an error.

Question 10 

Line 12 prints 3. The variable length is declared using const outside the loop and is assigned the value of prices.length, which is 3. const is block-scoped and declared in the function scope, thus it remains accessible at line 12. Therefore, logging length prints 3 and no error occurs.

Question 11

The function returns [50, 100, 150]. The loop iterates through each element in the prices array and applies the discount by multiplying each value by (1 - 0.5).
Each discounted value is added to the discounted array and the final array is returned. All variables are declared and called correctly.

**DATA TYPES**

Question 12 

A. student.name

B. student['Grad Year']

C. student.greeting()

D. student['Favorite Teacher'].name

E. student.courseLoad[0]

**Basic Operators & Type Conversion**

Question 13
Arithmetic

A. '3' + 2 = '32'  
Explanation: Since one of them is a string, JavaScript just sticks them together.

B. '3' - 2 = 1  
Explanation: The minus sign makes JavaScript turn '3' into a number first.

C. 3 + null = 3  
Explanation: null basically acts like 0 here.

D. '3' + null = '3null'  
Explanation: Because there is a string, JavaScript combines them into one string.

E. true + 3 = 4  
Explanation: true acts like 1, so it becomes 1 + 3.

F. false + null = 0  
Explanation: false is 0 and null is also 0.

G. '3' + undefined = '3undefined'  
Explanation: JavaScript turns undefined into text and adds it to the string.

H. '3' - undefined = NaN  
Explanation: JavaScript tries to do math, but undefined does not work as a number.

Question 14
Comparison

A. '2' > 1 = true  
Explanation: '2' turns into 2, and 2 is bigger than 1.

B. '2' < '12' = false  
Explanation: Since both are strings, JavaScript compares them like text, not numbers.

C. 2 == '2' = true  
Explanation: == allows JavaScript to convert the string so the values match.

D. 2 === '2' = false  
Explanation: === checks the type too, and one is a number while the other is a string.

E. true == 2 = false  
Explanation: true becomes 1, and 1 is not equal to 2.

F. true === Boolean(2) = true  
Explanation: Boolean(2) becomes true, so both sides are exactly true.

Question 15
Difference between == and ===

== checks if two values are the same after JavaScript converts them if needed.

=== checks if two values are the same without converting them, so the value and the type both have to match.

Question 17


Result: [2, 4, 6]

Explanation: The function goes through each number in the array and applies the doSomething function, which multiplies each number by 2. So 1 becomes 2, 2 becomes 4, and 3 becomes 6.

Question 19


Output:
1

4

3

2

Explanation: 1 and 4 run immediately. The setTimeout with 0 delay runs after the main code finishes, so 3 comes next. The setTimeout with 1000 delay runs last, so 2 is printed after 1 second.





