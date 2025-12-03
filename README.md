# Grepik

Simple version of `grep` written in rust just for learning purposes.

## Installation

### Prerequisites

- Rust toolchain

### Building from source code

Clone the repository and open the folder:
```bash
git clone git@github.com:vojt444/grepik.git
cd grepik
```

Build the application: 
```bash
cargo build --release
```
The binary is available at `target/release/grepik`

## Usage
### Command structure

```bash
grepik [STRING_TO_SEARCH] [FILE_WHERE_TO_SEARCH]
```

### Case sensitivity
Set `IGNORE_CASE` environment variable to any number to make the searching case insensitive.

Example: 
```bash
grepik Paris ./who.txt
```