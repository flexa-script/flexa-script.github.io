# Control Flows

There are some ways to control flows in a CP program, like if, switch etc.

## Usage

### `if` statement
The if statement let it to check multiple expressions, once a spression evaluates true, it's block is executed and prevent the others from execution.
```cp
var lv = read("type a value: ");
var rv = read("type another value: ");
if (lv > rv) {
    print("first value is greater than second value");
} else if (lv == rv) {
    print("both values are equal");
} else {
    print("second value is greater than first value");
}
```

### Ternary if statement
Ternary if can be used in expressions and can perfrom a if-else verification.
```cp
var val = read("type a value: ");
print(int(val) == 10 ? "is equal" : "is not equal");
```

### `switch` statement
Switch statement perform a jump to matched case, executing it's block until it find a break statement, even if the block is in next cases. Default will execute if none of the case was matched. The values of case must be a constant value, variable or literal.
```cp
switch (val) {
case 0:
    print("val is 0");
    break;
case 1:
case 2:
    print("val is 1 or 2");
    break;
case 3: // if it enter in this case, it will execute the next case too
    print("val is 3");
case 4:
    print("val can be 4");
    break;
default:
    print("val is greater than 4");
}
```

See next: [Bar](/bar.md)
