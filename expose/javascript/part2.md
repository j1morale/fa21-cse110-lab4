Question 1: Line 12 will print 3 because the for loops will iterate 3 times and the variable i is a var so it is not limited to scope. <br/>
Question 2: Line 13 will return 150 because it will retain the value given at the last iteration of the for loop. Thus, 300*.5 = 150. <br/>
Question 3: Line 14 will return 150 because it will retain the value given at the last iteration of the for loop. Thus, the rounded value of 150 * 100 / 100 = 150. <br/>
Question 4: The function will return an array of [ 50, 100, 150 ] because the for loop pushes the finalPrices calculated in each iteration of the for loop. <br/>
Question 5: Line 12 will print "ReferenceError: i is not defined" because i is not being called in the scope that it is accessible in. <br/>
Question 6: Line 13 will print "ReferenceError: discountedPrice is not defined" because discountedPrice is not being called in the scope that it is accessible in. <br/>
Question 7: Line 14 will return 150 because it will retain the value given at the last iteration of the for loop. Thus, the rounded value of 150 * 100 / 100 = 150. The let variable is accessible in this scope because it was declared before the for loop. <br/>
Question 8: The function will return an array of [ 50, 100, 150 ] because the for loop pushes the finalPrices calculated in each iteration of the for loop. The let variable is accessible in this scope because it was declared before the for loop. <br/>
Question 9: Line 11 will print "ReferenceError: i is not defined" because i is not being called in the scope that it is accessible in. <br/>
Question 10: Line 12 will print 3 because the variable length was set as 3 at the beginning of the function and is accessible at the bottom of the function to be printed. <br/>
Question 11: The function will return an array of [ 50, 100, 150 ] because the for loop pushes the finalPrices calculated in each iteration of the for loop. Pushing to the array does not re-assign or re-declare the constant, but just adds to the list that the constant array points to. <br/>
Question 12: <br/>
    Part A: student.name <br/>
    Part B: student['Grad Year'] <br/>
    Part C: student.greeting() <br/>
    Part D: student['Favorite Teacher'].name <br/>
    Part E: student.courseLoad[0] <br/>
Question 13: <br/>
    Part A:  5 because 3 is converted to a number. <br/>
    Part B:  1 because 3 is converted to a number. <br/>
    Part C:  3 because null is considered a 0. <br/>
    Part D:  3 because 3 is converted to a number and null is 0. <br/>
    Part E:  4 because true is considered a 1. <br/>
    Part F:  0 because both are considered a 0. <br/>
    Part G:  NaN because undefined is not a number. <br/>
    Part H:  NaN because undefined is not a number. <br/>
Question 14: <br/>
    Part A:  True because 2 is converted to a number. <br/>
    Part B:  True because both are converted to numbers. <br/>
    Part C:  True because same values. <br/>
    Part D:  False because different types. <br/>
    Part E:  False because true is considered a 1. <br/>
    Part F:  False because they are different types. <br/>
Question 15: '==' checks for same value. '===' checks for same value and type. <br/>

Question 17: modifyArray will return the array [2,4,6] because the callback function modifies the original array and multiplies them all by 2 and each one is pushed to the newArr which is returned.<br/>
Question 19: 1 4 3 2 <br/>