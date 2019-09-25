## Debugging HW

###### 1. What is the purpose of a breakpoint?
The purpose of a breakpoint is to pause the running of the code at a specific point so it can be evaluated for errors.

###### 2. Does the line of code on a breakpoint run when you start debugging?
No. The code runs to the line before and pauses on the line where the breakpoint was placed.

###### 3. How do we debug the next line of code?
Once the line we are working on has been checked/fixed the step over command in the debugger console can be used to move to the next line.

###### 4. What does the step into command do?
Allows you to go directly to the start of a linked method.

###### 5. What is the difference between evaluate expression and evaluate code fragment?
Evaluate expression allows you to test a single line of code without having to include a semi colon. Evaluate Code Fragment, however, has the same rules as normal java but allows you to evaluate multiple lines at the same time. You can also incorporate variables to run the lines with.
