# wowJS
You heard that right!

## 001 Console Stuff

Try doing these on your browser console.
```
// Log to console
console.log('Hello World');
console.log(123);
console.log(true);
var greeting = 'Hello';
console.log(greeting);
console.log([1,2,3,4]);
console.log({a:1, b:2});
console.table({a:1, b:2});

console.error('This is some error');
console.clear();
console.warn('This is a warning');
```
Calculate console time between certain events.
```
console.time('Hello');
  console.log('Hello World');
  console.log('Hello World');
  console.log('Hello World');
  console.log('Hello World');
  console.log('Hello World');
  console.log('Hello World');
console.timeEnd('Hello');
/*
  multi
  line
  comments
*/

```

## 002 Var, Let and Const

Try below on a browser console

```
// var

var varName = 'Akash';
console.log(varName);
varName = 'Adhikari' // reassign
console.log(varName);

// let

let letName = 'Akash';
console.log(letName);
letName = 'Adhikari';
console.log(letName); // reassign

// const

const name = 'Akash'
console.log(name)


// name = 'Adhikari' 
// console.log(name)
// ERROR: Cannot reassign the name like the above

// const something;
// ERROR: Also, we cannot just leave the const assigned


// const for object
const person = {
    name: 'Akash',
    address: 'Nepal'
}
console.log(person)
console.table(person)

// ressign person.name to something else
person.name = 'Jaime'
person.address = 'Kings Landing'
console.table(person)

// const for array
const arr = [1,2,3,4,5]
arr.push(6)
console.log(arr)

```