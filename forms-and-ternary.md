What is a ‘Controlled Component’?

We can make React state be the “single source of truth”. Then the React component that renders a form also controls what happens in that form on subsequent user input. An input form element whose value is controlled by React in this way is called a “controlled component”

- ref -https://reactjs.org/docs/forms.html


Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
we should update state as they enter their responses because then it can be passed to other ui elements as well.

How do we target what the user is entering if we have an event handler on an input field?

you can add a name attribute and then let the handler choose base on event.target.name

Why would we use a ternary operator?

A ternary operator is used instead of a if condition which makes the code neater and easier to understand with the use of a ? the ? testes the condition with a boolean

```
  if(x===y){
 console.log(true);
  } else {
 console.log(false);
  }


  let result = x===y ? console.log(true) : console.log(false)