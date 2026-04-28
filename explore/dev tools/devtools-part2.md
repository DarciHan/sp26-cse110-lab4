Question 1 

The bug was that num1 and num2 were being read as strings from the input fields, so using + caused string concatenation instead of numerical addition. For example, "2" + "3" resulted in "23" instead of 5.

Question 2 

function calculateSum(num1, num2) {

    let result = Number(num1) + Number(num2);
    
    return result;
    
}

