Question 1: Line 12 will print 3 because the for loops will iterate 3 times and the variable i is a var so it is not limited to scope. 
Question 2: Line 13 will return 150 because it will retain the value given at the last iteration of the for loop. Thus, 300*.5 = 150.
Question 3: Line 14 will return 150 because it will retain the value given at the last iteration of the for loop. Thus, the rounded value of 150 * 100 / 100 = 150.
Question 4: The function will return an array of [ 50, 100, 150 ] because the for loop pushes the finalPrices calculated in each iteration of the for loop.
Question 5: Line 12 will print "ReferenceError: i is not defined" because i is not being called in the scope that it is accessible in.
Question 6: Line 13 will print "ReferenceError: discountedPrice is not defined" because discountedPrice is not being called in the scope that it is accessible in.
Question 7: Line 14 will return 150 because it will retain the value given at the last iteration of the for loop. Thus, the rounded value of 150 * 100 / 100 = 150. The let variable is accessible in this scope because it was declared before the for loop.
Question 8: The function will return an array of [ 50, 100, 150 ] because the for loop pushes the finalPrices calculated in each iteration of the for loop. The let variable is accessible in this scope because it was declared before the for loop.
Question 9: Line 11 will print "ReferenceError: i is not defined" because i is not being called in the scope that it is accessible in.
Question 10: Line 12 will print 3 because the variable length was set as 3 at the beginning of the function and is accessible at the bottom of the function to be printed.
Question 11: The function will return an array of [ 50, 100, 150 ] because the for loop pushes the finalPrices calculated in each iteration of the for loop. Pushing to the array does not re-assign or re-declare the constant, but just adds to the list that the constant array points to. 