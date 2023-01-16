# CodeWars Rust Solutions

----

## Simple_multiplication

This kata is about multiplying a given number by eight if it is an even number and by nine otherwise.


----

### **Given code**

```rust 
fn simple_multiplication(number: u8) -> u8 {
}
```

----

### **Solution**

```rust
fn simple_multiplication(number: u8) -> u8 {
    if number % 2 == 0 { number * 8 } else { number * 9 }
}
```
----

[Task on CodeWars](https://www.codewars.com/kata/583710ccaa6717322c000105/solutions/rust)
