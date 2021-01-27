# Part 1
1. What will happen at line 11 and why?  
*console.log(i)* will output an integer corresponding to the length of prices. This is because in the for loop we increment i until it equals the length of the array prices.
2. What will happen at line 12 and why?  
*console.log(discountedPrice)* it will output NaN because discountedPrice is modified by prices and discount which are NaN values. This makes discountedPrice to be NaN.
3. What will happen at line 13 and why?  
*console.log(finalPrice)* will output NaN because finalPrice will be modified by discountedPrice inside of the for loop.  
4. What will the function return if we call discountPrices([100,200,300],0.5)? Give a brief explanation.  
The output of the function when passing in [100,200,300] and 0.5 will be [50, 100, 150]. This is because in the for loop we are using the variable discount as our parameter to calculate the new prices of the array called prices. We then push these values into discounted and return it. Note that var is function scoped.
5. What will happen at line 11 and why?  
It will give us an error because the variable i is declared using let, which has a block visibility. Since i was declared in the for loop that variable can only be accessed within it.
6. What will happen at line 12 and why?  
 It will give us an error because the variable discountedPrice is declared using let, which has a block visibility. Since discountedPrice was declared in the for loop that variable can only be accessed within it.
7.  What will happen at line 13 and why?
It will output 150 because the variable is declared using the keyword 'let', which has a block visibility. Since it was declared at the beginning of the function, then it will be accessible in every line with the same indentation (inside of the function).
8. What will the function return if we call discountPrices([100,200,300],0.5)? Give a brief explanation.  
The output of the function when passing in [100,200,300] and 0.5 will be [50, 100, 150]. This is because in the for loop we are using the variable discount as our parameter to calculate the new prices of the array called prices. We then push these values into discounted and return it. Note that discounted is declared using let which is block scoped variable.
9. What will happen at line 11 and why?  
It will give us an error because the variable i is declared using let, which has a block visibility. Since i was declared in the for loop that variable can only be accessed within it.
10. What will happen at line 12 and why?  
There will be an error thrown inside of the for loop, because the variable is declared with the keyword const which is unmutable, meaning that it cannot be changed once it's defined.
11. What will happen at line 13 and why?
There will be an error thrown inside of the for loop, because the variable is declared with the keyword const which is unmutable, meaning that it cannot be changed once it's defined.
12. What will the function return if we call discountPrices([100,200,300],0.5)? Give a brief explanation.  
The program will not run because of the error thrown inside of the for loop, which will cause the program to stop.
13. Given the above Object, write the notation for:
    1.  student.name
    2.  student['Grad Year']
    3.  student.greeting()
    4.  student['Favorite Teacher'].name
    5.  student.courseLoad[0]
14. Arithmetic
    1.  32 --> String concatenation, because of the '+' operator (everything after the + will be a string)
    2.  1 --> Arithmetic because of the '-' operator.
    3.  3 --> Adding nothing to an integer with the '+' operator.
    4.  3null --> String concatenation, because of the '+' operator (everything after the + will be a string).
    5.  4 --> Simple arithmetic where the true equals 1.
    6.  0 --> Simple arithmetic where the true equals 0.
    7.  3undefined --> String concatenation, because of the '+' operator (everything after the + will be a string).
    8.  NaN --> We are combining two different types, string and then an undefined.
15. Comparison
    1.  true --> The first parameter is treated as an integer and then we compare it to the second parameter.
    2.  false --> The first and second parameters are treated as integers and then we compare them.
    3.  true --> The second parameter is treated as an integer and then we compare it to the first parameter.
    4.  false --> Keeps the type of the variable when making the comparison, since they are different types the comparison returns false.
    5.  false --> 1 is not equal to 2
    6.  true --> Boolean(2) will return true which is the same as true.
16. The difference is that == will make the appropiate conversions to try to compare the variables. While === will compare the variables as they are without any prior modifications regarding each of their types.
17. 'How are you?' is going to get printed. Because else if (2) will always evaluate to true since 2 is a positive integer.
18. part1-question18.js
19. This call will return [6, 8, 10]. This is because for each element in the input array [1,2,3] we add 2 by calling the function doSomething (through modifyArray) and then we multiply it by two in the function modifyArray.
20. part1-question20.js
21. This snippet of code will output: first the value of the variable i , then it will output 4, then it will output 3 and then 2.