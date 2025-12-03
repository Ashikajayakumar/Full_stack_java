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

<h2 style="text-align:center;"><b>“Unary”, “Binary”, “Operand”</b></h2>

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

   
