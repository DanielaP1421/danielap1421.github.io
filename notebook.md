# My Coding Notebook
---
## Table of ontents:
- [Binary notes](#binary-notes)
     -[Binary Flippy-do/number system](#binary-flippy-do-with-number-system)
     -[Practice](#pratice)
-[Code definitions](#code-definition)
-[Notebook Style Guide](#markdown-style-guide-for-coding-notebooks)

---
8/28 class:
## Patterns:

|000|111|101|110|
|-|-|-|-|
|001|011|110|100|

---
## Binary:
Binary is a number system that use 0 and 1.
     
     0 is unactive
     1 is active

## Binary Flippy-do/number system:

|Power:|2^7|2^6|2^5|2^4|2^3|2^2|2^1|2^0|
|-|-|-|-|-|-|-|-|-|
|Value:|128|64|32|16|8|4|2|1|
|Binary:|0|1|0|0|0|1|0|1|

### Add up the values to get the answer:
    100010 = 34
    10100011 = 163
    1111111 = 127
    11011011 = 219
    10101010 = 170
    01000101 = 69
    00000100 = 4
    00111011 = 59
    00100011 = 35

---

## Code Definition:

| Term | Definition | Base Structure / Syntax | Real Life Example | App Example |
|------|------------|--------------------------|-------------------|-------------|
| variable | A named container used to store a value that may change. | `var x = 5;` | age | time |
|      | A fixed value that cannot change once set. | `const PI = 3.14;` | navigation buttons | logos |
| Data type | The kind of value a variable holds, like numbers or text. | `int`, `String`, `bool` |  |  |
| Strings | A sequence of characters used to represent words or text. | `"Hello World"` | comments |  |
| Integer | Whole number values. | `int age = 16;` | score | streek |
| Double | Number values with decimals. | `double age = 16.2;` | space between yards | timer |
| Boolean | A value that can be true or false. | `bool isLoggedIn = false;` |  |  |
| List | A collection of values in a specific order. | `List<String> names = [];` |  |  |
| Null | A special value that means “nothing.” | `String? name = null;` |  |  |
| Function | A reusable block of code that performs an action. | `void sayHi() { print("Hi"); }` |  |  |
| Parameter | The information passed into a function to change how it works. | `greet(String name)` |  |  |
| Return | The result a function gives back. | `return total;` |  |  |
| Scope | Where a variable or function can be used. | (No set syntax — concept-based) |  |  |
| Class | Blueprint for creating objects with specific structure and behavior. | `class Dog {}` |  |  |
| Object | A specific version of a class. | `Dog myDog = Dog();` |  |  |
| Property | A variable that belongs to a class/object. | `String name;` |  |  |
| Method | A function that belongs to a class. | `void bark() {}` |  |  |
|      | A special function used to set up a class when it’s created. | `Dog(this.name);` |  |  |
|      | Hiding the inner workings of code so users only interact with what they need. | (Concept — not specific code) |  |  |
|      | Changing how a built-in or inherited function behaves. | `@override` |  |  |
|      | A function that does not return a value. | `void printMessage() {}` |  |  |

---
[Notebook Style Guide](style.md)
