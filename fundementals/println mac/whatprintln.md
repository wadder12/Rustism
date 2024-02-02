
## println macro

The `println` macro in Rust is used to display information to the terminal. It is particularly useful for debugging purposes. 

Macros in Rust expand into additional code, allowing for more flexibility and convenience. 

Here is an example of using the `println` macro:


```rust
let life = 42; 

println!("hello");

println!("{:?}", life);

println!("{:?} {:?}", life, life);

println!("the meaning is {:?}", life);
```

## use can also use 

```rust
let life = 42; 

println!("{life:?}"); //- :? begug version

println!("{life}"); //- end user display version
```