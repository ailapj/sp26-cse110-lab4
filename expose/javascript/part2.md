1. the code will print 3 since line 12 is reached after the for-loop finishes and the last value of i was 3, which is why the loop ends. Since i was declared as a var, its scope is beyond just the for-loop and lives for the entire function. 
2. the code will print 150 since line 13 is reached after the for-loop finished and the last value of discountedPrie would be the last iteration of the loop, which is at i=2. This results in 300*0.5 which is equal to 150. Since discountedPrice is declared as a var, its scope is the entire function
3. the code will print 150 since line 14 is reached after the for-loop finished and the last value of discountedPrie would be the last iteration of the loop, which is at i=2. This results in round(150*100)/100 which is 150. Since discountedPrice is declared as a var at the beginning of the function, its scope is the entire function
4. [50, 100, 150] is returned since each iteration of the loop calculates the final price of each prices entry and pushes it to discounted. However, since the array is only ever returned and not displayed, nothing will be printed to the console. 
5. ReferenceError: i is not defined. This will cause an error since i was declared as a let inside the for-loop and therefore it has a limited scope only to that block. Since line 12 is outside the loop block, i cannot be accessed. 
6. ReferenceError: discountedPrice is not defined. This will cause an error since discountedPrice was declared as a let inside the for-loop and therefore it has a limited scope only to that block. Since line 13 is outside the loop block, discountedPrice cannot be accessed.
7. 150 will be printed since finalPrice is delcared at the beginning of the function and therefore has a scope of the entire function. Since the last iteration of the loop assigns 150 to it, that is the value that will be printed. 
8. [50, 100, 150] is returned since each iteration of the loop calculates the final price of each prices entry and pushes it to discounted. However, since the array is only ever returned and not displayed, nothing will be printed to the console. 
9. ReferenceError: i is not defined since i is declared as a let in the for-loop and therefore has a scope of just the loop. Since line 11 is outside the loop, i cannot be accessed. 
10. 3 will be printed since length was declared at the beginning of the function and line 12 is still in the function. 
11. [50, 100, 150] will be returned since each iteration of the loop calculates the discounted price of each prices entry and pushes it to discounted. However, since the array is only ever returned and not displayed, nothing will be printed to the console.
12.
    A. student.name  
    B. student['Grad Year']  
    C. student.greeting()  
    D. student['Favorite Teacher'].name  
    E. student.courseLoad[0]  
14. A. '32' -> since + triggers string onccatenation and 2 is mapped to its exact string representation  
    B. 1 -> since - trigers numeric conversion and '3' is mapped to its exact numeric representation  
    C. 3 -> null is converted to 0, 3+0 = 3  
    D. 3null -> string concatenation and null is converted to "null"   
    E. 4 -> true is converted to 1 and 1+3=4   
    F. 0 -> both false and null converted to 0 and 0+0=0  
    G. 3undefined -> string concatenation and undefined is converted to "undefined"  
    H. NaN -> both converted to numbers but undefined is NaN so 3 - NaN = NaN   

15. A. true -> '2' converted to 2 and 2>1 is true   
    B. false -> both are strings and string comparison is lexicogrpahic and '2' > '1'    
    C. true -> '2' is converted to 2 and 2==2 is true  
    D. false -> === checks for both vlue and type and number is not a string   
    E. false -> true is converted to 1 and 1 is not equal to 2   
    F. true -> Boolean(2) is true since any non-zero number is true, and true is equal to true.   

16. == is a loose equality that compares the values after type conversion while === is strict equality and compares both value and data type without any type conversion. 

17. part2-question16.js
18. [2, 4, 6] will be the result because inside modifyArray, for each entry of the array, [1, 2, 3], we pass that number to the callback function, in this case, doSomething, which doubles the number. We then pusht the result of this function to newArr which is then returned. Therefore, each entry of the array is doubled and returned in newArr. 
19. part2-question18.js
20. 1
    4
    3
    2
    
