# My Coding Notebook
---
## Table of ontents:
- [Binary Notes](#binary-notes)
     - [Binary Conversion Table](#binary-conversion-table)
     - [From Decimal Conversion Table](#convert-from-decimal)
- [Coding](coding)
     - [Code Definitions](#code-definition)
     - [Pseudocode and Java Table](pseudocode-java-reference)
     - [Variables and Datatypes](#variables-and-datatypes)
     - [Conditionals](#conditionals)
     - [Notebook Style Guide](style.md)

---
8/28 class:
## Binary Notes:

### Patterns:
|000|111|101|110|
|-|-|-|-|
|001|011|110|100|

---
### Binary:
Binary is a number system that use 0 and 1.
     
     0 is unactive
     1 is active

### Binary Flippy-do/number system:

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

### Binary conversion Table

Convert 110101 from Binary (base 2) to Decimal (base 10)
| Value        | 1   | 1   | 0   | 1   | 0   | 1   |
|--------------|-----|-----|-----|-----|-----|-----|
| base^Exponent (B^E) | 2^5 | 2^4 | 2^3 | 2^2 | 2^1 | 2^0 |  
| (B^E) * value       | 32*1 | 16*1 | 8*0 | 4*1 | 2*0 | 1*1 |    
| Results added       | 32+  | 16+  | 0+  | 4+  | 0+  | 1 |

**Result is 53**

### Convert from decimal

Convert 2989 from decimal (base 10) to hexadecimal (base 16)
| Value/base | 2989/16 | 186/16 | 11/16 |
|------------|----------|---------|--------|
| Result     | 186      | 11      | 0      |   
| Remainder  | D (13)   | A (10)  | B (11) |   

**Result is BAD**

---

## Coding:

### Code Definition:

| Term | Definition | Base Structure / Syntax | Real Life Example | App Example |
|------|------------|--------------------------|-------------------|-------------|
| Variable | A named container used to store a value that may change. | `var x = 5;` | age | time |
| Constant | A fixed value that cannot change once set. | `const PI = 3.14;` | navigation buttons | logos |
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
| Method | A function that belongs to a class. | `void bark() {}` | Drive a car |  |
| Constructor | A special function used to set up a class when it’s created. | `Dog(this.name);` |  |  |
| Abstraction | Hiding the inner workings of code so users only interact with what they need. | (Concept — not specific code) |  |  |
| Override | Changing how a built-in or inherited function behaves. | `@override` | Flash can run much faster than anyone else |  |
| Void | A function that does not return a value. | `void printMessage() {}` | Speaking |  |

---

### Pseudocode and Java Table:  

| **Concept** | **CSP Pseudocode** | **Java** |
|-------------|--------------------|----------|
| **Variables** | `x ← 5`<br/>`name ← "Alex"` | `int x = 5;`<br/>`String name = "Alex";` |
| **If/Else** | `IF score ≥ 60`<br/>`    DISPLAY "Pass"`<br/>`ELSE`<br/>`    DISPLAY "Fail"` | `if (score >= 60) {`<br/>`    System.out.println("Pass");`<br/>`} else {`<br/>`    System.out.println("Fail");`<br/>`}` |
| **Else If Chains** | `IF score ≥ 90`<br/>`    DISPLAY "A"`<br/>`ELSE IF score ≥ 80`<br/>`    DISPLAY "B"`<br/>`ELSE`<br/>`    DISPLAY "C or below"` | `if (score >= 90) {`<br/>`    System.out.println("A");`<br/>`} else if (score >= 80) {`<br/>`    System.out.println("B");`<br/>`} else {`<br/>`    System.out.println("C or below");`<br/>`}` |
| **For Loop** | `FOR i ← 1 TO 10`<br/>`    DISPLAY i` | `for (int i = 1; i <= 10; i++) {`<br/>`    System.out.println(i);`<br/>`}` |
| **While Loop** | `REPEAT UNTIL guess = secret`<br/>`    guess ← INPUT()` | `while (guess != secret) {`<br/>`    guess = input.nextInt();`<br/>`}` |
| **Lists (ArrayList)** | `numbers ← [2, 4, 6]`<br/>`APPEND 8 TO numbers`<br/>`REMOVE numbers[1]`<br/>`x ← LENGTH(numbers)` | `ArrayList<Integer> numbers = new ArrayList<>();`<br/>`numbers.add(2);`<br/>`numbers.add(4);`<br/>`numbers.add(6);`<br/>`numbers.add(8); // APPEND`<br/>`numbers.remove(1); // REMOVE`<br/>`int x = numbers.size(); // LENGTH` |
| **Traversal (For Each)** | `FOR EACH num IN numbers`<br/>`    DISPLAY num` | `for (int num : numbers) {`<br/>`    System.out.println(num);`<br/>`}` |
| **Traversal (Index)** | `FOR i ← 0 TO LENGTH(numbers)-1`<br/>`    DISPLAY numbers[i]` | `for (int i = 0; i < numbers.size(); i++) {`<br/>`    System.out.println(numbers.get(i));`<br/>`}` |
| **Procedure (Void)** | `PROCEDURE greet(name)`<br/>`    DISPLAY "Hello " + name` | `public static void greet(String name) {`<br/>`    System.out.println("Hello " + name);`<br/>`}` |
| **Procedure (Return)** | `PROCEDURE square(num)`<br/>`    RETURN num * num` | `public static int square(int num) {`<br/>`    return num * num;`<br/>`}` |
| **Procedure (Boolean)** | `PROCEDURE isEven(num)`<br/>`    IF num MOD 2 = 0`<br/>`        RETURN true`<br/>`    ELSE`<br/>`        RETURN false` | `public static boolean isEven(int num) {`<br/>`    if (num % 2 == 0) {`<br/>`        return true;`<br/>`    } else {`<br/>`        return false;`<br/>`    }`<br/>`}` |

---

### Variables and Datatypes:

**Structure of a variable**
```java
//Datatype variableName = value;
//= is the assingment opperator, spoken as "gets"
String name = "Daniela";
int grade = 10;
double gpa = 3.5;
char initial = 'D';
boolean isOn = false;
```

**Primitive Datatype**
Is a value that takes no more than 1 byte
Examples; int, char, boolean, double

**Pointer Datatype**
Object Datatype, they are too big for 1 byte, so instead of storing tha data, it stores a pointer, which points to the memory location of the data
Examples: String, ArrayList, and objects created from a class

**Senicolon ;**
Is like a period. It's end of your code statement

---

### Conditionals

if(condition)
{
	//do if condition is true
} else if (nextCondition)
{
//do if condition is false but nextCondition is true
} else
{
	//do if all prior conditions are false
}

### Symbols:
> greater than
< less than
≥

word.equals(word2) --> to check if the values of strings are equal

### Functions/Procedures

Base Structure:
```Java
AccessModifier static* returnType functionName(parameter(s) dataType parameter1, dataType parameter2)
{
	//body of function, wrrite code block here
}
Defining the parts of the function:
AccessModifier:
	public: can be accessed outside of the file/class - standard
	private: can only be accssed within the file/class

Static: common, but optional, means that it can



//Example:
```Java
public static void greet(String name)
{
	System.outprintln("Hello, ")
}

