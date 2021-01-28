{{ include /processed/fragments/_header.html }}

Wasmin is a minimalistic programming language that compiles to [WASM](https://developer.mozilla.org/en-US/docs/WebAssembly).

It has a very **simple syntax** and **compiles extremely fast** to clean and lightweight WASM.

Its other main characteristics are the support for **concatenative style** programming and the total lack of a runtime or a
garbage collector.

This is what Wasmin code looks like:

```rust
def factorial [i32] i32;
pub fun factorial n = if n, le_s 2;
    n;
    n, mul factorial(n, sub 1);
```

## Features

* foo
* bar

{{ include /processed/fragments/_footer.html }}