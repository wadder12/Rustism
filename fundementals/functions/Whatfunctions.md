## Functions

Functions are a fundamental concept in programming that allow you to encapsulate a program's functionality. They can optionally accept data as input and optionally return data as output. Functions are commonly used for code organization and can make code easier to read.

Benefits of using functions:
- Encapsulation of program functionality
- Improved code organization
- Enhanced code readability

By using functions effectively, you can greatly improve the quality and maintainability of your code.

anatmoy of a function

```rust
fn add (a: i32, b: i32) -> i32 {
    a + b
}
```

``fn`` - begins a new function

``add`` - name of the function (can be anything as long as it doesnt start with number or start with a keyword)

``(a: i32, b: i32)`` - function parameters (dictate what type of data this function works with ) 

``a: & b: - are the variables within in the function`` || ``i32 - type of parameter of the fucntion (can be any type) 32 bit interger``

``-> i32`` - return type (to return data we use ``->`` && then we request what type of data we want to return - we want 32 bit)

## we have the function body (down below)

```rust
            {
    a + b
}
```
