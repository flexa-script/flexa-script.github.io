# Data Structures

Data structures allow you to organize and store data efficiently. Flexa provides built-in support for arrays and structs, which are essential for managing collections of data and creating custom types. In this section, we'll explore how to use these data structures effectively.

---

## Arrays

Arrays are collections of elements of the same type. They are useful for storing and manipulating sequences of data.

### Declaring Arrays
Arrays are declared using the following syntax:

```flexa
var array_name: type[] = {element1, element2, ...};
```

- `array_name`: The name of the array.
- `type`: The type of elements in the array.
- `element1`, `element2`, ...: The initial elements of the array.

#### Example
```flexa
var numbers: int[] = {1, 2, 3, 4, 5};
var names: string[] = {"Alice", "Bob", "Charlie"};
```

### Accessing Array Elements
Array elements are accessed using their index (starting from 0).

```flexa
var first_number = numbers[0]; // first_number = 1
var second_name = names[1];    // second_name = "Bob"
```

### Modifying Array Elements
You can modify array elements by assigning new values to specific indices.

```flexa
numbers[0] = 10; // numbers = {10, 2, 3, 4, 5}
```

### Array Length
The length of an array can be obtained using the `len` function.

```flexa
var count = len(numbers); // count = 5
```

### Iterating Over Arrays
You can use a `foreach` loop to iterate over the elements of an array.

```flexa
foreach (var num in numbers) {
  println("Number: " + num);
}
```

---

## Structs

Structs are user-defined types that group related data together. They are useful for creating complex data structures.

### Declaring Structs
Structs are declared using the `struct` keyword, followed by the struct name and a block of fields.

```flexa
struct StructName {
  var field1: type;
  var field2: type;
  ...
}
```

- `StructName`: The name of the struct.
- `field1`, `field2`, ...: The fields (variables) of the struct.

#### Example
```flexa
struct Person {
  var name: string;
  var age: int;
}
```

### Creating Struct Instances
You can create instances of a struct using the struct name followed by a block of field assignments.

```flexa
var person: Person = Person{name="Alice", age=30};
```

### Accessing Struct Fields
Struct fields are accessed using the dot (`.`) operator.

```flexa
println(person.name); // Prints "Alice"
println(person.age);  // Prints 30
```

### Modifying Struct Fields
You can modify struct fields by assigning new values.

```flexa
person.age = 31; // person.age is now 31
```

### Nested Structs
Structs can contain other structs as fields.

```flexa
struct Address {
  var street: string;
  var city: string;
}

struct Employee {
  var name: string;
  var address: Address;
}

var employee: Employee = Employee{
  name="Bob",
  address=Address{street="123 Main St", city="Springfield"}
}
```

---

## Array of Structs

You can create arrays of structs to manage collections of complex data.

```flexa
var people: Person[] = {
  Person{name="Alice", age=30},
  Person{name="Bob", age=25},
  Person{name="Charlie", age=35}
};

foreach (var person in people) {
  println(person.name + " is " + person.age + " years old.");
}
```

---

## What's Next?

Now that you understand how to work with arrays and structs, it's time to learn about **error handling** in Flexa. Head over to the [Error Handling](error-handling) section to dive deeper.

---

[← Back to Functions](functions) | [Next: Error Handling →](error-handling)
