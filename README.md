# Javascript-code-practice
-Data Types in Programming
A data type is a classification of data that determines the kinds of values that a variable can store in programming. To write programs that work, it is imperative to comprehend the various data types that exist across programming languages.

JavaScript, often referred to as the “language of the web,” is a versatile and widely used programming language that allows developers to create dynamic and interactive web applications.

Because JavaScript is dynamically typed, you do not need to declare a variable’s data type before using it. Instead, based on the value assigned to the variable, JavaScript will automatically determine the data type. Because of this feature, JavaScript is more flexible than statically typed languages, but it also necessitates that you understand the various data types and how they behave.

In JavaScript, data is fundamental, and it can be categorized into two main types: primitive and non-primitive (also known as reference) data types. Understanding the distinction between these two is crucial for writing efficient and bug-free JavaScript code.

Every variable has a data type that tells what kind of data is stored. There are two types of data types in JavaScript.

Primitive data types
Non-primitive data types
Primitive data types: The predefined data types provided by the JavaScript language are known as primitive data types. Primitive data types are also known as in-built data types. They are directly stored in memory, and their values are not subject to change once they are assigned. String, Boolean, Number, BigInt, Null, Undefined, and Symbol are the six primitive data types available in JavaScript.

Non-primitive data types: The data types that are derived from the primitive data types of the JavaScript language are known as non-primitive data types. It is also known as “derived data types” or “reference data types.”

Non-Primitive: Objects (arrays, functions) are also called object references.

The fundamental difference between primitives and non-primitives is that primitives are immutable and non-primitives are mutable.

EXAMPLES OF JAVASCRIPT PRIMITIVE AND NON-PRIMITIVE DATA TYPES
Primitive Data Types
JavaScript has six primitive data types:

1. Number
The Number data type includes both integers and floating-point numbers. For example:

let age = 30;
let price = 19.99;
2. String
The String data type represents sequences of characters enclosed in single or double quotes. For example:

let name = "John";
3. Boolean
The Boolean data type has only two possible values: true and false. It’s commonly used for conditional statements and logical operations. For example:

let isTrue = true;
let isFalse = false;
4. Undefined
The undefined data type represents a variable that has been declared but has not been assigned a value yet. For example:

let uninitializedVariable;
5. Null
The null data type is used to indicate the absence of a value or a deliberate non-value. For example:

let emptyValue = null;
6. Symbol (ES6)
Introduced in ECMAScript 6 (ES6), the Symbol data type represents a unique and immutable value, often used as object property keys. Symbols help avoid name collisions. For example:

const uniqueSymbol = Symbol('description');
When it comes to primitive data types, their values are what are compared. Two variables with the same primitive value are considered equal.

Non-primitive data types
1. Object
The Object data type is a versatile container that can hold key-value pairs, making it suitable for complex data structures. Objects can store functions and other objects, making them a fundamental part of JavaScript. For example:

const person = {
name: "Alice",
age: 25,
};
2. Array
The Array data type is a specialized form of an object used to store ordered lists of values. Arrays can store elements of different data types and are accessed by numerical indices. For example:

const colors = [“red”, “green”, “blue”];
3. Function
Functions are also objects in JavaScript. They can be assigned to variables, passed as arguments, or returned from other functions. For example:

function greet(name) {
return `Hello, ${name}!`;
}
4. Date
The Date data type represents dates and times and provides methods for working with them. For example:

const today = new Date();
5. Custom Objects
Developers can create custom non-primitive data types by defining their own object structures. This allows for more specialized data storage and manipulation.

When comparing non-primitive data types, their references are compared. Two variables that reference the same object are considered equal.
