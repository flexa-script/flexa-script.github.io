# Libraries

## Clause: using
CP language supports either system libs than custom file libs. It's possible to include a custom developed lib, just adding the lib path after a using clause.

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
