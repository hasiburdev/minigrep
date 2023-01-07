# Minigrep

A minimal version of the command line program `grep`.

#### `grep` is a program that is used for finding texts and patterns in files.

Features:

- Search texts from files.
- Search texts with case insensitive mode.
- Shows appropriate errors if fails.

To build this program, you need to have rust compiler (`rustc`) and rust dependency manager (`cargo`) installed in your computer. use the following command -

```bash
git clone https://github.com/hasiburdev/minigrep.git
cd minigrep
cargo build --release
```

The binary file will be generated at `/target/release/minigrep`.
