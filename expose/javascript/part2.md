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
Therefore, trying to log i at line 12 results in an error.

Question 6
Line 13 causes a ERROR. The variable discountedPrice is declared using let inside the for loop, which makes it block-scoped. Thus discountedPrice only exists within the loop and is not accessible outside of it. Therefore, trying to log discountedPrice at line 13 results in an error.

Question 7 
Line 14 prints 150. The variable finalPrice is declared outside the loop using let, so it is accessible after the loop finishes. 
During each iteration, finalPrice is updated, and after the loop ends, it holds the value from the final iteration, so that value is printed.
