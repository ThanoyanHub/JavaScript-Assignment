# JavaScript-Assignment
1. What is a variable?
A variable is a named container used to store data values in memory.

2. How do you declare a variable?
In modern JavaScript, you declare a variable using one of three keywords followed by a name:
let name = "Alex";

3. Differences between var, let, and const
var is RE-assignable and Re-declarable
let is non Re-assignable and Re-declarable
const is non Re-assignable and Re-declarable

4. Explain variable hoisting
Hoisting is JavaScript's default behavior of moving declarations to the top of the current scope.
Variables declared with var are initialized as undefined.

5. Scoping rules
Global Scope: Variables declared outside any function/block; accessible everywhere.
Function Scope (var): Accessible only inside the function where it is defined.
Block Scope (let, const): Accessible only inside the curly braces {} where it is defined (e.g., inside an if statement or a for loop).

6. Template Literals
Template literals allow you to create strings using backticks (`) instead of quotes. They support string interpolation (inserting variables directly) and multi-line strings.

7. Primitive Data Types
      String 
      Number 
      BigInt 
      Boolean 
      Undefined 
      Null
      Symbol
8. null vs. undefined
undefined: Means a variable has been declared but has not yet been assigned a value.
null: Is an assignment value. It is used by developers to represent "no value" or an empty object.

9. How to verify the type
Use the typeof operator:
    typeof "Hello";

10. Primitive vs. Reference Types
Primitive Types: Stored directly in the variable (stack). When you copy them, you create a real copy of the value.
Reference Types (Objects, Arrays): The variable stores a pointer to the data's location in memory (heap). When you copy them, both variables point to the same data.

11. String to Number
The most common way is using Number():
    let str = "10";
    let num = Number(str);

12. Number to String
Use the .toString() method or the String() constructor:
    let num = 25;
    let str = num.toString();

13. Methods to convert String to Number
Number(str): Direct conversion; returns NaN if the string contains non-numeric characters.
parseInt(str): Extracts the first integer it finds; stops at a non-digit.
parseFloat(str): Similar to parseInt but includes decimals.
Unary Plus (+str): A shorthand way to trigger conversion.

14. Handling Type Conversion (Number + String)
When you add a number and a string, JavaScript performs coercion. It converts the number to a string and concatenates them.

15. What is an Object?
An object is a collection of key-value pairs. It allows you to store complex data and entities under one name. Keys (properties) represent the "what," and values represent the "data."
    let car = {
      brand: "Tesla",
      model: "Model 3"
  };
