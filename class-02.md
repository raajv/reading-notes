# TEXT

Semantic information can be displayed in an HTML document using many different tags.

For eg.

- <b> <strong> makes the text **BOLD**
- <i> <em> makes the text *italic*
- </br> introduces a line break so that the text is displayed on the next line
- <address> Browsers often display the
content of the <address>
element in italics.
- <del> puts a line through the center of the text


# CSS

## CSS allows you to create rules that specify how the content of
an element should appear.


CSS works by associating rules with HTML elements. These rules govern
how the content of specified elements should be displayed. A CSS rule
contains two parts: a selector and a declaration.


` p { color : blue ;}`

Where *p*  is a selector which will tell all the p elements in the html page to apply the styling
And *{}* is the *declaration* which shows how the element selected is to be styled.

The text after the ":" Is called the property for eg "color" which affects how the elements are displayed.

There are different types of selectors , some of them are

- universal selector "*" which applies styling to all the elements in a page
-class selector "." which applies to the value of the class attribute given to the element
-child selector ">" which targets all the elements nested in other elements for eg li>a
-type selector , just like the example above targets the individual elements


CSS rules cascade from top to bottom in the css document
They can appear in different document( linked via external stylesheet) or be in the HTML document itself ( internal or inline)



# BASIC JAVASCRIPT INSTRUCTIONS

## STATEMENTS

A script is a series of instructions that the computer can follow one by one. Each individual step is called a statement.

One should always write comments to help explain what your code does.

## VARIABLES

a script will store information bits it needs to do its job. It stores this data in variables.

Before using a variable we need to give it a name , this is called declaring a variable.

Once you name your variable you will have to assign it a value.Values can be numbers , strings or booleans

## ARRAYS

Arrays store a list of values.

If you don't know how many
items a list will contain, rather
than creating enough variables
for a long list (when you might
only use a small percentage
of them), using an array is
considered a better solution. - Pg 70 jon duckett js book

you create an array using box brackets instead of paranthesis and separate the values with a ","

# OPERATORS CHEAT SHEET

Arithmatic operators -
- `+` addition  
- `-` subtraction
- `*` multiply
- `/` divide
- `%` divides two values and returns the remainder

String operators - 
`+` is the only string operator 

# DECISION AND LOOPS

There are places in a script where a decision has to be made what code is to run next , a flow 
chart helpts in making these decisions

to make a decision -

The condition is evaluated and then a conditional statement says what to do in a given situation

for eg -

`if (score>50){
  document.write('you passed!');
} else {
  document.write('try again');
}`


eg of comparion operators are -

- `>,<,>=,<=`

eg of logic operators are -

- `&&, ||`