# Answers
<hr>

1. Since ```var``` is function scope, line 12 will print an integer value representing the length of ```prices``` - 1, which in this case would be 2. This is because the variable `i` is being incremented by the counted for loop until it is one shy of the length of ```prices```.

2. Line 13 will print 150. This is because ```discountedPrice``` will be equal to the last element in ```prices``` multiplied by 1 - 0.5, which is 300*0.5 which is 150.

3. Line 14 will also print 150. This is because the last ```discountedPrice``` is 150, which multiplied by 100 then divided by 100 is also 150.

4. This function will return an array of size 3, with the three elements being 50, 100, 150. This is because the function is essentially creating a new array of the same size as the passed in array, but multiplying all of the elements by (1 - ```discount```), which in this case meant halving the elements.

5. This will cause an error since `i` is block scope (having been declared with `let`), meaning that outside of that for loop it is not recognizable.

6. For the same reason as #5, this will cause an error. `discountedPrice` is block scope, and will not be recognized outside of that for loop, so trying to print it will cause an error.

7. Since `finalPrice` was declared outside of the for loop, and in the same scope as the `console.log` statement, this will print 150 (for the same mathematical reason that #3 printed 150).

8. This function, like #4, will return an array of size 3, with the three elements being 50, 100, 150. This is because the function is essentially creating a new array of the same size as the passed in array, but multiplying all of the elements by (1 - ```discount```), which in this case meant halving the elements.

9. This will cause an error since `i` is block scope (having been declared with `let`), meaning that outside of that for loop it is not recognizable.

10. This will print 3, since the length of the `prices` array that is passed in is 3.

11. Like #4 and #8, this function - because a const array does not mean it is immutable - will return an array of size 3, with the three elements being 50, 100, 150. This is because the function is essentially creating a new array of the same size as the passed in array, but multiplying all of the elements by (1 - ```discount```), which in this case meant halving the elements.

12. A. `student.name`
    B. `student['Grad Year']`
    C. `student.greeting()`
    D. `student['Favorite Teacher'].name`
    E. `student.courseLoad[0]`

13. A. ‘3’ + 2 = `'32'`
    B. ‘3’ - 2 = `1`
    C. 3 + null = `3`
    D. ‘3’ + null = `'3null'`
    E. true + 3 = `4`
    F. false + null = `0`
    G. '3' + undefined = `'3undefined'`
    H. '3' - undefined = `NaN`

14. A. ‘2’ > 1 = `true`
    B. ‘2’ < ‘12’ = `false`
    C. 2 == ‘2’ = `true`
    D. 2 === ‘2’ = `false`
    E. true == 2 = `false`
    F. true === Boolean(2) = `true`

15. The `==` operator checks for equality after type conversion, whereas `===` checks for equality before type conversion.

16. See `part2-question16.js`.

17. This will return the array `[2, 4, 6]`. This is because the function is iterating through the elements of the passed in array, and changing them using the passed in function, which doubles the number. This means the array `[1, 2, 3]` will return `[2, 4, 6]`.

18. See `part2-question18.js`.

19. This will print:
```
1
4
3
2
```