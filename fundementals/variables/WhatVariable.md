## What is a variable?

A variable is a temporary memory location that holds data. It allows programmers to work with memory easily.

- Variables can be set to any value and type.
- By default, variables are immutable, meaning they cannot be changed.
- However, variables can also be made mutable, allowing them to be changed.

In summary:
- Immutable variables: Cannot be changed.
- Mutable variables: Can be changed.

```rust
fn main() {
    let x = 5; // Immutable variable
    let mut y = 10; // Mutable variable

    println!("x: {}", x);
    println!("y: {}", y);

    y = 15; // Changing the value of y

    println!("Updated y: {}", y);
}
```

more examples: ``let`` creates variables in rust

```rust
let two = 2;

let hello = "hello";

let j = "j"

let my_half = 0.5;

let mut my_name = "bill";

let quit_program = false;

let your_half = my_half;
```