# Js Value Types

Javascript has two types of values: primitive values and reference values.

Primitive Types: Primitive Types are the most fundamental blocks of data as for javascript, these are strings, numbers, null, undefined, boolean, bigint and recently added symbol.

Reference Types: Reference types are generally container's to hold multiple primitive/reference types in them.

## Stack and heap memory
When we declare variable, the Javascript engine allocates the memory on two locations: stack and heap.

e.g provided image of typical stack and heap setup
![stack](https://www.javascripttutorial.net/wp-content/uploads/2022/01/JavaScript-heap-memory.svg)

### Stack 
```javascript
const name = 'Yogest';
const age = 47;
```
As because `name` and `age` are primitive values, the Javascrip engines stores these variables on the stack


But unlike primitive values, Javascript stores objects(objects,arrays) and functions on the heap, As reference values are not fixed they are allocated space in heap memory.


* *Javascript has two types of values: primitive values and reference * values.*
* *You can add, change, or delete properties to a reference value, whereas you cannot do it with a primitive value.*
* *Copying a primitive value from one variable to another creates a * separate value copy. It means that changing the value in one variable does not affect the other.*
* *Copying a reference from one variable to another creates a reference so that two variables refer to the same object. This means that changing the object via one variable reflects in another variable.*


