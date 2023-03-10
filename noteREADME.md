# ALL YOU NEED TO KNOW || JAVASCRIPT 
## Console
Console is a built-in object that containe error messages or log data and help us to debug our codes.

### console.log();
console.log() is a method that print our output in a message to the browser's developer console.

``` javascript
console.log("Hello, world!");
```

### Variables
Variables, its like a container that used to store and manipulate data in a program.

let and const are the two new keywords that were introduced in ECMAScript 6. The let keyword is used to declare a block-scoped variable, and the const keyword is used to declare a variable that cannot be reassigned.

In JavaScript, variables can be used to hold any type of data like numbers, strings, objects, arrays and functions.

```javascript
let number = 10;
let string = 'Hello World';
let obj = {name: 'John', age: 25};
let array = [1,2,3,4,5];
let func = function(){console.log('Hello')}

```
### Reserved Words
In JavaScript, a reserved word is a word that has a specific meaning and cannot be used as an identifier (such as a variable or function name) in the code. Examples of reserved words in JavaScript include "var", "function", "if", "else", "for", "while", and "return". These words are reserved by the language and cannot be used for any other purpose.

### Data Types
There are two major data type present in JavaScript with sub categories

1. Primitive
    - Number
    - String
    - Boolean
    - Null
    - Undefined
2. Object
    - Array
    - Object
    - Function

### String
 A string is a sequence of characters enclosed in single or double quotes

 ``` javascript
let str = 'String';
let str2 = "String";
let str3 = `String`;
let str4 = String(450);
````

### Boolean 
A Boolean data type is a primitive data type that can have only two values: true or false. Boolean values are often used in conditional statements to check if a certain condition is true or false. For example, you might use a Boolean variable to check if a user is logged in or not.

In JavaScript, you can create a Boolean variable by assigning the values true or false to it, or by using the Boolean() function to convert a non-Boolean value to a Boolean value.

``` javascript
let x = true;
let y = false;
let z = Boolean(1); // true
```

Boolean values are also used in logical operations such as && (and), || (or) and ! (not)

``` javascript
let a = true;
let b = false;
console.log(a && b); //false
console.log(a || b); // true
console.log(!a); // false
```

### Null & Undefined
Null refers to an already assigned value whereas Undefined is a declared variable but its value does not assign yet

``` javascript
    let studentObj = null;
    let studentID;
    console.log(studentObj);
    console.log(studentID);
```