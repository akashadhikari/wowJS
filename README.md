# wowJS
You heard that right!

## 001 Console Stuff

Try doing these on your browser console.
```javascript
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
```javascript
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

```javascript
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

## 003 Data types

- Primitive Data Type
- Reference data type

**Primitive Type**  
String, Number, Boolean, Null, Undefined, Symbols (ES6)

**Reference Type**  
Arrays, Object Literal, Function, Dates, etc.

```javascript
// PRIMITIVE TYPE
// ==============

// String  
const name = 'Akash';
console.log(typeof name)

// Number
const num = 42;
console.log(typeof num)

// Boolean
const isAwesome = true;
console.log(typeof isAwesome)

// Null
const sad = null;
console.log(typeof sad)

// Undefined
let test;
console.log(typeof test)

// Symbol
const sym = Symbol()
console.log(typeof sym)

// More examples on Symbol
const symbol1 = Symbol();
const symbol2 = Symbol(42);
const symbol3 = Symbol('foo');

console.log(typeof symbol1);
// expected output: "symbol"

console.log(symbol3.toString());
// expected output: "Symbol(foo)"

console.log(Symbol('foo') === Symbol('foo'));
// expected output: false

// REFERENCE TYPE
// ==============

// Array
languages = ['python', 'javascript', 'english']

console.log(languages)

// Object literal
const person = {
    name: 'Akash',
    address: 'Kathmandu'
}
console.log(typeof person)

// Date example
const today = new Date()
console.log(today)
console.log(typeof today)
```