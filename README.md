# CP Language
CP is a beginner-friendly programming language designed to be easy to learn and understand. It's perfect for those new to programming and looking to build a solid foundation in coding concepts. While not recommended for experienced developers seeking advanced features, CP Language offers a straightforward and minimalistic syntax for educational purposes.

## Features
- **Simplicity:** SimpleLang focuses on simplicity, making it an ideal language for beginners to grasp the basics of programming.
- **Readability:** The language prioritizes human readability, aiming to provide a clear and straightforward code structure.
- **Education:** SimpleLang is specifically designed for educational purposes, serving as a stepping stone for those new to programming.

## Getting Started

### Installation
To use SimpleLang, follow these steps:
1. Clone the repository: `git clone https://github.com/your-username/SimpleLang.git`
2. Navigate to the SimpleLang directory: `cd SimpleLang`
3. Run the SimpleLang interpreter: `python simplelang.py`

### Hello, World!
Here's a classic "Hello, World!" program in SimpleLang:

```cp
print("Hello, World!");
```

Save this code in a file with a `.sl` extension, for example, `hello.sl`. Then, run it using the SimpleLang interpreter:

```bash
python simplelang.py hello.sl
```

You should see the output:

```
Hello, World!
```

## Language Basics

### Variables

Declare a variable using the `var` keyword:

```simplelang
var message = "Hello, SimpleLang!"
print(message)
```

### Control Flow

SimpleLang supports basic control flow structures:

```simplelang
var number = 42

if number > 50 {
    print("Greater than 50")
} else {
    print("Less than or equal to 50")
}
```

### Loops

Use the `while` loop for repetitive tasks:

```simplelang
var count = 0

while count < 5 {
    print(count)
    count = count + 1
}
```

For more detailed information and examples, check out the [documentation](docs/).

## Contributing

Contributions to SimpleLang are welcome! Whether you find a bug, have a feature request, or want to contribute code, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Happy coding with SimpleLang! 🚀
