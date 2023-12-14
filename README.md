# CP Language
CP is a beginner-friendly programming language designed to be easy to learn and understand. It's perfect for those new to programming and looking to build a solid foundation in coding concepts. While not recommended for experienced developers seeking advanced features, CP Language offers a straightforward and minimalistic syntax for learing and study purposes.

## Features
- **Simplicity:** CP focuses on simplicity, making it an ideal language for beginners to grasp the basics of programming.
- **Readability:** The language prioritizes human readability, aiming to provide a clear and straightforward code structure.

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
./cp  hello.cp
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
