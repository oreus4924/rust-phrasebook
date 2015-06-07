####helloworld.rs
```rust
fn main() { 
// Define the main function
    println!("Hello world!"); 
    // Invoke the println macro with the static string "Hello world!"
}
// End the main function
```

####variablebindings.rs
```rust
fn main() {
// Define the main function
    let x = 5;
    // State that x is a binding with the value five (the type is inferred to be i32)
    
    let (y, z) = (1, 2);
    // State that the tuple (y, z) is bound to the other tuple (1, 2) so y is a binding with the value one and z is a binding with the value 2 
    // (the type is inferred to be (i32, i32)
    
    let w: i32 = 5;
    // State that w is a binding with the type i32 and the value five
    
    let mut v = 8;
    // State that v is a mutable binding with the value eight
    v = 13;
    // the mutable binding v now has the value thirteen
}
```
