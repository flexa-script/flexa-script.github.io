# Variables and Types

## Types
CP language supports many types, declared or not. The basic variable types are:
- `bool`: boolean values, e.g. `true` and `false`
- `int`: integer values, e.g. `0`, `1`, `99`
- `float`: floating values, e.g. `.0`, `10.75`, `99f`
- `char`: single character value, e.g. `'c'`, `'A'`
- `string`: string values, e.g. `"Hello world!"`
CP already has complex types, like:
- Types can be arrays, e.g. `{"Hi", ",", "there"}`, `{{0, 0, 0}, {0, 0, 0}, {0, 0, 0}}`
- We can have struct values, e.g. `Foo{bar=0}`)
- And functions, e.g. `() { print("Hello, world!"); }`

## Variables
To declare a variable, you can do it starting a statement with `var`, there are some examples:
```cp
var str: string[10];
var i: int[3][3];
struct Foo { var bar: int; };
var fun: function = () { print("Hello, world!"); };
```


## Usage
You can add libs just in the start of file, after the first statement<sup>1</sup>, you can't add mor libs.
Example:
```cp

```
Where mylib and bar are the .cp files, and foo is the containing folder of bar lib, so in the system explorer, it will be like './foo/bar.cp'.


<sup>1</sup> Statements are the program commands. Eg. `print("foo");`.
