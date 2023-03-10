# Reading Notes Class 10

## Code 301 - Intermediate Software Development

## Readings: In memory storage

[Understanding the JavaScript Call Stack](https://medium.freecodecamp.org/understanding-the-javascript-call-stack-861e41ae61d4)

- What is a ‘call’?
  - The call stack is primarily used for function invocation (call).
- How many ‘calls’ can happen at once?
  - One at a time
- What does LIFO mean?
  - LIFO: When we say that the call stack, operates by the data structure principle of Last In, First Out, it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.
- Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
  - 
- What causes a Stack Overflow?

[JavaScript error messages](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)

- What is a ‘reference error’?
  - The ReferenceError object represents an error when a variable that doesn't exist (or hasn't yet been initialized) in the current scope is referenced.
- What is a ‘syntax error’?
  - An exception caused by the incorrect use of a pre-defined syntax. Syntax errors are detected while compiling or parsing source code. For example, if you leave off a closing brace ( } ) when defining a JavaScript function, you trigger a syntax error.
- What is a ‘range error’?
  - A RangeError is thrown when trying to pass a value as an argument to a function that does not allow a range that includes the value. This can be encountered when: passing a value that is not one of the allowed string values to String.
- What is a ‘type error’?
  - The TypeError object represents an error when an operation could not be performed, typically (but not exclusively) when a value is not of the expected type.
- What is a breakpoint?
  - In the debugger window, you can set breakpoints in the JavaScript code. At each breakpoint, JavaScript will stop executing, and let you examine JavaScript values. After examining values, you can resume the execution of code (typically with a play button).
- What does the word ‘debugger’ do in your code?
  - A debugger is a computer program to aide in testing and rooting out bugs/errors in other programs.

## Bookmark and Review

[JavaScript errors reference on MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors)



