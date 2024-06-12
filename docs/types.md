# Built-in Types

CP supports many types, declared or infered. The basic variable types are:
- `bool`: boolean values, e.g. `true` and `false`
- `int`: integer values, e.g. `0`, `1`, `99`
- `float`: floating values, e.g. `.0`, `10.75`, `99f`
- `char`: single character value, e.g. `'c'`, `'A'`
- `string`: string values, e.g. `"Hello world!"`

CP already has support to arrays, structs and functions:
- Types can be arrays, e.g. `{"Hi", ",", "there"}`, `{{0, 0, 0}, {0, 0, 0}, {0, 0, 0}}`
- We can have struct values, e.g. `Foo{bar=0}`
- And functions, e.g. `() { print("Hello, world!"); }`

## Usage
It is possible to use types instantianting variables, converting values, returning from functions and so on. Example:
```cp
// basic types
var b: bool;
var i: int;
var f: float;
var c: char;
var s: string;

// arrays
var sarr: string[10];
var iarr: int[3][3];

// structs
struct Foo {
    var bar: string;
    var baz: int;
    var qux: float;
};
var str: Foo = Foo{bar="bar", baz=10, qux=5f};

// functions
var fun: function = () { print("Hello, world!"); };
fun();

```

We can infer types simply using `any` or not declaring a type:
```cp
// any value
var a: any;

// not declared any value
var b;
```

See next: [Variables](/variables.md)
