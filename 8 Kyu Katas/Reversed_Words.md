# CodeWars Rust Solutions

----

## Reversed Words

Complete the solution so that it reverses all of the words within the string passed in.

Words are separated by exactly one space and there are no leading or trailing spaces.

Example(Input --> Output):
```
"The greatest victory is that which requires no battle" --> "battle no requires which that is victory greatest The"
```
----

### **Given code**

```rust 
fn reverse_words(words: &str) -> String {
}
```

----

### **Solution**

```rust
fn reverse_words(str: &str) -> String {
   return str.split_whitespace()
        .rev()
        .collect::<Vec<_>>()
        .join(" ");
}
```
----

[Task on CodeWars](https://www.codewars.com/kata/51c8991dee245d7ddf00000e/solutions/rust)
