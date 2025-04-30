### 1. Answer: values added: 20.
### 2. Answer: final result: 20
### 3. Answer: Var can lead to accidental name collision and can be hard to track bugs. Also using var to declare your variables in your programs led to naming conflicts and scoping issues. 
### 4. values added: 20
### 5. Error : ReferenceError: result is not defined. This happens because result was only declared inside the if block. "let"  function is block scoped
### 6. Code returns error because at line 7 when result is reassigned and error appears because result was declared with "const" which is read only. The error type is "Assignment to constant variable"
### 7. Same answer here an error appears because function crashed at line 7.
## Part 2
### 1. What will happen at line 12 and why? If the code causes an error, explain why.: 
   The terminal prints 3. This is because i was declared by var. So after the for loop i is incremented to 3 and at line 12 when console.log(i) 3 is printed.
### 2. What will happen at line 13 and why? If the code causes an error, explain why.
Terminal prints 150 because var was used to declare discountedprice so after the for loop(300*.5) the terminal prints 150
### 3. What will happen at line 14 and why? If the code causes an error, explain why.
 Prints 150 because every pass before gets overwritten and the last pass assigns 150 to finalPrice
### 4. What will this function return? Give a brief explanation why. If the code causes an error, explain why
 An array gets printed: [50, 100, 150] because all of the values inside the original array are halfed by the .5
### 5. What will happen at line 12 and why?  If the code causes an error, explain why. ^^^ (assume this function is being called like the others: discountPrices([100, 200, 300], 0.5)).
    Code causes ReferenceError i is not defined because i was declared at let inside the for loop so it only exists there.
### 6. What will happen at line 13 and why? If the code causes an error, explain why.
        Code causes ReferenceError discountedPrice is not defined because discountedPrice was declared at let inside the for loop so it only exists there.
### 7. What will happen at line 14 and why? If the code causes an error, explain why.
        Code causes ReferenceError finalPrice is not defined because finalPrice was declared at let inside the for loop so it only exists there.
### 8. What will this function return? Give a brief explanation. If the code causes an error, explain why. 
    Function returns [50,100,150] because each original price gets halfed then rounded and pushed onto the discounted Array
### 9. What will happen at line 11 and why? If the code causes an error, explain why.
    Code returns ReferenceError i is not defined because i is declared with the "let" header so the variable's scope ends when the loop block ends.   
### 10. What will happen at line 12 and why? If the code causes an error, explain why.
    At line 12 the terminal prints 3 because lentgth is defined as "const" and it stores the prices.length which is 3. (3 elements in the array)
### 11. What will this function return? Give a brief explanation. If the code causes an error, explain why.
    The function returns [50,100,150] because the variable const "discounted" is done inside the loop exactly


