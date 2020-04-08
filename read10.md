# SUMMARY #

## call stack ##

**A call stack is a mechanism for an interpreter (like the JavaScript interpreter in a web browser) to keep track of its place in a script that calls multiple functions — what function is currently being run and what functions are called from within that function, etc.**
- When a script calls a function, the interpreter adds it to the call stack and then starts carrying out the function.
- Any functions that are called by that function are added to the call stack further up, and run where their calls are reached.
- When the current function is finished, the interpreter takes it off the stack and resumes execution where it left off in the last code listing.
- If the stack takes up more space than it had assigned to it, it results in a "stack overflow" error.
**We started with an empty Call Stack, and whenever we invoke a function, it is automatically added to the Call Stack, after executing all of its codes, it is automatically removed from the Call Stack. At the end, we ended up with an empty stack too.**

![image](https://i.ytimg.com/vi/2ZH_1d8TYVg/maxresdefault.jpg)


## JavaScript error messages && debugging ##

**Types of error messages**
- The first thing that indicates you that something is wrong with your code is the (in)famous error message that the one we saw just moments ago, it usually appears on your console (being developer tools of the browser, terminal or whatever else you are using).
- Reference errors:
This is as simple as when you try to use a variable that is not yet declared you get this type os errors.
- Syntax errors:
I know it’s in the name of the errors, but like it says itself, this occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.
- Range errors:
Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.
- Type errors
Like the name indicates, this types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.
