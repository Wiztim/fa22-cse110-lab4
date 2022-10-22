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
