1. In code below "Mark" is a string.  What is name?
```js
var name = "Mark";
```
//variable name//

2. Find the error if any
```js
  var product cost = 3.45;
```
//var productCost = 3.45;//

3. Write `Right or Wrong` next to the code below.

```js
  "Hello World"-right
  'Hello World"-wrong
  "Hello World'-wrong
  'Hello World'-right
```

## Write `VALID` and `INVALID` infront of the variable name defined below
```js
var man; valid
var 1girl; invalid
var woman3; valid
var -girl; invalid
var blackDog; valid
var 42; invalid
var $42; valid
var userName; valid
var x, y, z;
//var x=3, y=2, z=1;
console.log(x,y,z);
VM531:2 3 2 1  valid
var x = 5, y = 6, z = 7; valid
var x = 5 + 10 + 2; valid
```

## Basic Operations

Mathematical Operations:

Solve this using mathematical operations. (+, -, *, / , etc)

```js
var amount = 2080;
// Define a new variable and store the value that is 80 less then the value of amount.
var amount = 2080;
var one;
one= amount-80;
2000
// Define a new variable and store the value that is 200 more then the value of amount.
var amount = 2080;
var two;
two= amount+200;
2280;
// Define a new variable and store the value that is 4 times the value of amount.
var amount = 2080;
var three;
three= amount*4;
8320;
// Define a new variable and store the reminder when the value of amount is  divided by 21.
var amount = 2080;
var four;
four= amount%21;
1;
```

Logical Operation:

Solve this using logical operations. (<, >, &&, ||)

```js
var johnAge = 45;
var markAge = 35;

// Check who is older eithe John or Mark
if (johnAge>markAge)
alert(johnAge);
else
alert(markAge);
..........................
johnAge>markAge;
true;
// Check who is younger
if (johnAge>markAge)
alert(markAge);
else
alert(johnAge);
.........................
johnAge>markAge;
true;
// Check if their age is equal
var johnAge = 45;
var markAge = 35;
johnAge>markAge && markAge<johnAge;
if (false)
alert ("equal");
else
alert("not equal");

// Create a new variable and assign the age of john to new variable.
var johnAge = 45;
var john1=johnAge;
alert(john1);
// Check if john is equal to or greater then mark.
var johnAge = 45;
var markAge = 35;
johnAge>=markAge;
true

// Check if john is less then or equal to mark.
var johnAge = 45;
var markAge = 35;
johnAge<>=markAge;
false
// Calculate the average age of john and mark and assign to a new variable.
var average= (johnAge+markAge)/2;
alert(average);
```