# catr

---

## rust cat using CLI

The CLI app that mimics echo, but written in rust

You have the option -n to omit newline, To use in bash enter:

```terminal
cargo build --release
target/release/catr <filename>
```

or with cargo

To export output to file:

```terminal
cargo run -- -n hello world > file.txt
```

---

## Tools Used

- VS Code
- Rust
- clap
- assert_cmd
- predicates
- rand

---

## Recent Updates

- Created 2022-03-20

---

## Getting Started

Clone this repository to your local machine.

```terminal
git clone https://github.com/will-ing/catr.git
```

```terminal
cd YourRepo/YourProject
cargo build
cargo run
```

Unit testing is included in the project

```terminal
cargo test
```

---

---

## Change Log

***The change log will list any changes made to the code base.***
1.0 App created

---

## Authors

Will Koger\
April 2022

## References

Rust book\
OReily Command-Line Rust
