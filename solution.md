## Return Negative

```js
function makeNegative(num) {
  if (num < 0)
  {return num * 1}
  else {
    return num * -1
}}
```

## Sum of Positive

```js
function positiveSum(arr) {
  let total = 0;    
  for (i = 0; i < arr.length; i++) {  
    if (arr[i] > 0) {                   
      total += arr[i];                  
    }
  }
  return total;
  }                
```

## Function 2

```js
function square(num)
{ return num * num}
```

## Sum Arrays

```js
function sum (numbers) {
    "use strict";
    let sumNum=0
        for(let i = 0; i < numbers.length; i++) {
          sumNum += numbers[i]
        }
  return sumNum;
}
```

## Reversed Strings

```js
function solution(str){
  return str.split('').reverse('').join('');  
}
// full disclosure, I had to find this in the answers segment on code wars. I did not know what a split or join command was until this. I also confess I do not know why the '' indicates the input is to be inserted there, while a blank () does not. I find it all very strange. That aside, it does make sense to me. You split the word into various components, reverse them, and then join them together.
```
