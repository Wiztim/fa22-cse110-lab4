1. 3 is output. This is because i is declared as a var, so its scope is beyond the function its declared in. It counts the length of prices.
2. 150 is the output. Similar to i in part one, it is declared var. The final operation done to it before logging it was checking the price of the final item.
3. 150 is also the output. This is similar to discountedPrice, except it is multiplied by 100, rounded, then divided by 100, which has no effect on 150.
4. The function returns [50, 100, 150], a size 3 array of the prices each multiplied by the discount
5. The error "i is not defined" is thrown since i's scope is the for loop.
6. Same error as with i.
7. The output is 150. Since the declaration is in the function with the log, it is in scope. Changes made to it in other functions will persist.
8. The function returns [50, 100, 150]. No errors are caused from changing var to let.
9. Same error as in question 5, i is out of scope.
10. 3 is output. The const variable is in scope of the log, resulting in the length of price.
11. The function returns [50, 100 150]. None of the variables throw errors when used.
12. A. student.name
    B. student['Grad Year']
    C. student.greeting();
    D. student['Favorite Teacher'].name
    E. student.courseload[0]
13. A. The output is '32'. Since '3' is a string, it concatonates 2.
    B. The output is 1. Since you can't subtract strings, it converts '3' into an int and subtracts 2.
    C. The output is 3. Null is treated as 0 when doing arithmetic.
    D. The output is 3null. Null is treated as a string 'null' when concatenating.
    E. The output is 4. True is treated as a 1 int.
    F. The output is 0. False is treated as 0 when an int, so as null.
    G. The output is 3undefined. The undefined variable is treated as a string 'undefined'.
    H. The output is NaN. This is because strings can't be subtracted and undefined can't be an int, so Javascript uses NaN.
14. A. True. When using an int and a string, the string becomes an int and 2 > 1. 
    B. False. No type conversion occurs, so 2 appears later than 1, making it false.
    C. True. '2' is converted to an int, which is equal to 2
    D. False. '2' is not converted to an int, and an int is not equal to a string.
    E. False. True is 1 under int conversion, and 2 is not equal to 1.
    F. True. The function Boolean turns all ints (except 0, -0, and NaN) into true, making the equality true.
15. == attempts to convert the both parameters types to match eachother. === does not do this.
17. Callback lets function be treated as variables, thus making the output [2, 4, 6] since doSomething(num) is called on every element of the array.
19. 1 4 3 2
