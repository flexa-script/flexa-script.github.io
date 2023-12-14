# Variables and Types

## Types
CP language supports many types, declared or not. The variable types are:
- `bool`: boolean values (`true` and `false`)
- `int`: integer values (`0`, `1`, `99`)
- `float`: floating values (`.0`, `10.75`, `99f`)
- `char`: single character value (`'c'`, `'A'`)
- `string`: string values (`"Hello world!"`)

## Variables
To declare a variable, you can do it 


## Usage
You can add libs just in the start of file, after the first statement<sup>1</sup>, you can't add mor libs.
Example:
```cp
using mylib;
using foo.bar;

// program statements
```
Where mylib and bar are the .cp files, and foo is the containing folder of bar lib, so in the system explorer, it will be like './foo/bar.cp'.


<sup>1</sup> Statements are the program commands. Eg. `print("foo");`.
