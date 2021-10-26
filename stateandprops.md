Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

First the 'render' takes plae and after the 'compnentDidMount'
What is the very first thing to happen in the lifecycle of React?

Mounting first happens in the life cycle of react
Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

-constructor
-render
-componentDidMount
-React Updates
-componentWillMount


What does componentDidMount do?

This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here. This method is a good place to set up any subscriptions. If you do that, don’t forget to unsubscribe in componentWillUnmount().
-ref https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093


What types of things can you pass in the props?

props are something that is used to display some data inside of a component that would not be changed , ie a title or subtitle or initital count etc ie when the information is static and doesnt change inside of the component.


What is the big difference between props and state?

props is something that you put in the component for eg starting point of a counter , while state is done within in the component eg the current count incase the user changes it. props have to be updated outside while state has to be updated inside of the component.


When do we re-render our application?

when we re render we change the state of the ocmponent and thus it is re rendered 


What are some examples of things that we could store in state?

state stores information that is used to update and re render your application , for eg numbers ,or count or text . this is based on user input , for eg a form or text box.