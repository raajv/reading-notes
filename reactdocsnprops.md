What does .map() return?

.map returns an new array with each element being a result of the call back function.


If I want to loop through an array and display each value in JSX, how do I do that in React?
use .map()


Each list item needs a unique key.


What is the purpose of a key?

the key returns an array whose elements are strings corresponding to the innumerable properties found directly in the object.


What is the spread operator?

The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.


List 4 things that the spread operator can do.

-Adding an item to a list
-Adding to state in React
-Combining objects
-Converting NodeList to an array


Give an example of using the spread operator to combine two arrays.

```
const myArray = [`🤪`,`🐻`,`🎌`]
const yourArray = [`🙂`,`🤗`,`🤩`]
const ourArray = [...myArray,...yourArray]
console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩
 ```

Give an example of using the spread operator to add a new item to an array.
```
const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]
```
Give an example of using the spread operator to combine two objects into one.
```
const hello = {hello: "😋😛😜🤪😝"}
const world = {world: "🙂🙃😉😊😇🥰😍🤩!"}

const helloWorld = {...hello,...world}
console.log(helloWorld) // Object { hello: "😋😛😜🤪😝", world: "🙂🙃😉😊😇🥰😍🤩!" }
```


In the video, what is the first step that the developer does to pass functions between components?

create the function where the state is 


In your own words, what does the increment function do?
the increment function uses map menthod to loop through the object and then looks for the name  in the object if the name matches the name clicked then it increments the count 


How can you pass a method from a parent component into a child component?
you can pass a method creating another list by using this. 'ref to the method' and then use props on the child component.

How does the child component invoke a method that was passed to it from a parent component?
use it by this.props.method()
