# My JavaScript Study Notes
After learning React I decided to go back to revise the basics of JavaScript so that I can really comprehend it and use it wisely (I hope). 

## The Basics
### Features
- Lightweight language that doesn't consume much memory
- cross-plateform
- object-oriented - a language based on objects
- One of the three core web development languages
- Can be used on both client-side and server-side (with node.js)
- Popular JS frameworks/libraries: React, Angular, Vue, JQuery etc

### Metaphor
- HMTL - Content [Nouns]
- CSS - Presentation [Adjectives]
- JS - Dynamic & Interactive Effects [Verbs]

### Variables
- Naming convension : camelCase
- Cannot start with numbers or symbols (except for "$" or "_")
- Cannot use reserved JS keywords as variable names (ie. function, delete, if etc)
  
### Primitive JS Data Types (Non-object)
1. Number: Floating point nubmers (decimal/integers)
2. String: Sequence of characters (text)
3. Boolean: Logical data type (true/false)
4. Undefined: Data type of a variable yet to have a value assigned
5. Null: Non-existent

JS has dynamic typing - data types are automatically assigned to variables:
- Pro: Convenient, save time
- Con: Source of potential bugs that are harder to find

### Type Coercion
- JS automatically converts types when concatenating variables
- Eg. Converting number into string:
```javascript
const firstname = 'Sam'
const age = 20

console.log(firstname + ' is ' + age)
```
Result: Same is 20

### Variable Mutation
- Variable type is mutable with var variable declaration
```javascript
var age = 10
age = 'ten'
```
   
### Comments
``` javascript
// Single line comment

/*
   Multiline 
   comment
*/
```

### Console Scripts
``` javascript
console.log("Displays text in console")
```

### Operators
- Operators are like functions that are written in different ways in JS.
- Math operators: +, - , *, /, %
- Logical operators: >, <, ==, ===, >=, <=, !
- Typeof operator: typeof (tells type of variables)
``` javascript
var x
console.log(typeof x)
```
Result: undefined