1. 3 is outputted because there were three prices inputted, so 'i' stopped at 3
2. 150 is outputted because the final value of discountedPrice is 50% of 300
3. 150 is outputted because finalPrice is the same as discountedPrice, rounded to two past the decimal point
4. [ 50, 100, 150 ], which is each price times 50%
5. error - 'i' is not defined outside the scope of the for loop
6. error - 'discountedPrice' is not defined outside the scope of the for loop
7. 150 is outputted because finalPrice is within the scope of the function
8. [ 50, 100, 150 ], discounted is within the scope of the function
9. error - 'i' is not defined outside the scope of the for loop
10. 3 is outputted becuase length doesn't change and is defined within the right scope
11. [ 50, 100, 150 ], even though discounted is a const, in javascript, it is okay to modify its contents  
12a. student.name  
12b. student['Grade Year']  
12c. student.greeting()  
12d. student['Favorite Teacher'].name  
12e. student.courseLoad[0]  
13a. 32 - concatenation   
13b. 1 - the '-' sign signals arthimetic  
13c. 3 - the null is treated as 0  
13d. 3null - concatenation  
13e. 4 - true is converted to 1  
13f. 0 - false and null are converted to 0  
13g. 3undefined - concatenation  
13h. NaN - undefined can't be turned into a number  
14a. true - 2 is converted to a number and is greater than 1  
14b. false - 2 is less than 12 in lexicographic order  
14c. true - '2' is converted to 2  
14d. false - === does not do conversion  
14e. false - true is converted to 1, and 1 != 2  
14f. true - 2 is converted to a boolean, which is automatically true if the number is > 0  
15. == is a regular equality check, ==== is an equality check without type conversion
16. see code
17. [ 2, 4, 6 ] is the output, we arrive at this because the modifyArray takes each element of the array, and doubles it by inputting it into the doSomething function. 
18. see code
19. The output is 1 4 3 2 (on separate lines) - it prints 1 and 4 first because there is no delay, then 3 because the delay is 0, then 2 last because there is a delay of 1
