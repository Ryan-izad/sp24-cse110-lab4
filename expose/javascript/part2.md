# Part 2 Question Answers
1. 3, because i is incremented from 0 by 1 three times because prices.length = 3, and the variable is in scope of the entire function
2. 150, because the last iteration of the for loop multiplies the last item of prices (300) by .5, and the variable is in scope of the entire function
3. 150, because the last iteration of the for loop takes the discounted price (150), and multiplies it by 100 and divides by 100 to get a whole number with no decimal point. 
4. [ 50, 100, 150 ], returns the array of orignal prices multiplied by 0.5
5. ReferenceError: i is not defined, because let causes i to only be in scope for the for loop, not outside of that code block.
6. ReferencError: discountedPrice is not defined, same reason for #5, discountedPrice is only in scope throughout the for loop. 
7. 150, since the variable is technically in scope since it was declared as a let variable outside of the for loop. 
8. [ 50, 100, 150 ], returns the discounted array properly, since discounted was declared as a let variable outside of the for loop, keeping it in scope. 
9. A TypeError: Assignment to constant variable, occurrs since in the for loop we are assigning to constant variables. 
10. Prints out 3, the accurate length of the prices array since it was orignally assigned as a constant and never attepmted to be changed. 
11. [ 50, 100, 150 ], it returns the accurate discounted array. It might seem like const is being reassigned, but since it is being declared in each iteration of the for loop, it technically is never assigned a value twice to violate the rules of a const.
12. (A): student.name
    (B): student['Grad Year']
    (C): student.greeting()
    (D): student['Favorite Teacher'].name
    (E): student.courseLoad[0]
13. (A) '32', concatenating string literals
    (B) 1, literal representaiton of the string 3 - 2
    (C) 3, null = 0 in the integer case
    (D) '3null', concatating string literals 
    (E)  4, true = 1 in the integer case
    (F) 0, false and null both equal 0 in addition
    (G) '3undefined' concatenating string literals
    (H) NaN, cannot subtract string integer with undefined 
14. (A) True, 2 > 1
    (B) False, compares only the first integer of each string
    (C) True, 2 = 2, compares only values
    (D) False, 2 = 2, but "===" compares value and type
    (E) False, true = 1 so 1 != 2
    (F) True, Boolean(2) = true so equal
15. The == operator only compares the values, while the === operator compares both the value and type.
17. [2,4,6], Walking through the modifyArray function, we create a new array, and for each iteration of [1,2,3], we push to the new array the original array values and multiply them by 2, since that is what occurs in doSomething.
19. 1 4 3 2  