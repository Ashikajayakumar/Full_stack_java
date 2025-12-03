                                                                 DATA TYPE IN JAVASCRIPT

## Data Types

1. Number  
2. Big Integer  
3. String  
4. Boolean  
5. Null  
6. Undefined  
7. Object and Symbol


<h2 style="center;"><b>1.Number </b></h2>

* The number type represents both **integer** and **floating point numbers**.

### Example for Number

```js
alert(1/0)          // Infinity
alert(Infinity)     // Infinity
alert(-1/0)         // -Infinity
alert(NaN)          // NaN
alert("abc"/2)      // NaN
alert(NaN + 1)      // NaN
```

<h2 style="center;"><b>2.Big Integer </b></h2>

* In JavaScript, the “number” type cannot safely represent integer values larger than **(2⁵³ − 1)** (that’s 9007199254740991), or less than  **-(2⁵³ − 1)** for negatives.
  
### Example for Big Integer

```js
console.log(9007199254740991 + 1); // 9007199254740992
console.log(9007199254740991 + 2); // 9007199254740992
```

<h2 style="center;"><b>3.String </b></h2>

* In languages like C or Java, a single character has a special type called **char**.

* JavaScript has **only one type: string**.

   It can be empty, one character, or many characters.
  

### Example for Big Integer

```js
let str = "Hello";                          // Double
let str2 = 'Single quotes are ok too';      //Single
let phrase = `can embed another ${str}`;    //Backticks
```

<h2 style="center;"><b>4.Boolean </b></h2>

* The boolean  types only have values **true** and **false** values.
  

### Example for Boolean

```js
let nameFieldChecked = true; // yes, name field is checked
let ageFieldChecked = false; // no, age field is not checked
```

<h2 style="center;"><b>5.null </b></h2>

* The null - nothing,empty,value unknown

### Example for null

```js
let age = null;
console.log(age);        // null
console.log(typeof age); // "object"
```

<h2 style="center;"><b>5.undefined </b></h2>

* **undefined** means a variable is **declared but not assigned**.

### Example for undefined

```js
let age;
alert(age); // shows "undefined"
```


<h2 style="center;"><b>6.Object and Symbol </b></h2>

<h3 style="text-align:center;"><b>Object </b></h3>

* **Primitive** values (string, number, boolean, null, undefined, bigint, symbol) store only one value.
* But **objects** can store **multiple values** together — like a container.
  
### Example for object

```js
let age;
alert(age); // shows "undefined"
```


<h3 style="center;"><b>Symbol </b></h3>

* Symbols create **unique identifiers**.
* Even if two symbols have the same description, they are *never equal*.

### Example for Symbol

```js
let id1 = Symbol("id");
let id2 = Symbol("id");
console.log(id1 === id2);  // false
```


<h2 style="center;"><b> Interaction  </b></h2>

<h3 style="text-align:center;"><b> 1. alert  </b></h3>

* ```alert ```  shows a message and waits for the user to press “OK”.
  
 ```js 
 alert("Hello");
```



<h3 style="text-align:center;"><b> 2. prompt  </b></h3>

* ``` prompt ``` Ask for user input .
  
 ```js 
let test = prompt("Test");
```


  
<h3 style="text-align:center;"><b> 3. Confirm  </b></h3>

 * The function   ``` confirm ``` shows a modal window with a question and two buttons: **OK and Cancel**.

  
 ```js 
let isBoss = confirm("Are you the boss?");
alert( isBoss ); // true if OK is pressed
```
