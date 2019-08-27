

# Team Work Challenge

## Help Sheet

If you have never played with JavaScript or you see yourself a bit lost, we recommend performing one or a couple of free courses which will help you to have a better understanding of Javascript from the beginning. See links below:

Focus on the JavaScript topic:

https://learn.freecodecamp.org/

Here you will find the introduction to JavaScript tp review:

https://www.codecademy.com/learn/learn-javascript

If you already know some basic JavaScript we have written some information which might help you to be successful in the challenge.

### Variable

A variable is a named location for storing a value. That way an unpredictable value can be accessed through a predetermined name.

The var statement declares a variable, optionally initializing it to a value.

Syntax
```
var varname1 [= value1]
```

Demo:
```
var x = 1;

if (x === 1) {
  var x = 2;

  console.log(x);
  // expected output: 2
}

console.log(x);
// expected output: 2
```

Documentation: 

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/var


### Array

An array is an ordered collection of data (either primitive or object depending upon the language). Arrays are used to store multiple values in a single variable. This is compared to a variable that can store only one value. 

Each item in an array has a number attached to it, called a numeric index, that allows you to access it. In JavaScript, arrays start at index zero and can be manipulated with various methods. 

Syntax:
```
[element0, element1, ..., elementN]
```

Demo:
```
var fruits = ['Apple', 'Banana'];

```

Documentation: 

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array

### For loop

The for statement creates a loop that consists of three optional expressions, enclosed in parentheses and separated by semicolons, followed by a statement (usually a block statement) to be executed in the loop.

Syntax
```
for ([initialization]; [condition]; [final-expression])
   statement
```

Demo:
```
var str = "";

for (var i = 0; i < 9; i++) {
  str = str + i;
}

console.log(str);
// expected output: "012345678"
```

Documentation: 

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for

### Functions

A function is a code snippet that can be called by other code or by itself, or a variable that refers to the function. When a function is called, arguments are passed to the function as input, and the function can optionally return an output. A function in JavaScript is also an object.

A function name is an identifier declared as part of a function declaration or function expression. The function name's scope depends on whether the function name is a declaration or expression.

Functions are one of the fundamental building blocks in JavaScript. A function is a JavaScript procedure—a set of statements that performs a task or calculates a value. To use a function, you must define it somewhere in the scope from which you wish to call it.

Syntax
```
function name(parameter1, parameter2) {
  // code to be executed
}
```

Demo:
```
var number = 2;

function square(number) {
  return number * number;
}

square(number);

// expected output: 4
```

Documentation: 

https://developer.mozilla.org/en-US/docs/Glossary/Function

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions


### If statement

The if statement executes a statement if a specified condition is truthy. If the condition is falsy, another statement can be executed.

Syntax
```
if (condition)
   statement1
[else
   statement2]
```

Demo:
```
function testNum(a) {
  if (a > 0) {
    return "positive";
  } else {
    return "NOT positive";
  }
}

console.log(testNum(-5));
// expected output: "NOT positive"
```

Documentation: 

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else

### Objects In Javascript

In JavaScript, objects are king. If you understand objects, you understand JavaScript.
All JavaScript values, except primitives (like string), are objects.

Javascript variables can contain single values
var person = "Maria Garcia ";
Javascript objects can contain many values
var person = {firstName:"Maria", lastName:"Garcia", age:50, eyeColor:"blue"};
The named values, in JavaScript objects, are called properties.

The syntax for accessing the property of an object is either of the two below options:
- objectName.property
- objectName['property']
to reassign a propery we can use:
person.lastName = "Jones";
if this propery doesnt exist it will add a new one to the object.

Documentation: 


https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_Objects



## Team Challenge
You are working together as a great team and you want to develop the best project ever!! Teamwork is super important for succeeding :smile: You know that it is crucial to have the best performers in your team and make your project scalable. Let’s go and create a formula for success!
Your team needs 2 developers, 1 designers and 1 data analyst.

- First thing we need is to create an object with the names and roles of each one of the 4 members of the team

- Awesome! Now we need to have their names and position. You need to print their names in a different screen

- Ok super! now we need to know just the name of the person who works in Data

- Great, the project is a success but we need to get a CTO. It should be one of the founders of the project. Also, you should add someone else who will get the old position of the new CTO.

