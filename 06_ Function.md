                                            FUNCTION
                   
 <h2 align="center"><b> Function </b></h2>
* Functions are the main “building blocks” of the program. They allow the code to be called many times without repetition.

<h2 style="text-align:center;"><b> Function Syntax </b></h2>

* To create a function we can use a *function declaration*.
  
```js
  function functionName(parameter1, parameter2) {
    // code to execute
}
```

<h2 align="center"><b> Local Variable  </b></h2>

```js
function showMessage() {
  let message = "Hello, I'm JavaScript!"; // local variable
  alert( message );
}
showMessage(); // Hello, I'm JavaScript!
alert( message ); // <-- Error! The variable is local to the function
```

<h2 align="center"><b> Outer Variable  </b></h2>

```js
let userName = 'John';
function showMessage() {
  let message = 'Hello, ' + userName;
  alert(message);
}
showMessage(); // Hello, John
```
<h2 align="center"><b> Parameter </b></h2>

```js
function showMessage(from, text) { // parameters: from, text
  alert(from + ': ' + text);
}
showMessage('Ann', 'Hello!'); // Ann: Hello! (*)
showMessage('Ann', "What's up?"); // Ann: What's up? (**)
```

<h2 align="center"><b> Default Value </b></h2>
* If a function is called, but an argument is not provided, then the corresponding value becomes  ```undefined```.


```js
function showMessage(from, text = "no text given") {
  alert( from + ": " + text );
}
showMessage("Ann"); // Ann: no text given
```

<h2 align="center"><b> Returning Value </b></h2>

```js
function sum(a, b) {
  return a + b;
}
let result = sum(1, 2);
alert( result ); // 3
```

<h2 align="center"><b> Arrow Function </b></h2>

```js
let sum = (a, b) => a + b;
/* This arrow function is a shorter form of:
let sum = function(a, b) {
  return a + b;
};
*/
alert( sum(1, 2) ); // 3
```

