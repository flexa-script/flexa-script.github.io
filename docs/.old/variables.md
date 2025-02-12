# Variables
Variables can store values of many types.

## Usage
To declare a variable, you can do it starting a statement with `var`, there are some examples:

```cp
// we can declare values without initialize
var b: bool;
var i: int;
var f: float;

// or initializing
var c: char = 'C';
var s: string = "Hi, there";

// if a variable isn't initialized, it can't be used
var str: Foo;
print(str); // will generate an error

```

### Arrays

- Arrays always must respect the defined dimension, you can't assign and `int[3]` with `int[3][3]`.
- If an array is defined with no size, it can be assigned with any size of array.
- It is possible initialize array size with non-constant values

```cp
// initialize arrays
var iarr: int[3][3] = `{% raw %}{{0, 0, 0}, {0, 0, 0}, {0, 0, 0}}{% endraw %}`;

// or just initialize as null
var sarr: string[10] = null;
```

### Any

Any value can be initialized with any type of value.
```cp
var a: any = false;
// and it's not necessary to declare any
var b = 'b';
// and it's possible to assign with any other value
b = 7;
```
Altought, if we define a variable with a type, it can't be assigned with other value than the defined.

See next: [Functions](/functions.md)
