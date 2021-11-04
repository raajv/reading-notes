What is functional programming?

Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data .
What is a pure function and how do we know if something is a pure function?

A function is pure if -
It returns the same result if given the same arguments (it is also referred as deterministic)
It does not cause any observable side effects
It returns the same result if given the same arguments
What are the benefits of a pure function?

So we can unit test pure functions with different contexts:
Given a parameter A → expect the function to return value B
Given a parameter C → expect the function to return value D


What is immutability?

When data is immutable, its state cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.

What is Referential transparency?
if a function consistently yields the same result for the same input, it is referentially transparent.
pure functions + immutable data = referential transparency

What is a module?

A module encapsulates a set of related functions and components semantically related with its own functional responsibility
What does the word ‘require’ do?

In NodeJS, require() is a built-in function to include external modules that exist in separate files. require() statement basically reads a JavaScript file, executes it, and then proceeds to return the export object

ref - 
JavaScript require vs import - Flexiplehttps://flexiple.com › javascript-require-vs-import

How do we bring another module into the file the we are working in?

 the module that we want to bring to another file and then use require ('./') and put it in a variable in the file 
What do we have to do to make a module available?
we use module.exports= (function) in the module we want to make available 
