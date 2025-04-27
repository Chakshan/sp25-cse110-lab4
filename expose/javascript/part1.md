# Part 1

1. Line 9 prints: `values added:  20`
2. Line 13 prints: `final result:  20`
3. `var` should not be used because it has function level scope as opposed to block scope. This means that it can be accessed anywhere throughout a function ignoring blocks. This can lead to unintended behavior and bugs.
4. Line 9 prionts: `values added:  20`
5. The code returns an error because `result` is not defined at line 13. It's scope is limited to the if block that it was defined in.
6. The code returns an error. Since `result` was defined to be `const`, its value cannot be changed from its initialization. Hence, line 7 causes an error and line 9 is unable to execute.
7. The code returns an error. As stated in question 6, since `result` was defined to be `const`, line 7 causes an error and the code ends its execution before reaching line 13.
