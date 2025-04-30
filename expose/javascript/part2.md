### 12.Accessing the value of the name property in the student object
Accessing the value of the Grad Year property in the student object: 
student['Grad Year']
Calling the function for the greeting property in the student object: 
student.greeting()
Accessing the name property of the object in the Favorite Teacher property in student: 
student['Favorite Teacher'].name
Access index zero in the array of the courseLoad property of the student object: 
student.courseLoad[0]
## Questions 13-15
### 13. Arithmetic
A: '3' + 2 : 
32
B:'3' - 2
1
C .3 + null
3
D.'3' + null
3null
E: true + 3
4
F: false + null
0
G: '3' + undefined
3undefined
H: '3' - undefined
NaN
### 14. Comparison
A: '2' > 1
true
B: '2' < '12'
false
C: 2 == '2'
true
D: 2 === '2'
false
E: true == 2
false
F: true === Boolean(2)
true
### 15. Explain the difference between the == and === operators.
Difference is that == first tries to convert the two to the same type and than compares whereas === skips conversions, meaning the operands must be the same types and same value to be equal
### 17.If the function above is called with the following parameters modifyArray([1,2,3], doSomething), what will be the result? Briefly walk through how you arrived at that result. (This should be in your part2.md). Here we are passing in a function as a parameter, however we can also return a function from another function just as easily, you're encouraged to play around with callbacks as they are used heavily in frontend JS development. 
The result is [2,4,6]. I got this because each element from the original array is passed through doSomething which doubles the values. The new values are collected in a different array.
### 19. What is the output of the above code? 
1
4
3
2
