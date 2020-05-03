1. 🎖 Write a program to calculate the total price of your phone purchase. With these conditions
 * [ ] You will keep purchasing phones (hint: loop!) until you run out of bank balance.
 * [ ] You'll also buy accessories for each phone as long as your purchase amount is below your spending threshold.
 * [ ] After you've calculated your purchase amount, add in the tax, then print out the calculated purchase amount, properly formatted.
 * [ ] Finally, check the amount against your bank account balance to see if you can afford it or not.
 * [ ] Write a function called calculateTax which takes an argument 'amount' and calculates the tax you need to pay.
 * [ ] Write a function named formatAmount which returns you amount in this format '$ 132.45' make the decimal fixed to 2 places.
```js


const SPENDING_THRESHOLD = 200;
const TAX_RATE = 0.08;
const PHONE_PRICE = 99.99;
const ACCESSORY_PRICE = 9.99;

var bank_balance = 303.91;
var amount = 0;
var n=0;
while(bank_balance>0){
bank_balance=(bank_balance-PHONE_PRICE);
n=n++;
alert(n);
}
do{
    var purchase_amount=(bank_balance-ACCESSORY_PRICE);
}
while(bank_balance=SPENDING_THRESHOLD)
alert(purchase_amount);

    
}
```
 ⛑ Answer of the above will `$334.76`.

2. 🎖 Write a for loop that will iterate from 0 to 20. For each iteration, it will check if the current number is even or odd, and report that to the screen using `alert` (e.g. "2 is even").
```js
var i;
for(i=0;i<21;i++)
{if(i%2==0)
alert(i +" is even");
else
alert(i+" is odd");}
```

3. 🎖Write a for loop that will iterate from 0 to 10. For each iteration of the for loop, it will multiply the number by 9 and log the result in console (e.g. "2 * 9 = 18").
```
   var i,j;
   for(i=0;i<11;i++)
   {  j=i*9;
       alert(j);
   }
   ```
4. 🎖Use a nested for loop to show the tables for every multiplier from 1 to 10 (100 results total).
(e.g.
"1 * 1 = 1"
"1 * 2 = 2"
"1 * 3 = 3"
"1 * 4 = 4"
.... for all 100 results)
```
var i,j,k;
for(i=1;i<11;i++){
    for(j=1;j<11;j++){
        k=i*j;
        alert(i+"*"+j+"="+k);}
}
```
5. 🎖Show the following output using one loop.
```js
// 1, 2, 3, 4, 5
var i;
for(i=1;i<6;i++)
alert(i);
// 6, 7, 8, 9, 10
for(i=6;i<11;i++)
alert(i);


```

6. 🎖Use a while loop to add up the numbers 1 to 20.
```js
 var i=1,sum=0;
while(i<21)
{   sum+=i;
}alert(sum);
```

7. 🎖Use a while loop to print out the even number from 1 to 20. (You'll need Modulus for this. And an IF Statement.)
```js
var i=1;
while(i<21)
{
    if(i%2==0)
    {alert("even number is"+i);}
}
```

