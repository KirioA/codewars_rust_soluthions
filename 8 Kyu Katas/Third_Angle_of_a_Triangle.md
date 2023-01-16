# CodeWars Rust Solutions

----

## Third Angle of a Triangle

You are given two angles (in degrees) of a triangle.

Write a function to return the 3rd.

Note: only positive integers will be tested.

----

### **Given code**

```rust 
fn other_angle(a: u32, b: u32) -> u32 {
}
```

----

### **Solution**

```rust
fn other_angle(a: u32, b: u32) -> u32 {
    180 - a - b
}
```
----

[Task on CodeWars](https://www.codewars.com/kata/5a023c426975981341000014/solutions/rust)
