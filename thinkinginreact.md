1) What is the single responsibility principle and how does it apply to components?

is that every module, class or function in a computer program should have responsibility over a single part of that program’s functionality, and it should encapsulate that part.

2)What does it mean to build a ‘static’ version of your application?

Static applications and websites render in the user’s browser without the need for server side processing, this means that all the rendering of HTML, CSS, and JavaScript is done on the client side, rather then relying on server side

3)Once you have a static application, what do you need to add?

Identify The Minimal (but complete) Representation Of UI State

4)What are the three questions you can ask to determine if something is state?


Is it passed in from a parent via props? If so, it probably isn’t state.
Does it remain unchanged over time? If so, it probably isn’t state.
Can you compute it based on any other state or props in your component? If so, it isn’t state.

5)How can you identify where state needs to live?

We have to dentify all the  components that renders something based on that state.
Find a common owner component (a single component above all the components that need the state in the hierarchy).
Either the common owner or another component higher up in the hierarchy should own the state.
If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

Higher-Order Functions


1)What is a “higher-order function”?

Functions that operate on other functions, either by taking them as arguments or by returning them, are called higher-order functions.

2)Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

it is creating a new function which is comparing the variable m to the variable n .

3)Explain how either map or reduce operates, with regards to higher-order functions.

The map method transforms an array by applying a function to all of its elements and building a new array from the returned values. The new array will have the same length as the input array, but its content will have been mapped to a new form by the function.

The higher-order operation that represents this pattern is called reduce (sometimes also called fold). It builds a value by repeatedly taking a single element from the array and combining it with the current value. When summing numbers, you’d start with the number zero and, for each element, add that to the sum.