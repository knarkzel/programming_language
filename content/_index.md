+++
title = "Writing a Programming Language in Rust"
+++

## Writing a Programming Language in Rust

Welcome! In this blog series we'll be creating a programming language from scratch in the Rust programming language. Each
post is a small tutorial and includes all the needed code, so you can follow along if you like. The source code is also available
in the corresponding Github repository.

We'll be creating a language which looks like this (blend of C, Go and Rust):

```
fn sum(numbers []int) int {
    total = 0
    for number in numbers {
        acc += number
    }
    return total
}

fn main() {
    numbers = [1, 2, 3, 4, 5]
    total = sum(numbers)
    print("Total is {total}")
}
```

Some basic features with this language:

- Statically typed
- Simplicity is key
- Less lines of code to accomplish same thing is better
- Type inference (no need to specify types where it can be inferred!)
