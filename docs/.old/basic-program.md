# Getting Started

## Hello, World!
Here's a classic "Hello, World!" program in CP:

```cp
print("Hello, World!");
```

Save this code in a file with a `.cp` extension, for example, `hello.cp`. Then, run it using the CP interpreter:

```bash
./cp  hello.cp
```

You should see the output:

```
Hello, World!
```

## Variables

Declare a variable using the `var` keyword:

```cp
var message = "Hello, CP!";
print(message);
```

## Control Flow

CP supports some control flow structures, for example, the classic if-else statement:

```cp
var number = 42;

if (number > 50) {
    print("Greater than 50");
} else {
    print("Less than or equal to 50");
}
```

## Loops

The statement `while` is a possible loop for repetitive tasks:
```cp
var count = 0;

while (count < 5) {
    print(count);
    count = count + 1;
}
```

See next: [Types](/types.md)
