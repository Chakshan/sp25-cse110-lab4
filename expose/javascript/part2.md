# Part 2

1. Line 12 will print `3` to the console. When the loop terminates, `i` has a value of `3`. Because `i` was declared with `var`, it has function scope and can be accessed at line 12 where its values is printed.
2. Line 13 will print `150` to the console since that is the discounted price of the last element of input array.
3. Line 14 will print `150` to the console since that is discounted price of the last element of the input array rounded to 2 decimals.
4. The function will return `[50, 100, 150]` because the the function goes through each value in the input array, applies a discount, and adds that final price to the output `discounted` list which is what it returns.
5. The code causes an error because `i`, defined with `let` in the for loop, is out of scope at line 12.
6. The code causes an error because `discountedPrice`, defined with `let` in the for loop, is out of scope at line 13.
7. Line 14 will print `150` to the console because `finalPrice` is in-scope within the same function it was defined in.
8.  The function will return `[50, 100, 150]` as explained in question 4. There is no error with scoping since each variable is only accessed within their defined blocks.
9.  The code will cause an error because `i`, defined with `let` in the for loop, is out of scope at line 11.
10. Line 12 will print `3`, the length of the input array. Variables with `const` have no restriction on being read and `length` is accessed in its scope.
11. The function will return `[ 50, 100, 150 ]` as described in question 4. As variables are accessed in their scope and no prohibited operations are executed.

12. Object access
     1. A. `student.name`
     2. B. `student["Grad Year"]`
     3. C. `student.greeting()`
     4. D. `student["Favorite Teacher"].name`
     5. E. `student.courseLoad[0]`

13. Arithmetic
    1.  A. `'32'` — `2` is converted to a string and concatenated with `'3'`
    2.  B. `1` — `'3'` is converted to an number and then `3-2` is performed
    3.  C. `3` — `null` is converted to an number becoming `0` before being added
    4.  D. `'3null'` — `null` is converted to an string becoming `'null'` before being concatenated
    5.  E. `4` — `true` is converted to an number becoming `1	 before being added
    6.  F. `0` — both `false` and `null` are converted to numbers, both becoming `0` before being added
    7.  G. `3undefined` — `undefined` is converted to a string becoming `'undefined'` before being concatenated
    8.  H. `NaN` — both `'3'` and `undefined` are converted to numbers, `'3'` becomes `3` and `undefined` becomes `NaN` and there difference is `NaN`

14. Comparison
    1.  A. `true` — string `'2'` becomes a number 2
    2.  B. `false` — both are compared as strings and `'12'` precedes `'2'` alphabetically and is therefore not greater
    3.  C. `true` — `'2'` is converted to a number `2`
    4.  D. `false` — `===` checks for equality without any type conversion
    5.  E. `false` — `true` is converted to a number `1`
    6.  F. `true` — `Boolean(2)` evalutes to `2`

15. `==` performs any necessary type conversion before checking for equality. `===` is the strict equality operator and check for equality without type conversion; if the operands are different types, it immediately returns `false`.

17. The result is `[ 2, 4, 6 ]`. This is because the `modifyArray` function applies the `doSomething` function to each element of the array and pushes the result to the array returned. Since `doSomething` returns the input doubled, the output has the input array numbers doubled.

19. The outputs: `1`, `4`, `3`, `2` on seperate lines. `1` and `4` are printed by the function call then `3` is printed right after and then `2` is printed after 1 second.