# wasm3-ESP8266-rust

## Setup
0.1. cargo new testing --bin
0.2. rustup target add wasm32-wasi
0.3. cargo run 
    
## Build
1. cargo build --release --target wasm32-wasi
2. wasm3 ./target/wasm32-wasi/release/testing.wasm


## Links
https://github.com/wasm3/wasm3/blob/main/docs/Cookbook.md
https://docs.wasmer.io/
https://aur.archlinux.org/packages/wasm3/
https://archlinux.org/packages/community/x86_64/rustup/
https://webassembly.sh/

