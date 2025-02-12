# Functions
Functions can define scoped statements, being possible receive parameter and return values.

## Usage

### A simple method
Functions can be defined using `def` keyword:
```cp
def foo() {
    print("bar");
}
```

### Receiving parameters
There are some ways to pass parameters:
```cp
// we can ommit variable type
def foo(a, b) {}

// or explicit set it
def foo(a: int, b: string) {}
```
And it is possible to define same name functions with different parameters.

### Returning
It's also possible to ommit return type:
```cp
// like
def foo() {
    return true;
}

// or explicit set it
def foo(): string {
    return "bar";
}
```


See next: [Foo](/bar)
