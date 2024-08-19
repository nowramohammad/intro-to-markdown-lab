**bold**


<h1>Writing a Function in JavaScript</h1>

In JavaScript, functions are blocks of reusable code. They allow you to bundle functionality, make it more readable, and avoid repetition. Here's a brief tutorial on writing an arrow function in JavaScript.


<h2> 1.Basic syntax</h2>

<h4>const: functionName = (params) => {
  // code to be executed
}

const: const should be used whenever a function expression is assigned to a variable.
The function name: The name you choose for the function.
Parameters: Optional comma separated parameters. This is the data passed into the function. If there are no parameters, the () is still required.
The arrow syntax: Indicates that this will be a function.
The body: The statements that make up the function itself. Surrounded by curly braces.</h4>

<h3>Example:</h3>

<h4>const greet = (name) => {
  console.log("Hello, " + name + "!");
}

Tip: Functions often perform actions, so naming with a verb can make it clear what the function does. Examples include fetchData( ), calculateArea( ), or printReport( ). </h4>

<h2>2. Calling a function</h2>

<h4>To execute the function, you call or invoke it by using its name followed by parentheses.</h4>

<h3>Example:</h3>

<h4>greet('Alice'); // Outputs: Hello, Alice!</h4>

<h2>3. Return values</h2>

<h4>Functions can process data input and output a value using the return keyword.</h4>

<h3>Example:</h3>

<h4>const addNums = (numA, numB) => {
  return numA + numB
}

const total = addNums(2, 4);

console.log(total) // Expected value: 6

For more information on functions and how they are used in JS, check out the MDN docs. 
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions</h4>
