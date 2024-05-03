# CP Language
CP is a toy programming language that draws inspiration from languages as C, Python, C#, and JavaScript.

## Features
- **Readable Syntax:** Inspired by Python, CP boasts a clean and easily understandable syntax.
- **Dynamic Typing:** Following the footsteps of Python and JavaScript, CP employs dynamic typing, enabling flexible variable declaration and manipulation without the need for explicit type annotations.
- **Built-in Libraries:** With a rich set of built-in libraries and modules, CP provides powerful tools for tasks such as file I/O, networking, and mathematical operations, reducing the need for external dependencies.

## Getting Started

### Installation
To use CP, follow these steps:
1. Download the release interpreter
2. Navigate to the CP directory
3. Run the CP interpreter: `./cp main.cp`

### Hello, World!
Here's a classic "Hello, World!" program in CP:

```cp
print("Hello, World!");
```

Save this code in a file with a `.cp` extension, for example, `hello.cp`. Then, run it using the CP interpreter:

```bash
$ ./cp  hello.cp
```

You should see the output:

```
Hello, World!
```

## Language Basics

### Variables

Declare a variable using the `var` keyword:

```cp
var message = "Hello, CP!";
print(message);
```

### Control Flow

CP supports basic control flow structures:

```cp
var number = 42;

if (number > 50) {
    print("Greater than 50");
} else {
    print("Less than or equal to 50");
}
```

### Loops

Use the `while` loop for repetitive tasks:

```cp
var count = 0;

while (count < 5) {
    print(count);
    count = count + 1;
}
```

For more detailed information and examples, check out the [documentation](docs).

## Contributing

Contributions to CP are welcome! Whether you find a bug, have a feature request, or want to contribute code, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Happy coding with CP! 🚀
