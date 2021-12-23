# Chapter 3

## Variable

A Rust variable is immutable by default.
To make it mutable, is needed to add the `mut` statement
before the variable's name.

```rust
// example:
let mut variable = 0;
```

## Constants

Constants are always immutable.
Types on constants always must be annotated.
Constants can be declared in any scope.
Constants may be set only to a constant expression, not the result of a value that could only be computed at runtime.
Keyword: `const`.

```rust
// example
const THREE_HOURS_IN_SECONDS: u32 = 60 * 60 * 3;
```

## WIP

Continue on shadowing.
