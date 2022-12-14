# Replicate Any File With Rust

This repo is about replicating a file with Rust and cargo package manager. It is not my code! I am just testing and adding additional functions.

## Installation

You have to install cargo and rustup first:
```bash
# to install rustup and setting up enviroment in linux OS
curl https://sh.rustup.rs -sSf | sh
source "$HOME/.cargo/env” 
```
```bash
# to install cargo package manager
git clone https://github.com/rust-lang/cargo
cd cargo
cargo build --release
```

## Usage

```bash
# compile
cargo build

# an example of how to run
# it gets 4 arguments so the 3rd and 4th arg should be
# the existing file and the filename you want to create
cargo run "find" "replace" Cargo.toml CopyOfCargoFile.toml
```