# CodeWars Rust Solutions

----

## Sum of odd numbers

Given the triangle of consecutive odd numbers:
```
             1
          3     5
       7     9    11
   13    15    17    19
21    23    25    27    29
```
Calculate the sum of the numbers in the nth row of this triangle (starting at index 1) e.g.: (Input --> Output)
```
1 -->  1
2 --> 3 + 5 = 8 
```
----

### **Given code**

```rust 
fn row_sum_odd_numbers(n:i64) -> i64 {
}
```

----

### **Solution**

```rust
fn row_sum_odd_numbers(n:i64) -> i64 {
    let mut sum = 0;
    let start = (n * n) - (n - 1);
    let end = start + n * 2;

    for n in start..end {
        if !(n % 2 == 0) {
            sum += n;
        }
    }
    return sum
}
```
----

[Task on CodeWars](https://www.codewars.com/kata/55fd2d567d94ac3bc9000064/solutions/rust)
