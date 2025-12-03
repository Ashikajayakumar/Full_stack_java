                                                                           TYPE CONVERSATION

<h2 style ="centre"><b>TYPE CONVERSATION </b></h2>

* Most of the time, operators and functions automatically convert the values given to them to the right type.
* For example, ```alert``` automatically converts any value to a string to show it. Mathematical operations convert values to numbers.

  

  <h2 style ="text-align:center;"><b>STRING CONVERSATION </b></h2>


 ```js
let value = true;
alert(typeof value); // boolean
value = String(value); // now value is a string "true"
alert(typeof value); // string
```
```js
let age = 'true';
console.log(typeof age); // String
age=Number(age);
console.log(typeof age);//number
console.log(age);//NaN
```


 <h2 style="text-align:center;"><b>Numeric Conversion</b></h2>

 ```js
alert( "6" / "2" ); // 3, strings are converted to numbers
```
* We can use the ```Number(value)``` function to explicitly convert a ```value``` to a number:
```js
let str = "123";
alert(typeof str); // string
let num = Number(str); // becomes a number 123
alert(typeof num); // number
```

 <h2 style ="text-align:center;"><b>Boolean Conversion</b></h2>

 * Boolean conversion is the simplest one.

   It happens in logical operations (later we’ll meet condition tests and other similar things) but can also be performed explicitly with a call to ```Boolean(value).```

   ```js
   alert( Boolean(1) ); // true
   alert( Boolean(0) ); // false
   alert( Boolean("hello") ); // true
   alert( Boolean("") ); // false
   ```

                                                               Basic operators

1. “unary”, “binary”, “operand”
2. Assignment
3. Modify-in-place
4. Increment/decrement
5. Bitwise operators

<h2 align="center"><b> 1.“Unary”, “Binary”, “Operand”</b></h2>

 <h3 align="center""><b> A. Unary </b></h3>

* An operator is *"unary"* if it has a single operand. 
 ```js
let x = 1;
x = -x;
alert( x ); // -1, unary negation was applied
```

 <h3 align=" center"><b>  B. Binary  </b></h3>

* An operator is *"binary"* if it has two operands. The same minus exists in binary form as well:
```js
let x = 1, y = 3;
alert( y - x ); // 2, binary minus subtracts values
```

  <h3 align=" center"><b>  C.Operator  </b></h3>
  
                                                                              Maths
The following math operations are supported:

1. Addition +,
2. Subtraction -,
3. Multiplication *,
4. Division /,
5. Remainder %,
6. Exponentiation **.


```js
alert( 5 % 2 ); // 1, the remainder of 5 divided by 2
alert( 2 ** 2 ); // 2² = 4
alert( 4 ** (1/2) ); // 2 (power of 1/2 is the same as a square root)


let s = "my" + "string";
alert(s); // mystring

let x = 1;
alert( +x ); // 1

let y = -2;
alert( +y ); // -2

// Converts non-numbers
alert( +true ); // 1
alert( +"" );   // 0
```

<h2 align="center"><b>2. Assignment</b></h2>

* assignment ```=``` is also an operator

<h3 align="center"><b>A. Assignment = returns a value</b></h3>

* The fact of ```=``` being an operator, not a “magical” language construct has an interesting implication.
* All operators in JavaScript return a value. That’s obvious for ```+``` and ```-```, but also true for ```=```.
* The call ``` x = value``` writes the ```value``` into ```x``` and then returns it.

```js
let a = 1;
let b = 2;

let c = 3 - (a = b + 1);

alert( a ); // 3
alert( c ); // 0
```

<h3 align="center"><b>B. Chaining assignments</b></h3>
  
```js 
let a, b, c;
a = b = c = 2 + 2;
alert( a ); // 4
alert( b ); // 4
alert( c ); // 4
```

<h2 align="center"><b>  3. Modify-in-place </b></h2>

* This notation can be shortened using the operators ```+=``` and ```*=```
  
```js
let n = 2;
n += 5; // now n = 7 (same as n = n + 5)
n *= 2; // now n = 14 (same as n = n * 2)
alert( n ); // 14
```

<h2 align="center"><b> 4. Increment/decrement</b>

### Increment
```js
let counter = 2;
counter++;        // works the same as counter = counter + 1, but is shorter
alert( counter ); // 3
```

### Decrement
```js
let counter = 2;
counter--;        // works the same as counter = counter - 1, but is shorter
alert( counter ); // 1
```



<h2 align="center"><b> 5. Bitwise operators </b></h2>

* Bitwise operators treat arguments as 32-bit integer numbers and work on the level of their binary representation.
* These operators are not JavaScript-specific. They are supported in most programming languages.

The list of operators:

1. AND ( & )
2. OR ( | )
3. XOR ( ^ )
4. NOT ( ~ )
5. LEFT SHIFT ( << )
6. RIGHT SHIFT ( >> )
7. ZERO-FILL RIGHT SHIFT ( >>> )
