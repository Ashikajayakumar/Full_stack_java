                                                                                        COMPARSION

<h2 style="text-align:center;"><b> 1.Boolean Comparsion </b></h2>

```js
alert( 2 > 1 );  // true (correct)
alert( 2 == 1 ); // false (wrong)
alert( 2 != 1 ); // true (correct)
```

<h2 style="text-align:center;"><b>  2.String Comparsion </b></h2>

``` js
alert( 'Z' > 'A' ); // true
alert( 'Glow' > 'Glee' ); // true
alert( 'Bee' > 'Be' ); // true
```
 <h2 style="text-align:center;"><b> Comparison of different types </b></h2>

 ```js
alert( '2' > 1 ); // true, string '2' becomes a number 2
alert( '01' == 1 ); // true, string '01' becomes a number 1


alert( true == 1 ); // true
alert( false == 0 ); // true
```


<h2 style="text-align:center:"><b>Comparison with null and undefined</b></h2>

```js
alert( null === undefined ); // false
alert( null == undefined ); // true
```
```js

alert( null > 0 );  // (1) false
alert( null == 0 ); // (2) false
alert( null >= 0 ); // (3) true


alert( undefined > 0 ); // false (1)
alert( undefined < 0 ); // false (2)
alert( undefined == 0 ); // false (3)
```





                                                                                  Conditional  Statement 
<h2 align="center"><b>If condition </b></h2>


```js
let year = prompt('In which year was ECMAScript-2015 specification published?', '');
if (year == 2015) alert( 'You are right!' );
```

<h2 align="center"><b>else statement</b></h2>

```js 
let year = prompt('In which year was the ECMAScript-2015 specification published?', '');

if (year == 2015) {
  alert( 'You guessed it right!' );
} else {
  alert( 'How can you be so wrong?' ); // any value except 2015
}
```

<h2 align="center"><b> else -if Statement</b></h2>

```js
let year = prompt('In which year was the ECMAScript-2015 specification published?', '');

if (year < 2015) {
  alert( 'Too early...' );
} else if (year > 2015) {
  alert( 'Too late' );
} else {
  alert( 'Exactly!' );
}
```

<h2 align="center"><b> Multiple  </b></h2>

```js
let age = prompt('age?', 18);

let message = (age < 3) ? 'Hi, baby!' :
  (age < 18) ? 'Hello!' :
  (age < 100) ? 'Greetings!' :
  'What an unusual age!';

alert( message );
```
                                                                   Logical  

<h2 align="center"><b>  OR( || ) </b></h2>

```js
let hour = 9;
if (hour < 10 || hour > 18) {
  alert( 'The office is closed.' );
}
```

<h2 align="center"><b> AND( &&) </b></h2>

```js
let hour = 12;
let minute = 30;
if (hour == 12 && minute == 30) {
  alert( 'The time is 12:30' );
}
```

<h2 align="center"><b> NOT( ! ) </b></h2>

```js
alert( !true ); // false
alert( !0 ); // true
```


