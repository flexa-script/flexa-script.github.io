# Language Reference

This section provides a comprehensive reference for the Flexa programming language. It covers the syntax, rules, and features of Flexa in a concise and organized manner. Use this guide as a quick reference while writing Flexa code.

---

## Table of Contents

1. [Program Structure](#program-structure)
2. [Variables and Constants](#variables-and-constants)
3. [Data Types](#data-types)
4. [Operators](#operators)
5. [Control Structures](#control-structures)
6. [Functions](#functions)
7. [Structs](#structs)
8. [Arrays](#arrays)
9. [Error Handling](#error-handling)
10. [Built-in Functions](#built-in-functions)
11. [Built-in Libraries](#built-in-libraries)

---

## Program Structure

A Flexa program consists of:
- **Namespace declaration** (optional)
- **Library imports** (optional)
- **Namespace includes/excludes** (optional)
- **Function and variable declarations**
- **Executable code**

### Example
```flexa
namespace my_program;

using flx.core.console;

include namespace flx;

fun main() {
  println("Hello, Flexa!");
}

main();
```

---

## Variables and Constants

### Variables
```flexa
var name: type = value;
```
- Example: `var age: int = 25;`

### Constants
```flexa
const name: type = value;
```
- Example: `const PI: float = 3.14;`

---

## Data Types

### Primitive Types
- `bool`: `true` or `false`
- `int`: Integer numbers (e.g., `42`)
- `float`: Floating-point numbers (e.g., `3.14`)
- `char`: Single character (e.g., `'a'`)
- `string`: Sequence of characters (e.g., `"Hello"`)

### Composite Types
- **Arrays**: `int[]`, `string[]`, etc.
- **Structs**: User-defined types.

### Special Types
- `function`: Represents a function or lambda.
- `void`: Represents the absence of a value.
- `any`: Represents a value of any type.

---

## Operators

### Value Reference Operators
- `ref`, `unref`

### Increment Operators
- `++`, `--`

### Ternary Operator
- `expression ? if_true_expression : if_false_expression`

### Arithmetic Operators
- `+`, `-`, `*`, `/`, `%`, `**` (exponentiation), `/%` (floor division)

### Comparison Operators
- `==`, `!=`, `<`, `>`, `<=`, `>=`, `<=>` (three-way)

### Logical Operators
- `and`, `or`, `not`

### Bitwise Operators
- `&`, `|`, `^`, `~`, `<<`, `>>`

### Assignment Operators
- `=`, `+=`, `-=`, `*=`, `/=`, `%=`, `**=`, `&=`, `|=`, `^=`, `<<=`, `>>=`

---

## Control Structures

### Conditionals
- `if`, `else`, `else if`, `switch`

### Loops
- `while`, `do-while`, `for`, `foreach`

### Flow Control
- `break`, `continue`, `return`, `exit`

---

## Functions

### Function Declaration
```flexa
fun name(parameter: type, ...): return_type {
  // Function body
}
```

### Lambda Functions
```flexa
var lambda: function = fun (parameter: type, ...): return_type {
  // Function body
};
```

---

## Structs

### Struct Declaration
```flexa
struct Name {
  var field1: type;
  var field2: type;
}
```

### Struct Instance
```flexa
var instance: Name = Name{field1=value1, field2=value2};
```

---

## Arrays

### Array Declaration
```flexa
var array[]: type = {value1, value2, ...};
```

### Array Access
```flexa
var element = array[index];
```

---

## Error Handling

### Try-Catch
```flexa
try {
  // Code that may throw an exception
} catch (var error) {
  // Handle the exception
}
```

### Throw
```flexa
throw string_expression;
// or
throw Exception{error=string_expression};
```

---

## Built-in Functions

- `print(optional_message)`: Prints a message to the console.
- `println(optional_message)`: Prints a message to the console with a newline.
- `read(optional_message)`: Reads a line of input from the console.
- `readch()`: Reads a single character from the console.
- `len(value)`: Returns the length of a string or array.
- `sleep(milliseconds)`: Pauses the program for a specified time.
- `system(command)`: Executes a system command.

---

## Built-in Libraries

Flexa provides a rich set of built-in libraries for tasks like file handling, networking, and data manipulation. Some of the key libraries include:
- `flx.core.console`: Console input/output.
- `flx.core.files`: File operations.
- `flx.core.HTTP`: HTTP communication.
- `flx.std.math`: Mathematical functions.
- `flx.std.strings`: String manipulation.

---

## What's Next?

If you have questions or run into issues while using Flexa, check out the [FAQ and Common Issues](faq-and-common-issues) section for solutions and tips.

---

[← Back to Advanced Examples](advanced-examples) | [Next: FAQ and Common Issues →](faq-and-common-issues)
