                                                            Logical

<h2 align="center"><b>While-Loop</b></h2>

```js
let i = 0;
while (i < 3) { // shows 0, then 1, then 2
  alert( i );
  i++;
}
```

<h2 align="center"><b>do- While-Loop</b></h2>

```js
let i = 0;
do {
  alert( i );
  i++;
} while (i < 3);
```

<h2 align="center"><b>for Loop</b></h2>

```js
for (let i = 0; i < 3; i++) { // shows 0, then 1, then 2
  alert(i);
}
```

<h2 align="center"><b> break </b></h2>

```js
for(let i=0;i<=10;i++){
  if(i==5){
    console.log(i);
    break;
  }
console.log(i);
}
```

<h2 align="center"><b> Continue  </b></h2>

```js
for (let i = 0; i < 10; i++) {
  // if true, skip the remaining part of the body
  if (i % 2 == 0) continue;
  alert(i); // 1, then 3, 5, 7, 9
}
```
<h2 align="center"><b> Switch  </b></h2>                                    

```js
let a = 2 + 2;

switch (a) {
  case 3:
    alert( 'Too small' );
    break;
  case 4:
    alert( 'Exactly!' );
    break;
  case 5:
    alert( 'Too big' );
    break;
  default:
    alert( "I don't know such values" );
}
```
