# Rusty React

create Rust app with `argo init --lib .`

`wasm-bindgen` transpiles to WASM

Rust target: `wasm32-unknown-unknown`
Use with build script: `cargo build --target wasm32-unknown-unknown`

dump JS wrapped WSAM code in build dir:
`wasm-bindgen target/wasm32-unknown-unknown/debug/rusty_react.wasm --out-dir build`
