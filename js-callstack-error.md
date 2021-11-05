What is a ‘call’?

function invocation is a call
How many ‘calls’ can happen at once?

 function(s) execution, is done, one at a time, from top to bottom.
What does LIFO mean?

last in first out - its adata structure that temporarily stores and manages function invocation (call).

Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

function firstFunction(){
  console.log("Hello from firstFunction");
}

function secondFunction(){
  firstFunction();
  console.log("The end from secondFunction");
}

secondFunction();

What causes a Stack Overflow?
A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. 

What is a ‘refrence error’?

This is as simple as when you try to use a variable that is not yet declared you get this type os errors.

What is a ‘syntax error’?

 this occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.
What is a ‘range error’?

Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.
What is a ‘tyep error’?

Like the name indicates, this types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.
What is a breakpoint?

If the line you selected was run you will be able to see what has happened before that point and you can try and evaluate the next lines to check if everything is outputting what you are expecting.
The breakpoint can also be achieved by putting a debugger statement in your code in the line you want to break.

What does the word ‘debugger’ do in your code?

debugger adds a break point in your code 