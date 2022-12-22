## Comments

Programmers leave *comments* in their source code that the compiler will ignore 
but people reading the source code may find useful.

Here’s a simple comment:

```rust
// hello, world
```

Single comments start with two slashes, continuing until the end of the line. Example:

```rust
// So we’re doing something complicated here, long enough that we need
// multiple lines of comments to do it! Whew! Hopefully, this comment will
// explain what’s going on.
```

Comments can also be placed at the end of lines containing code:

<span class="filename">Filename: src/main.rs</span>

```rust
{{#rustdoc_include ../listings/ch03-common-programming-concepts/no-listing-24-comments-end-of-line/src/main.rs}}
```

More commonly used in this format, with the comment on a
separate line above the code it’s annotating:

<span class="filename">Filename: src/main.rs</span>

```rust
{{#rustdoc_include ../listings/ch03-common-programming-concepts/no-listing-25-comments-above-line/src/main.rs}}
```

Rust also has documentation comments, which we’ll
discuss in the [“Publishing a Crate to Crates.io”][publishing]<!-- ignore -->
section of Chapter 14.

[publishing]: ch14-02-publishing-to-crates-io.html
