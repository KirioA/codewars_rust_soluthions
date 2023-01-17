# CodeWars Rust Solutions

----

## Sum of angles

Find the total sum of internal angles (in degrees) in an n-sided simple polygon. N will be greater than 2.

----

### **Given code**

```rust 
fn angle(n: u32) -> u32 {
}
```

----

### **Solution**

```rust
fn angle(n: u32) -> u32 {
  return (n - 2) * 180
}
```
----

[Task on CodeWars](https://www.codewars.com/kata/5a03b3f6a1c9040084001765/solutions/rust)
